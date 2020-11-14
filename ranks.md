---
layout: template
filename: ranks.md
permalink: /ranks/
---
<center> <h1> RANKS </h1> </center>
<hr>

<center>
Click on a rank below to view the description and associated requirements.<br>
 
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
   if (count!=1) 
   {
    document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
   } 
}

function hoverroninrank() 
{
  document.getElementById("roninrank").src = "/OSINTRONINLogo.svg";
}

function unhoverroninrank() 
{
   if (count!=2) 
   {
    document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
   } 
}

function hoversamurairank() 
{
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo.svg";
}

function unhoversamurairank() 
{
   if (count!=3) 
   {
    document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
   } 
}

function hoverdaimyorank() 
{
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo.svg";
}

function unhoverdaimyorank() 
{
   if (count!=4) 
   {
    document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
   } 
}

function hovershogunrank() 
{
  document.getElementById("shogunrank").src = "/OSINTShogunLogo.svg";
}

function unhovershogunrank() 
{
   if (count!=5) 
   {
    document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";
   } 
}

function clickstudent()
 {
  count = 1;
 
  document.getElementById("chosenrank").innerHTML =`<h3>Rank Description</h3>Student is the first rank on your journey to becoming a better OSINT practitioner. Users in this level should be somewhat familiar with OSINT terms and methodology, if not, they are highly recommended to do research either on their own or via the Resources link to the left. At this level, users are being introduced to the different categories of challenges that are designed to strengthen their OSINT skills, particularly writing, verbal communication, and investigation. There is no minimum amount of time required before obtaining this rank.<br><br>

In order to obtain this rank, you must submit a rank up <a href="https://www.osintdojo.com/rankuprequest/">request</a> to the OSINT Dojo with proof that you have completed all of the Rank Requirements listed below. You may use any previously completed work to meet the challenge requirements for this rank. <br> <br>

<h3>Rank Requirements</h3>
<b>1:</b> Participate in an OSINT CTF<br>
<b>2:</b> Attempt 2 OSINT quizzes of any kind<br>
<b>3:</b> Create and share a 2-minute video showcasing the steps you took to solve a previous OSINT quiz<br>
<b>4:</b> Write and publish an article, tweet, or blog post of at least 250 words showcasing steps you took to solve a previous OSINT quiz<br>
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
   document.getElementById("chosenrank").innerHTML =`<h3>Rank Description</h3>Ronin is the second level within the OSINT Dojo. Those performing at the Ronin rank should be familiar with basic OSINT techniques and terms, and should be comfortable with searching for solutions to anything that they do not immediately understand. Users in this level will see their challenges increase in difficulty and they will be expected to perform at a slightly higher level than they did in the Student rank. Similar to the Student rank, challenges in the Ronin level heavily revolve around performing simple OSINT challenges and then using that experience to provide video or written products. Users must spend a minimum of 1 month in the Student level before applying for the Ronin rank.<br><br>

In order to obtain this rank, you must submit a rank up <a href="https://www.osintdojo.com/rankuprequest/">request</a> to the OSINT Dojo with proof that you have completed all of the Rank Requirements listed below. You may only use work completed while holding the Student level to meet the challenge requirements for this rank.<br> <br>

<h3>Rank Requirements</h3>
<b>1:</b> Rank in the top 75% of competitors or teams in an OSINT CTF<br>
<b>2:</b> Attempt 1 non-Geolocation-Based OSINT quiz<br>
<b>3:</b> Create and share a 2-minute video showcasing any OSINT topic or technique<br>
<b>4:</b> Write and publish an article, tweet, or blog post of at least 250 words showcasing steps you took to solve a previous OSINT quiz<br>
<b>5:</b> Find a new or recent OSINT article, technique, code repository, etc and share it with the OSINT Dojo community so we can add it to our resources list`

  document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";
 }
 
 function clicksamurai()
 {
 
  count = 3;
   
  document.getElementById("chosenrank").innerHTML =`<h3>Rank Description</h3>The third rank in the OSINT Dojo is Samurai. Users at this level should be familiar with many OSINT techniques, methodologies, and platforms, and may even already have a specialization in one or more areas. Those that reach this level will continue to hone their OSINT skills introduced in the Student and Ronin stages, while simultaneously reducing their reliance on OSINT challenges as prompts for video or writing challenges. Users are also expected to judge or provide some other form of volunteer assistance for an OSINT CTF to gain experience and learn how others perform the same OSINT tasks, though often using different techniques and methodologies. Users must spend a minimum of 2 months in the Ronin level before applying for the Samurai rank.<br><br>

In order to obtain this rank, you must submit a rank up <a href="https://www.osintdojo.com/rankuprequest/">request</a> to the OSINT Dojo with proof that you have completed all of the Rank Requirements listed below. You may only use work completed while holding the Ronin level to meet the challenge requirements for this rank.<br> <br>

<h3>Rank Requirements</h3>
<b>1:</b> Rank in the top 50% of competitors or teams in an OSINT CTF<br>
<b>2:</b> Be the first to successfully answer one OSINT quiz of any type<br>
<b>3:</b> Create and share a 4-minute video showcasing an OSINT technique or demonstration unrelated to an OSINT quiz<br>
<b>4:</b> Write and publish an article, tweet, or blog post of at least 500 words showcasing steps you took to solve a previous OSINT quiz<br>
<b>5:</b> Judge, or otherwise work as staff for an OSINT CTF`

  document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";
 }
 
 function clickdaimyo()
 {
 
  count = 4;
  document.getElementById("chosenrank").innerHTML =`<h3>Rank Description</h3>Daimyo is the fourth rank in the OSINT Dojo, and the first of the two senior ranks. Users at this level should no longer rely on simple OSINT challenges as a prompt for video or writing challenges, and instead should be looking to share their expertise with others. As part of this requirement, those applying for the Daimyo level are also required to provide some form of mentorship to another OSINT Dojo member at a rank below their own. A Daimyo also should have obtained enough experience to be able to provide commentary, answer questions, or otherwise hold a conversation regarding OSINT in a podcast, webcast, or similar setting. Users must spend a minimum of 4 months in the Samurai level before applying for the Daimyo rank.<br><br>

In order to obtain this rank, you must submit a rank up <a href="https://www.osintdojo.com/rankuprequest/">request</a> to the OSINT Dojo with proof that you have completed all of the Rank Requirements listed below. You may only use work completed while holding the Samurai level to meet the challenge requirements for this rank.<br> <br>

<h3>Rank Requirements</h3>
<b>1:</b> Rank in the top 25% of competitors or teams in an OSINT CTF<br>
<b>2:</b> Be the first to successful answer a non-geolocation OSINT quiz<br>
<b>3:</b> Speak as a guest regarding OSINT on a podcast, webcast, or similar<br>
<b>4:</b> Write and publish one OSINT related article not related to an OSINT quiz that contains at least 500 words<br>
<b>5:</b> Provide mentorship to another OSINT Dojo member of a lower rank`

  document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo2.svg";
 }
 
 function clickshogun()
 {
 
  count = 5;
  
document.getElementById("chosenrank").innerHTML =`<h3>Rank Description</h3>Shogun is the most senior rank in the traditional path of the OSINT Dojo. Users obtaining this level will have likely already made a significant impact on the OSINT community. At the Shogun level, users are expected to continue to hone their skills by attempting more difficult challenges and placing higher up in the list of competitors in OSINT CTFs. Those achieving the Shogun level should also have a strong enough technical understanding of several OSINT techniques or methodologies to be able to give a related talk at a virtual or in-person conference as well as create or contribute to an OSINT project at a technical level. Users must spend a minimum of 6 months in the Daimyo level before applying for the Shogun rank.<br><br>

In order to obtain this rank, you must submit a rank up <a href="https://www.osintdojo.com/rankuprequest/">request</a> to the OSINT Dojo with proof that you have completed all of the Rank Requirements listed below. You may only use work completed while holding the Daimyo level to meet the challenge requirements for this rank.<br> <br>

<h3>Rank Requirements</h3>
<b>1:</b> Rank in the top 10% of competitors or teams in an OSINT CTF<br>
<b>2:</b> Complete one of Sector35's OSINT quizzes<br>
<b>3:</b> Give an OSINT related presentation at a virtual or in person conference<br>
<b>4:</b> Write and publish one OSINT related article not related to an OSINT quiz that contains at least 1000 words<br>
<b>5:</b> Create a new, or contribute to an existing, OSINT tool, project, or code repository`

  document.getElementById("studentrank").src = "/OSINTStudentLogo2.svg";
  document.getElementById("roninrank").src = "/OSINTRONINLogo2.svg";
  document.getElementById("samurairank").src = "/OSINTSamuraiLogo2.svg";
  document.getElementById("daimyorank").src = "/OSINTDaimyoLogo2.svg";
  document.getElementById("shogunrank").src = "/OSINTShogunLogo.svg";
 }
            
</script>

