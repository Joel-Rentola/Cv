<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
.info{
    float: left;
    width: 35%;
    height: 590px;
    background-color: #53d2ef;
    margin-right: 25px;
}
.box{
    height: 150px;
    background-color: #43aac4;
    padding-left: 10px;
}
.box img{
    float: left;
}
</style>
<body>
    <div class="info">
    <div class="box">
        <h3 style="margin-top: 0; margin-bottom: 5px; padding-top: 5px;">Personal info:</h3>
        <img src="data:image/png;base64,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" style="height: 20px; width: 20px;"><p style="margin: 0;">Joel Rentola</p>
        <img src="https://cdn2.iconfinder.com/data/icons/font-awesome/1792/phone-512.png" style="height: 20px; width: 20px;"><p style="margin: 0;">045 6931959</p>
        <img src="https://cdn-icons-png.flaticon.com/512/4213/4213968.png" style="height: 20px; width: 20px;"><p style="margin: 0; margin-left: 22px;">joel06.rentola@gmail.com</p>
        <img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" style="height: 20px; width: 20px;"><a href="https://github.com/Joel-Rentola" target="_blank" style="margin: 0; margin-top: 0px; margin-left: 2px; color: black;">https://github.com/Joel-Rentola</a>
    </div>

    <div style="margin-left: 10px;">
        <h3 style="margin-top: 5px;">A little bit of me:</h3>
        <p>Hello! I'm Joel Rentola a second year software developer student from Finland. I'm fluent in Finnish and English.
            I can also speak a little bit of Swedish too. Most of my code projects has been coded in C#, but I've used other languages such as python etc. too.
             I also have an experience of coding very basic websites.</p>
    </div>
    </div>

    <div>
        <h3 style="margin: 0; padding-top: 5px;">Education:</h3>
        <p>
            -Primary school &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;graduated 1.6.2022. <br>
            -Gradia vocational college software development &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ongoing <br>
        </p>
    
        <h3>My work experiense:</h3>
        <p>-Internship: Power Seppälä Jyväskylä &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9.2.2023-13.3.2023 Customer serving, IT-support and other IT stuff<br>
            -My own 4H IT company &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            &nbsp; For about a year
        </p>
    
        <h3>Other jobs:</h3>
        <p>
            -Student council of Koulukeskus Uurainen 20.10.2018-1.6.2020<br>
            -Secretary of the Student council of Koulukeskus Uurainen 20.10.2020-1.6.2021<br>
            -Chairman of the Student council of Koulukeskus Uurainen 20.10.2021-1.6.2022<br>
            -Member of Youth council of Uurainen 11.10.2018-31.12.2019 <br>
            -Chairman of Youth council of Uurainen 1.1.2020-1.6.2022 <br>
        </p>
    
        <fieldset style="width: 280px;">
            <legend>Coding languages I've coded with</legend>
            <img src="https://static-00.iconduck.com/assets.00/c-sharp-c-icon-1822x2048-wuf3ijab.png" style="width: 40px; height: 40px; margin-right: 40px; margin-left: 5px; margin-bottom: 10px;">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/1869px-Python-logo-notext.svg.png" style="width: 40px; height: 40px; margin-right: 40px; margin-bottom: 8px;">
            <img src="https://banner2.cleanpng.com/20180411/cvq/kisspng-javascript-html-computer-software-web-browser-watermark-5acdbd54ac19f7.4484983215234327887049.jpg" style="width: 40px; height: 40px; margin-bottom: 10px;"> <br>
            <img src="https://cdn-icons-png.flaticon.com/512/5968/5968267.png" style="width: 50px; height: 50px; margin-right: 30px;">
            <img src="https://cdn.iconscout.com/icon/free/png-256/free-css-38-226095.png?f=webp" style="width: 50px; height: 50px; margin-right: 30px;">
            <img src="https://cdn-icons-png.flaticon.com/512/5968/5968332.png" style="width: 50px; height: 50px; margin-top: 8px;">
        </fieldset>
    </div>
</body>
</html>
