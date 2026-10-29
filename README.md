# Sony Xperia 5 III headphone gain boost for magisk


**Only for Sony Xperia 5 III running LineageOS 21.0**

Changes values in `/vendor/etc/audio/sku_lahaina/mixer_paths.xml` for RX_Digital_Volume in order to set the "master" volume for headphone out (3.5mm jack) to "84".
After that, every individual volume step will scale accordingly.
This value has been well tested to not cause any distortions at max. volume.



## Requirements
- Sony Xperia 5 III (pdx214) running LineageOS 21.0 rooted via Magisk.


