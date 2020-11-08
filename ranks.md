---
layout: template
filename: ranks.md
permalink: /ranks/
---
<center> <h1> RANKS </h1> </center>
<hr>

<center>
Click on a rank below to view the description and associated requirements.
<img id="studentrank" onclick="clickstudent();" src="/OSINTStudentLogo2.svg" width="90" height="90" onmouseover="hoverstudentrank();" onmouseout="unhoverstudentrank();"  alt="Student"/> 
<img id="roninrank" onclick="clickronin();"   src="/OSINTRONINLogo2.svg" width="90" height="90" onmouseover="hoverroninrank();" onmouseout="unhoverroninrank();" alt="Ronin"/>
<img id="samurairank" onclick="clicksamurai();" src="/OSINTSamuraiLogo2.svg" width="90" height="90" onmouseover="hoversamurairank();" onmouseout="unhoversamurairank();" alt="Samurai"/>
<img id="daimyorank" onclick="clickdaimyo();" src="/OSINTDaimyoLogo2.svg" width="90" height="90" onmouseover="hoverdaimyorank();" onmouseout="unhoverdaimyorank(); "alt="Daimyo"/>
<img id="shogunrank" onclick="clickshogun();" src="/OSINTShogunLogo2.svg" width="90" height="90" onmouseover="hovershogunrank();" onmouseout="unhovershogunrank();" alt="Shogun"/>
</center>
<hr>

<div id="chosenrank"> </div>

<script>
 
function hoverstudentrank() 
{
  document.getElementById("studentrank").src = "/OSINTStudentLogo.svg";
}

function unhoverstudentrank() 
{
    document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
}

function hoverroninrank() 
{
  document.getElementById("roninrank").src = "/OSINTRONINLogo.svg";
}

function unhoveroninrank() 
{
    document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
}

function hoversamurairank() 
{
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo.svg";
}

function unhoversamurairank() 
{
    document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
}

function hoverdaimyorank() 
{
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo.svg";
}

function unhoverdaimyorank() 
{
    document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
}

function hovershogunrank() 
{
  document.getElementById("shogunrank").src = "/OSINTShogunLogo.svg";
}

function unhovershogunrank() 
{
    document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";
}

function clickstudent()
 {
  document.getElementById("chosenrank").innerHTML =`STUDENT TEXT`
  document.getElementById("studentrank").src = "/OSINTStudentLogo.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";  
 }
 
 function clickronin()
 {
  document.getElementById("chosenrank").innerHTML =`RONIN TEXT`
  document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";
 }
 
 function clicksamurai()
 {
  document.getElementById("chosenrank").innerHTML =`SAMURAI TEXT`
  document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";
 }
 
 function clickdaimyo()
 {
  document.getElementById("chosenrank").innerHTML =`DAIMYO TEXT`
  document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";
 }
 
 function clickshogun()
 {
  document.getElementById("chosenrank").innerHTML =`SHOGUN TEXT`
  document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo.svg";
 }
            
</script>
