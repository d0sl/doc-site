---
title: "d0sl"
---

## `d0SL`: Delta Zero Semantic Language Привет

**`d0SL`** is a next step generation of so called Business Rules Engines (BRE). Just like regular BRE's `d0SL` allows you to implement business logic of you system by using declarative logical specifications language. 

{{% notice note %}}
Main components of `d0SL`:

1. `d0SL` language itself
2. `d0VM` -- semantic virtual machine which executes _semantic models_ written in `d0SL` language
3. `d0SDK`  -- an _IDE_ for creating semantic models, which also includes `d0SL` examples
4. _Domain models_ (or so called _drivers_) which serve to link the semntic models with external systems, and allow you to define logical rules, using terms of the subject area.
{{% /notice %}}



### There are several important advantages over traditional BRE:

> 1. `d0SL` has very simple purely logical syntax, which does not require any programming skills from users who use it to specify business logic. Which any one who has basic understanding of logic can start using it in a matter of several hours unlike other BRE, which require significant investment of time to learn and special programming skills to understand and write business rules.

> 2. `d0SL` scales from embedded systems to enterprise level. Its footprint is very lightweight and can be deployed even on embedded systems like Raspberry PI. On the other hand, `d0SL` can be used on enterprise level (we have carrier grade version of `d0SL` called Eyeline SDP, which is used by several mobile telcos, banks etc).

> 3. `d0SL` has very clear intuitive semantics for non programmers, because `d0SL` is based on a pure Delta 0 subset of first order predicate logic and has mathematically proven semantic. Unlike `d0SL` other BRE's have non clear semantic which makes them much more difficult to use.

> 4. `d0SL` allows to create DSL's (domain specific languages) which can be used to create business rules not only by your employees, but also by your end users.  

> 5. `d0SL` provides IDE our of the box, which simplifies creation of logical rules. We supply this in a form of `d0SL` plugin for JetBrains MPS. This simplifies the creation of semantic logical models because this plugin helps the user to create syntactically correct semantic models.

> 6. `d0SL` allows easy integration with your existing software by implementing integration drivers (so called domain models).

> 7. `d0SL` allows to implement one set of logical rules on top of the other sets of logical rules (a set of logical rules are called semantic model). This allows to increase level of abstraction as much as you need. And this is important for you to create a Domain Specific Language for your users/employees which is easy to learn and easy to use.



{{% notice note %}}
We like the word `d0SL` and we will use it both for the language and for the system as a whole, or even for the components mentioned above. The meaning should be clear from the context , for example, `d0SL` language, `d0SL` virtual machine etc.
{{% /notice %}}

{{% notice tip %}}
You can think of `d0SL` as a logical operating system which can execute _semantic models_ written in `d0SL` language. As any OS `d0SL` needs _drivers_ to communicate with an environment: such drivers in `d0SL` are called **domain models**. Another similar analogy is the JDBC drivers, which connect to the database.
{{% /notice %}}

{{%expand "How `d0SL` can save humanity from robots rebellion?" %}}
## The industrial revolution has us to belive in the science fiction

{{% notice note %}}
Remember the three Laws of Robotics which govern the behaviour of Isaac Asimov's fictional Positronic Robots were formally stated by Asimov in his story "Runaround" (March 1942):{{% /notice %}}

1. A robot may not injure a human being or, through inaction, allow a human being to come to harm.

2. A robot must obey orders given it by human beings except where such orders would conflict with the First Law.

3. A robot must protect its own existence as long as such protection does not conflict with the First or Second Law.

New industrial revolution begins now. 

- Neural networks drive a car instead of a person. 
- Complex mechanisms and systems work longer and longer without human participation.
- We face robots more and more often.

But there is a recognized problem in the field of artificial intelligence. Namely the black box problem. Even a neural network technician does not know what is going on inside.

Who is responsible for robots? Who controls them if programmers and datasсientists cannot understand the algorithms by which artifitial intelligince operates?

{{% notice tip %}}
`d0SL` technology can be embedded in AI, IoT, autonomous systems of any complexity. In this case, it becomes possible to determine the logical rules of the behavior of such systems in a clear language of human logic. For example, so can be implemented the three Laws of Robotics.
{{% /notice %}}

{{% /expand%}}