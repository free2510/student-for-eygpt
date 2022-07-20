# student-for-eygpt
* {
    padding: 0;
    margin: 0;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

header {
    padding: 0 40px 0 20px;
    width: 100%;
    background-color: #4d589b;
    border-bottom: #840032 5px solid;
    position: fixed;
    z-index: 999;
}

.contaner {
    justify-content: space-between;
    display: flex;
    align-items: center;
}

.contaner .namefamily {
    width: 200px;
    height: 100px;
    padding: 0;
    margin: 0;
}

.contaner .namefamily img {
    display: flex;
    justify-content: center;
    width: 100%;
}

.contaner .navigation {
    display: flex;
    direction: rtl;
}

.contaner .navigation ul {
    display: flex;
}

.contaner .navigation ul li {
    text-decoration: none;
    list-style: none;
    padding-right: 40px;
    padding-top: 20px;
}

.contaner .navigation .material {
    position: relative;
}

.contaner .navigation ul .material ul {
    display: flex;
    flex-direction: column;
    padding: 0;
    margin: 10px 14px 0 0;
    position: absolute;
    width: 146px;
    display: none;
    background-color: #1fa6d3;
    border-radius: 20px;
}

.contaner .navigation ul .material ul li {
    margin: 0;
    padding: 0;
    line-height: 35px;
}

.contaner .navigation ul .material ul a {
    padding: 0 20px;
    display: flex;
    justify-content: center;
    color: #83C5BE;
}

.contaner .navigation ul .material ul li:hover {
    background-color: #97799c;
    border-radius: 40px;
}

.contaner .navigation ul .material ul li a:hover {
    color: #ffffff;
}

.contaner .material:hover .drop_menu {
    display: block;
}

.contaner .navigation ul li a {
    text-decoration: none;
    color: #2f0f35;
    font-weight: 600;
    font-size: 1.25em;
    padding-right: 40px;
    padding-top: 100px;
    text-transform: uppercase;
    transition: 0.5s ease;
    padding-bottom: 50px;
}

.contaner .navigation a:hover {
    color: #0501fc;
    transform: scale(110%);
}

.contaner .navigation .home {
    color: #ffffff;
}



.main {
    background-color: #1e335c;
    min-height: 80vh;
    display: flex;
    justify-content: space-between;
    padding: 120px 100px 50px 100px;
    direction: rtl;
    position: relative;
    align-items: flex-start;
}

.contaner_main {
    width: 80%;

}

.contaner_main .slider {
    width: 900px;
    height: 500px;
    display: flex;
    overflow: hidden;
    position: relative;
    border-radius: 5%;
}

input {
    display: none;
    position: absolute;
}

.contaner .imge-slide {
    width: 900px;
    height: 500px;
    transition: 5 ease;

}

.slider .imge-slide img {
    width: 900px;
    height: 500px;

}

.main .cont_lable {
    align-items: center;
    justify-content: center;
    display: flex;
    margin-left: 300px;
    margin-top: 20px;
}

.main label:hover {
    background-color: rgba(128, 128, 0, 0.479);
}

.main label {
    border-radius: 50%;
    border: #0501fc 3px solid;
    width: 20px;
    height: 20px;
    display: flex;
    margin: 0 7px;
    cursor: pointer;
}




#radio1:checked~.first {
    margin-left: 0px;
    transition: 5s;
    animation: auto_slide 30s infinite ease reverse;
}

#radio2:checked~.first {
    margin-left: -900px;
    transition: 5s;
    animation: auto_slide 30s infinite ease reverse;
}

#radio3:checked~.first {
    margin-left: -1800px;
    transition: 5s;
    animation: auto_slide 30s infinite ease reverse;
}

#radio4:checked~.first {
    margin-left: -2700px;
    transition: 5s;
    animation: auto_slide 30s infinite ease reverse;
}

#radio5:checked~.first {
    margin-left: -3600px;
    transition: 5s;
    animation: auto_slide 30s infinite ease reverse;
}

#radio6:checked~.first {
    margin-left: -4500px;
    transition: 5s;
    animation: auto_slide 30s infinite ease reverse;
}

.main .some-inf {
    width: 1000px;
    min-height: 5%;
    font-weight: 700;
    line-height: 40px;
    display: block;
    padding-right: 1%;
    font-size: 1.2em;

}

.main .some-inf p h3 {
    display: block;

}



aside {
    width: 250px;
    min-height: 500px;
    background-color: rgb(231, 231, 231);
    display: block;
    padding: 20px;
    border-radius: 12px;
}

.main aside img {
    width: 100%;
    margin-top: 10px;
}

.main aside p {
    font-size: 1.0625em;
    font-weight: 600;
}




.second {
    min-height: 100vh;
    padding: 20px 100px;
    padding-top: 100px;
    background-color: #1E3266;
}

.second a {
    text-decoration: none;
}

.second .title {
    font-size: 3.125em;
    font-weight: 800;
    letter-spacing: 1px;
    color: #1fa6d3;
    text-transform: uppercase;
    margin-bottom: 60px;
    display: block;
    display: flex;
    justify-content: center;
}

.second .second-main .news-card {
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    width: 100%;
    justify-content: center;
}

.second .second-main .news-card .card-contaner {
    display: flex;
    justify-content: center;
}

.second .second-main .news-card .card-contaner .card {
    width: 250px;
    height: 50px;
    background-color: rgb(174, 196, 216);
    border-radius: 15px;
    border: 2px;
    padding: 8px;
    line-height: 20px;
    height: 100%;
    box-shadow: 0 10px 20px rgba(98, 98, 105, 100%);
    margin: 0 10vh;
    transition: 0.8s;
}

.second .second-main .news-card .card-contaner .card:hover {
    transform: scale(115%);
}

.second .second-main .news-card .card-contaner .card img {
    width: 100%;
    border-radius: 25px;
}

.second .second-main .news-card .card-contaner .card p {
    font-size: 0.75em;
    font-weight: bold;
}

.second .second-main .news-card .card-contaner .card h4 {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
}

.second .second-main .news-card .card-contaner .card a {
    font-size: smaller;
}

.footer {
    min-height: 30px;
    background-color: #4d589b;
    font-size: 30px;
    color: #ffffff;
    padding: 30px 70px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    direction: rtl;
}
.footer a{ font-size: 50px;color: #c5a7a7; margin-left: 30px;display: inline-flex; text-decoration: none; }
.footer p{font-size: 0.9em;}
.footer span{font-size: 1.1em;color: #523a3a;font-weight: 700;text-transform: uppercase ; letter-spacing: 1px;}

@media screen and (max-width:26cm) {

    .second .second-main .news-card .card-contaner {
        display: flex;
        flex-direction: column;

    }

    .second .second-main .news-card .card-contaner .card {
        margin: 1vh 3vh;
        width: 433px;
        height: max-content;
    }

    aside {
        position: static;
        display: block;
        left: 0%;
    }

    .main .slider {
        width: 600px;
        height: 500px;
    }

    .main {
        padding: 120px 42px 50px 42px;
        font-size: 0.6em;
        display: inline-flex;
    }

    .imge-slide {
        width: 600px;
        height: 500px;
    }

    .slider .imge-slide img {
        width: 600px;
        height: 500px;
    }

    #radio1:checked~.first {
        margin-left: 0px;
        transition: 5s;
    }

    #radio2:checked~.first {
        margin-left: -600px;
        transition: 3s;
    }

    #radio3:checked~.first {
        margin-left: -1200px;
        transition: 3s;
    }

    #radio4:checked~.first {
        margin-left: -1800px;
        transition: 3s;
    }

    #radio5:checked~.first {
        margin-left: -2400px;
        transition: 3s;
    }

    #radio6:checked~.first {
        margin-left: -3000px;
        transition: 3s;

    }

    .main .some-inf {
        margin-top: 121px;
        width: 649px;
        font-size: 1.8em;
    }

    header {
        font-size: 1.1em;
    }

    header .contaner .namefamily {
        width: 170px;
        height: 90px;
    }

    .contaner .navigation ul .material ul {
        width: 206px;
    }

    .contaner .navigation ul li a {
        padding-right: 14px;
    }

    .contaner .navigation ul .material ul li {
        line-height: 50px;
    }

    .main aside p {
        font-size: 2.1em;
        font-weight: 650;
    }

    .contaner_main {
        width: 67%;
    }

    .main .cont_lable {
        margin-left: -34px;
    }

    .main {
        min-height: 45vh;
    }
    .footer {min-height: 170px;}
}

@media (min-width:26cm) and (max-width:30cm) {
    .main {
        padding: 120px 50px 50px 50px;
        font-size: 0.7em;
    }

    .second .second-main .news-card .card-contaner {
        display: flex;
        flex-wrap: wrap;
    }

    .second .second-main .news-card .card-contaner .card {
        margin: 1vh 3vh;
        width: 300px;
        height: max-content;
    }

    .main aside p {
        font-weight: 650;
    }

    .contaner_main {
        width: 67%;
    }

    .contaner_main .slider {
        width: 660px;
        height: 460px;
    }

    .main .cont_lable {
        margin-left: -34px;
    }

    .main .some-inf {
        margin-top: 28px;
        width: 700px;
    }

    .imge-slide {
        width: 660px;
        height: 460px;
    }

    .slider .imge-slide img {
        width: 660px;
        height: 460px;
    }

    #radio1:checked~.first {
        margin-left: 0px;
        transition: 5s;
    }

    #radio2:checked~.first {
        margin-left: -660px;
        transition: 3s;
    }

    #radio3:checked~.first {
        margin-left: -1320px;
        transition: 3s;
    }

    #radio4:checked~.first {
        margin-left: -1980px;
        transition: 3s;
    }

    #radio5:checked~.first {
        margin-left: -2640px;
        transition: 3s;
    }

    #radio6:checked~.first {
        margin-left: -3300px;
        transition: 3s;

    }
}

@media (min-width:30cm) and (max-width:35cm) {
    .main {
        padding: 120px 50px 50px 50px;
        font-size: 0.9em;
    }

    .second .second-main .news-card .card-contaner {
        display: flex;
        flex-wrap: wrap;
    }

    .second .second-main .news-card .card-contaner .card {
        margin: 1vh 3vh;
        width: 300px;
        height: max-content;
    }

    .main aside p {
        font-weight: 650;
    }

    .contaner_main {
        width: 67%;
    }

    .contaner_main .slider {
        width: 762px;
        height: 460px;
    }

    .main .cont_lable {
        margin-left: -34px;
    }

    .main .some-inf {
        margin-top: 28px;
        width: 700px;
    }

    .imge-slide {
        width: 762px;
        height: 460px;
    }

    .slider .imge-slide img {
        width: 762px;
        height: 460px;
    }

    #radio1:checked~.first {
        margin-left: 0px;
        transition: 5s;
    }

    #radio2:checked~.first {
        margin-left: -762px;
        transition: 3s;
    }

    #radio3:checked~.first {
        margin-left: -1524px;
        transition: 3s;
    }

    #radio4:checked~.first {
        margin-left: -2286px;
        transition: 3s;
    }

    #radio5:checked~.first {
        margin-left: -3048px;
        transition: 3s;
    }

    #radio6:checked~.first {
        margin-left: -3810px;
        transition: 3s;

    }
}
