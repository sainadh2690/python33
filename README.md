''' program to determine the character entered by a user , whether it is an alphabet, digit or space by using seperate if condition and predefined string functions'''
char= input("Press any key:")
if char.isalpha():
    print("The user has entered character")
if char.isdigit():
    print("The user has entered digit")
if char.isspace():
    print("The user has entered space")
