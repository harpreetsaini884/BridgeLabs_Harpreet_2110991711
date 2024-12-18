# Monday
Today i have done the basic command of Linux File System -

File and Directory Navigation
pwd
Prints the current working directory.

pwd
ls
Lists files and directories in the current directory.

ls
ls -l       # Long format with detailed info
ls -a       # Show hidden files (starting with .)
ls -lh      # Human-readable file sizes

cd
Changes the current directory.

cd /path/to/directory  # Go to a specific directory
cd ~                   # Go to the home directory
cd ..                  # Move one directory up
cd -                   # Go to the previous directory

touch
Creates an empty file.

touch filename.txt
cat
Displays the content of a file.

cat filename.txt
cp
Copies files or directories.

cp source.txt destination.txt
cp -r /source/dir /destination/dir  # Recursive copy for directories
mv
Moves or renames files or directories.

mv oldname.txt newname.txt  # Rename a file
mv file.txt /new/directory  # Move a file
rm
Deletes files or directories.

rm file.txt                  # Delete a file
rm -r directory/             # Delete a directory and its contents
rm -i file.txt               # Prompt before deletion
Directory Operations
mkdir
Creates a new directory.

mkdir new_directory
mkdir -p parent/child        # Create parent and child directories
rmdir
Removes an empty directory.

rmdir directory_name
File Viewing and Searching
less
Displays file content one screen at a time.

less filename.txt
head
Displays the first few lines of a file.

head filename.txt
tail
Displays the last few lines of a file.

tail filename.txt
tail -f filename.txt        # Monitor file in real-time (e.g., logs)
find
Searches for files and directories.

find /path -name filename.txt
