sa-vnc-remote-desktop
=====================

[![Build Status](https://travis-ci.org/softasap/sa-vnc-remote-desktop.svg?branch=master)](https://travis-ci.org/softasap/sa-vnc-remote-desktop)


Installs x11vnc server guardened by {{vnc_password}}



Example of use:
```YAML

     - {
         role: "sa-vnc-remote-desktop"
       }

```

Advanced:
```YAML
     - {
         role: "sa-vnc-remote-desktop",
         vnc_password: "myverysecurevncpasswordyeah"
       }
```

See box-example for standalone installation example

Remarks

1. Default vnc_password value is: 'vnc'.


Usage with ansible galaxy workflow
----------------------------------

2. If you installed the sa-vnc-remote-desktop rule using the command


`
   ansible galaxy install softasap.sa-vnc-remote-desktop
`

the role will be available in the folder library\softasap.sa-vnc-remote-desktop.
Please adjust the path accordingly.
```YAML

     - {
         role: "softasap.sa-vnc-remote-desktop",
         vnc_password: "myverysecurevncpasswordyeah"
       }

```


Copyright and license
---------------------

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)


