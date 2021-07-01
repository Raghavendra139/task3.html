# task3.html
forms<!DOCTYPE html>
<html>
<head>
<title>FORMS</title>
</head>
<body>
<form action="#" method="post">
<h2>Register</h2>
<label>First Name:</label><br>
<input type="text" name="fname" placeholder="Enter Firt Name"/><br>
<label>Last Name:</label><br>
<input type="text" name="lname" placeholder="Enter Firt Name"/><br>
<label>Email:</label><br>
<input type="Email" name="Email" placeholder="Enter Email"/><br>
<label>Password:</label><br>
<input type="password" name="pwd" placeholder="Enter Password"/><br>
<label>Confirm Password:</label><br>
<input type="password" name="confirm pwd" placeholder="Re-enter Password"/><br>
<label>Gender:</label><br>
<input type="radio" name="Gender" value="Male"/>Male
<input type="radio" name="Gender" value="Female"/>Female
<input type="radio" name="Gender" value="Others"/>Others
<label>Submit</label><br>
<input type="submit" name="submit"/>
</form>
<hr>
<form action="#" method="post">
<fieldset style="width:25%">
<h2 align="center">Novell services Login</h2>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<label>Username:</label>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<input type="username"name="username"placeholder="Enter Username"><br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<label>Password:</label>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<input type="password"name="pwd"placeholder="Enter Password"><br><br>
&nbsp;<label>City of Employment:</label>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<input type= "text"name="COE" placeholder="City"/><br><br>
webserver:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<select name="top down">
<option value="choose a server">-choose a server-
</select><br><br>
Please specify Your role:&nbsp;&nbsp;
<input type="radio" name="role" value="Admin"/>Admin<br>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<input type="radio" name="role" value="Engineer"/>Engineer<br>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<input type="radio" name="role" value="Manager"/>Manager<br>&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<input type="radio" name="role" value="Guest"/>Guest<br>
Single Sign-on to the following:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<input type="checkbox"name="Mail"/>Mail<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<input type="checkbox"name="Payroll"/>Payroll<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<input type="Checkbox" name="Self-service"/>Self-serivce<br>
<center>
<input type="submit"name="submit"value="Login"/>
<input type="reset"/>
</center>
</fieldset>
</form>
<hr>
<form action="#" method="post">
<h2>Travel Reservation Form</h2><br>
<h3>*DenotesMandatory</h3>
<label>Full Name*:<label><br>
<input type="text"name="Full Name*"placeholder="Enter Full Name"/><br>
<label>Email Address*:<label><br>
<input type="email"name="Email"placeholder="Enter Email"/><br>
<label>Select Tour Package*:</label>
<br><select name="dropdown"><br>
<option value="Pondicherry">Pondicherry</option>
<option value="Goa">Goa</option><br></select><br>
Arrival date*:<br>
<input type="datetime-local"/><br>
Number of Persons*:<br>
<input type="number"name="number"placeholder="UNKNOWN_TYPE"/><br>
What would You want to avail*:<br>
<input type="checkbox"name="Boarding"/>Boarding<br>
<input type="checkbox"name="Fooding"/>Fooding<br>
<input type="checkbox"name="Sight seeing"/>Sight seeing<br>
Discount Coupon Code:<br>
<input type="number"name="coupon code" placeholder="UNKNOWN_TYPE"/><br>
Terms and Conditions*:<br>
<input type="radio"name="TOC" value="I Agree"/>I Agree<input type="radio"name="TOc"value="I Disagree"/>I Disagree<br>
<input type="submit"name="complete"value="complete reservation"/>
</form>
<hr>
</form action="#" method="post">
<h2><font face="italic"size="2">please,fill the form.Required fields marked</font><font color="red"size="2">*</font></h2>
<br>
<fieldset style="width:25%">
<legend>Contact information</legend><br>
<label>Name<font color="red"size="2">*</font><label>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<input type="text"name="Name"/><br><br>
<label>Telephone<font color="red"size="2">*</font><label>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<input type="tel"name="telphone"/><br><br>
<label>Email<font color="red"size="2">*</font><label>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<input type="email"name="email"/>
</fieldset>
</form>
<form action="#"method="post">
<fieldset style="width:25%">
<legend>Personal information</legend><br>
<label>Age<font color="red"size="2">*</font><label>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<input type="number"name="Age*"/><br><br>
Gender:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<select name="dropdown">
<option value="Male">Male</option>
<option value="Female">Female</option>
</select><br><br>
List personal qulities:
<textarea rows="1" cols="10"></textarea>
</fieldset>
</form>
<form action="#"method="post">
<fieldset style="width:25%">
<legend>choose from the list</legend>
<input type="checkbox"name="CSS"/>CSS
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<input type="checkbox"name="HTML"/>HTML<br>
<input type="checkbox"name="JAVASCRIPT"/>JAVASCRIPT
&nbsp;&nbsp;&nbsp;&nbsp;
<input type="checkbox"name="PHP"/>PHP<br>
<input type="submit" value="submit information"style="width:38%">
</fieldset>
</form>
</body>
</html>
