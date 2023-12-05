<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Loan Information Form</title>
  <link rel="stylesheet" type="text/css" href="style.css"> 
</head>
<body bgcolor="pink">
    <center>
<form id="loanForm">
    <fieldset>
        <h1>Employee Loan Information Form</h1>
    </fieldset>
    <table align="center" height="80%" >
        
        <tr>
            <td><label for="employeeID">Employee ID:</label></td>
            <td><input type="text" id="employeeID" required></td>
        </tr>
        <br>
        <tr>
            <td><label for="name">Name:</label></td>
            <td><input type="text" id="name" required></td>
        </tr>
        <br>
        <tr>
            <td><label for="address">Address:</label></td>
            <td><input type="text" id="address" required></td>
        </tr>
        <br>
        <tr>
            <td><label for="designation">Designation:</label></td>
            <td><select id="designation" required>
                <option value="manager">Manager</option>
                <option value="employee">Employee</option>
              </select></td>
        </tr>
        <br>
        <tr>
            <td><label for="loanAmount">Loan Amount:</label></td>
            <td><input type="number" id="loanAmount" required></td>
        </tr>
        <br>
        <tr>
            <td><label for="loanDate">Date of Loan Taken:</label></td>
            <td><input type="date" id="loanDate" required></td>
        </tr>
        <br>
        <tr>
            <td><label for="interestRate">Interest Rate:</label></td>
            <td><input type="number" id="interestRate" required></td>
        </tr>
        <br>
        <tr>
            <td><label for="maturityDate">Maturity Date:</label></td>
            <td><input type="date" id="maturityDate" required></td>
        </tr>
        <br>
        <tr>
            <td>
                <button type="button" onclick="calculateLoan()">Calculate Loan</button>
            </td>
        </tr>       
</table>
</form>
</center>
<div id="result"></div>

<script src="script.js"></script>

</body>
