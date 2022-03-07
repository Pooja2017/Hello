<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <title>Next Website</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            font-family:'poppins' sans-serif;
             box-sizing: border-box;
        }
        .hero{
            width: 100%;
            height: 100vh;
            background-image: linear gradient(0,0,0,0.7),#3551b5 ,url(feature.png);
            background-color: rgb(255, 115, 0);
            background-size: cover;
            background-position: center;
            font-family: sans-serif;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        form{
            width: 90%;
            max-width: 600px;
        }
        .input-group{
            margin-bottom: 30px;
            position: relative;
        }
        input,textarea{
            width: 100%;
            padding: 10px;
            outline: 0;
            border: 1px solid #fff;
            color: #fff;
            background: transparent;
            font-size: 15px;
        }
        label{
            height: 100%;
            position: absolute;
            left: 0;
            top:0;
            padding: 10px;
            color: #fff;
            cursor: text;
            transition: 0.2s;
        }
        button{
            padding: 10px 0;
            color: #fff;
            outline:none;
            background: transparent;
            border:1 px solid #fff;
            width:100% ;
            cursor: pointer;
        }
        input :focus~label{
            top:-35px;
            font-size: 14px;
        }

    </style>
</head>
<body>
    
    <div class="hero">
       <form >
           <div class="input-group">
               <input type="text"  id="name" required>
               <label for="name">Your name</label>
          </div>
          <div class="input-group">
            <input type="text"  id="number" required>
            <label for="number">Phone Number</label>
       </div>
       <div class="input-group">
        <input type="email"  id="email" required>
        <label for="email">Email-id</label>
   </div>
   <div class="input-group">
    <textarea id="message" rows="8"></textarea>
    <label for="message">Your message</label>
</div>
<button type="submit">SUBMIT</button>
       </form>
    </div>
</body>
</html>
