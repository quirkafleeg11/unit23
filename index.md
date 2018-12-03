<!DOCTYPE html>

<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login to MyGrades</title>
</head>
<body>
    <b><center><font size="24">Please login to MyGrades for Jamie Welch</font></center></b>
    <center><html>
<head>
    <title>Login Page</title>
</head>
<body style="font-family:Arial;">
    <form name="loginForm" method="post" action="login.php">
        <table width="20%" bgcolor="ffffff" align="center">

            <tr>
                <td colspan=2><center><font size=6><b>Login to MyGrades</b></font></center></td>
            </tr>

            <tr>
                <td>Username:</td>
                <td><input type="text" size=30 name="userid"></td>
            </tr>

            <tr>
                <td>Password:</td>
                <td><input type="Password" size=30 name="pwd"></td>
            </tr>

            <tr>
                <td><input type="Reset"></td>
                <td><input type="submit" onclick="return check(this.form)" value="Login"></td>
            </tr>

        </table>
    </form>
    <script language="javascript">
        function check(form) {

            if (form.userid.value == "welch" && form.pwd.value == "hazel-rah") {
                window.open('list.html')
                return true;
            }
            else {
                alert("That is incorrect. Please try again.")
                return false;
            }
        }
    </script>

    <footer>MyGrades Version 1.0, made with love in London by Jamie Welch Freelance Web Development. All rights reserved.</footer>
</body>
</html></center>
</body>
</html>
