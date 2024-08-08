1. Filter an array of objects based on a specific key-value pair.
Example: [{id: 1, color: "blue"}, {id: 2, color: "red"}, {id: 3, color: "green"}] with key color and value red becomes [{id: 2, color: "red"}].

2. Sum the values of a specific key in an array of objects.
Example: [{price: 10}, {price: 20}, {price: 30}] becomes 60.

3. Merge two arrays of objects based on a common key.
Example: [{id: 1, name: "Alice"}, {id: 2, name: "Bob"}] and [{id: 1, age: 25}, {id: 2, age: 30}] becomes [{id: 1, name: "Alice", age: 25}, {id: 2, name: "Bob", age: 30}].

4. Convert a nested array into a single-level array.
Example: [[1, 2], [3, 4], [5, 6]] becomes [1, 2, 3, 4, 5, 6].

5. Group an array of objects by a specific key.
Example: [{type: "fruit", name: "apple"}, {type: "vegetable", name: "carrot"}, {type: "fruit", name: "banana"}] becomes {fruit: [{name: "apple"}, {name: "banana"}], vegetable: [{name: "carrot"}]}.

6. Convert an array of strings into a hash with keys as the strings and values as the lengths of the strings.
Example: ["apple", "banana", "cherry"] becomes {"apple": 5, "banana": 6, "cherry": 6}.

7. Find the intersection of two arrays.
Example: [1, 2, 3] and [2, 3, 4] becomes [2, 3].

8. Sort an array of objects by a specific key.
Example: [{name: "Alice", age: 25}, {name: "Bob", age: 20}] sorted by age becomes [{name: "Bob", age: 20}, {name: "Alice", age: 25}].

9. Create a hash from an array of keys and an array of values.
Example: ["name", "age"] and ["Alice", 25] becomes {"name": "Alice", "age": 25}.

10. Remove duplicate objects from an array based on a specific key.
Example: [{id: 1, name: "Alice"}, {id: 2, name: "Bob"}, {id: 1, name: "Alice"}] becomes [{id: 1, name: "Alice"}, {id: 2, name: "Bob"}].