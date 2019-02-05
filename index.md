---
layout: page
id: home
---

# Digital Scholarship Research Institute

## Call for Applications

The Digital Scholarship Research Institute (DSRI) is a two-day intensive institute for Tri-Co faculty to explore interdisciplinary, digital scholarship research and teaching methods through hands-on workshops and guided practices. The DSRI is grounded in fundamentals, and we welcome both faculty new to digital scholarship and those interested in taking their skills to the next level. Participants can expect to gain experience with fundamental digital scholarship tools and methods including navigating your computer via the command line, cleaning messy data, version control, and sharing your work publicly while also learning about local digital scholarship communities and support.

Apply now. Review of applications begins on March 1, 2019. Notice will be sent to applicants by March *.

The DSRI is sponsored by *, *, and Bryn Mawr College’s LITS. Much of the curriculum was developed as part of the NEH-sponsored Digital Humanities Research Institute hosted at the CUNY Grad Center in June 2018. 

Because an essential aspect of the DSRI is building community among Tri-Co faculty members interested in digital scholarship, participants are expected to commit to attending the full two-day experience at Bryn Mawr College from May 6-7, 2019 and to attend all of the workshops, seminars, and events during this time.  (See childcare options provided or recommended by [Bryn Mawr](https://www.brynmawr.edu/humanresources/daycare-assistance), [Haverford](https://www.haverford.edu/sites/default/files/Office/Provost/HC-Daycare-Recommendations.pdf), and [Swarthmore](https://www.swarthmore.edu/human-resources/child-and-eldercare-resources.)

---

## Tentative Schedule

### Monday, May 6, 2019

8:15-9:00   Registration & Breakfast

9:00-9:30   Introductions, Overview

9:30-10:45  Introduction to the Command Line

10:45-11:00     Break 

11:00-12:00     Introduction to the Command Line, Part II

12:00-1:30  Lunch 

1:30-2:45   Tidy Data

2:45-3:00   Break

3:00-4:00   Tidy Data

4:00-5:00   Daily wrap-up and Happy Hour Installations

### Tuesday, May 7, 2019

8:15-9:00   Breakfast

9:00-9:15   Introductions, Overview

9:15-10:45  Git/GitHub for Scholars

10:45-11:00     Break

11:00-12:00     Git/GitHub for Scholars

12:00-1:30  Lunch 

1:30-2:45   Introduction to HTML/CSS

2:45-3:00   Break

3:00-4:30   Introduction to HTML/CSS

4:30-5:00   Wrap-up

5:00-6:30   Reception

---

## Workshop Descriptions

### Command Line

The command line is a powerful, text-based way to interact with your computer. You can automate tasks such as creating, copying, and converting files, set up your programming environment, run programs, control other computers remotely, and access programs and utilities that do not have graphical equivalents. In this introduction, we will learn common commands to explore and manipulate a simple data set. By the end of the session, we'll be able to navigate your computer, create and manipulate files, and transform text-based data using only the command line. Stepping away from a point-and-click workflow, we move into an environment where we have more minute control over each task we'd like the computer to perform. In addition to being a useful tool in itself, the command line gives us access to a second set of programs and utilities and is a complement to learning programming.

### Tidy Data (with OpenRefine?)

By the end of the session, we’ll be introduced to a flexible tool and strategies for taking very different kinds of information and creating well-formed data, data that can then be used for analysis or visualization. [placeholder]

### Intro to git/GitHub

Git is a tool for managing changes to a set of files. It allows users to recover earlier versions of a project, and collaborate with other contributors. GitHub is a web-based platform that provides access to open source repositories and facilitates collaboration on files, code, or datasets. This session will introduce participants to version control and collaboration using Git and GitHub, and demonstrate their use in digital projects.

---

### Why learn the command line?
- [ProfHacker](https://www.chronicle.com/blogs/profhacker/the-profhacker-guide-to-the-command-line/36125)
- [Programming Historian](https://programminghistorian.org/en/lessons/intro-to-bash)

### Why learn to keep your data clean and tidy?
- [Programming Historian](https://programminghistorian.org/en/lessons/cleaning-data-with-openrefine#why-should-historians-care-about-data-quality)

### Why learn Git and GitHub?
- [PhDComics](http://phdcomics.com/comics/archive_print.php?comicid=1531)
- [Version Control and Academic Writing](https://www.colinmclear.net/posts/versioncontrol/)

---

## Course Instructors

<div class="contributors-gallery">
{% assign contributors = site.data.contributors %}

{% for contributor in contributors %}

<div class="contributor">
<div class="avatar" style="background-image:url({{ contributor[1].image | prepend: 'images/'; }});" alt="{{ contributor[1].name }}"></div>
<div class="bio">
{{ contributor[1].name | prepend: "<h3>" | append: "</h3>" }}
{{ contributor[1].bio | prepend: "<p>" | append: "</p>" }}
</div>
<div class="clearfix"></div>
</div>
{% endfor %}
</div>