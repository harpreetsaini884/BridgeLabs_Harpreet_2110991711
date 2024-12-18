# Tuesday

Today i have practice and execute these command in the linux

df (Disk Free)
The df command shows the disk space usage of the file system.

Basic Usage:
df
This will display the disk usage for all mounted filesystems.

Human-Readable Format:


df -h
Displays sizes in a human-readable format (e.g., KB, MB, GB).

df /path/to/directory
du (Disk Usage)
The du command shows the disk usage of a directory and its contents.

Basic Usage:


du
This will show the disk usage of the current directory.

Human-Readable Format:

du -h
Summary of a Specific Directory:


du -sh /path/to/directory
The -s flag provides a summary, and the -h flag shows the size in a human-readable format.

Display Usage of All Subdirectories:

du -h /path/to/directory
Display Only Total Usage of All Files:

du -ch
diff (Compare Files)
The diff command compares the contents of two files line by line.

Basic Usage:

diff file1.txt file2.txt
This will show the differences between file1.txt and file2.txt.

Side-by-Side Comparison:

diff -y file1.txt file2.txt
Ignore Whitespace Differences:

diff -w file1.txt file2.txt
 locate (Find Files by Name)
The locate command is used to find files by their name, using a pre-built index database.

Basic Usage:

locate filename
This will search the index for files matching filename.

Update the Database:
The locate command relies on a database that needs to be updated manually:

sudo updatedb
Case-Insensitive Search:

locate -i filename
 find (Search Files in Directory Hierarchy)
The find command allows you to search for files and directories within a given directory hierarchy.

Basic Usage:

find /path/to/search -name "filename"
Search for Files by Type:
Find all directories:

find /path/to/search -type d
Search for Files Modified in the Last N Days:
Find files modified in the last 7 days:

find /path/to/search -mtime -7

Search for Files by Size:
Find files larger than 100MB:

find /path/to/search -size +100M

