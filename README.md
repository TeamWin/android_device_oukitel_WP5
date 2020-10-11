ACKNOWLEDGEMENTS: My thanks primarily to rokibhasansagar whose guide to building TWRP for MTK devices inspired this work, and for vital assistance along the way, including crucial patches and the use of his droid-builder tool (for the initial builds under 20.04 LTS) before reverting to Ubuntu Bionic. I also acknowledge chankruze whose WP1 tree provided a useful template. 

IMPORTANT NOTES: To avoid boot-loops, Android Verified Boot should be disabled (flash an empty vbmeta partition). Note also that it is not possible to decrypt the data partition, so press cancel on the main dialogue screen. Attempting to get round this, by reformatting the partition, effectively causes a factory reset and does not provide a permanent solution.

FURTHER DETAILS (regarding the build, acknowledgments, magisk etc.) may be found at https://github.com/dwastell/TWRP_Oukitel_WP5
