# EXP 02 - CREATING A COMMERCIAL WEBSITE USING HTML & CSS
## AIM:

To create a commercial website using html and css.

## SOFTWARE:

Visual Studio Code.

## ALGORITHM:

1) Create a new HTML file and save it with a .html extension.Begin with the basic structure by adding the <!DOCTYPE html> declaration at the top.
2) Set up the Head:

       Inside the <head> element, add the <title> element and give it a meaningful title for your website.
       Link your CSS file by adding the <link> element with the rel attribute set to "stylesheet" and 
       the href attribute pointing to your CSS file.

3) Develop the Content:

        Divide the main content area into sections using appropriate HTML elements like <section>, <div>, or <article>.
        Use headings <h1> to <h6> to structure your content hierarchically.
        Incorporate text, images, videos, and other media within the content sectionS


4) Style with CSS:
 
  Create a new CSS file and save it with a .css extension.
  Select the elements you want to style using CSS selectors.
  Apply styles using properties and values. 
  For example, you can change colors, fonts, sizes, margins, and padding.

5) Find a web hosting provider to host your website online.
Upload your HTML, CSS, and any other necessary files to the hosting server.

6) Test your website again after deployment to ensure it works as intended.
  
## PROGRAM:
  
### HTML CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Ice Cream</title>
  <link rel="stylesheet" href="temp.css">
</head>
<body  style="background-color: rgb(255, 250, 250);font-size:0;" >
        <center>
            <div class="bo">
                <img src="mainpic.jpg" alt="mainpic" style="width:70%;height:450;">
                <div class="text">    
                    <h1 style="font-size:65px; color:rgb(255, 255, 255) ">SOY MILK ICE</h1> 
                </div>
            </div>
            <div class="bo">
              <img src="blank.jpg" alt="blank"style="width:70%;height:250;">
              <div class="btext">
                <p style="padding-right:665px;"><b>Sherbet</b></p>
              </div>
              <div class="btext">
                <p style="padding-right:370px;"><b>Gelato</b></p>
              </div>
              <div class="btext">
                <p style="padding-left:400px;"><b>Ice Cream</b></p>
              </div>
            </div>
            <div class="bo">
              <img src="mainpic2.jpg" alt="mainpic2" style="width:70%;">
              <div class="dtext">
                <p style="padding-right:465px;color:rgb(158, 36, 119); ">Popsticks<br/>Scoops</p>
              </div>
              <div class="dtext">
                <p style="padding-right:150px;color:rgba(66, 95, 33, 0.854) ;">Rolls<br/>Cones</p>
              </div>
              <div class="sep">
                <p>Soft serve<br/>Rolls</p>
              </div>>
            </div>
            <div class="bo">
              <img src="pic33.jpg" alt="mainpic3" style="width:70%;height:50;">
              <div class="cen">
                  <p><b>FLAVORS</b></p>
              </div>
              <div class="menu">
                <ol>Cappuccino</ol>
                <ol>Pistachio</ol>
                <ol>Belgian vanilla</ol>
                <ol>Strawberry</ol>
                <ol>Lemon sorbet</ol>
                <ol>Choco Hazelnut</ol>
                <ol>Peanut Butter</ol>
                <ol>Peppermint</ol>
                <ol>Salted Caramel</ol>
              </div>
              
              
            </div>

            
        </center>
</body>  
```

### CSS CODE:
```      
.bod {
    margin: 0;
    font-family: Arial, sans-serif;
       
  }
.text{
  position: absolute;
  bottom: 550px;
  right: 20px;
  color: rgb(0, 0, 0);
  padding-left: 55px;
  padding-right: 480px;
} 
.btext
{
  position: absolute;
  top: 580px;
  font-size: 50px;
  bottom:600px;
  right:300px; 
} 
.dtext
{
  position: absolute;
  top: 860px;
  font-size: 30px;
  bottom:500px;
  right: 550px;
  font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif
}
.sep
{
  position: absolute;
  top: 860px;
  right:300px;
  font-size:30px;
  color: rgb(201, 144, 31); 
  font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.cen
{
  position:absolute;
  font-size:40px;
  padding-left:605px;
  bottom:-520px;
  color:rgb(0, 0, 0);
  line-height: 0.5;
}
.menu
{
  position:absolute;
  font-size:25px;
  padding-left:580px;
  bottom:-800px;
  color:rgb(0, 0, 0);
  line-height: 0.2;
  text-align: left;
}
.top
{
  position:absolute;
  font-family:monospace;
  font-size:35px;
  padding-left:640px;
  bottom:-950px;
  color:rgb(0, 0, 0);
  line-height: 0.5;
}
.topmenu
{
  position:absolute;
  font-family:'Times New Roman', Times, serif;
  font-size:30px;
  padding-left:510px;
  bottom:-1050px;
  color:rgb(0, 0, 0);
  line-height: 1.2;
  word-spacing: 10px;
}
```
## OUTPUT
 ![image](https://github.com/swethamohanraj/exp-2/assets/94228215/88ca27d5-c2e1-4878-9dfb-1d60988b421b)
![image](https://github.com/swethamohanraj/exp-2/assets/94228215/e2081945-c6d5-4d32-81aa-2eb209c34642)
![image](https://github.com/swethamohanraj/exp-2/assets/94228215/24af55d9-3e10-4847-803d-188efd9048f0)


## RESULT:
      
Thus the website is created.
