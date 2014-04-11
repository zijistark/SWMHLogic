SWMH Logic
=========

*A core sub-module of [**SWMH**](https://github.com/Aasmul/SWMH) for dynamic logic support*

## Summary ##

This repository holds a Crusader Kings II module to be used with the SWMH module (*SomeWhat More Historic*) to add general dynamic scripting logic to the project while remaining within its scope.  It's currently in its infancy; beware the unpacked boxes and empty rooms.

It is intended to be used with all SWMH installations ideally, but still, a logical separation of the core SWMH history work and auxilliary dynamic scripting has many advantages.  Due to the scope of SWMH, SWMH Logic will never contain any "flavor" or "mechanics" scripting: it will contain largely startup events to apply additional levels of history adaptation, dynamic cultural melting pot / split / transition support events to take the gist of SWMH's history work and make sure it carries over into CKII campaigns dynamically.

SWMH Logic is part of the Historical Immersion Project (HIP), as is SWMH, and as such, its master branch will always be synchronized with the latest public release of SWMH, and those releases will be installed together automatically when using the HIP installer and selecting SWMH.

SWMH Logic is owned by Matthew D. Hall, also known as **zijistark**, a member of the [Project Balance](https://github.com/Meneth/PB-git) team and general HIP meta-team guru, and the module is thus a product of much HIP incest-- organizationally, but from very different schools of thought.  In a similar vein, check out the general [HIP-tools](https://github.com/zijistark/HIP-tools) repository for a random collection of actual software tools developed for HIP (and likely for this module directly and certainly indirectly through its tools such as **culture-melt**).

## Branch Policy ##

Aside from largely using topic-based branches for all development, the exact branch policy of this repository is TBD, as it needs to conveniently map to that of SWMH, and SWMH's own policy, as the project is new to GitHub, is still being determined.

In general, my intentions are:

The master branch will always be a snapshot of the latest stable, public release.  As SWMH Logic will mostly certainly make hard references to SWMH titles and even possibly dynasty IDs or the like, it will be necessarily updated along with SWMH to reflect changes in those dependencies.  This sort of 'general updates' work will be queued in a beta branch before releasing into master.  The path from beta -> master is known as the mainline development path.

Otherwise, most actual work will be done on topic branches that will be added and deleted as necessary, and then usually merged into mainline-- beta before master-- so that different queued changes get a chance to be tested together before public release.  Sometimes, topic branches, even though their development is done, will also remain out of mainline until SWMH is getting ready to release whatever enhancement it is for which the branch's contents are complementary.  This makes a snapshot of the beta branch always valid for testing against the current development version of SWMH.

## Contact Information ##

Please use email. I cannot be reliably reached through the Paradox Forums, for example.

Matthew D. Hall (**zijistark**)
Seattle, WA, USA (PST/PDT)
[zijistark.com](http://www.zijistark.com/)
[zijistark@gmail.com](mailto:zijistark@gmail.com)
