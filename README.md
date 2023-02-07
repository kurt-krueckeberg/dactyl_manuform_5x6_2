# viaqmk\_firmware\_files

## Description of Files

* `handwired_dactyl_manuform_5x6_5_via.hex` is the Via firmware file [handwired_dactyl_manuform_5x6_5_via.hex](https://www.caniusevia.com/docs/download_firmware#0) from <https://www.caniusevia.com/docs/download_firmware>

* `handwired_dactyl_manuform_5x6_default_kb2040.uf2` is the firmware file from the keyboard seller  [CustomErgoBoards](https://www.etsy.com/shop/CustomErgoBoards) on Etsy. It is the original firmware that came with the jeyboard.

## Description of Keyboard Problemgit pull

Four (of the five) left-hand side thumb keys do not work correctly. Their key mappings are wrong. The actual key mappings do not match those shown by the Via application's Configurator. 

Via CONFIGURE shows these mappings for the cluster of the four thumb keys that are `Home`, `End`, `Bksp` 
and \` (the backtick whose uppercase is the tilde character):

![Left side configure](/assets/left-side-configure.jpg)

However, actual key mappings are rotated clockwise one position from those shown on the Via CONFIGURE screen. The actual key mappings, as confirmed by the Via KEY TESTER, are:

|           |      |      |
| --------- |------|------|
| MO(2)     | Tab  | Home |
|           | `    | Bksp |

Re-flashing the keyboard with the Via firmware file [handwired_dactyl_manuform_5x6_5_via.hex](https://www.caniusevia.com/docs/download_firmware#0) from <https://www.caniusevia.com/docs/download_firmware> did not help. The same problem results.

Nor can you use the Via Configurator in the normal way to reassign the keys.

All this suggests there is a problem with the hardware.