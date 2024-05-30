<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <style>
        form{
            color: blue;
            /*background-image: url(./IMG_20240320_101307\ \(2\).jpg);*/
            
                
           /* background-size: cover;*/
           border-style: dashed solid double dotted ;
           border-width: 1cqmax;
           border-color: brown;
           border-radius: 2px 2px 2px 2px;
          /* margin: 0px 0px 0px 20px ;   */
          margin-left: 10px;   
          padding-left: 10px;
        }
    </style>
    
</head>
<body> 
    
    <form action="">
        <h1 align="center">Novell Service Login</h1>
        <table>
        <tr>
            <td>username</td>
            <td><input required type="text"></td>

        </tr>

        <tr>
            <td> password: </td>
            <td> <input type="password" name="" id=""></td>
        </tr>
        <tr>
           <td> city of<br>employment: </td> 
           <td><input type="text" name="" id=""></td>
        </tr>

        <tr>
           <td> web server:</td>
           <td>
            <select name="" id="">
                <option value="">--choose a server--</option>
            </select><br>
        </td>
        </tr>
        <br>
        <tr>
            <td>please specify<br>your role: </td>
            <td>
            <input type="radio" name="role" id="">
            admin <br>
            <input type="radio" name="role" id="">
            empbr <br>

            <input type="radio" name="role" id="">
            manager <br>
            <input type="radio" name="role" id="">
            guest
            </td>
        <tr>
        <tr>
            <td> single sign-on <br> to the following:</td>
            <td>
            <input type="checkbox" name="1" id="1">
            mail <br>
            <input required type="checkbox" name="1" id="1">
            payroll <br>
            <input type="checkbox" name="1" id="1">
            self service
            </td>
        </td>
        </tr>
        <tr>
            <td colspan="2" align="center"><input type="submit" value="Login">

           <input type="reset"></td>
        </tr>
    </table>
    <div><input type="file"></div>

    </form>
</body>
</html>
