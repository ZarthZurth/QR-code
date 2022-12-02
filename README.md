# QR-code
Design preview for the QR code component coding challeng
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- <link rel="stylesheet" href="/styleQR.css"> -->
    <title>QR Code Component</title>
    <style>
        /* @import url('https://fonts.google.com/specimen/Outfit'); */
*{
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

body{
    font-family: 'Outfit', sans-serif;
    font-size: 15px;
    line-height: 1.7;
    color:#333;
    background: hsl(212, 45%, 89%);

}

.attirubituon {
    width:fit-content;
    margin: 100px auto;
    padding: 20px;
    display: grid;
    grid-template-columns:repeat(3, 1fr);
           
    }

    .card {
        
        background: #fff;
        border-radius: 20px;
        padding: 15px;
        box-shadow: rgba(17,12,46,0.15) 0px 48px 100px
        0px;
        margin-bottom: 10px;
        font-size: 11px; text-align: center;
        grid-column: 2;
        width: 300px;       
    }

    .card p{
        opacity: 70%;
        font-size: 15px;
    }

    .card h3{
        font-size: 20px;
        margin-top: 20px;
        margin-bottom: 20px;
    }
    .card-QR-code{
        border-radius: 10px;  
        width: 99%;
             
        
    }

    footer{
        text-align: center;
    }

    footer a{
        color: #333;
        text-decoration: none;
    }

    @media(max-width:768px){
        .attirubituon{
            grid-template-columns:auto;
            
            width: 100%;
        }

        footer{
            display: none;
        }
        
    }
    </style>
</head>
<body>
    <div class="attirubituon">
        <div class="card">
            <img src="/images/image-qr-code.png" class="card-QR-code" alt="">
            
            <h3> Improve your front-end skills by building projects</h3>
            <p>can the QR code to visit Frontend Mentor and take your coding skills to the next level</p>



        </div>
    </div>
    <footer>Challenge by <a href="">Frontend Mentor.</a> Coded by <a href="">Your Name Here.</a></footer>
    
</body>
</html>
