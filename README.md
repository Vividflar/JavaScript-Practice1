# JavaScript DOM Manipulation Demo

This project is a simple demonstration of how **JavaScript** can interact with HTML elements to dynamically update content using the DOM (`Document Object Model`).

---

## Features

- Uses **JavaScript variables** to store strings and numbers.
- Updates HTML content via:
  - `document.getElementById("id").innerHTML`
- Demonstrates **string concatenation** and number handling in JavaScript.
- Example outputs include:
  - A heading replaced with `"Another day, another DRRRr! Another diary"`
  - A paragraph replaced with `"Boom. Shoot my hair! What the Hell! What the HELL! WHAT the Hell!!!"`
  - A second paragraph replaced with `"Yhoo Wema! 69"`

---

## Code Example

```html
<h1 id="heading1">Hello</h1>
<p id="paragraph1">Everyone</p>
<p id="paragraph2"></p>

<script>
    var noice = "Another day, another DRRRr! Another diary";
    var haibo = "What the Hell! What the HELL! WHAT the Hell!!!";
    var shoot = "Boom. Shoot my hair! ";

    var bumA = 6;
    var bumB = 9;

    document.getElementById("heading1").innerHTML = noice;
    document.getElementById("paragraph1").innerHTML = shoot + haibo;
    document.getElementById("paragraph2").innerHTML = "Yhoo Wema! " + (bumA + bumB);
</script>
```

## Getting Started

Clone or download this repo.

Open the index.html file in a browser.

Watch how the page text changes dynamically!

## Learning Outcomes

How to select HTML elements with getElementById.

How to insert text dynamically with innerHTML.

The difference between string concatenation ("6" + "9" = "69") and numeric addition (6 + 9 = 15).

## Author

Paul Nhlanhla Sikhakhane
GitHub: Vividflar
