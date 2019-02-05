---
layout: post
title:  "Isothermal Heat Transfer???"
date:   2019-02-05 10:00:00 +0530
categories: thermo2
author: "babywei"
---
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`Isothermal heat transfer`? This phrase doesn't make any sense to me at first glance.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This is a phrase I came upon a lot when studying the `Stirling Cycle`. One of the phase in Stirling cycle is to add heat to the system without increasing its temperature, hence 'Isothermal Heat Transfer'. Well, I don't know about you but that seems counterintuitive to me on first encounter. We are brought up with the notion that heat equals temperature, so adding heat increases the temperature.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;But `heat` and `temperature` is different. Let's start with temperature as its more relatable to our daily experience. Temperature is the degree of hotness of a substance, basically a way to quantify the sensation between touching a glass of ice water and a cup of boiling water. Heat is different. You can't sense or directly measure heat. You could even argue that heat doesn't exist if the only prove you want is sensory prove. In fact, heat is some abstract term physicists came up to explain the missing part in equations of natural phenomenon. For instance, if I put in 4 units amount of work input and get only 3 units of work output, where did the remaining 1 unit went? Hence scientist name the remaining 1 unit as heat to balance the equation. And it happens that establishing the 1 unit as heat stands true and consistent in later experiments, hence it's generally accepted that way.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Now that we understand heat and temperature, how does the heat added not increase the substance's temperature? This can happen in a few cases, one of them is as in the case where the heat is used as `latent energy` during phase change to break the chemical bonds between atoms.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;But in our case of Stirling cycle, to achieve isothermal heat addition or rejection, process should occur in very slow manner. As we have in thermodynamics first law,

```
dQ = dW + dU
*  dQ = change in heat,
   dW = change in work,
   dU = change in internal energy

```

where, change in internal energy `dU=0` (for T=Constant) i.e. for Isothermal Process

and as that implies, `dQ = dW`,<br/>
which means whatever heat is added into the system is used to do work or is rejected out of the system, and none of it is used to increase the internal energy, dU `i.e. temperature` of the atoms. How is that possible? Well quoting the answer to this question by Nilesh on Quora,

> In order to achieve isothermal heat addition or rejection, process should occur in very slow manner. so that whatever internal energy is gained by the system because of heat addition, it will have sufficient time to reject it to surrounding.This way we can maintain internal energy constant.

But it nearly impossible to conduct this process this in real life, hence isothermal heat transfer is called ideal process as in the Carnot cycle and is merely used for concept purposes.

<br/><br/>
This question is originally answered in Quora so credits to the people involved.

[Link&emsp;>>&emsp;Quora - Why isn’t isothermal heat addition and heat rejection possible in the Carnot cycle?](https://www.quora.com/Why-isn%E2%80%99t-isothermal-heat-addition-and-heat-rejection-possible-in-the-Carnot-cycle)
