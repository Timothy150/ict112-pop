# ict112-pop
Introduction to programming in Python
# Solutions to Assignment 3
# Index Number: 5240100255

# 1. Reverse the string "Programming"
original = "Programming"
reversed_str = original[::-1]
print("Reversed string:", reversed_str)

# 2. Print initials in uppercase from full name
full_name = input("Enter your full name: ")
initials = ".".join([name[0].upper() for name in full_name.strip().split()]) + "."
print("Initials:", initials)

# 3. Check if a string is a palindrome
word = input("Enter a word to check for palindrome: ")
if word == word[::-1]:
    print(f"'{word}' is a palindrome.")
else:
    print(f"'{word}' is not a palindrome.")

# 4. Count number of words in a sentence
sentence = input("Enter a sentence: ")
words = sentence.split()
print("Number of words:", len(words))

# 5. Replace all "is" with "was"
text = "This is a string and it is an example."
modified_text = text.replace("is", "was")
print("Modified string:", modified_text)
