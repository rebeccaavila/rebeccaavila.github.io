# rebeccaavila.github.io
<!DOCTYPE html>
<html>
<head>
   <meta charset="utf-8">
   <meta name="viewport" content="width=device-width">
   <title></title>

  <style>
    
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap');

    /*CSS Rules */

     h1 {
        color: hotpink;
        background-color: lightpink;
        border-radius: 2rem;
        margin: auto;

  }
 body {
    background-image: url("https://cdn.pixabay.com/photo/2017/07/08/12/36/background-2484300_1280.png");
    background-repeat: no-repeat;
    background-size: cover;
    width: 500px;
    margin: auto;
    font-family: "Poppins";
  }

form {
  background: rgb(255,192,203);
  border-radius: 2rem;
  width: 500px
  margin: auto;


}

img {
    border-radius: 20px;
    width: 120%;
  }
    
  </style>
    
</head>
<body>
<h1 id="title"> Hello Kitty Club Intrest form: </h1>

<P id="description"> Complete the form below if your intrested in the formation of a hello kitty club on campus! </p>

<figure>
    <img src="https://wallpapers.com/images/featured/7jjpu7c549ruidaf.jpg"/>
 
    <figcaption> ૮ • ﻌ - ა </figcaption>
</figure> 
<br>

<form id="survey-form">

<label for="name" id="name-label"> Name: </label>
  <input type="text" id="name"required name="name" required  placeholder="Enter your name">
  <br>
<label for="email" id="email-label"> Email: </label>
   <input type="email" id="email"required name="email" required placeholder="Enter your email"> 
<br>
<label for="number" id="number-label"> Age: </label>
    <input type="number" name ="qty"
    min="13" max="100"  id="number"required name="name" required placeholder="Age">
<br>
<br>

<label for="dropdown" id="character"> What is your favorite Sanrio Character? </label>
<select id="dropdown"> 
<option value="hello_kitty"> Hello kitty </option> 
<option value="kuromi"> Kuromi </option>
<option value="my_melody"> My Melody </option>
<option value="cinnamoroll"> Cinnamoroll </option>
  </select>
<br>
<br>

<label for="in_person" id="in_person"> Would you be able to attend in-person meetings? </label>
<br>
<input id="in_person" type="radio" id="yes" name="option" value="yes">
<label for="in_person"> Yes!</label>
<br>
<input id="in_person" type="radio" id="no" name="option" value="no">
<label for="in_person"> No..</label>
<br>
<input id="in_person" type="radio" id="depends" name="option" value="depends">
<label for="in_person"> Depends on the meeting time</label>
<br>
<br>

<label for"choices"> What <em>club times</em> would best work for your schedule? </label>
  <br>
<input id="checkbox" type="checkbox" name="choices" value="mornings">
<label for="checkbox"> Mornings: 9:00 am - 10:00 am </label>
<br>
<input id="checkbox" type="checkbox" name="choices" value="noon">
<label for="checkbox"> Noons: 11:00 am -12:00 pm </label>
<br>
<input id="checkbox" type="checkbox" name="choices" value="afternoons">
<label for="checkbox"> Afternoons: 3:00 pm -4:00 pm </label>
<br>
<input id="checkbox" type="checkbox" name="choices" value="evenings">
<label for="checkbox"> Evenings: 7:00 pm -8:00 pm </label>
<br>
<br>

<label for"days"> What <em>days</em> would best work for your schedule? </label>
  <br>
<input id="checkbox" type="checkbox" name="days" value="mondays">
<label for="checkbox"> Mondays</label>
<br>
<input id="checkbox" type="checkbox" name="days" value="tuesday">
<label for="checkbox"> Tuesdays </label>
<br>
<input id="checkbox" type="checkbox" name="days" value="wed">
<label for="checkbox"> Wednesdays </label>
<br>
<input id="checkbox" type="checkbox" name="days" value="th">
<label for="checkbox"> Thursdays </label>
<br>
<input id="checkbox" type="checkbox" name="days" value="fr">
<label for="checkbox"> Fridays </label>
<br>
<input id="checkbox" type="checkbox" name="days" value="st">
<label for="checkbox"> Saturdays </label>
<br>
<input id="checkbox" type="checkbox" name="days" value="sun">
<label for="checkbox"> Sundays </label>
<br>
<br>

<label id="textarea"> Any suggestions or comments for the club are much appreciated! </label>
<br>
<textarea id="textarea" name="comments" rows="5" cols="40">
  </textarea>
<br>

<input id="submit" type="submit" value="submit form">
  </form>


</body>
</html>
