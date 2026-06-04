---
layout: post
title: "이론 물리학의 기하학적 구조에 대한 강의 - 도입"
author: GeunYeong PARK
date: 2026-06-04
categories: [수리물리학]
tags: [수리물리학]
---

이 연재글은 Frederic P. Schuller 교수님의 강의, **Lectures on the Geometric Anatomy of Theoretical Physics**의 내용을 공부한 것을 한국어로 정리하여 공유하기 위한 것이다.  
이 강의는 [Youtube](https://youtube.com/playlist?list=PLPH7f_7ZlzxTi6kS4vCmv4ZKm9u8g5yic&si=s7cyskQ1GfvxCWdp)와 [Lecture Note](https://tales.mbivert.com/Lectures_on_Geometric_Anatomy_of_Theoretical_Physics.pdf)를 통해 학습 가능하다.  

우선 Lecture Note의 도입부를 소개한다.  
이 강의의 바탕이 되는 철학을 이해하는 데 큰 도움이 될 것이다.  

# Introduction
Theoretical physics is all about casting our concepts about the real world into rigorous mathematical form, for better or worse.  
> 좋든 싫든, 이론 물리학은 실제 세계에 대한 우리의 개념들을 드리우는 것에 대한 모든 것이다.

But theoretical physics doesn’t do that for its own sake.  
> 그러나 이론 물리학은 그 자체를 위해 그러한 일을 하지 않는다.

It does so in order to fully explore the implications of what our concepts about the real world are.  
> 실제 세계에 대한 우리의 개념들이 무엇을 암시하는지 완전히 탐구하기 위해 그러한 일을 한다.

So, to a certain extent, the spirit of theoretical physics can be cast into the words of Wittgenstein who said: “What we cannot speak about [clearly] we must pass
over in silence.”  
> 그래서 어느 정도는, 이론 물리학의 영혼은 비트겐 슈타인의 발언("우리가 명료하게 말할 수 없는 것에 대해 침묵해야 한다.")에 갇혀있다.

Indeed, if we have concepts about the real world and it is not possible to cast them into rigorous mathematical form, that is usually an indicator that some aspects of these concepts have not been well understood.  
> 실제로, 우리가 현실 세계에 대한 개념들을 가지고 있으나 엄격한 수학적 형싱에 그것을 가두는 것이 가능하지 않다면, 보통 그것은 이 개념들의 어떠한 측면이 사실은 잘 이해되지 않고 있음을 지시한다.

Theoretical physical aims at casting these concepts into mathematical language.  
> 이론 물리학은 이 개념들을 수학의 언에 안에 가두는 것을 목표로 한다.

But then, mathematics is just that: it is just a language.  
> 그렇기는 하지만, 수학은 단지 언어일 뿐이기도 하다.

If we want to extract physical conclusions from this formulation, we must interpret the language.  
> 우리가 이런 공식으로부터 물리적 결론을 이끌어내기를 원한다면, 우리는 언어를 해석해야만 한다.

That is not the purpose or task of mathematics, that is the task of physicists.  
> 그것은 수학의 목적이나 과업이 아니고, 물리학자의 과업이다.

That is where it gets difficult.  
> 그것이 바로 어려운 점이다.

But then, again, mathematics is just a language and, going back to Wittgenstein, he said: “The theorems of mathematics all say the same. Namely, nothing.”
What did he mean by that?  
> 다시, 그렇긴 하지만, 수학은 그저 언어일 뿐이고, 비트겐슈타인의 발언("수학의 정리들은 전부 같은 것을 말한다. 다시말해 다른 것이 아니다.")으로 돌아가서, 그가 말하고자 하는 바는 무엇이었을까?

Well, obviously, he did not mean that mathematics is useless.  
> 명백하게도, 그가 수학이 쓸모없음을 말하고자 하지는 않았을 것이다.

He just referred to the fact that if we have a theorem of the type “A if, and only if, B”, where A and B are propositions, then obviously B says nothing else that A does, and A says nothing else than B does.  
> 그는 그저 사실을 언급했을 뿐이다: 만약 우리가 A와 B는 등가이며, 이때 A와 B는 명제라면, B는 A가 말하는 것 외의 다른 것을 말하지 않고, A는 B가 말하는 것 외의 다른 것을 말하지 않음은 명백하다.

It is a tautology.   
> 동어반복이다.

However, while from the point of view of logic and mathematics it is a tautology, psychologically, in terms of our understanding of A, it may be very useful to have a reformulation of A in terms of B.  
> 그러나, 수학과 논리의 관점에서 그것이 동어반복이긴 하지만, 심리적으로, A에 대한 우리의 이해 측면에서, A를 B의 측면에서 재구성하는 것은 매우 유용하다.

Thus, with the understanding that mathematics just gives us a language for what we want to do, the idea of this course is to provide proper language for theoretical physics.  
> 따라서, 수학이 우리에게 그저 우리가 하고자 하는 작업을 위한 언어를 제공해준다는 이해와 함께, 이 강의의 발상은 이론 물리학을 위한 적절한 언어를 제공하는 것이다.

In particular, we will provide the proper mathematical language for classical mechanics, electromagnetism, quantum mechanics and statistical physics.  
> 특히, 우리는 고전 역학, 전자기학, 양자 역학, 그리고 통계 물리학을 위한 적절한 수학적 언어를 제공할 것이다.

We are not going to revise all the mathematics that is needed for these four subjects, but rather we will develop the mathematics from a higher point of view assuming some prior knowledge of these subjects.  
> 우리는 이들 네 과목을 위해 요구되는 모든 수학을 복습하지는 않을 것이나, 오히려 우리는 이들 과목들의 일부 선행지식을 추정하는 더 높은 관점으로부터 수학을 전개할 것이다.

# The Structure of This Course
추가로 Youtube의 첫 강의에서 Frederic 교수님이 그린 두 개의 구조도를 소개한다.  

![FredericOCW_Figure1.1](/assets/img/Figures_ FredericOCW_1.1.png)  
수학의 가장 큰 분류에서의 세 분야(기하학, 대수학, 해석학)에 대해, 물리학의 각 분야가 수학과 어떻게 연결되어 있는지 확인할 수 있다.  

![FredericOCW_Figure1.2](/assets/img/Figures_ FredericOCW_1.2.png)  
이 강의의 진행이 어떻게 이루어질지 보여준다.  
논리학에서부터 시작하여 수학의 탑을 쌓고, 물리학의 각 분야를 다루는 방식을 채택한다.  