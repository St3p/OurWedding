---
title: "RSVP"
description: "Reservation link"

cascade:
  showDate: false
  showAuthor: false
  invertPagination: true
---

<h2>Que Onda RSVP: Join the Fiesta in Nuevo Vallarta!</h2>

We hope this message finds you well! As our wedding day in Nuevo Vallarta approaches, we're eager to know if you'll be able to join us for this special celebration.

Your presence means a lot to us, and we've made the RSVP process quick and easy. Kindly let us know if you'll be part of our joyous day. We're also adding a personal touch to the celebration – feel free to request a song so you can shake that ass.

**Please note that this event will be adults-only, so plan for an evening of fun and celebration just for the grown-ups.**

<form  action="https://formspree.io/f/xeojanyk"method="POST">
<label for="name">Full Name:</label>
<input type="text" name="name" required>

<label for="email">Email Address:</label>
<input type="email" name="email" required>

<label for="attendance">Will you attend?</label>
<select name="attendance" required>
  <option value="yes">Yes, I will attend</option>
  <option value="no">No, I am unable to attend</option>
  <option value="maybe">Maybe, I'm not sure yet</option>
</select>

<label for="meal">Dietary Restrictions:</label>
<input type="text" name="Restrictions">

<label for="Menu">Please select a menu option for the big day!</label>
<select name="Menu" required>

  <option value="option 1">Option 1</option>
  <option value="option 2">option 2</option>
</select>

<label for="songRequests">Song Requests:</label>
<input type="text" name="songRequests">
  <!-- your other form fields go here -->
  <button type="submit">Send</button>
</form>

<style>
  form {
    max-width: 600px;
    margin: 20px auto;
    background-color: #ffffff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }

  label {
    display: block;
    margin-bottom: 8px;
    font-weight: bold;
  }

  input,
  select,
  textarea {
    width: 100%;
    padding: 8px;
    margin-bottom: 16px;
    box-sizing: border-box;
    border: 1px solid #ccc;
    border-radius: 4px;
  }

  textarea {
    height: 100px;
  }

  button:hover {
    color: #F18D32;
  }
</style>
