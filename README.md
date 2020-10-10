# cv
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Forms</title>
</head>
<body>
    <!-- FORMS -->
    <!-- This is a very important topic -->
    <h2>This is HTML form</h2>
    <!-- action tells where we have to submit the created form -->
    <form action="backend.php">
        <!-- like br tag div tag is also used to break the lines unlike br and span are inline elements div is a block element which means it take a whole line due to which element have to go into the next line *avoid br as much as possible in design-recommended*-->
        <label for="name">Name</label>
        <div>
            <!-- The name which is after the type is used for the backend purpose and specifying it helps us in telling the backend that from where we have to pickup and what to pickup -->
            <!-- There are many types of inputs are available some of them are:- text,date,checkbox,radiobutton,submit,time,number,reset -->
            <input type="text" name="myName" id="name">
        </div>
        <br>
        <label for="Role">Role</label>
        <div> 
            <!-- Label tag is used when we want to go to the box filling by selecting the text of that box -->
        <input type="text" name="myRole" id="Role">
        </div>
        <br>
        <label for="email">Email</label>
        <div> 
            <input type="email" name="myEmail" id="email">
        </div>
        <br>
        <label for="Date">Date</label>
        <div>
            <input type="date" name="myDate" id="Date">
        </div>
        <br>
        <label for="Bonus">Bonus</label>
        <div>
            <input type="number" name="myBonus" id="Bonus">
        </div>
        <br>
        <div>
            <label for="Age">Are you 18+</label>
            <input type="checkbox" name="myAge" id="Age">
        </div>
        <br>
        <div>
            Gender: male<input type="radio" name="myGender">Female: <input type="radio" name="myGender">other: <input type="radio" name="myGender">
        </div>
        <br>
        <div>
            <label for="car">Cars: </label>
             <select name="myCar" id="car">
                <option value="Indica">Indica</option>
                <option value="swf" selected>Swift</option>
                <option value="tata">Tata</option>
             </select>   
        </div>
        <br>
         <!--while using label tag remind that id should be that which you use in the label for tag it means that id value should be that value which you write in for value in label tag-->
         <!-- if you want that a particular option is already selected than we can use the selected tag after the option value  -->
        <div>
            <textarea name="my text" id="write about yourself" cols="60" rows="8"></textarea>
        </div>
        <br>
        <div> 
            <input type="submit" value="Submit now">
            <input type="reset" value="Reset Now">
        </div>
        <br>
    </form>
</body>
</html>
