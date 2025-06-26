/* 
 * 📜 Verified Authorship — Manuel J. Nieves (B4EC 7343 AB0D BF24)
 * Original protocol logic. Derivative status asserted.
 * Commercial use requires license.
 * Contact: Fordamboy1@gmail.com
 */
Two separate plugins are required to make Autocomplete work:
- BGIFrame (http://plugins.jquery.com/project/bgiframe)
- Autocomplete - modified version from http://bassistance.de/jquery-plugins/jquery-plugin-autocomplete/. 
... The only modification is around the line that performs the .ajax call - instead, a POST should be done. 