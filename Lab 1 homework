<!DOCTYPE html>
<html>
<head> 
    <meta charset="UTF-8">
    <title>Page Title Here</title>
    <script type="text/javascript">
        // Prompt the user for information
        var fullName = prompt("Please enter your full name:", "No Name");
        var address = prompt("Please enter your address:", "No Address");
        var city = prompt("Please enter your city:", "London");
        var province = prompt("Please enter your province:", "Ontario");
        var accountBalance = parseFloat(prompt("Please enter your account balance:", "0.0"));

        // Calculate penalty based on account balance
        var penalty = 0;
        if (accountBalance > 0 && accountBalance < 1000) {
            penalty = accountBalance * 0.02;
        } else if (accountBalance >= 1000) {
            penalty = accountBalance * 0.03;
        }

        // Calculate total amount owing
        var totalAmountOwing = accountBalance + penalty;

        // Output the information and total amount owing
        document.write("<h1>Customer Information:</h1>");
        document.write("<p>Full Name: " + fullName + "</p>");
        document.write("<p>Address: " + address + "</p>");
        document.write("<p>City: " + city + "</p>");
        document.write("<p>Province: " + province + "</p>");
        document.write("<p>Account Balance: $" + accountBalance.toFixed(2) + "</p>");
        document.write("<h1>Penalty:</h1>");
        document.write("<p>Penalty Amount: $" + penalty.toFixed(2) + "</p>");
        document.write("<h1>Total Amount Owing:</h1>");
        document.write("<p>Total Amount Owing: $" + totalAmountOwing.toFixed(2) + "</p>");

        // If account balance is zero, display a message
        if (accountBalance === 0) {
            document.write("<h2>Thank-you for your payment</h2>");
        }
    </script>
</head>
<body>
</body>
</html>
