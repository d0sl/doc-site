---
title: "d0sl"
---

## `d0SL` -- Delta`0` Semantic Language

`d0SL` effectively represents an **AI 2.0** platform for **autonomous decision making** systems based on a semantic modelling approach.

Main components of `d0SL` platform:

1. `d0VM` -- semantic virtual machine which executes _semantic models_ written in `d0SL` language
2. `d0SDK`  -- an _IDE_ for creating semantic models, which also includes `d0SL` examples
3. other _tools_ and *domain models*

{{% notice tip %}}
You can think of `d0SL` as a logical semantic operating system which can execute _semantic models_ written in a logical language. As any OS `d0SL` needs _drivers_ to communicate with an environment: such drivers are called **domain models**.
{{% /notice %}}

## Revolution of autonomization

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
    c3[fa:fa-user Human logic]-->c4[fa:fa-brain d0SL]
    c4-->c1
    end
    subgraph With d0SL control
    a1[fa:fa-robot Robot]-->a2[fa:fa-brain d0SL]
    a4[fa:fa-user Human logic]-->a2[fa:fa-brain d0SL]
    a2-->a3[fa:fa-car Car]
    end
    subgraph Lone neural robot
    b1[fa:fa-robot Robot]-->b2[fa:fa-car Car]
    end

{{< /mermaid >}}