---
content_type: page
title: 'Unit III: Fourier Series and Laplace Transform'
uid: 7c43a75f-68dd-f5b6-042a-c63be40a5296
---

« [Previous]({{< baseurl >}}/pages/unit-ii-second-order-constant-coefficient-linear-equations/exam-2) | [Next]({{< baseurl >}}/pages/unit-iii-fourier-series-and-laplace-transform/fourier-series-basics) »

![figunit3page.jpg]({{< resource_file eb17af89-aa31-f940-4157-cb04de77386c >}})

Convolution as a superposition of impulse responses. Modeled on the MIT mathlet _Convolution Accumulation._

In this unit we will learn two new ways to represent certain types of functions, and these will help us solve linear time invariant (LTI) DE's with these functions as inputs.

We start with Fourier series, which are a way to write periodic functions as sums of sinusoids. In Unit Two we learned how to solve a constant coefficient linear ODE with sinusoidal input. Now using Fourier series and the superposition principle we will be able to solve these equations with any periodic input.

Next we will study the Laplace transform. This operation _transforms_ a given function to a new function in a different independent variable. For example, the Laplace transform of _ƒ(t)_ = _cos_(3_t_) is _F_(_s_) = _s / (s2 + 9)_. If we think of _ƒ(t)_ as an input signal, then the key fact is that its Laplace transform _F(s)_ represents the same signal viewed in a different way. The Laplace transform converts a DE for the function _x(t)_ into an algebraic equation for its Laplace transform _X(s)_. Then, once we solve for _X(s)_ we can recover _x(t)_.

In the course of this unit, two important ideas will be introduced. The first is the _convolution product_ of two functions. At first meeting this operation may seem a bit strange. Nonetheless, as we will see, it arises naturally, and the Laplace transform will allow us to work easily with it.

The second important idea is the _delta function_. Up to now all inputs to our systems have caused small changes in a small amount of time. An impulse is an input that causes a sudden jump in the system. For example, a sharp blow to a mass will cause its momentum to jump. The delta function is a mathematical idealization of an impulse and one which allows us to handle DE's with these types of inputs.

« [Previous]({{< baseurl >}}/pages/unit-ii-second-order-constant-coefficient-linear-equations/exam-2) | [Next]({{< baseurl >}}/pages/unit-iii-fourier-series-and-laplace-transform/fourier-series-basics) »