---
layout: page
title: Résumé
permalink: /about/
weight: 1
---

# **Résumé**

<br/>
<h4><i class="fas fa-user-alt"></i> Profile</h4>
Currently living in Berlin, enrolled in the 2nd Semester and pursuing a MSc Degree in Media and Computer Science at the Humboldt University of Berlin, Germany.

<br/>
<h4><i class="fas fa-tools"></i> Programming Language & Technologies</h4>
<ul>
<li>HTML, CSS, JavaScript, Java</li>
<li>Python (Data Scraping, Data Analysis)</li>
<li>SQL, MySQL, PostgreSQL</li>
<li>Git-/Hub/Lab, SourceTree, Jira, Trello, Slack</li>
<li>IntelliJ, Visual Studio Code, Android Studio, PyCharm</li>
<li>Adobe (XD, Photoshop, Premiere, Pro, After Effects, Lightroom, Audition)</li>
</ul>

<br/>
<h4><i class="fas fa-globe"></i> Languages</h4>
<ul>
<li>Indonesian – Native language</li>
<li>English (good) – UNIcert II</li>
<li>German (good) – DSH 2</li>
</ul>


<br/>
<h4><i class="fas fa-briefcase"></i> Work Background</h4>
<div class="row">
{% include about/work-background.html %}
</div>

<br/>
<h4><i class="fas fa-graduation-cap"></i> Education Background</h4>
<div class="row">
{% include about/education-background.html %}
</div>

<br/>
<h4><i class="fas fa-award"></i> Achievement</h4>
{% capture carousel_images %}
https://user-images.githubusercontent.com/33756873/73468506-2e04cf80-4385-11ea-9ccf-8df7b99fded4.jpg
https://user-images.githubusercontent.com/33756873/73469623-f1d26e80-4386-11ea-9795-28f54ead2f4e.jpg
https://user-images.githubusercontent.com/33756873/73469742-2514fd80-4387-11ea-934c-52a982402fb9.jpg
{% endcapture %}

{% capture carousel_texts %}
"The Winner 3rd Place Award Gastro Hackathon 2019 | A project with title "hacking the taste" is about filtering the ingredients in menu for allergens. Hackathon was organized by Dishtracker and the GAST Messe in Salzburg, Austria."
"The Winner 2nd Place Award ThinkQuest International Competition 2011 | A project with an entry titled "Make Plastics and Papers Become the Earth Friends!" organized by Oracle Education Foundation in San Fransisco, California, USA."
"Participants of Jakarta International Marathon 10K-2011 South West Monas Atrium, Indonesia. I was 16 years old, freshman in High School."
{% endcapture %}

{% include elements/carousel.html %}