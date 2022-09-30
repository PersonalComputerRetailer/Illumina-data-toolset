# Illumina-data-toolset
## Basic Unin/Lunix commands
**Change directory**

`cd ..` Change to parent directory.

`cd ~` Change to home directory.

`cd /` Change to root directory.

`cd /user/abc` Change to `/user/abc` directory. This is absolute path, start from root.

`cd ../efg` Change to parent directory and enter `efg/` directory.

**Print working directory**

Type `pwd` ,then return `/home/ychen` on your screen. This is the command where you are. 

**Print list**

`ls` Print files in the current director. This is the command telling you what we have in the current director.

`ls -a` Print all files including hiden files.

`ls -l` Print files in long format. e.g.
```
$ ls -l
drwxr--r--   1 fjones editors     4096 Mar  2 12:52  drafts
-rw-r--r--   3 fjones editors    30405 Mar  2 12:52  edition-32
-r-xr-xr-x   1 fjones bookkeepers 8460 Jan 16  2022  edit.sh
```
The above example shows the "d" )(directory) or "-" (file) indicator, Unix file permission notation (R for read, W for write, X for execition), number of Hard_links (1 or 3). In the working directory the owner fjones has a directory named drafts, a regular file named edition-32, and an old executable named edit.sh

`ls -t -l` or `ls -lt` Print files in long format, sort the list by modification time.

**Copy file or directory**

`cp /home/ychen/abc.txt /home/achen/` Copy files from sourece (/home/ychen/abc.txt) to destination (/home/achen/).

`cp /home/ychen/zzz /home/achen/` Copy direcotry from sourece (/home/ychen/zzz) to destination (/home/achen/).

**Move/Rename file**

`mv /home/ychen/abc.txt /home/achen/` Move files (or directory) from sourece to destination.

`mv /home/ychen/abc.txt /home/ychen/zzz.txt` Change file name from abc.txt to zzz.txt.

**Remove file or directory** (***USE WITH CAUTION. IT CAN'T UNDO***. No recycle bin. Gone is gone.)

`rm abc.txt` Remove a file, abc.txt

`rm abc.txt def.pdf zzz.png` Remove multiple files.

`rm -r <directory>` Remove a directory.

**Make new directory**

`mkdir new_result` Create a new directory, named new_result.

**Create a empty file**
`touch test.txt` Create a emtpy file, named as test.txt.

## To use Conda
## Install packages viv Conda
## bcl2fastq
## Illumina run metrics
## fastqc
## multiqc
