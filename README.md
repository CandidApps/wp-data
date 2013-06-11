wp-data
==============================================================================

Command line utility for exporting and importing the WordPress database.

The main intention for this was to manage a local WordPress setup across
multiple machines with their own local database. Theortically you could use
this for production but I'm not sure how optimised the methods are.


Usage
------------------------------------------------------------------------------

Drop the file into the root of your WordPress setup. In the terminal, head to
the root where drop the file and you execute the following commands.

Export the whole database

    php wp-data export
    
Import the exported data

    php wp-data import
