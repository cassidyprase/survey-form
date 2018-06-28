# survey-form
Survey Form

<link href="https://fonts.googleapis.com/css?family=Prosto+One|Ruda" rel="stylesheet">



<html>
<head>
  <h1 id="title">Survey Form</h1>
  <p id="description">Holidays</p>
</head>
<body>
  <div id="div">
  <form id="survey-form">
<label for="name" id="name-label">Name:</label>
<input type="text"  id="name" placeholder="What's your name?" required> <br>
<br>
<label for="email" id="email-label">Email:</label>
<input type="email" id="email" placeholder="What's your email?" required>
<br>
<br>
    <label for="age" id="number-label">Age:</label>
    <input type="number" id="number" placeholder="Age" min="0" max="125" required>
<br>
<br>
    <label id="dropdown-label">What's Your Favorite Holiday?:</label>
<select id="dropdown" placeholder="Select your favorite">
<option value="Big Ten">New Year's</option>
  <option value="SEC">Valentine's Day</option>
  <option value="ACC">Easter</option>
  <option value="Big 12">4th of July</option>
  <option value="Halloween">Halloween</option>
  <option value="Thanksgiving">Thanksgiving</option>
  <option value="Christmas">Christmas</option>
</select>
  <br>
  <br>
    <label id="preference-two">Gender:</label>
    <input type="radio" name="preference" value="gender" id="Female"><label id="female-label">Female</label>

    <input type="radio" name="preference" value="gender" id="Male"><label id="male-label">Male</label>
    <br>
    <br>
    <label id="favorite">What are your two favorite parts about holidays?</label>
    <br>
    <input type="checkbox" name="family" value="family" id="family">
    <label id="family-label">Time spent with family</label>
    <br>
    <input type="checkbox" name="gifts" value="gifts" id="gifts">
    <label id="gifts-label">Receiving gifts</label>
    <br>
    <input type="checkbox" name="food" value="food" id="food">
    <label id="food-label">Eating delicious food</label>
    <br>
    <br>
    <label id="suggestions">Any comments or suggestions?</label>
    <br>
    <textarea name="comment" form="usrform" placeholder="comments/suggestions here"></textarea>
    <br>
    <button type="submit" name="submit" id="submit">Submit</button>
    </div>
  </form>
</body>
</html>
