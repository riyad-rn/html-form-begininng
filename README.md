<!DOCTYPE html>

<html lang="en">
<head>
    <title> creating job </title>
    <meta charset="UTF-8">

</head>

<body>
    <form action="#" method="post">

<h1 style="text-align: center;"> JOB APPLICATION FORM </h1>
<hr>
<h2> <u> personal information:-</u> </h2>
<label for="user_name">full name</label>
<input type="text" id="user_name" name="user_name" placeholder="ENTER YOUR NAME" required>
<br>
<label for="email">email address</label>
<input type="email" id="email" name="email" placeholder="ENTER YOUR EMAIL" required>
<br>
<label for="phone">phone number </label>
<select name="code">
    <option value="+880">+880</option>
    <option value="+971">+971</option>
    <option value="+44">+44</option>
</select>
<input type="number" id="phone" name="phone" placeholder="ENTER YOUR PHONE NUMBER" required> 
<br>
<label for="dob">date of birth</label>
<input type="date" id="dob" name="dob" required>
<br>
<input type="radio" id="male" name="gender" value="male">
<label for="male">Male</label>
<input type="radio" id="female" name="gender" value="female" >
<label for="female">Female</label>
<input type="radio" id="other" name="gender" value="other">
<label for="other">Other</label>
<br>
<h2><u>address details:-</u></h2>
<label for="street">street address</label>
<input type="text" id="street" name="street">
<br>
<label for="ct">city</label>
<input type="text" id="ct" name="ct">
<br>
<label for="state">state</label>
<input type="text" id="state" name="state">
<br>
<label for="zip">zip code</label>
<input type="number" name="zip" id="zip">
<br>
<h2><u>job preferences:-</u></h2>
<label for="dp">desired position</label>
<input type="text" name="dp" id="dp">
<br>
<label for="es">expected salary</label>
<input type="number" id="es" name="es"><BR>
<label for="work_type">work type</label>
<select name="work_type" id="work_type" > 
<option value="full-time">full time</option>
<option value="part-time">part time</option>
<option value="remote">remote</option>

</select>
<br>
<h2><u>education and experience</u></h2>
<label for="edu"> highest education experience</label>
<input list="edu" id="edu" name="education">
<datalist id="edu">
<option value="jsc">jsc</option>
<option value="ssc">ssc</option>
<option value="hsc">hsc</option>
<option value="etc">etc</option>
</datalist>
<br>
<label for="uni">university/institute name</label>
<input type="text" id="uni" name="uni">
<br>
<label for="yoe">years of experience</label>
<input type="number" id="yoe" name="yoe">
<br>
<label for="skill">skills</label><br>
<input type="checkbox" name="skills" id="html">
<label for="html">html</label>
<input type="checkbox" name="css" id="css">
<label for="css">css</label>
<input type="checkbox" name="skills" id="javascript">
<label for="javascript">javascript</label>
<input type="checkbox" name="skills" id="etc">
<label for="etc">etc</label>

<br>
<h2><u>resume upload</u></h2>
<br>
<input type="file" name="resume" id="resume">
<br>
<br>
<br>
<input type="checkbox" name="correction" id="correction" required>
<label for="correction">confirm that all the information provided is correct</label>
<br>
<br>
<input type="submit">
<input type="reset">
    </form>








</body>


</html>
