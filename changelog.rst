Changelog
=========

For more recent build information please look into this `document <https://docs.google.com/document/d/1GlHxnGjXo6N6AGHT71RDXDJRNaxNlgMYgO73MSdbtoo/edit?usp=sharing>`_

Build-1 (7 Oct 2014)
--------------------

* Added following packages on ubuntu-14.04.1 core rootfs(60MB compressed)::

   geany g++ gcc gedit libnotify-bin bc notify-osd gnome-time-admin thunderbird fbreader libreoffice python-pip scilab r-base r-cran-rcmdr r-mathlib expeyes gchempaint geogebra jmol texlive-base xsane octave emacs freemind inkscape scribus zim latex-beamer arduino ngspice celestia-gnome step kmplot tuxpaint marble pencil xfig gnuplot-x11 vlc mplayer chromium texworks scratch  audacity freeplane etoys sozi turtleart vim-gnome rsync mayavi2 guake python-pandas python-nose python-sympy spyder cython python-mpi4py git mercurial gitk meld xournal gnome-terminal kturtle tuxmath libav-tools audacious python-vte python-gtksourceview2 software-properties-common kazam mlocate

* Additional 3rd party packages::

   microhope, pheonix, learnbycoding

* Python pip packages::

   ipython pyzmq pygments tornado jinja2

* Fonts::

   EkMukta Fonts

Build-2 (10 Dec 2014)
---------------------

* Packages on top of Build-1::

    python-matplotlib lsof ttf-indic-fonts myspell-en-us lubuntu-software-center default-jdk python-visual gdb ace-of-penguins xboard florence orca language-selector-gnome ibus ibus-m17n m17n-contrib ibus-gtk3 ibus-qt4

* Packages removed::

    spyder freemind lxmusic

* Additional 3rd party packages::

   microhope pyqtgraph

* Fixed TimeZone and font cache

* Fixed ``ping`` and ``ifconfig`` permission denied issue


Build-3 (21 Jan 2015)
---------------------

* Packages on top of Build-2::

    codeblocks mtd-utils abootimg shutter imagemagik lshw gnome-screensaver lightdm-gtk-greeter smplayer lubuntu-dark-theme numix-bevel smplayer

* Packages removed::

    gnome-keyring motion puppet

* Custom themes and fonts

* Added Kernel 3.4.5 and associated modules

* Added support for WiFi wakeup after sleep

* Disabled wlan1 entry from ``udev`` and ``network-manager``


Build-4 (28 Jan 2015)
---------------------

* Packages on top of Build-3::

    firefox glade lxproxy pm-utils dmz-cursor-theme oxygen-cursor-theme pidgin filezilla bluefish

* Additional 3rd party packages::

    simplecpp jflap

* Changed console timeout from 10-minutes to 50-minutes

* Fit emacs window default size

* Guest user session enabled

* Any new user will have similar look and feel as of default student account

* Recording through microphone is possible

