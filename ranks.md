---
layout: template
filename: ranks.md
permalink: /ranks/
---
<center> <h1> RANKS </h1> </center>
<hr>

<center>
Click on a rank below to view the description and associated requirements.
<img id="studentrank">  onclick="clickstudent();" src="/OSINTStudentLogo.svg" width="90" height="90" alt="Student"/> 
<img id="roninrank">  onclick="clickronin();"   src="/OSINTRONINLogo.svg" width="90" height="90" alt="Ronin"/>
<img id="samurairank">  onclick="clicksamurai();" src="/OSINTSamuraiLogo.svg" width="90" height="90" alt="Samurai"/>
<img id="daimyorank">  onclick="clickdaimyo();" src="/OSINTDaimyoLogo2.svg" width="90" height="90" alt="Daimyo"/>
<img id="shogunrank">  onclick="clickshogun();" src="/OSINTShogunLogo.svg" width="90" height="90" alt="Shogun"/>
</center>

<div id="chosenrank"> </div>

<script>
 
function clickstudent()
 {
  document.getElementById("chosenrank").innerHTML =`STUDENT`
 }
 
 function clickronin()
 {
  document.getElementById("chosenrank").innerHTML =`RONIN`
 }
 
 function clicksamurai()
 {
  document.getElementById("chosenrank").innerHTML =`SAMURAI`
 }
 
 function clickdaimyo()
 {
  document.getElementById("chosenrank").innerHTML =`DAIMYO`
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo.svg";
 }
 
 function clickshogun()
 {
  document.getElementById("chosenrank").innerHTML =`SHOGUN`
 }
            
</script>
