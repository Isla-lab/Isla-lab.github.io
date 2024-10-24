---
title: "ISLa - Members"
layout: gridlay
excerpt: "ISLa Members"
sitemap: false
permalink: /members/
---

# Group Members
Multiple Master's and Bachelor's thesis are currently available in our research group. If interested, please email to [alessandro.farinelli@univr.it](mailto:alessandro.farinelli@univr.it). Please specify your area of interest:

* Artificial Intelligence algorithms for Autonomous Surface Vehicles.
* Deep Reinforcement Learning for Robotic Systems in Complex Environments with Unity3D.
* Situation Awareness and Safe Navigation for Drones.
* Formal Verification methods for Deep Neural Networks.
* Neurosymbolic AI.
* Monte Carlo Methods for solving POMDP.

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




<h3 style="color:blue;"> <u> Alumni </u> </h3>

<table align="center" style="width:100%">

  <tr>
    <td> - <b>Maddelena Zuccotto</b>. Thesis title: "Learning in Monte Carlo Tree Search Planning". (PhD cycle XXXV).</td>
  </tr>
  <tr>
    <td> - <b>Davide Corsi</b>. Thesis title: "Safe Deep Reinforcement Learning: Enhancing the Reliability of Intelligent Systems". (PhD cycle XXXV).
      Davide Corsi is a Postdoctoral Associate at University of California Irvine (updated on 2024).  </td>
    </tr>
    <tr>
    <td> - <b>Adrià Fenoy</b>. 
      Thesis title: "Combining Optimization and Machine Learning for the Formation of Collectives". (PhD cycle XXXV).
      Adrià Fenoy is an AI engineer at MeteoSim (updated on 2024) 
      </td>
      </tr>
      <tr>
    <td> - <b>Giulio Mazzi</b>. 
  Thesis title: "Rule-Based Policy Interpretation and Shielding for Partially Observable Monte Carlo Planning" (PhD cycle XXXIV). </td>
  </tr>
  <tr>
    <td> - <b>Enrico Marchesini</b>. 
Thesis title: "Enhancing Exploration and Safety in Deep Reinforcement Learning". (PhD cycle XXXIV). Enrico Marchesini is a Postdoctoral Associate at Massachusetts Institute of Technology (MIT) (updated on 2024).
 </td>
   </tr>
     <tr>
    <td> - <b>Riccardo Sartea</b>. 
Thesis title: "Active Malware Analysis based on reinforcement learning techniques". (PhD cycle XXXII). Riccardo Sartea is Data Scientist at Amazon Web Services (AWS) (updated on 2024). </td>
  </tr>
    <tr>
    <td> - <b>Lorenzo Bottarelli</b>. 
Thesis Title: "Optimizing Information Gathering for Environmental Monitoring Applications". (PhD Cycle XXXI). Lorenzo Bottarelli is head of Machine Learning at Ignitia AB (updated on 2024). </td>
  </tr>
    <tr>
    <td> - <b>Masoume M. Raeissi</b>. 
Thesis Title: "Modeling Supervisory Control in Multi-Robot Applications". (PhD cycle XXX). Masoume Raeissi is Research Associate (AI) at Wageningen University & Research (updated on 2024) </td>
  </tr>
    <tr>
    <td> - <b>Filippo Bistaffa</b>. 
Thesis Title: "Constraint Optimisation Techniques for Real-World Applications". (PhD Cycle XXVIII).
Filippo Bistaffa is tenured researcher at IIIA-CSIC (updated on 2024) </td>
 </tr>

</table>



 









