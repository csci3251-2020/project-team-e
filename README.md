# Introduction
Hello! This is team E!
In this project, we will implement what we have learned in this course to complete 8 different tasks, including:
1. Starting issues
2. Project board
3. Set up readme.md 
4. Show your team to the Internet
5. Keep checking... 
6. Write C code 
7. Get a status badge
8. Promote your repo

# Code
```c
{% include_relative code.c %}
```
![](https://github.com/csci3251-2020/project-team-e/workflows/Task6_v1_TeamE/badge.svg)

# Contributors
{% for students in site.stu %}
* <img src="{{ students.image }}" width="50" height="50"> <span>@{{students.user}}</span> ({{ students.name }})
  * {{ students.content}}

{% endfor %}
Last updated: {{ site.time }}
