# nush-pos-data
Programme of Studies data in JSON format, generated using Walnit's [nushPOSextractor tool](https://github.com/Walnit/nushPOSextractor) and converted from CSV to JSON using [csvjson.com/csv2json](https://csvjson.com/csv2json).
The POS itself in PDF format is available on the [school website](https://www.nushigh.edu.sg/studying-at-nus-high/the-nus-high-diploma/programme-of-studies/
).

The contents.json file is a list of all the years for which POS data is present in the repo.

*Note: I modified the nushPOSextractor tool slightly to account for some module errors (and ended up modifying one piece of module source code), but the tool itself might/should still work*

---

Content served through GitHub Pages at [gohjy.github.io/nush-pos-data/data/[YEAR]/pos.json](https://gohjy.github.io/nush-pos-data/data/2030/pos.json) for the edited files (fixing any whitespace issues and the like), and [gohjy.github.io/nush-pos-data/data/[YEAR]/raw.json](https://gohjy.github.io/nush-pos-data/data/2030/raw.json) for the raw, unedited JSON output.

Due to the extremely infrequent nature of POS updates, you may want to consider downloading a copy and hosting it locally instead to save on both our bandwidths.
