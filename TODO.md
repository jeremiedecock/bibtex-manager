# TODO

- [ ] Parse bibtex file: convert Bibtex to Python structures (some libraries already exist for that)
- [ ] GUI: Tkinter ? GTK ? Qt (the best choice ? -> webkit, 2d, ...) ?
- [ ] Save bibtex file: convert the internal Python structure to Bibtex
- [ ] Set the default bibtex file in ~/.bibtex-manager.conf
- [ ] Set "title", "authors", "isbn", "doi", ..., "status", "keyword" (several possibles), "abstract", "pdf", "url", "cite", "citedin", "notes" (link to a document written by users and containing notes about the document), "tag" (several possibles), ... fields from the UI
- [ ] Add the "bm-format" command to "clean" bibtex files: sort items, sort fields, remove useless spaces, ...
- [ ] Download PDF function: requires url field, file name = SHA1 of its content + fill the "pdf" field (the download directory is set in ~/.bibtex-manager.conf
- [ ] Function to automatically get the number of citations of an article (to quickly see what interesting articles should be readed)
- [ ] Function to automatically fetch items fields with PyWAWA (requires one parser per website: google schoolar, IEEE, arxive, ...)
- [ ] Make Graphviz representation with "cite" and "citedin" fields + clic on nodes to get info, automatically make a new item, ... (to quickly see what interesting articles should be readed) ; label = item key (author year subject) + the number of citations ; use colors to distinguish readed items to unreaded items
- [ ] Add an option to export the bibliography in an interactive HTML document where graphs are displayed with 3d.js ? (would be great on personal web pages...)
- [ ] Import/Export to JSON
