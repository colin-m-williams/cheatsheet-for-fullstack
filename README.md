# cheatsheet-for-fullstack

## Javascript

Description | Javascript
--- | ---
Create a variable `elem1` | `var elem1;`
Create an empty array | `var arr = [];`
Create an empty object | `var obj = {};`


## jQuery

Description | jQuery
--- | ---
Get a reference to the element with ID `someid` | `var elem = $("#someid")`;
Create a new div | `var elem = $("<div>")`;
Set the inner text | `elem.text("hello");`
Insert `elem1` as the last child inside `parentElem` | `parentElem.append(elem1);`
Insert `elem1` as the first child inside `parentElem` | `parentElem.prepend(elem1);`
Send a request to a server | ` $.ajax({ url: "http://example.com", method: "GET" }).then(function(response) { console.log(response); });`
Set a click handler on elements with class `button` | `$(".button").on("click", function(event) { console.log("Event:", event); console.log("DOM node:", this); });`
Get the current value of an `<input>` element | `var val = $("#comment-input").val();`
Get the current value of the `data-state` attribute on `elem` | `var val = elem.attr("data-state");`
Set the `src` attribute on `elem` | `elem.attr("src", "http://example.com");`

## localStorage / sessionStorage

Description | localStorage | sessionStorage
--- | --- | ---
Clear localStorage for the current page | `localStorage.clear();` | `sessionStorage.clear();`
Set a value in localStorage | `localStorage.setItem("name", name);` | `sessionStorage.setItem("name", name);`
Get a value from localStorage | `var val = localStorage.getItem("name");` | `var val = sessionStorage.getItem("name");`
