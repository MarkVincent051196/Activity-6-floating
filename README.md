<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width-devicewidth, initial-scale=1.0">
    <title>Floating Elements</title>
    <script type="text/javascript" src="https://gc.kis.v2.scr.kaspersky-labs.com/FD126C42-EBFA-4E12-B309-BB3FDD723AC1/main.js?attr=ScwI2HwLbzHuOAlz__mqqLYr9C42_McFEWuz08Ul4E09-UzHv58UAiqF4OdbppubKP29lsYQgCFzyy5VFbYoSnvm89ya0j_D6tgGUgJaWfU_bf5oK4azaUzFxdO_8YKh8crZnozQxOFcs6QZZ7zx_nLyYHO0FKX_U74jblguWTd4AeNDjY3U6G_ElyTXuTH_7HKe0_oEfMk1xrLWiuKeZM5uHV7dEVsnlM89d4ynSaPoP082sXA7-ccGQul1FU4xRenAG1vxfXRP40WUEMwiqT9bA4H2HD07J7O-Nx0SEF6WV-TMdB0L2SoOV5dhEnCcKS-B1-TkUmIhnrbR4vk4sNhsT1QneLnrggXHyisrIEeJBoByhI2rUbFjBFKsKJJZC_E0rnEslC89C3wbFXWzbIg4V40WP4ETven5uQqeVgnd6CCtoRgGH1jhjeYFthqaE9ORjgfwwijzLwKM1a1TOvgxYHqIcKojzFlECx3Q_ZE" charset="UTF-8"></script><style>
        div {
            background-color: darkmagenta;
        }
        
        p {
            width: 50px;
            height: 50px;
            border: 1px solid black;
            margin-right: 10px;
        }
        
        #p1 {
            background-color: Tomato;
            float: left;
            height: 400px;
        }
        
        #p2 {
            background-color: orange;
            float: left;
            height: 300px;
        }
        
        #p3 {
            background-color: dodgerblue;
            clear: both;
        }
        
        #p4 {
            background-color: mediumseagreen;
        }
    </style>
</head>

<body>
    <h1>Floating Elements</h1>
    <div id="container">
        <p id="p1"></p>
        <p id="p2"></p>
        <p id="p3"></p>
        <p id="p4"></p>
        <section>Content that follows after the paragraph.</section>
    </div>

</body>

</html>
