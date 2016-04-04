+++
date = "2015-10-26T21:25:32-05:00"
title = "Reading group on proof-nets"
menu = "main"

+++

These are the notes for the reading group on proof-nets in linear logic, spanning April 8 and 15 of the [logic seminar](http://blogs.unimelb.edu.au/logic/) at the University of Melbourne. The aim is to:

  * **April 8**: understand the definition of proof-nets and their cut-elimination procedure, and see the statement of the two main theorems in the theory: the Sequentialisation Theorem (which identifies those proof-nets coming from sequent calculus proofs) and the Strong Normalisation Theorem. 
  * **April 15**: work through details of the proof that in stratified linear logic, cut-elimination is achieved in polynomial time (Theorem 16 of Baillot and Mazza's "Linear logic by levels") as stated in my [previous talk](http://therisingsea.org/notes/talk-stratifications.pdf) without details.
  
The main references are:

  * [G87] J.Y. Girard's original paper "[Linear logic](http://iml.univ-mrs.fr/~girard/linear.pdf)"
  * [G96] J.Y. Girard "[Proof-nets: the parallel syntax for proof-theory](http://iml.univ-mrs.fr/~girard/Proofnets.pdf.gz)"
  * [J91] J. Davoren "[A Lazy Logician's Guide to Linear Logic](https://blogs.unimelb.edu.au/logic/files/2015/11/Davoren-LLGLL-2cedcbe.pdf)"
  * [BM09] P. Baillot and D. Mazza "[Linear Logic by Levels and Bounded Time Complexity](http://arxiv.org/abs/0801.1253)"
  * [PTF09] M. Pagani and L. Tortora de Falco "[Strong Normalization Property for Second Order Linear Logic](http://www.pps.univ-paris-diderot.fr/~pagani/snllTCS-1.pdf)"
  
Here is a rough plan that makes sense to me, for the first seminar:

1. General background on linear logic ([J91] Sections 0, 1, 3 and then [BM09] Section 1). Ideally we all would have skimmed this before Friday, to refresh our memories.
2. Definition of proof-nets up to the definition of depth ([BM09] from p.8 to p.10).
3. Some examples of proof-nets (Church numerals from [G87] Section 5.3.2 p. 86 and binary integers from p.26 of [BM09]).
4. Sequentialisation of sequent calculus proofs to proof-nets ([BM09] p.11).
5. Examples of proof-nets that are not sequentialisable, and proof-nets that are the sequentialisation of multiple sequent calculus proofs; discussion of the advantages of proof-nets vs sequent calculus ([J91] p.140, p.156, p.157).
6. Definition of switchings and statement of the Sequentialisation Theorem (very brief statement in [BM09] Proposition 2, details from [G96], examples from [J91] Section 6).
7. Definition of cut-elimination transformations and statement of Strong Normalisation Theorem ([BM09] p.12, p.13 and [PTF09]). This was proven in [G87] for a subsystem but only recently in [PTF09] for full linear logic.
8. If there is any time remaining, some details of the proof of the Sequentialisation Theorem from [G96].

The canonical reference for proof-nets and the Sequentialisation Theorem is Girard [G96], but in order to have notational consistency with the second seminar on light linear logic, and to see an overview free of complicating details, I think [BM09] is a better starting point for us. This means we would view [G96], [J91], [PTF09] as augmenting references for the real details (which are completely absent from [BM09]).