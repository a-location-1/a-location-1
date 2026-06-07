---
title: "Tender Buttons Project"
date: 2024-08-10
---

<img src="https://github.com/a-location-1/tender-buttons/blob/main/images/Mequitta-Ahuja-218.png?raw=true" alt="Mequitta Ahuja's 2018 painting Le Damn Revisited" style="width:40%; height:auto;">

###### Mequitta Ahuja, *Le Damn Revisited*, 2018.[^1]

#### Introduction

> In the inside there is sleeping, in the outside there is reddening, in the morning there is meaning, in the evening there is feeling. In the evening there is feeling.

This self-directed project uses the basic tools of data analysis to engage with the structure and language of Gertrude Stein's 1914 book of prose poems, *Tender Buttons*. 

*Tender Buttons* is in the public domain, [and is available at Project Gutenberg](https://www.gutenberg.org/files/15396/15396-h/15396-h.htm).

#### Why analyze Tender Buttons?

Modernist writing has a reputation for difficulty; data analysis is a way to approach modernist texts from a different angle. 

*Tender Buttons* in particular is the perfect candidate for sustained analysis because its substance - the meaning of the words, the sound of the words, the length of the words, the order of the words, the selection of certain words and not others - is the product of tremendous attention. In a 1946 interview Stein described the process of writing *Tender Buttons*: "I used to take objects on a table, like a tumbler or any kind of object and try to get the picture of it clear and separate in my mind and create a word relationship between the word and the things seen. [...] I try to call to the eye the way it appears by suggestion the way a painter can do it. This is difficult and takes a lot of work and concentration to do it. I want to indicate it without calling in other things."[^2]

Modernist writers like Gertrude Stein have fans and detractors - as Hermione Lee sums up the question, is Stein "the most remarkable creative experimentalist of her century or a ludicrously self-inflated, interlably repetitive, and dead-end mannerist--or perhaps a bit of both"?[^3]

> A SUBSTANCE IN A CUSHION.
>
> The change of color is likely and a difference a very little difference is prepared. Sugar is not a vegetable.

This project treats *Tender Buttons* as an experiment. What are the results of this experiment? Stein scholar Francesca Wade writes that in *Tender Buttons* "words are set free from the shackles of memory [...] and charged with the power to make the world afresh."[^4] If this is so, mutating the text through manipulation and analysis may help us see what changes have been wrought on the 10,101 unique words that make up the book. 

<img src="https://github.com/a-location-1/tender-buttons/blob/main/images/Damien-Elwes-2010.png?raw=true" alt="Damien Elwes' 2010 painting Picasso's studio at Bateau Lavoir" style="width:50%; height:auto;">

###### Detail of Damien Elwes, *Picasso's studio at Bateau Lavoir 1908* (2010).[^5] Robert Bartlett Haas writes that "*Tender Buttons* was to Gertrude Stein's development what the "Demoiselles d'Avignon" was to Picasso's, a key work marked with the enormous struggle of creating a new value."[^6]

It's also serendipitous that "tender buttons" sounds like one of GitHub's randomly generated names for a new repository - the legacy of modernism in contemporary form.

#### Project Overview

> A glass is of any height, it is higher, it is simpler and if it were placed there would not be any doubt. 

The project uses five stages:

| Stage      | Implementation | 
| ----------- | ----------- | 
| *Ingestion.* Import the text. | **Python.** Read the text from a local .txt file. | 
| *Data Cleaning.* Organize the text in a useful way. | **Python.** Brute force through the text to identify and organize the words. | 
| *Loading.* Export the data to a relational database. | **Python, DBBrowser for SQLite.** Export the table of words to .csv, and upload the .csv into DBBrowser. | 
| *Data Analysis.* Query the data. | **SQLite.** Run a battery of basic queries in an attempt to find interesting patterns. | 
| *Data Visualization.* Display the results.  | **LibreOffice's Calc Spreadsheet.** Display the results in a static worksheet. | 

#### Results

Here are some basic results: TBD. 

[^1]: From [Mequitta Ahuja's digital portfolio.](http://www.mequittaahuja.com/digital-portfolio.html). In *Le Damn Revisted* (2018), Mequitta Ahuja sits in front of a depiction of *Le Damn*, the artist's earlier interpretation of Picasso's *Les Demoiselles D'Avignon*. *Le Damn Revisited* also iterates on *Xpect*, a similar composition in which the the artist sits before *Le Damn* and holds a sonogram; Ahuja used *Xpect* to announce her pregnancy in 2018. Combining the historical context of art history with the contemporary landscape of social media, *Le Damn Revisited* introduces many of the same themes explored by this data analysis project: meaning created through careful patterns, repetition as a core faucet of process, the treatment of historical works with current technology, and the importance of critiquing Picasso. 

[^2]: "A Transatlantic Interview--1946." *A Primer for the Gradual Understanding of Gertrude Stein.* Ed. Robert Bartlett Haas. Black Sparrow Press, 1971. 

[^3]: "Epic Ambitions: a Review of Francesca Wade's Gertrude Stein: An Afterlife." *The New York Review* (12 Feb 2026).

[^4]: *Gertrude Stein: An Afterlife.* Scribner, 2025.

[^5]: Printed in Baiges, Maite Méndez. "After Picasso: Reinterpretations and recreations of *Les Demoiselles D'Avignon* in Contemporary Art." *Les Demoiselles d'Avignon and Modernism.* Firenze University Press, 2022.

[^6]: "A Transatlantic Interview--1946."  
