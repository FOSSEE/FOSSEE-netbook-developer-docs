Known Issues
============

The netbook Kernel is under rapid development. Few of the identified
issues have been listed here.


1. Switch user doesn't work if multiple users are logged in at the same time::

	No fix available as of now.

#. While 'logout', screen goes blank::

	In a terminal, or in a tty console(Ctl + Alt + F1):

	sudo rm /etc/lightdm/lightdm.conf.d/50-FOSSEE-LXDE.conf && sudo reboot

#. Codeblocks with simplecpp gives ``permission-denied``::

	sudo chmod -R a+rw /opt/simplecpp/

#. Wifi/Network icon at system tray is invisible(not missing) ::

	In '/etc/network/interfaces' comment out all lines and add the following

	auto lo
        iface lo inet loopback

	Save and exit.

	sudo service networking restart

#. HDMI not working::

        We are working on the device driver part, hopefully we might have it in next
        build

#. Webcam not working with any software::

	Webcam device drivers are not installed

#. Bluetooth mouse and keyboard are working but doesn't show up in the list
   of devices::

	True. It has least priority for now. But we will definitely address this issue

#. Video playback in fullscreen looses frames and its slow::

	This is due to missing VPU user space drivers. We are working on it

#. Cannot install ``blender``, it says missing EGL libraries::

	The non-free MALI GPU userspace drivers are not available for our platform device. We
	are trying to use LIMA, but this effort might take some time

#. No cursor in tty consoles


