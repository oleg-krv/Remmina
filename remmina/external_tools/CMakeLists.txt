# desktop/remmina - The GTK+ Remote Desktop Client
#
# Copyright (C) 2011 Marc-Andre Moreau
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
# Foundation, Inc., 59 Temple Place, Suite 330,
# Boston, MA 02111-1307, USA.

set(EXTERNAL_TOOLS_DIR "$ENV{HOME}/.remmina/external_tools")

file(MAKE_DIRECTORY ${EXTERNAL_TOOLS_DIR})

INSTALL(PROGRAMS launcher.sh pause.sh remmina_filezilla_sftp.sh remmina_filezilla_sftp_pki.sh remmina_nslookup.sh remmina_ping.sh remmina_traceroute.sh DESTINATION ${EXTERNAL_TOOLS_DIR})

