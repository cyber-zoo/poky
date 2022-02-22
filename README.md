# Poky Fork

## Introduction

It's a fork of Yocto poky. Which URL: https://git.yoctoproject.org/poky/

As description in [Sync Action](.github/workflows/sync.yml), the sync action runs hourly with `master` branch and `all tags`.

## License of Poky

Different components of OpenEmbedded are under different licenses (a mix
of MIT and GPLv2). See LICENSE.GPL-2.0-only and LICENSE.MIT for further 
details of the individual licenses.

All metadata is MIT licensed unless otherwise stated. Source code
included in tree for individual recipes (e.g. patches) are under 
the LICENSE stated in the associated recipe (.bb file) unless 
otherwise stated.

License information for any other files is either explicitly stated 
or defaults to GPL version 2 only.

Individual files contain the following style tags instead of the full license 
text to identify their license:

    SPDX-License-Identifier: GPL-2.0-only
    SPDX-License-Identifier: MIT

This enables machine processing of license information based on the SPDX
License Identifiers that are here available: http://spdx.org/licenses/
