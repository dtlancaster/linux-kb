### Table of Contents
[I. Learning the Shell](https://github.com/dtlancaster/linux-guide/blob/master/README.md#i-learning-the-shell)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[1. Navigation](https://github.com/dtlancaster/linux-guide/blob/master/README.md#1-navigation)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[1.1 `cd` Shortcuts](https://github.com/dtlancaster/linux-guide/blob/master/README.md#11-cd-shortcuts)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2. Exploring the System](https://github.com/dtlancaster/linux-guide/blob/master/README.md#2-exploring-the-system)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.1 Common `ls` Options](https://github.com/dtlancaster/linux-guide/blob/master/README.md#21-common-ls-options)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.2 `ls` Long Listing Fields](https://github.com/dtlancaster/linux-guide/blob/master/README.md#22-ls-long-listing-fields)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.3 `less` Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#23-less-commands)<br/>

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












