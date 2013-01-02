The Date AJAX update module adds a Field formatter allowing privileged users to
update a Date field via a customizable AJAX update link on any Entity.

Date AJAX update was written and is maintained by Stuart Clark (deciphered).
- http://stuar.tc/lark
- http://twitter.com/Decipher

Date AJAX update was originally an entry in The Module Off module development
competition.



Features
--------------------------------------------------------------------------------

- AJAX update formatter for standard Date field types:
  - Formatter settings:
    - Update settings:
      - Link text - Change the text for the AJAX update link.
      - Value to set - Value to change the date field to (Now or relative).
    - Display settings:
      - Formatter - Date field formatter to process the date fields output
        alongside the AJAX update link.
  - Support for multi-field date fields.
  - Entity type agnostic.
- Example feature.



Setup
--------------------------------------------------------------------------------

1. Install and enable the module and it's dependencies.
2. Add a Date field to an Entity Bundle (Node content type, etc).
3. Set the Display for the newly added Date field to use the 'AJAX update'
   formatter and configure appropriately.
