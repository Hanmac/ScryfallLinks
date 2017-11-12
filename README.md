# ScryfallLinks

ScryfallLinks is a [MediaWiki extension](https://www.mediawiki.org/wiki/Manual:Extensions) that creates [Scryfall](https://scryfall.com/) links from [*Magic: The Gathering*](https://magic.wizards.com/) card names.

It is designed to be backwards-compatible with the [MTG Wiki](https://mtg.gamepedia.com)'s "MTGSCards" extension.

It is based on https://www.mediawiki.org/wiki/Extension:BoilerPlate.

It makes use of the [Scryfall API](https://scryfall.com/docs/api/images) to load images, and [OOjs popups](https://doc.wikimedia.org/oojs-ui/master/js/#!/api/OO.ui.PopupWidget), which are native to MediaWiki.

Running `npm test` and `composer test` will run automated code checks.

If you want to hack on this, whatever you're looking for is probably in `extension.json`, or `/modules`, or `/src`.
