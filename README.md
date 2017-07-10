# Portfolio

<!DOCTYPE html>
<html>

<h1>ABOUT ME</h1>

<p>I am a rising junior at Los Gatos High School. I am involved in Yearbook, and currently hold the title as Editor. I enjoy all outdoor activities, including; boating, skiing, swimming, hiking, golfing and traveling. I love to write, design layouts, take pictures and spend time with my family. I am an organized, kind, helpful, passionate person. I am involved in many non-profit organizations, and enjoy giving my time on a weekly basis. I complete 100+ hours/year. I am also a technology guru. I love exploring new technology... and am quite good at it. As a detail-oriented person, I am currently working on more design projects, I enjoy graphic and interior design-- plus I have a great eye for colors and position. I live with my dad, mom, ll year-old sister Natalie and 2 orange tabbies, Oliver and Tigger. As a 16 year-old, I love to hangout with my friends, and have fun. I am currently interested i coding -- as it’s the now and the future. I enjoy using code, and have worked and produced many projects with the support of the Microsoft staff.

Thanks,

Hannah Lane</p>


<img src="http://www.mercurynews.com/wp-content/uploads/2016/10/slgw1014house01.jpg?w=486" alt="Helping Others" style="width:100px;height:100px;">

<img src="https://media.giphy.com/media/TKqXCyRwqf0DC/giphy.gif"/>

<img src="https://media.giphy.com/media/l0HFkso2E6ty4naCs/giphy.gif"/>

<style>
/* Popup container - can be anything you want */
.popup {
    position: relative;
    display: inline-block;
    cursor: pointer;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
}

/* The actual popup */
.popup .popuptext {
    visibility: hidden;
    width: 160px;
    background-color: #555;
    color: #fff;
    text-align: center;
    border-radius: 6px;
    padding: 8px 0;
    position: absolute;
    z-index: 1;
    bottom: 125%;
    left: 50%;
    margin-left: -80px;
}

/* Popup arrow */
.popup .popuptext::after {
    content: "";
    position: absolute;
    top: 100%;
    left: 50%;
    margin-left: -5px;
    border-width: 5px;
    border-style: solid;
    border-color: #555 transparent transparent transparent;
}

/* Toggle this class - hide and show the popup */
.popup .show {
    visibility: visible;
    -webkit-animation: fadeIn 1s;
    animation: fadeIn 1s;
}

/* Add animation (fade in the popup) */
@-webkit-keyframes fadeIn {
    from {opacity: 0;} 
    to {opacity: 1;}
}

@keyframes fadeIn {
    from {opacity: 0;}
    to {opacity:1 ;}
}
</style>
</head>
<body style="text-align:center">

<h2>Popup</h2>

<div class="popup" onclick="myFunction()">Click me to toggle the popup!
  <span class="popuptext" id="myPopup">A Simple Popup!</span>
</div>

<script>
// When the user clicks on div, open the popup
function myFunction() {
    var popup = document.getElementById("myPopup");
    popup.classList.toggle("show");
}
</script>


</body>
</html>
