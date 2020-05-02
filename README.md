# Less tools
**(Pun intended)**
Basic css snippets usually used in every project.
Written in less(?!).

## Usage
- `.reset-list;`
- `.init-pseudo;`
- `.clear;`

### Reset lists
Remove default list spacing and icon by adding `.reset-list;`

### Initialize pseudo-elements
Makes pseudo-elements functional by setting the css rule: `content: "";` when `.init-pseudo;` is added.

### Clearfix
The good old clearfix that we all know and love. Add `.clear;` to the parent of the floating elements and you are good to go. Adds the css rule `clear: both;` to the pseudo element `::after` of the parent element.
