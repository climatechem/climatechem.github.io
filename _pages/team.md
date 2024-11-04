---
title: People
layout: gridlay
excerpt: 'Team members'
sitemap: false
permalink: "/team/"
---


<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="5000" data-pause="hover" >
	
    <!-- Menu -->
    <ol class="carousel-indicators">
        <li data-target="#carousel" data-slide-to="0" class="active"></li>
	<li data-target="#carousel" data-slide-to="1"></li>
	<li data-target="#carousel" data-slide-to="2"></li>
 	<li data-target="#carousel" data-slide-to="3"></li>
  	<li data-target="#carousel" data-slide-to="4"></li>
	    
    </ol>

    <!-- Items -->
    <div class="carousel-inner" markdown="0">

	<div class="item active">
            <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/a1.jpg" alt="Slide 0" />
	    <div class="carousel-caption d-none d-md-block">
    		<p>2024 Group Photo</p>
    		<p>From left to right: </p>
  	    </div>  
        </div> 

	<div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/a2.jpg" alt="Slide 1" />
	    <div class="carousel-caption d-none d-md-block">
    		<p>Group celebrating the Year of the Loong!</p>
  	    </div>  
        </div> 
	
 	<div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/a3.jpg" alt="Slide 2" />
	    <div class="carousel-caption d-none d-md-block">
    		<p>Group celebrating the Year of the Rabbit!</p>
  	    </div>  
        </div>   
	  
	<div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/a4.jpg" alt="Slide 3" />
	    <div class="carousel-caption d-none d-md-block">
    		<p>2022 Group Photo</p>
  	    </div>  
        </div> 
	    
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/a5.jpg" alt="Slide 4" />
	    <div class="carousel-caption d-none d-md-block">
    		<p>2021 Group Photo</p>
    		<p>From left to right: </p>
  	    </div>  
        </div>
	
	   
        
    </div>
  <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#carousel" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>


## Group Leader

{% assign number_printed = 0 %}
{% for member in site.data.team_0 %}


{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}


<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <br>Office: {{ member.office }}<br>Tel: {{ member.tel }}      <br>
		Email: <{{ member.email }}></i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
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

{% comment %}
[Full CV (as of April 2024)](CV.pdf) 
	{% endcomment %}

## Current Group Members

{% assign number_printed = 0 %}
{% for member in site.data.team_1 %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="28%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>Email: {{ member.email }}</i>
  <ul style="overflow: hidden">
	  
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}
  
  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
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

### Co-supervised students in [Prof. Wen Zhou](https://aos.fudan.edu.cn/97/c3/c14809a432067/page.htm)'s group at Fudan University

{% assign number_printed = 0 %}
{% for member in site.data.team_10 %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="28%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>Email: {{ member.email }}</i>
  <ul style="overflow: hidden">
		
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


{% comment %}
### Master and Undergraduate Students
{% for member in site.data.team_2 %}
  <h5>{{ member.name }},       <i>{{ member.info }}</i></h5>
{% endfor %}
{% endcomment %}

## Alumni
{% assign number_printed = 0 %}
{% for member in site.data.team_3 %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}</i>
  {% if member.linkable == 1 %}
  <i>Now: <a href="{{ member.link }}">{{ member.now }}</a></i>
  {% endif %}
  {% if member.linkable == 0 %}
  <i>Now: {{ member.now }}</i>
  {% endif %}
  <ul style="overflow: hidden">
		
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
	
