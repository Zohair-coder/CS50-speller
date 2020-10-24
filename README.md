# Speller

A program that uses hashtable to check misspelled words in a text file from a dictionary. Sample text files and dictionaries to use for this program are available in the keys, texts, and dictionaries folder.

## Usage

```
./speller [DICTIONARY] textfile.txt
```
The program will output all the misspelled words, and the following at the end:
```
WORDS MISSPELLED:     
WORDS IN DICTIONARY:  
WORDS IN TEXT:        
TIME IN load:         
TIME IN check:        
TIME IN size:         
TIME IN unload:       
TIME IN TOTAL:        
```

## Example

```
./speller keys/lalaland.txt
```

For more information, go to: [CS50 pset5](https://cs50.harvard.edu/x/2020/psets/5/speller/)