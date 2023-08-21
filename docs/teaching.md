---
layout: default
title: Teaching
---

# Physics 110A Fall 2023
* Week 2

# Physics 105 Spring 2023
Worksheets:
* [Week 2](https://jacoberl.github.io/assets/105/week%202%20worksheet.pdf)
* [Week 4](https://jacoberl.github.io/assets/105/week%204%20worksheet.pdf)
* [Week 7](https://jacoberl.github.io/assets/105/week%207%20worksheet.pdf)
* [Week 9](https://jacoberl.github.io/assets/105/week%209%20worksheet.pdf)
* [Week 15](https://jacoberl.github.io/assets/105/week%2015%20worksheet.pdf)
  
Solutions available upon request.


# Physics 137B Fall 2022
Worksheets:
{%assign counter=2%}
{% assign worksheet_files = site.static_files | where: "137b", true %}
{% for mypdf in worksheet_files %}
{% if counter == 6%}
 * [Week {{counter}}](https://jacoberl.github.io/{{mypdf.path}})
{% assign counter = counter | plus:1%}
{% endif %}
 {% assign counter = counter | plus:1%}
{% endfor %}

Solutions available upon request.
