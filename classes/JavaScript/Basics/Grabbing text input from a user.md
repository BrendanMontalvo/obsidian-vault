Syntax
----
Example: declare a variable that grabs the input from the HTML
<code>const inputEl = document.getElementById("input-el")<break></break>
myLeads.push(inputEl.value)
</code>

the `.value` syntax attached to inputEl is already determined to grab text because in the html the input type is 'text'. <strong>very</strong> important to make sure that the input type is established otherwise you may get different results.