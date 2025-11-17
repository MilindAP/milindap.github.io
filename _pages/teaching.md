---
layout: page
title: "Teaching"
permalink: /teaching/
---

# Teaching Experience

Below is a summary of the teaching roles I have held at  
**San Jose State University**, supporting graduate-level engineering instruction in:

- Artificial Intelligence  
- Machine Learning  
- Computer Vision  
- Computer Architecture  

All detailed teaching pages are pulled automatically from the **teaching collection**.

---

## 🧑‍🏫 Teaching Roles

{% assign sorted_teaching = site.teaching | sort: "date" | reverse %}

{% for item in sorted_teaching %}
### <a href="{{ item.url }}">{{ item.title }}</a>

- **Course Type:** {{ item.type }}
- **Institution:** {{ item.venue }}
- **Term:** {{ item.date | date: "%B %Y" }}
- **Location:** {{ item.location }}

---

{% endfor %}

If you would like deeper details about any teaching experience, click on the individual entries above.
