# WASP Beamer Template

This template can create WASP-style presentations.  It defines the
following colours:

- waspgrey
- wasplightgrey
- waspblue
- waspmagenta

Note that I will not guarantee that this meets the entirety of the
style guide; it's a not-even-best-effort replication of the slides
that I've seen.

# Dependencies

The template depends on the MinionPro and MyriadPro fonts (which are
the fallback fonts requested by the WASP style guide).  Unfortunately,
neither of them ships in typical LaTeX distributions.  There are a
number of sources around the web on how to install them; the solution
I ended up picking gave me slightly broken fonts (resulting in missing
ligatures for slide headings-- possibly due to some additional hacks
that I did but forgot to note down).  For reference, the solution I
used is linked below:

https://github.com/sebschub/FontPro


Alternatively, you can remove the MinionPro and MyriadPro references
in beamerthemeWASP.sty and fall back to regular fonts.  You will
definitely not adhere to the WASP style guide, though.

# Getting started

Just run pdflatex on `talk.tex`.

Note that I am not sure whether the recommended style is to include
all universities in the title slide or just our own; feel free to
tweak that in `beamerthemeWASP.sty`.

