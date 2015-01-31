Known Issues
============

The netbook Kernel is under rapid development. Few of the identified
issues have been listed here.


1. Switch user doesn't work if multiple users are logged in at the same time::

   No fix available as of now.

#. When logout, screen goes blank::

   sudo rm /etc/lightdm/lightdm.conf.d/50-FOSSEE-LXDE.conf && sudo reboot

#. Wifi/Network icon at system tray is invisible(not missing)::

   Click on the empty space next to battery icon and select any available network
   and attempt to connect. Once connected, the network icon will appear from next
   boots

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


