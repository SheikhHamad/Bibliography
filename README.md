# Bibliography
This project contains the full project bibliography as csl-json `SheikhHamad-Bibliography.json`. It may be used with Zotero or Mendeley. `SheikhHamad-Bibliography.rtf` gives you another downloadable and word-readable file of the data.

## Usage
The Bibliography is downloadable and usable in two ways:
* As Word-Doc`.rtf`-file exported with the style 'American Journal of Archaeology'
* As `.json`, to import it in your favorit Citation-Management-Program (e.g. Zotero, Mendeley).

## Contribute
If you like to contribute, create an issue or merge request.

## Standardizations
Before pushing or merging into this project, please remove any zotero or mendely internal ids from the exported json file. The `id` should be the same as the Z.Bibliog. No. in the short title or the call-number (signature). The export should be sorted by call-number. This is to avoid app specific data in the project.

Because Zotero cannot work with date ranges in the csl-object `issued`, these should be noted in the extra-field as `issued: year1/year2`. If possible, it can be transfered manually in the exported json file. Unfortunaly Zoteros import feature currently discards the second date in the csl-object `issued`.

After export, also a second file should be generated as word-readable .rtf with all entries with the style American Journal of Archaeology.

## Technical info
Json is compatible with csl-data. Cf. https://github.com/citation-style-language/schema.

## Contributors
Schech Hamad Project, FU-Berlin
* Anja Fügert
* Jens Rohde
* Janoscha Kreppner
* Konstantin Gnybek
* Hartmut Kühne
* Tobias Schmidt
