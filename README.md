# form1.github.io
Hii this is Apalak Rajesh
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forms</title>
    <body>
        <h2>This is the Form you have to fill and give the screenshot to Apalak</h2>
        <form action="backend.php">
            <!--label is used for clicking the desired heading of form to directly came under the block insted of clicking the block-->
            <label for="name"> Name</label>
            <!--Input tag is used to take input-->
            <div>
                <!--Here input is in form of text-->
                 <input type="text" name="myName" id="name">
            </div>
            <br>
            
            <div>
               Relation with Apalak<input type="text" name="myRole">
            </div>
            <br>
            
            <div>
                 Friendship level with Apalak<input type="email" name="myEmail">
            </div>
    
            <br>
            
            <div>
                <!--here input is in form of calander-->
                Date of Birth: <input type="date" name="myDateofbirth ">
            </div>
            <br>
        
          <!-- <div>
                 <input type="number" name="mySalary">
            </div>
            <br>
            
            <div>
                here input is checkbox so html creates a checkbox and using checked at the end means it is checked by defalut-->
                <!--Are u Eligible?:<input type="checkbox" name="myEligibility" checked>-->
            </div>
            <br>
            <div>
                <!--Radio input is for select between options--> 
                Gender: Male <input type="radio" name="myGender"> Female <input type="radio" name="myGender">
                Other <input type="radio" name="myGender">
            </div>
    
            <br>
            
            <div>
                
                <!--Here textarea creates a text box with no.of column and rows written as per the attributes cols and rows respectively-->
                    Write what is bad and good in Apalak <br><textarea name="myText" cols="90" rows="10"></textarea>
            </div>
    
            <br>
            <div>
                <!--slect is for selection -->
                   Is he smart or not <select name="myCar" id="car">
                    <!--options are provdided under selections you wantnand for by default selection use selected  -->
                    <option value="no">no </option>
                    <option value="yes"selected>yes</option>
                </select>
            </div>
            <br>
    
            <div></div>
            <!--here type sumbit for submission of form and type reset for reset form-->
                <input type="submit" value="Submit Now">
                <input type="reset" value="Reset Now">
            </div>
        </form>
    </body>
    
    </html>
</head>
<body>
    
</body>
</html>
