# Lab database revamp

The lab I am working in has a very basic HTML based plasmid database. I want to use this opportunity to rewrite it with a few more features. For me this is just a project to learn HTML/CSS and Javascript.

## Features

1. A basic overview of the plasmid information:

   | Information        | Description                                   |
   | ------------------ | --------------------------------------------- |
   | clone number       | ID of the plasmid in the database             |
   | vector             | Parent vector                                 |
   | construct          | Inserted construct                            |
   | promotor           | Promotor that drives the construct expression |
   | resistance         | Antibiotic resistance marker                  |
   | date of creation   | Date of creation                              |
   | provider           | Scientist/Company that created the plasmid    |
   | plasmid map        | Serial cloner file with plasmid map           |
   | datasheet          | PDF file with additional information          |
   | vector information | additional information txt file               |
   | Comment            | Any short comment                             |

2. Sorting the plasmids into different categories
3. A form to add new entries to the database
4. (optional) everything saved in an SQLite database
