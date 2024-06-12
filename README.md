<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>cv</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.css" integrity="sha512-5A8nwdMOWrSz20fDsjczgUidUBR8liPYU+WymTZP1lmY9G6Oc7HlZv156XqnsgNUzTyMefFTcsFH/tnJE/+xBg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" type="text/css" href="style.css">
    
<style>
 @import url('https://fonts.googleapis.com/css?family=Poppins:200,300,400,500,600, 700,800,900&display=swap');
 *
 {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'poppins' , sans-serif;
 }

 body
 {
    background-color: lightblue;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
 }

 .container{
    position: relative;
    width: 100%;
    max-width: 1200px;
    min-height: 1000px;
    background: #fff;
    margin: 50px;
    display: grid;
    grid-template-columns: 1fr 2fr;
    box-shadow: 0 35px 55px rgba(0,0,0,0,1);

 }

 .container .left-side
 {
    position: relative;
    background: #003147;
    padding: 40px;
 } 

 .profile-text
 {
    position: relative;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-bottom: 20px;
    border-bottom: 1px solid rgba(255,255,255,0.2);
 }

 .profile-text .image
 {
    position: relative;
    width: 200px;
    height: 200px;
    border-radius: 50%;
    overflow: hidden;

 }

 .profile-text h2
 {
   color: #fff;
   font-size: 1.5em;
   margin-top: 20px;
   text-transform: uppercase;
   text-align: center;
   font-weight: 600;
   line-height: 1.4em;
 }

 .profile-text h2 span 
 {
   font-size: 0.8em;
   font-weight: 300;
 }

 .contactinfo
 {
   padding-top: 40px;
 }

 .title
 {
   color: #fff;
   text-transform: uppercase;
   font-weight: 600;
   letter-spacing: 1px;
   margin-bottom: 20px;
 }

 .contactinfo ul li{

   position: relative;
   list-style: none;
   margin: 10px 0;
   cursor: pointer;
 }

 .contactinfo ul li .icon
 {
   display: inline-block;
   width: 30px;
   font-size: 18px;
   color: #03a9f4;



 }

 .contactinfo ul li span
 {
   color: #fff;
   font-weight: 300;

 }

 .contactinfo.education li
 {
  margin-bottom: 15px;

 }

 .contactinfo.education h5
 {
   color: #03a9f4;
   font-weight: 500;

 }

 .contactinfo.education h4
 {
  color: #fff;
  font-weight: 300;
 }

 .contactinfo.education h4:nth-child(2)
 {
   color: #fff;
   font-weight: 500;
 }

 

 .container .right-side
 {
    position: relative;
    background: #fff;
    padding: 40px;
 } 

 .about
 {
  margin-bottom: 50px;
 }

 .about:last-child
 {
  margin-bottom: 0;

 }

 .title2
 {
  color: #003147;
  text-transform: uppercase;
  letter-spacing: 1px;
  margin-bottom: 10px;

  
 }
 p{
  color: #333;
  
 }

 .about .box
 {
  display: flex;
  flex-direction: row;
  margin: 20px 0;
 }

 .about .box .year-company
 {
  min-width: 150px;

 }

 .about .box .year-company h5
 {
  text-transform: uppercase;
  color: #848c90;
  font-weight: 600;

 }

 .about .box .text h4
 {
  text-transform: uppercase;
  color: #2a7da2;
  font-size: 16px;
 }

 .skill .box
 {
  position: relative;
  width: 100%;
  display: grid;
  grid-template-columns: 150px 1fr;
  justify-content: center;
  align-items: center;
 }

 .skill .box h4
 {
  text-transform: uppercase;
  color: #848c99;
  font-weight: 500;

 }

 .skill .box  .percent
 {
  position: relative;
   width: 100%;
   height: 10px;
   background: #f0f0f0 ;
   
 }

 .skill .box .percent div 
 {

  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  background: #077fb3;
 }

 .interest ul
 {
  display: grid;
  grid-template-columns: repeat(4,1fr);

 }

 .interest ul li
 {
  list-style: none;
  color: #333;
  font-weight: 500;
  margin: 10px 0;

 }

 .interest ul li .fa 
 {
   color: #03a9f4;
   font-size: 18px;
   width: 20px;
 }

 @media (max-width: 1000px)
 {
  .container
  {
    margin: 10px;
    grid-template-columns: repeat(1,1fr);


  }
  .interest ul 
  {
    grid-template-columns: repeat(1,1fr); ;
  }
 }



    </style>


</head>

<body>

    <div class="container">
        <div class="left-side">
            <div class="profile-text">
                <div class="image">
                    <img src="profile.jpeg" width="200px">
                </div>
                <h2>Muhammad muzammil<br><span>Web Devoloper</span></h2>
            </div>

            <div class="contactinfo">
                <h3 class="title">Contact Info</h3>
                <ul>
                    <li>
                        <span class="icon"><i class="fa fa-phone" aria-hidden="true"></i></span>
                        <span class="text">03144077222</span>
                    </li>
                    <li>
                        <span class="icon"><i class="fa fa-envelope" aria-hidden="true"></i></span>
                        <span class="text">muzammilnaveed41@gmail.com</span>
                    </li>
                    <li>
                        <span class="icon"><i class="fa fa-globe" aria-hidden="true"></i>
                        </span>
                        <span class="text">www.muzammil.com</span>
                    </li>
                    <li>
                        <span class="icon"><i class="fa fa-linkedin" aria-hidden="true"></i>
                        </span>
                        <span class="text">www.linkdin.com</span>
                    </li>
                    <li>
                        <span class="icon"><i class="fa fa-map-marker" aria-hidden="true"></i>
                        </span>
                        <span class="text">karachi,Sindh Pakistan</span>
                    </li>
                </ul>
            </div>

            <div class="contactinfo education">
                <h3 class="title">Education</h3>
                <ul>
                    <li>
                        <h5>2020-2024</h5>
                        <h4>bachelor in software engineering</h4>
                        <h4>Iqra University Main Campus</h4>
                    </li>

                    <li>
                        <h5>2018</h5>
                        <h4>Matriculation </h4>
                        <h4>The City School</h4>
                    </li>

                    <li>
                        <h5>2020</h5>
                        <h4>Intermediate</h4>
                        <h4>Pak-Turk Maarif International School And Colleges</h4>
                    </li>
                    
                </ul>
            </div>

        </div>
        <div class="right-side">
            <div class="about">
                <h2 class="title2">Profile</h2>
                <p>hello</p>
            </div>
            <div class="about">
                <h2 class="title2">Experience</h2>
                <div class="box">
                    <div class="year-company">
                        <h5>2024-Present</h5>
                        <h5>Company name</h5>
                    </div>
                    <div clas="text">
                       <h4>Web developer</h4>
                       <p>write description here</p>
                    </div>
                </div>
            </div>

            <div class="about skill">
                <h2 class="title2">Professional Skills</h2>
                <div class="box">
                    <h4>Html</h4>
                    <div class="percent">
                        <div style="width: 100%;"></div>
                    </div>
                    
                    

                </div>
                <div class="box">
                    <h4>Css</h4>
                    <div class="percent">
                        <div style="width: 95%;"></div>
                    </div>

                </div>
                <div class="box">
                    <h4>Html</h4>
                    <div class="percent">
                        <div style="width: 95%;"></div>
                    </div>

                </div>
                <div class="box">
                    <h4>JavaScript</h4>
                    <div class="percent">
                        <div style="width: 95%;"></div>
                    </div>

                </div>

            </div>
            <div class="about interest">
                <h2 class="title2">Interest</h2>
                <ul>
                    <li><i class="fa fa-gamepad" aria-hidden="true"></i>Gaming</li>
                    <li><i class="fa fa-futbol-o" aria-hidden="true"></i>Cricket</li>
                    <li><i class="fa fa-book" aria-hidden="true"></i>Reading</li>
                    <li><i class="fa fa-film" aria-hidden="true"></i>Movies</li>
                </ul>
            </div>

        </div>
    </div>


    
</body>
</html>