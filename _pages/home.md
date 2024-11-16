---
title: Gao Meng Group at HKBU
layout: homelay
excerpt: Home
sitemap: false
permalink: "/"
---

<style>
    .main-container {
        display: flex;
        gap: 30px;
        align-items: flex-start;
    }
    
    .content-column {
        flex: 2;
    }
    
    .news-column {
        flex: 1;
        max-width: 350px;
        position: sticky;
        top: 20px;
    }
    
    .news-container {
        background-color: #f8f9fa;
        padding: 15px;
        border-radius: 8px;
    }
    
    .news-header {
        color: #333;
        padding: 10px 0;
        font-size: 1.5em;
        font-weight: bold;
        border-bottom: 2px solid #ddd;
        margin-bottom: 15px;
    }
    
    .news-item {
        margin-bottom: 20px;
        padding-bottom: 15px;
        border-bottom: 1px solid #eee;
    }
    
    .news-date {
        color: #666;
        font-size: 0.9em;
        margin-bottom: 5px;
    }
    
    .news-title {
        color: #0056b3;
        text-decoration: none;
        font-size: 1em;
        line-height: 1.4;
        display: block;
    }
    
    .news-title:hover {
        color: #003d82;
        text-decoration: underline;
    }
    
    .see-all {
        text-align: right;
        margin-top: 15px;
    }
    
    .see-all a {
        color: #0056b3;
        text-decoration: none;
        font-size: 0.9em;
    }
    
    @media (max-width: 992px) {
        .main-container {
            flex-direction: column;
        }
        .news-column {
            max-width: 100%;
        }
    }
</style>

<div class="main-container">
    <div class="content-column">
        We are the Air Quality and Atmospheric Chemistry Modeling Group at Hong Kong Baptist University. Our researches focus on Chemistry-Climate Interactions, Environmental Health, Climate Change Mitigation. The group uses global and regional models with observations to study the formation mechanisms and long-term trends of air pollution, and its interactions with weather/climate systems.

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
                    <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/1.png" alt="Slide 1" />
                </div>
                <div class="item">
                    <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/2.png" alt="Slide 2" />
                </div>
                <div class="item">
                    <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/3.png" alt="Slide 3" />
                </div>
                <div class="item">
                    <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/4.png" alt="Slide 4" />
                </div>
                <div class="item">
                    <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/5.png" alt="Slide 5" />
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

        {% comment %}
        We usually have openings for new PhD students, Postdocs, Master students, and undergradate students to join the team [(check here)]({{ site.url }}{{ site.baseurl }}/openings) !
        {% endcomment %}
    </div>
    
    <div class="news-column">
        <div class="news-container">
            <div class="news-header">
                News
            </div>
            
            <div class="news-item">
                <div class="news-date">26. Aug 2024</div>
                <a href="#" class="news-title">
                    祝贺芬嘉茵在第三届大气环境化学博士生学术会议中获得优秀报告奖！
                </a>
            </div>

            <div class="news-item">
                <div class="news-date">10. Jul 2024</div>
                <a href="#" class="news-title">
                    祝贺邓笑获得北京大学环境科学与工程学院直博保送资格！
                </a>
            </div>

            <div class="news-item">
                <div class="news-date">7. Jun 2024</div>
                <a href="#" class="news-title">
                    祝贺王浩霖（博士）、刘思怡（本科）获得2024年度中山大学校级优秀毕业生奖
                </a>
            </div>

            <div class="see-all">
                <a href="#">... see all News</a>
            </div>
        </div>
    </div>
</div>
