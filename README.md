# Alfred-Wiki
A handful of Alfred commands for editing Wikipedia

This workflow provides a couple of useful aliases for Wikipedia editors. By default it uses English Wikipedia, but this can be changed by altering the URLs in the workflow.


1. `[[<query>` will open the Wikipedia page named `<query>`. This may seem lopsided, but in my experience it's incredibly intuitive, as it uses the same syntax as a wikilink when editing. If there isn't a page with that exact name, this will take you to the appropriate search results page.
	- `[[asian elephant` => `en.wikipedia.org/wiki/Asian_elephant`
	- `[[vespid wasp` => `en.wikipedia.org/wiki/Vespidae`
	- `[[pollen vector` => `en.wikipedia.org/w/index.php?search=pollen%20vector`
	
2. `ww` will quickly open your watchlist.

3. `{{<query>` will open the Wikipedia template page named `<query>`. This command is case-insensitive and will fail if given a nonexistent page.
	- `{{re` => `en.wikipedia.org/wiki/Template:Reply_to`


4. `WP:<query>` will take you to the relevant shortcut page, without requiring the `[[`command. This command is case-insensitive and will fail if given a nonexistent page.
	- `wp:5p` => `en.wikipedia.org/wiki/Wikipedia:Five_pillars`

5. `MOS:<query>`does the same as `WP:<query>`, but with MOS: pages.
	- `mos:genderid` => `en.wikipedia.org/wiki/Wikipedia:Manual_of_Style#Gender_identity`
