<html>
<head>
<title>Password Required</title>

<script language="javascript" type="text/javascript">
<!--
<!--

function SubmitPassword(frm) {
    //
    // Get the value entered into the text box
    //
    var password = frm.pw.value
    //
    // Convert it to lowercase
    //
    password = password.toLowerCase()
    //
    // Add the .htm extension
    //
    var loc = password + ".htm"
    //
    // Make sure the user entered something
    //
    if (password != "")
    {
        //
        // If so, send the browser there
        //
        opener.location.href = loc
    }
    //
    // Close this window
    //
    window.close()
}

//-->
</script>

</head>
<body bgcolor="#cccccc">

<form>
This page requires a password:<br>
<input type="text" name="pw" size="15">
<input type="button" value="OK"
onClick="SubmitPassword(this.form)">
</form>

</body>
</html>
