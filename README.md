# cli-basics
Linux command line introduction
... I will make an introduction when I have time, until then here is some good to know commands


## Useful Shell Commands

```shell
$ pwd       # Print current working directory.
$ ls -la    # Print list of files (and directories) in the current directory.
            # The -l flag lists files vertically with details. The -a flag includes hidden files.
$ cd <path> # Change directory. Path can be absolute or relative.
            # To go back one directory use "cd ..". To go your home directory use "cd ~".
$ touch <file>      # Create a new file.
$ mkdir <dir>       # Create a new empty directory.
$ rm <file>         # Remove file.
$ rm -rf <dir>      # Removes a directory and everything within.
                    # The -r flag removes subdirectories recursively. The -f flag removes write protected files without prompt.
$ rmdir <dir>       # Only remove directory if empty.
$ mv <src> <dest>   # Move/rename file or directory.
$ cp <src> <dest>   # Copy file.
$ cp -r <src> <dest>        # Copy directory. The -r flag copies subdirectories recursively.
$ find . -name "foo*.txt"   # Searches the current and all subdirectories for file names starting with "foo" and ending with ".txt".
$ grep -r foo       # Searches the current and all subdirectories for files containing within them the text "foo".
$ cat <file>        # Print contents of text file. To only print the 10 first/last lines use head/tail command instead of cat.
```
