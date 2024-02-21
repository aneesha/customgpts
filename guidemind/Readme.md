# Guide Mind Any Subject Tutor

The aim of this prompt was to try to make a tutor with pedagogical moves only using zero or few shot examples and then to try and get ChatGPT to self-adapt the examples to any domain. 

The Pedagogical moves are taken from the MathDial paper presented at EMNLP 2023 (Macina et al., 2023). 

| Category  | Intent                      | Example                                      |
|-----------|-----------------------------|----------------------------------------------|
| Focus     | Seek Strategy               | So what should you do next?                  |
| Focus     | Guiding Student Focus       | Can you calculate ... ?                      |
| Focus     | Recall Relevant Information | Can you reread the question and tell me what is ... ? |
| Probing   | Asking for Explanation      | Why do you think you need to add these numbers? |
| Probing   | Seeking Self Correction     | Are you sure you need to add here?           |
| Probing   | Perturbing the Question     | How would things change if they had ... items instead? |
| Probing   | Seeking World Knowledge     | How do you calculate the perimeter of a square? |
| Telling   | Revealing Strategy          | You need to add ... to ... to get your answer. |
| Telling   | Revealing Answer            | No, he had ... items.                        |
| Generic   | Greeting/Fairwell           | Hi ..., how are you doing with the word problem? |
| Generic   | Greeting/Fairwell           | Good Job! Is there anything else I can help with? |
| Generic   | General inquiry             | Can you go walk me through your solution?    |

## Features
- A chatbot tutor that uses pedagogical moves (i.e does not just give a direct answer)
- Can tutor for any subject

## Enabled Capabilities
- Web Browsing
- DALL-E Image Generation
- Code Interpreter

## Citing this Prompt
If you re-use in an academic publication please cite as:

Bakharia, A. (2024). Custom GPT Prompts - Guide Mind Any Subject Tutor. GitHub. https://github.com/aneesha/customgpts


## References

Macina, J., Daheim, N., Chowdhury, S. P., Sinha, T., Kapur, M., Gurevych, I., & Sachan, M. (2023). MathDial: A Dialogue Tutoring Dataset with Rich Pedagogical Properties Grounded in Math Reasoning Problems. arXiv preprint arXiv:2305.14536.
