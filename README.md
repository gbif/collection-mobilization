# collection-mobilization
This repository is used to coordinate data mobilisation based on GRSciColl (https://www.gbif.org/grscicoll) entries. See the code used to create GitHub issues here: https://github.com/ManonGros/Small-scripts-using-GBIF-API/blob/master/create_github_issues_grscicoll_inst.ipynb

## Workflow

[to be defined/updated]

## Labelling guidelines

[to be defined/updated]

* Add the `registered publisher` label if the institution is registered on GBIF.
* Add the `Not registered as a publisher on GBIF` label if the institution is not registered as a GBIF publisher.
* Add the `some specimens in GBIF` label if the institution (or a third party) has already published some of the institution's specimens on GBIF.
    * Add the `published by third party` label if the institution has datasets that published by a third party.
    * Add the `unlinked occurrences` label when a search based on new information (codes, names) found published data not yet linked to the institution
* Add the `outside of GBIF scope` label if the institution has only collections that wouldn't fit in GBIF (like geology or archeology collections)
* Add the `pending collection verification` label if initial search shows no indication of collection curation.
* Add the `collection missing from GBIF` label if some of the collections aren't available on GBIF yet.
* Add the `some digitised specimens-metadata missing from GBIF` label if the institution has something almost like occurrences (scientific name, location, date) available like a database or online inventory for their specimens.
    * Add the `media available` label if the institutions has specimen-related media or is in the process of getting media (e.g. capturing images).
* Add the `contacted` label when an email is sent to the institutions for asking the willingness to mobilize data.
    * Add the `agree to mobilize data` label when the institution is contacted and agree to mobilize the data
* Add the `duplicate` label when an institution is a duplicate of a parent entry and are merged.
