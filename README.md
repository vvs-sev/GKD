The Kolkhoze doctrine: ten simple principles that should be scrupulously applied by all developers
==================

The kolkhozian doctrine is a quintessential element of programmatical wisdom. For decades, the doctrine has been passed down orally, from generation to generation, among the members of the secret order of kolkhozian programmers. Unfortunately as time passed, the study of the doctrine itself reached an end, and was overshadowed by numerous interpretations and commentaries. We witnessed the emergence of [heretics of a sort](https://twitter.com/sum3rman), who knowingly [distorted](http://devzen.ru/episode-0028/) the doctrine in order to instill fear and doubt within our hearts. Thus, the order sees no other way to protect the truth than to reveal the doctrine with great publicity. Below, we present the most exact approximation of the original doctrine, which we were able to reconstitute from individual fragments, thanks to the work of a few dedciated people.

## Rules of the Great Kolkhozian Doctrine (a.k.a. GKD, Kolkhoz Doctrine, Kolkhoz-driven development or simply The Principle)

1. The goal of any programmer is to produce a working product and happy users. The users must never suffer (or at least, not more than the usual). If, for example, you rolled out a fix that causes hardship to the user, no matter what the cause is, cancel it and [investigate the problem in a separate branch](http://eax.me/vcs-practice/). The users know nothing of the bad people that are tied up in the development of undocumented features of your marvellous API and the likes. A direct consequence of this rule consists in the fact that any alteration made to the product should not make it worse than it already was up to that point. If it turns out that the product did indeed turn out worse, take back the release and replace it with a previous version.
2. Understand that you are not the only one in command. Let's just agree, you say, that we can solve  a problem by just doing away with the Paxos protocol. But apart from you, there are five more people in command, and it's highly doubtful that they would want to even know what your Paxos protocol is. And it is also quite unlikely that people who would pass by your office everyday would have even heard that word. The fault lies not in your colleagues, but in yourself, and you are the only one who can argue in favour of your decision. That decision is above your responsibility, so find another. Don't turn all categorical, but seek a compromise, find a way to solve conflicts that will arrange everything. For example, leave the last word to your team leader.
3. Only the (ситхи) make absolutism a principle. For example, only ever launch a single process in Docker, use only constant variables, or on the contrary, only and exclusively apply OOP principles, write everything using Vim, praise the MacBook as an ideal working tool that simply "just works", say that you should never use Java because its garbage collector sometimes does a "stop the world", or, for example, that Erlang has `remsh` and hot code upgrade and that all other languages are therefore utterly useless -- that is all just heresy. Another lesson here is that one should avoid categorical statements such as: "it is perfectly obvious that everything is the fault of our database (the language we are writing this in), so let's just migrate everything to MongoDB (Haskell)". Technological choices rarely turn out to be the cause of a problem, as a matter of fact it is almost always the people. Carefully examine each concrete situation independently, and pick an appropriate tool using stringent criteria, and not whichever fantasy of yours about what is right and what is wrong.
4. Fight perfectionism. Crappy code is normal. On any project, more than one programmer is going to work long and hard. Client demands, and therefore the code itself, are constantly changing. It would be strange not to find crappy code here and there. _It works, don't touch it!_
