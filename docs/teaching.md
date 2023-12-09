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

## Review Sessions
[Midterm Review](https://jacoberl.github.io/assets/110a/review-problems-1.pdf)

[Midterm Review Solutions](https://jacoberl.github.io/assets/110a/review-problems-1-solutions.pdf)

[Final Review](https://jacoberl.github.io/assets/110a/review-problems-2.pdf)

[Final Review Solutions](https://jacoberl.github.io/assets/110a/review-problems-2-solutions.pdf)

**Update:** I woke up today with a solution to the removed Exercise 2. Since the radius of the metal ball is much less than the thickness of the plates, we can use the second term of Equation 3.76 to calculate E, and then calculate the energy stored in the fields by integrating over a ball centered at the center of the metal ball, where we take r from the radius of the ball "a" to half the plate thickness, say "d/2". Since a<<d/2, we can ignore any changes to the energy of the capacitor outside this ball. This is the "extra" energy which the ball imparts to the capacitor, so that mv^2/2 must be equal to this.



## Solutions
* [Week 2](https://jacoberl.github.io/assets/110a/week-2-worksheet-solutions.pdf)
* [Week 4](https://jacoberl.github.io/assets/110a/week-4-worksheet-solutions.pdf)
* [Week 5](https://jacoberl.github.io/assets/110a/week-5-worksheet-solutions.pdf)
* [Week 6](https://jacoberl.github.io/assets/110a/week-6-worksheet-solutions.pdf)
* [Week 8](https://jacoberl.github.io/assets/110a/week-8-worksheet-solutions.pdf)
* [Week 9](https://jacoberl.github.io/assets/110a/week-9-worksheet-solutions.pdf)
* [Week 10](https://jacoberl.github.io/assets/110a/week-10-worksheet-solutions.pdf)
* [Week 11](https://jacoberl.github.io/assets/110a/week-11-worksheet-solutions.pdf)
* [Week 12](https://jacoberl.github.io/assets/110a/week-12-worksheet-solutions.pdf)
* [Week 13](https://jacoberl.github.io/assets/110a/week-13-worksheet-solutions.pdf)
* [Week 15](https://jacoberl.github.io/assets/110a/week-15-worksheet-solutions.pdf)



## Resources
* Week 2: A couple of students asked for recommendations for books on the mathematical background for E&M. I don't have any explicitly on div, grad, and curl; however, I can recommend <em>Calculus on Manifolds</em> by Michael Spivak. This book is accessible with just a knowledge of mutlivariable calculus, it's short (only ~50 pages), and it will take you (rigorously) through the material necessary to understand the general Stokes' theorem in any dimension. This material won't be <em>explicitly</em> helpful for the course, but it will definitely help you fill in some gaps afterwards. For example, it will teach you about differential forms, and these can be used to very succinctly express Maxwell's equations, as well as generalize them to arbtirary relativistic gauge theories.

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
