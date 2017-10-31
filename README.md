# bc-static-comp2

A Turing project.  The challenge was to mirror the layout of the original design (seen below) while having creative liscence with images, logos, and content.  While the original design has a serious, workplace demeanor, I made mine a lighthearted design around a party-game called "super smash brothers wii u".  This presented several challenges.  First, there was a significant amount of text - which would detract from the image, and second the text would not remain consistent with the playful spirit I was going for.  My solution was to introduce a hover-state that would not only satisfy the comp requirements, but also preserve the quality of image and mood of the other cards that were not in hover state.

Technical details:
My design has three breakpoint that were mathed out using 300px card widths and 10px margins.  There is a maximum of 4 cards per row, limited by the <main> size.  The site is created with flex: wrap, and cards pushed to the next row will align to the left side. 
