# Contents

- [Introductory remarks](#introduction)
	- [What is this?](#what-is-this)
	- [What is required to do this?](#what-is-required-to-do-this)
	- [Who is this for?](#who-is-this-for)
	- [How should I study mathematics?](#how-to-study-mathematics)
   	- [My favorite textbook isn't on there!](#my-favorite-textbook-isnt-on-there)
- [Part I: Core Subjects](#part-i-core-subjects)
	- [Discovering the basics](#discovering-the-basics)
		- [Learning and metacognition](#learning-and-metacognition)
		- [Precalculus](#precalculus)
		- [Calculus](#calculus)
		- [Proof Techniques](#proof-techniques)
	- [Building Foundations](#building-foundations)
		- [Linear Algebra](#linear-algebra)
		- [Real Analysis](#real-analysis)
		- [Discrete Mathematics](#discrete-mathematics)
		- [Basic Number Theory](#basic-number-theory)
	- [Mastering the fundamentals](#mastering-the-fundamentals)
		- [Abstract Algebra](#abstract-algebra)
		- [General Topology](#general-topology)
		- [Ordinary Differential Equations](#ordinary-differential-equations)
		- [Classical Differential Geometry](#classical-differential-geometry)
- [Part II: Electives](#part-ii-electives)
	- [Analysis](#analysis)
	- [Algebra](#algebra)
	- [Topology](#topology)
	- [Differential Geometry](#differential-geometry)
	- [Algebraic Geometry](#algebraic-geometry)
	- [Number Theory](#number-theory)
	- [Miscellaneous](#miscellaneous)
	- [Applications](#applications)
		- [Physics](#physics)
		- [Computer Science](#computer-science)
		- [Finance](#finance)
		- [Biology](#biology)
		- [Chemistry](#chemistry)
- [Part III: Possible Tracks](#part-iii-possible-tracks)
	- [Generalist track](#generalist-track)
	- [Analyst track](#analyst-track)
	- [Algebraist track](#algebraist-track)
	- [Geometer track](#geometer-track)
	- [Algebraic Geometer track](#algebraic-geometer-track)
	- [Number Theorist track](#number-theorist-track)
	- [Physicist track](#physicist-track)
	- [Computer Scientist track](#computer-scientist-track)
	- [Finance track](#finance-track)

# Introductory remarks

## What is this?

This website is a three-parts curriculum aimed to help beginners self-study mathematics. The first part discusses core mathematical subjects that most undergraduate mathematics student will see in some way or another. The second part is a series of electives that can be studied more independently, concluding with a few applications to different fields outside of mathematics. The third part discusses possible tracks one might follow for electives.

## What is required to do this?

 I assume a modest mathematical background, mostly high school mathematics. The most important thing to have is patience. Learning mathematics takes a very long time, and you will get stuck over and over and over and over again.

## Who is this for?

Anyone with an interest in mathematics, provided they fit the requirements above.

## How should I study mathematics?

Do as many exercises and problems as you can. Mathematics is mostly an exercise-based game. Most of your time should be spent solving stuff. If you don't like problem-solving, you probably won't like mathematics very much.

Practically speaking, I suggest reading through the section you are working on quickly, and then trying your hand at the first few exercises. If you get immediately stuck, re-read the theory and the proofs in it. What techniques are being used? How are these techniques applied to the problem? Can I use that same technique to solve my exercise? If not, could I modify it to suit the task at hand?

Do not be too quick to look up the solution to the exercise. You learn most when you are stuck for a certain amount of time trying to figure out all possible paths to the solution. At most, ask for a hint. Take your time. It's a marathon, play the long game.

## My favorite textbook isn't on there!

I'm sorry. Either I read it and didn't particularly enjoy or care for it, or I don't know about it. Some popular book series will not come up on this list, since it's my list and it's based on what I know and like. If you make your own list, feel free to [contact me on GitHub about it](https://github.com/donkuri), I would love to see it!

# Part I: Core Subjects

This part deals with common subjects found in most undergraduate mathematics degree. There isn't really any subject here I would skip, all of them are important in helping you acquire mathematical maturity, as well as a general understanding of the various basic structures in mathematics.

## Discovering the basics

This section is mostly concerned with revisiting things you should have seen in high school, as well as strengthening your mathematical dexterity by introducing proofs into the mix. Even at this level, we can find conjectures that [seem hopelessly difficult](https://en.wikipedia.org/wiki/Collatz_conjecture) or that have [evaded mathematicians for decades](https://en.wikipedia.org/wiki/Jacobian_conjecture). Mathematics is by nature a pyramide of knowledge, everything builds from the basics, so spend adequate time to study them properly.

### Learning and metacognition

Learning how to learn is very important and something that is rarely discussed outright. I suggest following [this course](https://www.coursera.org/learn/learning-how-to-learn?). Alternatively, read the book:

**[A Mind for Numbers](https://www.amazon.com/Mind-Numbers-Science-Flunked-Algebra/dp/039916524X)**, *Barbara Oakley*

<img src="/learn-mathematics/img/oakley.jpg" alt="Oakley" width="200px"/>

The book [Good Habits, Bad Habits](https://www.amazon.com/Good-Habits-Bad-Science-Positive/dp/1250159075) is a great way to learn about creating habits. I suggest you make learning mathematics a part of your daily routine, if you're serious about learning it. Another good idea would be to read this:

**[How to Think Like a Mathematician](https://www.amazon.com/How-Think-Like-Mathematician-Undergraduate/dp/052171978X/)**, *Steve Houston*

<img src="/learn-mathematics/img/houston.jpg" alt="Houston" width="200px"/>

### Precalculus

Precalculus deals with high school subjects before calculus is introduced. This means functions, (in)equations, analytic geometry, trigonometry and sometimes matrices as well as limits. There is a myriad of books you can use for this, and I suggest you find one you like. Here is my favorite:

**[Precalculus Mathematics in a Nutshell](https://www.amazon.com/Precalculus-Mathematics-Nutshell-Geometry-Trigonometry/dp/1592441300/)**, *George F. Simmons*

<img src="/learn-mathematics/img/simmons.jpg" alt="Simmons" width="200px"/>

The book is short, so do everything in there. Another option is to read Lang's precalculus book, although if you do use it, be sure to look for an errata online because I remember it having quite a few mistakes and typos. It's what you might call "old school", from one of the greatest math textbook writer of all time, part of the influential [Bourbaki group](https://en.wikipedia.org/wiki/Nicolas_Bourbaki). You could learn a lot just reading books by Lang, as he wrote quite extensively and we will find him recommended here quite often.

**[Basic Mathematics](https://www.amazon.com/Basic-Mathematics-Serge-Lang/dp/0387967877)**, *Serge Lang*

<img src="/learn-mathematics/img/lang-basic_mathematics.jpg" alt="Basic Mathematics" width="200px"/>

Make sure you are extremely comfortable with algebra and trigonometry before moving on. 

### Calculus

Calculus deals with infinity in a computational manner. You learn to take derivatives and integrals as you try to understand how to relate the infinitesimally small with the infinitely large. We will come back to these questions in a deeper way in the [real analysis section](#real-analysis), but this subsection is concerned more with the application of these tools to solve problems such as optimizing functions and finding volumes of revolution. My favorite book happens to have a "pay what you want" model:

**[APEX Calculus](https://leanpub.com/apexcalculus)**, *Gregory Hartman*

<img src="/learn-mathematics/img/apex.png" alt="APEX" width="400px"/>

I suggest you do every chapter in the book, keeping in mind that this will take you a large amount of times. There are many, many exercises and you probably shouldn't do every single one of them before moving on. When you feel like you've understood the concept well enough, and you've done enough drills then go to the next section. There is another absolutely fantastic book series that I can't help but recommend, although it is pretty old by now, but to me it is still the gold standard for calculus:

**[Differential and Integral Calculus, Vol. 1-2](https://www.amazon.com/Differential-Integral-Calculus-Vol-1-ebook/dp/B08S74TL87/)**, *Nikolai S. Piskunov*

<img src="/learn-mathematics/img/piskunov.jpg" alt="Piskunov" width="200px"/>

This book is written in the Soviet style of mathematics: it is terse, with examples taken largely from physics (especially classical mechanics) and decently hard exercises. If that sounds appealing to you, go with that one. Better yet, use both! Finally, the book I actually used to learn calculus:

**[A First Course in Calculus](https://www.amazon.com/First-Course-Calculus-Undergraduate-Mathematics/dp/0387962018/)**, *Serge Lang*

<img src="/learn-mathematics/img/lang-calculus.jpg" alt="Lang Calculus" width="200px"/>

As usual with Lang, this book is well written and I remember enjoying the integrals section in particular. This has [a follow-up course](https://www.amazon.co.uk/Calculus-Several-Variables-Undergraduate-Mathematics/dp/0387964053/).

### Proof Techniques

In this section, we take some time to learn basic proof patterns and how they are used in mathematics to make sure we are correct in our arguments. Proofs are not the end all be all of mathematics, but rigor is necessary to avoid nonsense, as [19th century mathematics proved time and time again](https://link.springer.com/book/10.1007/978-3-319-23715-2). I like this free book:

**[Book of Proof](https://www.people.vcu.edu/~rhammack/BookOfProof/)**, *Richard Hammack*

<img src="/learn-mathematics/img/hammack.jpg" alt="Hammack" width="200px"/>

You should do everything here. Do notice chapter 13 will be revisited in the real analysis section, but it's not a bad idea to see it here first.

## Building foundations

In this section, we now move on to actual mathematics major classes. If you have done everything in the past section, you are now ready for it. That doesn't mean it will be easy, however. There is a definitely a jump in difficulty here, and it is normal. The good news is that it will probably the hardest jump you'll have to clear.

### Linear Algebra

Linear Algebra is the heart and soul of mathematics. In practically every field, our first instinct is to linearize problems and see if we can retrieve the original solution from it. It is central to everything that will follow and for this reason you need to be extremely proficient with it. Thankfully, the linear algebra textbooks that follow are of very good quality and my top recommendation is entirely free:

**[Linear Algebra Done Wrong](https://www.math.brown.edu/streil/papers/LADW/LADW.html)**, *Sergei Treil*

<img src="/learn-mathematics/img/ladw.png" alt="LADW" width="200px"/>

This book is just great. Don't be fooled by the cheeky name (probably a reference to the next book), this textbook is wonderful, with a great spread of exercises ranging from simple verification to more involved problems. I suggest doing everything in there. Another good text is the following classic:

**[Linear Algebra Done Right](https://www.amazon.com/Linear-Algebra-Right-Undergraduate-Mathematics/dp/3031410254/)**, *Sheldon Axler*

<img src="/learn-mathematics/img/ladr.jpg" alt="LADR" width="200px"/>

The "Done Right" comes from the author's opinion that determinants tend to muddy up understanding of linear algebra among first year students who then go on to learn things the "wrong" way. I am not sure I agree all that much, but at least the textbook is consistent and well-written. I would use this one to supplement Linear Algebra Done Wrong and as a source of more exercises. There is another book I recommend if you have never seen matrices before. This book is much simpler than either of the other two recommended textbooks and I'd get it if you feel like you're completely lost. I have only worked with the 4th and 5th editions, so I would suggest getting these:

**[Linear Algebra and its Applications](https://www.amazon.com/Linear-Algebra-Its-Applications-Global/dp/1292351217/)**, *David C. Lay, et al*

<img src="/learn-mathematics/img/lay.jpg" alt="Lay" width="200px"/>

Alternatively, if you liked Lang before, you might want to read his books on linear algebra, the first one is an introduction, and the second a more advanced treatment. My first exposure to linear algebra was with the introduction. Personally, I'd read one after the other, but I will only show the second one here:

**[Linear Algebra](https://www.amazon.com/Linear-Algebra-Undergraduate-Texts-Mathematics/dp/0387964126/)**, *Serge Lang*

<img src="/learn-mathematics/img/lang-linear.jpg" alt="Lang LA" width="200px"/>

### Real Analysis

And now the subject that strikes fear in many undergraduate students: real analysis. This is the subject where you will truly have to wrestle with the definitions, propositions and proofs. Studying analysis requires a change of mindset and the acquisition of new tools that often confuse the beginning mathematician. For this reason, I offer you four main options as well as a complimentary counterexample book and a sort of study guide. The first book is perhaps my favorite mathematics textbook of all time:

**[Understanding Analysis](https://www.amazon.com/Understanding-Analysis-Undergraduate-Texts-Mathematics-ebook/dp/B00XWDQUH4/)**, *Stephen Abbott*

<img src="/learn-mathematics/img/abbott.jpg" alt="Abbott" width="200px"/>

This is the book that made me fall in love with mathematics. Abbott is a master didactician and his introduction of analysis is thoroughly motivated, his style is clear and precise but is surprisingly gentle. I actually suggest you look at both the first and the second edition if you can, because they have different discussions to introduce the chapters. Perhaps the only issue with the text is I wish it'd have more really hard exercises to grind your teeth against. For this, I recommend the following book, which is another favorite of mine:

**[Mathematical Analysis I-II](https://www.amazon.com/Mathematical-Analysis-Universitext-V-Zorich/dp/366248790X/)**, *Vladimir A. Zorich*

<img src="/learn-mathematics/img/zorich.jpg" alt="Tao" width="200px"/>

These two books taken together provide a very thorough introduction to analysis in general, and I very heavily recommend it. The next book fills a particular niche by having you construct most of the theory yourself:

**[Analysis I-II](https://www.amazon.com/Analysis-Third-Texts-Readings-Mathematics-ebook/dp/B01LFAANIW/)**, *Terence Tao*

<img src="/learn-mathematics/img/tao.webp" alt="Tao" width="200px"/>

What to say about Terence Tao that hasn't already been said. Everyone always mentions [his famous blog](https://terrytao.wordpress.com/) and of course his many mathematical contributions. A Fields medalist, not only is he a master at mathematics, he's a master at mathematics writing and this text is a perfect example. It is definitely not easy as you are required to do a lot of the thinking behind the theory itself, but it is worth doing for precisely that reason. The power you get from constructing the course yourself is very exhilarating. With that said, I can't help but recommend one more book by Lang, this one slightly lesser known but still very good (I especially liked the discussion on potentials):

**[Undergraduate Analysis](https://www.amazon.com/Undergraduate-Analysis-Texts-Mathematics/dp/0387948414)**, *Serge Lang*

<img src="/learn-mathematics/img/lang-undergrad_analysis.jpg" alt="Undergraduate Analysis" width="200px"/>

For this one, I suggest you do the main sequence Lang proposes and then pick two-three special topics that interest you and study those. All four of these books focus on building examples to help you understand the theory, but counterexamples are just as important, even more so in analysis. This is where the following book helps:

**[Counterexamples in Analysis](https://www.amazon.com/Counterexamples-Analysis-Dover-Books-Mathematics/dp/0486428753/)**, *Bernard R. Gelbaum, John M.H. Olmsted*

<img src="/learn-mathematics/img/counterexamples_analysis.jpg" alt="Counterexamples Analysis" width="200px"/>

I suggest you look at the counterexamples that interest you personally, instead of just reading through the book linearly. The next book aims to prepare and help you work through analysis:

**[How to Think about Analysis](https://www.amazon.com/Think-About-Analysis-Lara-Alcock-ebook/dp/B00O94K6NO/)**, *Lara Alcock*

<img src="/learn-mathematics/img/alcock.jpg" alt="Alcock" width="200px"/>

### Discrete Mathematics

This section is concerned with so-called "discrete mathematics", which here would be basic combinatorics (including induction) and mostly graph theory. This kind of mathematics is especially useful for computer science, and one of my favorite textbook on the subject is written by Donald Knuth, one of the greatest programmer of all times.
If you are especially interested in computer science or programming, then it's hard to beat it:

**[Concrete Mathematics](https://www.amazon.com/Concrete-Mathematics-Foundation-Computer-Science-ebook/dp/B08F5H9DYM/)**, *Ronald Graham, et al*

<img src="/learn-mathematics/img/concrete.jpg" alt="Cocnrete" width="200px"/>

Another very good introduction to the subject is this book:

**[Discrete Mathematics and Its Applications](https://www.amazon.com/Discrete-Mathematics-Applications-Kenneth-Rosen-ebook/dp/B07FF9DY66/)**, *Kenneth H. Rosen*

<img src="/learn-mathematics/img/rosen-dm.jpg" alt="Rosen DM" width="200px"/>

Finally, here's a funny book that uses ducks to introduce discrete mathematics, because why not:

**[Discrete Mathematics with Ducks](https://www.amazon.com/Discrete-Mathematics-Ducks-Textbooks-dp-1138052590/dp/1138052590/)**, *sarah-marie belcastro*

<img src="/learn-mathematics/img/duck.jpg" alt="Ducks" width="200px"/>

It is a bit easier than the others but the instruction quality is very good nonetheless.

### Basic Number Theory

We now move to the *Queen of Mathematics*, as Gauss used to say. Basic number theory is a subject that tends to be dismantled and studied in different parts of mathematics. But number theory is too beautiful to be dismembered so, and I think it is crucial to study it to better understand further examples in higher mathematics, notably in abstract algebra. The following book is well suited to introducing the elementary parts of the theory, those parts of the subject that do not use analysis or abstract algebra:

**[Elementary Number Theory](https://www.amazon.com/Elementary-Number-Theory-Its-Application/dp/0321500318/)**, *Kenneth H. Rosen*

<img src="/learn-mathematics/img/rosen-nt.jpg" alt="Rosen NT" width="200px"/>

Another classic, albeit slightly dated, is this wonderful book:

**[An Introduction to Theory of Numbers](https://www.amazon.com/Introduction-Theory-Numbers-G-Hardy/dp/0199219869/)**, *G. H. Hardy, E. M. Wright*


<img src="/learn-mathematics/img/hardy.jpg" alt="Hardy" width="200px"/>

I would suggest exploring the book, rather than outright studying it. Walk through the various chapters lightly, stopping where your interest takes you, and study that part of the book.

## Mastering the fundamentals

We now move to the core of a mathematics undergraduate degree. This is where abstraction and generalization is taken to another level. These courses are absolutely crucial to understanding modern mathematics, and all of these theories were developped to help mathematicians solve important problems. For instance, much of modern algebra was developped to solve [Fermat's Last Theorem](https://en.wikipedia.org/wiki/Fermat%27s_Last_Theorem). Differential equations and differential geometry grew, in part, out of physics. Topology is a natural extension of real analysis and helps transfer its tools to other fields.

The selection of the following four topics is somewhat arbitrary. For instance, Fourier analysis has a central place in modern analysis and could have been here. Similarly, Galois theory is central to abstract algebra, although it is rarely covered early on in mathematics textbooks. The interested student is encouraged to study both of these early on, but they will instead be listed in [Analysis](#analysis) and [Algebra](#algebra) respectively.

### Ordinary Differential Equations

Most of physics is described by differential equations, and it is a very mature and rich theory. Yet unlike some of the more abstract subjects, differential equations has a practical nature, and many differential equations are not solved exactly but through numerical methods. This makes for an interesting topic, that can be approached from multiple angles. Personally, my favorite way to introduce differential equations is the way this book presents it:

**[Differential Equations with Applications and Historical Notes](https://www.amazon.com/Differential-Equations-Applications-Historical-Mathematics/dp/1032477148/)**, *George F. Simmons*

<img src="/learn-mathematics/img/simmons-ode.jpg" alt="Simmons ODE" width="200px"/>

If you would like a presentation style closer to Russian-style books, with a focus on rigor and structure, then the following textbook might interest you:

**[Differential Equations](https://www.amazon.com/Differential-Equations-Springer-Undergraduate-Mathematics/dp/3319452606/)**, *Viorel Barbu*

<img src="/learn-mathematics/img/barbu.jpg" alt="Barbu" width="200px"/>

### Classical Differential Geometry

Classical Differential Geometry takes the tools of calculus and uses them to go further than analytic geometry, and introduce notions of speed, acceleration and curvature in geometry. This is interesting in many ways. For one, you actually use the tools you constructed in your previous analysis classes to do something with them, and this is where you first see the full power of calculus and why it was revolutionary. I studied the subject using the following book:

**[Differential Geometry of Curves and Surfaces](https://www.amazon.com/Differential-Geometry-Surfaces-Undergraduate-Mathematics/dp/3319397982/)**, *Kristopher Tapp*

<img src="/learn-mathematics/img/tapp.jpg" alt="Tapp" width="200px"/>

Another interesting book that recently got reprinted is the classic by Kobayashi:

**[Differential Geometry of Curves and Surfaces](https://www.amazon.com/Differential-Geometry-Surfaces-Undergraduate-Mathematics/dp/981151738X/)**, *Shoshichi Kobayashi*

<img src="/learn-mathematics/img/kobayashi.jpg" alt="Kobayashi" width="200px"/>

In the same vein, the gold standard for classical differential geometry is the book by Do Carmo:

**[Differential Geometry of Curves and Surfaces](https://www.amazon.com/Differential-Geometry-Curves-Surfaces-Mathematics/dp/0486806995/)**, *Manfredo P. Do Carmo*

<img src="/learn-mathematics/img/docarmo.jpg" alt="Do Carmo" width="200px"/>

This is probably the book that is used most for a single-semester undergraduate differential geometry class. I like it, it's great.

### Abstract Algebra

Abstract algebra (often called algebra more simply) is a language used to describe the concept of equality, and all possible generalizations of it, such as equivalence relationships and the like. Many parts of mathematics have an algebraic counterpart: algebraic topology, algebraic geometry, even algebraic analysis. As such, it is paramount that you get familiar with it. My favorite textbook on the subject is free:

**[Abstract Algebra: Theory and Applications](http://abstract.ups.edu/aata/aata.html)**, *Thomas W. Judson*

<img src="/learn-mathematics/img/aata.png" alt="AATA" width="200px"/>

The book is great and is available in French and Spanish. My only issue with the book is that the exercises are often too simple, and I suggest finding other exercises elsewhere. One possible book for this is the following books:

**[Algebra I-II, Gorodentsev](https://www.amazon.com/Algebra-I-Textbook-Students-Mathematics-ebook/dp/B01NACZUA4/)**, *Alexey L. Gorodentsev*

<img src="/learn-mathematics/img/gorodentsev.jpg" alt="Gorodentsev I" width="200px"/>

This is the first out of two textbooks (written in the Russian style) that form one gigantic course in algebra, covering way more than a generic abstract algebra undergraduate course. I would suggest starting with the first book, and if you like its style and presentation, consider doing the second one. Personally, it has some of my favorite exposition but it is not as gentle as Judson, and the ordering of the topics is quite different from most other such books. This will either feel fantastic or horrendous, so try it out and see. One highlight is covering quaternions and spinors, which I barely ever see in undergraduate mathematics textbook. Another textbook that discusses interesting topics that are not always given enough time at the undergraduate level is this masterpiece:

**[Algebra](https://www.amazon.com/Algebra-2nd-Michael-Artin/dp/0132413779/)**, *Michael Artin*

<img src="/learn-mathematics/img/artin.jpg" alt="Artin" width="200px"/>

This is the book I used along with Judson to learn algebra. One interesting point is that Artin makes heavy use of linear algebraic notions and examples to explore abstract algebra, a wise choice in my opinion. Finally, here is the obligatory Lang reference:

**[Undergraduate Algebra](https://www.amazon.com/Undergraduate-Algebra-Texts-Mathematics/dp/0387220259/)**, *Serge Lang*

<img src="/learn-mathematics/img/lang-undergrad_algebra.jpg" alt="Undergraduate Algebra" width="200px"/>

I particularly liked the chapter on rings.

### General Topology

General Topology (sometimes called Point-Set Topology) is a generalization of the concepts of analysis (convergence, compactness and the likes) that can be applied in many different fields, usually yielding a rich theory. What happens when the space we are working with is so weird that it is hard to even define a distance on it? Can we deform space? In what way? This is the essence of topology. My favorite textbook is the following:

**[Topology](https://www.amazon.com/Topology-Undergraduate-Texts-Mathematics-J%C3%A4nich/dp/0387908927/)**, *Klaus Jänich*

<img src="/learn-mathematics/img/janich.jpg" alt="Jänich" width="200px"/>

I have yet to see a better exposition of topology. Unfortunately, it has no exercises, so I'd suggest pairing it with another one. This one is cheap and clear, especially the chapter on metric spaces:

**[Introduction to Topology](https://www.amazon.com/Introduction-Topology-Second-Dover-Mathematics/dp/0486406806/)**, *Theodore W. Gamelin, Robert Everist Greene*

<img src="/learn-mathematics/img/greene.jpg" alt="Greene" width="200px"/>

I would recommend doing the entire chapter on metric spaces, with all the exercises. Metric spaces are the central examples in basic topology, and a large portion of the theory is dedicated to knowing when a metric can be put on a space or not. After this, I would work through the following book:

**[Topology](https://www.amazon.com/Topology-Classic-Classics-Advanced-Mathematics/dp/0134689518/)**, *James R. Munkres*

<img src="/learn-mathematics/img/munkres.jpg" alt="Munkres" width="200px"/>

This book is the classic undergraduate textbook on topology. It is a bit rough, but it has good explanations. If you liked classical differential geometry and you already know you want to know more about it, I would skip Munkres and I would do this instead:

**[Introduction to Topological Manifolds](https://www.amazon.com/Introduction-Topological-Manifolds-Graduate-Mathematics/dp/1441979395/)**, *John M. Lee*

<img src="/learn-mathematics/img/lee-top.jpg" alt="Top Mfds" width="200px"/>

This is the book I used to learn topology. Do not be scared by the fact it is supposed to be a graduate-level textbook, it is very approachable. Instead of discussing topology in full, absolute generality, the author (my favorite math author might I add) focuses on manifolds, the basic geometric object of interest. 

# Part II: Electives

In this part, we give a few potential electives an undergraduate mathematics student might take. Most of these are graduate-level, but if you have worked through the previous part, you are more than prepared for graduate-level classes. Some classes are more advanced than others, and you can follow tracks found in part III if you'd rather not choose. Sadly, this is also where my biases will start to show. In some cases, I will mention books I have only looked at rapidly. There are many, many topics I do not know about or have never studied (especially at the graduate-level). This means that some recommendations are there in part due to community support and/or through someone who recommended it to me. I believe it is better to have them up rather than nothing, because it's at least a place to start. Nonetheless, I have at least looked at all of these before, there is no book placed here only on hearsay.

In turn, some topics I have studied deeper (like geometry, analysis and especially algebra) will have more references and more topics will be discussed. If you are interested in subjects not covered here, it doesn't mean I don't like them or I do not consider them important, it is simply that I have not seen anything about them yet.

## Analysis

If you have liked undergraduate analysis topics such as calculus, real analysis and differential equations, this is for you. At the very least, I would expect most undergraduate students to take Fourier, complex and functional analysis, even if you don't plan on becoming an analyst. Fourier analysis is the heart of analysis. Complex analysis is the perfect example of beauty in mathematics. Functional analysis bridges the gap between analysis and algebra. Measure theory and probability rounds up what I would call the "core analysis graduate" sequence, and yes I consider probability to be a part of analysis, at least at the early graduate level. Other interesting subjects include dynamical systems (what I'd call the geometry of differential equations), harmonic analysis (Fourier on steroids), partial differential equations (the backbone of physics) and stochastic processes (a rich theory with many applications).
Ok, let's get into it.

### Fourier Analysis

Fourier analysis is the genesis of much of what you have studied in real analysis. The convergence of Fourier series motivated both real analysis and measure theory. I believe every undergraduate student in mathematics, physics and engineering should have a class on Fourier series. For this, my favorite book is the first part of the four-part analysis series by Stein and Shakarchi:

**[Fourier Analysis](https://www.amazon.com/Fourier-Analysis-Introduction-Princeton-Lectures/dp/069111384X/)**, *Elias M. Stein, Rami Shakarchi*

<img src="/learn-mathematics/img/stein-fourier.jpg" alt="Stein & Shakarchi, Vol.1" width="200px"/>

This book is absolutely stunning (as are all the books in the series, and I suggest using them to study graduate analysis). The examples are motivated well and the exercises are just right. There is another book that I have read for a bit, especially for its discussion of wavelets:

**[Introduction to Fourier Analysis and Wavelets](https://www.amazon.com/Introduction-Analysis-Wavelets-Graduate-Mathematics/dp/082184797X/)**, *Mark A. Pinsky*

<img src="/learn-mathematics/img/pinsky.jpg" alt="Pinksy" width="200px"/>

Both books are great, try them out!

### Complex Analysis

Complex analysis is pure beauty. Everything you hated about real analysis seems to magically disappear when we enter the complex realm: Differentiable implies analytic, the zeros of a complex function are defined in a beautiful pattern, etc. This doesn't mean the subject is easy however, as the theory is pretty unique in the way it handles computation, for instance contour integrals. As above, my favorite book on the subject is the second-part of Stein & Shakarchi:

**[Complex Analysis](https://www.amazon.com/Complex-Analysis-Princeton-Lectures-No/dp/0691113858/)**, *Elias M. Stein, Rami Shakarchi*

<img src="/learn-mathematics/img/stein-complex.jpg" alt="Stein & Shakarchi, Vol.2" width="200px"/>

A very lucid introduction to the topic, I like the selection of exercises and the presentation. There are many other good books on the subject. Another one that is more accessible is this one:

**[Complex Analysis](https://www.amazon.com/Complex-Analysis-Undergraduate-Texts-Mathematics/dp/1441972870/)**, *Joseph Bak, Donald J. Newman*

<img src="/learn-mathematics/img/bak.jpg" alt="Bak" width="200px"/>

There is another book that takes an interesting approach to the theory:

**[Visual Complex Analysis](https://www.amazon.com/Visual-Complex-Analysis-25th-Anniversary/dp/0192868926/)**, *Tristan Needham*

<img src="/learn-mathematics/img/needham.jpg" alt="Needham" width="200px"/>

I think all three books are interesting and give different perspectives, so try all three if you can.

### Measure Theory and Integration

We finally come back to real analysis, but this time through a more mature lens. We go back to the notion of integral we developed in calculus and real analysis, and we refine it to make it both more general and more powerful. This is also where we take a look back on probability, and see why it really can be seen as a subfield of analysis. I will give two recommendations that discuss measure theory on its own, and two recommendations that tackle probability as well.

**[Real Analysis](https://www.amazon.com/Real-Analysis-Integration-Princeton-Lectures/dp/0691113866/)**, *Elias M. Stein, Rami Shakarchi*

<img src="/learn-mathematics/img/stein-real.jpg" alt="Stein & Shakarchi Vol.3" width="200px"/>

Yes, yes, what can I say? What a surprise. But once again, this book is gold. There is a reason why all the books in the series form the core of my recommendations for graduate analysis: they're just that good. This book is interesting because while it does focus on measures and integration, it also revisits previous topics from Fourier and complex analysis. It also has an interesting discussion of fractals. The exercises are splendid, with a great range of difficulty. Another great exposition is of course:

**[An Introduction to Measure Theory](https://www.amazon.com/Introduction-Measure-Graduate-Studies-Mathematics/dp/1470466406/)**, *Terence Tao*

<img src="/learn-mathematics/img/tao-graduate.jpg" alt="Tao Graduate" width="200px"/>

As I have said before, Tao is great at writing mathematics and it shows. On top of this, the AMS graduate textbooks just feel comfortable to me in a strange way I can't really describe. Anyway, it's good, try it out. Now on to books that discuss measure theory motivated mostly by probability:

**[Measures, Integrals and Martingales](https://www.amazon.com/Measures-Integrals-Martingales-Ren%C3%A9-Schilling/dp/1316620247/)**, *René L. Schilling*

<img src="/learn-mathematics/img/schilling.jpg" alt="Schilling" width="200px"/>

I really like this book, it's how I personally learnt measure theory. If it is a bit tough, you can try this one out first, which is simpler:

**[Measure, Integral and Probability](https://www.amazon.com/Measure-Integral-Probability-Marek-Capinski/dp/1852337818/)**, *Marek Capiński, Ekkehard Kopp*

<img src="/learn-mathematics/img/mip.jpg" alt="MIP" width="200px"/>

### Functional Analysis

Now onto my favorite part of analysis. Functional analysis takes a closer look at functions, and to be more specific, *functionals*. This is the part of analysis that takes linear algebra and asks what happens when the basis becomes infinite. The question is more subtle than it seems, because infinity implies convergence and convergence implies topology. Still, it is in my opinion the coolest part of analysis (my algebraist bias shows here) and I think every mathematics enthusiast should study it. Naturally, it's hard to avoid the obvious choice:

**[Functional Analysis](https://www.amazon.com/Functional-Analysis-Introduction-Princeton-Lectures/dp/0691113874/)**, *Elias M. Stein, Rami Shakarchi*

<img src="/learn-mathematics/img/stein-functional.jpg" alt="Stein & Shakarchi, Vol.4" width="200px"/>

However, this is not the book I used to learn functional analysis. Instead, I used the following book:

**[Introductory Functional Analysis with Applications](https://www.amazon.com/Introductory-Functional-Analysis-Applications-Kreyszig/dp/0471504599/)**, *Erwin Kreyszig*

<img src="/learn-mathematics/img/kreyszig.jpg" alt="Kreyszig" width="200px"/>

This is a classic for a reason. The exposition is great and very gentle, you don't need much to learn with it. In fact, I took a class using this book when I was in my undergrad and the hardest requirement was basic topology. Another book that I really liked is this one:

**[Functional Analysis](https://www.amazon.com/Functional-Analysis-Peter-D-Lax/dp/0471556041/)**, *Peter D. Lax*

<img src="/learn-mathematics/img/lax.jpg" alt="Lax" width="200px"/>

This is perhaps the coolest textbook of the bunch because it includes very cool sections on stuff that you rarely see in introductory functional analysis textbooks. It's harder than Kreyszig though. Also, the chapters are very short.

### Probability and Stochastics

You have perhaps already encountered probability at the graduate level depending on your choice of measure theory textbook. In this section, I give textbooks that focus mostly on graduate probability and where measure theory is either assumed or in an appendix or something. If the book is too difficult, try looking at one of the measure theory textbooks that discuss probability as well.

**[Foundations of Modern Probability](https://link.springer.com/book/10.1007/978-3-030-61871-1)**, *Olav Kallenberg*

<img src="/learn-mathematics/img/kallenberg.webp" alt="Kallenberg" width="200px"/>

This gigantic book (now re-edited by Springer in two volumes) is my favorite book on graduate probability, but it is huge. Do not expect to read this in a few weeks, this will take months and months to go through. On the flipside, it is exceptionally clear and I find it outstanding. If you want something smaller, this classic is worth it:

**[Probability](https://www.amazon.com/Probability-Graduate-Texts-Mathematics-v/dp/0387945490/)**, *A. N. Shiryaev*

<img src="/learn-mathematics/img/shiryaev.jpg" alt="Shiryaev" width="200px"/>

I love this book. It starts with intuitive probability and goes from there. It has this unmistakebly Russian flavor to it, but at the same time it gives enough examples that you do not feel completely lost. If you're more interested in stochastic calculus specifically, this is a good reference:

**[Brownian Motion and Stochastic Calculus](https://www.amazon.com/Brownian-Stochastic-Calculus-Graduate-Mathematics/dp/0387976558/)**, *Ioannis Karatzas, Steven E. Shreve*

<img src="/learn-mathematics/img/karatzas.jpg" alt="Karatzas" width="200px"/>

Another classic is this, which I have used as a reference before:

**[Brownian Motion, Martingales and Stochastic Calculus](https://www.amazon.com/Brownian-Martingales-Stochastic-Calculus-Mathematics/dp/3319310887/)**, *Jean-François le Gall*

<img src="/learn-mathematics/img/legall.jpg" alt="Le Gall" width="200px"/>

Taking this further, this is the best book I know on stochastic differential equations:

**[Stochastic Differential Equations](https://www.amazon.com/Stochastic-Differential-Equations-Introduction-Applications/dp/3540047581/)**, *Bernt Øksendal*

<img src="/learn-mathematics/img/oksendal.jpg" alt="" width="200px"/>

### Harmonic Analysis

Okay, this section I do not know well as the only harmonic analysis I have looked at was some basics about the Fourier integral on LCA groups and a few keypoints about Tate's thesis. For this reason, I will only suggest one book: the one I used to learn some basic concepts.

**[Principles of Harmonic Analysis](https://www.amazon.com/Principles-Harmonic-Analysis-Universitext-Deitmar-ebook/dp/B00PUM0HJM/)**, *Anton Deitmar, Siegfried Echterhoff*

<img src="/learn-mathematics/img/deitmar.jpg" alt="Deitmar" width="200px"/>

### Dynamical Systems

Dynamical systems is roughly the idea of studying differential equations through a geometric lens. It's a powerful tool and it has really cool applications, such as ecology and the like. There are two books I really like on the subject. The first one is this absolute classic:

**[Differential Equations, Dynamical Systems and an Introduction to Chaos](https://www.amazon.com/Differential-Equations-Dynamical-Systems-Introduction/dp/0123820103/)**, *Morris W. Hirsch, et al*

<img src="/learn-mathematics/img/hirsch-smale.jpg" alt="Smale" width="200px"/>

This book was written in part by one of my favorite mathematician ever, Stephen Smale. The book is great, it covers a wide variety of topic at a level suitable for the subject. Great stuff. That being said, this wouldn't be my list if I didn't recommend V.I. Arnol'd:

**[Ordinary Differential Equations](https://link.springer.com/book/9783540345633)**, *Vladimir I. Arnol'd*

<img src="/learn-mathematics/img/arnold.jpg" alt="Arnold" width="200px"/>

I love Arnol'd, read his books.

### Partial Differential Equations

While we have seen ordinary differential equations in the first part, studying partial differential equations is a whole new ball game entirely. For a very large portion of them, we have no idea how to solve them directly (or we can't) and we need either weak solutions or numerical methods. This is a subject I do not know very well so I cannot recommend a lot of different books, but I liked reading a bit of this one:

**[Partial Differential Equations](https://www.amazon.com/Partial-Differential-Equations-Graduate-Mathematics/dp/1470469421/)**, *Lawrence C. Evans*

<img src="/learn-mathematics/img/evans.jpg" alt="Evans" width="200px"/>

There is another book I have seen before and I have used when I followed a seminar on graduate functional analysis:

**[Functional Analysis, Sobolev Spaces and Partial Differential Equations](https://www.amazon.com/Functional-Analysis-Differential-Equations-Universitext/dp/0387709134/)**, *Haim Brezis*

<img src="/learn-mathematics/img/brezis.jpg" alt="Brezis" width="200px"/>

What I like about it is that it mixes functional analysis and PDEs, two topics that are closely intertwined. Give it a try.

## Algebra

In this section, we revisit abstract algebra but go much, much further.

### Graduate Algebra

A graduate course in algebra can mean anything and everything. In general, it revisits topics from undergraduate abstract algebra but goes at a much faster pace. My favorite textbook on the subject is:

**[Basic Algebra I-II](https://www.amazon.com/Basic-Algebra-Second-Dover-Mathematics/dp/0486471896/)**, *Nathan Jacobson*

<img src="/learn-mathematics/img/jacobson.jpg" alt="Jacobson" width="200px"/>

Jacobson is the father of modern algebra, the Jacobson radical being named after him. His book is refreshing (although I wouldn't use it for undergrad) and I personally found his explanations to be some of my favorites. That being said, the standard textbook in the subject was written by an author that has already featured prominently on this list:

**[Algebra](https://www.amazon.com/Algebra-Graduate-Texts-Mathematics-Serge/dp/038795385X/)**, *Serge Lang*

<img src="/learn-mathematics/img/lang-algebra.jpg" alt="Lang Algebra" width="200px"/>

This book is huge, both physically and in terms of actual content. It covers so much and is so authorative, but I personally find it a bit dry. It is also notoriously difficult. A more gentle textbook (in my opinion) but with a similar style is:

**[Algebra](https://www.amazon.com/Algebra-Graduate-Texts-Mathematics-v/dp/0387905189/)**, *Thomas W. Hungerford*

<img src="/learn-mathematics/img/hungerford.jpg" alt="Hungerford" width="200px"/>

Hungerford is great and probably what I would use if I had to teach a graduate algebra sequence myself.

### Galois Theory

Galois theory is arguably the heart of abstract algebra and in large parts its catalyst, at least when it comes to groups and fields. It is a beautiful theory with a master theorem. If you have taken a graduate algebra class, you probably already saw the subject. If you haven't (or if you want another exposition), here is my favorite place to read about it:

**[Fields and Galois Theory](https://www.jmilne.org/math/CourseNotes/ft.html)**, *J.S. Milne*

<img src="/learn-mathematics/img/milne-ft.jpg" alt="Milne FT" width="200px"/>

J.S. Milne is a fantastic author, and most of his works are completely free on [his website](https://www.jmilne.org/math/). Almost everything he has written will be referenced in this list because it's great, systematic and free. And free books are always welcome! Either way, here is the classic reference on the subject:

**[Galois Theory](https://www.amazon.com/Galois-Theory-Graduate-Texts-Mathematics/dp/038790980X/)**, *Harold M. Edwards*

<img src="/learn-mathematics/img/edwards.jpg" alt="" width="200px"/>

What I like most about the book is that the author chose to discuss at lengths about the history of the subject, especially where it came from and what allowed Galois to discover his famous theorem.

### Commutative Algebra

Commutative algebra is the backbone of algebraic geometry and algebraic number theory and is a crucial course in the life of an algebraist. There are many different great books on the subject, so I will list a few. First, my favorite out of them all:

**[A Term of Commutative Algebra](http://web.mit.edu/18.705/www/13Ed.pdf)**, *Allen Altman, Steven Kleiman*

<img src="/learn-mathematics/img/term-commutative.png" alt="A Term of Commutative Algebra" width="200px"/>

It would be better to call this book a free set of lectures notes. The exposition is fantastic and it is the book I used most when I was learning the subject. The exercises are great, and I love the fact this book uses category theory at length, which helps simplify the arguments in my opinion. It is a modernized version of [Atiyah & Macdonald](https://www.amazon.com/Introduction-Commutative-Algebra-Addison-Wesley-Mathematics/dp/0367091283/), the classic textbook on the subject. The other book I used to learn the subject is this one:

**[Basic Commutative Algebra](https://www.amazon.com/Basic-Commutative-Algebra-Balwant-Singh/dp/9814313610)**, *Balwant Singh*

<img src="/learn-mathematics/img/singh.jpg" alt="Singh" width="200px"/>

Again, fantastic book, fantastic exposition and great exercises. What I love most is the organization of the material. Homological algebra is discussed in two separate chapters that are separated by a few other chapters which is very clever, as it becomes more digestible. The next book is one of the classics written on the subject and it aims to introduce all the necessary algebra to be able to read Hartshorne (which we will see below):

**[Commutative Algebra](https://www.amazon.com/Commutative-Algebra-Algebraic-Geometry-Mathematics/dp/0387942696/)**, *David Eisenbud*

<img src="/learn-mathematics/img/eisenbud.jpg" alt="Eisenbud" width="200px"/>

This book is huge however. It really isn't written in the same manner as the two above. There are lengthy discussions which is good if you like that, bad if you don't. The first chapter is maybe how I would introduce commutative algebra to students, by starting with algebraic geometry. There is one more reference on general commutative algebra I would like to give:

**[Commutative Ring Theory](https://www.amazon.com/Commutative-Cambridge-Studies-Advanced-Mathematics/dp/0521367646/)**, *Hideyuki Matsumura*

<img src="/learn-mathematics/img/matsumura.jpg" alt="Matsumura" width="200px"/>

I couldn't possibly make a list of commutative algebra books without mentioning this gem. It's a classic for a reason. Go read it, you won't be disappointed. Finally, here's a recommendation for people interested in the computational side of commutative algebra (think Gröbner bases and the like):

**[Computational Commutative Algebra I-II](https://www.amazon.com/Computational-Commutative-Algebra-Martin-Kreuzer/dp/354067733X/)**, *Martin Kreuzer, Lorenzo Rabbiano*

<img src="/learn-mathematics/img/kreuzer.jpg" alt="Kreuzer" width="200px"/>

I used these books to help me study post-quantum cryptography and it served me excellently. It is sometimes a bit rough, but with enough patience you will get through it. It might be better as a reference.

### Homological Algebra

Homological algebra takes homology (the geometric-topological construct) as a starting point and generalizes from there. It is a very important tool in modern algebra. I actually haven't found many books I like about it. I mostly learned it from the commutative algebra books above, but there is one exposition I actually like a good deal:

**[An Introduction to Homological Algebra](https://www.amazon.com/Introduction-Homological-Algebra-Universitext/dp/0387245278/)**, *Joseph J. Rotman*

<img src="/learn-mathematics/img/homological.jpg" alt="Homological" width="200px"/>

This was the main external reference I used when I learned the subject, and I liked the way things were explained. I didn't feel like it was just pure abstract nonsense, which I cannot say for every homological algebra book I've seen. There's also this classic on the subject:

**[Homology](https://www.amazon.com/Homology-Classics-Mathematics-Saunders-MacLane/dp/3540586628/)**, *Saunders MacLane*

<img src="/learn-mathematics/img/homology.jpg" alt="Homology" width="200px"/>

Personally, I like reading MacLane and I think all his books are great. The text is well written and the explanations are nice. I still prefer Rotman but you can't go wrong with either of them.

### Representation Theory

Okay, now this is a subject I do not know a lot about, so I will not be able to recommend a lot of things. Representation theory is the idea that linear algebra was easier after all, so maybe we could try our best to replicate it. I have only looked at three books, the first one being my favorite:

**[Representation Theory](https://www.amazon.com/Representation-Theory-Course-Graduate-Mathematics/dp/0387974954/)**, *William Fulton, Joe Harris*

<img src="/learn-mathematics/img/fulton-harris.jpg" alt="Fulton Harris" width="200px"/>

So this is a big book. But it's worth it. It's the classic treatise on the subject and it deals with the subject matter well. I haven't read very far, but I have liked what I have read. Next is a book written by one of the founding fathers of modern algebraic geometry and one of the greatest mathematician of all time, Jean-Pierre Serre:

**[Linear Representations of Finite Groups](https://www.amazon.com/Linear-Representations-Finite-Graduate-Mathematics/dp/0387901906/)**, *J.-P. Serre*

<img src="/learn-mathematics/img/serre.jpg" alt="Serre" width="200px"/>

Serre is a mathematical genius and it shows. Everything flows nicely and it is the text that was used in the course given at my university, although I ended up not taking it in the end. I think it is interesting it grew out of lecture notes for chemistry students. That doesn't make it easy though, so be warned. Finally, the best book I know on Lie algebras and their representations:

**[Introduction to Lie Algebras and Representation Theory](https://www.amazon.com/Introduction-Algebras-Representation-Graduate-Mathematics/dp/0387900535/)**, *James E. Humphreys*

<img src="/learn-mathematics/img/humphreys-lie.jpg" alt="" width="200px"/>

This book is *hard*. But it is a great book, and Lie algebras are ubiquitous in modern mathematics.

## Topology

In this section, we continue the work we did in the general topology section in the first part.

### Algebraic Topology

Algebraic Topology is a beautiful theory and one of my favorite subjects ever. The rough idea is that instead of studying homeomorphisms directly (which are oftentimes hard to construct), why not find algebraic invariants on topological spaces instead? This is exactly what algebraic topology deals with, and it is great. The textbook I used to learn the subject is:

**[Algebraic Topology](https://www.amazon.com/Algebraic-Topology-Allen-Hatcher/dp/0521795400/)**, *Allen Hatcher*

<img src="/learn-mathematics/img/hatcher.jpg" alt="Hatcher" width="200px"/>

This book is a bit infamous in that some people absolutely love it, and some others absolutely hate it. Personally, I love the way Hatcher discusses algebraic topology, I find it very visual and intuitive. That doesn't mean it is easy though, and you will have to work for it, but it's great. I liked the appendix on cell complexes, and I liked the treatment of cellular homology more generally. Another great book is:

**[An Introduction to Algebraic Topology](https://www.amazon.com/Introduction-Algebraic-Topology-Graduate-Mathematics/dp/0387966781/)**, *Joseph J. Rotman*

<img src="/learn-mathematics/img/rotman-topology.jpg" alt="Rotman Topology" width="200px"/>

As you might have noticed by now, I love reading Rotman. His books are always well written and very clear and this one is no stranger to this. I just wish there was a bit more on cohomology. Here's another recommendation taking a different approach:

**[Algebraic Topology](https://www.amazon.com/Algebraic-Topology-Course-Graduate-Mathematics/dp/0387943277/)**, *William Fulton*

<img src="/learn-mathematics/img/fulton.jpg" alt="Fulton" width="200px"/>

The approach here is pretty different. Cohomology is introduced first and the theory kind of unravels from there into homology groups and then the fundamental group, which is usually the exact opposite of how students learn algebraic topology. Personally, I like this order much better as I find it more intuitive to understand. I love that it starts from path integrals, it makes the entire presentation less abstract and you immediately understand how and why (co)homology was introduced. Finally, it's impossible to make a list of algebraic topology books without mentioning this one:

**[Differential Forms in Algebraic Topology](https://www.amazon.com/Differential-Algebraic-Topology-Graduate-Mathematics/dp/1441928154/)**, *Raoul Bott, Loring W. Tu*

<img src="/learn-mathematics/img/bott-tu.jpg" alt="Bott Tu" width="200px"/>

This book uses differential forms throughout to discuss algebraic topology. It discusses spectral sequences as well as characteristic classes (I really liked that part).

### Low-Dimensional Topology

Low-Dimensional Topology is about manifolds in 2, 3 and 4 dimensions. Sadly, I have not taken a class on 3 and 4 manifolds specifically (there is a very, very rich theory there), but I have taken a class on knot theory. We used this textbook:

**[Knots, Links, Braids and 3-Manifolds](https://www.amazon.com/Knots-Links-Braids-3-Manifolds-Low-Dimensional/dp/0821808982/)**, *V. V. Prasolov, A. B. Sossinsky*

<img src="/learn-mathematics/img/prasolov.jpg" alt="Prasolov" width="200px"/>

It's a Russian-style book on the subject. I thought it was good, I liked the explanations but it could have been a bit more approachable. I used the following to get some more intuition and understand things better:

**[The Knot Book](https://www.amazon.com/Knot-Book-Colin-Adams/dp/0821836781/)**, *Colin Adams*

<img src="/learn-mathematics/img/knot.jpg" alt="Knot Book" width="200px"/>

It's an interesting book, I love the explanations and the way things are introduced, it makes a lot more sense. Much easier too. I think this would be a great book for undergrad research topics.

### Homotopy Theory

Homotopy is notably difficult to deal with. Whereas homology groups of spheres are basically trivial to compute, their (stable) homotopy counterparts are a nightmare. I have not done much homotopy theory, I have only read a bit of this book in the context of a homotopical algebra class:

**[Categorical Homotopy Theory](https://www.amazon.com/Categorical-Homotopy-Theory-Mathematical-Monographs-ebook/dp/B00J8LQS80/)**, *Emily Riehl*

<img src="/learn-mathematics/img/riehl-homotopy.jpg" alt="Riehl Homotopy" width="200px"/>

I knew Riehl from her category theory textbook (see below), and I liked it well enough. Apparently, this other book is really good, but I can't say much as I haven't read it in any deep meaningful way:

**[Introduction to Homotopy Theory](https://www.amazon.com/Introduction-Homotopy-Theory-Universitext-Arkowitz/dp/1441973281/)**, *Martin Arkowitz*

<img src="/learn-mathematics/img/arkowitz.jpg" alt="Arkowitz" width="200px"/>

### Symplectic Topology

This section describes a relatively recent development, symplectic topology, a particular interest of mine. The fundamental result is the non-squeezing theorem. Some people might argue this is a part of symplectic geometry, I personally disagree. If you want to argue, argue with Dusa McDuff (you will most likely lose the argument though, so beware). By the way, she wrote this absolute gem:

**[Introduction to Symplectic Topology](https://www.amazon.com/Introduction-Symplectic-Topology-Graduate-Mathematics/dp/0198794908/)**, *Dusa McDuff*

<img src="/learn-mathematics/img/dusa.jpg" alt="McDuff" width="200px"/>

This is the book I used to study symplectic topology. It covers J-holomorphic curves and all the standard tools of the trade. I supplemented the book with this one:

**[Symplectic Invariants and Hamiltonian Dynamics](https://www.amazon.com/Symplectic-Invariants-Hamiltonian-Birkh%C3%A4user-Lehrb%C3%BCcher/dp/3764350660/)**, *Helmut Hofer, Eduard Zehnder*

<img src="/learn-mathematics/img/zehnder.jpg" alt="Zehnder" width="200px"/>

The main unifying theme behind the book is symplectic capacities and the interesting rigidity phenomena that arise in the symplectic world.

## Differential Geometry

We did some differential geometry in the first part, but here, we will generalize the theory from curves and surfaces to arbitrary dimensions, leading us to arguably the most important object in geometry, the manifold.

### Smooth Manifolds

To do analysis, we require our manifolds to be smooth, meaning they need to carry a structure that allows us to do calculus on them. My favorite book on the subject is this masterpiece:

**[Introduction to Smooth Manifolds](https://www.amazon.com/Introduction-Smooth-Manifolds-Graduate-Mathematics/dp/1441999817/)**, *John M. Lee*

<img src="/learn-mathematics/img/smooth.jpg" alt="Smooth Manifolds" width="200px"/>

I could write an essay on John M. Lee. He is a fantastic writer and this book is the only book I have ever wanted signed by an author. It is fantastic, I love it. The material is selected well, it has my favorite exposition of smooth manifolds, tensors and differential forms. If you are going to study modern geometry, get this book. Another book I like (although not as much) is this:

**[An Introduction to Manifolds](https://www.amazon.com/Introduction-Manifolds-Second-Universitext/dp/1441973990/)**, *Loring W. Tu*

<img src="/learn-mathematics/img/tu.jpg" alt="Tu" width="200px"/>

What I like is the appropriate length of the book, it's just right. Practically everything I read in the book I liked except for one thing: The section on differential forms. I thought the explanations were dry, not well-motivated and that it was confusing. To this day, I still don't like it. Other than this, great book and good explanations of the basic parts of the theory. I liked the chapter on quotient manifolds a lot.

### Riemannian Geometry

Riemannian geometry is what happens when you add a metric to a smooth manifold. We can now compute distances and take geodesics. This subject is crucial to modern physics as well. My favorite book on the subject without much surprise is:

**[Introduction to Riemannian Manifolds](https://www.amazon.com/Introduction-Riemannian-Manifolds-Graduate-Mathematics/dp/3319917544/)**, *John M. Lee*

<img src="/learn-mathematics/img/lee-riem.jpg" alt="Lee Riemannian" width="200px"/>

It's Lee and it's wonderful. The newest version had a title change, I knew it as "An Introduction to Curvature"
, but I believe it is the same book, just rewritten to be better. The classic text on the subject however is this book:

**[Riemannian Geometry](https://www.amazon.com/Riemannian-Geometry-Manfredo-Perdigao-Carmo/dp/0817634908/)**, *Manfredo P. Do Carmo*

<img src="/learn-mathematics/img/docarmo-riem.jpg" alt="" width="200px"/>

It's a standard reference for a reason. If you liked Do Carmo's book on classical differential geometry, you will most likely like this one too. Finally, if your main interest is general relativity, I think this book might be of use to you:

**[Semi-Riemannian Geometry with Applications to Relativity](https://www.amazon.com/Semi-Riemannian-Geometry-Applications-Relativity-Mathematics/dp/0125267401/)**, *Barrett O'Neill*

<img src="/learn-mathematics/img/o'neill.jpg" alt="O'Neill" width="200px"/>

It discusses semi-Riemannian geometry (what I would personally call Lorentzian geometry, but maybe it is my interest in physics showing). I personally found the book a bit rough in terms of explanations, it is a bit old and you can tell. It's still great though, and I'm glad to see actual applications to relativity.

### Lie Groups

This section slightly intersects with the one on representation theory, so you might want to check there first. Lie initially studied symmetries in differential equations and out of it grew the concept of a Lie group, which roughly speaking encodes the infinitesimal symmetries of a system. Another way to look at it is as a smooth manifold with a compatible group structure, and as such some differential topology knowledge is useful when studying the subject. I mostly studied Lie groups from a mathematical gauge theory book (you can find it further down below), but I also used this:

**[Introduction to the Theory of Lie Groups](https://www.amazon.com/Introduction-Theory-Lie-Groups-Universitext-ebook/dp/B073H646GB/)**, *Roger Godement*

<img src="/learn-mathematics/img/godement.jpg" alt="Godement" width="200px"/>

It is a pretty small book (I like that series personally) and it has plenty of examples. For some reason, I found it a bit hard to get into at first. I also used this:

**[Lie Groups, Lie Algebras, and Representations](https://www.amazon.com/Lie-Groups-Algebras-Representations-Introduction/dp/3319134663/)**, *Brian C. Hall*

<img src="/learn-mathematics/img/hall-lie.jpg" alt="Hall Lie" width="200px"/>

I was familiar with Hall from his book on quantum mechanics (which I like). This seems to be a standard reference and it shows. The exercises are great and the explanations are good. Probably what I would use if I wanted a book to start with. Slightly easier is:

**[Naive Lie Theory](https://www.amazon.com/Naive-Theory-Undergraduate-Texts-Mathematics/dp/0387782141/)**, *John Stillwell*

<img src="/learn-mathematics/img/naive.jpg" alt="Naive" width="200px"/>

I like Stillwell, he wrote a fantastic book on mathematics history. The approach to Lie theory here is pretty unique and it is easier to get into in my opinion. Suitable to advanced undergraduates. Obviously doesn't go nearly as far as the other books.

### Symplectic and Contact Geometry

Symplectic and contact geometry are pairs of geometry (which one occurs depends on the dimension of the manifold) that have very rich and interesting structures, pretty different ones from basic smooth manifolds. For instance, symplectic manifolds are historical generalizations of the notion of phase space in Hamiltonian mechanics and the main symplectic structure is a differential 2-form, traditionally measuring area. As you can see, it requires more machinery than simple topology. I do not know much contact geometry past the basics, but I am familiar with symplectic geometry (from symplectic topology actually) and I have recommendations for it. A book I like to get into these kinds of geometries is this undergraduate textbook:

**[First Steps in Differential Geometry](https://www.amazon.com/First-Steps-Differential-Geometry-Undergraduate/dp/146147731X/)**, *Andrew McInerney*

<img src="/learn-mathematics/img/mcinerney.jpg" alt="McInerney" width="200px"/>

I like the exposition, it is not hard but it isn't trivial either, and the idea of showing all three kinds of geometry is nice and different from the textbooks below. I also like the fact it isn't targeted towards someone who already knows they want to get into symplectic (or contact) geometry, but it can be (and it should be) read by anyone interested in modern geometry. Next is one of the standard texts on symplectic geometry:

**[Lectures on Symplectic Geometry](https://www.amazon.com/Lectures-Symplectic-Geometry-Lecture-Mathematics/dp/3540421955/)**, *Ana Cannas da Silva*

<img src="/learn-mathematics/img/ana.jpg" alt="Ana" width="200px"/>

The lecture notes style of the book is still extremely present and I like it. The exercises-as-projects are a wonderful idea, I wish more books did this. I particularly liked the presentation of the compatibility of symplectic, riemannian and complex structures on a manifold. I just wish the subject was better motivated, it's a bit bland. Personally, I think I might like this book better:

**[An Introduction to Symplectic Geometry](https://www.amazon.com/Introduction-Symplectic-Geometry-Graduate-Mathematics/dp/0821820567/)**, *Rolf Berndt*

<img src="/learn-mathematics/img/berndt.jpg" alt="Berndt" width="200px"/>

There is just something about AMS textbooks, they seem to just work every time I read them. One high point is the connections with mathematical physics, especially the chapter on quantization, a topic I find fascinating.

## Algebraic Geometry

Algebraic geometry is my favorite subject in mathematics, and the one I have dedicated the most time to. It is a jewel and I personally consider it the central field in mathematics. There are many, many, *many* textbooks written about it.

### Classical Algebraic Geometry

Classical algebraic geometry roughly means "algebraic geometry before schemes", although I kind of disagree with this definition for reasons I shall not get into here. Point being, we're usually restricting ourselves to varieties in this context. Of course, the first textbook I mention is the usual:

**[Algebraic Geometry](https://www.jmilne.org/math/CourseNotes/ag.html)**, *J.S. Milne*

<img src="/learn-mathematics/img/milne-ag.png" alt="Milne AG" width="200px"/>

It's free, it's well-written, I like the examples. What is there not to like. But it is not how I learned the theory. Instead, this is the book I used:

**[Algebraic Curves](https://dept.math.lsa.umich.edu/~wfulton/CurveBook.pdf)**, *William Fulton*

<img src="/learn-mathematics/img/fulton-ag.png" alt="Fulton AG" width="200px"/>

Another free book! Algebraic geometry seems to have so many free books (there are more below). Algebraic Curves is a nice book, I find it had just the right amount of difficulty in the exercises and the examples were chosen well. I like Fulton's writing style. I also used the following:

**[Basic Algebraic Geometry 1](https://www.amazon.com/Basic-Algebraic-Geometry-Varieties-Projective/dp/364242726X/)**, *Igor R. Shafarevich*

<img src="/learn-mathematics/img/shafarevich.jpg" alt="Shafarevich" width="200px"/>

Shafarevich wrote two books, this is the first one dealing with varieties. The book is great though I found it more difficult than both Milne and Fulton personally. Still, it has my favorite explanations.

### Modern Algebraic Geometry

Here we are, schemes, the good stuff, the difficult stuff. This is my favorite subject in mathematics. And my favorite book happens to be free! I think most people were expecting to see Hartshorne first, but my favorite is actually:

**[Introduction to Schemes](https://www.uio.no/studier/emner/matnat/math/MAT4215/data/masteragbook.pdf)**, *Geir Ellingsrud, John Christian Ottem*

<img src="/learn-mathematics/img/ottem-ellingsrud.png" alt="Ottem-Ellingsrud" width="200px"/>

I love the presentation of the subject as I found it easiest to learn from personally. The examples *really* help understand what's going on and why schemes are defined the way they are. I think organization could be a bit better though. Another book I love and that I don't see mentioned enough is this:

**[Algebraic Geometry I-II](https://www.amazon.com/Algebraic-Geometry-Examples-Exercises-Mathematik/dp/3658307323?ref_=ast_sto_dp)**, *Ulrich Görtz, Torsten Wedhorn*

<img src="/learn-mathematics/img/gortz.jpg" alt="Görtz-Wedhorn" width="200px"/>

This is a translation of the two German classics on scheme theory. The first one deals with general aspects of schemes while the second one focuses on the cohomology of schemes, a notoriously difficult part of an already notoriously difficult subject. I think if I had to get a single resource to study algebraic geometry (outside of maybe the lecture notes above), it would be this. Next, this insane book that is _also_ free:

**[Foundations of Algebraic Geometry](http://math.stanford.edu/~vakil/216blog/FOAGnov1817public.pdf)**, *Ravi Vakil*

<img src="/learn-mathematics/img/foag.png" alt="FOAG" width="200px"/>

I have used this book as part of a summer course on algebraic geometry taught by Ravi Vakil himself. The course was great and his book was as well, but the writing style is very, very different. The book, while not exactly verbose, is very wordy. The exercises are great though, I love the selection. Things are motivated well, and I like that, unlike the obvious choice for a textbook in algebraic geometry:

**[Algebraic Geometry](https://www.amazon.com/Algebraic-Geometry-Graduate-Texts-Mathematics/dp/0387902449/)**, *Robin Hartshorne*

<img src="/learn-mathematics/img/hartshorne.jpg" alt="Hartshorne" width="200px"/>

Yes, of course, Hartshorne. What a surprise. This book strikes fear in the eyes of many for its exercises, but it is exactly the good part of the book. I find Hartshorne's exposition of the theory to be a bit rough, perhaps because it was the first textbook to really synthesize the magic that had happened when Grothendieck, Serre and the others worked on the foundations of algebraic geometry. Still, it is a classic for a reason and going through the exercises in the book is a rite of passage for any prospective student of algebraic geometry. Interestingly enough, none of these options were the very first textbook I worked through. Instead, it was the following:

**[Algebraic Geometry and Arithmetic Curves](https://www.amazon.com/Algebraic-Geometry-Arithmetic-Graduate-Mathematics/dp/0199202494/)**, *Qing Liu*

<img src="/learn-mathematics/img/liu.jpg" alt="Liu" width="200px"/>

This book, while extremely well written, is hard. Personally, I found it a tad bit harder to read than Hartshorne (many will disagree with me here). I think this book is better once you already know some algebraic geometry because Liu takes quite a few shortcuts here and there (mind you, so does Hartshorne). Nonetheless, it's a good book and there's a reason it's recommended. Not to mention, it does discuss a bit of arithmetic geometry, which I like.

### Complex Geometry

Complex geometry is algebraic geometry over the complex numbers. I don't know too much about it, but everyone I know who has studied it has loved it. I only know three books, the first one by Huybrechts:

**[Complex Geometry](https://www.amazon.com/Complex-Geometry-Introduction-Daniel-Huybrechts/dp/3540212906/)**, *Daniel Huybrechts*

<img src="/learn-mathematics/img/huybrechts.jpg" alt="Huybrechts" width="200px"/>

This discusses both algebraic and analytic aspects of complex and Kähler manifolds. The book I liked best was:

**[Algebraic Geometry over the Complex Numbers](https://www.amazon.com/Algebraic-Geometry-Complex-Numbers-Universitext/dp/1461418089/)**, *Donu Arapura*

<img src="/learn-mathematics/img/arapura.jpg" alt="Arapura" width="200px"/>

I especially liked the discussion on sheaf theory. In general, the section on sheaves and geometry where the author discusses manifolds via sheaves was great. Finally, there's the classic:

**[Algebraic Curves and Riemann Surfaces](https://www.amazon.com/Algebraic-Riemann-Surfaces-Graduate-Mathematics/dp/0821802682/)**, *Rick Miranda*

<img src="/learn-mathematics/img/miranda.jpg" alt="Arapura" width="200px"/>

Miranda is a classic book on the subject. I like that it starts with maybe my favorite object in mathematics: Riemann surfaces. If I had to get one book on complex geometry, I'd make it this one.

### Computational Algebraic Geometry

Computational Algebraic Geometry tries to solve systems of polynomial equations via numerical methods such as Gröbner bases. Personally, I love this subject and it's one of my favorite part of algebraic geometry. The easiest book I know is:

**[Ideals, Varieties, and Algorithms](https://www.amazon.com/Ideals-Varieties-Algorithms-Computational-Undergraduate/dp/3319167200/)**, *David A. Cox, et al*

<img src="/learn-mathematics/img/cls.jpg" alt="CLS" width="200px"/>

Simple and great, love the examples and the explanations. That being said, I think it could use some more difficult exercises. There is a graduate-level version:

**[Using Algebraic Geometry](https://www.amazon.com/Using-Algebraic-Geometry-Graduate-Mathematics-ebook/dp/B00FB0FL6W/)**, *David A. Cox, et al*

<img src="/learn-mathematics/img/cls-grad.jpg" alt="CLS Graduate" width="200px"/>

This book was written by the same authors and it goes a bit more in-depth (and faster) through the subject. Personally, I'd just use both.

### Étale Cohomology

Étale Cohomology is a very specific part of algebraic geometry, and I debated even mentioning it here. But I mean, why not? The only books I have looked at for this are written by Milne, what a surprise. I have not finished either though, because my master's thesis was asking for my attention. Anyway, here is the book:

**[Étale Cohomology](https://www.amazon.com/%C3%89tale-Cohomology-PMS-33-Princeton-Mathematical/dp/0691171106/)**, *J.S. Milne*

<img src="/learn-mathematics/img/milne-ec.jpg" alt="Milne ECohom" width="200px"/>

This is the book version. It goes faster and treads more ground than the lecture notes below:

**[Lectures on Étale Cohomology](https://www.jmilne.org/math/CourseNotes/lec.html)**, *J.S. Milne*

<img src="/learn-mathematics/img/milne-lec.png" alt="Milne LEC" width="200px"/>

I like those notes, they are free and they introduce the subject in a way that makes it clearer why the machinery is necessary. Good stuff.

### Algebraic Groups

We said in the Lie groups section that Lie groups were smooth manifolds that had a compatible group structure. What about schemes that have a compatible group structures? Well, here we are: algebraic groups. I was set to take a course on the subject but I dropped it because I had too much to do. I don't know much about it though, but I can still mention the books I had looked at. The book required for the course was:

**[Linear Algebraic Groups](https://www.amazon.com/Linear-Algebraic-Groups-Graduate-Mathematics/dp/0387901086/)**, *James E. Humphreys*

<img src="/learn-mathematics/img/humphreys-ag.jpg" alt="Humphreys AG" width="200px"/>

It's Humphreys so I assume it is both difficult and great at the same time. Milne wrote a book on the subject that is probably worth checking out:

**[Algebraic Groups](https://www.amazon.com/Algebraic-Groups-Cambridge-Advanced-Mathematics-ebook/dp/B074XC6NCP/)**, *J.S. Milne*

<img src="/learn-mathematics/img/milne-agroups.jpg" alt="Milne AGroups" width="200px"/>

In general, if I had a student interested in modern algebra, I'd just have them read everything Milne wrote.

### Elliptic Curves

Elliptic curves are some of the most interesting objects in mathematics. I have taken multiple courses on the subject and it's always a pleasure. My favorite first book on the subject is this:

**[Elliptic Curves](https://www.amazon.com/Elliptic-Curves-Cryptography-Mathematics-Applications/dp/1420071467/)**, *Lawrence C. Washington*

<img src="/learn-mathematics/img/washington.jpg" alt="Washington" width="200px"/>

The book is exceptionally clear with good exercises. I loved the parts that discussed cryptography. Personally, I would supplement it with something else, maybe a bit more difficult. I used this book:

**[The Arithmetic of Elliptic Curves](https://www.amazon.com/Arithmetic-Elliptic-Curves-Graduate-Mathematics/dp/0387094938/)**, *Joseph H. Silverman*

<img src="/learn-mathematics/img/silverman.jpg" alt="Silverman" width="200px"/>

It's a standard reference textbook for a reason. The section on elliptic curves in ℂ was very nice, one of the coolest bit of mathematics I have learned. Of course, I have to recommend Milne as well:

**[Elliptic Curves](https://www.amazon.com/Elliptic-Curves-Second-James-Milne-ebook/dp/B08H5GM99Y/)**, *J.S. Milne*

<img src="/learn-mathematics/img/milne-ecurve.jpg" alt="" width="200px"/>

Not much to say on this one, I haven't used it a whole lot but it's Milne so it's hard to go wrong. There is a follow-up:

**[Complex Multiplication](https://www.jmilne.org/math/CourseNotes/cm.html)**, *J.S. Milne*

<img src="/learn-mathematics/img/milne-cm.png" alt="" width="200px"/>

Complex multiplication is a fascinating topic that has a rich history. While the theory was originally developed for elliptic curves, it grew to include abelian varieties more generally (see below). The reference I know and I consulted a bit is Lang:

**[Complex Multiplication](https://www.amazon.com/Complex-Multiplication-Grundlehren-mathematischen-Wissenschaften/dp/0387907866/)**, *Serge Lang*

<img src="/learn-mathematics/img/lang-cm.jpg" alt="Lang CM" width="200px"/>

### Arithmetic Geometry

Arithmetic geometry is at the crossroads between algebraic geometry and modern number theory. Roughly speaking, it is what happens when you are interested in doing algebraic geometry over things like the integers. It is a wonderful subject, and much of the machinery behind algebraic geometry (schemes and the likes) were developped to solve questions in arithmetic geometry, most notably the Weil conjectures, which include the famous finite field version of Riemann's Hypothesis. Part of the subject is generalizing things such as elliptic curves:

**[Abelian Varieties](https://www.jmilne.org/math/CourseNotes/AV.pdf)**, *J.S. Milne*

<img src="/learn-mathematics/img/milne-av.png" alt="Milne AV" width="200px"/>

Abelian varieties are what happens when you are interested in (projective) algebraic varieties that are also algebraic groups. Elliptic curves are an example, but there are others. The lectures notes by Milne on the subject are a great place to start. A more recent book that looks at arithmetic geometry is:

**[An Invitation to Arithmetic Geometry](https://www.amazon.com/Invitation-Arithmetic-Geometry-Graduate-Mathematics/dp/1470467259/)**, *Dino Lorenzini*

<img src="/learn-mathematics/img/lorenzini.jpg" alt="lorenzini" width="200px"/>

I like that the book starts with commutative algebra and progressively builds up to the full proof of the Riemann Hypothesis in the finite case. Good stuff, I will probably read it in full soon.

## Number Theory

We have met number theory in the first part, but in this section we introduce analytic and algebraic tools that let us go further and prove some really interesting theorems.

### Analytic Number Theory

Analytic number theory uses (complex) analysis to prove some truly spectacular results such as the prime number theorem. My favorite introduction to the subject is:

**[Introduction to Analytic Number Theory](https://www.amazon.com/Introduction-Analytic-Number-Theory-Apostol/dp/0387901639/)**, *Tom M. Apostol*

<img src="/learn-mathematics/img/apostol.jpg" alt="Apostol" width="200px"/>

Apostol is a great writer, I also liked his calculus and especially his analysis book. I liked the discussions in the first chapter. It is easier than something like:

**[Multiplicative Number Theory](https://www.amazon.com/Multiplicative-Number-Theory-Graduate-Mathematics/dp/0387950974/)**, *Harold Davenport*

<img src="/learn-mathematics/img/davenport.jpg" alt="Davenport" width="200px"/>

A standard reference on the subject. Personally I do not know a whole lot of analytic number theory so I cannot tell you too much about it, I only used it as a reference. Another standard reference that is beloved by many is the following:

**[Multiplicative Number Theory I](https://www.amazon.com/Multiplicative-Number-Theory-Classical-Mathematics/dp/0521849039/)**, *Hugh L. Montgomery, Robert C. Vaughan*

<img src="/learn-mathematics/img/montgomery.jpg" alt="Montgomery" width="200px"/>

### Algebraic Number Theory

Algebraic number theory uses tools from abstract algebra (especially commutative algebra) to study number theory. Generally, the subject deals with extensions of the rational numbers, with the ultimate goal being to find the absolute Galois group of the rationals. There are multiple books I really like. The one I used to learn the basics of the subject is:

**[Algebraic Number Theory](https://www.amazon.com/Algebraic-Number-Grundlehren-mathematischen-Wissenschaften/dp/3540653996/)**, *Jürgen Neukirch*

<img src="/learn-mathematics/img/neukirch.jpg" alt="Neukirch" width="200px"/>

It's well written and I like the examples. The exercises are well chosen too. Great recommendation. Next is:

**[Algebraic Number Theory](https://www.jmilne.org/math/CourseNotes/ANT.pdf)**, *J.S. Milne*

<img src="/learn-mathematics/img/milne-ant.png" alt="Milne ANT" width="200px"/>

The standard Milne recommendation. He wrote extensively about algebraic number theory and it is a wonderful starting place. I also suggest the other notes he wrote on the subject:

**[Class Field Theory](https://www.jmilne.org/math/CourseNotes/ANT.pdf](https://www.jmilne.org/math/CourseNotes/cft.html)**, *J.S. Milne*

<img src="/learn-mathematics/img/milne-CFT.png" alt="Milne ANT" width="200px"/>

If you are looking for something slightly easier and more approachable, I liked the following:

**[Number Fields](https://www.amazon.com/Number-Fields-Universitext-Daniel-Marcus/dp/3319902326/)**, *Daniel A. Marcus*

<img src="/learn-mathematics/img/marcus.jpg" alt="Marcus" width="200px"/>

This focuses on number fields exclusively, i.e. algebraic extensions of the rationals. I found it much more approachable than Neukirch and the like. Great stuff. Finally, the usual Lang recommendation:

**[Algebraic Number Theory](https://www.amazon.com/Algebraic-Number-Theory-Graduate-Mathematics/dp/0387942254/)**, *Serge Lang*

<img src="/learn-mathematics/img/lang-ant.jpg" alt="Lang ANT" width="200px"/>

As usual with Lang, there are interesting discussions on the finer points of the theory. The discussion on ideles and adeles was nice, I like it.

### ***p***-Adic Methods

In real analysis, you saw how to complete the rationals with respect to the Euclidean distance to get the real number system. It turns out there are other possible metrics, namely the *p*-adic metrics. If you complete the rationals with respect to these, you get *p*-adic fields. These are exceptionally cool and I loved the class I took on *p*-adic analysis in particular. The most approachable book I know is:

**[*p*-adic Numbers](https://www.amazon.com/p-adic-Numbers-Introduction-Fernando-Gouv%C3%AAa/dp/3030472949/)**, *Fernando Q. Gouvêa*

<img src="/learn-mathematics/img/gouvea.jpg" alt="Gouvea" width="200px"/>

The book is great and suitable to undergraduates even. I liked chapter 7 on analysis in particular. The book I first used to learn the subject was this:

**[*p*-adic Numbers, *p*-adic Analysis, and Zeta-Functions](https://www.amazon.com/Numbers-Analysis-Zeta-Functions-Graduate-Mathematics/dp/0387960171/)**, *Neal Koblitz*

<img src="/learn-mathematics/img/koblitz.jpg" alt="Koblitz" width="200px"/>

This is harder than Gouvêa and also more exhaustive. The exercises are good, they will help you master the inherent weirdness that comes with *p*-adics. Still, I would read Gouvêa first personally.

### Modular and Automorphic Forms

Modular (and more generally automorphic) forms are special kinds of complex analytic functions with values in a topological group such that they are invariant under the action of a subgroup. They have important applications in number theory, notably through the [Langlands program](https://en.wikipedia.org/wiki/Langlands_program). I do not know too much about them except for the special case of the Eisenstein series and elliptic functions, but I did have to read about it and I used this book:

**[Automorphic Forms](https://www.amazon.com/Automorphic-Forms-Universitext-Anton-Deitmar/dp/1447144341/)**, *Anton Deitmar*

<img src="/learn-mathematics/img/deitmar-af.jpg" alt="Deitmar AF" width="200px"/>

There are a few books written by Deitmar on this list and they are all good, this is no exception. I found it hard, but that was probably due to my inexperience rather than the actual book. At least I think so. Either way, the short amount I read was good, I liked the examples in particular. There is of course:

**[Modular Functions and Modular Forms](https://www.jmilne.org/math/CourseNotes/mf.html)**, *J.S. Milne*

<img src="/learn-mathematics/img/milne-mf.png" alt="Deitmar AF" width="200px"/>

Milne really wrote about everything and made almost all of it free. Absolutely fantastic. It's Milne so it's probably really good, I haven't read much so I can't tell. Finally there is this:

**[Modular Functions and Dirichlet Series in Number Theory](https://www.amazon.com/Modular-Functions-Dirichlet-Graduate-Mathematics/dp/1461269784/)**, *Tom M. Apostol*

<img src="/learn-mathematics/img/apostol-mf.jpg" alt="Apostol MF" width="200px"/>

This is the follow-up book to Apostol's introduction to analytic number theory book.

## Miscellaneous

In this section, I discuss various subjects that didn't fit directly into any of the other, starting with one of my favorite subject.

### Category Theory

Category theory, affectionately called *abstract nonsense*, is an interesting theory. It tries to look at mathematical structures primarily through the lens of maps between them, as per the Grothendieck doctrine. I have read multiple books on the subject when I first learned it for algebraic geometry. The one I read that I liked best was maybe:

**[Category Theory in Context](https://www.amazon.com/Category-Theory-Context-Aurora-Originals/dp/048680903X/)**, *Emily Riehl*

<img src="/learn-mathematics/img/riehl.jpg" alt="Riehl" width="200px"/>

Riehl discusses many, many examples of categories, functors and the like. I love that. I am not a fan of how wordy the book is though, but that's part of the deal since the book is meant to be approachable. Interesting discussion of Kan extensions, I love the title of the chapter. The standard reference is of course:

**[Categories for the Working Mathematician](https://www.amazon.com/Categories-Working-Mathematician-Graduate-Mathematics/dp/1441931236/)**, *Saunders MacLane*

<img src="/learn-mathematics/img/maclane.jpg" alt="MacLane" width="200px"/>

Mac Lane (along with Eilenberg) invented (discovered?) category theory, so it is no surprise the textbook he wrote would be fantastic. And it is. Personally, I found it a tad bit harder to get into, but I liked it better than Riehl once I knew a bit more about category theory. Get both ideally. I also used this:

**[Categories and Sheaves](https://www.amazon.com/Categories-Sheaves-Introduction-mathematischen-Wissenschaften-ebook/dp/B000UG85UQ/)**, *Masaki Kashiwara, Pierre Schapira*

<img src="/learn-mathematics/img/kashiwara.jpg" alt="Kashiwara" width="200px"/>

This book is huge and covers more than is necessary for the vast majority of people. Personally I used it to study sheaves and homological aspects, but it was very rough. I mean the book is written well, but it goes fast and it's not easy to follow in my opinion. Still, it's the best reference I know since it has most anything I'd ever want. Another short book I got that I liked tremendously was this:

**[An Introduction to the Language of Category Theory](https://www.amazon.com/Introduction-Language-Category-Textbooks-Mathematics-ebook/dp/B01MS5LCNA/)**, *Steven Roman*

<img src="/learn-mathematics/img/roman-ct.jpg" alt="Roman-CT" width="200px"/>

Steven Roman is a great writer, his book on Field Theory is exceptional. What's better is that he has a YouTube channel where he presents mathematics. This book in particular has an accompanying YouTube series. Anyway, the book is short and sweet, as is usual with the compact series from Springer. The exercises are nice, on the easier side I would say but I liked them. Finally, here's a textbook that's even easier:

**[Category Theory](https://www.amazon.com/Category-Theory-Oxford-Logic-Guides/dp/0199237182/)**, *Steve Awodey*

<img src="/learn-mathematics/img/awodey.jpg" alt="Awodey" width="200px"/>

The presentation is good and it's very approachable. It's adapted to students of computer science as well in my opinion.

### Mathematical Logic

I know practically nothing about mathematical logic so I will keep this section short. The textbooks I know are these two:

**[A Course in Mathematical Logic for Mathematicians](https://www.amazon.com/Course-Mathematical-Mathematicians-Graduate-Mathematics/dp/1441906142/)**, *Yu. I. Manin*

<img src="/learn-mathematics/img/manin.jpg" alt="Manin" width="200px"/>

A reference on the subject and probably the book I'd use to learn about things. If I'm not mistaken, the latest edition has a chapter on model theory which is a very cool subject. The other reference is this:

**[Mathematical Logic](https://www.amazon.com/Mathematical-Logic-Graduate-Texts-Mathematics/dp/3030738388/)**, *Heinz-Dieter Ebbinghaus, et al*

<img src="/learn-mathematics/img/ebbinghaus.jpg" alt="Ebbinghaus" width="200px"/>

Interestingly enough, it was originally edited in the undergraduate series, but I think they bumped it up to the graduate series for some reason. Either way, I heard it was kind of difficult, but I'm not sure. Maybe it was too difficult for undergrads.

### Graph Theory

Graph Theory is very cool because it's inherently visual, and it has a very wide range of applications. Anything that can be represented as a graph can benefit from it. I know only the very basics and I have read about it in these three books:

**[Graph Theory](https://www.amazon.com/Graph-Theory-Graduate-Texts-Mathematics/dp/1849966907/)**, *J.A. Bondy, U.S.R. Murty*

<img src="/learn-mathematics/img/bondy.jpg" alt="Bondy" width="200px"/>

My favorite of the three. I particularly like the examples. There is also:

**[Graph Theory](https://www.amazon.com/Graph-Theory-Graduate-Texts-Mathematics/dp/3662575604/)**, *Reinhard Diestel*

<img src="/learn-mathematics/img/diestel.jpg" alt="Diestel" width="200px"/>

I believe this is the standard recommendation. As said before, I can't comment much as I haven't read a lot from it. Here's a final recommendation I heard was good from a graph theorist friend of mine:

**[Modern Graph Theory](https://www.amazon.com/Modern-Graph-Theory-Graduate-Mathematics/dp/0387984887/)**, *Béla Bollobás*

<img src="/learn-mathematics/img/bollobas.jpg" alt="Bollobás" width="200px"/>

I am not sure what is meant by "modern" here as I am pretty sure the other two books mentioned above also mention modern methods, but either way check it out.

### Statistics

Some people might object to the classication of statistics as being a subfield of mathematics. Personally, I don't really care. The section is so small anyway it's irrelevant. My favorite book on mathematical statistics is this:

**[Statistics for Mathematicians](https://www.amazon.com/Statistics-Mathematicians-Rigorous-Textbooks-Mathematics-ebook/dp/B01GQ7XQOM/)**, *Victor M. Panaretos*

<img src="/learn-mathematics/img/panaretos.jpg" alt="Panaretos" width="200px"/>

Panaretos writes well, the level is suitable to undergraduate students (last I know it was used as such) and it really is a book on statistics made for mathematicians. So it is written in the usual theorem-proof style, and I find that refreshing when dealing with statistics. Another good book is this:

**[Mathematical Statistics](https://www.amazon.com/Mathematical-Statistics-Asymptotic-Graduate-Mathematics/dp/0821852833/)**, *Alexander Korostelev, Olga Korostelev*

<img src="/learn-mathematics/img/korostelev.jpg" alt="Korostelev" width="200px"/>

This goes much, much deeper than the first book and is suitable for a graduate course on the subject. I like the fact the chapters are short and sweet. Needless to say, it is a lot harder than the first textbook. If you are interested in statistical learning, it's hard to beat this:

**[The Elements of Statistical Learning](https://www.amazon.com/Elements-Statistical-Learning-Prediction-Statistics/dp/0387848576/)**, *Trevor Hastie, et al*

<img src="/learn-mathematics/img/hastie.jpg" alt="Hastie" width="200px"/>

The book is a classic for a reason. It is well written and suitable to graduate students. If you need something a bit more accessible, try the easier version:

**[An Introduction to Statistical Learning](https://www.amazon.com/Introduction-Statistical-Learning-Applications-Statistics/dp/1071614177/)**, *Gareth James, et al*

<img src="/learn-mathematics/img/james.jpg" alt="James" width="200px"/>

It is written by the same authors roughly and takes things a step slower, which may or may not be great for you. Try both and see.

### Game Theory

Game Theory is interesting because rarely has a mathematical discipline had so many books written about it by non-mathematicians, or mathematicians with an audience of non-mathematicians. I think it's because it's so applicable to a variety of fields, including war tactics and economics. In this section, I'll try to focus on the mathematical aspects. The first is written by one of my favorite author:

**[On Numbers and Games](https://www.amazon.com/Numbers-Games-John-H-Conway/dp/1568811276/)**, *John H. Conway*

<img src="/learn-mathematics/img/conway.jpg" alt="Conway" width="200px"/>

Conway writes beautifully, both in his papers (I read one called division by 3, can you believe it?) and in his books. This book delves on the connection between, well, numbers and games. It's a great first book on the subject. Here are two more references for two different parts of the theory:

**[Combinatorial Game Theory](https://www.amazon.com/Combinatorial-Theory-Graduate-Studies-Mathematics/dp/082185190X/)**, *Aaron N. Siegel*

<img src="/learn-mathematics/img/siegel.jpg" alt="Siegel" width="200px"/>

The standard textbook for a graduate class on the subject. I haven't read much about it but it looks good. Then there is:

**[Differential Games](https://www.amazon.com/Differential-Games-Mathematical-Applications-Optimization/dp/0486406822/)**, *Rufus Isaacs*

<img src="/learn-mathematics/img/isaacs.jpg" alt="Isaacs" width="200px"/>

This one specializes on differential games in particular, meaning games that have a variable whose state over time is governed by a differential equation. It is a fascinating theory and this is a great introduction.

#### Numerical Analysis

Numerical analysis is crucial when a direct, analytic solution is not easily found. This includes computational versions of a mathematical subject (see the commutative algebra and algebraic geometry sections for examples) or more generally numerical methods (such as with PDEs). I do not know a whole lot about the subject, I only took a senior undergraduate class on it. We used this textbook:

**[Scientific Computing with MATLAB and Octave](https://www.amazon.com/Scientific-Computing-Computational-Science-Engineering/dp/364245366X/)**, *Alfio Quarteroni, et al*

<img src="/learn-mathematics/img/quarteroni.jpg" alt="Quarteroni" width="200px"/>

Quite frankly, I really liked it. I thought I would hate numerical analysis and this textbook made it bearable. I don't know much about other books, I have seen this one:

**[Theoretical Numerical Analysis](https://www.amazon.com/Theoretical-Numerical-Analysis-Functional-Mathematics-ebook/dp/B00HWV1RFW/)**, *Kendall Atkinson*

<img src="/learn-mathematics/img/atkinson.jpg" alt="Atkinson" width="200px"/>

Apparently it uses functional analysis, but I'm not sure what they mean by this. Read, find out and let me know! Of course, it would be a shame not to mention a book on partial differential equations and numerical methods:

**[Finite Difference Methods for Ordinary and Partial Differential Equations](https://www.amazon.com/Difference-Methods-Ordinary-Differential-Equations/dp/0898716292/)**, *Randall J. LeVeque*

<img src="/learn-mathematics/img/leveque.jpg" alt="LeVeque" width="200px"/>

This seems to be a standard reference on the theory, but I haven't read it so I cannot say much.

### Mathematics History

Mathematics has a rich history, and there are many books written on the subject. My favorite author is Jeremy Gray, and he has written a variety of books:

**[The Real and the Complex](https://www.amazon.com/Real-Complex-Analysis-Undergraduate-Mathematics/dp/3319237144/)**, *Jeremy Gray*

<img src="/learn-mathematics/img/gray-real.jpg" alt="" width="200px"/>

This one is my favorite, it discusses analysis in the 19th century, a beautiful story.

**[Worlds Out of Nothing](https://www.amazon.com/Worlds-Out-Nothing-Undergraduate-Mathematics/dp/0857290592/)**, *Jeremy Gray*

<img src="/learn-mathematics/img/gray-worlds.jpg" alt="" width="200px"/>

This one focuses on geometry, and its development is absolutely fascinating.

**[A History of Abstract Algebra](https://www.amazon.com/History-Abstract-Algebra-Undergraduate-Mathematics/dp/3319947729/)**, *Jeremy Gray*

<img src="/learn-mathematics/img/gray-algebra.jpg" alt="" width="200px"/>

A history of algebra as the title says. It's interesting to see the difference between the way the ideas were born and how they are taught in modern algebra textbooks, for instance by having groups and rings before fields.

**[Change and Variations](https://www.amazon.com/Change-Variations-Differential-Undergraduate-Mathematics/dp/3030705749/)**, *Jeremy Gray*

<img src="/learn-mathematics/img/gray-variations.jpg" alt="" width="200px"/>

This discusses differential equations and calculus of variations, a subject I do not know enough to comment on, but it's great stuff. Calculus of variations in particular is useful in physics. Okay, here's a more general textbook:

**[Mathematics and Its History](https://www.amazon.com/Mathematics-Its-History-Undergraduate-Texts/dp/144196052X/)**, *John Stillwell*

<img src="/learn-mathematics/img/stillwell-math.jpg" alt="Stillwell Math" width="200px"/>

I like Stillwell. He writes nicely and this is no different. Great textbook and would be perfect for an undergraduate math history course. Finally, here's another one I like:

**[Number Theory and Its History](https://www.amazon.com/Number-Theory-History-Dover-Mathematics-ebook/dp/B00A73FH1W/)**, *Oysten Ore*

<img src="/learn-mathematics/img/ore.jpg" alt="Ore" width="200px"/>

This discusses number theory specifically, and it's good side reading if you're studying number theory at the same time, to see where the idea came from. For instance, did you know that the name ideal from algebra comes from looking for idealized numbers that would act like primes in certain number fields? Dedekind was ahead of his time, that's for sure.

## Applications

In this section, we look at some applications from mathematics. These books are either mathematical textbooks on the subject they are covering or books targeted at mathematics majors.

### Physics

We finally come to my favorite science: physics. I find physics super cool and the applications to and from mathematics abound.

#### Classical Mechanics

Classical (especially celestial) mechanics is the genesis behind symplectic geometry and in some ways, calculus of variations. There is only one book I recommend, but what a book! Of course, it's Arnol'd:

**[Mathematical Methods of Classical Mechanics](https://www.amazon.com/Mathematical-Classical-Mechanics-Graduate-Mathematics/dp/0387968903/)**, *Vladimir I. Arnol'd*

<img src="/learn-mathematics/img/arnold-cm.jpg" alt="Arnol'd CM" width="200px"/>

This book is not easy. It's about classical mechanics, but it will end up doing symplectic geometry! Still, it's great, and it's written by one of the greats. I think everyone should read it, honestly.

#### Quantum Mechanics

Ah, quantum mechanics. Everyone knows about it nowadays, or at least, they think they do. Regardless, it's a fascinating subject and I loved taking a class on it in university. It was a class for math majors so functional analysis was required. Here are the books I used for it:

**[Quantum Theory, Groups and Representations](https://www.amazon.com/Quantum-Theory-Groups-Representations-Introduction/dp/3319646109/)**, *Peter Woit*

<img src="/learn-mathematics/img/woit.jpg" alt="Woit" width="200px"/>

Perhaps my favorite of the three. Woit writes very well and this book has a sort of majestic feel to it (to me at least). I like the presentation and the level is just right. I found Hall slightly easier though:

**[Quantum Theory for Mathematicians](https://www.amazon.com/Quantum-Theory-Mathematicians-Graduate-Mathematics/dp/146147115X/)**, *Brian C. Hall*

<img src="/learn-mathematics/img/hall-qm.jpg" alt="Hall QM" width="200px"/>

This was the book for the course. Hall wrote a great book on Lie theory and while I like this one, I find it slightly worse. Nothing much though, it's still good stuff. Finally, there's:

**[Quantum Mechanics for Mathematicians](https://www.amazon.com/Quantum-Mechanics-Mathematicians-Graduate-Mathematics/dp/0821846302/)**, *Leon A. Takhtajan*

<img src="/learn-mathematics/img/takhtajan.jpg" alt="Takhtajan" width="200px"/>

It was a bit hard for me to follow as I didn't have the required prerequisites, but what I did get from it, I liked.

#### Relativity

Relativity is a fascinating topic, and I personally find it much weirder than quantum mechanics. It is also exceptionally well suited to mathematics. There are even undergraduate level books discussing it. My favorite is:

**[The Geometry of Spacetime](https://www.amazon.com/Geometry-Spacetime-Introduction-Undergraduate-Mathematics/dp/0387986413/)**, *James J. Callahan*

<img src="/learn-mathematics/img/callahan.jpg" alt="Callahan" width="200px"/>

It is very approachable. I loved the discussion of Minkowski space on it. The high number of diagrams and drawings is a high point. It mostly focuses on special relativity, but there is a discussion of general relativity at the end. Another great book is:

**[Special Relativity](https://www.amazon.com/Special-Relativity-Springer-Undergraduate-Mathematics/dp/1852334266/)**, *N.M.J. Woodhouse*

<img src="/learn-mathematics/img/woodhouse-sr.jpg" alt="WoodHouse SR" width="200px"/>

This is the first out of two books discussing relativity, the second being:

**[General Relativity](https://www.amazon.com/General-Relativity-Springer-Undergraduate-Mathematics/dp/1846284864/)**, *N.M.J. Woodhouse*

<img src="/learn-mathematics/img/woodhouse-gr.jpg" alt="Woodhouse GR" width="200px"/>

These books are clear and I feel like they give a really good introduction to relativity as a whole. If you want something a bit more involved, read this:

**[General Relativity for Mathematicians](https://www.amazon.com/General-Relativity-Mathematicians-Graduate-Mathematics/dp/038790218X/)**, *R. K. Sachs, H. Wu*

<img src="/learn-mathematics/img/sachs.jpg" alt="Sachs" width="200px"/>

This is a standard reference for a graduate-level course on general relativity. It is surprisingly short. I like that they included a chapter on cosmology.

#### Gauge Theory

Gauge theory is an important concept in physics, roughly describing physical systems whose Lagrangian is invariant under certain (local) transformations. This is particularly important for particle physics in particular, such as the Standard Model. The book I used to learn about the topic is:

**[Mathematical Gauge Theory](https://www.amazon.com/Mathematical-Gauge-Theory-Applications-Universitext/dp/3319684388/)**, *Mark J.D. Hamilton*

<img src="/learn-mathematics/img/hamilton.jpg" alt="Hamilton" width="200px"/>

Hamilton writes very well and this is one of my favorite books. It has a complete discussion of Lie groups and algebras as well as their representations, but I think you can find a slightly better exposition of the theory elsewhere. The real gold is in the physics portion in my opinion. There is also this very interesting book:

**[Gauge Fields, Knots and Gravity](https://www.amazon.com/GAUGE-FIELDS-KNOTS-GRAVITY-Everything/dp/9810220340/)**, *John Baez, Javier P. Muniain*

<img src="/learn-mathematics/img/baez.jpg" alt="Baez" width="200px"/>

Baez is an interesting figure in the mathematical physics community (as well as a relative to Joan Baez, funny!). This book is pretty ambitious and seeks to show links between, well, gauge fields, knots and quantum gravity. I think you will get more out of the book if you know physics decently well already, but it's worth it. Finally, I could never make a list of mathematics textbook and not mention this:

**[Geometry, Topology and Physics](https://www.amazon.com/Geometry-Topology-Physics-Graduate-Student/dp/0750306068/)**, *Mikio Nakahara*

<img src="/learn-mathematics/img/nakahara.jpg" alt="Nakahara" width="200px"/>

I am not sure how to classify this amazing book, as most of it is actually about differential geometry, but it is written with researchers in (mathematical) physics in mind, and it does have an important chapter on gauge theories. Regardless, if you are interested in theoretical physics, please read it.

#### Quantum Field Theory

Quantum field theory (usually called QFT) is what happens when you try to quantize fields (such as the electromagnetic field). Unlike quantum mechanics, the mathematics of quantum field theory are... complicated. And also not always defined properly. What does it mean to take an integral over all possible paths? What is the measure? I'm not sure. Either way, it's very interesting. I learned of the theory by reading a cute little book:

**[Frobenius Algebras and 2D Topological Quantum Field Theory](https://www.amazon.com/Frobenius-Algebras-Topological-Theories-Mathematical-ebook/dp/B000SMDWFA/)**, *Joachim Kock*

<img src="/learn-mathematics/img/kock.jpg" alt="Kock" width="200px"/>

Honestly, one could barely call this book a quantum field theory book. It is mostly a book about algebra, topology and category theory. Regardless, it has quantum field theory in the name so it counts (ah!). Either way, I loved reading it and I thought it was great. Not really what quantum field theory is about though. Here's a better read for that:

**[Quantum Fields and Strings](https://www.amazon.com/Quantum-Fields-Strings-Course-Mathematicians/dp/0821820141/)**, *Pierre Deligne, et al*

<img src="/learn-mathematics/img/deligne.gif" alt="Deligne" width="200px"/>

These lecture notes grew out of a course given by Deligne, Witten and other math geniuses at the IAS. It is not easy, and it assumes you're already a mathematician trying to understand what QFT is about. It's a reference though. Instead, I would rather use this:

**[Quantum Field Theory](https://www.amazon.com/Quantum-Field-Theory-Mathematicians-Mathematical/dp/1470464837/)**, *Gerald B. Folland*

<img src="/learn-mathematics/img/folland.jpg" alt="Folland" width="200px"/>

This is a gentler introduction to the subject though it still assumes a lot of prerequisites. Folland does his best to discuss the parts of the theory that are relevant to mathematicians, or at least somewhat mathematically rigorous. There is also this series:

**[Quantum Field Theory I-III](https://www.amazon.com/Quantum-Field-Theory-Mathematics-Mathematicians/dp/3540347623/)**, *Eberhard Zeidler*

<img src="/learn-mathematics/img/zeidler.jpg" alt="Zeidler" width="200px"/>

I have not read all of this, obviously, as it is a mountain of work, but it's good to know there's a series of multiple books dedicated to quantum field theory for mathematicians. What I read from the first book, I really liked. Finally, there is this new book that came out recently:

**[What Is a Quantum Field Theory?](https://www.amazon.com/What-Quantum-Field-Theory-Mathematicians/dp/1316510271/)**, *Michel Talagrand*

<img src="/learn-mathematics/img/talagrand.jpg" alt="Talagrand" width="200px"/>

I haven't had the chance to read it yet, but I heard it was great. I will take a look and report back.

### Computer Science

Computer science is arguably [not a science, and it is not about computers](https://youtu.be/-J_xL4IGhJA?si=jq8MO80Uw93Gb4MW&t=27). To me, computer science is a subfield of mathematics, and it was most definitely founded by mathematicians. Still, in modern times we tend to see both as separate entities and academic fields. As such, I have decided to separate them here.

#### Cryptography

Cryptography is one of my favorite subjects in mathematics. There are many great books on it, my favorite is this one, written by a master:

**[Cryptography Made Simple](https://www.amazon.com/Cryptography-Made-Simple-Information-Security/dp/3319219359/)**, *Nigel P. Smart*

<img src="/learn-mathematics/img/smart.jpg" alt="Smart" width="200px"/>

Smart is very well known in the community. I knew he was great at cryptography before reading the book, but it seems he's also a great writer. The book is clear, precise, with ample examples. It's the best. There is also this, which is perfect for undergraduate students:

**[An Introduction to Mathematical Cryptography](https://www.amazon.com/Introduction-Mathematical-Cryptography-Undergraduate-Mathematics/dp/1493917102/)**, *Jeffry Hoffstein, et al*

<img src="/learn-mathematics/img/hoffstein.jpg" alt="Hoffstein" width="200px"/>

Personally, I found it a bit (too) easy, but it was still really good. Of course, I cannot help but recommend:

**[Post-Quantum Cryptography](https://www.amazon.com/Post-Quantum-Cryptography-Daniel-J-Bernstein/dp/3540887016/)**, *Daniel J. Bernstein, et al*

<img src="/learn-mathematics/img/bernstein.jpg" alt="Bernstein" width="200px"/>

This discusses various post-quantum cryptosystems, although it is now slightly outdated since the NIST chose the winner of the post-quantum cryptography competition. Also, Rainbow was broken in two swift strikes since this book was written. Still, it's a good start to post-quantum cryptography.

#### Information and Coding Theory

Coding Theory and Information Theory more generally is an interesting subject with a unique flavor. The kind I know of uses a lot of algebra, mostly ring theory. I learned the subject from this book:

**[Introduction to Coding Theory](https://www.amazon.com/Introduction-Coding-Theory-Graduate-Mathematics/dp/3540641335/)**, *J.H. van Lint*

<img src="/learn-mathematics/img/lint.jpg" alt="Lint" width="200px"/>

It's a great book, with good exercises and well laid out examples. It's perfect if you want an introduction to the subject as a whole, but I find it a bit old. For more modern coverage, I would use this:

**[A Course in Algebraic Error-Correcting Codes](https://www.amazon.com/Algebraic-Error-Correcting-Compact-Textbooks-Mathematics-ebook/dp/B088CQWQ3R/)**, *Simeon Ball*

<img src="/learn-mathematics/img/ball.jpg" alt="Ball" width="200px"/>

I love this book. It is more recent than Lint so it has a lot of interesting topics (*p*-adic codes!). In general, I love the compact textbook series so do give it a try. Finally, there is the paper (turned into a book) that started it all, by the father of information theory himself, Shannon:

**[The Mathematical Theory of Communication](https://www.amazon.com/Mathematical-Theory-Communication-Claude-Shannon/dp/0252725484/)**, *Claude E. Shannon, Warren Weaver*

<img src="/learn-mathematics/img/shannon.jpg" alt="Shannon" width="200px"/>

Every computer science student should read this. Every mathematician interested in information theory should read this. You should read this.

#### Type Theory

Type theory discusses, well, types as in type systems you can encounter in programming languages. It became pretty hot recently due to homotopy type theory being considered as an alternative for [mathematical foundations](https://en.wikipedia.org/wiki/Foundations_of_mathematics). If you want an introduction to the subject in general, the only book I am familiar with is:

**[Type Theory and Formal Proof](https://www.amazon.com/Type-Theory-Formal-Proof-Introduction/dp/110703650X/)**, *Rob Nederpelt*

<img src="/learn-mathematics/img/nederpelt.jpg" alt="Nederpelt" width="200px"/>

Great book, praised in the computer science community for a reason. I think it's decently approachable. If you wanna know about homotopy type theory (HoTT) specifically, I recommend the HoTT book directly:

**[Homotopy Type Theory](https://homotopytypetheory.org/book/)**, *Univalent Foundations of Mathematics*

<img src="/learn-mathematics/img/hott.webp" alt="HoTT" width="200px"/>

I haven't read the book, I just know it because everyone talks about HoTT currently. That's the book to read if you want to know what all the fuss is about.

#### Signal Processing

I love audio engineering. It's super fun and creative. Signal Processing is the theory that underpins it. I do not know too much about it, only two books which I have most definitely not read in full. First is:

**[Digital Audio Processing Fundamentals](https://www.amazon.com/Digital-Processing-Fundamentals-Springer-Topics-ebook/dp/B0BSKVH1VF/)**, *Aurelio Uncini*

<img src="/learn-mathematics/img/uncini.jpg" alt="Uncini" width="200px"/>

I like this book. It's approachable yet very detailed. The chapter on physical modeling in particular is really cool. It is pretty hefty though, with a total of around 700 pages. Sadly, this seems to be common in the field as the next one is 600 pages:

**[Analog and Digital Signal Analysis](https://www.amazon.com/Analog-Digital-Signal-Analysis-Applications-ebook/dp/B01L3EW1W6/)**, *Frédéric Cohen Tenoudji*

<img src="/learn-mathematics/img/tenoudji.jpg" alt="Tenoudji" width="200px"/>

This one goes even deeper with wavelets and random signals, including filtering by a random signal. Again, it is very in-depth and very long, but if you're interested in signal processing, it's wonderful.

### Finance

Finance has a lot of mathematics going on, mostly stochastics. I have taken a few finance classes and portfolio optimization is definitely mathematical in nature. There are two main textbooks I have learned from. The first one is this:

**[Mathematics for Finance](https://www.amazon.com/Mathematics-Finance-Introduction-Engineering-Undergraduate/dp/0857290819/)**, *Marek Capiński, Tomasz Zastawniak*

<img src="/learn-mathematics/img/capinski-fin.jpg" alt="Capiński Finance" width="200px"/>

Written by Capiński (the same author that wrote Measure, Integral, Probability), this is a good introduction to methods in mathematical finance. The book is very approachable, even undergraduates can read it. If you want something with more depth, I suggest the two books by Shreve:

**[Stochastic Calculus for Finance I-II](https://www.amazon.com/Stochastic-Calculus-Finance-Binomial-Springer/dp/0387249680/)**, *Steven E. Shreve*

<img src="/learn-mathematics/img/shreve.jpg" alt="Shreve" width="200px"/>

These two volumes give a detailed exposition of mathematical finance, with plenty of exercises. If you want to go even further, you can read this:

**[Methods of Mathematical Finance](https://www.amazon.com/Methods-Mathematical-Probability-Stochastic-Modelling/dp/1493968149/)**, *Ioannis Karatzas, Steven Shreve*

<img src="/learn-mathematics/img/karatzas-shreve.jpg" alt="Karatzas-Shreve" width="200px"/>

Also written by Shreve. I didn't read it myself, but I have skimmed it and it looks great. Finally, there is this focusing on hedging specifically:

**[Fundamentals and Advanced Techniques in Derivatives Hedging](https://www.amazon.com/Fundamentals-Advanced-Techniques-Derivatives-Universitext-ebook/dp/B01HQ6DNOU/)**, *Bruno Bouchard, Jean-François Chassagneux*

<img src="/learn-mathematics/img/bouchard.jpg" alt="Bouchard" width="200px"/>

I have not had the chance to read it yet, but I will, hopefully.

### Biology

Mathematical biology is a really cool field. I have taken a graduate class on dynamical systems that discussed among other things applications to ecology and it was wonderful. Here's a recommendation:

**[Mathematical Biology](https://www.amazon.com/Mathematical-Biology-Introduction-Undergraduate-Mathematics/dp/1489982817/)**, *Ronald W. Shonkwiler, James Herod*

<img src="/learn-mathematics/img/shonkwiler.jpg" alt="Shonkwiler" width="200px"/>

This book is pretty big. Personally, I would choose one topic you're interested in and start there. You should probably start with the chapter called "Some Mathematical Tools" though. There is also this from an author I like:

**[Mathematical Methods in Biology and Neurobiology](https://www.amazon.com/Mathematical-Methods-Biology-Neurobiology-Universitext/dp/1447163524/)**, *Jürgen Jost*

<img src="/learn-mathematics/img/jost.jpg" alt="Jost" width="200px"/>

I really like the chapter on pattern formation. The chapter on discrete structures is great as well. This book is pretty short which might be better for a first book on the subject. Finally, there is this interesting book:

**[Mathematical Models in Population Biology and Epidemiology](https://www.amazon.com/Mathematical-Population-Biology-Epidemiology-Mathematics/dp/146141685X/)**, *Fred Brauer, Carlos Castillo-Chavez*

<img src="/learn-mathematics/img/brauer.jpg" alt="Brauer" width="200px"/>

Again, a pretty hefty book at around 500 pages, but it has chapters on epidemic models, which I find very interesting personally. It starts with single-species models and then builds from there to model interacting species. Give it a try!

### Chemistry

Chemistry doesn't have too many textbooks that I know using mathematics, they are almost all about group theory in chemistry, where finite groups are used to describe symmetries of orbitals. Here is one example of such a book:

**[Group Theory in Chemistry](https://www.amazon.com/Group-Theory-Chemistry-Dover-Books/dp/0486673553/)**, *David M. Bishop*

<img src="/learn-mathematics/img/bishop.jpg" alt="Bishop" width="200px"/>

There are a myriad of them out there, this is the only one I have looked through. If you don't like it, odds are there's another one you will like better with the exact same name (or very close). There is one book I actually read and liked though, it's this one:

**[Linearity, Symmetry, and Prediction in the Hydrogen Atom](https://www.amazon.com/Linearity-Symmetry-Prediction-Undergraduate-Mathematics/dp/0387246371/)**, *Stephanie Frank Singer*

<img src="/learn-mathematics/img/singer.jpg" alt="Singer" width="200px"/>

Singer introduces everything she will need to present the symmetry group of the hydrogen atom directly in the book. It is pretty cool and I think it would be a great undergraduate research topic.

# Part III: Possible tracks

In this last part, I would like to describe a few possible tracks someone could take through the many, many topics discussed above. After all, there are many different possible choices and it can lead to decision paralysis. Of course, you are free to create your own, just make sure you have all the prerequisites to the courses you are interested in doing. Usually, I would be studying two topics at the same time, but you are free to do something different.

First of all, there is a core track that I will assume you have done before moving on. The books listed here can be changed for other books in the same category, it is just the list I would personally follow to learn these subjects, assuming I don't already know them. Here is what the core sequence consists of:

**Core Sequence**:

1. Precalculus Mathematics in a Nutshell
2. APEX Calculus
3. Book of Proof
4. Linear Algebra Done Wrong
5. Understanding Analysis
6. Discrete Mathematics and Its Applications
7. Elementary Number Theory
8. Differential Equations with Applications and Historical Notes
9. Differential Geometry of Curves and Surfaces (Tapp)
10. Abstract Algebra: Theory and Applications
11. Introduction to Topology (ch.1 on Metric Spaces)
12. Topoology (ch.1-7) 

This is what I will call the core sequence and you are assumed to have taken all of these. The tracks below builds from there into graduate-level topics.

## Generalist track

Assuming you have no particular interest in any specific subfield of mathematics (or like me, you have an interest in all of them!), this is what I would recommend.

1. Fourier Analysis
2. Commutative Algebra
3. Complex Analysis
4. Smooth Manifolds
5. Measure Theory
6. Algebraic Topology
7. Functional Analysis
8. Classical Algebraic Geometry
9. Lie Groups
10. Algebraic Number Theory

For the Lie groups course, I would do Hall because it covers both Lie groups and Lie algebras.

## Analyst track

This is the track for die-hard analysis fans.

1. Fourier Analysis
2. Complex Analysis
3. Measure Theory
4. Functional Analysis
5. Dynamical Systems
6. Harmonic Analysis
7. Partial Differential Equations
8. Probability and Stochastics
9. Analytic Number Theory
10. Modular Forms

For the last two subjects, I would read both books by Apostol personally, but you are free to do things differently.

## Algebraist track

This is the track for people mostly interested in algebra.

1. Graduate Algebra (w/ Galois Theory)
2. Category Theory
3. Commutative Algebra
4. Homological Algebra
5. Representation Theory
6. Algebraic Topology
7. Elliptic Curves
8. Algebraic Number Theory
9. Classical Algebraic Geometry
10. Modern Algebraic Geometry

## Geometer track

This track focuses on everything geometry.

1. Smooth Manifolds
2. Riemannian Geometry
3. Algebraic Topology
4. Partial Differential Equations
5. Lie Groups
6. Dynamical Systems
7. Symplectic and Contact Geometry
8. Classical Mechanics
9. Relativity
10. Geometry, Topology and Physics

The last recommendation is literally the book named like this. For Algebraic Topology, I would study it with Bott & Tu's book.

## Algebraic Geometer track

This track is for people interested in becoming algebraic geometers:

1. Category Theory
2. Commutative Algebra
3. Algebraic Topology
4. Classical Algebraic Geometry
5. Homological Algebra
6. Representation Theory
7. Modern Algebraic Geometry
8. Étale Cohomology
9. Algebraic Groups
10. Arithmetic Geometry

## Number Theorist track

This track focuses on number theory:

1. Complex Analysis
2. Analytic Number Theory
3. Commutative Algebra
4. Elliptic Curves
5. Algebraic Number Theory
6. *p*-adic Methods
7. Modular Forms
8. Classical Algebraic Geometry
9. Modern Algebraic Geometry
10. Arithmetic Geometry

You could also swap out the algebraic geometry spots with something else.

## Physicist track

This track emphasizes physics:

1. Smooth Manifolds
2. Riemannian Geometry
3. Complex Analysis
4. Functional Analysis
5. Lie Groups
6. Classical Mechanics
7. Quantum Mechanics
8. Relativity
9. Gauge Theory
10. Quantum Field Theory

For Functional Analysis, try Kreyszig.

## Computer scientist track

This track discusses courses that might be useful to a computer scientist:

1. Graph Theory
2. Fourier Analysis
3. Category Theory
4. Numerical Analysis
5. Cryptography
6. Post-Quantum Cryptography
7. Coding Theory
8. Type Theory
9. Statistics
10. Game Theory

If you're doing this track, read Concrete Mathematics instead of Rosen in the core sequence.

## Finance track

A track that might be interesting if you want to go into financial mathematics.

1. Measure Theory and Integration
2. Dynamical Systems
3. Partial Differential Equations
4. Probability and Stochastics
5. Stochastic Calculus for Finance I
6. Stochastic Calculus for Finance II
7. Methods of Mathematical Finance
8. Statistics
9. Game Theory
10. Numerical Analysis

You could take out the last three for something else that interests you.
