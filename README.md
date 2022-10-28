<!DOCTYPE html>
<html lang="hu">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>

<style>
    * {
        box-sizing: border-box;
    }

    body {
        margin: 0;
    }

    /* Style the header */
    .header {
        background-color: #f1f1f1;
        padding: 20px;
        text-align: center;
    }

    /* Style the top navigation bar */
    .topnav {
        overflow: hidden;
        background-color: #333;
    }

    /* Style the topnav links */
    .topnav a {
        float: left;
        display: block;
        color: #f2f2f2;
        text-align: center;
        padding: 14px 16px;
        text-decoration: none;
    }

    /* Change color on hover */
    .topnav a:hover {
        background-color: #ddd;
        color: black;
    }

    /* Create three equal columns that floats next to each other */
    .column {
        float: left;
        width: 33.33%;
        padding: 15px;
    }

    /* Clear floats after the columns */
    .row:after {
        content: "";
        display: table;
        clear: both;
    }

    /* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
    @media screen and (max-width:600px) {
        .column {
            width: 100%;
        }
    }
</style>


<body>

    <div class="header">
        <h1>Mercedes</h1>
        <p>Mercedes autó bemutató</p>
    </div>

    <div class="topnav">
        <a
            href="https://www.mercedes-benz.hu/passengercars/mercedes-benz-cars/models/amg-gt/coupe-c190/explore/footnote-amg.module.html">MerceMercedesdes-AMG
            GT</a>
        <a href="https://www.mercedes-benz.hu/passengercars/models/saloon/a-class/overview.html">Mercedes-A-osztály
            limuzin</a>
        <a href="https://www.mercedes-benz.hu/passengercars/the-brand/eqxx/stage.module.html">Mercedes-VISION EQXX</a>
    </div>

    <div class="row">
        <div class="column">
            <h2>Mercedes-AMG
            GT</h2>
            <p>The Mercedes-AMG GT (C190 / R190) is a grand tourer produced in coupé and roadster bodystyles by German automobile manufacturer Mercedes-AMG. The car was introduced on 9 September 2014 and was officially unveiled to the public in October 2014 at the Paris Motor Show.[4] After the SLS AMG, it is the second sports car developed entirely in-house by Mercedes-AMG. The Mercedes-AMG GT went on sale in two variants (GT and GT S) in March 2015, while a GT3 racing variant of the car was introduced in 2015.</p>
            <img src="https://www.mercedes-benz.hu/passengercars/mercedes-benz-cars/models/amg-gt/coupe-c190/explore/highlights/_jcr_content/contentgallerycontainer/par/contentgallery/par/contentgallerytile/image.MQ6.8.20210625103134.jpeg" alt="" width="70%" height="70%">
        </div>

        <div class="column">
            <h2>Mercedes-A-osztály
            limuzin</h2>
            <p>The Mercedes-Benz A-Class is a subcompact car produced by the German automobile manufacturer Mercedes-Benz as the brand's entry-level vehicle. The first generation (internally coded W168) was introduced in 1997, the second generation (W169) in late 2004 and the third generation (W176) in 2012. <br> <img src="https://www.pappas.hu/clients/pappas/global/car-model/pkw/mercedes-benz/A-Klasse%20Limousine/2018/gallery/image-thumb__233949__img-grid-slider-mobile/18C0485_062.webp" alt="" width="70%" height="70%"> </p>
            
        </div>

        <div class="column">
            <h2>Mercedes-VISION
                EQXX</h2>
            <p>Mercedes-EQ is a series of battery electric vehicles manufactured by Mercedes-Benz. The first model was previewed at the Paris Motor Show in 2016 with the Generation EQ concept vehicle.[1] Mercedes-Benz intends to produce ten EQ models by 2022, three of which will have the Smart brand, representing between 15% and 25% of the company's global sales. <img src="https://www.motortrend.com/uploads/2022/07/EQXX-drive-top.png" alt="" width="70%" height="70%"></p>
        </div>
    </div>

</body>

</html>
