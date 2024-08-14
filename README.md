# PhD Thesis for IMAS, UTAS

This is a template version of the document I used to create my PhD thesis for the Institute of Marine and Antarctic Studies at the University of Tasmania. 

## History

Michael Sumner's 2014 UTAS PhD Latex thesis (https://github.com/mdsumner/utas_latex_thesis) was a copy of Tim Callaghan's 2004 version, which is no longer available. The newer version was then updated in 2020 by Wilma Huneke (https://github.com/wghuneke/UTasIMAS_PhDThesis_Template) to conform to IMAS requirements. I am once again adding to this noble tradition with updates of my own, including:
 - Conform to the 2023 HDR thesis formatting guidelines
 - Optimising for PDF by default instead of print (gotta get with the times, yo)
 - Using APA7 referencing style
 - Adding more required and optional preface sections
 - Adding some QoL shortcuts for our field specifically including citation aliases, dynamic species names, and figure caption icons

## Using this template

I am in the process of adding a readme file within the template itself with detailed instructions on how to use each part of this tempate, as I realise that often the thesis-writing process is the first time that many students will be using Latex. Stay tuned also for a detailed featurelist on my blog at https://drtreimer.com.

I originally imported this project from Overleaf, so the simplest way to get started with it is to download it as a zip file and upload it as your own new project to Overleaf. You don't even need a premium subscription! 

## Troubleshooting

I'm not sure I'll always have the time to answer questions if you're having difficulties with this template, but if you ask very nicely I might answer your question. I'll also try to keep a list of common problems here.
- **Command \underbar has changed**: this warning happens when two packages load different definitions of the same command (\underbar, in this case). Since I didn't actually use the \underbar command (it's basically math-mode-only underlining), I just ignored the error. If you want to actually use the command you'll need to find out which two packages are conflicting and load your preferred package before the other in the package list. 
