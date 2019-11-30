## Overview

**Moonfish** is a free UCI chess engine derived from Stockfish,
which is derived from Glaurung 2.1.
For further information see (https://stockfishchess.org)
and (https://github.com/official-stockfish/Stockfish).


## Goals

The first goal is to change some things I don't like in current Stockfish.
For example, the handling of the pair of bishops, or the structure of
the Hash Table. The fail-high research with a lower depth has already been changed.
At this phase I will try to keep Moonfish still in sync with Stockfish.

In the next step, I plan to change the search. For example,
I want a valid score for each root move. This will also have some impact
on a Multi PV search. From here on I will stop to incorporate patches from Stockfish.

Later, I will eventually try to build an evaluation from scratch.


## Terms of use

Moonfish is free and distributed under the **GNU General Public License version 3** (GPL v3).
Essentially, this means that you are free to do almost exactly
what you want with the program, including distributing it among your
friends, making it available for download from your web site, selling
it (either by itself or as part of some bigger software package), or
using it as the starting point for a software project of your own.

The only real limitation is that whenever you distribute Moonfish in
some way, you must always include the full source code or a pointer
to where the source code can be found. If you make any changes to the
source code these changes must also be made available under the GPL.

For full details, read the copy of the GPL v3 found in the file named
*Copying.txt*.
