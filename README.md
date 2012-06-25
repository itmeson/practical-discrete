practical-discrete
==================

An introduction to discrete mathematics using an interactive
programming environment and workbook model.


Science and mathematics textbooks are generally used for two purposes:
as a reference and as a learning guide.  But traditional textbooks do
a poor job guiding early learners, as they rely too heavily on
numerous practice problems and a didactic mode of exposition that does
not respect how learners actually learn, nor does it promote the kind
of exploration that is supposed to be the hallmark of mathematical and
scientific thought.  They do serve as excellent references, however,
to the intermediate or advanced student seeking to improve their
facility and efficiency through practice.

A number of recent books have sought to correct this by offering a
"workbook" model, in which students are guided through a process of
inquiry that is carefully tailored to find and correct common
misconceptions, and to allow students to construct knowledge and
skills that are more in keeping with a scientific mindset than is the
old standard "drill-and-practice".  These workbook approaches have
been quite successful in a number of studies showing increased student
learning over other approaches. (See, for example, the [Tutorials in
Introductory Physics][tutorials] books produced by the University of
Washington Physics Education research group)

The difficulty with these workbooks is that they fail to provide a
reference that is useful to the student attempting to add onto the
deep conceptual understanding gained from the workbook the facility
and efficiency that is a further hallmark of mastery.  Nor do they
provide the kind of reference a student can use after a course is
completed to "guide" their memory, unless the student is willing to
repeat the inquiry exercises that they have already completed.  Such
references exists, of course, in the form of traditional textbooks
(which are expensive) or sites like Wikipedia -- but these are both
written in a completely different style than the workbooks, and are
difficult for a student trained in inquiry to use.


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


How to Make This Book 
==================== 

Major questions remain to be answered about how to create this book.
Writing the narrative is "easy" in the sense that the technical
questions are simple, while the workbook prompts themselves are
moderate in that authoring is easy, but hitting the right notes on
every topic is hard, but there are a number of options for creating
the remixable, executable text.  These options include:

 1.  Sage.  This is the currently implemented option.  To build the book,
 fork the repo, cd into the practical_discrete directory, then type "make".
 Assumes you have htlatex, tex2sws in your home directory, and a working
 sage installation with the executable in your PATH.  Then upload the
 .sws file into Sage.

 Sage is -- a notebook-style interface to Python and a number of
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


How to Help
===========
Assuming someone is so inclined, I could use help in:

  1. Making the build process in Sage simpler.  
  2. Making the book prettier (LaTeX customization)
  3. Writing demonstrations and problems, with explanatory
  text and executable code in Sage
  4. Making the Sage portions of the book separable, so sections written in
  other languages can be spliced in place.



[tutorials]: http://www.phys.washington.edu/groups/peg/tut.html