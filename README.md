sa-vnc-remote-desktop
=====================

[![Build Status](https://travis-ci.org/softasap/sa-vnc-remote-desktop.svg?branch=master)](https://travis-ci.org/softasap/sa-vnc-remote-desktop)


Installs x11vnc server guardened by {{vnc_password}}



Example of use:
```

     - {
         role: "sa-vnc-remote-desktop"
       }

```

Advanced:
```
     - {
         role: "sa-vnc-remote-desktop",
         vnc_password: "myverysecurevncpasswordyeah"
       }
```

Remarks
1. Default vnc_password value is: 'vnc'.
2. If you installed the sa-vnc-remote-desktop rule using the command


`
   ansible galaxy install softasap.sa-vnc-remote-desktop
`

the role will be available in the folder library\softasap.sa-vnc-remote-desktop.
Please adjust the path accordingly.
```

     - {
         role: "softasap.sa-vnc-remote-desktop",
         vnc_password: "myverysecurevncpasswordyeah"
       }

```
