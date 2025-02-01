# notesConverter
converts any .html file in a specified folder into a .txt file and combines all single
.txt files into one big text file. Afterwards this script will split the big text file
into splitted small files which you can import at 'Notebook LM' or any other LLM as
data sources. 

# Use Case Scenario 1
## Self Analysis
If you save all your 'Apple Notes' and/or 'Google Keep Notes' as .html files somewhere in
a folder, this script can convert the exported .html notes to plain text files. Import
these combined and cleaned .txt files as source to 'Notebook LM' to get a private database 
of your thoughts, memories and everything you ever stored as note. You can use it for analyzing
or asking questions about your self or whatever you have in mind.

# notesConverter Requirements
A folder with .html files. These .html files must contain notes or text.

# Requirements
- lynx

# Usage
```bash
notesConverter <path/to/html/files> <2M,2000KB,2G>
notesConverter ~/Downloads/exportedNotes 2M
(will split the output.txt into 2MB files)
```
