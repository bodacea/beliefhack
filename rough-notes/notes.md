# Rough Notes

We’re in this perfect storm of concepts: data-driven business, profiling, data-driven power exchanges. But don’t think that only one side can do this \(if there are indeed sides; it’s more like there’s population divided by a clever elite atm\).

What is belief? What do we hold to be truths, and how do we learn them?

1. Why do I care about belief?

2. What’s in these sessions?

3. What is belief?

4. Godel

5. Cyberspace, meet Meatspace…

Data science isn't just about the process of moving from questions and data to insights. There's a lot of that, but there's also what I think of as 'applied cynicism': the art of questioning everything in the process, from the biases of people collecting or generating data to the scope and validity of results. Some of this cynicism is built into the process; some of it is those "oh, wait" moments when a result just doesn't ring true. That's useful in an environment whose inputs have the usual errors and uncertainties of anything involving humans; what's becoming more interesting now is how we do data science in an environment with deliberate misinformation and competitive intent. I plan to look at our current data science mechanisms for handling uncertainty/error, at existing mechanisms for misinformation, and pre-big-data reasoning systems to see what we could potentially do.

**Course on belief: 10 sessions. **

1\) What is belief? What do we hold to be truths, and how do we learn them?

2\) Human belief: Psychology of belief. Collapsed and non-collapsed beliefs: what we can learn from Aspergers and other ways to process perceptions.

3\) Computational belief: Bayesian and frequentist statistics

4\) Practical uses of belief: AB testing and friends

5\) Belief given partial information: perception, partial beliefs and multiple-viewpoint theory.

6\) Beyond normative beliefs: building systems that don’t just go for the middle.

7\) Belief in a complex landscape of ‘truths’ and ‘lies': ACH, Phemes etc.

8\) Challenging belief: the interactions between creativity and knowledge \(CK theory etc\), managing rapid belief change \(e.g. scientific revolutions\) and gaming belief changes in populations \(hello, information injection and information incest detection\).

9\) Lies, damned lies: how evidence and propaganda interact \(or don’t\), and the influence of desire.

10\) Trust but verify. More real-world applications of computational belief; more theories and places to explore.

Truth and Data talk

* 30 mins. Use outline above. 
* “What color is this car?” Does it matter? What could help \(what else could I use, e.g. backup systems, confirmation\). 

References: include searching for happiness book \(et that humans adapt\).

Session: feature selection and attention

* [http://machinelearningmastery.com/an-introduction-to-feature-selection/](http://machinelearningmastery.com/an-introduction-to-feature-selection/)
* if you can’t handle everything, what should you ignore? 
* Why do you do feature selection in the first place? 
* How do you compare and use different types of feature? 

“Illusion of truth”

[https://www.troyhunt.com/the-beginners-guide-to-breaking-website/](evernote-html-snippet://#)



“Most people don't have the time or headspace to handle IW: we're going to need to tool up. Is not much, but I'm talking next month on belief, and how some of the pre-big-data AI tools and verification methods we used in mapping could be useful in this new \(for many\) IW world... am hoping it sparks a few people to build stuff.” - me, whilst thoroughly lost somewhere in Harlem.  


Dammit. I’ve started talking about belief and information warfare, and my thoughts looked half-baked and now I’m going to have to follow through. I said we’d need to tool up to deal with the non-truths being presented, but that’s only a small part of the thought. So here are some other thoughts.

1\) The internet is also made of beliefs. The internet is made of many things: pages and and comment boxes and ports and protocols and tubes \(for a given value of ‘tubes’\). But it’s also made of belief: it’s a virtual space that’s only tangentially anchored in reality, and to navigate that virtual space, we all build mental models of who is out there, where they’re coming from, who or what to trust, and how to verify that they are who they say they are, and what they’re saying is true \(or untrue but entertaining, or fantasy, or… you get the picture\).

2\) This isn’t new, but it is bigger and faster. The US is a big country; news here has always been either hyperlocal or spread through travelers and media \(newspapers, radio, telegrams, messages on ponies\). These were made of belief too. Lying isn’t new; double-talk isn’t new; what’s new here is the scale, speed and number of people that it can reach.

3\) Don’t let the other guys frame your reality. We’re entering a time where misinformation and double-talk are likely to dominate our feeds, and even people we trust are panic-sharing false information. It’s not enough to pick a media outlet or news site or friend to trust, because they’ve been fooled recently too; we’re going to have to work out together how best to keep a handle on the truth. As a first step, we should separate out our belief in a source from our belief in a piece of information from them, and factor in our knowledge about their potential motivations in that.

4\) Verification means going there. For most of us, verification is something we might do up front, but rarely do as a continuing practice. Which, apart from making people easy to phish, also makes us vulnerable to deliberate misinformation. We want to believe stuff? We need to do the leg-work of cross-checking that the source is real \(crisismappers had a bunch of techniques for this, including checking how someone’s social media profile had grown, looking at activity patterns\), finding alternate sources, getting someone to physically go look at something and send photos \(groups like findyr still do this\). We want to do this without so much work every time? We need to share that load; help each other out with [\#icheckedthis](https://www.facebook.com/hashtag/icheckedthis?source=feed_text&story_id=10154418491028736) tags, pause and think before we hit the “share” button.

5\) Actions really do speak louder than words. There will most likely be a blizzard of information heading our way; we will need to learn how to find the things that are important in it. One of the best pieces of information I’ve ever received \(originally, it was about men\) applies here: “ignore everything they say, and watch everything they do”. Be aware of what people are saying, but also watch their actions. Follow the money, and follow the data; everything leaves a trace somewhere if you know how to look for it \(again, something that perhaps is best done as a group\).

6\) Truth is a fragile concept; aim for strong, well-grounded beliefs instead. Philosophy warning: we will probably never totally know our objective truths. We’re probably not in the matrix, but we humans are all systems whose beliefs in the world are completely shaped by our physical senses, and those senses are imperfect. We’ll rarely have complete information either \(e.g. there are always outside influences that we can’t see\), so what we really have are very strong to much weaker beliefs. There are some beliefs that we accept as truths \(e.g. I have a bruise on my leg because I walked into a table today\), but mostly we’re basing what we believe on a combination of evidence and personal viewpoint \(e.g. “it’s not okay to let people die because they don’t have healthcare”\). Try to make both of those as strong as you can.

I haven’t talked at all about tools yet. That’s for another day. One of the things I’ve been building into my data science practice is the idea of thinking through problems as a human first, before automating them, so perhaps I’ll roll these thoughts around a bit first. I’ve been thinking about things like perception, e.g. a camera’s perception of a car color changes when it moves from daylight to sodium lights, and adaptation \(e.g. using other knowledge like position, shape and plates\) and actions \(clicking the key\) and when beliefs do and don’t matter \(e.g. they’re usually part of an action cycle, but some action cycles are continuous and adaptive, not one-shot things\), how much of data work is based on chasing beliefs and what we can learn from people with different ways of processing information \(hello, Aspies!\), but human first here.

IMP: The internet is \(mostly\) location-independent. That affects perception: if I say my favorite color is green, then the option to follow me and view the colours I like is only available to a few people; others must either follow my digital traces and my friends’ traces \(which can be faked\), believe me or decide to hold an open mind until more evidence appears.  Location independence makes verification hard… 

We train our algorithms like we train our children. Except we don’t do that.  We install culture, correct ‘errors’ and deviations from that, etc. What’s the algorithmic equivalent of that? 

Guv bid is part of belief project. Trying to influence mass of people.  Need to find influencers, but not priest and teacher any more.  Can use social media tricks. To find e.g. network influencers like advertising does. But does this translate to offline?

Superbowl. I watched it in a venue that was really really gay. We rooted for Atlanta \("vaguely pro trump", "hey they cheated", "did you notice it's a mostly black team against a mostly nice white boys one?"\) \(But being new York, there were Patriots fans in there too\)…

Thinking about \#fakenews.  Starting with “what is it”. 

* We’re not dealing with truth here: we’re dealing with gaming belief systems.  That’s what fake news does \(well, one of the things; another thing it does is make money from people reading it\), and just correcting fake news is aiming at the wrong thing.  Because… 
* Information leaves traces in our heads, even when we know what’s going on. If I jokingly tell you that I’ve crashed your car, then go ‘ha ha’, you know that I didn’t crash your car, but I’ve left a trace in your head that I’m an unsafe driver.  The bigger the surprise of the thing you initially believe, the bigger the trace it leaves \(this is why I never make jokes like that\). 
* That’s important because \#fakenews isn’t about the thing that’s being said. It’s about the things that are being implied. Always look for the thing being implied. That’s what you have to counter. 
* Some of those things are, e.g. "Liberals are unpatriotic”.  "Terrorists are a real and present threat \*to you\*". Work out counters for these, and mechanisms for those counters. F’example: wearing US flags at protests and being loudly patriotic whilst standing up for basic rights is a good idea. 
* Yes, straighten the record, but you’re not aiming at the person \(or site\) spouting fake news.  What you \*are\* trying to change is their readers' belief in whether something is true. 
* America is a big country. Not everyone can go and see what’s true or not.  Which means they have to trust someone else to go look for them.  The Internet is even bigger. Some of the things on it \(e.g. beliefs about other people’s beliefs\) don’t have physical touchpoints and are impossible to confirm or deny as ‘truth’. 
* Which means you’re trying to change the beliefs of large groups of people, who have a whole bunch of trust issues \(both overtrust for in-group, and serious distrust of out-group people\) and no direct proof.
* You know who else hacks trust and beliefs in large groups?  Salesmen and advertisers. Learn from them \(oh, and propagandists, but you might want to be careful what you learn there\). 

* People often hold conflicting beliefs in their heads \(unless they’re Aspie: Aspies have a hard time doing this\).  Niggling doubts are levers, even when people are still being defensive and doubling-down on their stated beliefs. Look for the traces of these.
* But go gentle. Create too much cognitive dissonance, and people will shut down. Learn from the salesmen on this. 
* People are more likely to trust people they know.  Get to know the people whose beliefs you want to change \(even if it means hanging out in conservative chat channels\). Also know that your attention is a resource: learn to distinguish between people who are engaged and might listen \(hint: they’re often the ones shouting at you; they might also be lurkers\), people who won’t, and sock puppets. 
* More advertising tricks: look for influencers \(not just on Twitter 'cos it’s easy goddammit; check in the real world too\).  There’s only one you: use that you wisely. 

Some reading:

* A field guide to earthlings \(the Aspie reference\)
* Social psychology: a very short introduction

Why is it dangerous \(and pernicious\)?

* Belief affects how people act. 

What are the core beliefs that we’re fighting here?  What else? 

Conversations with people you don’t know or trust… 

* I used to be terrified of public speaking \(as in, throw up, run away, do anything but go up to the podium\).  And then I thought about it a bit, and realized that what a talk is is really a conversation starter.  It’s there to frame the start of a discussion. 

Lies = conflicts and clashes. Also surprise. Can we use surprise? 

“Facts don’t matter: ability to manipulate does”.   


Talk: 

* Intro: What belief is. How people in crowds believe things. Why face to face surveys still matter \(people as BS detectors\). Truth, lies and manipulations \(syntactic, semantic, pragmatic understandings of language: “deep NLP”\). 
* First half: How much of DS and engineering is based on beliefs. 
* Second half: how to talk about belief in an environment where people lie. Science fiction of this \(telling the machine not to trust you\), propaganda, 
* * We’ve already seen this, mapping crises and wars.  Crowdsourcing, verification, information forensics
  * How do the big guys handle this? Infosec, injection, information incest, CIA processing, military counterintelligence techniques…  surprise… 
  * “Watch what they do, ignore what they say \(ish\)”

A lot of DS is based on belief.  We’ve gone heavy on bayesian statistics lately, and this is what that means… 

This is Bayesian statistics.  It differs/ed from traditional “frequentist” statistics because…  Priors become important. Sampling becomes important...

I spend a lot of time talking about beliefs.  Here’s a LVT, part of the lean enterprise idea.  \(Discuss levels of tree\)…  as a DS, I work one two levels of belief here: belief in what’s important to do \(what has the volume and potential value\), and belief in the results of each experiment.  

At the bottom level is HDD… the idea that we create hypotheses and test these - having first set what we believe to be appropriate acceptance levels on them.  

And I keep hearing the same things when we do things like AB testing.  

This is AB testing… 

So that’s belief in LE.  

Misinfocon: 

* Persuasive computing, nudges, resonance…, Kant, non-consensual experiments…  

Counterfactuals!

CIA: describe-explain-evaluate-estimate

Pheme project

* [https://www.pheme.eu/](https://www.pheme.eu/)
* Pheme = rumorous meme. 
* Veracity tracking… 
* 4 areas:  speculation, controversy, misinformation, disinformation
* 3 parts: information in pheme, cross-reference \(to known sources\), diffusion \(what info to whom, how\)
* OS tool, based on GATE + onto text + graphdb. 



“Watch everything they do, ignore everything they say”.  We’ve spent years observing people to understand what they’re really doing… we’re moving into an era where \(unless we really carefully design our tools to be comprehensible\) we’ll have to do the same with machines.  Specifically, with anything using deep learning.  Sunlight detector… built-in biases from data… autonomous systems… 

LVT for winning an election… here’s the tree, here’s how you might start to hack that tree using dev techniques.  Market analysis and segmentation - adaptive segmentation… persuasion… 

LVT for an org… where data science fits into that… where belief fits into that… 

Beliefs post: "You’ve got this the wrong way up": Talk about people thinking about truth when they should be talking about belief.   


  


  


  


