#HTML 
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <link href="https://fonts.googleapis.com/css?family=Encode+Sans+Expanded" rel="stylesheet">
  <link rel="stylesheet" type="text/css"  href="stylesheet.css">
</head>

<body>
   <h1> Lets create an ID card!</h1>

<h3>First Name:</h3>
 <input type="text" onfocus="this.value=''" id="FirstName" placeholder="FirstName"/><br>
 <h3>LastName:</h3>
    <input type="text" onfocus="this.value=''" id="LastName" placeholder="LastName"/><br>
    <h3>Age:</h3>
       <input type="number" onfocus="this.value=''" id="Age" placeholder="Age"/> <br>
       <h3>Phone Number:</h3>
         <input type="text" onfocus="this.value=''" id="PhoneNumber" placeholder="Phone Number"/><br>
         <h3>Address:</h3>
           <input type="Address" onfocus="this.value=''" id="Address" placeholder="Address"/><br>
    <button type="submit" onclick="IDcard()">get ID card</button>


    <div  id="idCard">
        <img id="img" src="http://www.iconninja.com/files/373/611/612/person-user-profile-male-man-avatar-account-icon.svg" />
            <h2 id="postFullName"></h2><br>
            <div4 id="idcontent">
            <p id="postAge"></p>
            <p id="postPhoneNumber"></p>
            <p id="postAddress"></p>
            </div4>

             </div>





  <script src="app.js"> </script>
</body>

</html>
