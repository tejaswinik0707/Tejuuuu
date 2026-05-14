# Tejuuuu
Assignment 4
a = 2
while a <= 10:
    print(a)
    a = a + 2


    a = 1
sum = 0

while a <= 10:
    sum = sum + a
    a = a + 2

print("Sum =", sum)


a = 0
b = 1

while a <= 50:
    print(a)
    c = a + b
    a = b
    b = c

    text = input("Enter string: ")
result = ""

i = 0
while i < len(text):
    result = result + text[i]
    i = i + 2

print("Result =", result)
