This example uses class hidden to hide an element.

When you click a button the class hidden is added or removed from the section you want to hide show.


CSS class definition
```
.hidden {
    display: none;
}

```

Sample js code

```
let group1 = document.getElementById("group1");
let group2 = document.getElementById("group2");

let buttonMore = document.getElementById("button-more");
let buttonLess = document.getElementById("button-less");

buttonMore.onclick = function () {
    group1.classList.add("hidden");
    group2.classList.remove("hidden");
}

buttonLess.onclick = function () {
    group1.classList.remove("hidden");
    group2.classList.add("hidden");
}

```