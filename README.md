# Stack
Creating stack
<html>
<script>
function calc(a)
{
if(a.elements[2].checked)
{
a.result.value=a.entry.value*a.exit.value;
}
if(a.elements[4].checked)
{
a.result.value=a.entry.value-a.exit.value;
}
if(a.elements[5].checked)
{
a.result.value=a.entry.value/a.exit.value;
}

}
</script>

<body>

<h1 align="center">Maths calculation</h1>
<form>
<center>
<table>
<tr>
<td>Enter first value</td>
<td>
<input type="text" value="0" name="entry"></td>
<td>Enter second value</td>
<td>
<input type="text" value="0" name="exit"></td>
</tr>
<tr>
<td>Action</td>
<td>
<input type="radio"  name="action" onclick="calc(this.form);">Double
<br>

<input type="radio" name="action" onclick="calc(this.form);">Subtract
<br>

<input type="radio" name="action" onclick="calc(this.form);">Divison
<br>

</td>
</tr>
<tr>
<td>
 Result:
</td>
<td><input type="text" name="result" onfocus="this.blur();"></td></tr>
</table>
</center>
</body>
</html>

