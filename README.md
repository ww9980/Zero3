# Zero3

This is a config file for LinuxCNC using Heiz Stepper Control Zero 3 + HIGH-Z S-400T.

`C` port (4th axis control) is not used in this config.
`X` is inverted by default.

Please check the `resolution switch` in your Zero 3. It can either be `10 microsteps` or `5 microsteps`. More details can be found on page 15 of this document: http://www.prototools.co.uk/shop/download/media/controller/zero3.pdf

Emergency stop pin is not enabled. If needed, please specify it to parallel port number `11`.

Please put the files to `/home/username/linuxcnc/configs/`



Created on 20 April 2016
By Anton Grounds and Weikang Fan
