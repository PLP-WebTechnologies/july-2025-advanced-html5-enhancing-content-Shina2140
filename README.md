# 📘 Assignment: Enhancing HTML5 Content & Mastering Forms

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Enhanced Form Page</title>
</head>
<body>

  <header>
    <h1>Enhanced HTML5 Page</h1>
    <p>This page demonstrates lists, tables, embedded media, and a complete HTML5 form.</p>
  </header>

  <!-- Section 1: Lists -->
  <section>
    <h2>Our Services</h2>
    <ul>
      <li>Web Development</li>
      <li>Digital Marketing</li>
      <li>Data Analytics</li>
    </ul>

    <h3>Steps to Get Started</h3>
    <ol>
      <li>Sign up for an account</li>
      <li>Choose your desired service</li>
      <li>Submit your request</li>
    </ol>
  </section>

  <!-- Section 2: Table -->
  <section>
    <h2>Pricing Table</h2>
    <table border="1" cellspacing="0" cellpadding="8">
      <thead>
        <tr>
          <th>Plan</th>
          <th>Price</th>
          <th>Features</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Basic</td>
          <td>$10/month</td>
          <td>Email Support</td>
        </tr>
        <tr>
          <td>Pro</td>
          <td>$25/month</td>
          <td>Email + Chat Support</td>
        </tr>
        <tr>
          <td>Enterprise</td>
          <td>$50/month</td>
          <td>24/7 Support</td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- Section 3: Media -->
  <section>
    <h2>Media Showcase</h2>
    <img src="https://www.w3schools.com/html/pic_trulli.jpg" alt="Sample Image" width="300">

    <h3>Audio Example</h3>
    <audio controls>
      <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>

    <h3>Video Example</h3>
    <video width="400" controls>
      <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </section>

  <!-- Section 4: Form -->
  <section>
    <h2>Sign Up Form</h2>
    <form action="#" method="post">
      <fieldset>
        <legend>Personal Information</legend>
        
        <label for="fullname">Full Name:</label>
        <input type="text" id="fullname" name="fullname" placeholder="Enter your full name" required minlength="3"><br><br>

        <label for="email">Email Address:</label>
        <input type="email" id="email" name="email" placeholder="example@mail.com" required autocomplete="on"><br><br>

        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" placeholder="123-456-7890" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}" required><br><br>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>
      </fieldset>

      <fieldset>
        <legend>Account Details</legend>

        <label for="username">Username:</label>
        <input type="text" id="username" name="username" required minlength="4"><br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required minlength="6"><br><br>

        <label for="confirm-password">Confirm Password:</label>
        <input type="password" id="confirm-password" name="confirm-password" required minlength="6"><br><br>
      </fieldset>

      <fieldset>
        <legend>Preferences</legend>

        <label for="plan">Choose Plan:</label>
        <select id="plan" name="plan" required>
          <option value="">-- Select a Plan --</option>
          <option value="basic">Basic</option>
          <option value="pro">Pro</option>
          <option value="enterprise">Enterprise</option>
        </select><br><br>

        <p>Subscribe to newsletter?</p>
        <label><input type="radio" name="newsletter" value="yes" required> Yes</label>
        <label><input type="radio" name="newsletter" value="no"> No</label><br><br>
      </fieldset>

      <button type="submit">Submit</button>
      <button type="reset">Reset</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Enhanced HTML5 Demo Page</p>
  </footer>

</body>
</html>


