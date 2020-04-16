---
summary: 'Use HTML table elements to create a calendar of events.'
time: '2 hours'
deliverables: '1 HTML file, 4 CSS files'
---

# Events calendar

## Overview

- *Fork this repository.*
- Use `<table>` to create the calendar layout
- Style the calendar using as little CSS in `main.css` as possible—leverage `modules.css` and `type.css`
- Text can be found inside the `content.txt` file.
- *Run it through Markbot and make sure it passes all the checks.*

---

## Details

- *Typefaces:* `Merriweather`
- *Corner radii:* `8px`
- *Colours:*
  - *Greys:* `#ccc`, `#666`, `#333`, `#f2f2f2`
  - *Greens:* `#d1e0bf`, `#6b7e54`, `#51603f`
  - *Reds:* `#f2bcbc`, `#b92828`, `#991919`
  - *Blues:* `#d2d6f0`, `#1d38da`, `#38448e`
- *Typografier settings:* defaults
- *Modulifier settings:* select all

---

## Goal

Visually match the images in the “screenshots” folder.

- Final screenshots in the “screenshots” folder.

---

## Hand in

Drop this folder into your Markbot application. Make sure to fix all the errors. And submit for grades using Markbot.


<!DOCTYPE html>
<html lang="en-ca">
<head>
  <meta charset="utf-8">
  <title>Events calendar</title>
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <link href="css/modules.css" rel="stylesheet">
  <link href="css/type.css" rel="stylesheet">
  <link href="css/main.css" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css?family=Merriweather&display=swap" rel="stylesheet">
</head>
<body>

  <main>
    <div class="island">
      <table border="1">
        <caption class="italic mega text-center push-0 pad-t-4 pad-b">November, 1963</caption>
        <thead>
          <tr class="list-group">
            <th class="sun bold" scope="col">Sun</th>
            <th class="mon bold" scope="col">Mon</th>
            <th class="tues bold" scope="col">Tues</th>
            <th class="wed bold" scope="col">Wed</th>
            <th class="thurs bold" scope="col">Thurs</th>
            <th class="fri bold" scope="col">Fri</th>
            <th class="sat bold" scope="col">Sat</th>
          </tr>
        </thead>

        <tbody>

          <tr class="list-group">
            <td class="bold pad-b-2" colspan="5"></td>
            <td class="bold bold text-right">1</td>
            <td class="bold bold text-right">2</td>
          </tr>



          <tr class="list-group">
            <td class="bold text-right">3
              <p class="grey milli not-bold gutter-1-4 push-0">Vostok 3 & 6 launched</p>
            </td>
            <td class="bold text-right">4</td>
            <td class="bold text-right">5</td>
            <td class="bold text-right">6</td>
            <td class="bold text-right">7</td>
            <td class="bold text-right">8</td>
            <td class="bold text-right">9</td>
          </tr>
          <tr class="list-group">
            <td class="bold text-right">10</td>
            <td class="bold text-right">11
              <p class="red milli gutter-1-4 push-0">Remembrance Day</p>
              <p class="grey milli gutter-1-4 push-0">Kosmos 21 failed to escape orbit</p>
            </td>
            <td class="bold text-right">12</td>
            <td class="bold text-right">13</td>
            <td class="bold text-right">14</td>
            <td class="bold text-right">15
              <p class="green milli gutter-1-4 push-0">Surtsey Island created</p>
              <p class="green milli gutter-1-4 push-0">Robert W. Smith set altitude record</p>
            </td>
            <td class="bold text-right">16</td>
          </tr>
          <tr class="list-group">
            <td class="boldtext-right">17</td>
            <td class="bold text-right">18</td>
            <td class="bold text-right">19</td>
            <td class="bold text-right">20</td>
            <td class="bold text-right">21
              <p class="grey milli gutter-1-4 push-0">India launched its first rocket</p>
            </td>
            <td class="bold text-right">22
              <p class="blue milli gutter-1-4 push-0">Death of Aldous Huxley</p>
            </td>
            <td class="bold text-right">23
              <p class="blue milli gutter-1-4 push-0">Doctor Who premiered</p>
            </td>
          </tr>
          <tr class="list-group">
            <td class="bold text-right">24</td>
            <td class="bold text-right">25</td>
            <td class="bold text-right">26
              <p class="grey milli gutter-1-4 push-0">Explorer 18 launched</p>
            </td>
            <td class="bold text-right">27</td>
            <td class="bold text-right">28</td>
            <td class="bold text-right">29</td>
            <td class="bold text-right">30</td>
          </tr>

        </tbody>
      </table>

    </div>
  </main>
</body>
</html>

html {
  font-family: "Merriweather", serif;
  margin: 0;
}

main {
  border-color: #f2f2f2
}

p {
  text-align: left;
}

.red {
  background-color: #f2bcbc;
  color: #991919;
  border: 1px solid #b92828;
  border-radius: 8px;
}

.grey {
  background-color: #f2f2f2;
  color: #333;
  border: 1px solid #666;
  border-radius: 8px;
}

.green {
  background-color: #d1e0bf;
  color: #6b7e54;
  border: 1px solid #51603f;
  border-radius: 8px;
}

.blue {
  background-color: #d2d6f0;
  color: #1d38da;
  border: 1px solid #38448e;
  border-radius: 8px;
}
