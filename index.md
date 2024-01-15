<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="<?php echo $_SERVER["PHP_SELF"];?>" method="post">
        First name: <input type="text" name="fName"><br>
        Surname: <input type="text" name="sName"><br>
        Student number: <input type="number" name="studentNum"><br>
        Group Id: <input type="text" name="groupId"><br>
        Course: <select name="course">
            <option value="web">Web coding</option>
            <option value="software">Software coding</option>
        </select><br>
        Beginning date of the course: <input type="date" name = "courseDate"><br>
        Teacher: <select name="teacher">
            <option value="Aki">Aki Savolainen</option>
            <option value="Henwiikka">Henwiikka</option>
            <option value="Hammerhead">Hammerlind Berry</option>
        </select><br>
        <input type="submit">
    </form>
</body>
<?php
if ($_SERVER["REQUEST_METHOD"] == "POST"){
    $msg = "Name: " . $_POST["fName"] . " " .  $_POST["sName"] . "<br>";
    $msg .= "Student number: " . $_POST["studentNum"] . "<br>";
    $msg .= "Group Id: " . $_POST["groupId"] . "<br>";
    $msg .= "Course: " . $_POST["course"] . "<br>";
    $msg .= "Teacher: " . $_POST["teacher"] . "<br>";
    $msg .= "Start date: " . $_POST["courseDate"] . "<br>";
    $msg .= "Teacher: " . $_POST["teacher"] . "<br>";
    
    //Sending email (doesn't work atm). When works change all "<br>":s to "\n" and remove code under.
    mail("someone@example.com","My subject",$msg);

    //Showing message on website because sending email doesn't work atm
    echo "<br>";
    echo $msg;
}
?>
</html>
