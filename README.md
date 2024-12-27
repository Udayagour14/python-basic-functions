### python-basic-functions
def get_greeting():

       return "Hello, welcome to Python programming!"

### Step 1: Call the function
message = get_greeting()

### Step 2: Print the returned value
print(message)

Step 1: Define the Function

When the Python interpreter reads the def get_greeting(): line, it stores the function in memory but does not execute it.
The function has no arguments, so the parentheses are empty, meaning it doesn’t expect any input.

Step 2: Call the Function
The function is called using get_greeting(). At this point, Python executes the function.

Step 3: Execute the Function Body

The function body contains one line:

return "Hello, welcome to Python programming!"

Step 4: Assign the Returned Value

The returned value "Hello, welcome to Python programming!" is assigned to the variable message.

Step 5: Print the Value

The print(message) line outputs the value stored in message to the console.

### Full Process Summary:
Define the function → The function is stored in memory.

Call the function → Executes the function body.

Return the value → Returns the string "Hello, welcome to Python programming!".

Assign the value → Stores the returned string in message.

Print the value → Outputs the string to the console.

### Final Output:
### Hello, welcome to Python programming!
## Global and local variables

Local variables are those that are initialized within a function and are unique to that function. It cannot be accessed outside of the function. Let’s look at how to make a local variable.

def f():
     
      s = "I love Geeksforgeeks"  # local variable
    
    print(s)
f()

If we will try to use this local variable outside the function then let’s see what will happen.

def f():
	
	# local variable
 
	s = "I love Geeksforgeeks"
 
	print("Inside Function:", s)

f()
print(s)
NameError: name 's' is not defined
