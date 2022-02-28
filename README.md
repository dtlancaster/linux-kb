### Table of Contents
[I. Learning the Shell](https://github.com/dtlancaster/linux-guide/blob/master/README.md#i-learning-the-shell)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[1. Navigation](https://github.com/dtlancaster/linux-guide/blob/master/README.md#1-navigation)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[1.1 cd Shortcuts](https://github.com/dtlancaster/linux-guide/blob/master/README.md#1.1-cd-shortcuts)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2. Exploring the System](https://github.com/dtlancaster/linux-guide/blob/master/README.md#1-exploring-the-system)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.1 Common ls Options](https://github.com/dtlancaster/linux-guide/blob/master/README.md#2.1-common-ls-options)<br/>


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
</table>
















