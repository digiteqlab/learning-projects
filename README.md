<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Digiteq Lab Survey Form</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <h1 id="title">DIGITEQ LAB SURVEY FORM</h1>
    <p id="description">Share with your feedback and suggestions with us!</p>
    <form id="survey-form" method="get" action="https://register-demo.freecodecamp.org" >
    <fieldset>
      <label for="name" id="name-label">Name:  <input type="text" id="name" name="user-name" placeholder="Enter your name" required></label>
      <label for="email" id="email-label">Email:  <input type="email" id="email" name="user-email" placeholder="Enter your email" required></label>
      <label for="number" id="number-label">Age(optional) <input type="number" id="number" name="user-age" min="13" max="99" placeholder="Age"></label>
      <label for="dropdown" id="dropdown-label">What is your current occupation?
        <select id="dropdown" name="user-occupation">
          <option value="">Select your occupation</option>
          <option value="1">Student</option>
          <option value="2">Part-time Worker</option>
          <option value="3">Full-time Worker</option>
          <option value="4">Prefer not to say</option>
          <option value="5">Other</option>
        </select>
      </label>
    </fieldset>
    <fieldset class="recommendation">
      <legend class="text" id="recommendation">Would You Recommend digiTEQ to a Friend?</legend>
      <label for="positive"> <input id="positive" type="radio" value="yes" name="user-recommendation" class="options" checked> Yes, of course</label>
      <label for="doubt"> <input id="doubt" type="radio" value="yes-no" name="user-recommendation" class="options"> Let's see</label>
      <label for="negative"> <input id="negative" type="radio" value="no" name="user-recommendation" class="options"> Never</label>
    </fieldset>
    <fieldset>
      <label for="new-dropdown" id="new-dropdown-label">Which one of our services do you like best?
        <select id="new-dropdown" name="user-occupation">
          <option value="">Select a service</option>
          <option value="1">Technical Support</option>
          <option value="2">Graphic Design</option>
          <option value="3">Web Development</option>
          <option value="4">Sofware Development</option>
          <option value="5">Computer Networking</option>
        </select>
      </label>
    </fieldset>
    <fieldset class="recommendation">
      <legend class="text">Which one of our services need more improvement?</legend><p class="brackets">(Select all that applies)</p>
      <label for="training"><input id="training" type="checkbox" value="training" name="training" class="options" checked> Training</label>
      <label for="sales"><input id="sales" type="checkbox" value="sales" name="sales" class="options"> Sales Services</label>
      <label for="support"><input id="support" type="checkbox" value="support" name="support" class="options"> Customer Support</label>
      <label for="repair"><input id="repair" type="checkbox" value="repair" name="repair" class="options"> Servicing and Repair</label>
      <label for="install"><input id="install" type="checkbox" value="install" name="install" class="options"> Installation</label>
    </fieldset>
    <fieldset>
      <label for="comments">Leave us with your comments or suggestions.
        <textarea id="comments" cols="30" rows="5" placeholder="Type in here..." name="comments"></textarea>
      </label>
    </fieldset>
    <input type="submit" value="Submit" id="submit">
    </form>
  </body>
</html>
