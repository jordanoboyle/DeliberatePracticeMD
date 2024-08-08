SET 1 Write nested conditionals.
1. Write a program that stores a customer's age and a movie's time in two separate variables. Then calculate the price of a movie ticket based on the following conditions:

If the age is 12 years old or younger, the ticket price is $5.
If the age is between 13 and 59 years old and the movie is before 6 PM, the ticket price is $7. After 6 PM, the ticket price is $10.
If the customer is 60 years old or older, the ticket price is $7. 

2. Write a program to store the type of book (regular, reference, or special collection) and the number of days its overdue. Then calculate the fine amount based on the following conditions:

If the book is a regular book and overdue by up to 7 days, the fine is $1 per day.
If the book is a regular book and overdue by more than 7 days, the fine is $2 per day.
If the book is a reference book, there is no fine, regardless of the number of days overdue.
If the book is a special collection book, the fine is $5 per day, regardless of the number of days overdue.

BONUS: write a method that generates a random book type, and random number of days for overdue to test your other method. 

3. Write a program that stores a person's order value and membership level (regular or premium). Then calculate a discount amount based on the following conditions:

If the total order value is less than $50, there is no discount.
If the total order value is between $50 and $100, the discount is 5% for regular customers and 10% for premium customers.
If the total order value is greater than $100, the discount is 10% for regular customers and 15% for premium customers.

4. Write a Ruby program that stores the weight of a package and the destination (domestic or international). Then calculate the shipping fee based on the following conditions:

If the destination is domestic:
If the weight is less than or equal to 1 kg, the shipping fee is $5.
If the weight is greater than 1 kg, the shipping fee is $10.
If the destination is an international shipment:
If the weight is less than or equal to 1 kg, the shipping fee is $15.
If the weight is greater than 1 kg, the shipping fee is $25.


SET 2 Write Nested Loops
1. Use a nested loop to convert an array of number pairs into a single flattened array.
For example, [[1, 3], [8, 9], [2, 16]] becomes [1, 3, 8, 9, 2, 16].

2. Use a nested loop with two arrays of strings to create a new array of strings with each string combined.
For example, ["a", "b", "c"] and ["d", "e", "f", "g"] becomes ["ad", "ae", "af", "ag", "bd", "be", "bf", "bg", "cd", "ce", "cf", "cg"].

3. Use a nested loop with one array of strings to create a new array that contains every combination of each string with every other string in the array.
For example, ["a", "b", "c", "d"] becomes ["ab", "ac", "ad", "ba", "bc", "bd", "ca", "cb", "cd", "da", "db", "dc"].

4. Use a nested loop to find the largest product of any two different numbers within a given array.
For example, [5, -2, 1, -9, -7, 2, 6] becomes 63.

5. Use a nested loop to compute the sum of all the numbers in an array of number pairs.
For example, [[1, 3], [8, 9], [2, 16]] becomes 39.

6. Use a nested loop with two arrays of numbers to create a new array of the sums of each combination of numbers.
For example, [1, 2] and [6, 7, 8] becomes [7, 8, 9, 8, 9, 10].

7. Use a nested loop with an array of numbers to compute an array with every combination of products from each number.
For example, [2, 8, 3] becomes [4, 16, 6, 16, 64, 24, 6, 24, 9].




SET 4 CONVERT DATA FROM ONE DATA TYPE TO ANOTHER. 

1. Convert an array of arrays into a hash.
For example, [[1, 3], [8, 9], [2, 16]] becomes {1 => 3, 8 => 9, 2 => 16}.co 

2. Convert an array of hashes into a hash using the :id key from the array's hashes as the keys in the new hash.
For example, [{id: 1, color: "blue", price: 32}, {id: 2, color: "red", price: 12}, {id: 3, color: "green", price: 13}] becomes {1 => {id: 1, color: "blue", price: 32}, 2 => {id: 2, color: "red", price: 12}, 3 => 3 => {id: 3, color: "green", price: 13}}.

3. Convert a string into a hash with keys for each letter in the string and values for the number of times the letter appears in the string.
For example, "bookkeeper" becomes {"b" => 1, "o" => 2, "k" => 2, "e" => 3, "p" => 1, "r" => 1}.

4. Convert a hash into an array of arrays.
For example, {"chair" => 100, "book" => 14, "desk" => 98, "footstool" => 133} becomes [["chair", 100], ["book", 14], ["desk", 98], ["footstool", 133]]..

5. Convert a hash into an array of hashes using the keys from each hash as the :id key in each of the array's hashes.
For example, {321 => {name: "Alice", age: 31}, 322 => {name: "Maria", age: 27}} becomes [{id: 321, name: "Alice", age: 31}, {id: 322, name: "Maria", age: 27}].

6. Convert an array of strings into a hash with keys for each string in the array and values for the number of times the string appears in the array.
For example, ["do", "or", "do", "not"] becomes {"do" => 2, "or" => 1, "not" => 1}.

7. Convert a hash into a flat array containing all the hash’s keys and values.
For example, {"a" => 1, "b" => 2, "c" => 3, "d" => 4} becomes ["a", 1, "b", 2, "c", 3, "d", 4].

8. Combine data from a hash with names and prices and an array of hashes with names, colors, and weights to make a new hash.
For example, {"chair" => 75, "book" => 15} and [{name: "chair", color: "red", weight: 10}, {name: "book", color: "black", weight: 1}] becomes {"chair" => {price: 75, color: "red", weight: 10}, "book" => {price: 15, color: "black", weight: 1}}.

9. Convert an array of hashes into a hash of arrays, using the author as keys and the titles as values.
For example, [{author: "Jeff Smith", title: "Bone"}, {author: "George Orwell", title: "1984"}, {author: "Jeff Smith", title: "RASL"}] becomes {"Jeff Smith" => ["Bone", "RASL"], "George Orwell" => ["1984"]}.

10. Given a hash, create a new hash that has the keys and values switched.
For example, {"a" => 1, "b" => 2, "c" => 3} becomes {1 => "a", 2 => "b", 3 => "c"}.


SET 4 WRITE CUSTOM CLASS WITH COMPLEX ATTRIBUTES

1. Write a ShoppingCart class that stores an array of items with methods to add an item, remove an item, and display all the items.

2. Write a Product class that stores the name, price, and metadata, where metadata is a hash that stores additional information about the product.

3. Write a Playlist class that stores a name and an array of songs with methods to add a song, remove a song, shuffle the songs into a random order, and display all the songs.

4. Write a Contact class that stores the name, age, and contact_info, where contact_info is a hash that stores any additional information about the contact.