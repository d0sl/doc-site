---
title: "d0sl"
---

## d0sl: Delta 0 Semantic Language

**d0sl** is a next step generation of so called Business Rules Engines (BRE). Just like regular BRE's d0sl allows you to implement business logic of you system by using declarative logical specifications language. 

> _There are several important advantages over traditional BRE:_

> d0sl has very simple purely logical syntax, which does not require any programming skills from users who use it to specify business logic. Which any one who has basic understanding of logic can start using it in a matter of several hours unlike other BRE, which require significant investment of time to learn and special programming skills to understand and write business rules.

> d0sl scales from embedded systems to enterprise level. Its footprint is very lightweight and can be deployed even on embedded systems like Raspberry PI. On the other hand, d0sl can be used on enterprise level (we have carrier grade version of d0sl called Eyeline SDP, which is used by several mobile telcos, banks etc).

> d0sl has very clear intuitive semantics for non programmers, because d0sl is based on a pure Delta 0 subset of first order predicate logic and has mathematically proven semantic. Unlike d0sl other BRE's have non clear semantic which makes them much more difficult to use.

> d0sl allows to create DSL's (domain specific languages) which can be used to create business rules not only by your employees, but also by your end users.  

> d0sl provides IDE our of the box, which simplifies creation of logical rules. We supply this in a form of d0sl plugin for JetBrains MPS. This simplifies the creation of semantic logical models because this plugin helps the user to create syntactically correct semantic models.

> d0sl allows easy integration with your existing software by implementing integration drivers (so called domain models).

> d0sl allows to implement one set of logical rules on top of the other sets of logical rules (a set of logical rules are called semantic model). This allows to increase level of abstraction as much as you need. And this is important for you to create a Domain Specific Language for your users/employees which is easy to learn and easy to use.

Main components of d0sl:

1. d0sl language itself
1. d0VM -- semantic virtual machine which executes _semantic models_ written in d0sl language
1. d0SDK  -- an _IDE_ for creating semantic models, which also includes d0sl examples
1. Domain models (or so called drivers) that serves to link the language with external systems, and allow you to define logical rules, using terms of the subject area.

{{% notice note %}}
We like the word d0sl and we will use it both for the language and for the system as a whole, or even for the components mentioned above. The meaning should be clear from the context , for example, d0sl language, d0sl virtual machine etc.
{{% /notice %}}

{{% notice tip %}}
You can think of d0sl as a logical operating system which can execute _semantic models_ written in d0sl language. As any OS d0sl needs _drivers_ to communicate with an environment: such drivers in d0sl are called **domain models**. Another similar analogy is the JDBC drivers, which connect to the database.
{{% /notice %}}

{{%expand "How d0sl can save humanity from robots rebellion?" %}}
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
d0sl technology can be embedded in AI, IoT, autonomous systems of any complexity. In this case, it becomes possible to determine the logical rules of the behavior of such systems in a clear language of human logic. For example, so can be implemented the three Laws of Robotics.
{{% /notice %}}

{{% /expand%}}