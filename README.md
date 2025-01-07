# AD&D DMG (2011) Treasure Tables

These tables are from the __AD&D Dungeon Masters Guide__ Revised Edition 2011
and are formatted for the [tablator](https://github.com/crithead/tablator)
table library.

Some of the tables don't have a reference in the DMG so weights were assigned
in a way that seemed to make sense at the time.  Some liberties were taken with
the gems and jewelry tables to make them fit the capabilities of _tablator_
rather than adding seemingly unnecessary complexity.

The artifact and relic table is incomplete.  It is neat to dream about finding
(or placing) an artifact or relic in a game, but they don't really come up in
play very often.  It is something that the DM should probably hand craft.
Generating an item with multiple abilities like an artifact falls more into the
realm of an independent program that has more decision logic than comfortably
fits in the table library. The same thing can be said about tables for
intelligent swords and even spell scrolls.

## Tablator Examples

List the tables in _data-dir_

    tablator --data-dir add-dmg-2011-treasure --list

Print, then roll three times on the _potions_ table

    tablator --data-dir add-dmg-2011-treasure --print potions
    tablator --data-dir add-dmg-2011-treasure --number 3 potions

List and roll on the _lair-a_ table list

    tablator --data-dir add-dmg-2011-treasure lair-a --print
    tablator --data-dir add-dmg-2011-treasure lair-a
