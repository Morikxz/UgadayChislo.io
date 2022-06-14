# UgadayChislo.io
<!-- Над проектом работали: ?pythonDev, Дамир -->
<!-- Версия игры: 1.3-->
<!DOCTYPE html>
<html>
    <head>
        <title>Угадай число</title>
		<link rel="icon" href="ugaday chislo.ico">
    </head>
	
	<style type="text/css">
	body {
   background-color:rgb(255, 183, 50); 
}

#menu {
    color:#80b629;
}

#zagadyvanie {
    text-decoration: none;
    background-color:#2f7be6;
    border-radius:50px;
    color: #5fe2e2;
    border: unset;
    cursor: pointer;
    transition: 0.3s;
}

#zagadyvanie:hover {
    box-shadow: -5px 3px 10px #2f7be6;
}

#rewimy {
    color:#d38003;
    cursor:text;
}

#otgadyvanie {
    cursor:pointer ;
    border: none;
    border-radius:50px;
    color: #a6dd4c;
    display: flex;
	float:right;
    background-color: rgb(40, 177, 27);
    transition: 0.5s;
}

#otgadyvanie:hover {
    box-shadow: 5px 3px 10px rgb(40, 177, 27);
}

.ot_zag {
    display: flex;
    list-style: none;
}

.ito {
    width: 350px;
}

title:hover {
    background-color: black;
    color: darkturquoise;
}
	</style>
	
    <body>
    
        <h1 id="menu" align="center" title="Слово меню"><big>Меню</big></h1>
        <h2 id="rewimy" align="center" title="Слово режимы"><i>Режимы:</i></h2>
       <ul class="ot_zag"> 
           <li class="ito">
      <button id="zagadyvanie" onclick="zagadyvanie()" title="Режим загадывания">Загадывание</button>
      </li>
      <li class="ito">
      <button id="otgadyvanie" onclick="otgadyvanie()" title="Режим отгадывания">Отгадывание</button>
      </li>
       </ul>
	   
	   <script type="text/javascript">
	   // Created by ?pythonDev

// Created by Дамир Дамир

function otgadyvanie() {
    window.location.href = "file:///C:/Users/YAROSLAV/Documents/%D0%92%D1%81%D1%91%20%D0%94%D0%B0%D0%BC%D0%B8%D1%80%D0%B0/%D0%A3%D0%B3%D0%B0%D0%B4%D0%B0%D0%B9%20%D0%A7%D0%B8%D1%81%D0%BB%D0%BE%20[%D0%98%D0%B3%D1%80%D0%B0]%20%D0%9E%D1%82%D0%B3%D0%B0%D0%B4%D1%8B%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5.html";
}

function zagadyvanie() {
    window.location.href = "file:///C:/Users/YAROSLAV/Documents/%D0%92%D1%81%D1%91%20%D0%94%D0%B0%D0%BC%D0%B8%D1%80%D0%B0/%D0%A3%D0%B3%D0%B0%D0%B4%D0%B0%D0%B9%20%D0%A7%D0%B8%D1%81%D0%BB%D0%BE%20[%D0%98%D0%B3%D1%80%D0%B0]%20%D0%97%D0%B0%D0%B3%D0%B0%D0%B4%D1%8B%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5.html";
}
	   </script>
	   
	   <br />
<br />
<br />
<p>©Игра <i>"Угадай Число"</i> версия 1.3 была выпущена в 2022 году компанией</p>
    </body>
</html>
