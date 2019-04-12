![Holm School](https://github.com/HolmSchool/HolmSchool/blob/master/images/small_banner.png)

<h2 align="center">Keep Free Computer Science Education Weird</h2>

#### So you're thinking about holmschooling

Holmshoolers are computer scientists that are home schooled, or even better, _unschooled_. Holmschoolers put their faith in open source and know that the open source community has developed free and copyleft educational resources for learning computer science (as well as other disciplines) to the point that paying for anything other than community or local public college is a tremendous risk of one's money. Because open source has been around for so long, there is enough of an archive of cultural works that a computer scientist could receive their training completely using free and open educational resources (OER) on the internet. This doesn't even factor in the utility of the public library in your town -- your public library has many programming books as well as free video tutorial sites like Lynda.com, which hosts many programming lessons in almost every programming language. They also have computers and laptops if you don't have one. Unschooling is learning college-level material on your own for as low of cost as possible, either by necessity or by choice.

Topic | Book
------------ | -------------
Unschooling | [Grace Llewellyn - The Teenage Liberation Handbook - How to quit school and get a real life and education](https://homominimus.files.wordpress.com/2013/11/the-teenage-liberation-handbook-how-to-quit-school-and-get-a-real-life-and-education.pdf)

#### First Books to Read

Did you know that if, instead of spending $60,000 on a bachelor's degree, you invested that money in by maxing out your 401k (in a S&P500 index fund) and IRA (in a total stock market index fund) over the course of three years instead (there is a $19,000 a year limit on a 401k and a $6000 a year limit on an IRA), you would earn (from age 20 to 60) roughly $1,303,471.29 dollars ($60,000 at 8% interest over 40 years). That's the opportunity cost of college! Colleges would rather charge __YOU__ $60,000 @ 5% or so interest from ages 20-60, then they would be the ones earning compound interest over 40 years! How much better it would be to teach yourself computer science using open source OER and put the money earned from your first programming job into a maxed-out 401k and IRA? If you maxed out your 401k and IRA every year you worked from age 22-32 ($19,000 each year in a 401k invested in a S&P500 index fund, and $6000 each year in a Vanguard IRA account invested in VTSAX), you'd have $250,000 in your retirement account at the age of 32, which would compound over the next 28 years (assuming 8% interest) to $2,156,776.60 at age 60. If you were to keep living frugally while earning a salary as a programmer from age 22+, just like you lived frugally while unschooling computer science from age 18-22 and avoided private university, then you could even retire early, as [Mr. Money Mustache](https://mrmoneymustache.com) did with his programming job by saving 50%-80% of your take-home salary each year. Holmschoolers are well-versed in personal finance and extend their frugal computer science education skills to frugal living as well, once employed as a programmer. That means that they are able to save so much money that they become financially independent (when your earnings from your index fund investments exceeds your yearly cost of living) at a young age. Holmschoolers study personal finance, index funds, financial independence, and early retirement (FIRE) just as eagerly as they study computer science, which means they know that fancy cars and houses aren't as important as being financially independent. Holmschoolers know that living frugally doesn't mean deprivation, and just like not having a college degree doesn’t doom you to failure, having a savings rate above 50% doesn’t mean you suffer either. 

Topic | Book
------------ | -------------
Financial Independence | [Mr. Money Mustache](http://www.mrmoneymustache.com/all-the-posts-since-the-beginning-of-time/)
Financial Independence | [J.L. Collins - The Simple Path to Wealth](https://jlcollinsnh.com/stock-series/)
Personal Finance | [Holm School - Tips for Personal Finance](https://holm.school/tips-for-personal-finance/)

#### Next Set of Books to Read

Computer science isn't a topic that requires a university education. Classroom discussions rarely happen, and whereas a professor could answer your questions, stack overflow seems to do the same. Simply put, all you need in modern times is a laptop (even a $50 raspberry pi will suffice) and an internet connection. If you don't have that, you can always go to the public library and use their computers on a cloud IDE. If you are impoverished, computer science is perhaps the most fruitful path for self-study towards a career because of the low cost of educational resources (OER is free) and the sheer ubiquity of inexpensive technology. Knowing how to program is a great way to escape poverty as well. More and more business need programmers outside of the expensive hubs of LA, SF, and NY, including the midwest or even rural locations. Many people have cell phones which could serve as an internet connection or PDF reader to fuel computer science self-study. Installing debian on a ten year old, $100 laptop usually is a good-enough environment for learning how to program. The Holm School curriculum isn't completely free. It requires you to purchase a raspberry pi if you don't have a linux desktop or install debian on an old laptop if you want. You can wave past this requirement if you do all of your work at the public library using their equipment. It also requires frequent trips to the public library to use their study space/internet, check out their programming books from the CS stack (Dewey Decimal 0-100!), as well as to fuel any all all off-topic study/entertainment. This at a minimum requires a bicycle or perhaps public transportation. But remember, we're replacing the university with the public library!

The second investment this curriculum requires is a copy of the ninth edition of Daniel Liang's Introduction to Java Programming, Comprehensive Version. This book sells for [$15 used on Amazon](https://www.amazon.com/Introduction-Java-Programming-Comprehensive-Version/dp/0132936526), and well worth the investment. This is the only book I recommend you purchase, because you can teach yourself two semesters worth of programming classes by reading the entirity of this book alone. But, here's the rub, you can't just read the book. You have to program, from scratch, every single challenge question at the end of each chapter. __Every single one, every single chapter, for the entirity of this book__ This is non-negotiable, because this is the only way you'll memorize programming syntax well enough to be able to write programs on your own without reference to any external material. You don't need the latest edition of this book to gain from it -- the $15 edition is enough to learn how to program for a beginner -- instead you just need to read it all and do every single programming challenge at the end of each chapter.

Topic    | Book
---------|----------
CS and poverty | [Holm School - How to Be a Not-Rich Computer Scientist](https://holm.school/about/)
Java | [Daniel Liang - Introduction to Java Programming, Comprehensive Version (9th Edition, $15)](https://www.amazon.com/gp/offer-listing/0132936526/ref=dp_olp_used?ie=UTF8&condition=used)

#### Set Up Your Raspberry Pi

Now let's set your Raspberry Pi up for development. Install Java 8 for Liang, and Visual Studio Code for an IDE. Install chromium for a browser, and python 3 while we're at it.

Topic    | Book
---------|----------
Raspberry Pi/Debian | [Install Java on a Raspberry Pi](https://gist.github.com/ribasco/fff7d30b31807eb02b32bcf35164f11f)
Raspberry Pi/Debian | Install Python: ```sudo apt-get install python3-pip```
Raspberry Pi/Debian | Install Chromium: ```sudo apt-get install chromium```
Raspberry Pi/Debian | Install VS Code: ```sudo apt update``` ```sudo apt-get install snapd``` ```sudo reboot``` (save first) ```sudo snap install code --classic``` 
Raspberry Pi/Debian | [Linux Basics: The Command Line Interface (edX)](https://www.edx.org/course/linux-basics-the-command-line-interface)
Raspberry Pi/Debian | [Introduction to Linux (edX)](https://www.edx.org/course/introduction-to-linux)
Raspberry Pi/Debian | [Introduction to the Command Line](https://launchschool.com/books/command_line)
Raspberry Pi/Debian | [Malcolm Maclean - Just Enough Linux](https://leanpub.com/jelinux/read)
Raspberry Pi/Debian | [Mark Bates - Conquering the Command Line](http://conqueringthecommandline.com/book)
Raspberry Pi/Debian | [Unix and Linux Visual Quickstart Guide - Deborah Ray, Eric Ray (Sample Excerpt)](http://ptgmedia.pearsoncmg.com/images/9780321997548/samplepages/9780321997548.pdf)
Raspberry Pi/Debian (optional) | [William Shotts - The Linux Command Line](http://linuxcommand.org/tlcl.php)

#### Open Educational Resources

Holm School uses OER primarily, because there are many free computer science textbooks thanks to the generosity of many writers the past few decades. Just like I praise the benefits of using a $15 old edition of Liang, there is much to be reaped from even old CS books. OER usually is more in depth than MOOC videos, because videos are usually just the equivalent of Cliffs Notes while books really delve deep into the subject and are much more thorough. Most people know about MOOCs, and there are other compendiums of CS MOOC classes ([ossu](https://github.com/ossu/computer-science)) as well as paid books ([teachyourselfcs.com](https://teachyourselfcs.com/)), but our focus at Holm School is curating the best OER resources for a self-taught college-level equivalent in computer science. I believe that reading CS books is essential training (and an essential habit) for computer scientists. Acquainting yourself with OER ensures that you're able to find new OER resources instead of having to purchase something when the time comes for you to teach yourself something new. Sink the money you save not buying textbooks into VTSAX!

Topic | Book
------|--------
OER | [Holm School - Computer Science OER in 2018](https://holm.school/computer-science-oer-in-2018/)
OER | [Holm School - Important Knowledge is in Books](https://holm.school/important-knowledge-is-in-books/)
OER | [EbookFoundation/free-programming-books](https://github.com/EbookFoundation/free-programming-books/blob/master/free-programming-books.md)
OER | [OpenStax.org](http://openstax.org)
OER (optional) | [Open: The Philosophy and Practices that are Revolutionizing Education and Science](https://www.ubiquitypress.com/site/books/10.5334/bbc/)

#### Java Programming

Have you read all 1344 pages of Liang 9th Edition, and done all the exercise problems for every chapter? If not, get started, it'll certainly take a lot of time! When you're comfortable with Java, let's read a couple more java data structures and algorithms to make sure we're comfortable with beginning computer science and then we can start studying languages other than java!

Topic | Book
------|-------
Java | AP Computer Science A: Java Programming - Purdue (edX) [part 1](https://www.edx.org/course/ap-computer-science-a-java-programming) / [part 2](https://www.edx.org/course/ap-computer-science-java-programming-purduex-cs180-2x-0)  / [part 3](https://www.edx.org/course/ap-computer-science-java-programming-purduex-cs180-3x-0) / [part 4](https://www.edx.org/course/ap-computer-science-java-programming-purduex-cs180-4x-0)
Java Data Structures | [Berkeley website with videos](https://sp18.datastructur.es/) / [archive video](https://archive.org/details/ucberkeley-webcast-PL4BBB74C7D2A1049C?sort=titleSorter)
Java Data Structurees | [Pat Morin - Open Data Structures](http://www.aupress.ca/books/120226/ebook/99Z_Morin_2013-Open_Data_Structures.pdf) | [website](http://opendatastructures.org)
Java Algorithms | [textbook](https://algs4.cs.princeton.edu/home/) /[coursera part 1](https://www.coursera.org/learn/algorithms-part1) | [part 2](https://www.coursera.org/learn/algorithms-part2)

#### CS50 as an introduction to C, Python, and Javascript

Topic | Book
------|--------
Beginning Programming | [cs50](https://www.edx.org/course/cs50s-introduction-to-computer-science)
C | [Mark Burgess and Ron Hale-Evans - The GNU C Programming Tutorial](http://www.crasseux.com/books/ctut.pdf)
C | [Jens Gustedt - Modern C](http://icube-icps.unistra.fr/img_auth.php/d/db/ModernC.pdf)
Python | [How to Think Like a Computer Scientist - Allen B. Downey](http://interactivepython.org/courselib/static/thinkcspy/index.html)
Python | [John DeNero - Composing Programs](http://composingprograms.com/) / [John DeNero - SICP](http://www-inst.eecs.berkeley.edu/~cs61a/sp12/book/)
JavaScript | [Kyle Simpson - You Don't Know JS](https://github.com/getify/You-Dont-Know-JS)
JavaScript | [Marijn Haverbeke - Eloquent JavaScript](http://eloquentjavascript.net/)
JavaScript | [Cody Lindley - JavaScript Enlightenment](http://www.javascriptenlightenment.com/)
JavaScript | [Nicholas C. Zakas - Understanding ECMAScript 6](https://github.com/nzakas/understandinges6)

#### Data Structures in C, Python, and JavaScript
After studying data structures and algorithms in Java, learning them in additional languages should come quickly. We throw in some complexity books (Foundations..., Think...) to further expand our CS horizons:

Topic | Book 
------|--------
C | [Al Aho, Jeff Ullman - Foundations of Computer Science](http://infolab.stanford.edu/~ullman/focs.html)
Python | [Allen B. Downey - Think Complexity](http://greenteapress.com/complexity/)
Python | [Problem Solving with Algorithms and Data Structures using Python](http://interactivepython.org/runestone/static/pythonds/index.html)
JavaScript | [Data Structures in JavaScript](https://pmary.gitbooks.io/data-structure-in-javascript/content/)

#### Discrete Mathematics
