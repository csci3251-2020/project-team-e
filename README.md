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
{% for students in site.stu %}
  >><img src="students.image" alt="image"><h2>@{{ students.user }}({{ students.name }})</h2>
     >>{{ students.content | markdownify }}
{% endfor %}
