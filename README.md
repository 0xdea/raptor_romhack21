# raptor_romhack21

[![](https://img.shields.io/github/stars/0xdea/raptor_romhack21.svg?style=flat&color=yellow)](https://github.com/0xdea/raptor_romhack21)
[![](https://img.shields.io/github/forks/0xdea/raptor_romhack21.svg?style=flat&color=green)](https://github.com/0xdea/raptor_romhack21)
[![](https://img.shields.io/github/watchers/0xdea/raptor_romhack21.svg?style=flat&color=red)](https://github.com/0xdea/raptor_romhack21)
[![](https://img.shields.io/badge/twitter-%400xdea-blue.svg)](https://twitter.com/0xdea)
[![](https://img.shields.io/badge/mastodon-%40raptor-purple.svg)](https://infosec.exchange/@raptor)

> "Converting a memory corruption into a nice weird machine is quite satisfying."
>
> -- Mark Dowd

This repository contains all materials related to *"My last Solaris talk (not your average keynote)"* presented at #RomHack21 on September 25, 2021.

## Related links 

* <https://youtu.be/Nc9ZLTb2hQ8> (video)
* <http://phrack.org/issues/70/13.html#article> (article)
* <https://hnsecurity.it/blog/my-last-solaris-talk-not-your-average-keynote/> (blog)

## Party pack

### article

* [**Exploiting a Format String Bug in Solaris CDE**](article/phrack70_13.txt). A Phrack article that expands on my presentation.

### exploits

* [**raptor_dtprintcheckdir_sparc2.c**](exploits/raptor_dtprintcheckdir_sparc2.c). The Solaris/SPARC format string exploit I dissected during my presentation.
* [**raptor_dtprintcheckdir_sparc.c**](exploits/raptor_dtprintcheckdir_sparc.c). Another version of the same exploit that targets function activation records.
* [**raptor_dtprintcheckdir_intel2.c**](exploits/raptor_dtprintcheckdir_intel2.c). Solaris/Intel format string exploit.
* [**raptor_dtprintcheckdir_intel.c**](exploits/raptor_dtprintcheckdir_intel.c). Solaris/Intel stack-based buffer overflow exploit.

### slides

* [**last.pdf**](slides/last.pdf). Slide deck presented at #RomHack21 (PDF version).
* [**last.pptx**](slides/last.pptx). Slide deck presented at #RomHack21 (PowerPoint version).
