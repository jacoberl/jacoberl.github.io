---
layout: default
title: Teaching
---

# Physics 110A Fall 2023
* [Week 2](https://jacoberl.github.io/assets/110a/week-2-worksheet.pdf)
* Week 3: We used the same worksheet as last week.
* [Week 4](https://jacoberl.github.io/assets/110a/week-4-worksheet.pdf)
* [Week 5](https://jacoberl.github.io/assets/110a/week-5-worksheet.pdf)
* [Week 6](https://jacoberl.github.io/assets/110a/week-6-worksheet.pdf)
* [Week 8](https://jacoberl.github.io/assets/110a/week-8-worksheet.pdf)
* [Week 9](https://jacoberl.github.io/assets/110a/week-9-worksheet.pdf)
* [Week 10](https://jacoberl.github.io/assets/110a/week-10-worksheet.pdf)
* [Week 11](https://jacoberl.github.io/assets/110a/week-11-worksheet.pdf)
* [Week 12](https://jacoberl.github.io/assets/110a/week-12-worksheet.pdf)
* [Week 13](https://jacoberl.github.io/assets/110a/week-13-worksheet.pdf)
* [Week 15](https://jacoberl.github.io/assets/110a/week-15-worksheet.pdf)

Solutions available upon request.

## Review Sessions
[Midterm Review](https://jacoberl.github.io/assets/110a/review-problems-1.pdf)

[Final Review](https://jacoberl.github.io/assets/110a/review-problems-2.pdf)

Solutions available upon request.

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
{% assign counter = counter | plus:1%}
{% endif %}
* [Week {{counter}}](https://jacoberl.github.io/{{mypdf.path}})
{% assign counter = counter | plus:1%}
{% endfor %}

Review Sessions:
* [2nd midterm](https://jacoberl.github.io/assets/137b/review/review%20session%20problems%202.pdf)
* [Final](https://jacoberl.github.io/assets/137b/review/final%20review%20session%20problems.pdf)

Solutions available upon request.
