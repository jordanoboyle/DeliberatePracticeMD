Description:
Write a function findAnagrams that takes a word and an array of words. The function should return an array of all words from the input array that are anagrams of the given word.

const word = "listen";
const wordsArray = ["enlist", "google", "inlets", "banana"];
const result = findAnagrams(word, wordsArray);
console.log(result);

// ["enlist", "inlets"]
