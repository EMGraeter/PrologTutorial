# PrologTutorial
A tutorial explaining the AI programming language Prolog

Prolog is a fun and easy programming language to learn. It serves a very important role in artificial inteligence. It is a programming language made for artificial inteligence rather than an AI algorithm made for programming languages. Prolog answers questions based on the knowledge given unlike most other programming languages which perform actions based on instructions given. You might not be able to use Prolog to solve your math homework for you, but the language is great for deducing relations between objects (Geeks for Geeks).

The most basic thing to know about Prolog is that the main code is the knowledge base and this code can be used with queries. the knowledge base is made of two parts, facts and rules. While the knowledge base can just be made of facts, I find it isn't as fun to query without rules. Just like most code the best way to learn Prolog is by example, so I'll start with the easiest thing, facts.

avengers(tonyStark).
avengers(steveRogers).
shield(nickFury).
shield(philCoulson).
battle.

Basically these statements just mean that Tony Stark and Steve Rogers are memebers of the Avengers, Nick Fury and Phil Coulson are agents of SHIELD and that there's a battle happening. Often with Prolog there will be two terminals, one for stating the knowledge base and one for asking queries. A good website for practicing your Prolog skills on is SWISH (https://swish.swi-prolog.org/).

An example of some queries would be:

?- avengers(tonyStark).
?- shawarma.

The first query would return true and the second query would return false. 

Geeks for Geeks By: Prasad_Kshirsagar, Improved By: ManasChhabra2 - https://www.geeksforgeeks.org/prolog-an-introduction/
Learn Prolog Now! By: Patrick Blackburn, Johan Bos, and Kristina Striegnitz - http://www.learnprolognow.org/lpnpage.php?pagetype=html&pageid=lpn-htmlli1
