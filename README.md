# Py-filehandling-lab 
It is time to learn file handling in python!


## Setup:


- Download the string.txt file


## Tasks:


In python do the following: 
- Read from the file and assign it's content to a string
- Take two substrings 
- Take each substring and wirte it into a differnt "part_(number).txt" file 
- Output: part_1.txt, part_2.txt, each one having a different part (substring) of the string

The solution:-

with open('string.txt', 'r') as file:
    content = file.read()

substring_1 = content[:len(content)//2]
substring_2 = content[len(content)//2:]


with open('part_1.txt', 'w') as file:
    file.write(substring_1)

with open('part_2.txt', 'w') as file:
    file.write(substring_2)




## Submission:


- After finishing the task upload your Python script file to the forked repo and then create a pull request.


----------------------------------------------------------------

