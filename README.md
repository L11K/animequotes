# animequotes

Anime Quotes for Node.


## Usage

 ```javascript
const animeQuotes = require("animequotes");

// Get Random Quote
console.log(animeQuotes.randomQuote());

// Get Quote by ID
console.log(animeQuotes.getQuote(1));

// Get Quotes by Anime
console.log(animeQuotes.getQuotesByAnime("Naruto"));

// Get Quotes by Character
console.log(animeQuotes.getQuotesByCharacter("Itachi Uchiha"));
```


## Example Object

```json
{
"quote": "The ones who aren't able to acknowledge their own selves are bound to fail.",
"anime": "Naruto",
"id": 5350,
"name": "Itachi Uchiha"
}
```


## License

 - **MIT** : http://opensource.org/licenses/MIT
