
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

# Java Collection Classes - Complete Method Overview

This document provides an overview of all methods in Java's `HashSet`, `TreeSet`, `LinkedHashSet`, `HashMap`, `TreeMap`, `Stack`, and `Queue` classes with brief descriptions for each.

---

## HashSet Methods

| Method | Description |
| --- | --- |
| `add(E e)` | Adds an element if not already present. |
| `addAll(Collection<? extends E> c)` | Adds all elements in the specified collection. |
| `clear()` | Removes all elements from the set. |
| `clone()` | Returns a shallow copy of this set. |
| `contains(Object o)` | Checks if the set contains the specified element. |
| `isEmpty()` | Checks if the set is empty. |
| `iterator()` | Returns an iterator over the set elements. |
| `remove(Object o)` | Removes the specified element if present. |
| `removeAll(Collection<?> c)` | Removes all elements from the set that are in the specified collection. |
| `size()` | Returns the number of elements. |
| `toArray()` | Returns an array containing all elements. |
| `toArray(T[] a)` | Returns an array with elements stored in the specified array. |
| `retainAll(Collection<?> c)` | Keeps only elements in this set that are also in the specified collection. |

---

## TreeSet Methods

| Method | Description |
| --- | --- |
| `add(E e)` | Adds the specified element if it is not present. |
| `ceiling(E e)` | Finds the least element ≥ the given element. |
| `clear()` | Removes all elements from the set. |
| `contains(Object o)` | Checks if the set contains the specified element. |
| `descendingIterator()` | Returns a descending order iterator. |
| `first()` | Returns the lowest element. |
| `floor(E e)` | Finds the greatest element ≤ the given element. |
| `higher(E e)` | Finds the least element > the given element. |
| `isEmpty()` | Checks if the set is empty. |
| `last()` | Returns the highest element. |
| `lower(E e)` | Finds the greatest element < the given element. |
| `pollFirst()` | Removes and returns the lowest element. |
| `pollLast()` | Removes and returns the highest element. |
| `size()` | Returns the number of elements in the set. |
| `subSet(E fromElement, E toElement)` | Returns a subset between `fromElement` and `toElement`. |

---

## LinkedHashSet Methods

| Method | Description |
| --- | --- |
| `add(E e)` | Adds the specified element if not already present. |
| `clear()` | Removes all elements from the set. |
| `contains(Object o)` | Checks if the set contains the specified element. |
| `isEmpty()` | Checks if the set is empty. |
| `iterator()` | Returns an iterator over the elements in insertion order. |
| `remove(Object o)` | Removes the specified element if present. |
| `size()` | Returns the number of elements. |
| `toArray()` | Returns an array with all set elements. |

---

## HashMap Methods

| Method | Description |
| --- | --- |
| `clear()` | Removes all key-value mappings. |
| `containsKey(Object key)` | Checks if the map contains a specified key. |
| `containsValue(Object value)` | Checks if the map contains a specified value. |
| `entrySet()` | Returns a set view of the mappings. |
| `get(Object key)` | Returns the value associated with the key. |
| `getOrDefault(Object key, V defaultValue)` | Returns the value or default if absent. |
| `isEmpty()` | Checks if the map is empty. |
| `keySet()` | Returns a set view of keys. |
| `put(K key, V value)` | Adds a key-value mapping. |
| `putAll(Map<? extends K, ? extends V> m)` | Copies mappings from the specified map. |
| `putIfAbsent(K key, V value)` | Adds the key-value pair if absent. |
| `remove(Object key)` | Removes a mapping by key. |
| `replace(K key, V value)` | Replaces value for a specified key. |
| `size()` | Returns the number of key-value pairs. |
| `values()` | Returns a collection view of values. |

---

## TreeMap Methods

| Method | Description |
| --- | --- |
| `clear()` | Removes all key-value mappings. |
| `ceilingEntry(K key)` | Finds the entry with the least key ≥ the specified key. |
| `ceilingKey(K key)` | Finds the least key ≥ the specified key. |
| `containsKey(Object key)` | Checks if the map contains a specified key. |
| `entrySet()` | Returns a set view of the entries. |
| `firstKey()` | Returns the lowest key. |
| `floorEntry(K key)` | Finds the entry with the greatest key ≤ the specified key. |
| `floorKey(K key)` | Finds the greatest key ≤ the specified key. |
| `get(Object key)` | Returns the value associated with the specified key. |
| `headMap(K toKey)` | Returns a view of the portion of the map whose keys are less than `toKey`. |
| `higherEntry(K key)` | Finds the entry with the least key > the specified key. |
| `isEmpty()` | Checks if the map is empty. |
| `lastKey()` | Returns the highest key. |
| `put(K key, V value)` | Adds a key-value pair. |
| `remove(Object key)` | Removes the mapping for a key if present. |
| `size()` | Returns the number of key-value mappings. |
| `subMap(K fromKey, K toKey)` | Returns a sub-map view from `fromKey` to `toKey`. |

---

## Stack Methods

| Method | Description |
| --- | --- |
| `empty()` | Checks if the stack is empty. |
| `peek()` | Returns the top element without removing it. |
| `pop()` | Removes and returns the top element. |
| `push(E item)` | Pushes an element onto the top of the stack. |
| `search(Object o)` | Finds the position of an element from the top. |
| `size()` | Returns the number of elements. |

---

## Queue Methods

| Method | Description |
| --- | --- |
| `add(E e)` | Inserts an element if possible without violating capacity. |
| `element()` | Retrieves, without removing, the head of the queue. |
| `offer(E e)` | Inserts an element if possible without violating capacity. |
| `peek()` | Retrieves, without removing, the head, or returns `null` if empty. |
| `poll()` | Retrieves and removes the head, or returns `null` if empty. |
| `remove()` | Retrieves and removes the head of the queue. |
| `size()` | Returns the number of elements. |

---

