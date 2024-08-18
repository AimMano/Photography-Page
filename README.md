*{
    margin: 0;
    padding: 0; 
    font-family: "poppins", sans-serif;
}
.main_box {
    background: url("photo.jpg");
    height: 100vh;
    background-size: cover;
}
.btn_one {
    color: white;
    font-size: 30px;
    font-weight: 700;
position: absolute;
left: 16px;
line-height: 60px;
}
.sidebar_menu{
    position: fixed;
     left: -300px; 
    height: 100vh;
    width: 300px;
    background-color: rgba(255, 255, 255, 0.1);
      box-shadow: 0 0 6px rgb(255, 255, 255,0.5);
      transition: all 0.2s linear;
}
.sidebar_menu .logo{
    position:  absolute;
    width: 100%;
    line-height: 60px;
    height: 60px;
    box-shadow: 0 2px 4px rgb(255, 255, 255,0.5);
}
.sidebar_menu .logo a{
position: absolute;
 left: 50px;
 color: white;
text-decoration: none;
font-size: 20px;
font-weight: 500;
}
.sidebar_menu .btn_two i{
    color: rgb(29, 161, 58);
    font-size: 25px;
    line-height: 60px;
    position: absolute;
    left: 275px;
}
.sidebar_menu .menu{
   position: absolute; 
   width: 100%;
   top: 80px;
}
.sidebar_menu .menu li{
    margin-top: 6px;
    padding: 14px 20px;
}
.sidebar_menu .menu i ,a{
    color: white;
    text-decoration: none;
    font-size: 20px;
}
.sidebar_menu .menu i{
    padding-right: 8px;
}
.sidebar_menu .social_media{
    position: absolute;
    left: 25%;
    bottom: 50px;
}
.sidebar_menu .social_media i{
    color: white;
    opacity: 0.5;
    padding: 0 5px;
}
#check{
display: none;
}
.sidebar_menu .menu li:hover{
box-shadow: 0 0 4px rgba(255,255, 255, 0.5);

}
.btn_ two i:hover{
    font-size: 40px;
}
.btn_one i:hover{
font-size: 40px;
}
.sidebar_menu .social_media i:hover{
opacity: 1;
transform: scale(1.6);
}
#check:checked~ .sidebar_menu{
left: 0;
}
#check:checked~ .btn_one i{
    opacity: 0;
}
#check:checked~ .sidebar_menu .btn_two i{
    opacity: 1;
}





