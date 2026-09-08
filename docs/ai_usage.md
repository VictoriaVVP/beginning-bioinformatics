# AI Use Log
- Tool/model & version: Gemini is the only LLM that was used. 
- What I asked for: I asked Gemini to modify my code and the lecture code in order to complete Rosalind questions. 
- Snippet of prompt(s):
- 
-   Problem 3: "
a  = int(input("Please enter the first number:"))
b = int(input("Please enter the second number:"))

start_num = min(a, b)
end_num = max(a, b)

sum_of_odd_numbers = 0

THIS FOR LOOP IS WRONG BECAUSE IT DID NOT INCLUDE A AND B
for number in range(start_num + 1, end_num):
  if number % 2 != 0:
    sum_of_odd_numbers += number
print(f"The sum of odd numbers is: {sum_of_odd_numbers}")
How is my code not correct?"

- Problem #4: "How do you code to read each line?"

- Problem #5: "
with open("rosalind_ini5 (1).txt","r") as data:

  line=data.read()

for word in line.split():
    print (word)

  Modify this code to keep count the frequency of each word that show up in a string" 

- Problem #8: "What are some useful functions in biopython?" "How do you stop translating RNA in this code?"

_ Problem #9: I copy and pasted the Rosalind question into Gemini and asked it to code for me because I am not familiar with biopython function and library. 

- What I changed before committing: Added code from the Rosalind homework. Within the code, I added comments on what I learned from how Gemini edited my code.
- How I verified correctness (test, sample data): To get the files that I used to test out on my code, I downloaded the submission files from Rosalind and input it in my code to verify correctness. If the answer was wrong, modifications would be made by either me or Gemini. 
