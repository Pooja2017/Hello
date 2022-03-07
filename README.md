<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
  <title>Document</title>
  <style>

 
  h2{
    text-align:left;
  }
  
 

  body{
    background-color:pink;
  }
  .websites{
   
    text-align:right;
    
  }
  .col1,.col2{
    flex-basis:50%;
  }
  </style>
</head>

</body>
<body>
  <div class ="websites">
  <a href="http://www.google.com">Google</a>
  <a href="http://www.Amazon.com">Amazon</a>
  <a href="http://www.Walmart.com">Walmart</a>
  <a href="http://www.Costco.com">Costco</a>
  </div>
    <h2>Register Here</h2>
  <label>UserName</label>
  <input placeholder="Enter UserName Here" type="text">
  </div>
  <label>Password</label>
  <input placeholder="Enter Your Password" type="password">
  <div>
  <p>Select Your Favorite Fruits</p>
  
    <input type="checkbox"/><label>Apple</label>
  <input type="checkbox"/><label>Mango</label>

  <input type="checkbox"/><label>Banana</label>

  <input type="checkbox"/><label>Strawberry</label>
  </div>
  <div>
  <p>Select Your Gender</p>
  <input type="radio"/><label>Male</label>
  <input type="radio"/><label>Female</label>
  </div>
  <p>Select Your Country</p>
  <select>
    <option value="USA">USA</option>
    <option value="IND">India</option>
    <option value="AUS">Australia</option>
  </select>

  
  <div>
  <button>Submit</button><button>Cancel</button>
  </div>
</body>
</html>
