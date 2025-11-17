---
layout: page
title: "Teaching"
permalink: /teaching/
---

# Teaching Experience

Below is a summary of the teaching roles I have held at **San Jose State University**, where I supported graduate-level engineering instruction in AI, Machine Learning, and Computer Vision.

All detailed teaching experience pages are listed automatically from the teaching collection.

---

## 🧑‍🏫 Teaching Roles

{% for item in site.teaching %}
### [{{ item.title }}]({{ item.url }})
- **Course Type:** {{ item.type }}
- **Institution:** {{ item.venue }}
- **Term:** {{ item.date | date: "%B %Y" }}
{% endfor %}

---

If you would like more details about any particular teaching experience, click on the individual entries above.
