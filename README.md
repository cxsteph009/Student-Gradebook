# Student-Gradebook

One of the most common uses of Excel in the field of academia is keeping track of students' grades. This spreadsheet averages out the scores of a 
fictional class's students, then determines whether each student has passed or failed the course.

## Process

* Created a formula that calculates the final grade for a student based upon their previous exams and papers.

* When making this calculation:

  * Every paper and exam was considered equal in weight.

  * Each one comprised one-fourth of a student's overall grade.

  * The result was rounded to the nearest integer.

* Using conditionals, created a formula that returns `PASS` if a student's final grade is greater than or equal to 60. If the student's final grade is below 60, the formula  returns `FAIL`.

## Bonus

* Created a nested `IF()` formula which returns a letter grade based on a student's final grade.

  * Greater than or equal to 90 = `A`
  * Greater than or equal to 80 and less than 90 = `B`
  * Greater than or equal to 70 and less than 80 = `C`
  * Greater than or equal to 60 and less than 70 = `D`
  * Anything less than 60 = `F`

## Hints

* In case you need some help with nested `IF()` statements in Excel, [Nest Formulas](https://support.office.com/en-us/article/IF-function-%E2%80%93-nested-formulas-and-avoiding-pitfalls-0b22ff44-f149-44ba-aeb5-4ef99da241c8) is a support article that goes over how to do so.
