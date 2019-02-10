---
title: "d0sl semantic language platform"
---
# Problem of algorithms
Theory of algorithms was created by Alan Turing as a part of effort of Allies during WWII to crack Nazi's Enigma code using so called computers. Computers can understand only exact sets of infrustrions explaining how to solve the problem. Such sets of instructions are called _algorithms_ of _computer programs_. 

But we humans in our every day life use logic in our language. Regular person could hardly remember all the  instructions even for the washing machine. So we have special people who can do a translation between us humans and computers, which are called _software developers_ or _programmers_. But the problem is that even after more than 70 year history of computers we still have less than **1% of population** who can do such job.

_Algorithms_ give computers an exact set of instructions on _how_ to solve the problem. In order to create such _algorithm_ you need to perform certain steps:

1. Specify the problem in a manner, which excludes uncertainties. Such specifications should have _rigid_ and _logical_ form.
2. Give it to programmers 
3. Eventually after several technological steps (such as architecture, OO design, etc) programmers convert the specification into a _program_ written in some of _programming languages_ 
4. Such program can now be translated into a _machine code_ and executed on a computer.


![What->Developer->How](/images/specs-dev-code.png)

This means that everytime we need to make computers to do something we have to have a computer program, which can be created only by software developers **manually**. Manual work as everybody knows involves human errors. So **#1 problem** is the **Quality** of software programs written by humans. Software _bugs_ can kill any good intention.

The more programs we need, the more software developers will be involved. The more computers are used by humanity, the more programs we need, and even more developers will be required. Introduction of _mobile phones_, _IoT_ and _Edge Computing_ into everyday life creates more and more demand for _programmers_. Don't forget that every mobile phone is a computer. And we want to put computer chips into _things_ like tea pots and fridges. 

Today we have more computers on the planet than humans. Think about this. Where are we going to get enough _software developers_ in the situation when number of computerized equipment grows much faster than numebr of developers. This **problem #2** -- we have **not enough programmers**.

And **problem #3** -- is that _mobile_ communications, _robots_, _edge computing_ and _Iot_ reiterates the problem of the quality: our civilization becomes more and more dependent on the **quality of computer programs**.

# Semantic modelling
Originally the mathematical theory behind this technology was developed in Sobolev's Institute of Mathematics by three famous  mathematicians Yuri L. Yershov, Sergey S. Goncharov and Dmitry I. Sviridenko. 

So the idea behind **semantic modelling** is how to make it simpler for _non-programmers_ to communicate with computers. Instead of creating yet another algorithmic language for programming, semantic modelling is focusing on using _logical_ language allowing _non-programmers_ to effectively explain computers _what_ to do (opposed to algorithms describing _how_). Such _semantic models_ are called **executable specifications**.

In _AutodromAII_ example you can see how semantic model specifies pure logical rules for autonomous cars. 

## Learn `d0sl` platform

`d0sl` stands for \\( \Delta_0 \\) (_delta zero_)Semantiс Language. (See `d0sl` syntax [here]({{< ref "/d0sl/_index.md" >}}) ). `d0sl` is a declarative executable specifications language, which is a constructive subset of the first order predicate logic language. You can find mathematical definition of \\( \Delta_0 \\)-formulas [here]({{< ref "/d0sl/delta0_math_def.md" >}}).  If you are interested in math theory behind please check this [list of articles] ({{< ref "/d0sl/articles.md" >}})

`d0sl` effectively represents an **AI 2.0** platform for **automomous decision making** systems based on a semantic modelling approach.

Main components of `d0sl` platform:

1. **d0sl core** engine which executes _semantic models_
2. **d0sl SDK** (semantic definition kit) -- an _IDE_ for creating semantic models, which also includes `d0sl` examples
3. other _tools_ and **domain models**

You can think of `d0sl` as a logical semantic operating system which can execute _semantic models_ written in a logical language. As any OS `d0sl` needs _drivers_ to communicate with an environment: such drivers we call _domain models_.

## Areas of applications for `d0sl` semantiс technology

Please don't be delluded, semantic modelling is not a silver bullet. It won't allow to create _any_ program for non programmers. Semantic modelling helps to solve so called logical or discrete problems. For example, if you need to solve some specific heavy computational tasks (like neural networks, differential equations, etc)  you still need to do traditional programming. UI is still easier to be developed by humans. 

We see the following areas of applications for semantic modelling:

1. **Autonomous systems**. For example, semantic modelling is being used for many years by mobile telcos, and banks. 
2. **Business logic** and **workflow** process automation.
3. **Embedded** systems and **edge computing**.
4. **Industrial IoT**
5. **Robotics** and autonomous equipment


# Revolution of autonomization

Several new advancements in technology drive the next industrial revolution:
1. AI 1.0 technology: _object recognition_, _machine learning_ and _neural networks_
1. _IoT_  - Internet of Things
1. _Edge Computing_: process data into information on the edge, instead of uploading big data into clouds
1. AI 2.0 technology: _semantic modelling_ and _ontologies_ allow to process information into _knowledge_

{{% notice note %}}
Remember the three Laws of Robotics which govern the behaviour of Isaac Asimov's fictional Positronic Robots were formally stated by Asimov in his story "Runaround" (March 1942):{{% /notice %}}

1. A robot may not injure a human being or, through inaction, allow a human being to come to harm.

2. A robot must obey orders given it by human beings except where such orders would conflict with the First Law.

3. A robot must protect its own existence as long as such protection does not conflict with the First or Second Law.

This is exactly what we want to turn into reality!
![Industrial revolution](/images/industrial-revolution.png)

Now there is a new industrial revolution. Neural networks drive a car instead of a person. Complex mechanisms and systems work longer and longer without human participation.

But there is a recognized problem in the field of artificial intelligence. Namely the black box problem. Even a neural network technician does not know what is going on inside.

{{% notice tip %}}
Our project is to help humanity to control artificial intelligence, autonomous systems (or even business processes) by using understandable domain specific language and human logic.
{{% /notice %}}

{{<mermaid align="left">}}
graph TB
    subgraph Or even embedding
    c1[fa:fa-robot Robot]-->c2[fa:fa-car Car]
    c3[fa:fa-user Human logic]-->c4[fa:fa-brain d0sl]
    c4-->c1
    end
    subgraph With d0sl control
    a1[fa:fa-robot Robot]-->a2[fa:fa-brain d0sl]
    a4[fa:fa-user Human logic]-->a2[fa:fa-brain d0sl]
    a2-->a3[fa:fa-car Car]
    end
    subgraph Lone neural robot
    b1[fa:fa-robot Robot]-->b2[fa:fa-car Car]
    end

{{< /mermaid >}}