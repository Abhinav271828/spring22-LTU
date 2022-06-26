---
title: Open-Source Morphology for Endangered Mordvinic Languages
numbersections: true
---

# Abstract
Shared devpt of finite-state description of Erzya, Moksha  
Morpholexical unity/diversity: motivation for shared open-source FST

# Introduction
Mordvinic languages are endangered  
Morph analyser is one of first NLP tasks on LRLs  
Here: open-source FST-based morph analyser  
Highlight importance of design decisions  
Describe how FSTs can be edited (?)

Erzya and Moksha have been studied

Open-source morph devpt has greatly benefited from projects  
Like GiellaLT  

People new to language doc should have opportunities to develop understanding

# Designing for a Reusable API
Similar tools and methods may be developed by diff groups  
Leads to fragmentation

Rule-based morphology is there in many systems  
We use HFST

Can be used in many contexts  
Have to design FSTs compatible for HFST  
Define API

Apertium also uses FSTs
Supports HFST  
But tagset is different

# Erzya and Moksha Language Pair
Roughly equal in GiellaLT  
Resources are not identical, but sizes are comparable  
Many situations where consistency would be good

Apertium uses shallow-transfer: morph analysis, lemma translation, morph generation  
Good for closely related languages

Mutual phenomena = Exact matches + Fuzzy matches  
Same categories, but paradigms have diff structures  
Union of tagsets

Diversity: definiteness, person, number  
Subject-object paradigm

# Current State and Ensuring Maintainability
Lemmas, stems and glosses acquired through several channels

Declension of nominals other than nouns has not been dealt with

Derivations = morphologically new forms + compounds  
Diminutive  
Something and all

Agile :)  
Unit testing

To allow noobs to contribute, two levels of abstraction:  
XML-based dictionary  
Ve'rdd, Akusanat UI

Method has been used before

# Conclusions
Have presented work on FSTs for Erzya and Moksha  
GiellaLT support: higher-level services

Open-source, accessibility also  
Generic multilingual Python API  
XML-based dictionary so anyone can contribute

Open-source good
