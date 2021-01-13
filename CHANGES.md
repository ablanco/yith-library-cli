# Changelog

## 0.3.1

- Fix version number in the command line tool.

## 0.3.0

- Add an option to export the file in the Bitwarden format.

## 0.2.2

- Keep `extra` field when importing Lastpass entries. Previous
  versions were overwriting `extra` with the `url` field. This fix
  concatenates `url` and `extra` into Yith Library's `notes` field.

## 0.2.1

- Document --import-lastpass in README.

## 0.2.0

- Added support to read an exported csv from LastPass and convert it to Yith
  Library's backup format.

## 0.1.2

- Be able to search, read and decrypt Yith Library's backups.
