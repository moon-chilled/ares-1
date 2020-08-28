ares, a cross-platform, multi-system emulator
=============================================

ares runs games
for a variety of classic computers and game consoles
on modern PCs.
It is a fork of [higan],
made after higan's author [byuu]
had handed higan over to the community to maintain,
but needed to keep himself busy during the 2020 pandemic.

higan vs. ares
--------------

byuu developed higan up until v110,
releasing it under the GNU Public Licence v3
to discourage commercial exploitation.
When he stepped back from higan development,
community members stepped up to maintain it,
still under the GPLv3.

byuu renamed his personal copy of the code
from "higan" to "ares",
and kept developing it in private.
When he retired fully in July 2020,
he released ares v115
(and relicensed previous versions)
under the more liberal ISC licence.

The community-maintained higan project
has incorporated the improvements from ares v115,
but since there have been other contributions since v110,
higan as a whole is still under GPLv3.

Where's the code?
-----------------

This repository contains two main branches.

  - [original] contains only code personally authored by byuu,
    released under the ISC licence.
    In the unlikely event that byuu returns to emulator development
    and publishes new versions of ares under the ISC licence,
    this branch will be updated to include those changes.

      - **Note:** The code released by byuu includes
        copies of the "angrylion" and "angrylion-plus" Nintendo 64 RDP cores.
        The default ares build does not include N64 support,
        but if you choose to enable it
        and include the angrylion code,
        the resulting program would *not* be under the ISC licence.

  - [with-fixes] adds small changes from other people,
    still under the ISC licence.

Like the main higan repository,
these branches include development history as far back as v068.
To go back further,
use the [bsnes history kit].

Contributing
------------

No contributions will be accepted to the "original" branch,
except from byuu himself.

Fixes will be accepted for the "with-fixes" branch,
as long as they are ISC licensed,
and demonstrably increase emulation accuracy,
code clarity,
or fix obvious typos, etc.

For larger-scale contributions,
refactorings,
architectural or user-interface improvements,
you are encouraged to contribute to the higan project,
or fork ares under a different, unrelated name.

[byuu]: https://byuu.org/about/
[higan]: https://github.com/higan-emu/higan
[original]: https://github.com/ares-emu/ares/tree/original
[with-fixes]: https://github.com/ares-emu/ares/tree/with-fixes
[bsnes history kit]: https://gitlab.com/higan/bsnes-history-kit/
