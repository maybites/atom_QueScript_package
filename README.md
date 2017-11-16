# QueScript-atom-package

QueScript package for the Atom editor associating the 'que' file extension with the QueScript [grammar](https://github.com/maybites/Lib_QueScript/wiki/QS-Reference) for validation and autocomplete.

## Structure

### grammars/quescript.cson

The QueScript grammar with the scope name `text.xml.quescript` specifying the extension `.que`

### schemata/quescript.xsd

the schema used for validation and autocomplete

### settings/quescript.cson

A settings file providing a rule to associate the schema at `schemata/quescript.xsd` with the grammar scope `text.xml.quescript`

### test/test.que

A test QueScript file

### package.json

## Installation

This package is not published in the Atom Package Repository. 

* install package [linter-autocomplete-jing](https://github.com/aerhard/linter-autocomplete-jing) and its dependencies under Atom > Settings.
* install package [xml-common-schemata](https://atom.io/packages/xml-common-schemata) under Atom > Settings.
* clone this project from GitHub and place it inside the `.atom/packages` - folder
* run `apm link` inside the terminal from the project's root directory.

 

## Notes

nope, no notes yet.
