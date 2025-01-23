# HTML_CSS
few_sample codes related to HTML_CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .main{
            display: grid;
            grid-template-columns: .7fr 1fr 1fr 1fr 1fr 1fr 1fr;
            grid-template-rows: 3cm 3cm 3cm 6cm 3cm;
            gap: 20px;
            margin: 0 auto
        }
        .div1{
            background-color: rgb(103, 152, 194);
            grid-row: 1/4;
            align-content: center;
            text-align: center;
        }
        .div2{
            background-color:aquamarine;
            grid-column: 2/7;
            align-content: center;
            text-align: center;
        }
        .div3{
            background-color:rgb(18, 60, 46);
            grid-column: 2/6;
            grid-row: 2/3;
            align-content: center;
            text-align: center;
        }
        .div4{
            background-color:rgb(158, 196, 20);
            grid-column: 2/3;
            grid-row: 3/4;
            align-content: center;
            text-align: center;
        }
        .div5{
            background-color:rgb(191, 127, 255);
            grid-column: 3/4;
            grid-row: 3/4;
            align-content: center;
            text-align: center;
        }
        .div6{
            background-color:rgb(255, 127, 127);
            grid-column: 4/5;
            grid-row: 3/4;
            align-content: center;
            text-align: center;
        }
        .div7{
            background-color:rgb(255, 144, 127);
            grid-column: 5/6;
            grid-row: 3/4;
            align-content: center;
            text-align: center;
        }
        .div8{
            background-color:rgb(23, 126, 92);
            grid-column: 6/7;
            grid-row: 3/4;
            align-content: center;
            text-align: center;
        }
        .div9{
            background-color:rgb(189, 255, 127);
            grid-column: 7/8;
            grid-row: 3/4;
            align-content: center;
            text-align: center;

        }
        .div10{
            background-color:rgb(255, 127, 180);
            grid-row: 4/5;
            align-content: center;
            text-align: center;
        }
        .div11{
            background-color:rgb(255, 127, 182);
            grid-row: 4/5;
            grid-column: 2/8;
            align-content: center;
            text-align: center;
        }
        .div12{
            background-color:aquamarine;
            grid-row: 5/6;
            grid-column: 2/8;
            align-content: center;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="main">
        <div class="div1">1</div>
        <div class="div2">2</div>
        <div class="div3">3</div>
        <div class="div4">4</div>
        <div class="div5">5</div>
        <div class="div6">6</div>
        <div class="div7">7</div>
        <div class="div8">8</div>
        <div class="div9">9</div>
        <div class="div10">10</div>
        <div class="div11">11</div>
        <div class="div12">12</div>

    </div>
</body>
</html>
