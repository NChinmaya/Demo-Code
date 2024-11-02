# Demo-Code
This is my first Git Repository.
<br>
Author - Chinmya Nayak

<!DOCTYPE html>
<html lang="en">
<head>
<title>DIPLOMA Examination Registration Form</title>
</head>
<body bgcolor="yellow">
    
        <h1 style="background-color:rgba(0, 255, 255, 0.819);color:red">CSE Examination Registration</h1>
    
<form action="/submit_registration" method="POST">
<fieldset>
<legend>Personal Information</legend>
<label for="full-name">Full Name:</label><br>
<input type="text" id="full-name" name="full_name" required><br><br>`\<label for="dob">Date of Birth:</label><br>
<input type="date" id="dob" name="dob" required><br><br>
<label for="gender">Gender:</label><br>
<input type="radio" id="male" name="gender" value="male" required>
<label for="male">Male</label><br>
<input type="radio" id="female" name="gender" value="female">
<label for="female">Female</label><br>
<input type="radio" id="other" name="gender" value="other">
<label for="other">Other</label><br><br>
<label for="address">Address:</label><br>
<textarea id="address" name="address" rows="4" required></textarea><br><br>
<label for="contact-number">Contact Number:</label><br>
<input type="tel" id="contact-number" name="contact_number" required pattern="[0-
9]{10}"><br><br>
<label for="email">Email Address:</label><br>
<input type="email" id="email" name="email" required><br><br>
</fieldset>
<fieldset>
<legend>Examination Details</legend>
<label for="program">Choose Your Program:</label><br>
<select id="" name="program" required>
<option value="program1">DATA STRUCTURE</option>
<option value="program2">JAVA</option>
<option value="program3">HTML</option>
<option value="program4">CSS</option>
<option value="program5">JAVA SCRIPT</option>
</select><br><br>
<label for="course">Favorite subject</label>
<br>
<input type="text" id="branch" name="branch"><br><br>
<label for="subjects">Subjects:</label><br>
<input type="checkbox" id="DSA" name="subjects" value="DSA">
<label for="CSA">DSA</label><br>
<input type="checkbox" id="OOM" name="subjects" value="OOM">
<label for="DBMS">OOM</label><br>
<input type="checkbox" id="Architecture" name="subjects" value="Architecture">
<label for="OS">Architecture</label><br>
<input type="checkbox" id="Electronics" name="subjects" value="Electronics">
<label for="C++">Electronics</label><br><br>
</fieldset>
<input type="submit" value="Submit">
<p> THANK YOU</p>
</form>
</body>
</html>
-*
