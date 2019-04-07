# Introduction
## Purpose of the system
PrepMaster aims to facilitate a English preparatory school students' learning.
## Scope of the system
PrepMaster will work on Android devices and mainly help students with retention of the English words in their memory.
## Objectives and success criteria of the project
PrepMaster shall include the (Çankaya University's) English preparatory school's target vocabulary and questions that may help students recall these words. Questions' asking shall be timed according to the SuperMemo 2 spacing formula.
## Definitions, acronyms, and abbreviations
None so far.
## References
SuperMemo 2: [Insert Link here]
## Overview
# Current system
Currently, there is no digital system that helps the students learn the target vocabulary.
# Proposed system
## Overview
PrepMaster will help Preparatory School students learn and remember English words more efficiently by enabling students to study English in short bursts on their smart phone, everyday. 

Students will use PrepMaster everyday to go over the English words they learned in school that week, and if there is need, to study earlier weeks' words.

PrepMaster will use SuperMemo algorithm to make sure students retain their knowledge of words.

## Functional requirements
- PrepMaster shall display a variety of questions to make sure the user learnt the word in question.
- PrepMaster shall time the gap between the asking of questions to satisfy spaced repetition requirements.


## Non functional requirements
### Usability
- PrepMaster shall have a simple UI.

### Reliability
- PrepMaster shall download all the necessary data before a study session so that the studying does not get interrupted.
- PrepMaster shall backup all the user data to its server so that the users never lose progress.

### Performance
- PrepMaster shall send as small data as possible to server (an server to PrepMaster) to make sure it is performant.

### Supportability
- It shall be easy to add features such as new question types to the PrepMaster app.

### Implementation
- PrepMaster app shall work on devices with Android OS.
- PrepMaster server shall run on servers with PHP 7+ & MySQL 5+ support.

### Interface
- No constraints here, since PrepMaster & server will only contact each other and no other outside technology.

### Packaging
- PrepMaster  shall be available to users through Google Play Store and/or the F-Droid store.
- It may also be packaged as APK and delivered through the Releases page of Github.

### Legal
- No legel requirements known at this time.

## System models
### Scenarios
### Use case model
### Object model
### Dynamic model
### User interface—navigational paths and screen mock-ups
# Glossary