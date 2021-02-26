Schematics for the ATD T512CLK-A1 derived from Rob Krenicki's board layout
==========================================================================

There may be errors, however, I found none in Rob Krenicki's work. KiCad's ERC and DRC checks likely caught all important errors in my work.

Do not produce the PCB layout from this KiCad project. Placing of standard KiCad parts onto the board has resulted in insufficient track spacing for production. If you wish to make a board, use Rob Krenicki's gerbers.

**Data point of note:** the required clock chip appears to be a DS1216B or DS1216C. I believe either variant will work given that no chip will be fitted into the DS1216. Note that this clock chip is not the more typical DS1216E SmartWatch chip for which there are reproductions. I don't know of any DS1216B or DS1216C reproduction. I may design one specifically intended for this board. In the mean time, old, used DS1216B or DS1216C's are still readily available from eBay, etc., and an external battery retrofitted with some work. Google "DS1216 battery replacement". If you are able to confirm that one of these clock chips does work, please let me know. 

More information on the T512CLK is available from Rob Krenicki's project: https://github.com/rkrenicki/Tandy1000-DMA-Upgrade
