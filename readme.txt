Welcome to my IMAS UTAS PhD thesis template! Don't be afraid, it's all going to be ok.

%% Basics

I tried to arrange this template in such a way so as to make it as simple as possible to work on dynamically. 

- The main document is "bind_thesis.tex" - this is where all the other pieces are compiled in the correct order to create the final document. 

- Each chapter has its own .tex file within the chapters/ directory. It's not strictly necessary to stick to 1 chapter = 1 file, but I found it easier to work with that way.

- The code for figures within chapters is contained within the chapter .tex itself, as you'll see. However, figure files (ie the actual pictures) have their own folder under the figures/ directory. This was done to avoid clogging up the chapters/ directory with old copies of files.

- Like figures, the code for small tables is contained within the chapter .tex. However for big (multi-page) tables I found that the code was getting in my way, so I seperated them into their own special directory called big_tables/.

- The other_content/ directory is where all the extra (non-research) stuff goes that will eventually be placed into the thesis. It's here that you'll find your acknowledgements, dedication, coathorship, and acronyms sections, as well as the files that contain all your reference list data.  

- Finally, the technical/ directly is where all the behind-the-scenes action is. imasphdthesis.sty is where most of the required formatting and package loading happens, while the formatting/ directory contains the fine-tuned formatting that happens for each individual chapter.

