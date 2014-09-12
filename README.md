# UPDATE
## Great news! node.js is now part of the synocommunity repository.
### [SynoCommunity](https://synocommunity.com/)


# synology-nodejs-bin

NodeJS binary builds for Synology DiskStation. Only two for the moment.

## node_88f6281_0.10.6-1.spk
NodeJS 0.10.6 cross-compiled for Marvell Kirkwood mv6282 (88f6282) and mv6281 (88f6281) based stations:

DS213air, DS213, DS112, DS112+, DS212j, DS212, DS212+, RS212, RS812, DS111, DS211, DS211+, DS411slim, DS411, RS411, DS413j, DS112j, DS211j, DS411j, DS110j, DS210j, DS410j, DS109, DS209, DS409, DS409slim, RS40

### HOWTO Use
1. Get package (use your git client or [download](https://rawgit.com/chesco-als/synology-nodejs-bin/master/node_88f6281_0.10.6-1.spk))
2. Log in to DSM > Package Center > Manuall Install

## mv6282_node-0.8.9
NodeJS 0.8.9 built on DS211+ (Marvell Kirkwood mv6282 1.6Ghz ARM (Marvell ARMADA 300)) with DSM 4.3.
It has to work on other mv6282-based models.

### HOWTO Use
1. Get package (use your git client or [download](https://rawgit.com/chesco-als/synology-nodejs-bin/master/mv6282_node-0.8.9.tar.gz))
2. Run commands `tar -xzf mv6282_node-0.8.9.tar.gz` `cd mv6282_node-0.8.9` `make install`


[What kind of CPU does my NAS have](http://forum.synology.com/wiki/index.php/What_kind_of_CPU_does_my_NAS_have)
