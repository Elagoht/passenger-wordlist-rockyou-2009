# Passenger Wordlist Repository: Rock You 2009

This repository contains the Rock You 2009 wordlist, which is a collection of passwords that were leaked from the Rock You 2009 database. But in a special format. Tinkered to be used with Passenger Passphrase Manager.

## Format

All passwords grouped by character count to separate files and sorted alphabetically to optimize for binary search. All files named according to the character count following by ".ticket" extension.

## Metadada

This repository has a `metadata.json` file that contains information about the wordlist.

Fields:

- `displayName`: The name of the wordlist.
- `slug`: Will be used to determine the directory to download the wordlist.
- `year`: The year of the wordlist.
- `source`: The source of the wordlist Not to be used for anything else than credits.
- `repository`: The git repository to be cloned to get the wordlist.
- `description`: The description of the wordlist.
- `publishedBy`: The original author of the wordlist.
- `adaptedBy`: The person who adapted the wordlist for this repository.
- `minLength`: The minimum length of the passwords in the wordlist.
- `maxLength`: The maximum length of the passwords in the wordlist.
- `totalFiles`: The total number of files in the wordlist.
- `totalPasswords`: The total number of passwords in the wordlist.
- `size`: The size of the wordlist on disk.
- `sizeUnits`: The unit of the size of the wordlist on disk.