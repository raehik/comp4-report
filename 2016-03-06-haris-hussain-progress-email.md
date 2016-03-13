Hi sir,

Update email as promised. Looking at my requirements list, I've implemented all
but desktop notifications and family sharing. The GUI doesn't yet allow manual
searching but the code is already implemented, and printing should be a few
lines away from working. I need to research how to use notifications preferably
cross-platform and I probably won't do family sharing.

About complexity: if the current system isn't complex enough, I could implement
a user system (in the veins of family sharing) which would check for clashes
when adding appointments. Theoretically it should be a 'safe' change because
most changes would be limited to my database handling class.

But looking at the complexity teacher help sheet, I seem to match 'A Complex
data processing problem' very well (4.1 pg. 7):

  * Data is processed after queries (date & time are stored as integers)
  * Safe SQL usage through almost fully parameterised queries -- also means no
	disallowed characters
  * Highly modular (data is manipulated through abstract "add_to_database"-type
	commands, so even the database could be switched out e.g. to plain-text,
	CSV, MySQL)
  * Haven't yet done normalisation/selecting from multiple tables but *will* if
	I implement notifications
  * I use all the SQL commands they mention
  * Also printing, and OOP separate from GUI

What do you think? If I implement notifications & normalise my database, is
that fully complex? I can also say that it is almost cross-platform (should be
little in the way of running on Windows).

Thanks,
Ben Orchard
