# Claude Shannon Algorithim Author Emulation Text Generator 
# Created by Ben Zhao
22 Feb 2022 

This program reads text documents and analyzes letter frequency of k-length inside TextGenerator.Java. Changing the filename inside the main method will allow
a specific text file to be read. 

Changing the level k which determine how the program generates a new style emulated text file. 
We determining the probability with which each character follows every possible sequence of characters of length k. 
For example, a level 5 analysis of Tom Sawyer would reveal that 'r' follows "Sawye" more frequently than any other character. 
After a level k analysis, you would be able to generate Tom Sawyer-esque text by always choosing the next character based on the previous k characters and the probabilities revealed by the analysis.
At only a moderate level of analysis (levels 5–7), randomly-generated text begins to take on many of the characteristics of the source text. 
It probably won’t make complete sense, but you’ll likely be able to determine it emulates Tom Sawyer as opposed to Frankenstein.

Examples: Tom Sawyer Text Emulation 

(Level 2:) “Yess been.” for gothin, Tome oso; ing, in to weliss of an’te cle - armit. Papper a comeasione, and smomenty, fropeck hinticer, sid, a was Tom, be suck tied. He sis tred a youck to themen

(Level 4) en themself, Mr. Welshman, but him awoke, the balmy shore. I’ll give him that he couple overy because in the slated snufflindeed structure’s kind was rath. She said that the wound the door a fever eyes that WITH him.

(Level 6:) people had eaten, leaving. Come - didn’t stand it better judgment; His hands and bury it again, tramped herself! She’d never would be. He found her spite of anything the one was a prime feature sunset, and hit upon that of the forever.

(Level 8:) look-a-here - I told you before, Joe. I’ve heard a pin drop. The stillness was complete, however, this is awful crime, beyond the village was sufficient. He would be a good enough to get that night, Tom and Becky.

(Level 10:) you understanding that they don’t come around in the cave should get the word “beauteous” was over-fondled, and that together” and decided that he might as we used to do - it’s nobby fun. I’ll learn you.”
