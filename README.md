# How to Use
On a js file, write the following command inside an async function:

`let info = await fetch('viikdev.github.io/booksApi/data.json')
.then((res) => res.json())
.then((data) => console.log(data))`
