# A-program-to-reverse-a-string-Python

The user will input a word

Create a function that will reverse the string.

Display the original word, the reversed word in all caps and string count.

----------------------------------------------------------------------------------

def reverse(word):

    b = " "

    for a in word:
    
        b = a + b
        
    return b

user = input("enter a word: ")

print("\nINPUT: " + str(user))

print("OUTPUT: " + reverse(user) + "(" + str(len(user)) + " characters" + ")")
