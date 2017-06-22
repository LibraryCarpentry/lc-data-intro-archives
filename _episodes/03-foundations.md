---
title: "Foundations"
teaching: 30
exercises: 15
questions:
- what best practice and generic skills underpin your encounters with data and research?
objectives:
- identify and use best practice in data structures
- identify and understand a data-driven mindset
keypoints:
- data are used in research
- archival collections and archival description are data
- data structures should be consistent and predictable
- consider the standards and structures used in your own data
- identify and use computational methods in your work
- identify how standards and structures can be used in research
 
---
 
## Foundations
 
In the last episode we discussed what we each think of as data. We came up with a lot of different ideas of what data looks like and how it can be used. Before we crack on with using the computational tools at our disposal, I want to spend some time on some foundation level stuff - a combination of best practice and generic skills that frame what you'll encounter across Archive Carpentry.
 
**Trainer Note**: we recommend using this section as an opportunity to discuss foundational skills that you think are relevant.
 
### Data are Collected Through Research
 
To summarize the brainstorming session that we had in the last episode, data are information collected through research. As archivists we support research. When we start to think of our collections as data we can start to support new methods of providing access to our data. Data can be manipulated using automated or computational methods allowing us to improve our workflows. When approaching our work with a data-aware mindset we should think of the systems that we are using to do our work.
 
### The computer and the systems inside it are stupid
 
This does not mean that the computer isn't useful. Given a repetitive task, an enumerative task, or a task that relies on memory, it can produce results faster, more accurately, and less grudgingly than you or I. Rather when I say that you should keep in mind that the computer is stupid, I mean to say that computer only does what you tell it to. If it throws up an error it is often not your fault, rather in most cases the computer has failed to interpret what you mean because it can only work with what it knows (ergo, it is bad at interpreting). This is not to say that the people who told the computer what to tell you when it doesn't know what to do couldn't have done a better job with error messages, for they could. So keep in mind as we go along that if you find an error message frustrating, it isn't the computer's fault that it is giving you an archaic and incomprehensible error message, it is a human person's.
 
- **The correct language to learn is the one that works in your local context**. There truly isn't a best language, just languages with different strengths and weaknesses, all of which incorporate the same fundamental principles;
- **Knowing the structure of the interface that you are using will assist you in learning **. Databases and computer systems can seem opaque. Knowing what data structures they were built to support can help you to troubleshoot 
- **Automate to make the time to do something else!** Taking the time to gather together even the most simple programming skills can save time to do more interesting stuff! (even if often that more interesting stuff is learning more programming skills ...)
- **Understanding the interface can help you to communicate with developers and engineers** Taking the time to gather together even the most simple programming skills can help you to better communicate your needs to developers.
 
### Beyond the Interface
 
Much of the work that you do with data may be completed through a software interface. Your archival catalog and excel spreadsheets are interfaces that allow you to view your data more easily. The data itself is organized into structures that many of you will be familiar with but is much more text heavy and may not be as simple for humans to read. The structures are simple for 
 
### Data structures for computers
 
### Plain text formats are your friend
 
Why? Because computers can process them! Structures and formats that may be easier for humans to read often cannot be read by computers.
 
If you want computers to be able to process your stuff, try to get in the habit where possible of using platform-agnostic formats such as .txt for notes and .csv or .tsv for tabulated data (the latter pair are just spreadsheet formats, separated by commas and tabs respectively). These plain text formats are preferable to the proprietary formats used as defaults by Microsoft Office because they can be opened by many software packages and have a strong chance of remaining viewable and editable in the future. Most standard office suites include the option to save files in .txt, .csv and .tsv formats, meaning you can continue to work with familiar software and still take appropriate action to make your work accessible. Compared to .doc or .xls, these formats have the additional benefit of containing only machine-readable elements. Whilst using bold, italics, and colouring to signify headings or to make a visual connection between data elements is common practice, these display-orientated annotations are not (easily) machine-readable and hence can neither be queried and searched nor are appropriate for large quantities of information (the rule of thumb is if you can't find it by CTRL+F it isn't machine readable). Preferable are standards that have been 
 
In archival practice, standards have been developed in order for computers to understand the methods that we use to describe our collections. ISAD(G) -- General International Standard Archival Description -- has helped archivists to determine how to describe their collections but EAD -- Encoded Archival Description -- has given archivists a standard way of formatting their description. 
 
