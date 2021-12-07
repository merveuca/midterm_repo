# midterm_repo

While I prepare my pdb file that is going to be used to start simulation, sometimes I need to exclude hydrogen atoms.

I had been used grep -v 'H' <pdb.file> command which means do not take hyrogen atoms.

However, after a while I realized when I used this command I also exlucude lines containing HIS (histitidine), THR (threonine) and etc. -eveything include 'H' word in the file. 

So obtaning the file that serves my desire, is difficult to obtain. 

That's why  I imagine a web-based tool that creates a pdb file according to the intention of the user that could be excluding Hydrogen atoms, only selecting alpha carbons or phosphate belongs to DNA backbone.

The name of the tool might be 'PDBlity' :)

If this may come true, I would be very nice and useful.   
