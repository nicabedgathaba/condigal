# condigal

1. Loops in Python
Loops are used to execute a block of code multiple times.

Example of a for loop:
Example of a for loop
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)

Explanation:
This loop goes through each element in the list (fruits) and prints it.

Output:
apple
banana
Cherry

Example of a while loop:
### Example of a while loop
i = 1
while i <= 5:
    print(i)
    i += 1  # increment i by 1

Explanation:
This loop will continue to execute as long as the condition (i <= 5) is true. After each iteration, the value of i increases by 1.

Output:
1
2
3
4
5


2. Arrays in Python
In Python, arrays can be implemented using lists. Arrays store multiple values in a single variable.

Example of an Array (List) in Python:
### Example of an array (list)
numbers = [1, 2, 3, 4, 5]

### Accessing elements
print(numbers[0])  # Output: 1

### Modifying elements
numbers[2] = 10  # Changing the 3rd element to 10
print(numbers)    # Output: [1, 2, 10, 4, 5]

### Iterating over an array
for num in numbers:
    print(num)

Explanation:
numbers is a list (or array) containing five elements.
You can access elements using indexing (starting from 0).
Lists are mutable, meaning elements can be changed.

Output of loop:
1
2
10
4
5


3. Conditional Statements in Python
Conditional statements allow you to execute code based on certain conditions.
Example of an if, elif, and else statement:

### Example of if-elif-else conditional statements
age = 18

if age < 18:
    print("You are a minor.")
elif age == 18:
    print("You just became an adult!")
else:
    print("You are an adult.")
Explanation:

if: Checks if the condition (age < 18) is true. If true, it executes the block.

elif: Checks the next condition (age == 18) if the first one is false.

else: Executes if none of the above conditions are true.

Output:
You just became an adult!


Putting it All Together:
Loop with Conditional and Array (List):
### Example combining loop, array, and conditional statements
numbers = [1, 2, 3, 4, 5]

for num in numbers:
    if num % 2 == 0:
        print(f"{num} is even.")
    else:
        print(f"{num} is odd.")


Explanation:
The loop iterates over each number in the list numbers.
The if statement checks whether each number is even or odd.

Output:
1 is odd.
2 is even.
3 is odd.
4 is even.
5 is odd.

