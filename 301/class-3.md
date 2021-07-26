# [Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)

1. What does .map() return?
 new array,.. returned by map()

2. If I want to loop through an array and display each value in JSX, how do I do that in React?
using curly braces {}.

3. Each list item needs a unique __key__.

4. What is the purpose of a key?

- Keys help React identify which items have changed, are added, or are removed.
 - special string attribute you need to include when creating lists of elements

 # [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

 1. What is the spread operator?
spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.

2. List 4 things that the spread operator can do.
- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments
- Adding an item to a list
- Adding to state in React
- Combining objects
- Converting NodeList to an array

3. Give an example of using the spread operator to combine two arrays.
\const array1 = [1,2,3]
\const array2 = [4,5,6]
\const array3 = [...myArray,...yourArray]


4. Give an example of using the spread operator to add a new item to an array.
\const fewFruit = ['s','h','r','a']
\const fewMoreFruit = ['b', 'u', ...fewFruit]

# [React - How to Pass Functions between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

1. In the video, what is the first step that the developer does to pass functions between components?
creat function where is the state where change

2. In your own words, what does the increment function do?
funtion to update vale using map 

3. How can you pass a method from a parent component into a child component?
In the parent component, create a callback function
This callback function will retrieve the data from the child component.
Pass the callback function to the child as a [props] from the parent component.
he child component calls the parent callback function using props and passes the data to the parent component

4. How does the child component invoke a method that was passed to it from a parent component?
this.setstate()