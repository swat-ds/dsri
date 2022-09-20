---
layout: page
id: home
---

# About DSRI

The TriCo Digital Scholarship Research Institute is an intensive, cohort-based learning program developed and taught by the TriCo Libraries Digital Scholarship Group. Over the course of two days of workshops, discussions, and project showcases, participants gain experience with fundamental digital scholarship tools and methods but also explore project support and grant opportunities in the Trico and beyond, crafting potential projects and digital assignments, and wayfinding through the maze of possible tools, services, and platforms for digital research. All TriCo faculty and staff are welcome to apply, whether they are new to digital scholarship or interested in taking existing skills to the next level.


### Updates

Due to staffing issues, the 2022 Institute has been cancelled.  Stay tuned for an announcement about the next institute to take place in Spring 2023. 

TriCo DS will be hosting a get-together for faculty and staff on **December 8, 2022** (4:30-6:00 PM). It's an opportunity to learn about current projects and programs (including the DSRI) and get to know the librarians and technologists who support digital scholarship at Bryn Mawr, Haverford, and Swarthmore. 

<button role="button" class="button-blue" aria-label="open registration form">
    <a href="https://forms.gle/En41yVdMQ5HJDWtZA">RSVP here</a>
</button> 

Questions? Email Alice McGrath at amcgrath1@brynmawr.edu


### Past institutes

- [2021 Institute held remotely](2021)
- [2019 Institute at Bryn Mawr College](2019)

<!--
---

## Schedule

---
-->

## Team

<div class="contributors-gallery">
{% assign contributors = site.data.contributors %}

{% for contributor in contributors %}

<div class="contributor">
<div class="avatar" style="background-image:url({{ contributor[1].image | prepend: 'images/' }});" alt="{{ contributor[1].name }}"></div>
<div class="bio">
<p>
<strong>{{ contributor[1].name }}</strong>
{{ contributor[1].bio }}
</p>
</div>
<div class="clearfix"></div>
</div>
{% endfor %}
</div>

*The DSRI is sponsored by Bryn Mawr College’s LITS, Haverford College Libraries, and Swarthmore Libraries. The Tri-Co DSRI was developed as part of the NEH-sponsored [Digital Humanities Research Institute](http://dhinstitutes.org/) hosted at the CUNY Grad Center in June 2018.*

[![digital humanities research institute logo](images/DHRI-03.svg)](http://dhinstitutes.org/)
[![national endowment for the humanities logo](images/NEH_stacked_logo-01_full-color.jpg)](https://www.neh.gov/)
{: .logos}
