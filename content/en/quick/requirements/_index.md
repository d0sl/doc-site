+++
title = "Requirements"
weight = 5
+++

So, our main goal is to give a person the opportunity to describe logical rules in an understandable language. We call it D0SL or Delta Zero Semantic Language.

For this, we should to implement the language, as well as provide a convenient editor (or IDE Integrated Development Environment) that would allow to create D0SL documents and even immediately run.

There are various ways to reach this, but we chose as a bases the powerfull Jetbrains MPS (Meta Programming System). 

{{% notice note %}}
You should preinstall it from [here](https://www.jetbrains.com/mps/download)
{{% /notice %}}

We choose MPS because:

>1. MPS IDE is very similar to Intelliji Idea, PyCharm and other Jetbrains products.
2. MPS helps to create powerful DSL (domain specific languages) and helps to create their powerful extensions.  
3. With MPS we can build plugins of D0SL Language for Intelliji Idea  
4. We were able to develop a technology that does not depend on the MPS and can be used separately. But we see no reason to abandon the convenience of the MPS where it is possible.