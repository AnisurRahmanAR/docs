---
Title: '.add()'
Description: 'It adds an element of any type at the end of the list'
Subjects:
  - 'Computer Science'
  - 'Web Design'
  - 'Web Development'
Tags:
  - 'Dart'
  - 'Lists'
  - 'Development'
CatalogContent: # Please use course/path landing page slugs, rather than linking to individual content items. If listing multiple items, please put the most relevant one first
  - 'learn-dart'
  - 'paths/learn-dart-lists'
---

The **'.all()'** method in Dart is used to add elements of any type to the end of a list that you have created. It is important to note that it modifes the original list in place and always adds the elements to the end of the list. This method does not return any value.

## Syntax

```collectionName.add(element)
```
Where:
    'collectionName' is the name of the collection to which you want to add the element.
    '.add()' is the method used to add elements to the collection.
    'element' is the value you want to add to the collection.

## Example

List<int> numbers = [1, 2, 3, 4];
numbers.add(5);

Output:
print(numbers); // Output: [1, 2, 3, 4, 5]

In this example, the '.add()' method is used to add the integer '5' to the end of the 'numbers' list.
