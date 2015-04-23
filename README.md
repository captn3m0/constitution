#constitution of india

This is a repository based on (not a fork of) <https://github.com/anoopdixith/TheConstitutionOfIndia>.

Go there if you want the complete history. This is for a few reasons:

- I was more interested in seeing blame and diff between versions
- The pdf files and zip files just bog down the repo

So, this is just a clean version of the the same content. There is no confusing
f/r-amendments, just clean history from first version of the constitution to the
current. To do this, I just ran through all the bundles in the other repo and
generated a history out of it.

All the code used to generate this repo can be found in [my "complete" fork](https://github.com/captn3m0/TheConstitutionOfIndia/tree/complete)
of the original repo. The main script is `complete.sh`, which can regenerate this
repo from scratch.

All credit goes to [Anoop](https://github.com/anoopdixith) for dealing with all
the hard work (cleaning, downloading). I'm just freeloading here.

#TODO

- Take care of commit dates and authors
- Try to consolidate commit information from original repo (such as notes)
- Clean up whitespace issues (I've taken care of some, but not all)
  - Especially those single letter words that are broken between linebreaks.
