---
layout: about
title: About
permalink: /
subtitle: # <a href='#'>Affiliations</a>. Address. Contacts. Moto. Etc.

social: false  # includes social icons at the bottom of the page

toc:
  sidebar: false
---

{%- include title.html -%}

<h2 id="about" class="fancy-heading">ABOUT</h2>

<div class="page-text">

<p>Robotic technology has proven to be an excellent solution for aiding humans in an ever-increasing number of scenarios: from domestic and urban routines to industrial tasks, robots reduce the workload burden on humans and their exposure to hazards. Despite the capabilities demonstrated in recent years, many obstacles remain to be overcome. New challenges arise from the increasing capabilities of advanced robotic platforms. The more complex and unstructured the environment, the more robots should be versatile and reliable to overcome obstacles, plan optimal motions, and reliably accomplish the designed tasks.</p>

<!-- <div style="margin-top: 50px; margin-bottom: 50px" class="container text-center">
  <div class="row">
    <div class="col">
      <img width="100%" src="assets/img/unitree_steppingdown3.png" alt="pic1">
    </div>
      <div class="col">
      <img width="100%" src="assets/img/anymal_rl.jpeg" alt="pic2">
    </div>
  </div>
</div> -->

<img style="margin-top: 50px; margin-bottom: 50px" width="100%" src="assets/img/centauro_walking.png" alt="pic1"/>

<p>This workshop continues to explore state-of-the-art advancements in control strategies that are behind the abilities of such robots, namely, planning and control of dynamic, whole-body motions. Pursuing the thread initiated with the <a href="https://events.pal-robotics.com/humanoids22-workshop">first edition</a> of this workshop, we will focus on trajectory optimization and optimal control: successful approaches that exploit the robotic systems' dynamics, particularly under-actuated ones. This second edition will also address links and synergies with machine learning approaches, e.g. reinforcement learning or deep learning, which are undeniably increasing their relevance and popularity for planning and control applications. Both strategies boil down to a minimization (or maximization) of a desired metric, resulting in a sequence of the most effective actions to take. However, they are fundamentally different approaches that exhibit inherent advantages and drawbacks. How do robotic systems benefit from these methods? Which are the properties shared by the two? How to combine these strategies? These questions will be addressed, soliciting a discussion to compare ideas and solutions from the invited speakers.</p>

<div style="margin-top: 50px; margin-bottom: 50px" class="container text-center">
  <div class="row">
    <div class="col">
      <img width="100%" src="assets/img/unitree_steppingdown3.png" alt="pic1">
    </div>
      <div class="col">
      <img width="100%" src="assets/img/anymal_rl.jpeg" alt="pic2">
    </div>
  </div>
</div>


</div>

<h2 id="speakers" class="fancy-heading">PROGRAM</h2>

<table class="program-table">
    <thead>
        <tr>
            <th>Time</th>
            <th>Section</th>
            <th>Speaker</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>8:45 - 9:00</td>
            <td>Welcome</td>
            <td>Organizers</td>
        </tr>
        <tr>
            <td>9:00 - 9:30</td>
            <td>Talk 1</td>
            <td></td>
        </tr>
        <tr>
            <td>9:30 - 10:00</td>
            <td>Talk 2</td>
            <td></td>
        </tr>
        <tr>
            <td>10:00 - 10:30</td>
            <td>Talk 3</td>
            <td></td>
        </tr>
        <tr>
            <td>10:30 - 11:00 </td>
            <td>Coffee Break</td>
            <td></td>
        </tr>
        <tr>
            <td>11:00 - 11:30</td>
            <td>Talk 4</td>
            <td></td>
        </tr>
        <tr>
            <td>11:30 - 12:00</td>
            <td>Talk 5</td>
            <td></td>
        </tr>
        <tr>
            <td>12:00 - 13:00</td>
            <td>Poster Session</td>
            <td>Accepted Authors</td>
        </tr>
        <tr>
            <td>13:00 - 14:00</td>
            <td>Lunch Break</td>
            <td></td>
        </tr>
        <tr>
            <td>14:00 - 14:30</td>
            <td>Talk 6</td>
            <td></td>
        </tr>
        <tr>
            <td>14:30 - 15:00</td>
            <td>Talk 7</td>
            <td></td>
        </tr>
        <tr>
            <td>15:00 - 15:30</td>
            <td>Talk 8</td>
            <td></td>
        </tr>
        <tr>
            <td>15:30 - 16:00</td>
            <td>Coffee Break</td>
            <td></td>
        </tr>
        <tr>
            <td>16:00 - 16:30</td>
            <td>Talk 9</td>
            <td></td>
        </tr>
        <tr>
            <td>16:30 - 17:15</td>
            <td>Final Discussion</td>
            <td>Oranizers + Speakers</td>
        </tr>
        <tr>
            <td>17:15 - 17:30</td>
            <td>Best Poster Award</td>
            <td></td>
        </tr>
        <tr>
            <td>19:00 - 22:00</td>
            <td>Social Dinner</td>
            <td>Organizers + Speakers + Finalists</td>
        </tr>
    </tbody>
</table>

<h2 id="speakers" class="fancy-heading">SPEAKERS</h2>
<div class="page-text">
<i>Click the play button on the top-right of each card to see the recorded talk!</i>
</div>
<div class="card-container">
  <div class="card hoverable" style="width: 250px; height: 440px">
    <a href="https://www.cs.washington.edu/people/postdocs/tassa">
    <img src="assets/img/yuval_tassa.jpg" alt="Yuval Tassa Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 17px">Yuval Tassa</h2>
      <h3 class="card-subtitle">Google DeepMind</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> Trajectory optimization with MuJoCo</p>          
    </div>
    {%- include pop-up.html
      id = "yuval_tassa_modal"
      title = 'Yuval Tassa' -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#yuval_tassa_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>

  <div class="card hoverable" style="width: 250px; height: 440px">
    <a href="https://www.dlr.de/rm/en/desktopdefault.aspx/tabid-3858/16537_read-29897/sortby-lastname/">
    <img src="assets/img/johannes_englsberger.jpg" alt="Johannes Englsberger Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 16px">Johannes Englsberger</h2>
      <h3 class="card-subtitle">DLR</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> Why I decided NOT to use MPC – a denier’s perspective</p>
    </div>
    {%- include pop-up.html
      id = "johannes_englsberger_modal"
      title = "Johannes Englsberger" -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#johannes_englsberger_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>

  <div class="card hoverable" style="width: 250px; height: 440px">
    <a href="https://sites.nd.edu/pwensing/">
    <img  src="assets/img/patrick_wensing.jpeg" alt="Patrick Wensing Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 17px">Patrick Wensing</h2>
      <h3 class="card-subtitle">University of Notre Dame</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> Accelerating MPC for dynamic locomotion: Exploiting structure, and letting learning guide the way</p>  
    </div>
    {%- include pop-up.html
      id = "patrick_wensing_modal"
      title = "Patrick Wensing" -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#patrick_wensing_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>

  <div class="card hoverable" style="width: 250px; height: 440px">
    <a href="https://mavt.ethz.ch/people/person-detail.MjI1NTcx.TGlzdC81NTksLTE3MDY5NzgwMTc=.html">
    <img src="assets/img/jean_pierre_sleiman.jpg" alt="Jean Pierre Sleiman Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 17px">Jean Pierre Sleiman</h2>
      <h3 class="card-subtitle">ETH</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> Whole-Body Motion Planning and Control for Multi-Contact Locomanipulation</p>
    </div>
    {%- include pop-up.html
      id = "jean_pierre_sleiman_modal"
      title = "Jean Pierre Sleiman" -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#jean_pierre_sleiman_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>

  <div class="card hoverable" style="width: 250px; height: 440px">
    <a href="https://members.loria.fr/SIvaldi/">
    <img src="assets/img/serena_ivaldi.jpg" alt="Serena Ivaldi Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 17px">Serena Ivaldi</h2>
      <h3 class="card-subtitle">Inria</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> Teleoperating humanoid robots: optimised controllers, contacts and human-like motions </p>
    </div>
    {%- include pop-up.html
      id = "serena_ivaldi_modal"
      title = "Serena Ivaldi" -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#serena_ivaldi_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>

  <div class="card hoverable" style="width: 250px; height: 440px">
    <a href = "https://cmastalli.github.io/">
    <img src="assets/img/carlos_mastalli.jpeg" alt="Carlos Mastalli Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 17px">Carlos Mastalli</h2>
      <h3 class="card-subtitle">Heriot-Watt University</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> Accelerating Algorithms for Numerical Optimization in Full-Dynamics MPC</p>
    </div>
    {%- include pop-up.html
      id = "carlos_mastalli_modal"
      title = "Carlos Mastalli" -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#carlos_mastalli_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>

  <div class="card hoverable" style="width: 250px; height: 440px">
    <a href = "https://webapps.unitn.it/du/it/Persona/PER0197808/Didattica">
    <img src="assets/img/andrea_del_prete.jpeg" alt="Andrea Del Prete Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 17px">Andrea Del Prete</h2>
      <h3 class="card-subtitle">Università di Trento</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> Integrating learning and trajectory optimization to achieve safe and efficient robot control</p>
    </div>
    {%- include pop-up.html
      id = "andrea_del_prete_modal"
      title = "Andrea Del Prete" -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#andrea_del_prete_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>

  <div class="card hoverable" style="width: 250px; height: 440px">
    <a href = "https://gepettoweb.laas.fr/index.php/Members/NicolasMansard">
    <img src="assets/img/nicolas_mansard.jpg" alt="Nicolas Mansard Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 17px">Nicolas Mansard</h2>
      <h3 class="card-subtitle">LAAS-CNRS</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> Whole-body MPC on real robots, by combining advanced solver and machine learning</p>
    </div>
    {%- include pop-up.html
      id = "nicolas_mansard_modal"
      title = "Nicolas Mansard" -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#nicolas_mansard_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>

  <div class="card hoverable" style="width: 250px; height: 440px">
    <a href = "#">
    <img src="assets/img/wang_xingxing.jpg" alt="Wang Xingxing Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 17px">Wang Xingxing</h2>
      <h3 class="card-subtitle">Founder & CEO of Unitree</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> AI-powered humanoid robot</p>
    </div>
    {%- include pop-up.html
      id = "wang_xingxing_modal"
      title = "Wang Xingxing" -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#wang_xingxing_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>
</div>

<h2 id="organizers" class="fancy-heading">ORGANIZERS</h2>


<div class="image-container">
<a href="https://www.iit.it/it/people-details/-/people/luca-rossini"> 
  <img class="hoverable" style="border-radius: 50%" src="assets/img/luca_rossini.png" alt="Prof. Luis Sentis Picture" width="200" /> 
  <figcaption style="color: var(--global-text-color)" class="image-caption">Luca Rossini<br>IIT</figcaption>
</a>
<a href="https://www.iit.it/it/people-details/-/people/francesco-ruscelli"> 
  <img class="hoverable" style="border-radius: 50%" src="assets/img/francesco_ruscelli.png" alt="Francesco Ruscelli Picture" width="200" /> 
  <figcaption style="color: var(--global-text-color)" class="image-caption">Francesco Ruscelli<br>IIT</figcaption>
</a>
<a href="https://members.loria.fr/EMingoHoffman/"> 
  <img class="hoverable" style="border-radius: 50%"  src="assets/img/enrico_mingo1.jpeg" alt="Enrico Mingo Hoffman Picture" width="200" /> 
  <figcaption style="color: var(--global-text-color)" class="image-caption">Enrico Mingo Hoffman<br>Inria</figcaption>
</a>
<a href="https://www.ae.utexas.edu/people/faculty/faculty-directory/sentis"> 
  <img class="hoverable" style="border-radius: 50%"  src="assets/img/luis_sentis.jpg" alt="Luis Sentis Picture" width="200" />   
  <figcaption style="color: var(--global-text-color)" class="image-caption">Luis Sentis<br>University of Texas <br> at Austin</figcaption>
</a>
<a href = "https://cmastalli.github.io/"> 
  <img class="hoverable" style="border-radius: 50%" src = "assets/img/carlos_mastalli.jpeg" alt = "Carlos Mastalli Picture" width ="200"/> 
  <figcaption style="color: var(--global-text-color)" class="image-caption">Carlos Mastalli<br>Heriot-Watt University</figcaption>
</a>

</div>

<h2 class="fancy-heading"> SPONSORS </h2>
<div class="social">
  <div class="contact-icons">
    {%- include sponsors.html -%}
  </div>
</div>

