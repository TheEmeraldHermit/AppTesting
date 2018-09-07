
<!DOCTYPE html>
<html>
<body>

<form action="">
Username: <input type="text" name="user"><br>
Password: <input type="password" name="password">
</form>

<p><b>Note:</b> The characters in a password field are masked (shown as asterisks or circles).</p>



<container direction="vertical" version="3" min-height="44" margin="3">
  <textfield name="User Name" height="40" label="User Name" margin="20" placeholder="Please Enter Your User Name" showclearbutton="true" halign="center" id="CA563B97-739C-70B4-F61E-3E1D858B573B" binding="Dataprovider1.user_name"></textfield>
  <textfield type="hidden" name="Password" height="40" label="Password" margin="20" placeholder="Please Enter Your Password" showclearbutton="false" halign="center" id="9445F156-0A06-E45F-493E-A71A32253A67" binding="Dataprovider1.text_field"></textfield>
  <button name="btnSubmit" width="120" value="Submit" height="44" label="" fontsize="14" margin="20" valign="right" size="14" halign="Center"></button>
</container>
  </body>
</html>
