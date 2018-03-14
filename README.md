# XT-IDE 8-Bit IDE Controller

[Glitch Works](http://www.glitchwrks.com/) continuing extension of the XT-IDE rev 2 ISA controller. This board, when used with a custom BIOS like the XT-IDE Universal BIOS, allows the use of modern 16-bit IDE devices on the 8-bit ISA bus.

More info on the Glitch Works project to provide boards, kits, and fully assembled units [can be found here](http://www.glitchwrks.com/xt-ide). A writeup on the rev 4 design process [is available here](http://www.glitchwrks.com/2017/11/23/xt-ide-rev4). 

If you're looking for the rev 3 branch, [it can be found here](https://github.com/glitchwrks/xt_ide/tree/rev_3). The README and related documentation have been preserved along with the design files.

### Jumper Settings

[modem7](http://minuszerodegrees.net/) created a great set of jumper diagrams for the rev 4 boards, available [on his site](http://www.minuszerodegrees.net/xtide/rev_4/XT-IDE%20Rev%204%20-%20general.htm) as well as in this Git repository:

* [IDE Jumper Settings](https://github.com/glitchwrks/xt_ide/blob/master/XT-IDE%20Rev%203%20-%20jumper%20configuration%20-%20IDE%20functionality.jpg)
* [ROM Jumper Settings](https://github.com/glitchwrks/xt_ide/blob/master/XT-IDE%20Rev%203%20-%20jumper%20configuration%20-%20optional%20boot%20rom.jpg)

### Bill of Materials

You can find a BOM with Mouser part numbers [here](https://github.com/glitchwrks/xt_ide/blob/master/bill_of_materials.md). Do note that you can purchase complete parts kits from [The Glitch Works](http://www.glitchwrks.com/xt-ide) in addition to bare PC boards.


### Slot 8 Support

If you want to use this card with an IBM 5160 PC/XT in Slot 8, you need a small daughterboard to make this happen. The project files for the board are available [on GitHub](https://github.com/glitchwrks/xt_ide_slot_8_support). You can find a writeup on the design and assembly process [here](http://www.glitchwrks.com/2017/02/03/slot-8-support). If you'd like to order a board, parts kit, or assembled module, see the [Glitch Works XT-IDE page](http://www.glitchwrks.com/xt-ide) for ordering information.

### Contributors

* Scott Christensen: inspriation 16-bit ATA interface for the 8-bit ISA bus
* Jeff Leyda/Hargle: original production board work, original BIOS work
* Andrew Lynch/N8VEM: layout work, initial group buy(s) on earlier revisions
* modem7: documentation, switch/jumper drawings

**Please contact me or send a pull request to get your name added to the list!**

There were no authors/contributors listed in the XT-IDE rev 2 schematics/board layout I started with. If you have contributed to this project and would like your name here, on the schematic, or on the board layout, please let me know. You can open an issue or submit a pull request.
