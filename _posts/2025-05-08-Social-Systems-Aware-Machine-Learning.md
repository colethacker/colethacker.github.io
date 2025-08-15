---
layout: post
title: "Social Systems Aware Machine Learning"
date: 2025-05-08
categories: SSAML
---

* TOC
{:toc}

## a beginning is a time for taking the most delicate care 

In this blog series, I'm going to explore applying what I know about Luhmann's social systems theory (more on this later) to AI, but more specifically, LLMs. We probably take too much for granted in our current paradigm, and it might be worthwhile to explore different paradigms for examining how to develop AI in a social systems-aware manner. I don't pretend to be a Luhmann or AI scholar. I have some knowledge of both, so forgive my ideas if they seem weird.

I'll call this approach Social Systems Aware Machine Learning (SSAML) for short, out of respect for the entirety of the Human-Centered Machine Learning (HCML) field, which made me think about this. I'll try my best to provide references as well as I can, but much of this is just stream-of-consciousness.

Another thing, perhaps you identify with this: I'm not trying to be some thought leader. I have ideas colliding and messing about in my head. I think that writing them down and putting them out there is important to me. The relevance or impact of my ideas isn't important — simply having them out there *is*. This post will serve as a brief introduction to Luhmann, setting the overall stage. It’s not a comprehensive survey, but enough to get off the blocks to examine how something different may look for machine learning. 

Let us begin.
## inhumanitas ex societate

It's common to feel that many systems we interact with feel "inhuman." We're often reduced to something less than our whole selves. When dealing with government agencies, we become merely a number in a queue. At work, we're a cost center to be optimized. During the most recent pandemic, we were reduced to cases and statistics.

Advanced technologies magnify this effect. Powerful, opaque recommendation systems curate content for us. We've become rows in databases, stored on distant servers, where our next actions can be accurately predicted. Artificial intelligence can generate text and imagery that appears novel and "real," leaving us uncertain about who or what is on the other end.

Moreover, many people struggle with maintaining "different selves." They act or talk differently at work, at church, and home, with various aspects of society seeing them as entirely different people than they truly are, or at least feel that they are.

It feels as if society is gradually dehumanizing itself, and we're left diminished. Some visceral wrong is done to us, an insult to our very being. Yet society keeps moving and, ostensibly, working. How can we feel dehumanized while society, which we believe should center around humans, still operates?

Society also feels impossible to influence. Despite various slogans about the power of the individual, it appears that no single person can truly control aspects of society. At best, there's a butterfly effect of consequences from our actions. At worst, it's as if we've done nothing at all, simply shouting into the void. Yet, society keeps changing. How can society change if no individual can effectively influence it?

Maybe we should ask instead: Can society no longer be thought of as merely a grouping of human beings? Should we shift our focus from examining the constituents of society to observing what actually happens within society?
## stranger in a strange (social) system

This is the basic premise of Niklas Luhmann's social systems theory. Communication, or the event of communication, is what matters. Social systems theory attempts to describe society in terms of its events or communications, not by any one of its members. This means we are not concerned with who (or what) is in society, only with what is generated—the communication itself.

This fundamental shift from individuals to communication has profound implications for how we understand social interaction. We cannot simply reach into someone's head and extract their ideas, thoughts, or feelings. We only have communication in some medium, which is understood and produced within a context. This context truly matters. Imagine trying to communicate about buying old furniture on Facebook Marketplace while speaking in strange, esoteric academic language. It simply wouldn't make sense. Therefore, we must communicate in economic terms when we buy or sell something on Facebook Marketplace.

Various systems in society are functionally differentiated. We identify systems by their differences from one another (which sounds silly, but it'll make sense). Overall, systems create an environment with these differences, where as Luhmann says "difference produced by the system and as the difference observed within the system" (as cited in Moeller, 2013, p. 68) emerges. A system views other systems in the environment through its lens, or perspective, and interprets external meaning according to its internal mechanisms.

Internal mechanisms are called **"codes,"** which develop **"programs."** In Luhmann's social systems theory, codes are the fundamental binary distinctions that govern how a system processes information (such as legal/illegal in law or true/false in science), while programs are the more complex criteria and procedures that apply these binary codes to specific situations, allowing systems to make nuanced decisions while maintaining their operational boundaries.

In another way, programs are how codes are applied, providing structure for processing. We can think of this like code being a grammar, and the programs being sentences or paragraphs. If you want to communicate something in a language, you need to have a common understanding of that language. You also need to express the idea with words while still using the grammar.

While codes and programs govern internal system operations, equally important is understanding how systems maintain their boundaries with other systems. Another aspect of the differences between systems, internally and externally, is that one cannot reach into another system's internal mechanism and change something. This is called **"operational closure”, or the ability for a system to operate independently of its environment**. We can think of this as the ability to differentiate oneself from others. If we couldn't be differentiated, we could simply reach into someone's brain and extract their true meaning without the need for communication. We can't do that (yet). Imagine if we could, I don't know if individuals could exist if we could, but I digress.

Operational closure allows systems to maintain their distinct identity. But how do these closed systems come into being and sustain themselves? Systems are also "**auto-poietic**," **meaning they are self-creating, self-maintaining, and self-referential**. Systems don't emerge from someone's mind or get constructed by some higher being, much like biological evolution. Systems react to, are stimulated by, and are irritated by their environments. Something that happens via systems existing in an environment is that through observations and interpretation of communication, some dependencies start to exist, called structural coupling.

Despite their operational closure, systems don't exist in isolation but in an environment of other systems. This leads us to another concept in Luhmann's theory: Systems can still maintain their operational closure and be interdependent. As an example of closure and interdependence, consider the relationship between two social systems: Politics and the economy. These two systems have a structural coupling via things like taxes, or more topically, tariffs. Tariffs, though not originating from the economy, are still dealt with by the economy according to their **operational closure**, and their internal code. Closure is obeyed, though the coupling mechanisms do "irritate" the internals of a closed system. However, systems that are irritated cannot avoid being irritated in turn. This is a two-way range. Effects on the economy by tariffs are communicated back in terms via the structural coupling with the political system.

The consequences of social systems challenge some of our cultural assumptions. Social systems are largely out of any specific person’s control, which is an uncomfortable thought. In the West, we largely have some implicit, and often explicit, belief in the sovereign individual. The Canadian/American Dream, entrepreneurial mythologies, manifestation and "girl boss"/"sigma male" culture all reinforce the idea that individuals can/should/must determine their way.  That we, in the individual sense, can make a difference based on our hard work and grit. The idea that things are beyond our control to influence is anathema to us in the West. 

However, I think that people are beginning to question these ideals. Climate change and economic inequality have revealed the limits of human agency in addressing societal problems. The growing popularity of critiques of hyper-individuality suggests a shift toward recognizing some of what Luhmann talked about: society operates through systems that are out of our control.

Most of what I write about Luhmann's theory is drawn from Hans-Georg Moeller’s *Luhmann Explained: From Souls to Systems* and Luhmann’s own *The Reality of the Mass Media*. For a more in-depth treatment, please refer to them. In my opinion, Moeller's book is not even-handed, is very generous to social systems theory, and presents little to no criticism or problems with the theory. In a separate post, I’ll collect some criticism of Luhmann's theories.
## do tokens dream of society?

A social systems view has downstream effects on artificial intelligence development. Artificial intelligence is largely about modelling something, the most salient being Large Language Models (LLMs). From a social systems perspective, the text data that trains LLMs is the communications, internal and external, of social systems in their environment. Perhaps this means that we are not modelling language, but instead functionally differentiated social systems.

Consider that different social systems communicate through their own binary codes: the courts through legal/illegal, education through pass/fail or science through true/untrue. When an LLM generates some text about science, it's not about reproducing language, it is simulating how the scientific social system produces communication. 

This thought has a variety of impacts, from the architecture of LLMs to data valuation mechanisms, alignment, and hallucinations. I'll explore these in future posts, along with others. For each subsequent post where I discuss SSAML, I'll describe some relevant bits of social systems theory to give a quick refresher on the important concepts. 

Below is where I'll keep an index of blog posts for ease of navigation.

## Social Systems Aware Machine Learning Post Index



### References

Moeller, H.-G. (2006). Luhmann explained: From Souls to Systems. Open Court.

Luhmann, N. (2000). The Reality of the Mass Media. Polity.
