# QuietOCR

## Description

OCR script for OSX

This script is designed to OCR one file at a time. It can be used to do a directory by specifying -a, but will run differently ./quietOCR.sh -a <fullDirectoryPath>. If you want to get the text by itself, run it with the -n parameter after -a (or first for single file).

## Examples:

Single file with searchable text
> $0 myFile.pdf 
 
Keeps original file and creates a new file with text from document
> $0 -n myFile.pdf

Makes all of the files in the current working directory searchable
> $0 -a pwd
 
Makes all of the files in the documents directory searchable
> $0 -a /home/$USER/Documents/
 
creates text documents with the words from all of the files from the current directory
> $0 -a -n pwd
