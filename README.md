<!DOCTYPE html>
<html>
<head>
  <title>Student Application Form</title>
</head>
<body>

  <h2>Student Application Form</h2>

  <form>
    <label>Full Name:</label><br>
    <input type="text" name="fullname"><br><br>

    <label>Date of Birth:</label><br>
    <input type="date" name="dob"><br><br>

    <label>Gender:</label><br>
    <input type="radio" name="gender" value="male"> Male<br>
    <input type="radio" name="gender" value="female"> Female<br><br>

    <label>Email:</label><br>
    <input type="email" name="email"><br><br>

    <label>Phone Number:</label><br>
    <input type="text" name="phone"><br><br>

    <label>Course:</label><br>
    <select name="course">
      <option value="btech">B.Tech</option>
      <option value="bsc">B.Sc</option>
      <option value="ba">B.A</option>
      <option value="bcom">B.Com</option>
    </select><br><br>

    <label>Address:</label><br>
    <textarea name="address" rows="4" cols="30"></textarea><br><br>

    <input type="submit" value="Submit">
  </form>

</body>
</html>
