Schematics for the ATD T512CLK-A1 derived from Rob Krenicki's board layout
==========================================================================

There may be errors. That said, I found none in Rob Krenicki's work. KiCad's ERC and DRC checks likely caught all important errors in my work.

Do not produce the PCB layout from this KiCad project. Placing of standard KiCad parts onto the board has resulted in insufficient track spacing for production. If you wish to make a board, use Rob Krenicki's gerbers.

**Data point of note:** the required clock chip appears to be a DS1216B or DS1216C. I have tested a DS1216C successfully. I believe either variant will work given that no chip will be fitted into the DS1216. Note that this clock chip is not the more typical DS1216E SmartWatch chip for which there are reproductions. I have designed, but not tested, a replacement here: https://github.com/JayesonLS/SmartWatchRedux . Alternatively, used DS1216B or DS1216C's are still readily available from eBay, etc. They likely have dead batteries and an external replacement battery can be retrofitted with some work. Google "DS1216 battery replacement".

Software for the ATD-20 (or DS1216-C) clock fitted to a T512CLK-A1 is available from here: http://www.minuszerodegrees.net/rtc/rtc.htm . Note that this sofware is not properly compatible with current dates, and so this clock module is not recommended for use. Instead, just use a DS1216-E or other Dallas SmartWatch replacement located in a ROM socket somewhere in the system.

More information on the T512CLK is available from Rob Krenicki's project: https://github.com/rkrenicki/Tandy1000-DMA-Upgrade
