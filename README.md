# Inventory Sorter Client

Actually Simple inventory sorting for Minecraft Forge.

**DOES NOT REQUIRE** installation on server.

_Why people call server-side-only mods "Simple" is a mystery to me._

## Features

Scroll wheel
> moves a single item from one inventory to another.

Middle mouse sorting
> Click the middle mouse button to sort the inventory from highest to least count. Uses item registry name to group similarly named items when the count is the same.

## Details

It only attempts to sort in the client, NOT delegating any work to the server.
This means it may be slower than other Mods.
It should work with all Vanilla containers, and tries to respect canExtract/isItemValid (it will avoid slots that are marked that way).

## License
This project is licensed according to GPL v3, see gpl-3.0.txt or https://www.gnu.org/licenses/gpl-3.0.en.html for more information.