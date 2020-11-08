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

<img id="daimyorank" onclick="clickdaimyo();" src="/OSINTDaimyoLogo2.svg" width="90" height="90" onmouseover="hoverdaimyorank();" onmouseout="unhoverdaimyorank();" alt="Daimyo"/>

<img id="shogunrank" onclick="clickshogun();" src="/OSINTShogunLogo2.svg" width="90" height="90" onmouseover="hovershogunrank();" onmouseout="unhovershogunrank();" alt="Shogun"/>
</center>
<hr>

<div id="chosenrank"> </div>

<script>
 
 var count = 0;
 
function hoverstudentrank() 
{
  document.getElementById("studentrank").src = "/OSINTStudentLogo.svg";
}

function unhoverstudentrank() 
{
   if (count=1) 
   {
    document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
   } 
   
   else 
   {
    document.getElementById("studentrank").src = "/OSINTStudentLogo.svg";
   } 

}

function hoverroninrank() 
{
  document.getElementById("roninrank").src = "/OSINTRONINLogo.svg";
}

function unhoverroninrank() 
{
   if (count=2) 
   {
    document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
   } 
   
   else 
   {
    document.getElementById("roninrank").src = "/OSINTRONINLogo.svg";
   } 
}

function hoversamurairank() 
{
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo.svg";
}

function unhoversamurairank() 
{
   if (count=3) 
   {
    document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
   } 
   
   else 
   {
    document.getElementById("samurairank").src = "/OSINTSamuraiLogo.svg";
   } 
}

function hoverdaimyorank() 
{
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo.svg";
}

function unhoverdaimyorank() 
{
   if (count=4) 
   {
    document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
   } 
   
   else 
   {
    document.getElementById("daimyorank").src = "/OSINTDaimyoLogo.svg";
   } 
}

function hovershogunrank() 
{
  document.getElementById("shogunrank").src = "/OSINTShogunLogo.svg";
}

function unhovershogunrank() 
{
   if (count=5) 
   {
    document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";
   } 
   
   else 
   {
    document.getElementById("shogunrank").src = "/OSINTShogunLogo.svg";
   } 
}

function clickstudent()
 {
  count = 1;
 
  document.getElementById("chosenrank").innerHTML =`<h3>Rank Description</h3>Student is the first rank on your journey to becoming a better OSINT practitioner. Users in this level should be somewhat familiar with OSINT terms and methodology, if not, they are highly recommended to do research either on their own or via the Resources link to the left. At this level, users are being introduced to the different categories of challenges that are designed to strengthen their OSINT skills, particularly writing, verbal communication, and investigation. There is no minimum amount of time required before obtaining this rank.<br><br>

In order to obtain this rank, you must send an email to the OSINT Dojo with proof that you have completed all of the Rank Requirements listed below. You may use any previously completed work to meet the requirements of challenges for this rank. Be sure to send the email from the email you would like the Badgr badge to be issued to.<br> <br>

<h3>Rank Requirements</h3>
<b>1:</b> Participate in an OSINT CTF<br>
<b>2:</b> Attempt 2 OSINT challenges or quizzes of any kind<br>
<b>3:</b> Create and share a 2-minute video showcasing the steps you tool to solve a previous OSINT challenge<br>
<b>4:</b> Write and publish an article of at least 250 words showcasing steps you took to solve a previous OSINT challenge<br>
<b>5:</b> Introduce yourself to the OSINT community and let others know you are ready to learn by including the hashtag #OSINTDOJO`

  document.getElementById("studentrank").src = "/OSINTStudentLogo.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";  
 }
 
 function clickronin()
 {
 
   count = 2;
   
  document.getElementById("chosenrank").innerHTML =`RONIN TEXT`
  document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";
 }
 
 function clicksamurai()
 {
 
  count = 3;
  
  document.getElementById("chosenrank").innerHTML =`SAMURAI TEXT`
  document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";
 }
 
 function clickdaimyo()
 {
 
  count = 4;
  
  document.getElementById("chosenrank").innerHTML =`DAIMYO TEXT`
  document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";
 }
 
 function clickshogun()
 {
 
  count = 5;
  
  document.getElementById("chosenrank").innerHTML =`SHOGUN TEXT`
  document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo.svg";
 }
            
</script>
