# Arrays-Strings
In array in C++ is a collection of items stored at contiguous memory locations and elements can be accessed randomly using indices of an array. They are used to store similar types of elements as in the data type must be the same for all elements. C++ string class internally uses character array to store character.



# **AIM-1**

c++ programe of Strings

## **THEORY**

A string in C++ is a type of object representing a collection (or sequence) of different characters. Strings in C++ are a part of the standard string class (std::string). The string class stores the characters of a string as a collection of bytes in contiguous memory locations. Strings are most commonly used in the programs where we need to work with texts. We can perform various operations on the strings in C++. For example, reversing, concatenating, or passing as an argument to a function.

The syntax to create a string in C++ is quite simple. We use the string keyword to create a string in C++. However, we also need to include the standard string class in our program before using this keyword.

string str_name = "This is a C++ string";

### **ALGORITHM**

- **String Display**
  
1. Start

2. Declare a string variable to store the input string (inputString).

3. Get the input string (inputString) from the user or from any source.

4. Use a `for` loop to iterate through the characters of the string:
   - Initialize a loop variable (i) to 0.
   - Continue the loop as long as i is less than the length of the string (inputString.length()).
   - In each iteration of the loop, print the character at index i.
   - Increment i after printing each character.

5. End

- **String Length**

1. Start

2. Declare a string variable to store the input string (inputString).

3. Get the input string (inputString) from the user or from any source.

4. Initialize a variable (length) to 0. This variable will be used to count the characters in the string.

5. Use a `for` loop to iterate through the characters of the string:
   - Initialize a loop variable (i) to 0.
   - Continue the loop as long as the character at index i is not the null character ('\0').
   - In each iteration of the loop, increment the length variable by 1.
   - Increment i to move to the next character.

6. After the loop completes, the length variable will contain the length of the string.

7. Display or use the length as needed.

8. End

- **String Concatenation and Reverse String Concatenation**
  
- *Concatenation Algorithm*:


1. Start

2. Declare two string variables, str1 and str2, to store the input strings.

3. Get input for str1 and str2 from the user or from any source.

4. Declare a string variable, resultStr, to store the concatenated string.

5. Use a `for` loop to concatenate str1 and str2:
   - Initialize a loop variable (i) to 0.
   - Iterate through the characters of str1 using i and append each character to resultStr.
   - Repeat the above step for str2.

6. Display or use resultStr as needed.

7. End

- *Reverse Concatenation Algorithm*:

1. Start

2. Declare a string variable, concatenatedStr, to store the concatenated string.

3. Get input for concatenatedStr from the user or from any source.

4. Declare two empty string variables, str1 and str2, to store the two original strings.

5. Calculate the length of the concatenatedStr.

6. Use a `for` loop to split the concatenatedStr into two original strings:
   - Initialize a loop variable (i) to 0.
   - Iterate through the characters of concatenatedStr using i.
   - Append each character to str1 until i reaches half the length of concatenatedStr.
   - Append the remaining characters to str2.

7. Display or use str1 and str2 as needed.

8. End

- **String Palindrome or not**

1. Start

2. Declare a string variable to store the input string (inputString).

3. Get the input string (inputString) from the user or from any source.

4. Remove spaces and punctuation marks (if needed) from the input string to ensure accurate palindrome checking.

5. Declare two integer variables, left and right:
   - Initialize left to 0 (indicating the start of the string).
   - Initialize right to the length of the string minus 1 (indicating the end of the string).

6. Use a `for` loop to compare characters from the beginning and end of the string:
   - Initialize a loop variable (i) to 0.
   - Continue the loop as long as i is less than or equal to right.
   - In each iteration of the loop, compare inputString[left] and inputString[right]:
     - If they are not equal, the string is not a palindrome; break out of the loop.
     - If they are equal, increment left and decrement right to check the next pair of characters.

7. If the loop completes without breaking, the string is a palindrome.

8. Display a message indicating whether the string is a palindrome or not.

9. End

### **OUTPUT**

- **String Display**
![Screenshot 2023-10-17 at 8 19 11 PM](https://github.com/sanskkriti/Arrays-Strings/assets/140137289/250aa0e3-295d-4f09-ac2d-aa6144eaae31)


- **String Length**
![Screenshot 2023-10-17 at 8 19 24 PM](https://github.com/sanskkriti/Arrays-Strings/assets/140137289/d98f50cd-a382-4142-8306-78e641fcb5cb)



- **String Concatenation and Reverse String Concatenation**

  ![Screenshot 2023-10-18 at 7 52 51 PM](https://github.com/sanskkriti/Arrays-Strings/assets/140137289/d1a231c4-00b8-41eb-9f97-bca3067ae2c1)



- **String Palindrome or not**

![Screenshot 2023-10-18 at 7 53 26 PM](https://github.com/sanskkriti/Arrays-Strings/assets/140137289/eb105e11-85d9-487e-ae05-7ea49131781c)



# **AIM-2**

C++ Program of Arrays 

## **THEORY**

In C++, an array is a data structure that is used to store multiple values of similar data types in a contiguous memory location.

For example, if we have to store the marks of 4 or 5 students then we can easily store them by creating 5 different variables but what if we want to store marks of 100 students or say 500 students then it becomes very challenging to create that numbers of variable and manage them. Now, arrays come into the picture that can do it easily by just creating an array of the required size.



## **ALGORITHM**

- **Enter the marks of 10 subjects and display it**

1. Start

2. Declare an array to store the marks for 10 subjects (marksArray).

3. Use a `for` loop to iterate 10 times (for each subject):
   - Initialize a loop variable (i) to 0.
   - Continue the loop as long as i is less than 10.
   - In each iteration of the loop, prompt the user to enter the marks for the current subject and store it in marksArray[i].

4. Display the marks for each subject using a `for` loop:
   - Initialize a loop variable (i) to 0.
   - Continue the loop as long as i is less than 10.
   - In each iteration of the loop, display the marks for the current subject from marksArray[i].

5. End

- **Enter the marks of subjects from user and display it**

1. Start

2. Declare variables for the number of subjects (numSubjects) and an array to store the marks (marksArray).

3. Prompt the user to enter the number of subjects (numSubjects).

4. Use a `for` loop to input marks for each subject:
   - Initialize a loop variable (i) to 0.
   - Continue the loop as long as i is less than numSubjects.
   - In each iteration of the loop, prompt the user to enter the marks for the current subject and store it in marksArray[i].

5. Display the marks for each subject using a `for` loop:
   - Initialize a loop variable (i) to 0.
   - Continue the loop as long as i is less than numSubjects.
   - In each iteration of the loop, display the marks for the current subject from marksArray[i].

6. End

- **C++ program to find the maximum and minimum value of given array**

1.Start

2.Declare an array to store the elements (arr) and variables to store the maximum (max) and minimum (min) values.

3.Initialize max and min with the first element of the array (i.e., max = arr[0] and min = arr[0]).

4.Use a for loop to iterate through the array:

5.Initialize a loop variable (i) to 1 (assuming the first element has already been assigned to max and min).

Continue the loop as long as i is less than the length of the array.

In each iteration of the loop:

Compare arr[i] with max:

If arr[i] is greater than max, update max to arr[i].

Compare arr[i] with min:

If arr[i] is smaller than min, update min to arr[i].

After the loop completes, max and min will contain the maximum and minimum values in the array, respectively.

6.Display the maximum and minimum values.

7.End

- **C++ Program to find array Sum_Average**

1.Start

2.Declare an array to store the elements (arr), a variable to store the sum (sum), and a variable to store the average (average).

3.Initialize sum to 0.

4.Use a for loop to iterate through the array:

5.Initialize a loop variable (i) to 0.

Continue the loop as long as i is less than the length of the array.

In each iteration of the loop:

Add arr[i] to sum.

5.Calculate the average by dividing the sum by the length of the array.

6.Display the sum and average.

7.End

- **To Flip Element**

1.Start

2.Declare an array to store the elements (arr).

3.Get the elements of the array from the user or from any source.

4.Calculate the length of the array (length).

5.Use a for loop to flip the array:

Initialize two loop variables, start and end.

Initialize start to 0 (indicating the beginning of the array) and end to length - 1 (indicating the end of the array).

Continue the loop as long as start is less than end.

In each iteration of the loop:

Swap arr[start] and arr[end].

Increment start by 1.

Decrement end by 1.

6.After the loop completes, the array will be flipped.

7.Display the flipped array.

8.End

#### **OUTPUT**

- **Enter the marks of 10 subjects and display it**
![Screenshot 2023-10-18 at 7 54 50 PM](https://github.com/sanskkriti/Arrays-Strings/assets/140137289/65a3c88d-e9d8-41ae-8a93-428434cbae12)

- **Enter the marks of subjects from user and display it**
![Screenshot 2023-10-18 at 7 54 59 PM](https://github.com/sanskkriti/Arrays-Strings/assets/140137289/a463af08-e264-406e-b09d-03bb742808e6)


![Screenshot 2023-10-18 at 7 55 05 PM](https://github.com/sanskkriti/Arrays-Strings/assets/140137289/7dc09a18-5ad1-489e-843f-8b4c03b2c894)

- **C++ program to find the maximum and minimum value of given array**

![Screenshot 2023-10-18 at 7 57 23 PM](https://github.com/sanskkriti/Arrays-Strings/assets/140137289/2a57e98a-4dad-4c8d-82fb-ffc149099596)


- **C++ Program to find array Sum_Average**
![Screenshot 2023-10-18 at 7 57 30 PM](https://github.com/sanskkriti/Arrays-Strings/assets/140137289/b1442a5b-43eb-4142-a690-919266682d87)


- **To Flip Element**
![Screenshot 2023-10-18 at 7 57 36 PM](https://github.com/sanskkriti/Arrays-Strings/assets/140137289/642ef5de-3e97-4097-8569-63f909f9a943)


  
