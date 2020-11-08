---
layout: template
filename: ranks.md
permalink: /ranks/
---
<center> <h1> RANKS </h1> </center>
<hr>

<center>
Click on a rank below to view the description and associated requirements.
<img id="studentrank" onclick="clickstudent();" src="/OSINTStudentLogo2.svg" width="90" height="90" onmouseover="hover(this);" onmouseout="unhover(this);"  alt="Student"/> 
<img id="roninrank" onclick="clickronin();"   src="/OSINTRONINLogo2.svg" width="90" height="90" alt="Ronin"/>
<img id="samurairank" onclick="clicksamurai();" src="/OSINTSamuraiLogo2.svg" width="90" height="90" alt="Samurai"/>
<img id="daimyorank" onclick="clickdaimyo();" src="/OSINTDaimyoLogo2.svg" width="90" height="90" alt="Daimyo"/>
<img id="shogunrank" onclick="clickshogun();" src="/OSINTShogunLogo2.svg" width="90" height="90" alt="Shogun"/>
</center>
<hr>

<div id="chosenrank"> </div>

<script>
 
function hover(studentrank) {
element.setAttribute('src', '/OSINTStudentLogo.svg');
}

function unhover(studentrank) {
  element.setAttribute('src', '/OSINTStudentLogo2.svg');
}
 
function clickstudent()
 {
  document.getElementById("chosenrank").innerHTML =`STUDENT`
  document.getElementById("studentrank").src = "/OSINTStudentLogo.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";  
 }
 
 function clickronin()
 {
  document.getElementById("chosenrank").innerHTML =`RONIN`
  document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";
 }
 
 function clicksamurai()
 {
  document.getElementById("chosenrank").innerHTML =`SAMURAI`
  document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";
 }
 
 function clickdaimyo()
 {
  document.getElementById("chosenrank").innerHTML =`DAIMYO`
  document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";
 }
 
 function clickshogun()
 {
  document.getElementById("chosenrank").innerHTML =`SHOGUN`
  document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo.svg";
 }
            
</script>
