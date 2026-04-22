<!DOCTYPE html>
<html>
<head>
    <title>Brew & Bean Cafe</title>
</head>

<body>

<h1 align="center">Brew & Bean Cafe</h1>
<p align="center">Fresh Coffee • Cozy Vibes • Perfect Moments</p>

<hr>

<form>

<fieldset>
    <legend><b>Customer Information</b></legend>

    <table cellpadding="8">
        <tr>
            <td>Name:</td>
            <td><input type="text" placeholder="Enter your name"></td>
        </tr>

        <tr>
            <td>Mobile:</td>
            <td><input type="text" placeholder="Enter mobile number"></td>
        </tr>
    </table>
</fieldset>

<br>

<fieldset>
    <legend><b>Menu Selection</b></legend>

    <table border="1" cellpadding="10" cellspacing="0" align="center">
        <tr>
            <th>Item</th>
            <th>Price ($)</th>
            <th>Select</th>
            <th>Quantity</th>
        </tr>

        <tr>
            <td>Coffee</td>
            <td align="center">3</td>
            <td align="center"><input type="checkbox"></td>
            <td align="center"><input type="number" value="1" min="1"></td>
        </tr>

        <tr>
            <td>Latte</td>
            <td align="center">5</td>
            <td align="center"><input type="checkbox"></td>
            <td align="center"><input type="number" value="1" min="1"></td>
        </tr>

        <tr>
            <td>Sandwich</td>
            <td align="center">4</td>
            <td align="center"><input type="checkbox"></td>
            <td align="center"><input type="number" value="1" min="1"></td>
        </tr>

        <tr>
            <td>Cookie</td>
            <td align="center">2</td>
            <td align="center"><input type="checkbox"></td>
            <td align="center"><input type="number" value="1" min="1"></td>
        </tr>
    </table>
</fieldset>

<br>

<table align="center" cellpadding="10">
    <tr>
        <td><input type="submit" value="Place Order"></td>
        <td><input type="reset" value="Clear"></td>
    </tr>
</table>

</form>

</body>
</html>
