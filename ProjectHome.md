# Development has moved! #
I have moved my development repository to https://github.com/jberger/MakeBeamerInfo , please follow its progress there. This repository will be slowly shut down, leaving only the current download list.

## Original Page ##

A Perl script to take the .nav file from a LaTeX Beamer (http://latex-beamer.sourceforge.net/) based presentation and create the .info file for use with Impress!ve (http://impressive.sourceforge.net/).

Specifically it is intended to remove all intermediate pages from the overview, create a different transition for the new frame and grab section and subsection titles as frame titles for the first page in each respective (sub)section. It also allows for the overriding of the default allowed transitions.

It is designed to create a visually interesting but clean presentation without any information of what is being displayed (i.e. no markers in the .tex file as gettransitions does). This allows one to use a Beamer presentation that was not specifically created for Impress!ve.

You will need perl to run the scripts. However, the new binaries can be run without perl, Linux only so far but more coming soon. You will also need a presentation created with LaTeX Beamer and Impress!ve for this to be useful for you.