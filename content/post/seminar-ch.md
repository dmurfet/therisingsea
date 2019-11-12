+++
date = "2018-03-19T00:42:06+00:00"
title = "Seminar"
menu = "main"

+++


The seminar is held in the **Russell Love theatre** of Peter Hall on Fridays 1-2pm (note the room change). For announcements of talks [subscribe](http://www.tinyletter.com/dmurfet) to the mailing list. The videos from the talks are available on [YouTube](https://www.youtube.com/channel/UCJTk6uSbSsclXN8v3b27_QQ/videos?flow=list&live_view=500&view=0&sort=dd). For previous semesters of the seminar, scroll down! 

#### Current seminar

In semester two of 2019 we are going to study reasoning in the context of **deep reinforcement learning** with an aim to understand AlphaGo and related breakthroughs, such as AlphaStar. Along the way we will look at deep learning more generally. Some relevant background information:

* [Deep learning in Australia](https://gist.github.com/dmurfet/072e8503368acdccf32b641f1e800e99) a very rough list of researchers in this area.

* [An introduction to deep reinforcement learning](https://arxiv.org/pdf/1811.12560.pdf).

* [AlphaGo documentary](https://www.imdb.com/title/tt6700846/) on NetFlix.

* [AlphaStar blog post](https://deepmind.com/blog/alphastar-mastering-real-time-strategy-game-starcraft-ii/)

There are three main components of AlphaGo: *Monte-Carlo tree search*, *deep learning* and *reinforcement learning*, and we will have talks on all three aspects. One important running theme will be the dichotomy between problems with small and large state spaces, and the corresponding need for function approximation (the successful incorporation of which is what makes AlphaGo scientifically interesting).

Talk schedule:

  * Lecture 0: Geoff Hinton [video](https://www.youtube.com/watch?v=izrG86jycck) "Deep learning" ([brief notes by DM](http://therisingsea.org/notes/deeprl-seminar-talk1.pdf))
  * Lecture 1: Daniel Murfet "Introduction to reinforcement learning" ([notes](http://therisingsea.org/notes/deeprl-seminar-lecture1.pdf) | [video](https://youtu.be/cfLfpCJA9mE))
  * Lecture 2: James Clift "Turing and Intelligent Machinery" ([notes](http://therisingsea.org/notes/deeprl-seminar-lecture2.pdf) | [video](https://youtu.be/iYdoW4ZLes4) | [Turing's paper](https://weightagnostic.github.io/papers/turing1948.pdf))
  * Lecture 3: Thomas Quella "Hopfield networks and statistical mechanics" ([notes](http://therisingsea.org/notes/deeprl-seminar-lecture3.pdf) | [video](https://youtu.be/Vv9dmlFZcfo))
  * Lecture 4: Will Troiani "Universal approximation by feedforward networks" ([notes](http://therisingsea.org/notes/deeprl-seminar-lecture4.pdf) | [paper](https://arxiv.org/pdf/1710.11278.pdf))
  * Lecture 5: Susan Wei "Deep learning as a continuous dynamical system" ([video](https://youtu.be/ZFLJ7svnP5E) | [paper](http://www.jmlr.org/papers/volume18/17-653/17-653.pdf))
  * Lecture 6: Mingming Gong "Convolutional neural networks"
  * Lecture 7: Daniel Murfet "AlphaGo" ([notes](http://therisingsea.org/notes/talk-alphago.pdf) | [video](https://youtu.be/rOiaZ1hVb-A) )
  * Lecture 8: Elliot Catt "Solomonoff induction and the limits of RL"
    
There is a bonus talk:

  * Rohan Mitta "Introduction to Formal Proof Verification in Lean" 13-9-19

Remarks

  * There is an interesting historical connection between talks 2 and 3. In his article "[Now what](https://pni.princeton.edu/john-hopfield/john-j.-hopfield-now-what)" Hopfield recalls working for a year on random networks before inventing his associative memory networks (Hopfield clarified in an email that he rejected Turing's approach because of the globally synchronised clock that it requires).
  * On the topic of formal proofs, see Kevin Buzzard's recent talk "[The future of mathematics?](https://www.youtube.com/watch?v=Dp-mQ3HxgDE)".
  * [Silver on classic games](https://www.youtube.com/watch?v=ld28AU7DDB4) 1:43:40 "If there's one thing to take away from this, it's that really doing things in the principled way - you have to believe in your principles and you have to believe that you can overcome all of this knowledge that it feels like you should be building into the system. But actually each time you put knowledge into a system you're really handicapping it, and if you really go back to the beginning and find the right principle to learn for itself it will do better eventually." (on this note see the [bitter lesson](http://www.incompleteideas.net/IncIdeas/BitterLesson.html))

Background on deep learning and reinforcement learning:

* I. Goodfellow, Y. Bengio, A. Courville "[Deep learning](https://www.deeplearningbook.org/)"
* R. S. Sutton and A. G. Barto "[Reinforcement learning](http://www.incompleteideas.net/book/the-book-2nd.html)" 2nd edition, 2018.
* C. F. Higham, D. J. Higham "[Deep learning: an introduction for applied mathematicians](https://arxiv.org/abs/1801.05894)"
* F. Chollet "Deep learning with Python" (practical)
* J. Clift, D. Doryn, D. Murfet, J. Wallbridge "[Logic and the 2-simplicial Transformer](https://arxiv.org/abs/1909.00668)"
* [Deep RL for theorem proving](https://www.youtube.com/watch?v=p_UXra-_ORQ&feature=youtu.be) an interview with Szegedy.

Interesting theory papers:

 * J. Lee, L. Xiao, S. S. Schoenholz, Y. Bahri, R. Novak, J. Sohl-Dickstein, J. Pennington, "[Wide neural networks of any depth evolve as linear models under gradient descent](https://arxiv.org/pdf/1902.06720.pdf)" 2019.

#### S1 2019 - Topological quantum computing

The aim of the seminar in semester one of 2019 was to understand **topological error correcting codes and how they enable universal quantum computers**. The primary organisers for this were *Thomas Quella* and *Charles Hill*. This is a remarkable application of topology to computation: one promising approach to making quantum computing work in practice is based on the homology and cohomology of surfaces. Moreover, some of [our neighbours](http://www.cqc2t.org/) are at the forefront of building quantum computers based on these ideas. An attractive feature of the subject is the sheer boldness of the underlying ideas, for example in Deutsch's paper on universal quantum computation he writes in a section titled "Programming physics":

> To view the Church-Turing hypothesis as a physical principle does not merely make computer science a branch of physics. It also makes part of experimental physics into a branch of computer science. The existence of a universal quantum computer Q implies that there exists a program for each physical process.

For an entree to quantum computing, see the following recent talks:

  * 2018 Australian of the Year Michelle Simmons "[The Einstein Lecture: The Quantum Computing Revolution](https://www.youtube.com/watch?v=FnPp73F5cnE)" (material on implementations of error correction from about 49:00).
  * Jason Alicea "[Topological Quantum Computing: Plenty of Room in the Middle](https://www.youtube.com/watch?v=qj-w6ISQL5Y)" 2018.

  * Lecture 1: James Clift "Universal Turing Machines" ([notes](http://therisingsea.org/notes/talk-james-utm.pdf))
  * Lecture 2: Will Troiani "Reversible Turing Machines" ([notes](http://therisingsea.org/notes/talk-will-reversible.pdf))
  * Lecture 3: Thomas Quella "Crash course in quantum mechanics" ([notes](http://therisingsea.org/notes/talk-thomas-quantum.pdf))
  * Lecture 4: Isaac David Smith "Feynman's quantum circuits" ([notes](http://therisingsea.org/notes/talk-isaac-quantumcircuits.pdf))
  * Lecture 5: Isaac David Smith "Deutsch's universal quantum computer (Part 1)"
  * Lecture 6: Sam Tonetto and Gary Mooney "On the complexity of Ising spin glass models"
  * Lecture 7: Stephane Dartois "Deutsch's universal quantum computer (Part 2)"
  * Lecture 8: Charles Hill "Applications of quantum computers 1: Algorithms"
  * Lecture 9: Charles Hill "Applications of quantum computers 2: Quantum annealers"
  * Lecture 10: Thomas Quella "Physical realisations of quantum computers"
  * Lecture 11: James Clift "Classical error correcting codes" ([notes](http://therisingsea.org/notes/talk-james-ecc.pdf))
  * Lecture 12: Will Troiani "Crash course in homology and cohomology" ([notes](http://therisingsea.org/notes/talk-will-homology.pdf))
  * Lecture 13: Isaac David Smith "Quantum error correcting codes" ([notes](http://therisingsea.org/notes/talk-isaac-1.pdf) | [video](https://youtu.be/Hs4q4FtuuNw))
  * Lecture 14: Isaac David Smith "Stabiliser formalism and the toric code" ([notes](http://therisingsea.org/notes/talk-isaac-2.pdf) | [video](https://youtu.be/TwlUgop_Qe4))
  * Lecture 15: Thomas Quella "Matrix product states and tensor networks" ([notes](http://therisingsea.org/notes/talk-thomas-mps.pdf) | [video](https://youtu.be/Bvs6ijMA3qM))
  * Lecture 16: Charles Hill "Open problems for mathematicians"

Primary references:

  * [AB] S. Arora, B. Barak "Computational complexity" 2009
  * [B] C. H. Bennett "[Logical reversibility of computation](https://www.math.ucsd.edu/~sbuss/CourseWeb/Math268_2013W/Bennett_Reversibiity.pdf)" 1973
  * [F] R. Feynman "[Lectures on Computation](https://www.amazon.com/Feynman-Lectures-Computation-Frontiers-Physics/dp/0738202967)" 1996.
  * [D] D. Deutsch, "[Quantum theory, the Church-Turing principle and the quantum computer](https://people.eecs.berkeley.edu/~christos/classics/Deutsch_quantum_theory.pdf)” 1985.
  * [DKLP] E. Dennis, A. Kitaev, A. Landahl, J. Preskill "[Topological quantum memory](https://arxiv.org/abs/quant-ph/0110143v1)" 2001
  * [K] A. Kitaev “[Fault-tolerant quantum computation by anyons](https://arxiv.org/abs/quant-ph/9707021)” 2003.
  * [C] C. Hill, E. Peretez, S. J. Hile, M. G. House, M. Fuechsle, S. Rogge, M. Y. Simmons and L. C. L. Hollenberg “[A surface code quantum computer in silicon](http://advances.sciencemag.org/content/1/9/e1500707)” 2015
  * [NC] M. Nielsen, I. Chuang "Quantum computation and quantum information" 2010.

Explanation of the talk schedule: the aim by the end of the semester is to understand what a universal quantum computer is [D] and how the surface code introduced in [DKLP] and elaborated in [C] solves the main problem that one faces in actually physically realising such a computer, namely, quantum error correction. To understand what a universal quantum computer is, one has to first know what universal computation means (hence, Universal Turing Machines) and what reversible computation means, and to understand quantum error correction it is important to have seen classical error correction.

Other useful links:

  * D. Brown, "[Lectures on topological codes and quantum computation](https://sites.google.com/site/danbrowneucl/teaching/lectures-on-topological-codes-and-quantum-computation)"
  * National Academies of Sciences, Engineering, and Medicine "[Quantum Computing: Progress and Prospects](https://www.nap.edu/catalog/25196/quantum-computing-progress-and-prospects)" 2018.
  
#### S2 2018 - Topos theory and categorical logic

Our aim in the second semester of 2018 was to understand **how to use adjoint functors and topoi to organise mathematical knowledge**, following Mac Lane and Moerdijk's book "Sheaves in Geometry and Logic". For an explanation of this aim see the [seminar announcement](http://therisingsea.org/notes/seminar-2018-sem1.pdf) and the first lecture below. The seminar is supported by funding from [Data61](https://www.data61.csiro.au/), [DST group](https://www.dst.defence.gov.au/) and [ACEMS](https://acems.org.au/home) as part of a collaboration which aims to [develop new tools](http://therisingsea.org/notes/fmme.pdf) to aid human reasoning about mathematics and software.
  
Talk schedule:

  * Lecture 1: Daniel Murfet "An invitation to topos theory" ([notes](http://therisingsea.org/notes/ch2018-lecture1.pdf) | [video](https://vimeo.com/259518045))
  * Lecture 2: Daniel Murfet "The Curry-Howard correspondence (Part 1)" ([notes](http://therisingsea.org/notes/ch2018-lecture2.pdf) | [video](https://vimeo.com/260227984) | [more notes](http://therisingsea.org/notes/talk-ch.pdf) | [response](http://therisingsea.org/notes/samq.pdf) to Sam's question)
  * Lecture 3: Will Troiani "Monads and programs" ([notes](http://therisingsea.org/notes/ch2018-lecture3.pdf) | [video](https://vimeo.com/261278443))
  * Lecture 4: James Clift "The definition of a topos (Part 1)" ([notes](http://therisingsea.org/notes/ch2018-lecture4.pdf) | [video](https://vimeo.com/262515533))
  * Lecture 5: James Clift "The definition of a topos (Part 2)" ([notes](http://therisingsea.org/notes/ch2018-lecture4.pdf) | [video](https://vimeo.com/264398841))
  * Lecture 6: Patrick Elliott "Sheaves of sets (Part 1)" ([notes](http://therisingsea.org/notes/ch2018-lecture6.pdf) | [video](https://vimeo.com/268009512))
  * Lecture 7: Patrick Elliott "Sheaves of sets (Part 2)" ([notes](http://therisingsea.org/notes/ch2018-lecture7.pdf) | [video](https://vimeo.com/268205555))
  * Lecture 8: Will Troiani "Higher-order logic and topoi (Part 1)" ([notes](http://therisingsea.org/notes/ch2018-lecture8.pdf) | [video](https://vimeo.com/269326119))
  * Lecture 9: Daniel Murfet "Higher-order logic and topoi (Part 2)" ([notes](http://therisingsea.org/notes/ch2018-lecture9.pdf) | [video](https://vimeo.com/276873346))
  * Lecture 10: Patrick Elliott "Sheaves form a topos (Part 1)" ([notes](http://therisingsea.org/notes/ch2018-lecture10.pdf) | [video](https://vimeo.com/277558756))
  * Lecture 11: Patrick Elliott "Sheaves form a topos (Part 2)" ([notes](http://therisingsea.org/notes/ch2018-lecture11.pdf) | [video](https://vimeo.com/279269351))
  * Lecture 12: Daniel Murfet "Classifying topoi (Part 1)" ([notes](http://therisingsea.org/notes/ch2018-lecture12.pdf) | [video](https://vimeo.com/279740146))
  * Lecture 13: James Clift "Higher-order logic and topoi (Part 3)" ([notes](http://therisingsea.org/notes/ch2018-lecture13.pdf) | [video](https://vimeo.com/283164538))
  * Lecture 14: Will Troiani "The classifying space of rings" ([notes](http://therisingsea.org/notes/ch2018-lecture14.pdf))
  * Lecture 15: Daniel Murfet "Abstraction and adjunction" ([notes](http://therisingsea.org/notes/ch2018-lecture15.pdf) | [video1](https://youtu.be/AZduV9RDITM))
  
References:

  * Mac lane, Moerdijk "Sheaves in Geometry and Logic".
  * Lambek, Scott "Introduction to higher-order categorical logic"
  * Barr, Wells "Toposes, triples and theories" 
  * Sorensen, Urzyczyn "[Lectures on the Curry-Howard isomorphism](https://www.elsevier.com/books/lectures-on-the-curry-howard-isomorphism/sorensen/978-0-444-52077-7)".
  * Caramello's paper "[The unification of mathematics via topos theory](https://arxiv.org/abs/1006.3930)",
  * Cartier's paper "[A mad day's work: from Grothendieck to Connes and Kontsevich](http://www.ams.org/journals/bull/2001-38-04/S0273-0979-01-00913-2/home.html)",
  * [Higher topoi](https://ncatlab.org/nlab/show/%28infinity%2C1%29-topos) are important in homotopy type theory,
  * Connes' talk on "[The arithmetic site](https://www.youtube.com/watch?v=FaGXxXuRhBI)".
  
#### S2 2016 - Curry-Howard correspondence

Our aim was to read Sorensen and Urzyczyn's book "Lectures on the Curry-Howard isomorphism", up to the proof of the original Curry-Howard correspondence (between simply-typed lambda calculus and intuitionistic logic) in Chapter 4.

  * 14-7 William Troiani "The Church-Rosser Theorem" ([lecture notes](http://therisingsea.org/notes/talk-will-churchrosser.pdf))
  * 2-8 William Troiani "Introduction to lambda calculus" (Sections 1.1-1.3, [lecture notes](http://therisingsea.org/notes/talk-will-lambda.pdf))
  * 9-8 Samuel Lyons "All partial recursive functions are lambda-definable" (Section 1.7, [lecture notes](http://therisingsea.org/notes/talk-sam-definable.pdf))
  * 16-8 James Clift "Simply-typed lambda calculus and strong normalisation" (Chapter 3, [lecture notes](http://therisingsea.org/notes/talk-james-simplytyped.pdf))
  * 23-8 Shawn Standefer "Introduction to natural deduction" (Chapter 2, [lecture notes](http://therisingsea.org/notes/talk-shawn-introintuit.pdf))
  * 30-8 Daniel Murfet "The category of simply-typed lambda terms" ([lecture notes](http://therisingsea.org/notes/talk-catsimplytyped.pdf))
  * 6-9 Shawn Standefer "Kripke semantics of intuitionistic logic" ([lecture notes](http://therisingsea.org/notes/talk-shawn-kripke.pdf))
  * 13-9 **No talk**, instead we'll watch Wadler's [Propositions as types](https://www.youtube.com/watch?v=IOiZatlZtGU) and discuss
  * 20-9 Daniel Murfet "The category of simply-typed lambda terms II" ([lecture notes](http://therisingsea.org/notes/talk-catsimplytyped2.pdf) and an [appendix](http://therisingsea.org/notes/talk-catsimplytyped2-cuts.pdf))
  * 4-10 Daniel Murfet "The Curry-Howard principle" ([lecture notes](http://therisingsea.org/notes/talk-ch.pdf))
  * 11-10 James Clift "System F: Polymorphic lambda calculus" ([lecture notes](http://therisingsea.org/notes/talk-james-systemF.pdf))
  * 18-10 William Troiani "System F in the real world: Haskell and functional programming" ([lecture notes](http://therisingsea.org/notes/talk-will-haskell.pdf)) (the referenced talk by Rich Hickey is "[Simple made easy](https://www.infoq.com/presentations/Simple-Made-Easy)")
  
References:

  * Sorensen, Urzyczyn "[Lectures on the Curry-Howard isomorphism](http://bookzz.org/s/?q=Lectures+on+the+Curry-Howard+Isomorphism&yearFrom=&yearTo=&language=&extension=&t=0)".
  * Girard, Lafont, Taylor "[Proofs and types](http://www.paultaylor.eu/stable/prot.pdf)".
  * Gallier "[Constructive Logics Part I](https://ai2-s2-pdfs.s3.amazonaws.com/55ec/dffd387d44e3d939a8a7dacf7c655a84a793.pdf)".
  * Wadler "[Propositions as types](http://homepages.inf.ed.ac.uk/wadler/papers/propositions-as-types/propositions-as-types.pdf)".
  * Martin-Lof "[On the meanings of the logical constants and the justifications of the logical laws](https://www.andrew.cmu.edu/user/ulrikb/80-518-818/MartinLof83.pdf)".

#### S2 2016 - Topological field theory

Our aim was to read [Kock's book](http://mat.uab.es/~kock/TQFT.html) on the equivalence between closed 2D TFTs and commutative Frobenius algebras. The talks:

  * 28-7 Daniel Murfet "Topological Quantum Field Theory in two dimensions" ([slides](http://therisingsea.org/notes/talk-2dtqft.pdf)).
  * 4-8 Patrick Elliott "Introduction to Frobenius algebras" ([lecture notes](http://therisingsea.org/notes/talk-patrick.pdf)).
  * 11-8 Michelle Strumila "The cobordism category 2Cob" (beginning of Chapter 1, [lecture notes](http://therisingsea.org/notes/talk-michelle-2cob.pdf)).
  * 18-8 Omar Foda "Supersymmetry and Morse theory" (references are [Witten's paper](http://www.math.toronto.edu/mgualt/Morse%20Theory/Witten%20Morse%20Theory%20and%20Supersymmetry.pdf) and [Nicolas Mee's thesis](http://www.virtualimage.co.uk/nickmee/html/supersymmetry.html)).
  * 1-9 Patrick Elliott "The category of Frobenius algebras" ([lecture notes](http://therisingsea.org/notes/talk-patrick-catfrob.pdf)).
  * 8-9 Thomas Quella "Chern-Simons theory as an example of a TQFT" ([lecture notes](http://therisingsea.org/notes/Talk20160908.pdf)).
  * 15-9 Campbell Wheeler "Symmetric monoidal categories and functors" ([lecture notes](http://therisingsea.org/notes/talk-campbell-monoid.pdf)).
  * 13-10 Daniel Murfet "The cobordism category" ([lecture notes](http://therisingsea.org/notes/talk-2cob.pdf)).
  
References:

  * [K] J. Kock's [TQFT book](http://mat.uab.es/~kock/TQFT.html).
  * [Ks] J. Kock's [short version of the TQFT book](http://mat.uab.es/~kock/TQFT/FS.pdf).
  * Atiyah "[An introduction to Topological Quantum Field Theories](http://www.maths.ed.ac.uk/~aar/papers/atiyahinttqft.pdf)"
  * Atiyah "[Topological quantum field theories](http://www.math.ru.nl/~mueger/TQFT/At.pdf)" Publications Mathematiques de l’IHES, 68 (1988), p. 175-186.
  * Segal "[The definition of conformal field theory](https://www.math.upenn.edu/~blockj/scfts/segal.pdf)"
  * Lurie "[On the classification of topological field theories](http://www-math.mit.edu/~lurie/papers/cobordism.pdf)"
  * Carqueville "[Lecture notes on 2-dimensional defect TFT](http://arxiv.org/abs/1607.05747)" (2016).
  * Carqueville "[3-dimensional defect TQFTs
and their tricategories](http://arxiv.org/pdf/1603.01171v1.pdf)" (2016).
  * Kapustin "[Topological Field Theory, Higher Categories, and Their Applications](http://arxiv.org/abs/1004.2307)" (2010).