# Assignment-4
# Program to display even numbers from 1 to 10

for i in range(1, 11):
    if i % 2 == 0:
        print(i) 

Out put :
2
4
6
8
10

# Program to display odd numbers from 1 to 10

for i in range(1, 11):
    if i % 2 != 0:
        print(i)

Output:
1
3
5
7
9


# Program to display Fibonacci series between 0 and 50

a = 0
b = 1

print("Fibonacci series between 0 and 50:")

while a <= 50:
    print(a)
    c = a + b
    a = b
    b = c

Output:
0
1
1
2
3
5
8
13
21
34


# Program to remove characters with odd index values

string = input("Enter a string: ")

result = ""

for i in range(len(string)):
    if i % 2 == 0:
        result += string[i]

print("String after removing odd index characters:", result)


Output : 
Enter a string: Python
String after removing odd index characters: Pto
