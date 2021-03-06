README
======

cloudraid-native
----------------

- 0.2-1: The split an merge interfaces do not require a keylength
  parameter any longer. The split interface addionally takes a base path
  from which is ignored for building the file hash. See
  src/de/dhbw/mannheim/cloudraid/jni/RaidAccessInterface.java for more
  information (2012-02-11)
- 0.1.1-1: Minor fixes (2012-02-11)
- 0.1-1: Initial version of the native CloudRAID RAID5 backend
  (2012-02-05)


hadoop0
-------

- 0.22.0-1: Initial Hadoop0 package similar to hadoop1-1.1.1-3 (2013-02-06)


hadoop1
-------

- 1.1.1-3: Since the start-all.sh script inside of Hadoop may cause weird
  constrains between running services (the jobtracker won't start, because the
  datanode hasn't been up when the jobtracker has been started), I added
  separate Systemd unit files for each Hadoop daemon. Since they somehow depend
  on each other, you can just start the tasktracker which will start all the
  other services as well (2013-02-06)
- 1.1.1-2: Small fixup regarding the SSH key pair handling (2013-02-03)
- 1.1.1-1: First attempt to make a system-wide Hadoop installation.
  (2013-02-03)


inyokaedit
----------

- 0.11.0-1 Update to latest stable (2013-10-04)
- 0.10.0-1 Update to latest stable; use qmake-qt4 (2013-07-16)
- 0.9.0-1 Update to latest stable (2013-04-26)
- 0.8.0-1 Update to latest stable (2013-01-27)
- 0.7.0-1 Update to latest stable (2012-11-10)
- 0.6.0-1 Update to latest stable (2012-09-07)
- 0.5.0-1 Update to latest stable (2012-07-21)
- 0.4.0-2 gcc and pkg-config must not be part of makedepends (2012-04-20)
- 0.4.0-1 New release (2012-04-20)
- 0.3.1-2 Install the desktop file (2012-03-09)
- 0.3.1-1 Update to 0.3.1. Changed the way the source code is downloaded from
  bazaar to simple tar.gz files.  (2012-03-08)
- 0.3.0-1 Update to 0.3.0 (2012-03-04)
- 0.2.0-5 Add conflicts information in order to support the inyokaedit-bzr
  package (2012-03-01)
- 0.2.0-4 Add wget to the dependencies for inyokaedit-0.2.0-4 (2012-02-28)
- 0.2.0-3 Remove the makefile patch to make the package build on i686
  (2012-02-28)
- 0.2.0-2 Small fixes and added missing dependency (2012-02-27)
- 0.2.0-1 initial version for the Inyoka markup offline editor
  (2012-02-27)


inyokaedit-bzr
--------------

- 20130716-1 Update to latest stable; use qmake-qt4 (2013-07-16)
- 20120907-1 Update to latest stable (2012-09-07)
- 20120721-1 Update to latest stable (2012-07-21)
- 20120420-2 gcc and pkg-config must not be part of makedepends (2012-04-20)
- 20120420-1 Add dependency to pkg-config (2012-04-20)
- 20120405-1 use the ``make install`` commmand (2012-04-05)
- 20120404-1 qmake detects the correct hunspell library (2012-04-04)
- 20120309-1 Install the desktop file (2012-03-09)
- 20120304-1 Adjust install commands to recent changes (2012-03-04)
- 20120301-2 Compress the man pages with highest compression rate
  (2012-03-01)
- 20120301-1 Initial version for the Inyoka markup offline editor build
  from trunk (2012-03-01)


nm-applet-icons-small
---------------------

- 0.1-2 Fix link (2013-01-31)
- 0.1-1 Initial version of the nm-applet-icons-small package. It creates the
  small 16x16 icons on-the-fly (2013-01-31)


taskd
-----

- 1.0.0-3 Initial really working version (2014-01-16)


znc-cap-sasl
------------

- 0.1-1: Initial version of the ZNC cap_sasl module (2012-02-21)
