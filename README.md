# Wednesday


ln (Link Files)
The ln command is used to create links between files. Links can be hard links or symbolic (soft) links.

ln [options] target link_name
Examples:
Create a Hard Link:

ln file.txt hard_link.txt
Creates a hard link (hard_link.txt) that points to file.txt.
Create a Symbolic (Soft) Link:

ln -s /path/to/file.txt symbolic_link.txt
Creates a symbolic link (symbolic_link.txt) pointing to file.txt.
Check Links: Use ls -l to view links:

ls -l
 grep (Search Text in Files)
The grep command searches for a specific pattern in files.

Syntax:
grep [options] pattern [file...]
Examples:
Search for a Word in a File:

grep "word" file.txt
Search Recursively in All Files in a Directory:

grep -r "word" /path/to/directory
Search with Line Numbers:

grep -n "word" file.txt
Ignore Case:

grep -i "word" file.txt
Search for Exact Match:

grep -w "word" file.txt
locate (Find Files by Name)
The locate command searches for files using a pre-built index.

Examples:
Find a File:

locate filename
Case-Insensitive Search:

locate -i filename
Update the Database:


sudo updatedb
find (Search Files and Directories)
The find command searches for files and directories in real-time.

Syntax:

find [path] [options] [expression]
Examples:
Find a File by Name:

find /path/to/search -name "filename"
Find Files by Size:


find / -size +100M
Find Files Modified in the Last 7 Days:

find /path/to/search -mtime -7
Execute a Command on Found Files:


find /tmp -name "*.log" -exec rm {} \;
diff (Compare Files)
The diff command compares two files line by line.

Examples:
Compare Two Files:

diff file1.txt file2.txt
Side-by-Side Comparison:


diff -y file1.txt file2.txt
Ignore Whitespace Differences:


diff -w file1.txt file2.txt
du (Disk Usage)
The du command shows the disk usage of files and directories.

Examples:
Display Disk Usage of a Directory:

du /path/to/directory
Show Disk Usage in Human-Readable Format:

du -h /path/to/directory
Display Total Disk Usage of a Directory:

du -sh /path/to/directory
Show Disk Usage for All Subdirectories:

du -h /path/to/directory
df (Disk Free Space)
The df command shows the available and used disk space on the file system.

Examples:
Display Disk Usage:

df
Show Disk Space in Human-Readable Format:

df -h
Check Disk Usage for a Specific File System:

df /path/to/directory
Include File System Types:


df -T

