---
layout: page
title: About
permalink: /about/
---

This blog is maintained by Team No Internet Access.

No Internet Access is a Newbie CTF team from National Institute of Technology Karnataka, Surathkal. We hope you find these write ups useful. We have a lot of fun participating in CTF contests, we hope you do too.

Good luck, have fun and happy hacking!
For any questions and feedbacks please mail us or post it in the comment section. We'd love to hear what you guys think and learn from you.


## Members
{% for author in site.authors %}
[{{ author[1].display_name }}](http://github.com/{{author[1].github}}) 
({{ author[1].name }})
{% endfor %}


