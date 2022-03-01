### Table of Contents
[I. Learning the Shell](https://github.com/dtlancaster/linux-guide/blob/master/README.md#i-learning-the-shell)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[1. Navigation](https://github.com/dtlancaster/linux-guide/blob/master/README.md#1-navigation)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[1.1 `cd` Shortcuts](https://github.com/dtlancaster/linux-guide/blob/master/README.md#11-cd-shortcuts)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2. Exploring the System](https://github.com/dtlancaster/linux-guide/blob/master/README.md#2-exploring-the-system)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.1 Common `ls` Options](https://github.com/dtlancaster/linux-guide/blob/master/README.md#21-common-ls-options)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.2 `ls` Long Listing Fields](https://github.com/dtlancaster/linux-guide/blob/master/README.md#22-ls-long-listing-fields)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.3 `less` Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#23-less-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.4 Directories Found on Linux Systems](https://github.com/dtlancaster/linux-guide/blob/master/README.md#24-directories-found-on-linux-systems)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[3. Manipulating Files and Directories](https://github.com/dtlancaster/linux-guide/blob/master/README.md#3-manipulating-files-and-directories)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[3.1 Wildcards](https://github.com/dtlancaster/linux-guide/blob/master/README.md#31-wildcards)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[3.2 Commonly Used Character Classes](https://github.com/dtlancaster/linux-guide/blob/master/README.md#32-commonly-used-character-classes)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[3.3 Wildcard Examples](https://github.com/dtlancaster/linux-guide/blob/master/README.md#33-wildcard-examples)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[3.4 `cp` Options](https://github.com/dtlancaster/linux-guide/blob/master/README.md#34-cp-options)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[3.5 `cp` Examples](https://github.com/dtlancaster/linux-guide/blob/master/README.md#35-cp-examples)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[3.6 `mv` Options](https://github.com/dtlancaster/linux-guide/blob/master/README.md#36-mv-options)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[3.7 `mv` Examples](https://github.com/dtlancaster/linux-guide/blob/master/README.md#37-mv-examples)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[3.8 `rm` Options](https://github.com/dtlancaster/linux-guide/blob/master/README.md#38-rm-options)<br/>

# I. Learning the Shell

## 1. Navigation
`pwd` Print name of current working directory<br/>
`cd` Change directory<br/>
`ls` List directory contents

### 1.1 `cd` Shortcuts
<table>
  <tr>
    <td><b>Shortcut</b></td>
    <td><b>Result</b></td>
  </tr>
  <tr>
    <td>cd</td>
    <td>Changes the working directory to your home directory.</td>
  </tr>
  <tr>
    <td>cd -</td>
    <td>Changes the working directory to the previous working directory.</td>
  </tr>
  <tr>
    <td>cd ~<i>user_name</i></td>
    <td>Changes the working directory to the home directory of <i>user_name</i>. For example, typing cd ~<i>bob</i> will change the directory to the home directory of user "bob".</td>
  </tr>
</table>

## 2. Exploring the System
`ls` List directory contents<br>
`file` Determine file type<br/>
`less` View file contents

### 2.1 Common `ls` Options
<table>
  <tr>
    <td><b>Option</b></td>
    <td><b>Long option</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>-a</td>
    <td>--all</td>
    <td>List all files, even those with names that begin with a period, which are normally not listed (that is, hidden).</td>
  </tr>
  <tr>
    <td>-A</td>
    <td>--almost-all</td>
    <td>Like the -a option except it does not list . (current directory) and .. (parent directory).</td>
  </tr>
  <tr>
    <td>-d</td>
    <td>--directory</td>
    <td>Ordinarily, if a directory is specified, ls will list the contents of the directory, not the directory itself. Use this option in conjunction with the -l option to see details about the directory rather than its contents.</td>
  </tr>
  <tr>
    <td>-F</td>
    <td>--classify</td>
    <td>This option will append an indicator character to the end of each listed name. For example, it will append a forward slash (/) if the name is a directory.
  </tr>
  <tr>
    <td>-h</td>
    <td>--human-readable</td>
    <td>In long format listings, display file sizes in human-readable format rather than in bytes.</td>
  </tr>
  <tr>
    <td>-l</td>
    <td></td>
    <td>Display results in long format.</td>
  </tr>
  <tr>
    <td>-r</td>
    <td>--reverse</td>
    <td>Display the results in reverse order. Normally, ls displays its results in ascending alphabetical order.</td>
  </tr>
  <tr>
    <td>-S</td>
    <td></td>
    <td>Sort results by file size.</td>
  </tr>
  <tr>
    <td>-t</td>
    <td></td>
    <td>Sort by modification size.</td>
  </tr>
</table><br/>

```
-rw-r--r-- 1 root root 3576296 2017-04-03 11:05 Experience ubuntu.ogg
-rw-r--r-- 1 root root 1186219 2017-04-03 11:05 kubuntu-leaflet.png
-rw-r--r-- 1 root root 47584 2017-04-03 11:05 logo-Edbuntu.png
-rw-r--r-- 1 root root 44355 2017-04-03 11:05 logo-Kubuntu.png
-rw-r--r-- 1 root root 34931 2017-04-03 11:05 logo-Ubuntu.png
-rw-r--r-- 1 root root 32059 2017-04-03 11:05 oo-cd-cover.odf
-rw-r--r-- 1 root root 159744 2017-04-03 11:05 oo-derivatives.doc
-rw-r--r-- 1 root root 27837 2017-04-03 11:05 oo-maxwell.odt
```

### 2.2 `ls` Long Listing Fields
<table>
  <tr>
    <td><b>Field</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>-rw-r--r--</td>
    <td>Access rights to the file. The first character indicates the type of file. Among the different types, a leading dash means a regular file, while a d indicates a directory. The next three characters are the access rights for the file's owner, the next three are for members of the file's group, and the final three are for everyone else.</td>
  </tr>
  <tr>
    <td>1</td>
    <td>File's number of hard links.</td>
  </tr>
  <tr>
    <td>root</td>
    <td>The username of the file's owner.</td>
  </tr>
  <tr>
    <td>root</td>
    <td>The name of the group that owns the file.</td>
  </tr>
  <tr>
    <td>32059</td>
    <td>Size of the file in bytes.</td>
  </tr>
  <tr>
    <td>2017-04-03 11:05</td>
    <td>Date and time of the file's last modification.</td>
  </tr>
  <tr>
    <td>oo-cd-cover.odf</td>
    <td>Name of the file.</td>
  </tr>
</table>

### 2.3 `less` Commands
<table>
  <tr>
    <td><b>Command</b></td>
    <td><b>Action</b></td>
  </tr>
  <tr>
    <td>Page Up or b</td>
    <td>Scroll back one page</td>
  </tr>
  <tr>
    <td>Page Down or Space</td>
    <td>Scroll forward one page</td>
  </tr>
  <tr>
    <td>Up arrow</td>
    <td>Scroll up one line</td>
  </tr>
  <tr>
    <td>Down arrow</td>
    <td>Scroll down one line</td>
  </tr>
  <tr>
    <td>G</td>
    <td>Move to the end of the text file</td>
  </tr>
  <tr>
    <td>1G or g</td>
    <td>Move to the beginning of the text file</td>
  </tr>
  <tr>
    <td>/characters</td>
    <td>Search forward to the next occurrence of "characters"</td>
  </tr>
  <tr>
    <td>n</td>
    <td>Search for the next occurrence of the previous search</td>
  </tr>
  <tr>
    <td>h</td>
    <td>Display help screen</td>
  </tr>
  <tr>
    <td>q</td>
    <td>Quit less</td>
  </tr>
</table>

### 2.4 Directories Found on Linux Systems
<table>
  <tr>
    <td><b>Directory</b></td>
    <td><b>Commments</b></td>
  </tr>
  <tr>
    <td><i>/</i></td>
    <td>The root directory, where everything begins.</td>
  </tr>
  <tr>
    <td><i>/bin</i></td>
    <td>Contains binaries (programs) that must be present for the system to boot and run.</td>
  </tr>
  <tr>
    <td><i>/boot</i></td>
    <td>Contains the Linux kernel, initial RAM disk image (for drivers needed at boot time), and the boot loader. Interesting files include <i>/boot/grub/grub.conf</i>, or <i>menu.lst</i>, which is used to configure the boot loader, and <i>/boot/vmlinuz</i> (or something similar), the Linux kernel.</td>
  </tr>
  <tr>
    <td><i>/dev</i></td>
    <td>This is a special directory that contains <i>device nodes</i>. "Everything is a file" also applies to devices. Here is where the kernel maintains a list of all the devices is understands.</td>
  </tr>
  <tr>
    <td><i>/etc</i></td>
    <td>The <i>/etc</i> directory contains all the system-wide configuration files. It also contains a collection of shell scripts that start each of the system services at boot time. Everything in this directory should be readable text. While everything in <i>/etc</i> is interesting, here are some all-time favorites: <i>/etc/crontab</i>, a file that defines when automated jobs will run; <i>/etc/fstab</i>, a table of storage devices and their associated mount points; and <i>/etc/passwd</i>, a list of the user accounts.</td>
  </tr>
  <tr>
    <td><i>/home</i></td>
    <td>In normal configurations, each user is given a directory in <i>/home</i>. Ordinary users can write files only in their home directories. This limitation protects the system from errant user activity.</td>
  </tr>
  <tr>
    <td><i>/lib</i></td>
    <td>Contains shared library files used by the core system programs. These are similar to dynamic link libraries (DLLs) in Windows.</td>
  </tr>
  <tr>
    <td><i>/lost+found</i></td>
    <td>Each formatted partition or device using a Linxu file system, such as ext3, will have this director. It is used in the case of a partial recovery from a file system corruption event. Unless something really bad has happened to your system, this directory will remain empty.</td>
  </tr>
  <tr>
    <td><i>/media</i></td>
    <td>On modern Linux systems, the <i>/media</i> directory will contain the mount points for removable media such as USB drives, CD-ROMs, and so on, that are mounted automatically on insertion.</td>
  </tr>
  <tr>
    <td><i>/mnt</i></td>
    <td>On older Linux systems, the <i>/mnt</i> directory contains mount points for removable devices that have been mounted manually.</td>
  </tr>
  <tr>
    <td><i>/opt</i></td>
    <td>The <i>/opt</i> directory is used to install "optional" software. This is mainly used to hold commercial software products that might be installed on the system.</td>
  </tr>
  <tr>
    <td><i>/proc</i></td>
    <td>The <i>/proc</i> directory is special. It's not a real file system in the sense of files stored on your hard drive. Rather, it is a virtual file system maintained by the Linux kernel. The "files" it contains are peepholes into the kernel itself. The files are readable and will give you a picture of how the kernel sees your computer.</td>
  </tr>
  <tr>
    <td><i>/root</i></td>
    <td>This is the home directory for the root account.</td>
  </tr>
  <tr>
    <td><i>/sbin</i></td>
    <td>This directory contains "system" binaries. These are programs that perform vital system tasks that are generally reserved for the superuser.</td>
  </tr>
  <tr>
    <td><i>/tmp</i></td>
    <td>The <i>/tmp</i> directory is intended for the storage of temporary, transient files created by various programs. Some configurations cause this directory to be emptied each time the system is rebooted.</td>
  </tr>
  <tr>
    <td><i>/usr</i></td>
    <td>The <i>/usr</i> directory tree is likely the largest one on a Linux system. It contains all the programs and support files used by regular users.</td>
  </tr>
  <tr>
    <td><i>/usr/bin</i></td>
    <td><i>/usr/bin</i> contains the executable programs installed by your Linux distribution. It is not uncommon for this directory to hold thousands of programs.</td>
  </tr>
  <tr>
    <td><i>/usr/lib</i></td>
    <td>The shared libraries for the programs in <i>/usr/bin</i>.</td>
  </tr>
  <tr>
    <td><i>/usr/local</i></td>
    <td>The <i>/usr/local</i> tree is where programs that are not included with your distribution but are intended for system-wide use are installed. Programs compiled from source code are normally installed in <i>/usr/local/bin</i>. On a newly installed Linux system, this tree exists, but it will be empty until the system administrator puts something in it.</td>
  </tr>
  <tr>
    <td><i>/usr/sbin</i></td>
    <td>Contains more system administration programs.</td>
  </tr>
  <tr>
    <td><i>/usr/share</i></td>
    <td><i>/usr/share</i> contains all the shared data used by programs in <i>/usr/bin</i>. This includes things such as default configuration files, icons, screen backgrounds, sound files, and so on.</td>
  </tr>
  <tr>
    <td><i>/usr/share/doc</i></td>
    <td>Most packages installed on the system will include some kind of documentation. In <i>/usr/share/doc</i>, we will find documentation files organized by package.</td>
  </tr>
  <tr>
    <td><i>/var</i></td>
    <td>With the exception of <i>/tmp</i> and <i>/home</i>, the directories we have looked at so far remain relatively static; that is, their contents don't change. The <i>/var</i> directory tree is where data that is likely to change is stored. Various databases, spool files, user mail, and so forth, are located here.</td>
  </tr>
  <tr>
    <td><i>/var/log</i></td>
    <td><i>/var/log</i> contains <i>log files</i>, records of various system activity. These are important and should be monitored from time to time. The most useful ones are <i>/var/log/messages</i> and <i>/var/log/syslog</i>. Note that for security reasons on some systems, you must be the superuser to view log files.</td>
  </tr>
</table>

## 3. Manipulating Files and Directories
`cp` Copy files and directories<br/>
`mv` Move/rename files and directories<br/>
`mkdir` Create directories<br/>
`rm` Remove files and directories<br/>
`ln` Create hard and symbolic links

### 3.1 Wildcards
<table>
  <tr>
    <td><b>Wildcard</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>*</td>
    <td>Matches any characters</td>
  </tr>
  <tr>
    <td>?</td>
    <td>Matches any single character</td>
  </tr>
  <tr>
    <td>[<i>characters</i>]</td>
    <td>Matches any character that is a member of the set <i>characters</i></td>
  </tr>
  <tr>
    <td>[!<i>characters</i>]</td>
    <td>Matches any character that is not a member of the set <i>characters</i></td>
  </tr>
  <tr>
    <td>[[:<i>class</i>:]]</td>
    <td>Matches any character that is a member of the specified <i>class</i></td>
  </tr>
</table>

### 3.2 Commonly Used Character Classes
<table>
  <tr>
    <td><b>Character class</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>[:alnum:]</td>
    <td>Matches any alphanumeric character</td>
  </tr>
  <tr>
    <td>[:alpha:]</td>
    <td>Matches any alphabetic character</td>
  </tr>
  <tr>
    <td>[:digit:]</td>
    <td>Matches any numeral</td>
  </tr>
  <tr>
    <td>[:lower:]</td>
    <td>Matches any lowercase letter</td>
  </tr>
  <tr>
    <td>[:upper:]</td>
    <td>Matches any uppercase letter</td>
  </tr>
</table>

### 3.3 Wildcard Examples
<table>
  <tr>
    <td><b>Pattern</b></td>
    <td><b>Matches</b></td>
  </tr>
  <tr>
    <td>*</td>
    <td>All files</td>
  </tr>
  <tr>
    <td><i>g</i>*</td>
    <td>Any file beginning with <i>g</i></td>
  </tr>
  <tr>
    <td><i>b</i>*.txt</td>
    <td>Any file beginning with <i>b</i> followed by any characters and ending with <i>.txt</i></td>
  </tr>
  <tr>
    <td><i>Data</i>???</td>
    <td>Any file beginning with <i>Data</i> followed by exactly three characters</td>
  </tr>
  <tr>
    <td>[<i>abc</i>]*</td>
    <td>Any file beginning with either an <i>a</i>, <i>a b</i>, or <i>a c</i></td>
  </tr>
  <tr>
    <td><i>BACKUP</i>.[0-9][0-9][0-9]</td>
    <td>Any file beginning with <i>BACKUP</i>. followed by exactly three numerals</td>
  </tr>
  <tr>
    <td>[[:upper:]]*</td>
    <td>Any file beginning with an uppercase letter</td>
  </tr>
  <tr>
    <td>[![:digit:]]*</td>
    <td>Any file not beginning with a numeral</td>
  </tr>
  <tr>
    <td>*[[:lower:]123]</td>
    <td>Any file ending with a lowercase letter or the numerals <i>1</i>, <i>2</i>, or <i>3</i></td>
  </tr>
</table>

### 3.4 `cp` Options

<table>
  <tr>
    <td><b>Option</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>-a, --archive</td>
    <td>Copy the files and directories and all of their attributes, including ownerships and permissions. Normally, copies take on the default attributes of the user performing the copy.</td>
  </tr>
  <tr>
    <td>-i, --interactive</td>
    <td>Before overwriting an existing file, prompt the user for confirmation. <b>If this option is not specified, <i>cp</i> will silently (meaning there will be no warning) overwrite files.</b></td>
  </tr>
  <tr>
    <td>-r, --recursive</td>
    <td>Recursively copy directories and their contents. This option (or the -a option) is required when copying directories.</td>
  </tr>
  <tr>
    <td>-u, --update</td>
    <td>When copying files from one directory to another, only copy files that either don't exist or are newer than the existing corresponding files in the destination directory. This is useful when copying large numbers of files as it skips files that don't need to be copied.</td>
  </tr>
  <tr>
    <td>-v, --verbose</td>
    <td>Display informative messages as the copy is performed.</td>
  </tr>
</table>

### 3.5 `cp` Examples
<table>
  <tr>
    <td><b>Command</b></td>
    <td><b>Results</b></td>
  </tr>
  <tr>
    <td>cp <i>file1 file2</i></td>
    <td>Copy <i>file1</i> to <i>file2</i>. If <i>file2</i> exists, it is overwritten with the contents of <i>file1</i>. If <i>file2</i> does not exist, it is created.</td>
  </tr>
  <tr>
    <td>cp -i <i>file1 file2</i></td>
    <td>Same as previous command, except that if <i>file2</i> exists, the user is prompted before it is overwritten.</td>
  </tr>
  <tr>
    <td>cp <i>file1 file2 dir1</i></td>
    <td>Copy <i>file1</i> and <i>file2</i> into directory <i>dir1</i>. The directory <i>dir1</i> must already exist.</td>
  </tr>
  <tr>
    <td>cp <i>dir1</i>/* <i>dir2</i></td>
    <td>Using a wildcard, copy all the files into <i>dir1</i> into <i>dir2</i>. The directory <i>dir2</i> must already exist.</td>
  </tr>
  <tr>
    <td>cp -r <i>dir1 dir2</i></td>
    <td>Copy the contents of directory <i>dir1</i> to directory <i>dir2</i>. If directory <i>dir2</i> does not exist, it is created and, after the copy, will contain the same contents as directory <i>dir1</i>. If directory <i>dir2</i> does not exist, then directory <i>dir1</i> (and its contents) will be copied into <i>dir2</i>.</td>
  </tr>
</table>

### 3.6 `mv` Options
<table>
  <tr>
    <td><b>Option</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>-i, --interactive</td>
    <td>Before overwriting an existing file, prompt the user for confirmation. <b>If this option is not specified, mv will silently overwrite files.</b></td>
  </tr>
  <tr>
    <td>-u, --update</td>
    <td>When moving files from one directory to another, only move files that either don't exit or are newer than existing corresponding files in the destinatio directory.</td>
  </tr>
  <tr>
    <td>-v, --verbose</td>
    <td>Display informative messages as the move is performed.</td>
  </tr>
</table>

### 3.7 `mv` Examples
<table>
  <tr>
    <td><b>Command</b></td>
    <td><b>Results</b></td>
  </tr>
  <tr>
    <td>mv <i>file1 file2</i></td>
    <td>Move <i>file1</i> to <i>file2</i>. <b>If <i>file2</i> exists, it is overwritten with the contents of <i>file1</i></b>. If <i>file2</i> does not exist, it is created. <b>In either case, <i>file1</i> ceases to exist</b>.</td>
  </tr>
  <tr>
    <td>mv -i <i>file1 file2</i></td>
    <td>Same as the previous command, except that if <i>file2</i> exists, the user is prompted before it is overwritten.</td>
  </tr>
  <tr>
    <td>mv <i>file1 file2 dir1</i></td>
    <td>Move <i>file1</i> and <i>file2</i> into directory <i>dir1</i>. The directory <i>dir1</i> must already exist.</td>
  </tr>
  <tr>
    <td>mv <i>dir1 dir2</i></td>
    <td>If directory <i>dir2</i> does not exist, create directory <i>dir2</i> and move the contents of directory <i>dir1</i> into <i>dir2</i> and delete directory <i>dir1</i>. If directory <i>dir2</i> does exist, move directory <i>dir1</i> (and its contents) into directory <i>dir2</i>.</td>
  </tr>
</table>

### 3.8 `rm` Options
<table>
  <tr>
    <td><b>Option</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>-i, --interactive</td>
    <td>Before deleting an existing file, prompt the user for confirmation. <b>If this option is not specified, rm will silently delete files.</b></td>
  </tr>
  <tr>
    <td>-r, --recursive</td>
    <td>Recursively delete directories. This means that if a directory being deleted has subdirectories, delete them too. To delete a directory, this option must be specified.</td>
  </tr>
  <tr>
    <td>-f, --force</td>
    <td>Ignore nonexistent files and do not prompt. This overrides the --interactive option.</td>
  </tr>
  <tr>
    <td>-v, --verbose</td>
    <td>Display informative messages as the deletion is performed.</td>
  </tr>
</table>






