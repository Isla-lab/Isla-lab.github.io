---
title: "ISLa - Members"
layout: gridlay
excerpt: "ISLa Members"
sitemap: false
permalink: /members/
---

# Group Members

 Multiple Master and Bachelor thesis are currently available in our research group. If interested, please email to [isla.univr@gmail.com](mailto:isla.univr@gmail.com) or to [alessandro.farinelli@univr.it](mailto:alessandro.farinelli@univr.it). Please specify which area interests you:

* Artificial Intelligence algorithms (Deep Reinforcement Learning) for Autonomous Surface Vehicles.
* Situation Awareness and Safe Navigation for Drones.
* Deep Reinforcement Learning for Robotic Systems in Complex Environments with Unity3D.
* Formal Verification methods for Deep Neural Networks.
* Monte Carlo Methods for solving POMDP

## Director
{% assign number_printed = 0 %}
{% for member in site.data.director %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="director col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive profile" style="float: left" />
  <h4>{{ member.name }}</h4>
  <a href="{{ member.website }}">Personal Website</a>
  <br/><i>{{ member.info }}</i>
  <ul style="overflow: hidden">
  
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}
  
  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}
  
  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}
  
  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}
 
  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}
  
  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Faculty
{% assign number_printed = 0 %}
{% for member in site.data.faculty %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <a href="{{ member.website }}">Personal Website</a>
  <br/><i>{{ member.info }}</i>
  <ul style="overflow: hidden">
  
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}
  
  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}
  
  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}
  
  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}
 
  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}
  
  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Research Fellow
{% assign number_printed = 0 %}
{% for member in site.data.postdoc %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <a href="{{ member.website }}">Personal Website</a>
  <br/><i>{{ member.info }}</i>
  <ul style="overflow: hidden">
  
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}
  
  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}
  
  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}
  
  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}
 
  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}
  
  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Ph.D. Students
{% assign number_printed = 0 %}
{% for member in site.data.phdstudents %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <a href="{{ member.website }}">Personal Website</a>
  <br/><i>{{ member.info }}</i>
  <h6>{{ member.expe }}</h6>
  <ul style="overflow: hidden">
  
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}
  
  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}
  
  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}
  
  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}
 
  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}
  
  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


<!--## Undergrad Students 


-->




<h3 style="color:blue;"> <u> Bachelor and Master students </u> </h3>

<table align="center" style="width:100%">

  <tr>
    <td> - Davide Corsi. Thesis title: "Safe Deep Reinforcement Learning: Enhancing the Reliability of Intelligent Systems". (PhD cycle XXXV).
      Davide Corsi is a Postdoctoral Associate at University o f California Irvine (updated on 2024).  </td>
    </tr>
    <tr>
    <td> - Adrià Fenoy. 
      Thesis title: "Combining Optimization and Machine Learning for the Formation of Collectives". (PhD cycle XXXV).
      Adrià Fenoy is an AI engineer at MeteoSim (updated on 2024) 
      </td>
      </tr>
      <tr>
    <td> - Giulio Mazzi. 
Thesis title: "Rule-Based Policy Interpretation and Shielding for Partially Observable Monte Carlo Planning" (PhD cycle XXXIV). </td>
  </tr>
  <tr>
    <td> - Enrico Marchesini. 
Thesis title: "Enhancing Exploration and Safety in Deep Reinforcement Learning". (PhD cycle XXXIV). Erico Marchesini is a Postdoctoral Associate at Massachusetts Institute of Technology (MIT) (updated on 2024).
 </td>
   </tr>
     <tr>
    <td> - Riccardo Sartea. 
Thesis title: "Active Malware Analysis based on reinforcement learning techniques". (PhD cycle XXXII). Riccardo Sartea is Data Scientist at Amazon Web Services (AWS) (updated on 2024). </td>
  </tr>
    <tr>
    <td> - Lorenzo Bottarelli. 
Thesis Title: "Optimizing Information Gathering for Environmental Monitoring Applications". (PhD Cycle XXXI). Lorenzo Bottarelli is head of Machine Learning at Ignitia AB (updated on 2024). </td>
  </tr>
    <tr>
    <td> - Masoume M. Raeissi. 
Thesis Title: "Modeling Supervisory Control in Multi-Robot Applications". (PhD cycle XXX). Masoume Raeissi is Research Associate (AI) at Wageningen University & Research (updated on 2024) </td>
  </tr>
    <tr>
    <td> - Filippo Bistaffa. 
Thesis Title: "Constraint Optimisation Techniques for Real-World Applications". (PhD Cycle XXVIII).
Filippo Bistaffa is tenured researcher at IIIA-CSIC (updated on 2024) </td>
 </tr>

</table>



 









