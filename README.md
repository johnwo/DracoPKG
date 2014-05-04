DracoPKG
========

Package management service. A simple D-Bus frontend for libDracoPKG.

Requirements
============

 * libQtCore
 * libQtNetwork
 * libQtDBus
 * libQtXml
 * libDracoPKG

Build
=====

```
# qmake
# make
```

Install
=======

```
# qmake
# make install
```

 * Default installation path is /usr/local, you can override this with the PREFIX variable.
 * Default installation path for the D-Bus service and configuration file are /usr/share/dbus-1/system-services and /etc/dbus-1/system.d, you can override this with the DBUS_SERVICE and DBUS_CONF variables.
 * Default documentation path is PREFIX/share/doc/NAME-VERSION, you can override this with the DOCDIR variable.
 * INSTALL_ROOT is supported during install.

Usage
=====

DracoPKG will be started by D-Bus on-demand. Any D-Bus client will work, note that the default settings only allows members of the group "wheel" to use the service.

Links
=====

 * http://www.dracolinux.org
 * http://github.com/dracolinux
 * http://github.com/olear

License
=======

Copyright (c) 2014 Ole Andre Rodlie <olear@dracolinux.org>. All rights reserved.

DracoPKG is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License version 2.

DracoPKG is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

You should have received a copy of the GNU General Public License version 2 along with DracoPKG.  If not, see <http://www.gnu.org/licenses/>.