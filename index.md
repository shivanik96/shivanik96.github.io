---
layout: page
title: "Home"
class: home
---

# Hi, I'm Shivani Kumar

<div class="columns" markdown="1">

<div class="intro" markdown="1">

I'm a Postdoctoral Research Fellow at the [BlaBlaBlab](https://blablablab.si.umich.edu/) at [University of Michigan](https://umich.edu/), where I am working with [Dr.   David Jurgens](https://jurgens.people.si.umich.edu/) on culturally enriched and morally refined language models. I completed my PhD from the [LCS2 Lab](https://lcs2.in/), advised by [Dr. Tanmoy Chakraborty](https://www.tanmoychak.com/), from [IIITD](https://www.iiitd.ac.in/), before which I had completed my masters (M.Sc.) and bachelors (B.Sc.) from [University of Delhi](https://www.du.ac.in/).

During my PhD, I worked in the are of conversational AI, exploring the emotional nuances of dialogue — capturing everything from emotions, humour, and sarcasm to the unique essence of each speaker.

<!-- In my PhD, I worked in the area of conversational AI, with a focus on affective traits of the dialogue, such as emotions, humour, sarcasm, and speaker profile. -->

<!-- During my PhD, I interned at the MDSR lab at [Adobe Systems](https://www.adobe.com/) under the mentorship of [Dr. Sumit Bhatia](https://scholar.google.com/citations?user=8HVTWNkAAAAJ&hl=en&oi=ao) and [Mr. Milan Aggarwal](https://scholar.google.com/citations?user=YiMNG_QAAAAJ&hl=en), where I worked on creating a dialogue specific foundational model. -->

</div>

<div class="me" markdown="1">
<picture>
  <source srcset='/images/shivani.jpg' type='image/webp' />
  <img
    src='/images/shivani.jpg'
    alt='Shivani Kumar'>
</picture>

{:.no-list}
* <a href="mailto:{{ site.email }}">{{ site.email }}</a>
* <a href="https://www.linkedin.com/in/shivani-kumar-033780166" target="_blank"> <i class="fa-brands fa-linkedin"></i> </a> <a href="https://scholar.google.com/citations?user=pkUmpskAAAAJ&hl=en&authuser=2" target="_blank"> <i class="ai ai-google-scholar-square ai-1x"></i> </a> <a href="https://github.com/shivanik96" target="_blank"> <i class="fa-brands fa-github"></i> </a> <a href="https://x.com/Shivani_220" target="_blank"> <i class="fa-brands fa-twitter"></i> </a>
</div>

</div>


<!-- 
## Featured <a href="{{ "/projects/" | relative_url }}">Projects</a>

<div class="featured-projects">
  {% assign sorted_projects = site.data.projects | sort: 'highlight' %}
  {% for project in sorted_projects %}
    {% if project.highlight %}
      {% include project.html project=project %}
    {% endif %}
  {% endfor %}
</div>

<a href="{{ "/projects/" | relative_url }}" class="button">
  <i class="fas fa-chevron-circle-right"></i>
  Show More Projects
</a>

## Featured <a href="{{ "/publications/" | relative_url }}">Publications</a>

<div class="featured-publications">
  {% assign sorted_publications = site.publications | sort: 'year' | reverse %}
  {% for pub in sorted_publications %}
    {% if pub.highlight %}
      <a href="{{ pub.pdf }}" class="publication">
        <strong>{{ pub.title }}</strong>
        <span class="authors">{% for author in pub.authors %}{{ author }}{% unless forloop.last %}, {% endunless %}{% endfor %}</span>.
        <i>{% if pub.venue %}{{ pub.venue }}, {% endif %}{{ pub.year }}</i>.
        {% for award in pub.awards %}<br/><span class="award"><i class="fas fa-{% if award == "Best Paper Award" %}trophy{% else %}award{% endif %}" aria-hidden="true"></i> {{ award }}</span>{% endfor %}
      </a>
    {% endif %}
  {% endfor %}
</div>

<a href="{{ "/publications/" | relative_url }}" class="button">
  <i class="fas fa-chevron-circle-right"></i>
  Show All Publications
</a>
 -->