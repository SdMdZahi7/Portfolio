# Portfolio
## AIM:
To create a portfolio using HTML and CSS

## ALGORITHM:
Set up the basic structure of your HTML document.

Create a CSS file named "styles.css" and link it to your HTML document. This file will contain the CSS rules for styling your portfolio.

Design the layout of your portfolio using HTML elements such as < header >, < nav >, < section >, < article >, and < footer >. Use appropriate classes or IDs to style these elements later with CSS.

Add a header section to display your name or the title of your portfolio.

Add images or media to enhance your portfolio. You can use the  tag to display images and embed videos or other media using appropriate HTML tags.

Apply responsive design techniques to ensure your portfolio looks good on different devices and screen sizes. Use CSS media queries to adjust the layout and styling as needed.

Apply CSS styling to your portfolio elements by targeting their respective classes or IDs in the "styles.css" file. Customize the colors, fonts, spacing, and other visual properties to match your desired design.

## CODE:
### HTML CODE:
~~~
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Portfolio</title>
        <link rel="stylesheet" href="zahi.css">
    </head>
    <body style="background-color: rgb(255, 255, 255);font-size:0px;">
        <center>
            <img src="zahi1.png" alt="pic1" style="height:800px; width:1400px">
            <div class="A">
                <p>PORTFOLIO</p>
            </div>
            <div class="B">
                <p>_______________________________________</p>
            </div>
            <div class="bb">
                <p>Syed Muhammed Zahi</p>
            </div>
            <div>
                <img src="zahi2.png" alt="pic2" style="height:800px; width:1400px">
                <div class="C">
                    <p>About me</p>
                </div>
                <div class="D">
                    <p>Student in Artificial Intelligence & Data Science.<br/>
                    I consider myself responsible and hardworking person.I am a <br/>mature team
                     worker and adaptive to the working environment.<br/>
                  Looking forward to take part in AI related projects. </p>
                </div>
                <div class="E">
                    <p>Carrier Objective</p>
                </div>
                <div class="F">
                    <p>To work in a challenging environment that provides ground to<br/>
                         implement my expertise and creativity to attain a high rank in the company<br/>
                          as well as in the society.</p>
                </div>
            </div> 
            <div>
                <img src="zahi3.png" alt="pic2" style="height:800px; width:1400px">
               
                <div class="H">
                    <p><b>2021-2025</b></p>
                </div>
                <div class="h1">
                    <p><b>~SAVEETHA ENGINEERING COLLEGE</b></p>
                </div>
                <div class="h2">
                    <p><li>Bachelor of Technology</li></p>
                </div>
                <div class="h3">
                    <p>(Artificial Intelligence and Data<br>Science, in progress)</p>
                </div>
                <div class="I">
                    <p><b>2019-2021</b></p>
                </div>
                <div class="i1">
                    <p><b>~DEVI ACADEMY<br> SENIOR SECONDARY SCHOOL</b></p>
                </div>
                <div class="i2">
                    <p><li>Secondary School</li></p>
                    <p><li>Higher Secondary Schools</li></p>
                </div> 
            </div>  
            <div >
                <img src="zahi4.png" alt="pic4" style="height:800px; width:1400px">
                <div class="j1">
                    <p><u>Monolith Technologies</u></p>
                </div>
                <div class="j2">
                    <ol>- I had the chance to work with a team of<br/> four people during my internship under
                        the<br/> direction of Mr.Dheepan.</ol>
                    <ol>- We concentrated on learning about AR/VR<br/> gadgets and their application.</ol>
                    <ol>- Our primary endeavour involves making a<br/> contribution to a study whether
                        or not<br/> dopamine levels rise after engaging in<br/> virtual reality.</ol>
                </div>
            </div>
            <div >
                <img src="zahi5.png" alt="pic5" style="height:800px; width:1400px">
                <div class="K">
                    <p><b>Technical skills</b></p>
                </div>
                <div class="k1">
                    <li>C Programming</li><br/>
                    <li>Python</li><br/>
                    <li>Web Designing</li><br/>
                    <li>Product Development</li><br/>
                    <li>3D Printing</li><br/>
                    <li>Excel Sheet</li><br/>
                </div>
                <div class="L">
                    <p><b>Soft skills</b></p>
                </div>
                <div class="l1">
                    <li>Adaptivity</li><br/>
                    <li>Time Management</li><br/>
                    <li>Creative</li><br/>
                    <li>Problem Solving Skills</li><br/>
                    <li>Critical Thinking</li><br/>
                    <li>Self-motivated</li><br/>
                </div>
            </div>
            <div>
                <img src="last.jpg" alt="last" style="height:400px; width:1400px">
                <div class="M">
                    <p><b>Contact Information</b></p>
                </div>
                <div class="m1">
                    <p><b>Address :</b></p>
                    <p><b>Phone :</b></p>
                    <p><b>Email :</b></p>
                </div>
                
                <div class="m2">
                    <p>No.06/185c,Bharathidasan Street,Valluvarkottam,ch-87</p>
                    <p>9840377116</p>
                    <p>syedmuhammedzahi63@gmail.com</p>
                </div>
            </div>
        </center>
    </body>
</html>

~~~
CSS CODE:
~~~
.A
{
    position: absolute;
    font-size:100px;
    top: 250px;
    color: #000000;
    padding-left:700px;
    line-height: 0.4px;
}
.B
{
    position:absolute;
    font-size:30px;
    top:340px;
    color: black;
    padding-left:680px;

}
.bb
{
    position:absolute;
    font-size:25px;
    top:400px;
    color: black;
    padding-left:1100px;
}
.C
{
    position:absolute;
    font-size:70px;
    top:870px;
    color: #583533;
    padding-left:180px; 
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
.D
{
    position:absolute;
    font-size:30px;
    top:1000px;
    color: #000000;
    padding-left:280px;
    text-align-last: left;
}
.E
{
    position:absolute;
    font-size:70px;
    top:1150px;
    color:#583533;
    padding-left:180px; 
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
}
.F
{
    position:absolute;
    font-size:30px;
    top:1300px;
    color: #000000;
    padding-left:280px;
    text-align-last: left;
}

.H
{
    position:absolute;
    font-size:35px;
    top:1990px;
    color: #574b4b;
    padding-left:370px;
    text-align-last: left; 
}
.h1
{
    position:absolute;
    font-size:26px;
    top:2070px;
    color: #000000;
    padding-left:220px;
      
}
.h2
{
    position:absolute;
    font-size:28px; 
    top:2110px;
    color: #000000;
    padding-left:310px;
}
.h3
{
    position:absolute;
    font-size:25px;
    top:2157px;
    color: #000000;
    padding-left:255px;
}
.I
{
    position:absolute;
    font-size:35px;
    top:1990px;
    color: #574b4b;
    padding-left:910px;
    text-align-last: left; 
}
.i1
{
    position:absolute;
    font-size:26px;
    top:2066px;
    color: #000000;
    padding-left:800px;
      
}
.i2
{
    position:absolute;
    font-size:28px; 
    top:2145px;
    color: #000000;
    padding-left:850px;
    line-height: 0.5;
    text-align: left;
}

.j1
{
    position:absolute;
    font-size:30px; 
    top:2620px;
    color: #000000;
    padding-left:910px;
    line-height: 0.5; 
}
.j2
{
    position:absolute;
    font-size:25px; 
    top:2690px;
    color: #000000;
    padding-left:800px;
    text-align-last: left; 
}
.K
{
    position:absolute;
    font-size:40px; 
    top:3350px;
    color: #000000;
    padding-left:800px;
    
}
.k1
{
    position:absolute;
    font-size:25px; 
    top:3450px;
    color: #000000;
    padding-left:820px;
    text-align: left;
    line-height:15px;
    
}
.L
{
    position:absolute;
    font-size:40px; 
    top:3620px;
    color: #000000;
    padding-left:800px;
    
}
.l1
{
    position:absolute;
    font-size:25px; 
    top:3720px;
    color: #000000;
    padding-left:820px;
    text-align: left;
    line-height:15px;   
}
.M
{
    position:absolute;
    font-size:45px;
    top:4000px;
    color: #000000;
    padding-left:220px;
    text-align: left;   
}
.m1
{
    position:absolute;
    font-size:25px; 
    top:4100px;
    color: #000000;
    padding-left:320px;
}
.m2
{
    position:absolute;
    font-size:25px; 
    top:4100px;
    color: #000000;
    padding-left:430px;
    text-align: left;
}
~~~
## OUTPUT:
![image](https://github.com/SdMdZahi7/Portfolio/assets/94187572/2c25f80f-b50b-47dc-b1e4-61371a0b3f87)
![image](https://github.com/SdMdZahi7/Portfolio/assets/94187572/ca8aae18-1904-4a16-8296-17b3096ca9f1)
![image](https://github.com/SdMdZahi7/Portfolio/assets/94187572/4da59dd7-9051-43ad-b839-7cfc7b9468fc)
![image](https://github.com/SdMdZahi7/Portfolio/assets/94187572/e084e8bd-8636-4afc-9822-d0ae99d2817a)
![image](https://github.com/SdMdZahi7/Portfolio/assets/94187572/d5da9f78-5355-40b4-9e76-299a1251a2fe)
![image](https://github.com/SdMdZahi7/Portfolio/assets/94187572/fd8bcde1-abeb-4816-9574-592253ac6034)


## RESULT:
Thus, a Portfolio is created using HTML and CSS.
