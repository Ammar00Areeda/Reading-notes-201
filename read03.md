# lists in HTML 

HTML lists allow web developers to group a set of related items in lists

## Unordered HTML List
An unordered list starts with the <(ul)> tag. Each list item starts with the <(li)> tag.

The list items will be marked with bullets (small black circles) by default:

<(ul>
  <(li>Coffee</(li>
  <(li>Tea</(li>
  <(li>Milk</(li>
<(/ul>


## HTML Description Lists
HTML also supports description lists.

A description list is a list of terms, with a description of each term.

The <dl> tag defines the description list, the <dt> tag defines the term (name), and the <dd> tag describes each term:

<(dl>
  <(dt>Coffee<(/dt>
  <(dd>- black hot drink<(/dd>
  <(dt>Milk<(/dt>
  <(dd>- white cold drink<(/dd>
</(dl>



tag | Description
------------ | -------------
<(ul> | 	Defines an unordered list
<(ol> | Defines an ordered list
<(li> | Defines a list item
<(dl> | Defines a description list
<(dt> | Defines a term in a description list
<(dd> | Describes the term in a description list

# The CSS Box Model

In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:

Explanation of the different parts:

 - Content - The content of the box, where text and images appear
 - Padding - Clears an area around the content. The padding is transparent
 - Border - A border that goes around the padding and content
 - Margin - Clears an area outside the border. The margin is transparent

 ## Width and Height of an Element

 In order to set the width and height of an element correctly in all browsers, you need to know how the box model works.

 Important: When you set the width and height properties of an element with CSS, you just set the width and height of the content area. To calculate the full size of an element, you must also add padding, borders and margins.

 ## array 

 he JavaScript Array class is a global object that is used in the construction of arrays; which are high-level, list-like objects.

 Arrays are list-like objects whose prototype has methods to perform traversal and mutation operations. Neither the length of a JavaScript array nor the types of its elements are fixed. Since an array's length can change at any time, and data can be stored at non-contiguous locations in the array, JavaScript arrays are not guaranteed to be dense; this depends on how the programmer chooses to use them. In general, these are convenient characteristics; but if these features are not desirable for your particular use, you might consider using typed arrays.

 ## Common operations

## Create an Array

 let fruits = ['Apple', 'Banana']

console.log(fruits.length)

## Access an Array item using the index position

let first = fruits[0]
// Apple

let last = fruits[fruits.length - 1]

## Loop over an Array

fruits.forEach(function(item, index, array) {
  console.log(item, index)
})
// Apple 0

## Add an item to the end of an Array

let newLength = fruits.push('Orange')
// ["Apple", "Banana", "Orange"]

## Remove an item from the end of an Array

let last = fruits.pop() // remove Orange (from the end)
// ["Apple", "Banana"]

## Remove an item from the beginning of an Array

let first = fruits.shift() // remove Apple from the front
// ["Banana"]

## Add an item to the beginning of an Array

let newLength = fruits.unshift('Strawberry') // add to the front
// ["Strawberry", "Banana"]

## Find the index of an item in the Array

fruits.push('Mango')
// ["Strawberry", "Banana", "Mango"]

let pos = fruits.indexOf('Banana')
// 1

## Remove an item by index position

let removedItem = fruits.splice(pos, 1) // this is how to remove an item

// ["Strawberry", "Mango"]

## Remove items from an index position

let vegetables = ['Cabbage', 'Turnip', 'Radish', 'Carrot']
console.log(vegetables)
// ["Cabbage", "Turnip", "Radish", "Carrot"]

let pos = 1
let n = 2

let removedItems = vegetables.splice(pos, n)
// this is how to remove items, n defines the number of items to be removed,
// starting at the index position specified by pos and progressing toward the end of array.

console.log(vegetables)
// ["Cabbage", "Carrot"] (the original array is changed)

console.log(removedItems)
// ["Turnip", "Radish"]


## Copy an Array

let shallowCopy = fruits.slice() // this is how to make a copy
// ["Strawberry", "Mango"]