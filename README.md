# LeetCode-242.-Valid-Anagram

## Adding every char to dictionaries
We add every character to a dictionary. If the key is not present in the current dictionary, default 0 is returned from get() method.
In Python, checking with == operator (dict1 == dict2) is more efficient than looping through every key and value. Thus we use == operator.

Time: O(len(s)+len(t))