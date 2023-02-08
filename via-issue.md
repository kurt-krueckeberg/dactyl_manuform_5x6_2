# Description of  `Dactyl/Manuform 5x6 2` Keyboard Via Problem

Four (of the five) left-hand side thumb keys do not work correctly. Their key mappings are wrong. They differ from those displayed by the Via Configurator.

Via CONFIGURE shows these mappings for the cluster of the four thumb keys that are `Home`, `End`, `Bksp` 
and \` (the backtick whose uppercase is the tilde character):

![Left side configure](/assets/left-side-configure.jpg)

However, actual key mappings are rotated clockwise one position from those shown on the Via CONFIGURE screen. The actual key mappings, as confirmed by the Via KEY TESTER, are:

|           |      |      |
| --------- |------|------|
| MO(2)     | Tab  | Home |
|           | `    | Bksp |

Re-flashing the keyboard with the Via firmware file [handwired_dactyl_manuform_5x6_5_via.hex](https://www.caniusevia.com/docs/download_firmware#0) from <https://www.caniusevia.com/docs/download_firmware> did not help. The problem persists. Nor can you use the Via Configurator to reassign the keys.

## Description of Files in This Repository

* `handwired_dactyl_manuform_5x6_5_via.hex` is the Via firmware file [handwired_dactyl_manuform_5x6_5_via.hex](https://www.caniusevia.com/docs/download_firmware#0) from <https://www.caniusevia.com/docs/download_firmware>

* `handwired_dactyl_manuform_5x6_default_kb2040.uf2` is the firmware file from the keyboard seller  [CustomErgoBoards](https://www.etsy.com/shop/CustomErgoBoards) on Etsy. It is the original firmware that came with the jeyboard.
