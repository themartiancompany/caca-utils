..
   SPDX-License-Identifier: AGPL-3.0-or-later

   ----------------------------------------------------------------------
   Copyright © 2024, 2025  Pellegrino Prevete

   All rights reserved
   ----------------------------------------------------------------------

   This program is free software: you can redistribute it and/or modify
   it under the terms of the GNU Affero General Public License as published by
   the Free Software Foundation, either version 3 of the License, or
   (at your option) any later version.

   This program is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU Affero General Public License for more details.

   You should have received a copy of the GNU Affero General Public License
   along with this program.  If not, see <https://www.gnu.org/licenses/>.


===================
cacawrite
===================

----------------------------------------------------
Display ASCII pictures and save them into files
----------------------------------------------------
:Version: cacawrite |version|
:Manual section: 1


Synopsis
========

cacawrite *[options]* *in_file* *(out_file)*


Description
===========

Displays ASCII pictures using
cacaview from libcaca and optionally save
them to file, so de facto acting
as an encoder.

An Android it relies on the sdotool
in order to hide the software keyboard
when saving pictures.

Options
========

-h                      This message.
-c                      Enable color output
-v                      Enable verbose output


Bugs
====

https://github.com/themartiancompany/caca-utils/-/issues

Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.

See also
========

* libcrash-bash
* cacaview
* ascii-viewer
* asciiwrite
* aview
* picture-viewer
* sdotool

.. include:: variables.rst
