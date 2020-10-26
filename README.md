<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forms</title>
    <style>
      *{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}
body{
    background-color: darkcyan;
}
.formContainer{
    margin-top: 20px;
    margin-left: 200px;
    background-color: darkgoldenrod;
    width: 200%;
    padding: 14px 22px;
}
.container{
      margin-left: 300px;
      
      
}
input[type=text], select {
    font-size: 12px;
    width: 100%;
    padding: 12px 20px;
    margin: 7px 0;
    display: block;
    border: 1px solid #ccc;
    border-radius: 4px;
    background: whitesmoke;
  }
  button {
    background-color: #4CAF50;
    color: white;
    padding: 8px 9px;
    margin: 4px 0;
    border: none;
    cursor: pointer;
    width: 20%;
    opacity: 0.9;
    
  }
  button:hover {
    opacity:1;
  }
  
  .cancelbtn {
    padding: 8px 9px;
    background-color: #f44336;
  }
  .cancelbtn, .signupbtn {
    float: middle;
    width: 10%;
  }
 </style>
</head>
<body>
    <form>
        <div class="formContainer">
        <h1>Sign Up Form</h1>
        
        </div>
        <br>
        <div class="container">
        <label for="fname">First Name</label>
  <input type="text" id="fname" name="firstname" placeholder="Your name..">
  </div>
<br>
  <div class="container">
<label for="lname">Last Name</label>
  <input type="text" id="lname" name="lastname" placeholder="Your last name..">
  </div>
<br>
<div class="container">
<label for="sname">Screen Name</label>
  <input type="text" id="sname" name="screenname" placeholder="Your screen name..">
  </div>
<br>
<div class="container">
<label for="email">Email Id</label>
  <input type="text" id="email" name="email" placeholder="Your email..">
</div>
<br>
<div class="container">
    Data : <input type="date"name="myDate">
</div>
<br>
<div class="container">
<label for="Password">Password</label>
  <input type="text" id="Password" name="Password" placeholder="Your Password..">
</div>
<br>
<div class="container">
<label for="CPassword">Confirm Password</label>
  <input type="text" id="CPassword" name="CPassword" placeholder="Your CPassword..">
</div>
<br>
<div class="container">
<label for="Phone">Phone</label>
  <input type="text" id="Phone" name="Phone" placeholder="Your Phone..">
</div>
<br>
<div class="container">
    Gender : Male<input type="radio"name="myGender">
                 Female<input type="radio"name="myGender">
<br>
</div>
<br>
<div class="container">
  <label for="country">Country</label>
  <select id="country" name="country">
    <option value="australia">Australia</option>
    <option value="canada">Canada</option>
    <option value="india">India</option>
    <option value="usa">USA</option>
    <option value="UA">UA</option>
  </select>
</div>
<br>
<div class="container">
    <button type="button" class="cancelbtn">Cancel</button>
       <button  type="submit" class="signupbtn">Submit</button>
     </div>
     </div>   
</form>
</body>
</html>
