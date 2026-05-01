# Week 1: Essential Unix Commands for Genomics
Date: May 1, 2026
Course: Command Line Tools for Genomic Data Science (Coursera - JHU)

Today I practiced the core Linux commands that are essential for handling large genomic datasets, sequence files, and bioinformatics pipelines.

## 1. Directory Navigation & Exploration
- pwd: Print Working Directory (To see where I am).
- ls: List files in the current directory.
- cd: Change Directory (Move between folders).
- ls -lt: List files with details, sorted by time (newest first).

## 2. Wildcards & Pattern Matching
- *: Matches any string (e.g., ls *.fasta).
- ?: Matches any single character.
- []: Matches any character within the brackets (e.g., [atgc]).
- {}: Expands to match multiple patterns (e.g., *.{fastq,fasta}).

## 3. File & Directory Management
- mkdir: Create a new directory.
- cp: Copy files or directories.
- mv: Move or rename files.
- rm: Remove (delete) files.
- rm -i: Interactive remove (asks for confirmation before deleting).
- rmdir: Remove an empty directory.

## 4. Accessing & Viewing Content
- cat: Display the entire content of a file.
- more: View file content screen by screen.
- less: View file content with scrolling (better for large genomic files).
- head: View the first few lines of a file.
- tail: View the last few lines of a file.  
  
## 5. Querying & Summarizing Content
- wc: Word, line, and byte count.
- wc -l: Count number of lines (useful for counting sequences).
- wc -w: Count number of words.
- wc -c: Count number of bytes/characters.
- sort: Sort lines of text files.

## 6. Redirection & Piping
- <: Redirect input from a file.
- >: Redirect output to a file (overwrites).
- | (Piping): Passes the output of one command as input to another.

---
*Next Step: Practicing these commands on real FASTQ/SAM files.*
