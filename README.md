# Digital Object Manager 

This plugin allows a user to create a Digital Object based on the metadata from a related Item record. It solves a problem we had at Denver where archivists were manually transcribing item-level metadata during the course of digitization activities, and (for us) removes the need to have native MODS export for archival object records.

It works by searching archival objects for the item you wish to digitize. It checks to see if digital objects are already attached to the item. The user can then either replace an existing Digital Object's metadata with the metadata in the item record, or attach a new Digital Object.

Things to do:
* Write the 'merge' action (it behaves slightly differently than the 'create' action)
* Accept a digitization date from user input instead of using the current system date

Questions? E-mail kevin.clair@du.edu.
