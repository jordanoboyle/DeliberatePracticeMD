  This is the Intermediate selection from Deliberate Practice

SET 1 INSERT A VARIABLE INTO A STRING USING EITHER CONCATENATION OR INTERPOLATION.
# 1 Write a program that uses variables to store a first and last name, then prints the full name in one line using string concatenation (the + operator).

# 2 Write a program that uses variables to store a first and last name, then prints the full name in one line using string interpolation (the #{} operator).

# 3 Write a program that asks the user to input a word. If the word is "marco", print "polo".

# 4 Write a program that uses variables to store three different colors, then prints out a sentence using the colors with string concatenation (the + operator).

# 5 Write a program that uses variables to store three different colors, then prints out a sentence using the colors with string interpolation (the #{} operator).

# 6 Write a program that asks the user to enter a name. If the name is not "Santa", print "You're not Santa."

# 7 Write a program that uses variables to store a book's title and author, then prints out a sentence using that information with string concatenation (the + operator).

# 8 Write a program that uses variables to store a book's title and author, then prints out a sentence using that information with string interpolation (the #{} operator).

# 9 Write a program that asks the user to enter a password. If the password is "Joshua", the program responds "Shall we play a game?". For any other password, the program responds "Access denied"

# 10 Write a program that uses variables to store the names of three cities, then prints out a sentence using that information with string concatenation (the + operator).


SET 2 MAP AN ARRAY TO A NEW ARRAY WITH SOME COMPUTATION PERFORMED ON EACH ITEM

# 1 Start with an array of numbers and create a new array with each number times 3. For example, [1, 2, 3, 4] becomes [3, 6, 9, 16].

# 2 Start with an array of strings and create a new array with each string upcased. For example, ["hello", "goodbye", "later"] becomes ["HELLO", "GOODBYE", "LATER"].

# 3 Start with an array of hashes and create a new array of string values from each hash's :name key. For example, [{name: "Alice", age: 27}, {name: "Blane", age: 16}, {name: "Cloud", age: 25}] becomes ["Alice", "Blane", "Cloud"].

# 4 Start with an array of numbers and create a new array with each number plus 7. For example, [1, 2, 3] becomes [8, 9, 10].

# 5 Start with an array of strings and create a new array with each string's length. For example, ["hello", "goodbye", "frog"] becomes [5, 7, 4].

# 6 Start with an array of hashes and create a new array of number values from each hash's :age key. For example, [{name: "Alice", age: 27}, {name: "Blane", age: 16}] becomes [27, 16]. (bonus: use string interpolation to print out a coherent sentence)

# 7 Start with an array of numbers and create a new array with each number divided by 2. For example, [1, 2, 3, 4] becomes [0.5, 1.0, 1.5, 2.0]. (BONUS) Try making an array of hashes like this {1: {0.5: "Is 1 / 2"}}

# 8 Start with an array of strings and create a new array with each string's first letter only. For example, ["hello", "goodbye"] becomes ["h", "g"]. BONUS: make a hash yielding [{first_l: "h", last_l: "o", whole: "hello"}]

# 9 Start with an array of hashes and create a new array of number values from each hash's :age key times 2. For example, [{name: "Alice", age: 27}, {name: "Blane", age: 16}, {name: "Barret", age: 33}] becomes [54, 32, 66].

# 10 Start with an array of numbers and create a new array with each number converted into a string. For example, [1, 2, 3, 4] becomes ["1", "2", "3", "4"].


SET 3 SELECT ITEMS FROM AN ARRAY INTO A NEW ARRAY WITH ITEMS THAT MATCH A CERTAIN CONDITION

# 1 Start with an array of numbers and create a new array with only the numbers less than 20. For example, [2, 32, 80, 18, 12, 3] becomes [2, 18, 12, 3].

# 2 Start with an array of strings and create a new array with only the strings that start with the letter "w". For example, ["winner", "winner", "chicken", "dinner"] becomes ["winner", "winner"].

# 3 Start with an array of hashes and create a new array with only the hashes with prices greater than 5 (from the :price key). For example, [{name: "chair", price: 100}, {name: "pencil", price: 1}, {name: "book", price: 4}] becomes [{name: "chair", price: 100}].

# 4 Start with an array of numbers and create a new array with only the even numbers. For example, [2, 4, 5, 1, 8, 9, 7] becomes [2, 4, 8].

# 5 Start with an array of strings and create a new array with only the strings shorter than 4 letters. For example, ["a", "man", "a", "plan", "a", "canal", "panama"] becomes ["a", "man", "a", "a"].

# 6 Start with an array of hashes and create a new array with only the hashes with names shorter than 6 letters (from the :name key). For example, [{name: "chair", price: 100}, {name: "pencil", price: 1}, {name: "book", price: 4}] becomes [{name: "chair", price: 100}, {name: "book", price: 4}].

# 7 Start with an array of numbers and create a new array with only the numbers less than 10. For example, [8, 23, 0, 44, 1980, 3] becomes [8, 0, 3].

# 8 Start with an array of strings and create a new array with only the strings that don't start with the letter "b". For example, ["big", "little", "good", "bad"] becomes ["little", "good"].

# 9 Start with an array of hashes and create a new array with only the hashes with prices less than 10 (from the :price key). For example, [{name: "chair", price: 100}, {name: "pencil", price: 1}, {name: "book", price: 4}] becomes [{name: "pencil", price: 1}, {name: "book", price: 4}].

# 10 Start with an array of numbers and create a new array with only the odd numbers. For example, [2, 4, 5, 1, 8, 9, 7] becomes [5, 1, 9, 7].



SET 4 REDUCE AN ARRAY TO A SINGLE VALUE BASED ON SOME COMPUTATION
# 1 Start with an array of numbers and compute the sum of all the numbers. For example, [5, 10, 8, 3] becomes 26.

# 2 Start with an array of strings and combine them all into a single string. For example, ["volleyball", "basketball", "badminton"] becomes "volleyballbasketballbadminton".

# 3 Start with an array of hashes and compute the sum of the prices (from the :price key). For example, [{name: "chair", price: 100}, {name: "pencil", price: 1}, {name: "book", price: 4}] becomes 105.

# 4 Start with an array of numbers and compute the the minimum number. For example, [5, 10, 8, 3, 9] becomes 3.

# 5 Start with an array of strings and compute the total length of all the strings. For example, ["volleyball", "basketball", "badminton"] becomes 29.

# 6 Start with an array of hashes and find the hash with the lowest price (from the :price key). For example, [{name: "chair", price: 100}, {name: "pencil", price: 1}, {name: "book", price: 4}] becomes {name: "pencil", price: 1}.

# 7 Start with an array of numbers and compute product of all the numbers. For example, [5, 10, 8, 3] becomes 1200.

# 8 Start with an array of strings and combine them all into a single string, separated by dashes. For example, ["volleyball", "basketball", "badminton"] becomes "-volleyball-basketball-badminton-".

# 9 Start with an array of hashes and find the hash with the shortest name (from the :name key). For example, [{name: "chair", price: 100}, {name: "pencil", price: 1}, {name: "book", price: 4}] becomes {name: "book", price: 4}.

# 10 Start with an array of numbers and compute the maximum number. For example, [5, 10, 8, 3] becomes 10.


SET 5 WRITE A CUSTOM CLASS WITH CUSTOM METHODS

# 1 Write a Song class with attributes and reader/writer methods for name, artist, and duration. Then write a method that prints the name, artist, and duration in a single sentence.

# 2 Write a Rectangle class with attributes and reader/writer methods for width and height. Then write a method that returns the area of the rectangle.

# 3 Write a Person class with attributes and reader/writer methods for name and age. Then write a method that returns the person's name in all capital letters.

# 4 Write a Coordinate class with attributes and reader/writer methods for latitude and longitude. Then write a method that prints out the latitude and longitude in a single sentence.

# 5 Write an Account class with attributes and reader/writer methods for name and balance. Then write a method that prints a warning if the balance is below $100.

# 6 Write a Movie class with attributes and reader/writer methods for title, director, and year. Then write a method that prints out the attributes in a single sentence.

# 7 Write a Car class with attributes and reader/writer methods for make, model, year, and color. Then write a method that returns the make and model as a single sentence in all lowercase letters.

# 8 Write a Point class with attributes and reader/writer methods for x, y, and z coordinates. Then write a method that returns true if all 3 numbers are positive, otherwise it returns false.

# 9 Write a Book class with attributes and reader/writer methods for title, author, and year. Then write a method that returns "Classic" if the book is older than 2000, otherwise it returns "Modern".

# 10 Write a Plant class with attributes and reader/writer methods for name, size, and price. Then write a method that prints out the attributes in a single sentence.