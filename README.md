<html>
<head>
    <meta charset="UTF-8">
    <title>document</title>
    <style>
        * {
            border-size:border-box;
            margin: 0vw;
            padding: 0vw;
        }
        #load {
            position:fixed;
            height: 100%;
            width: 100%;
            background: #000000 url("https://miro.medium.com/max/1400/1*cD8WMb82cSXACDTG8mlWhw.gif") no-repeat center ;
            z-index: 9999;
        }
        body {
            font-family:serif;
            background:#ecf0f1;
            
        }
        .backpage {
            height: 10vw;
            width: 10vw;
            margin: -20vw 2vw;
        }
        .head {
            font-size:5vw;
            margin-left: 25vw;
            margin-top: -25vw;
            
        }
        .accordion {
            width: 50vh;
            margin: 2vh;
            background: #ffffff;
        }
        .accordion-taggle {
            display:none;
        }
        label {
            color:#fff;
            background: #EFC050;
            font-size:5vw;
            display:block;
            padding: 5vw 12px;
            position: relative;
            font-weight:bold;
            border-radius:2vw;
            border-top:5vw solid #ecf0f1;
            height: 30vw;
        }
        .icon {
            height: 20vw;
            width: 20vw;
            border-radius: 50%;
        }
        .accordion-content {
            height: 0vw;
            transition: all 0.5s;
            overflow:hidden;
            
        }
        .accordion-taggle:checked ~ .accordion-content {
            height: 70vw;
        }
        .aadhar_img {
            height: 30vw;
            width: 90vw;
            margin: 10vw 2vw;
        }
        .pan_img {
            height: 40vw;
            width: 90vw;
            margin: 5vw 2vw;
        }
        .voter_img {
            height: 45vw;
            width: 90vw;
            margin: 5vw 2vw;
        }
        a {
            text-decoration:none;
            color:white;
            
        }
        button {
            height: 10vw;
            width: 30vw;
            border-radius: 2vw;
            border:0;
            background: #ff9e2a;
            margin: 2vw 8vw;
            color:white;
            font-size:4vw;
        }
        .contentbank {
            margin: 2vw 2vw;
            width: 22vw;
        }
        .bank {
            margin: 10vw 5vw;
            
        }
    </style>
</head>
<body onLoad="myfunc()">
    <div id="load"></div>
 
    <a href="https://manish301107.github.io/IDlogin/"><img src="https://img.icons8.com/flat-round/64/undefined/circled-left-2--v1.png" class="backpage"></a>
    <div class="accordion">
        <div class="accordion-tab">
            <input type="checkbox" name="toggle" id="toggle1" class="accordion-taggle">
            <label for="toggle1"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTjOP0cfhAX88fZDzTMIuJG2eXSbQvhmbH7rQ&usqp=CAU" class="icon"><p class="head">AADHAR</p></label>
            
            <div class="accordion-content">
             <img src="https://www.linkpicture.com/q/Screenshot_20220531_085208.png" class="aadhar_img">
             <a href="https://www.linkpicture.com/q/Screenshot_20220531_094301.png"><button class="content">SEE</button></a>
             <a href="https://drive.google.com/file/d/1f-JwcNNC1I5NmrATrp6Jbhwrvk2lQLj_/view?usp=drivesdk"><button class="content">DOWNLOAD</button></a>
            </div>
        </div>
        
        <div class="accordion-tab">
            <input type="checkbox" name="toggle" id="toggle2" class="accordion-taggle">
            <label for="toggle2"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRgGQ9wNyB0qkcGFEal7ISZcvRsV2Xx7pty0Q&usqp=CAU" class="icon"><p class="head">PAN CARD</p></label>
            <div class="accordion-content">
               <img src="https://www.linkpicture.com/q/Screenshot_20220531_212656.png" class="pan_img">
             <a href="https://www.linkpicture.com/q/Screenshot_20220531_094301.png"><button class="content">SEE</button></a>
             <a href="https://drive.google.com/file/d/1f-JwcNNC1I5NmrATrp6Jbhwrvk2lQLj_/view?usp=drivesdk"><button class="content">DOWNLOAD</button></a>
            </div>
        </div>
        
       <div class="accordion-tab">
            <input type="checkbox" name="toggle" id="toggle3" class="accordion-taggle">
            <label for="toggle3"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTO9TC3JdIWAKnKQeXahOJz51yre1gDI2ZvR9izNfXqqbF4jwM8Fktc_38&s=10" class="icon"><p class="head">VOTER ID</p></label>
            <div class="accordion-content">
               <img src="https://www.linkpicture.com/q/Screenshot_20220531_212656.png" class="voter_img">
             <a href="https://www.linkpicture.com/q/VOTER_SLIP_1654012271894.jpg"><button class="content">SEE</button></a>
             <a href="https://drive.google.com/file/d/1f-JwcNNC1I5NmrATrp6Jbhwrvk2lQLj_/view?usp=drivesdk"><button class="content">SHARE</button></a>
            </div>
        </div>
        
        <div class="accordion-tab">
            <input type="checkbox" name="toggle" id="toggle4" class="accordion-taggle">
            <label for="toggle4"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ0pryu--eN8k26OF_rouPoDyHgAbI7937Btg&usqp=CAU" class="icon"><p class="head">DRIVING LICENSE</p></label>
            <div class="accordion-content">
               <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTfPNtl1NPH88hHyqizdf4TRzCx2Tj5D7HkPw&usqp=CAU" class="voter_img">
             <a href=""><button class="content">SEE</button></a>
             <a href=""><button class="content">SHARE</button></a>
            </div>
        </div>
        
        <div class="accordion-tab">
            <input type="checkbox" name="toggle" id="toggle5" class="accordion-taggle">
            <label for="toggle5"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRwv0fGkiDVlNWWTKITrJ695skq6N0EnVIAVA&usqp=CAU" class="icon"><p class="head">BANK PASSBOOK</p></label>
            <div class="accordion-content">
               <p class="bank">TILPAT - 
             <a href=""><button class="contentbank">SEE</button></a>
             <a href=""><button class="contentbank">SHARE</button></a>
             </p>
             
             <p class="bank">NEHAR PAR - 
             <a href=""><button class="contentbank">SEE</button></a>
             <a href=""><button class="contentbank">SHARE</button></a>
             </p>
            </div>
        </div>
    </div>
    
    
    <script>
        
        function myfunc() {
        var loader = document.getElementById("load");
            loader.style.display="none";
        }
    </script>
</body>
</html>
