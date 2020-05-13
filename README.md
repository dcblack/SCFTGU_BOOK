# SCFTGU_BOOK

#### Archives of SystemC From The Ground Up Book Exercises

Files in this repository are zip archives that are designed to go
with the book:

- Title **SystemC From Ground Up 2nd Edition**
- Copyright 2010
- Authored by David Black, Jack Donovan, Bill Bunton and Anna Keist
- Published by Springer
- ISBN-13: 978-1489982667
- ISBN-10: 1489982663 

![Book cover](https://images.springer.com/sgw/books/medium/9780387699578.jpg)

#### Use

Please download and use this information only for use with the book.

Do **not** redistribute in any form other than to reference this website.
Respect the copyrights of the authors and publishers.

#### Book Sources

- Springer <https://www.springer.com/us/book/9780387699578>
- Amazon <http://a.co/91QwLwi>

#### Quotes

From the currently broken website <http://www.scftgu.com>:

> This new edition of an industry best seller is updated to reflect the
> standardization of SystemC as IEEE 1666 and other improvements that reflect
> feedback from readers of the first edition. The wide ranging feedback also
> include suggestions from editors of the Japanese and Korean language
> translations, professors and students, and computer engineers from a broad
> industrial and geographical spectrum, all who have successfully used the first
> edition.

> New chapters have been added on the SystemC Verification Library and the
> Transaction Level Modeling, and proposed changes to the current SystemC
> standard.

> David Black and Jack Donovan, well known consultants in the EDA industry, have
> teamed with Bill Bunton and Anna Keist, experienced SystemC modeling
> engineers, to write the second edition of this highly popular classic. As
> a team the authors bring over 100 years of ASIC and system design experience
> together to make a very readable introduction to SystemC. 

#### Notes

- The 2007 version of the file may have issues with current C++ and/or SystemC versions;
however, we assume the reader can word this out for themselves.

- The authors were working on a revised version of this material compliant with the latest
versions of C++ and SystemC in the sense of updating the coding style; however, given their
other obligations, we can make no promises and you should not plan on waiting for this.
Writing to the authors about this will only slow down progress unless you yourself wish to
do some of the work (see note). Please understand, we do not profit from this effort and we
have families to support.

- These exercises will also work for the first edition of the book if you happen to have
that version.

- In any case, anybody with a good grasp of C++ should be able to get through the book with
no particular difficulties.

#### Updating goals

Note: If you wish to help with the update (and we will acknowledge your help), you should
probably already be familiar with SystemC. More importantly, you need to be proficient with
the C++11 and C++14 versions of the standard. Much existing SystemC was written with to
match C++03.

Here is a subset of things we wish to improve with modern C++. None of this changes the
underlying principles of SystemC itself nor the lessons existing exercises have.

- Use uniform initialization to simply constructors

- Use user-defined literals to make time represenations more readable

- Automatic variable type inference to simplify typing

- Range based for-loops where appropriate

- Possibly add a few more examples.

#### The end
