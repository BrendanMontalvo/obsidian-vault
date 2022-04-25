Stands for Block Element Modifier

- Essentially all it is, is a way of simplifying how you name classes in your html.
- The idea is to be specific in terms of what your specific element is doing and name the class as such.

Example:

<code>
<div>This is an article excerpt</div>
<p>This is a link within the excerpt</p>
</code>
Now if we wanted to class the div line we could call it `class="article__excerpt"`

and if we  wanted to create a class for the link we could call it `class="excerpt__link"`

those two class names reference what the elements are, and in the case of the second element its referencing what the element does.

BEM keeps naming consistent and simple!
