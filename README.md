practical-discrete
==================

An introduction to discrete mathematics using an interactive
programming environment and workbook model.


The genesis of this project was a realization that most educators rely
heavily on the textbook to provide a reference and a learning guide
through worked examples and a large supply of practice problems.
Unfortunately, while most textbooks do a fine job of supplying
reference material and a copious supply of practice problems, they
often do a poor job of guiding the learner to true understanding and
mastery.  This happens because the types of problems we ask students
to do for practice lend themselves too easily to parroting procedures
observed in class or in the worked examples.  For the best students,
this leads to high grades but often poor understanding, and for
struggling students, it leads to a desperate attempt to memorize
procedures without the context to understand when those procedures are
relevant, leading inevitably to faulty recall and wildly variable
performance on summative assessments.


This book aims to improve this situation in the specific domain of
discrete mathematics, a course which, in many colleges, serves as an
introduction to the kind of thinking "real" mathematicians do, begins
the process of learning to read and write rigorous proofs, and offers
many interesting applications with relevance to operations research,
probability and statistics, and computer science, among others.  At my
institution, the course is primarily taken by sophomore and junior
level computer security and graphic design majors, which opens an
interesting variety of potential applications and intersections
between practical and artistic modes of thought.


The design principle of this book is to offer to students two
high-quality, parallel tools: a reference text of concepts and
applications of discrete mathematics, implemented in a re-mixable,
open format in which all examples are displayed as executable source
code that can be run and altered in an experimental fashion; and a
learning guide/tutorial/workbook that guides students through
exercises, also implemented as executable code, of types that offer
the entire hierarchy of concept exploration and introduction, guided
demolition of misconceptions, application, refinement, and extension.


While there are no perfect analogues of this project, a number of
resources offer inspiration for portions of the book.  For the
parallel reference and learning portions of the book, offering only as
much reference as is needed by the learner at any time, the paired
tutorial and reference manual of Python (python.org) and other
programming languages.  The Tutorials in Physics series produced by
the Physics Education Research group at the University of Washington
is one example of a similar approach to the workbook portion of the
text, as are the Process Oriented Guided Inquiry Lessons (POGIL) being
developed for chemistry education.  


And for the narrative that ties the whole together, I take inspiration
from books like "Div, Grad, Curl and All That: An Informal Text on
Vector Calculus" by H.M. Schey.

How to Make This Book 
==================== 

Major questions remain to be answered about how to create this book.
Writing the narrative is "easy" in the sense that the technical
questions are simple, while the workbook prompts themselves are
moderate in that authoring is easy, but hitting the right notes on
every topic is hard, but there are a number of options for creating
the remixable, executable text.  These options include:

 1.  Sage -- a notebook-style interface to Python and a number of
 excellent mathamatical libraries is the most obvious choice.
 However, deploying the book would require managing a server, or
 requiring all Windows users to install a virtual machine and Sage
 itself.  Submission of student work in a course would also require
 some further development.

 2. iPython -- a notebook-style interface to Python without the
 built-in mathematical libraries.  Installation or deployment seems to
 be easier than with Sage, and there are other examples of textbooks
 using this system, with some extra development work thrown in to
 handle the workflow of student access and submission.

 3. MakingMath -- a learning management system built on Mathematica
 that handles already all the details of managing a course, at the
 cost of requiring a $99 per student investment, and only 6 months of
 guaranteed access to the materials (which is comparable to that
 offered by major publishers of online textbooks).  If I develop using
 this system, "all" that would need to be done is to write the
 materials without needing to deal with other software issues.  I
 expect that if I do this, I will develop in parallel in Sage or
 iPython, so that students can be offered free access to a permanently
 accessible version of the book upon completion of the course.

 4.  ?




