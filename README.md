# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
# Step 1:
Open the text file in read mode.
# Step 2:
Read the content of the file.
# Step 3: 
Split the content into words based on whitespace.
# Step 4:
Count the number of words in the list created.
# Step 5:
Print the total word count.
# Step 6:
Close the file.
## PROGRAM:
```
# Developed By : MALLIGESH M
# Register No : 212223230119
```
```
def count_words_in_file(file_path):
    try:
        with open(file_path, 'r') as text_file:
            file_content = text_file.read()
            word_list = file_content.split()
            return len(word_list)
    except FileNotFoundError:
        print(f"The file {file_path} does not exist.")
        return 0

file_name = 'example.txt' 
word_count = count_words_in_file(file_name)
print(f"Total word count: {word_count}")


```
### OUTPUT:
![image](https://github.com/user-attachments/assets/679fcf6f-b4e8-4498-bdd9-b5d2d7460c2e)




## RESULT:
Thus the program is written to find the word count from a text.
