# TiMidity++ -- MIDI to WAVE converter and player
# Copyright (C) 1999-2002 Masanao Izumo <mo@goice.co.jp>
# Copyright (C) 1995 Tuukka Toivonen <tt@cgs.fi>
#
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2 of the License, or
# (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software
# Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA

include $(top_srcdir)/common.makefile.in

BITMAPS = \
	arrow.xbm \
	back.xbm \
	check.xbm \
	fast.xbm \
	fwrd.xbm \
	keydown.xbm \
	keyup.xbm \
	off.xbm \
	on.xbm \
	next.xbm \
	pause.xbm \
	play.xbm \
	prev.xbm \
	quit.xbm \
	slow.xbm \
	stop.xbm \
	random.xbm \
	repeat.xbm \
	timidity.xbm

EXTRA_DIST = $(BITMAPS)

install.bitmaps: $(BITMAPS)
	test -d $(DESTDIR)$(BITMAP_DIR) || mkdir -p $(DESTDIR)$(BITMAP_DIR)
	for f in $(BITMAPS) ''; do case ".$$f" in .);; *) $(INSTALL) -m 644 $$f $(DESTDIR)$(BITMAP_DIR);; esac; done
