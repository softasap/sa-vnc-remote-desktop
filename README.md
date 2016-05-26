sa-vnc-remote-desktop
=====================

[![Build Status](https://travis-ci.org/softasap/sa-vnc-remote-desktop.svg?branch=master)](https://travis-ci.org/softasap/sa-vnc-remote-desktop)


Installs x11vnc server guardened by {{vnc_password}}



Example of use:

<pre>

     - {
         role: "sa-vnc-remote-desktop"
       }

</pre>

Advanced:

<pre>


     - {
         role: "sa-vnc-remote-desktop",
         vnc_password: "myverysecurevncpasswordyeah"
       }


</pre>


