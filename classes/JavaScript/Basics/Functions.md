Creating a function is simple, using `function` we can create a function for any task we need.

Example below:

<!-- create a function that logs out the number 27 to the console

call/invoke the function-->

<code>function logger() {
console.log(27)
}
logger()</code>

It is always important to call a function in order to have it print properly. When creating the variable that represents the function `logger()` it is also called using the name we gave it.

<h2>collecting counts</h2>
You can create a function that increments however much you want it too.

for example:


`let count = 0
`function increment() {`
`count = count + 1`
console.log(count)`	

if you wanted to display this count you could get the element by the ID in the HTML for reference in your javaScript

<code>document.getElementById("")</code>

inside the quotes you will quote the ID name, and then you need to grab what is being referenced and needs to reflect the count. So if the HTML code you are using looks like this:

`<h2 id="count-el">0</h2>`

Then you may need to use the code below to reference the changing count, which in this case is the '0'.

<code>.innerText</code>

--------------------
You can use += instead of using count = count + 1 or whenever you want to add to a function without changing the function.

count += 1 means the same thing.

----------------------------
- side note: `.textContent` will grab all the characters of a text including space.


