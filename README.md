Café Mosaic — Static HTML Project

Short Description
Café Mosaic is a small website built only with HTML5.
It shows a simple café website with pages for home, menu, gallery, events, contact, and about.
The goal is to practice semantic HTML, tables, lists, forms, and navigation between pages.


---

How to Open the Website

1. Download or clone the cafe-mosaic/ folder.


2. Open the file index.html in your browser.


3. Use the links to move between pages.


4. The “Events” pages simulate a CRUD system (create, read, update, delete) but with static HTML only.




---

Folder Structure

cafe-mosaic/
│
├── index.html
├── menu.html
├── gallery.html
├── about.html
├── contact.html
├── README.md
├── images/
│   ├── interior.png
│   ├── coffee.png
│   └── ...
│
└── events/
    ├── events-list.html
    ├── event-create.html
    ├── event-view-1.html
    ├── event-edit-1.html
    ├── event-delete-1.html
    └── ...

> All names are lowercase and have no spaces.




---

Pages Overview

index.html — Home page with the main title, slogan, and navigation menu.

menu.html — Shows the café menu with lists and price tables. Includes <caption>, <thead>, <tbody>, and <time> for available hours or offers.

gallery.html — A gallery with at least 6 images. Each image is inside a <figure> with a <figcaption> and an alt text. Some images use loading="lazy".

about.html — About the café. Contains sections for history, team (using <ul> and nested lists), and opening hours (with <table>).

contact.html — Contact page with a contact form (name, email, subject, message) using <fieldset> and <legend>. Also includes contact details and a mailto: link.

events folder — Contains the event pages:

events-list.html — Shows a list of events with action links.

event-view-1.html — Shows event details.

event-create.html — Page to add a new event (simulation).

event-edit-1.html — Page to edit an event.

event-delete-1.html — Page to confirm event deletion.




---

CRUD Simulation

There is no real database or JavaScript.
Each page just simulates a CRUD flow using static links:

Create → event-create.html

Read → events-list.html and event-view-1.html

Update → event-edit-1.html

Delete → event-delete-1.html


All action buttons link to the next page to simulate real behavior.


---

HTML Rules & Accessibility

The document starts with <!DOCTYPE html> and lang="en".

Uses semantic HTML tags: <header>, <nav>, <main>, <section>, <footer>.

Every image has an alt attribute.

Every input has a <label> with for="...".

Tables include <caption>, <thead>, <tbody>, and <th>.

Internal links open in the same tab.

External links use target="_blank" and rel="noopener noreferrer".

Headings follow the correct order (h1 → h2 → h3).



---

What Was Used

✅ <ul> and nested <ul> lists
✅ <table> with captions and headers
✅ <figure> and <figcaption>
✅ <time> for hours or dates
✅ <form> with <fieldset> and <legend>
✅ <header>, <footer>, <section>, <aside>
✅ Internal links between all pages


---

Author

Adam Braija
Digital Developpement Student — Morocco
GitHub: https://github.com/AdamBraija
LinkedIn: https://www.linkedin.com/in/adam-braija