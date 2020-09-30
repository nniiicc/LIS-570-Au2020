---
layout: page
title: Research, Assessment, & Design  
---

LIS 570 is an introduction to the design of research projects, and the use of research methods to conduct evaluation in library and information science.

It's helpful to think of this course a *survey* of research and evaluation in LIS. Just as a *survey course* in literature or history is meant to give a general overview, so too is LIS 570 with respect to methods and evaluation.

# Schedule

**Lecture**: Video lectures will be posted each Friday at 11am PST.

**Class Discussion**:
Each week your TA's and I will host a 1 hour course discussion. The discussion will be an opportunity for you to offer thoughts, pose questions, or debate with us about that week's topic.

Discussion times (Pacific Standard Time):

- Mondays, 8:30 AM - [Zoom Link]( https://washington.zoom.us/j/94982906196)
- Tuesdays, 10:30 AM  [Zoom Link](https://washington.zoom.us/j/94422099280)

**Office hours**: Office hours with TA's are by appointment.

- Section A, Mondays at 9:30 AM - [Zoom Link]()
- Section B, Fridays at 4 PM  - [Zoom Link](https://washington.zoom.us/j/94989269902?pwd=THJveEpJNmp6b1NmRDlwMmZVOW11Zz09)

If you need to schedule a meeting with Dr. Weber use this [link](https://calendly.com/nmweber/15min).

**Weekly Topics**
<ul>
{% assign lectures = site['2020'] | sort: 'date' %}
{% for lecture in lectures %}
    {% if lecture.phony != true %}
        <li>
        <strong>{{ lecture.date | date: '%-m/%d' }}</strong>:
        {% if lecture.ready %}
            <a href="/LIS-570-Au2020/{{ lecture.url }}">{{ lecture.title }}</a>
        {% else %}
            {{ lecture.title }} {% if lecture.noclass %}[no class]{% endif %}
        {% endif %}
        </li>
    {% endif %}
{% endfor %}
</ul>

Video recordings of the lectures are available on pages throughout this course site and [on YouTube](https://www.youtube.com/playlist?list=PLbfZ2tKmriI7wsTY0fusl6OCrJsdhXSsr).

# About the class

**Staff**: This class is taught by [Nic](http://nicweber.info), and two TA's - [Claire]() and [Wan-Chen](https://wcleeblog.wordpress.com/).

**Questions**: See the FAQ page above


## Acknowledgements

Thanks and appreciation to Ricardo Gomez for sharing materials related to his teaching of this class, [@tttkay](https://twitter.com/tttkay) for the 'Black Excellence in LIS' reading list which informed many of the readings used here.  

---

<div class="small center">
<p><a href="https://github.com/nniiicc/LIS-570-Au2020">Source code</a>.</p>
<p>Licensed under CC BY-NC-SA.</p>
<p>See <a href="/license/">here</a> for info on license</p>
</div>
