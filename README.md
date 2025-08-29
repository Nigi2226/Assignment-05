# Emergency Service Directory README

## Overview
This is a web-based emergency service directory that provides quick access to emergency contact numbers with interactive features.

## Features
- Navbar with counters for hearts, coins, and copies.
- Hero section with a gradient background.
- Three emergency service cards with call and copy options.
- Call history that updates after simulated calls.

## Installation
1. Clone the repository or copy the HTML file.
2. Open the file in a web browser.

## Usage
- Click "Copy" to copy emergency numbers.
- Click "Call" to simulate a call (deducts 20 coins).
- Click "❤️" to increment the heart count.
- Click "Clear" to reset the call history.

## License
This project is open-source under the MIT License.
1. Difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll:

getElementById → Finds a single element by its unique id.

getElementsByClassName → Finds all elements with a given class (gives a live collection).

querySelector → Finds the first element that matches a CSS selector.

querySelectorAll → Finds all elements that match a CSS selector (returns a static list).

2. How to create and insert a new element into the DOM:

First, you create a new element.

Then, you insert it into the DOM by attaching it to a parent element (like appending it inside a div).

3. Event Bubbling and how it works:

Event bubbling means when an event happens on a child element, it automatically travels upward to its parent, then the parent’s parent, and so on, until it reaches the top (the document).

4. Event Delegation and why it’s useful:

Event delegation means attaching a single event listener to a parent element instead of adding one to every child.

It’s useful because it saves memory, makes code cleaner, and works for dynamically added elements.

5. Difference between preventDefault() and stopPropagation():

preventDefault() → Stops the default browser action (like stopping a form from submitting or a link from opening).

stopPropagation() → Stops the event from bubbling up to parent elements.

