<!DOCTYPE html>
<html lang="en">
<head>
   
    <title>Payment Form</title>
</head>
<body>
    <form action="">
        <h1>Payment Form</h1>
       
        <h2>Contact Information</h2>
        <p>Name: * <input type="text" name="name" required></p>
        <fieldset>
            <legend>Gender * </legend>
        <p>
             Male <input type="radio" name="gender" id="male" required> Female <input type="radio" name="gender" id="female" required>
        </p>
        </fieldset>
        <p>Address:<textarea name="address" id="" cols="100" rows="8"></textarea></p>
        <p>Email: * <input type="email" name="email" id="email" required></p>
        <p>Pincode: * <input type="number" name="pincode" id="pincode" required></p>
        <h2>Payment Information</h2>
        <p>Crad Type: *
            <select name="card_type" id="card_type" required>
               <option value="">--Select a Card Type--</option>
               <option value="Visa">Visa</option>
               <option value="Rupay">Rupay</option>
               <option value="Master Card">Master Card</option>
            </select>
        </p>
        <p>
            Card Number * <input type="number" name="card_number" id="card_number" required>
        </p>
        <p>
            Expiration Date: * <input type="date" name="exp_date" id="exp_date" id="exp_date"required>
        </p>
        <p>CVV * <input type="password" name="cvv" id="cvv" required></p>
        <input type="submit" value="Pay Now">
    </form>
    
</body>
</html>
