---
layout: default
title: Socially Responsible Tech Lab
---
---

## Our Mission
---

Our vision is to make responsibility a central part of computing. We believe that each person, each project, and each decision can contribute towards positive social change. 

In the Socially Responsible Tech Lab, we study and shape tech though research, design, and community building. We take a human-centered approach to computer science because we believe that technology should be designed, developed, and deployed in ways that reduce harm and benefit humanity. We apply an interdisciplinary mixed-methods approach to studying the social impacts of current computing technology and to designing socially responsible computing technology. Some of the methods we use are interviews, surveys, algorithmic audits, systematic literature analysis, design-based research, usability experiments, etc. 

Computers are changing the world. We explore how computers can support socially responsible change.

If you’re interested in working on problems like responsible design and harm reduction in computing, you’re in the right place! 

***

## News

***

## Members
<ul>
    {% for member in site.data.members %}
        <span>
            <img src="{{member.image}}" alt="{{member.name}}'s headshot"  width="400" height="400" role="img"/>
            <br>
        </span>
         <p><a href="mailto:{{member.email}}">
            <b>{{ member.name }}</b>
         <\p>
        </a>
            {{ member.title }}
    {% endfor %}
</ul>

***

### Contact Us

<a href="mailto:ari.schlesinger@uga.edu" target="_blank" aria-label="ari.schlesinger@uga.edu">Contact Dr. Ari Schlesinger here</a>

***
