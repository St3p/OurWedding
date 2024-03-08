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

Warm regards,

  <form action="https://getform.io/f/nbvkglya" method="POST">
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

  <label for="songRequests">Song Requests:</label>
  <input type="text" name="songRequests">

  <buttonRSVP type="submit">RSVP</button>

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

  buttonRSVP {
    background-color: #F18D32;
    color: #F18D32;
    padding: 10px 15px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 16px;
  }

  buttonRSVP:hover {
    background-color: #F18D32;
    color: #ffffff;
  }
</style>
