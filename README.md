# Prework Study Guide Webpage

## Description

This Prework Study Guide was created for boot camp students who were going through the Prework. It contains notes on HTML, CSS, Git, and JavaScript.

## Installation

N/A

## Usage

To use this Prework Study Guide, you can review the notes in each section. For suggestions on what to study first, open the Chrome DevTools by pressing Command+Option+I (macOS) or Control+Shift+I (Windows). A console panel should open either below or to the side of the webpage in the browser. There you will see a list of topics we learned from the prework along with a suggestion on which topic to study first.

## Credits

N/A

## License

MIT License

Copyright (c) 2024 onealshockley

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Prework Study Guide</title>
  </head>

  <body>
    <header id="top">
      <h1>Prework Study Guide</h1>
      <img src="./assets/bowtie-cat.png" alt="Profile image of cat wearing a bow tie." />
    <h2>✨ Open the Console to See What's Happening ✨</h2>
    </header>

    <main>
      <section class="card" id="html-section">
        <h2>HTML</h2>
        <ul>
          <li>The head element contains information about the webpage.</li>
          <li>The body element represents the visible content shown to the user.</li>
        </ul>
      </section>

      <section class="card" id="css-section">
        <h2>CSS</h2>
        <ul>
          <li>A margin indicates how much space we want around the outside of an element.</li>
          <li>A padding indicates how much space we want around the content inside an element.</li>
        </ul>
      </section>

      <section class="card" id="git-section">
        <h2>Git</h2>
        <ul>
          <li>git status: checks what branch we are currently on</li>
          <li>git checkout -b branch-name: creates a new branch and switches to it</li>
        </ul>
      </section>

      <section class="card" id="javascript-section">
        <h2>JavaScript</h2>
        <ul>
          <li>A variable is a named container that allows us to store data in our code.</li>
          <li>Control flow is the order in which a computer executes code in a script.</li>
        </ul>
      </section>
    </main>

    <footer>
      <p>I can code!</p>
    </footer>

    <script src="./assets/script.js"></script>
  </body>
</html>
