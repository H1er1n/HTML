<!DOCTYPE html>
<html>
<body>
<h1>Программирование - это интересно.</h1>
<h2>Существует очень много языков программирования.</h2>
    <h3>Каждый из них имеет свою фичу.</h3>
    <h4>Профессиональные программисты могут владеть несколькими языками программирования.</h4>
    <h5>Эти языки предназначены для написания программ.</h5>
    <h6>Язык определяется через спецификации стандарта и реализации стандарта.</h6>
    <p><b>Эльсинор. Площадка перед замком. Полночь. Офицер Бернардо сменяет солдата Франциско, стоящего на посту. На площади появляются офицер Марцелл и друг Гамлета Горацио. Марцелл спрашивает у Бернардо, не видел ли он призрака, которого уже дважды замечали замковые стражники. Горацио находит это просто игрой воображения.</b></p>
    <p><i>Неожиданно появляется призрак, похожий на покойного короля. Горацио спрашивает у духа, кто он, но тот, оскорбившись вопросом, исчезает. Горацио считает, что появление призрака – это «знак грозящих государству потрясений».</i></p>
<body style="background: #D6F1E1">
    <head>
    <style> 
        body {animation-duration: 3s; animation-name: slidein}
        @keyframes slidein{from {margin-left: 100%;
            width: 300%}
            to{margin-left: 0%; width: 100%}}
        table {
    border-collapse: collapse;
    width: 100%;
}

th, td {
    text-align: center;
    padding: 8px;
}

tr:nth-child(even) {background-color: #f2f2f2;}
        tr{ background-color: cadetblue;
    color: black;}
        a:link, a:visited {
    background-color: #f44336;
    color: white;
    padding: 14px 25px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
}

a:hover, a:active {
    background-color: red;
}
        .animation{animation: blink 2s infinite}
        @keyframes  blink{
            from{opacity: 1}
            to{opacity: 0}
        }
        u.rollover{background: url(image/u6.gif); display: block; width: 500px; height: 300px;}
        u.rollover:hover{background: url(image/u4.gif)}
        #dis{display: block}
        #op {opacity: 50%}
        li:hover{color: red}
        #color{color: #8A1F90}
        #center{text-align: center;font-family: sans-serif, monospace; padding: inherit; font-size: large}
        #right{text-align: inherit; padding: 20px}
        #left{text-align: left}
        #border{border: dotted #FFF900; background-color: #77C7DE; width: 7%}
        #list{display: flex;justify-content: space-around}
        #ul{display: grid; text-align: center;justify-content: space-around}
        #mirror{transform: scale(-1, 1)}
        #bord{border: solid #452B54; border-radius: 4px}
        input[type=text]{
    width: 40%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 4px;
    resize: vertical;
}
       input[type=submit] {
    background-color: #2B6E4F;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 20px;
    cursor: pointer;
    float: left;
}

input[type=submit]:hover {
    background-color: #25393F;
}
        textarea {
    width: 45%;
    height: 150px;
    padding: 12px 20px;
    box-sizing: border-box;
    border: 2px solid #ccc;
    border-radius: 4px;
    background-color: #f8f8f8;
    font-size: 16px;
    resize: none;
}
        .button {
  display: inline-block;
  border-radius: 25px;
  background-color: #f4511e;
  border: none;
  color: #FFFFFF;
  text-align: center;
  font-size: 28px;
  padding: 20px;
  width: 200px;
  transition: all 0.5s;
  cursor: pointer;
  margin: 5px;
}

.button span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
}

.button span:after {
  content: '\00bb';
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}

.button:hover span {
  padding-right: 25px;
}

.button:hover span:after {
  opacity: 1;
  right: 0;
}
    </style>
        </head>
    <section id="center">
<h1 style="color: aquamarine">Программирование - это интересно.</h1>
<h2 style="color: brown">Существует очень много языков программирования.</h2>
    <h3 style="color: #B6E3AC">Каждый из них имеет свою фичу.</h3>
    <h4 style="color: RGB(150,47,20)">Профессиональные программисты могут владеть несколькими языками программирования.</h4>
    <h5 style="color: crimson">Эти языки предназначены для написания программ.</h5>
        <div class="animation">
    <h6>Язык определяется через <span id="color">спецификации</span> стандарта и реализации стандарта.</h6>
        </div>
        </section>
    <section id="right">
    <p style="text-transform: uppercase"><b>Эльсинор. Площадка перед замком. Полночь. Офицер Бернардо сменяет солдата Франциско, стоящего на посту. На площади появляются офицер Марцелл и друг Гамлета Горацио. Марцелл спрашивает у Бернардо, не видел ли он призрака, которого уже дважды замечали замковые стражники. Горацио находит это просто игрой воображения.</b></p>
    <p style="text-decoration: underline overline dotted red"><i>Неожиданно появляется призрак, похожий на покойного короля. Горацио спрашивает у духа, кто он, но тот, оскорбившись вопросом, исчезает. Горацио считает, что появление призрака – это «знак грозящих государству потрясений».</i></p>
    <p><del>Марцелл интересуется у Горацио, почему в последнее время в королевстве активно готовятся к войне. Горацио рассказывает, что Гамлет убил в бою «властителя норвежцев Фортинбраса» и по договору получил земли побежденного. Однако «младший Фортинбрас» решил отбить потерянные земли, и именно это является «предлогом к сумятице и сутолоке в крае».</del></p>
    <p><u>Неожиданно призрак появляется вновь, но с криками петуха исчезает. Горацио решает рассказать об увиденном Гамлету.</u></p>
    <p><abbr title="Гамлет. Сцена 2.">Зал для приемов в замке. Король сообщает о своем решении взять в жены сестру покойного брата Гертруду. Возмущенный попытками королевича Фортинбраса вернуть власть на потерянных землях, Клавдий отправляет придворных с письмом к его дяде, королю норвежцев, чтобы тот пресек на корне замыслы племянника.</abbr></p>
        </section>
    <section id="border">
    <p>a<sup>m</sup>*a<sup>m</sup>=a<sup>n+m</sup></p>
    </section>
    <section id="ul">
    <ul>
    <li>Python</li>
    <li>C</li>
    <li>Java</li>
    <li>C++</li>
    <li>C#</li>
    <li>JavaScript</li>
    <li style="list-style-image: url(https://img.icons8.com/small/2x/mac-os.png); background-size: 50% 50%">Python</li>
    <li style="list-style-image: url(https://img.icons8.com/small/2x/apple-pay.png)">C</li>
    <li style="list-style-image: url(https://img.icons8.com/small/2x/apple-tv.png)">Java</li>
    <li style="list-style-image: url(https://img.icons8.com/small/2x/itunes-store.png)">C++</li>
    <li style="list-style-image: url(https://img.icons8.com/small/2x/imessage.png)">C#</li>
    <li style="list-style-image: url(https://img.icons8.com/small/2x/ios-photos.png)">JavaScript</li>
    </ul>
    <ol>
        </section>
        <section id="div">
    <ol id="list">
    <li>Понедельник</li>
    <li>Вторник</li>
    <li>Среда</li>
@@ -30,17 +163,35 @@ <h6>Язык определяется через спецификации ста
    <li>Суббота</li>
    <li>Воскресенье</li>
    </ol>
    <p><a href="https://www.google.ru">Ссылка на гугл.</a></p>
    <p align="center"><img src="image/image.jpg" alt="Ленин показывает сердечко"></p>
            </section>
            <section>
    <p><a href="https://www.google.ru">Google</a></p>
                </section>
                <section>
    <p align="center" id="op"><img src="image/u1.gif" ></p>
                    </section>
    <section>
    <p align="center" id="dis"><u class="rollover"></u></p>
                    </section>
    <section align="center">
    <img src="image/u5.gif">
        <img src="image/u5.gif" id="mirror">
                    </section>
                    <section style="padding: 100px; font-family: serif">
    <form action="file:///C:/Users/nazva/Desktop/sd/page.html"> 
        <fieldset>
        <fieldset id="bord" style="background-color: #397C90; width: 50%; text-align: left">
            <legend>Your information</legend>
       <p>Name:<br><input type="text"></p>
        <p>E-mail:<br><input type="text"></p>
        <p>Phone:<br><input type="text"></p>
        <input type="submit" value="Отправить">
        <textarea cols="30px" rows="10px">Напиши что-нибудь</textarea>
            <br>

        <input type="submit" name="Отправить">

            </fieldset>
    </form>
                        </section>
                        <section>
    <table border=5>
    <tr>
        <td>Время</td>
@@ -50,8 +201,8 @@ <h6>Язык определяется через спецификации ста
        <td>Четверг</td>
        <td>Пятница</td>
        <td>Суббота</td>
        </tr>
         <tr>
    </tr>
    <tr>
        <td>8.30-10.00</td>
        <td>---/----</td>
        <td>Ин.яз/---</td>
@@ -115,8 +266,14 @@ <h6>Язык определяется через спецификации ста
        <td>---/---</td>
        </tr>
    </table>
                            </section>
                            <section>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/cyuzt1Dp8X8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                                <button class="button" style="vertical-align:middle"><span>YouTube</span></button>
                                </section>
                                <section>
    <br><iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2441.4824575524476!2d104.25908325133551!3d52.27094257966847!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x5da824a8ee4f155d%3A0x368423aaef9b2b13!2z0JjRgNC60YPRgtGB0LrQuNC5INCz0L7RgdGD0LTQsNGA0YHRgtCy0LXQvdC90YvQuSDRg9C90LjQstC10YDRgdC40YLQtdGCINC_0YPRgtC10Lkg0YHQvtC-0LHRidC10L3QuNGP!5e0!3m2!1sru!2sru!4v1649069696070!5m2!1sru!2sru" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
                                    </section>
</body>
</html>
