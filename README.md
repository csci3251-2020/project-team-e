# Introduction
Hello! This is team E!
In this project, we will implement what we have learned in this course to complete 8 different tasks, including:
* Handle issues
* Create new projects
* Write README.md
* Create and approve pull requests
* And more!
# Code
# Contributors
{% for stu in site.stu %}
  <h2>{{ stu.user }} - {{ stu.image }} - {{ stu.name }}</h2>
  <p>{{ stu.content | markdownify }}</p>
{% endfor %}
