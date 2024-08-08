1. Convert a nested hash into a flat hash.
Example: {"a": {"b": {"c": 1}}} becomes {"a.b.c": 1}.

2. Invert the keys and values of a hash.
Example: {"a": 1, "b": 2} becomes {1: "a", 2: "b"}.

3. Calculate the frequency of words in a string.
Example: "the cat in the hat" becomes {"the": 2, "cat": 1, "in": 1, "hat": 1}.

4. Merge two hashes, summing the values of common keys.
Example: {"a": 1, "b": 2} and {"a": 2, "c": 3} becomes {"a": 3, "b": 2, "c": 3}.

5. Group an array of hashes by multiple keys.
Example: [{type: "fruit", color: "red", name: "apple"}, {type: "vegetable", color: "green", name: "carrot"}, {type: "fruit", color: "yellow", name: "banana"}] by type and color becomes {fruit: {red: [{name: "apple"}], yellow: [{name: "banana"}]}, vegetable: {green: [{name: "carrot"}]}}.

6. Calculate the sum of nested values in an array of hashes.
Example: [{a: {b: 1}}, {a: {b: 2}}, {a: {b: 3}}] becomes 6.

7. Create a hash with default values for missing keys.
Example: {"a": 1, "b": 2} with default value 0 for keys "c" and "d" becomes {"a": 1, "b": 2, "c": 0, "d": 0}.

8. Remove keys with null or undefined values from a hash.
Example: {"a": 1, "b": null, "c": undefined, "d": 4} becomes {"a": 1, "d": 4}.

9. Find the union of two arrays, removing duplicates.
Example: [1, 2, 3] and [2, 3, 4] becomes [1, 2, 3, 4].

10. Convert an array of objects into a nested hash based on multiple keys.
Example: [{continent: "North America", country: "USA", city: "New York"}, {continent: "Europe", country: "Germany", city: "Berlin"}] becomes {"North America": {"USA": ["New York"]}, "Europe": {"Germany": ["Berlin"]}}.