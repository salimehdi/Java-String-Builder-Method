
# Java String and StringBuilder Methods

This document provides an overview of the methods available in Java's `String` and `StringBuilder` classes, including descriptions of their functionalities.

---

## String Methods

| Method | Description |
| --- | --- |
| `str.charAt(int index)` | Returns the character at the specified index. |
| `str.concat(String str)` | Concatenates the specified string to the end. |
| `str.contains(CharSequence s)` | Checks if the string contains a specified sequence. |
| `str.contentEquals(CharSequence cs)` | Compares this string to a specified CharSequence. |
| `str.endsWith(String suffix)` | Checks if the string ends with the specified suffix. |
| `str.equals(Object obj)` | Compares this string to the specified object. |
| `str.equalsIgnoreCase(String anotherString)` | Compares to another string, ignoring case. |
| `str.indexOf(int ch)` | Returns the index of the first occurrence of the character. |
| `str.indexOf(String str)` | Returns the index of the first occurrence of the substring. |
| `str.lastIndexOf(int ch)` | Returns the index of the last occurrence of the character. |
| `str.length()` | Returns the length of the string. |
| `str.replace(char oldChar, char newChar)` | Replaces occurrences of `oldChar` with `newChar`. |
| `str.replace(CharSequence target, CharSequence replacement)` | Replaces each matching substring with the specified sequence. |
| `str.split(String regex)` | Splits the string around matches of the regex. |
| `str.startsWith(String prefix)` | Checks if the string starts with the specified prefix. |
| `str.substring(int beginIndex)` | Returns a substring from the specified index. |
| `str.substring(int beginIndex, int endIndex)` | Returns a substring within the specified range. |
| `str.toCharArray()` | Converts the string to a new character array. |
| `str.toLowerCase()` | Converts all characters to lowercase. |
| `str.toUpperCase()` | Converts all characters to uppercase. |
| `str.trim()` | Removes leading and trailing whitespace. |
| `str.join(CharSequence delimiter, CharSequence... elements)` | Joins strings with the specified delimiter. |

---

## StringBuilder Methods

| Method | Description |
| --- | --- |
| `sb.append(Object obj)` | Appends the string representation of an object. |
| `sb.append(String str)` | Appends the specified string. |
| `sb.append(char c)` | Appends the specified character. |
| `sb.append(CharSequence s, int start, int end)` | Appends a subsequence of the CharSequence. |
| `sb.delete(int start, int end)` | Removes characters in a substring of this sequence. |
| `sb.deleteCharAt(int index)` | Removes the character at the specified index. |
| `sb.insert(int offset, Object obj)` | Inserts the object's string representation. |
| `sb.insert(int offset, String str)` | Inserts the specified string at the specified position. |
| `sb.replace(int start, int end, String str)` | Replaces characters in the substring with the specified string. |
| `sb.reverse()` | Reverses the sequence of characters. |
| `sb.indexOf(String str)` | Returns the index of the first occurrence of the substring. |
| `sb.lastIndexOf(String str)` | Returns the index of the last occurrence of the substring. |
| `sb.setCharAt(int index, char ch)` | Sets the character at the specified position. |
| `sb.setLength(int newLength)` | Sets the length of this sequence. |
| `sb.length()` | Returns the length of this character sequence. |
| `sb.capacity()` | Returns the current capacity. |
| `sb.ensureCapacity(int minimumCapacity)` | Ensures capacity is at least `minimumCapacity`. |
| `sb.toString()` | Returns a string representing the data in this sequence. |

---

Feel free to use this reference to explore Java's `String` and `StringBuilder` functionalities!
