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
<div>
  <p><img src="{{ students.image }}" width="50" height="50"> <span>@{{students.user}}</span> ({{ students.name }})</p>  
  <p style="margin-left: 10px;">{{ students.content}}</p>
</div>
{% endfor %}
