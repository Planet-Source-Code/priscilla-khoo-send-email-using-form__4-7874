<div align="center">

## Send email using form


</div>

### Description

send email. Feell free to give comments. Please vote for me thanks
 
### More Info
 
sends email


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Priscilla Khoo](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/priscilla-khoo.md)
**Level**          |Beginner
**User Rating**    |3.0 (6 globes from 2 users)
**Compatibility**  |VbScript \(browser/client side\)

**Category**       |[Controls/ Forms/ Dialogs/ Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/controls-forms-dialogs-menus__4-3.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/priscilla-khoo-send-email-using-form__4-7874/archive/master.zip)





### Source Code

```
<html>
<head>
/* Done by Priscilla Khoo */
<title>User Information!</title>
<script language = "VBScript">
<!--
Sub cmdSubmit_onClick
' Submit this form for processing.
 MsgBox "Your form has been submitted."
 Document.frmUserInformation.Submit
End Sub
-->
</script>
</head>
<body>
<h1> User Information!</h1>
<Form Name = "frmUserInformation" Action = "MAILTO:yupi_girl@hotmail.com" Method = "post" enctype = "text/plain" >
<table>
<tr>
<td><b>User Name:</b></td>
<td><Input Type = "Text" Name = "txtUserName" Size = 20></td>
</tr>
<tr>
<td><b>Email ID:</b></td>
<td><Input Type = "Text" Name = "txtEmailID" Size = 20></td>
</tr>
<tr>
<td><b>Address:</b></td>
<td><input Type = "Text" Name = "txtAddress" size = 20></td>
</tr>
<tr>
<td><b>Mobile No:</b></td>
<td><Input Type = "Text" Name = "txtMobileNo" Size = 20></td>
</tr>
<tr>
<td><INPUT TYPE="Submit" NAME="cmdSubmit" VALUE="Submit"></td>
</tr>
</table>
</Form>
</body>
</html>
```

