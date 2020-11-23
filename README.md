# Website Privacy Statement Evaluator

Final project for the Building AI course

## Summary
Tool for Privacy Lawyers to check how their privacy statement compares to others out there. The AI would help to flag if the statement is missing legal requirements and help to draft it as user-friendly as possible (length, sentences, words used).
## Background

We all know that nobody reads the privacy statements, when they access a website for the first time. Or same pretty much applies to terms and conditions of online purchase.
The reason can be said to be legalese text: a text written to other lawyers, not to consumers. Privacy is one of digital world´s core accountability aspects. People visits millions of websites, and each website needs to have a privacy statement if the entity desires to collect data of their website users.
It is good to have transperancy how data is collected and for which purposes it is used. Thus, it is important that the privacy statements are easy to read without unnecessary legal terms. So that the user would easily understand their own position. 


## How is it used?

A privacy lawyer or someone else who is responsible to draft the privacy statement would insert the draft to the software (rather before going "live" with it in the website). The software will then give an output that defines all the features


## Data sources and AI methods

Privacy Statements could be collected from all kind of websites and utilize some own privacy statements that are analyzed and designed to be the ideal use-friendly statements.

I think that the AI methods that could be used are Natural Language Processing (NLP), Term Frequency Inverse Document Frequency (tf-idf) and Neural network for classification.
To open the idea, is that the AI methods would classify each word in the Privacy Legislation and Privacy Statements and give them certain weight. Then it would use a Neural network would connect different aspects to "create a conherent output". Also, the method would learn more everytime these is new privacy statement checked.


## Challenges

The project will not solve missuse of personal data. 
The challenge will be creating a model that understands "legal quality" as user-friendly but one that fullfills legal requirements for privacy statements. 
There isn´t one fits for all. The software will not give the perfect output as it will not now the purposes of the entity behind the website. A privacy statement is connected to the data that is collected and for what purpose. Different actors may have similar reasons and targets to collect data but also completely opposite even in the "same industry area". 

## What in the future?

First the plan is to start with only English and then continue to cover as many languages as possible. Perhaps the use of Facebook´s or Google´s language algorithms here is useful.
It could be interesting to wide the model to handle also the terms and conditions of online shopping (and why not others). They are also notoriously never opened by people, just click the box "Accept".
