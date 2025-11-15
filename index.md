# My Learning Blog 

Welcome to my personal documentation space

---

##  Explore by Category

- [warm-up](archive.html#warm-up)

> [📁 Blog Archive](archive.html).

---

##  Featured Learning Module
Under Construction
---

###  About Me

Hi, I'm **Reza** — **Soccer** is in my **Blood**.  
This blog documents my continuous learning journey.


---

### ❤️ A Dedication

> **To my father**  
> Who recently passed away — my passion for soccer and coaching comes from him,  
> and this blog is a way to honor his influence and memory.

*In his memory, I keep learning — one post at a time.*
— *Reza*

---

##  Latest Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) — *{{ post.date | date: "%B %Y" }}*
{% endfor %}

---
