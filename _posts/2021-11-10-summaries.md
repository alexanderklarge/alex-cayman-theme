---
layout: post
title:  "Summary of Key Ideas Guides"
description: Summary
date:   2021-11-10
tags: [Mermaid]
mermaid: true
---

I wanted to have a quick summary of each of the key ideas posts as I know they're a little verbose at the moment - the whole "if I had more time I'd have written a shorter letter" syndrome. 

I've also recently learned [Mermaid syntax](https://mermaid-js.github.io/mermaid/#/) for making flowcharts which I've been using a lot in Obsidian, and it seems like a great way to make some quick summaries!

## Key Ideas Guide 1 - Intro & Mission

<div class="mermaid">
graph TD;
	id1(Lack of<br>learning at<br>school)
	id2(Best ways to learn)
	
	bwtl1(Spaced<br>repetition)
	bwtl2(Active<br>recall)
	bwtl3(Active<br>encoding)

	id3(Anki)
	id4(Profundity of<br>memorisation)
	prof(Harold<br>Bloom)

	id5(Benefits<br>of anki)
	boa1(Learning<br>doesn't<br>degrade)
	boa2(Incremental<br>reading)
	boa3(Growth mindset<br> and belief in<br>ability to learn)

	id1 --> id2
	id2 --> bwtl1
	id2 --> bwtl2
	id2 --> bwtl3
	bwtl1 --> id3
	bwtl2 --> id3
	bwtl3 --> id3
	id3 --> id4
	id4 --> prof
	id4 --> id5
	id5 --> boa1
	id5 --> boa2
	id5 --> boa3

</div>

## Key Ideas Guide 2 - Learning, Knowledge, Intelligence, Mastery, Anki

<div class="mermaid">
graph TD;
	id1(Aim: Debunking<br>'Anki is just<br>for memorising<br> facts')
	id2(Quick anki<br>primer)
	a1(Daily<br>flashcard<br>process)
	a2(Creating<br>flashcards)
	a3(Contains the<br>3 components<br>of effective<br>learning)
	id3(What is<br>learning,<br>knowledge,<br>intelligence?)
	l1(Learning:<br>3 steps)
	l1_1(Encoding)
	l1_2(Consolidation)
	l1_3(Retrieval)
	id4(Bloom's<br>Taxonomy of<br>Learning)
	b1(6 Categories<br>of Learning)
	b1_1(Anki covers<br>at least<br>first 2)
	b2(4 Categories<br>of Knowledge)
	b2_1(Anki covers<br>at least<br>first 2)
	id5(Inert vs<br>activated<br>knowledge)
	id6(Prior knowledge<br>as foundation<br>for new<br>learning)
	id7(Intelligence)
	i1(Fluid)
	i2(Crytallised)
	id1 ==> id2
	id2 -.-> a1
	id2 -.-> a2
	id2 -.-> a3
	id2 ==> id3
	id3 -.-> l1
	l1 -.->l1_1
	l1 -.->l1_2
	l1 -.->l1_3
	id3 ==> id4
	id4 -.-> b1
	b1 -.-> b1_1
	id4 -.-> b2
	b2 -.-> b2_1
	id4 ==> id5
	id5 ==>id6
	id6 ==> id7
	id7 -.-> i1
	id7 -.-> i2
	
</div>

## Key Ideas Guide 3: Getting Started With Anki

<div class="mermaid">
graph TD
    id1(Downloading<br>Anki)
    id1_1(Free on<br>Desktop)
    id1_1_1(Recommend<br>starting here)
    id1_2(Free on Android)
    id1_3(Paid on iOS)
    
    id2(Using<br>Anki)
    id2_1(Making<br>cards)
    id2_2(Reviewing<br>cards)
    id2_3(Home page)
    id2_4(Creating<br>a deck)
    id2_5(How many<br>new cards<br>per day)
    id2_6(Anki as<br>daily habit)
    
    id3(Tips for<br>starting<br>strong)
    id3_1(Cloze<br>cards)
    id3_2(Make cards<br>in plain<br>text files!)
    id3_3(Don't make<br>orphan cards)
    id3_4(Master deck<br>with subdecks)
    id3_5(Make it<br>clear what<br>the card<br>is about)
    id3_6(Make it<br>memorable)
    
    id4(20 Rules<br>for Formulating<br>Knowledge)
    id4_1(First<br>understand)
    id4_2(Start with<br>big picture)
    id4_3(Simplify)
    id4_4(Mnemonic<br>techniques)
    id4_5(Optimise<br>wording)
    
    id1 -.-> id1_1 
    id1_1 -.-> id1_1_1
    id1 -.-> id1_2
    id1 -.-> id1_3
    id1 ==> id2
    id2 -.-> id2_1
    id2 -.-> id2_2
    id2 -.-> id2_3
    id2 -.-> id2_4
    id2 -.-> id2_5
    id2 -.-> id2_6
    id2 ==> id3
    id3 -.-> id3_1
    id3 -.-> id3_2
    id3 -.-> id3_3
    id3 -.-> id3_4
    id3 -.-> id3_5
    id3 -.-> id3_6
    id3 ==> id4
    id4 -.-> id4_1
    id4 -.-> id4_2
    id4 -.-> id4_3
    id4 -.-> id4_4 
    id4 -.-> id4_5

</div>
