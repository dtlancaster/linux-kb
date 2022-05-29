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
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[3.9 `rm` Examples](https://github.com/dtlancaster/linux-guide/blob/master/README.md#39-rm-examples)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4. Working with Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#4-working-with-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.1 Man Page Organization](https://github.com/dtlancaster/linux-guide/blob/master/README.md#41-man-page-organization)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[4.2 `info` Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#42-info-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[5. Redirection](https://github.com/dtlancaster/linux-guide/blob/master/README.md#5-redirection)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[6. Seeing the World as the Shell Sees it](https://github.com/dtlancaster/linux-guide/blob/master/README.md#6-seeing-the-world-as-the-shell-sees-it)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[6.1 Arithmetic Operators](https://github.com/dtlancaster/linux-guide/blob/master/README.md#61-arithmetic-operators)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[6.2 Backslash Escape Sequences](https://github.com/dtlancaster/linux-guide/blob/master/README.md#62-backslash-escape-sequences)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[7. Advanced Keyboard Tricks](https://github.com/dtlancaster/linux-guide/blob/master/README.md#7-advanced-keyboard-tricks)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[7.1 Cursor Movement Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#71-cursor-movement-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[7.2 Text Editing Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#72-text-editing-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[7.3 Cut-and-Paste Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#73-cut-and-paste-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[7.4 Completion Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#74-completion-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[7.5 History Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#75-history-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[7.6 History Expansion Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#76-history-expansion-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[8. Permissions](https://github.com/dtlancaster/linux-guide/blob/master/README.md#8-permissions)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[8.1 File Types](https://github.com/dtlancaster/linux-guide/blob/master/README.md#81-file-types)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[8.2 Permission Attributes](https://github.com/dtlancaster/linux-guide/blob/master/README.md#82-permission-attributes)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[8.3 Permission Attribute Examples](https://github.com/dtlancaster/linux-guide/blob/master/README.md#83-permission-attribute-examples)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[8.4 File Modes in Binary and Octal](https://github.com/dtlancaster/linux-guide/blob/master/README.md#84-file-modes-in-binary-and-octal)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[8.5 `chmod` Symbolic Notation](https://github.com/dtlancaster/linux-guide/blob/master/README.md#85-chmod-symbolic-notation)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[8.6 `chmod` Symbolic Notation Examples](https://github.com/dtlancaster/linux-guide/blob/master/README.md#86-chmod-symbolic-notation-examples)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[8.7 `chown` Argument Examples](https://github.com/dtlancaster/linux-guide/blob/master/README.md#87-chown-argument-examples)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[9. Processes](https://github.com/dtlancaster/linux-guide/blob/master/README.md#9-processes)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[9.1 Process States](https://github.com/dtlancaster/linux-guide/blob/master/README.md#91-process-states)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[9.2 BSD Style `ps` Column Headers](https://github.com/dtlancaster/linux-guide/blob/master/README.md#92-bsd-style-ps-column-headers)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[9.3 `top` Information Fields](https://github.com/dtlancaster/linux-guide/blob/master/README.md#93-top-information-fields)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[9.4 Common Signals](https://github.com/dtlancaster/linux-guide/blob/master/README.md#94-common-signals)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[9.5 Other Process-Related Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#95-other-process-related-commands)<br/>
[II. Configuration and the Environment](https://github.com/dtlancaster/linux-guide/blob/master/README.md#ii-configuration-and-the-environment)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[10. The Environment](https://github.com/dtlancaster/linux-guide/blob/master/README.md#10-the-environment)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[10.1 Environment Variables](https://github.com/dtlancaster/linux-guide/blob/master/README.md#101-environment-variables)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[10.2 Startup Files for Login Shell Sessions](https://github.com/dtlancaster/linux-guide/blob/master/README.md#102-startup-files-for-login-shell-sessions)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[10.3 Startup Files for Non-Login Shell Sessions](https://github.com/dtlancaster/linux-guide/blob/master/README.md#103-startup-files-for-non-login-shell-sessions)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[10.4 `.bashrc` Addition Examples](https://github.com/dtlancaster/linux-guide/blob/master/README.md#104-bashrc-addition-examples)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[11. Introduction to `vi`](https://github.com/dtlancaster/linux-guide/blob/master/README.md#11-introduction-to-vi)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[11.1 Cursor Movement Keys](https://github.com/dtlancaster/linux-guide/blob/master/README.md#111-cursor-movement-keys)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[11.2 Line Opening Keys](https://github.com/dtlancaster/linux-guide/blob/master/README.md#112-line-opening-keys)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[11.3 Text Deletion Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#113-text-deletion-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[11.4 Yanking Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#114-yanking-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[11.5 Global Search-and-Replace Syntax](https://github.com/dtlancaster/linux-guide/blob/master/README.md#115-global-search-and-replace-syntax)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[11.6 Replace Confirmation Keys](https://github.com/dtlancaster/linux-guide/blob/master/README.md#116-replace-confirmation-keys)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[12. Customizing the Prompt](https://github.com/dtlancaster/linux-guide/blob/master/README.md#12-customizing-the-prompt)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[12.1 Escape Codes Used in Shell Prompts](https://github.com/dtlancaster/linux-guide/blob/master/README.md#121-escape-codes-used-in-shell-prompts)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[12.2 Escape Sequences Used to Set Text Colors](https://github.com/dtlancaster/linux-guide/blob/master/README.md#122-escape-sequences-used-to-set-text-colors)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[12.3 Escape Sequences Used to Set Background Color](https://github.com/dtlancaster/linux-guide/blob/master/README.md#123-escape-sequences-used-to-set-background-color)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[12.4 Cursor Movement Escape Sequences](https://github.com/dtlancaster/linux-guide/blob/master/README.md#124-cursor-movement-escape-sequences)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[12.5 Breakdown of Complex Prompt String](https://github.com/dtlancaster/linux-guide/blob/master/README.md#125-breakdown-of-complex-prompt-string)<br/>
[III. Common Tasks and Essential Tools](https://github.com/dtlancaster/linux-guide/blob/master/README.md#iii-common-tasks-and-essential-tools)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[13. Package Management](https://github.com/dtlancaster/linux-guide/blob/master/README.md#13-package-management)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[13.1 Major Packaging System Families](https://github.com/dtlancaster/linux-guide/blob/master/README.md#131-major-packaging-system-families)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[13.2 Packaging System Tools](https://github.com/dtlancaster/linux-guide/blob/master/README.md#132-packaging-system-tools)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[13.3 Package Search Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#133-package-search-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[13.4 Package Installation Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#134-package-installation-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[13.5 Low-Level Package Installation Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#135-low-level-package-installation-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[13.6 Package Removal Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#136-package-removal-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[13.7 Package Update Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#137-package-update-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[13.8 Low-Level Package Upgrade Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#138-low-level-package-upgrade-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[13.9 Package Listing Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#139-package-listing-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[13.10 Package Status Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#1310-package-status-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[13.11 Package Information Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#1311-package-information-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[13.12 Package File Identification Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#1312-package-file-identification-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[14. Storage Media](https://github.com/dtlancaster/linux-guide/blob/master/README.md#14-storage-media)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[14.1 `/etc/fstab` Fields](https://github.com/dtlancaster/linux-guide/blob/master/README.md#141-etcfstab-fields)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[14.2 Linux Storage Device Names](https://github.com/dtlancaster/linux-guide/blob/master/README.md#142-linux-storage-device-names)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[15. Networking](https://github.com/dtlancaster/linux-guide/blob/master/README.md#15-networking)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[15.1 Examples of Interactive `ftp` Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#151-examples-of-interactive-ftp-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[16. Searching for Files](https://github.com/dtlancaster/linux-guide/blob/master/README.md#16-searching-for-files)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[16.1 `find` File Types](https://github.com/dtlancaster/linux-guide/blob/master/README.md#161-find-file-types)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[16.2 `find` Size Units](https://github.com/dtlancaster/linux-guide/blob/master/README.md#162-find-size-units)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[16.4 `find` Tests](https://github.com/dtlancaster/linux-guide/blob/master/README.md#163-find-tests)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[16.5 `find` AND/OR Logic](https://github.com/dtlancaster/linux-guide/blob/master/README.md#165-find-andor-logic)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[16.6 Predefined `find` Actions](https://github.com/dtlancaster/linux-guide/blob/master/README.md#166-predefined-find-actions)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[16.7 Commonly Used `find` Options](https://github.com/dtlancaster/linux-guide/blob/master/README.md#167-commonly-used-find-options)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[17. Archiving and Backup](https://github.com/dtlancaster/linux-guide/blob/master/README.md#17-archiving-and-backup)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[17.1 `gzip` Options](https://github.com/dtlancaster/linux-guide/blob/master/README.md#171-gzip-options)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[17.2 `tar` Modes](https://github.com/dtlancaster/linux-guide/blob/master/README.md#172-tar-modes)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[18. Regular Expressions](https://github.com/dtlancaster/linux-guide/blob/master/README.md#18-regular-expressions)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[18.1 `grep` Options](https://github.com/dtlancaster/linux-guide/blob/master/README.md#181-grep-options)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[18.2 POSIX Character Classes](https://github.com/dtlancaster/linux-guide/blob/master/README.md#182-posix-character-classes)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[18.3 Specifying the Number of Matches](https://github.com/dtlancaster/linux-guide/blob/master/README.md#183-specifying-the-number-of-matches)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[19. Text Processing](https://github.com/dtlancaster/linux-guide/blob/master/README.md#19-text-processing)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[19.1 Common `sort` Options](https://github.com/dtlancaster/linux-guide/blob/master/README.md#191-common-sort-options)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[19.2 Common `uniq` Options](https://github.com/dtlancaster/linux-guide/blob/master/README.md#192-common-uniq-options)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[19.3 `cut` Selection Options](https://github.com/dtlancaster/linux-guide/blob/master/README.md#193-cut-selection-options)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[19.4 `diff` Change Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#194-diff-change-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[19.5 `diff` Context Format Change Indicators](https://github.com/dtlancaster/linux-guide/blob/master/README.md#195-diff-context-format-change-indicators)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[19.6 `diff` Unified Format Change Indicators](https://github.com/dtlancaster/linux-guide/blob/master/README.md#196-diff-unified-format-change-indicators)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[19.7 `sed` Address Notation](https://github.com/dtlancaster/linux-guide/blob/master/README.md#197-sed-address-notation)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[19.8 `sed` Basic Editing Commands](https://github.com/dtlancaster/linux-guide/blob/master/README.md#198-sed-basic-editing-commands)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[20. Formatting Output](https://github.com/dtlancaster/linux-guide/blob/master/README.md#20-formatting-output)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[20.1 `nl` Markup](https://github.com/dtlancaster/linux-guide/blob/master/README.md#201-nl-markup)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[20.2 Common `nl` Options](https://github.com/dtlancaster/linux-guide/blob/master/README.md#202-common-nl-options)<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[20.3 `fmt` Options](https://github.com/dtlancaster/linux-guide/blob/master/README.md#203-fmt-options)<br/>

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

### 3.9 `rm` Examples
<table>
  <tr>
    <td><b>Command</b></td>
    <td><b>Results</b></td>
  </tr>
  <tr>
    <td>rm <i>file1</i></td>
    <td>Delete <i>file1</i> silently.</td>
  </tr>
  <tr>
    <td>rm -i <i>file1</i></td>
    <td>Same as the previous command, except that the user is prompted for confirmation before the deletion is performed.</td>
  </tr>
  <tr>
    <td>rm -r <i>file1 dir1</i></td>
    <td>Delete <i>file1</i> and <i>dir1</i> and its contents.</td>
  </tr>
  <tr>
    <td>rm -rf <i>file1 dir1</i></td>
    <td>Same as the previous command, except that if either <i>file1</i> or <i>dir1</i> do not exist, rm will continue silently.</td>
  </tr>
</table>

## 4. Working with Commands
`type` Indicate how a command name is interpreted<br/>
`which` Display which executable program will be executed<br/>
`help` Get help for shell builtins<br/>
`man` Display a command's manual page<br/>
`apropos` Display a list of appropriate commands<br/>
`info` Display a command's info entry<br/>
`whatis` Display one-line manual page descriptions<br/>
`alias` Create an alias for a command

### 4.1 Man Page Organization
<table>
  <tr>
    <td><b>Section</b></td>
    <td><b>Contents</b></td>
  </tr>
  <tr>
    <td>1</td>
    <td>User commands</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Programming interfaces for kernel system calls</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Programming interfaces to the C library</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Special files such as device nodes and drivers</td>
  </tr>
  <tr>
    <td>5</td>
    <td>File formats</td>
  </tr>
  <tr>
    <td>6</td>
    <td>Games and amusements such as screen savers</td>
  </tr>
  <tr>
    <td>7</td>
    <td>Miscellaneous</td>
  </tr>
  <tr>
    <td>8</td>
    <td>System administration commands</td>
  </tr>
</table>

### 4.2 `info` Commands
<table>
  <tr>
    <td><b>Command</b></td>
    <td><b>Action</b></td>
  </tr>
  <tr>
    <td>?</td>
    <td>Display command help</td>
  </tr>
  <tr>
    <td>Page up or Backspace</td>
    <td>Display previous page</td>
  </tr>
  <tr>
    <td>Page down or Spacebar</td>
    <td>Display next page</td>
  </tr>
  <tr>
    <td>n</td>
    <td>Next--display the next node</td>
  </tr>
  <tr>
    <td>p</td>
    <td>Previous--display the previous node</td>
  </tr>
  <tr>
    <td>U</td>
    <td>Up--display the parent node of the currently displayed node, usually a menu</td>
  </tr>
  <tr>
    <td>Enter</td>
    <td>Follow the hyperlink at the cursor location</td>
  </tr>
  <tr>
    <td>Q</td>
    <td>Quit</td>
  </tr>
</table>

## 5. Redirection
`cat` Concatenate files<br/>
`sort` Sort lines of text<br/>
`uniq` Report or omit repeated lines<br/>
`grep` Print lines matching a pattern<br/>
`wc` Print newline, word, and byte counts for each file<br/>
`head` Output the first part of a file<br/>
`tail` Output the last part of a file<br/>
`tee` Read from standard input and write to standard output and files

## 6. Seeing the World as the Shell Sees it
`echo` Display a line of text

### 6.1 Arithmetic Operators
<table>
  <tr>
    <td><b>Operator</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>+</td>
    <td>Addition</td>
  </tr>
  <tr>
    <td>-</td>
    <td>Subtraction</td>
  </tr>
  <tr>
    <td>*</td>
    <td>Multiplication</td>
  </tr>
  <tr>
    <td>/</td>
    <td>Division (but remember, since expansion supports only integer arithmetic, results are integers)</td>
  </tr>
  <tr>
    <td>%</td>
    <td>Modulo, which simply means "remainder"</td>
  </tr>
  <tr>
    <td>**</td>
    <td>Exponentiation</td>
  </tr>
</table>

### 6.2 Backslash Escape Sequences
<table>
  <tr>
    <td><b>Escape sequence</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>\a</td>
    <td>Bell (an alert that causes the computer to beep)</td>
  </tr>
  <tr>
    <td>\b</td>
    <td>Backspace</td>
  </tr>
  <tr>
    <td>\n</td>
    <td>Newline; on Unix-like systems, this produces a line feed</td>
  </tr>
  <tr>
    <td>\r</td>
    <td>Carriage return</td>
  </tr>
  <tr>
    <td>\t</td>
    <td>Tab</td>
  </tr>
</table>

## 7. Advanced Keyboard Tricks
`clear` Clear the terminal screen<br/>
`history` Display or manipulate the history list

### 7.1 Cursor Movement Commands
<table>
  <tr>
    <td><b>Key</b></td>
    <td><b>Action</b></td>
  </tr>
  <tr>
    <td>Ctrl-A</td>
    <td>Move cursor to the beginning of the line.</td>
  </tr>
  <tr>
    <td>Ctrl-E</td>
    <td>Move cursor to the end of the line.</td>
  </tr>
  <tr>
    <td>Ctrl-F</td>
    <td>Move cursor forward one character; same as the right arrow key.</td>
  </tr>
  <tr>
    <td>Alt-F</td>
    <td>Move cursor forward one word.</td>
  </tr>
  <tr>
    <td>Alt-B</td>
    <td>Move cursor backward one word.</td>
  </tr>
  <tr>
    <td>Ctrl-L</td>
    <td>Clear the screen and move the cursor to the top-left corner. The clear command does the same thing.</td>
  </tr>
</table>

### 7.2 Text Editing Commands
<table>
  <tr>
    <td><b>Key</b></td>
    <td><b>Action</b></td>
  </tr>
  <tr>
    <td>Ctrl-D</td>
    <td>Delete the character at the cursor location.</td>
  </tr>
  <tr>
    <td>Ctrl-T</td>
    <td>Transpose (exchange) the character at the cursor location with the one preceding it.</td>
  </tr>
  <tr>
    <td>Alt-T</td>
    <td>Transpose the word at the cursor location with th eone preceding it.</td>
  </tr>
  <tr>
    <td>Alt-L</td>
    <td>Convert the charcaters from the cursor location to the end of the word to lowercase.</td>
  </tr>
  <tr>
    <td>Alt-U</td>
    <td>Convert the characters from the cursor location to the end of the word to uppercase.</td>
  </tr>
</table>

### 7.3 Cut-and-Paste Commands
<table>
  <tr>
    <td><b>Key</b></td>
    <td><b>Action</b></td>
  </tr>
  <tr>
    <td>Ctrl-K</td>
    <td>Kill text from the cursor location to the end of the line.</td>
  </tr>
  <tr>
    <td>Ctrl-U</td>
    <td>Kill text from the cursor location to the beginning of the line.</td>
  </tr>
  <tr>
    <td>Alt-D</td>
    <td>Kill text from the cursor location to the end of the current word.</td>
  </tr>
  <tr>
    <td>Alt-Backspace</td>
    <td>Kill text from the cursor location to the beginning of the current word. If the cursor is at the beginning of a word, kill the previous word.</td>
  </tr>
  <tr>
    <td>Ctrl-Y</td>
    <td>Yank text from the kill-ring and insert it at the cursor location.</td>
  </tr>
</table>

### 7.4 Completion Commands
<table>
  <tr>
    <td><b>Key</b></td>
    <td><b>Action</b></td>
  </tr>
  <tr>
    <td>Alt-?</td>
    <td>Display a list of possible completions. On most systems, you can also do this by pressing the Tab key a second time, which is much easier.</td>
  </tr>
  <tr>
    <td>Alt-*</td>
    <td>Insert all possible completions. This is useful when you want to use more than one possible match.</td>
  </tr>
</table>

### 7.5 History Commands
<table>
  <tr>
    <td><b>Key</b></td>
    <td><b>Action</b></td>
  </tr>
  <tr>
    <td>Ctrl-P</td>
    <td>Move to the previous history entry. This is the same action as the up arrow.</td>
  </tr>
  <tr>
    <td>Ctrl-N</td>
    <td>Move to the next history entry. This is the same action as the down arrow.</td>
  </tr>
  <tr>
    <td>Alt-< </td>
    <td>Move to the beginning (top) of the history list.</td>
  </tr>
  <tr>
    <td>Alt-></td>
    <td>Move to the end (bottom) of the history list, i.e., the current command line.</td>
  </tr>
  <tr>
    <td>Ctrl-R</td>
    <td>Reverse incremental search. This searches incrementally from the current command line up the history list.</td>
  </tr>
  <tr>
    <td>Alt-P</td>
    <td>Reverse search, nonincremental. With this key, type in the search string and press Enter before the search is performed.</td>
  </tr>
  <tr>
    <td>Alt-N</td>
    <td>Forward search, nonincremental.</td>
  </tr>
  <tr>
    <td>Ctrl-O</td>
    <td>Execute the current item in the history list and advance to the next one. This is handy if you are trying to re-execute a sequence of commands in the history list.</td>
  </tr>
</table>

### 7.6 History Expansion Commands
<table>
  <tr>
    <td><b>Sequence</b></td>
    <td><b>Action</b></td>
  </tr>
  <tr>
    <td>!!</td>
    <td>Repeat the last command. It is probably easier to press the up arrow and Enter.</td>
  </tr>
  <tr>
    <td>!<i>number</i></td>
    <td>Repeat history list item <i>number</i>.</td>
  </tr>
  <tr>
    <td>!<i>string</i></td>
    <td>Repeat last history list item starting with <i>string</i>.</td>
  </tr>
  <tr>
    <td>!?<i>string</i></td>
    <td>Repeat last history list item containing <i>string</i>.</td>
  </tr>
</table>

## 8. Permissions
`id` Display user identity<br/>
`chmod` Change a file's mode<br/>
`umask` Set the default file permissions<br/>
`su` Run a shell as another user<br/>
`sudo` Execute a command as another user<br/>
`chown` Change a file's owner<br/>
`chgrp` Change a file's group ownership<br/>
`passwd` Change a user's password

### 8.1 File Types
<table>
  <tr>
    <td><b>Attribute</b></td>
    <td><b>File type</b></td>
  </tr>
  <tr>
    <td>-</td>
    <td>A regular file.</td>
  </tr>
  <tr>
    <td>d</td>
    <td>A directory.</td>
  </tr>
  <tr>
    <td>l</td>
    <td>A symbolic link. Notice that with symbolic links, the remaining file attributes are always rwxrwxrwx and are dummy values. The real file attributes are those of the file the symbolic link points to.</td>
  </tr>
  <tr>
    <td>c</td>
    <td>A <i>character special file</i>. This file type refers to a device that handles data as a stream of bytes, such as a terminal or /dev/null.</td>
  </tr>
  <tr>
    <td>b</td>
    <td>A <i>block special file</i>. This file type refers to a device that handles data in blocks, such as a hard drive or DVD drive.</td>
  </tr>
</table>

### 8.2 Permission Attributes
<table>
  <tr>
    <td><b>Attribute</b></td>
    <td><b>Files</b></td>
    <td><b>Directories</b></td>
  </tr>
  <tr>
    <td>r</td>
    <td>Allows a file to be opened and read.</td>
    <td>Allows a directory's contents to be listed if the execute attribute is also set.</td>
  </tr>
  <tr>
    <td>w</td>
    <td>Allows a file to be written to or truncated; however, this attribute does not allow to be renamed or deleted. THe ability to delete or rename is determined by directory attributes.</td>
    <td>Allows files within a directory to be created, deleted, and renamed if the execute attribute is also set.</td>
  </tr>
  <tr>
    <td>x</td>
    <td>Allows a file to be treated as a program and executed. Program files written in scripting languages must also be set as readable to be executed.</td>
    <td>Allows a directory to be entered, e.g., cd <i>directory</i>.</td>
  </tr>
</table>

### 8.3 Permission Attribute Examples
<table>
  <tr>
    <td><b>File Attributes</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>-rwx------</td>
    <td>A regular file that is readable, writable, and executable by the file's owner. No one else has any access.</td>
  </tr>
  <tr>
    <td>-rw-------</td>
    <td>A regular file that is readable and writable by the file's owner. No one else has any access.</td>
  </tr>
  <tr>
    <td>-rw-r--r--</td>
    <td>A regular file that is readable and writable by the file's owner. Members of the file's owner group may read the file. The file is world-readable.</td>
  </tr>
  <tr>
    <td>-rwxr-xr-x</td>
    <td>A regular file that is readable, writable, and executable by the file's owner. The file may be read and executed by everybody else.</td>
  </tr>
  <tr>
    <td>-rw-rw----</td>
    <td>A regular file that is readable and writable by the file's owner and members of the file's group owner only.</td>
  </tr>
  <tr>
    <td>lrwxrwxrwx</td>
    <td>A symbolic link. All symbolic links have "dummy" permissions. The real permissions are kept with the actual file pointed to by the symbolic link.</td>
  </tr>
  <tr>
    <td>drwxrwx---</td>
    <td>A directory. The owner and the members of the owner group may enter the directory and create, rename, and remove files within the directory.</td>
  </tr>
  <tr>
    <td>drwxr-x---</td>
    <td>A directory. The owner may enter the directory and create, rename, and delete files within the directory. Members of the owner group may enter the directory but cannot create, delete, or rename files.</td>
  </tr>
</table>

### 8.4 File Modes in Binary and Octal
<table>
  <tr>
    <td><b>Octal</b></td>
    <td><b>Binary</b></td>
    <td><b>File mode</b></td>
  </tr>
  <tr>
    <td>0</td>
    <td>000</td>
    <td>---</td>
  </tr>
  <tr>
    <td>1</td>
    <td>001</td>
    <td>--x</td>
  </tr>
  <tr>
    <td>2</td>
    <td>010</td>
    <td>-w-</td>
  </tr>
  <tr>
    <td>3</td>
    <td>011</td>
    <td>-wx</td>
  </tr>
  <tr>
    <td>4</td>
    <td>100</td>
    <td>r--</td>
  </tr>
  <tr>
    <td>5</td>
    <td>101</td>
    <td>r-x</td>
  </tr>
  <tr>
    <td>6</td>
    <td>110</td>
    <td>rw-</td>
  </tr>
  <tr>
    <td>7</td>
    <td>111</td>
    <td>rwx</td>
  </tr>
</table>

### 8.5 `chmod` Symbolic Notation
<table>
  <tr>
    <td><b>Symbol</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>u</td>
    <td>Short for "user" but means the file or directory owner.</td>
  </tr>
  <tr>
    <td>g</td>
    <td>Group owner.</td>
  </tr>
  <tr>
    <td>o</td>
    <td>Short for "others" but means world.</td>
  </tr>
  <tr>
    <td>a</td>
    <td>Short for "all." This is a combination of u, g, and o.</td>
  </tr>
</table>

### 8.6 `chmod` Symbolic Notation Examples
<table>
  <tr>
    <td><b>Notation</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>u+x</td>
    <td>Add execute permission for the owner.</td>
  </tr>
  <tr>
    <td>u-x</td>
    <td>remove execute permission from the owner.</td>
  </tr>
  <tr>
    <td>+x</td>
    <td>Add execute permission or the owner, group, and world. This is equivalent to a+x.</td>
  </tr>
  <tr>
    <td>o-rw</td>
    <td>Remove the read and write permissions from anyone besides the owner and group owner.</td>
  </tr>
  <tr>
    <td>go=rw</td>
    <td>Set the group owner and anyone besides the owner to have read and write permissions. If either the group owner or the world previously had execute permission, it is removed.</td>
  </tr>
  <tr>
    <td>u+x,go=rx</td>
    <td>Add execute permission for the owner and set the permissions for the group and others to read and execute. Multiple specifications may be separated by commas.</td>
  </tr>
</table>

### 8.7 `chown` Argument Examples
<table>
  <tr>
    <td><b>Argument</b></td>
    <td><b>Results</b></td>
  </tr>
  <tr>
    <td>bob</td>
    <td>Changes the ownership of the file from its current owner to user bob.</td>
  </tr>
  <tr>
    <td>bob:users</td>
    <td>Changes the ownership of the file from its current owner to user bob and changes the file grou powner to group users.</td>
  </tr>
  <tr>
    <td>:admins</td>
    <td>Changes the group owner to the group admins. The file owner is unchanged.</td>
  </tr>
  <tr>
    <td>bob:</td>
    <td>Changes the file owner from the current owner to user bob and changes the group owner to the login group of user bob.</td>
  </tr>
</table>

## 9. Processes
`ps` Report a snapshot of current processes<br/>
`top` Display tasks<br/>
`jobs` List active jobs<br/>
`bg` Place a job in the background<br/>
`fg` Place a job in the foreground<br/>
`kill` Send a signal to a process<br/>
`killall` Kill processes by name<br/>
`shutdown` Shut down or reboot the system

### 9.1 Process States
<table>
  <tr>
    <td><b>State</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>R</td>
    <td>Running. This means the process is running or ready to run.</td>
  </tr>
  <tr>
    <td>S</td>
    <td>Sleeping. The process is not running; rather, it is waiting for an event, such as a keystroke or network packet.</td>
  </tr>
  <tr>
    <td>D</td>
    <td>Uninterruptible sleep. The process is waiting for I/O such as a disk drive.</td>
  </tr>
  <tr>
    <td>T</td>
    <td>Stopped. The process has been instrubted to stop. You'll learn more about this later in the chapter.</td>
  </tr>
  <tr>
    <td>Z</td>
    <td>A defunt or "zombie" process. This is a child process that has terminated but has not been cleaned up by its parent.</td>
  </tr>
  <tr>
    <td> < </td>
    <td>A high-priority process. It's possible to grant more importance to a process, giving it more time on the CPU. This property of a process is called <i>niceness</i>. A process with high priority is said to be less nice because it's taking more of the CPU's time, which leaves less for everybody else.</td>
  </tr>
  <tr>
    <td>N</td>
    <td>A low-priority process. A process with low priority (a nice process) will get processor time only after other processes with higher priority have been serviced.</td>
  </tr>
</table>

### 9.2 BSD Style `ps` Column Headers
<table>
  <tr>
    <td><b>Header</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>USER</td>
    <td>User ID. This is the owner of the process.</td>
  </tr>
  <tr>
    <td>%CPU</td>
    <td>CPU usage in percent.</td>
  </tr>
  <tr>
    <td>%MEM</td>
    <td>Memory usage in percent.</td>
  </tr>
  <tr>
    <td>VSZ</td>
    <td>Virtual memory size.</td>
  </tr>
  <tr>
    <td>RSS</td>
    <td>Resident set size. This is the amount of physical memory (RAM) the process is using in kilobytes.</td>
  </tr>
  <tr>
    <td>START</td>
    <td>Time when the process started. For values over 24 hours, a date is used.</td>
  </tr>
</table>

### 9.3 `top` Information Fields
<table>
  <tr>
    <td><b>Row</b></td>
    <td><b>Field</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>1</td>
    <td>top</td>
    <td>This is the name of the program.</td>
  </tr>
  <tr>
    <td></td>
    <td>14:59:20</td>
    <td>This is the current time of day.</td>
  </tr>
  <tr>
    <td></td>
    <td>up 6:30</td>
    <td>This is called <i>uptime</i>. It is the amount of time since the machine was last booted. In this example, the system has been up for six and a half hours.</td>
  </tr>
  <tr>
    <td></td>
    <td>2 users</td>
    <td>There are two users logged in.</td>
  </tr>
  <tr>
    <td></td>
    <td>load average:</td>
    <td><i>Load average</i> refers to the number of processes that are waiting ro un; that is, the number of processes that are in a runnable state and are sharing the CPU. Three values are shown, each for a different period fo time. The first is the average for the last 60 seconds, the next is the previous 5 minutes, and finally the previous 15 minutes. Values less than 1.0 indicate that th emachine is not busy.</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Tasks:</td>
    <td>This summarizes the number of processes and their various process states.</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Cpu(s):</td>
    <td>This row describes the character of the activities that the CPU is performing.</td>
  </tr>
  <tr>
    <td></td>
    <td>0.7%us</td>
    <td>0.7 percent of the CPU is being used for <i>user processes</i>. This means processes outside the kernel.</td>
  </tr>
  <tr>
    <td></td>
    <td>1.0%sy</td>
    <td>1.0 percent of the CPU is being used for <i>system</i> (kernel) processes.</td>
  </tr>
  <tr>
    <td></td>
    <td>0.0%ni</td>
    <td>0.0 percent of the CPU is being used by "nice" (low-priority) processes.</td>
  </tr>
  <tr>
    <td></td>
    <td>98.3%id</td>
    <td>98.3 percent of the CPU is idle.</td>
  </tr>
  <tr>
    <td></td>
    <td>0.0%wa</td>
    <td>0.0 percent of the CPU is waiting for I/O.</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Mem:</td>
    <td>This shows how physical RAM is being used.</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Swap</td>
    <td>This shows how swap space (virtual memory) is being used.</td>
  </tr>
</table>

### 9.4 Common Signals
<table>
  <tr>
    <td><b>Number</b></td>
    <td><b>Name</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>1</td>
    <td>HUP</td>
    <td>Hang up. This is a vestige of the good old days when terminals were attached to remote computers with phone lines and modems. The signal is used to indicate to programs that the controlling terminal has "hung up". The effect of this signal can be demonstrated by closing a terminal session. The foreground program running on the terminal will be sent the signal and will terminate. This signal is also used by many daemon programs to cause a reinitialization. This means that when a daemon is sent this signal, it will restart and reread its configuration file. The Apache web server is an example of a daemon that uses the HUP signal in this way.</td>
  </tr>
  <tr>
    <td>2</td>
    <td>INT</td>
    <td>Interrupt. This performs the same function as Ctrl-C sent from the terminal. It will usually terminate a program.</td>
  </tr>
  <tr>
    <td>9</td>
    <td>KILL</td>
    <td>Kill. This signal is special. Whereas programs may choose to handle signals sent to them in different ways, including ignoring them all together, the KILL signal is never actually sent to the target program. Rather, the kernel immediately terminates the process. When a process is terminated in this manner, it is given no opportunity to "clean up" after itself or save its work. For this reason, the KILL signal should be used only as a last resort when other termination signals fail.</td>
  </tr>
  <tr>
    <td>15</td>
    <td>TERM</td>
    <td>Terminate. This is the default signal sent by the KILL command. If a program is still "alive" enough to receive signals, it will terminate.</td>
  </tr>
  <tr>
    <td>18</td>
    <td>CONT</td>
    <td>Continue. Thi swill restore a process after a STOP or TSTP signal. This signal is sent by the bg and fg commands.</td>
  </tr>
  <tr>
    <td>19</td>
    <td>STOP</td>
    <td>Stop. This signal causes a process to pause without terminating. Like the KILL signal, it is not sent to the target process, and thus it cannot be ignored.</td>
  </tr>
  <tr>
    <td>20</td>
    <td>TSTP</td>
    <td>Terminal stop. This is the signal sent by the terminal when Ctrl-Z is pressed. Unlike the STOP signal, the TSP signal is received by the program, but the program may choose to ignore it.</td>
  </tr>
  <tr>
    <td>3</td>
    <td>QUIT</td>
    <td>Quit.</td>
  </tr>
  <tr>
    <td>11</td>
    <td>SEGV</td>
    <td>Segmentation violation. This signal is sent if a program makes illegal use of memory; that is, if we tried to write somewhere it was not allowed to write.</td>
  </tr>
  <tr>
    <td>28</td>
    <td>WINCH</td>
    <td>Window change. This is the signal sent by the system when a window changes size. Some programs, such as top and less, will respond to this signal by redrawing themselves to fit the new window dimensions.</td>
  </tr>
</table>

### 9.5 Other Process-Related Commands
<table>
  <tr>
    <td><b>Command</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>pstree</td>
    <td>Outputs a process list arranged in a tree-like pattern showing the parent-child relationships between processes.</td>
  </tr>
  <tr>
    <td>vmstat</td>
    <td>Outputs a snapshot of system resource usage including memory, swap, and disk I/O. To see a continuous display, follow the command with a time delay (in seconds) for updates. Here's an example: vmstat 5. Terminate the output with Ctrl-C.</td>
  </tr>
  <tr>
    <td>xload</td>
    <td>A graphical program that draws a graph showing system load over time.</td>
  </tr>
  <tr>
    <td>tload</td>
    <td>Similar to the xload program but draws the graph in the terminal. Terminate the output with Ctrl-C.</td>
  </tr>
</table>

# II. Configuration and the Environment

## 10. The Environment
`printenv` Print part or all of the environment<br/>
`set` Set shell options<br/>
`export` Export environment to a subsequently executed programs<br/>
`alias` Create an alias for a command

### 10.1 Environment Variables
<table>
  <tr>
    <td><b>Variable</b></td>
    <td><b>Contents</b></td>
  </tr>
  <tr>
    <td>DISPLAY</td>
    <td>The name of your display if you are running a graphical environment. Usually this is :0, meaning the first display generatedd by the X server.</td>
  </tr>
  <tr>
    <td>EDITOR</td>
    <td>The name of the program to be used for text editing.</td>
  </tr>
  <tr>
    <td>SHELL</td>
    <td>The name of your shell program.</td>
  </tr>
  <tr>
    <td>HOME</td>
    <td>The pathname of your home directory.</td>
  </tr>
  <tr>
    <td>LANG</td>
    <td>Defines the character set and collation order of your language.</td>
  </tr>
  <tr>
    <td>OLDPWD</td>
    <td>The previous working directory.</td>
  </tr>
  <tr>
    <td>PAGER</td>
    <td>The name of the program to be used for paging output. This is often set to <i>/usr/bin/less</i>.</td>
  </tr>
  <tr>
    <td>PATH</td>
    <td>A colon-separated list of directories that are searched when you enter the name of an executable program.</td>
  </tr>
  <tr>
    <td>PS1</td>
    <td>Stands for "prompt string 1." This defines the contents of the shell prompt. As we will later see, this can be extensively customized.</td>
  </tr>
  <tr>
    <td>PWD</td>
    <td>The current working directory.</td>
  </tr>
  <tr>
    <td>TERM</td>
    <td>The name of your terminal type. Unix-like systems support many terminal protocols; this variable sets the protocol to be used with your terminal emulator.</td>
  </tr>
  <tr>
    <td>TZ</td>
    <td>Specifies your time zone. Most Unix-like systems maintain the computer's internal clock in <i>Coordinated Universal Time</i> (UTC) and then display the local time by applying an offset specified by this variable.</td>
  </tr>
  <tr>
    <td>USER</td>
    <td>Your username.</td>
  </tr>
</table>

### 10.2 Startup Files for Login Shell Sessions
<table>
  <tr>
    <td><b>File</b></td>
    <td><b>Contents</b></td>
  </tr>
  <tr>
    <td>/etc/profile</td>
    <td>A global configuration script that applies to all users.</td>
  </tr>
  <tr>
    <td>~/.bash_profile</td>
    <td>A user's personal startup file. It can be used to extend or override settings in the global configuration script.</td>
  </tr>
  <tr>
    <td>~/.bash_login</td>
    <td>If ~/.bash_profile is not found, bash attempts to read this script.</td>
  </tr>
  <tr>
    <td>~/.profile</td>
    <td>If neither ~/.bash_profile nor ~/.bash_login is found, bash attempts to read this file. This is the default in Debian-based distributions, such as Ubuntu.</td>
  </tr>
</table>

### 10.3 Startup Files for Non-Login Shell Sessions
<table>
  <tr>
    <td><b>File</b></td>
    <td><b>Contents</b></td>
  </tr>
  <tr>
    <td>/etc/bash.bashrc</td>
    <td>A global configuration script that applies to all users.</td>
  </tr>
  <tr>
    <td>~/.bashrc</td>
    <td>A user's personal startup file. It can be used to extend or override settings in the global configuration script.</td>
  </tr>
</table>

### 10.4 `.bashrc` Addition Examples
<table>
  <tr>
    <td><b>Line</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>umask 0002</td>
    <td>Sets the umask to solve the problem with the shared directories we discussed in Chapter 9.</td>
  </tr>
  <tr>
    <td>export HISTCONTROL=ignoredups</td>
    <td>Causes the shell's history recording feature to ignore a command if the same command was just recorded.</td>
  </tr>
  <tr>
    <td>export HISTSIZE=1000</td>
    <td>Increases the size of the command history from the usual default of 500 lines to 1,000 lines.</td>
  </tr>
  <tr>
    <td>alias l.='ls -d .* --color=auto'</td>
    <td>Creates a new command called l., which displays all directory entries that begin with a dot.</td>
  </tr>
  <tr>
    <td>alias ll='ls -l --color=auto'</td>
    <td>Creates a new command called ll, which displays a long-format directory listing.</td>
  </tr>
</table>

## 11. Introduction to `vi`

### 11.1 Cursor Movement Keys
<table>
  <tr>
    <td><b>Key</b></td>
    <td><b>Moves the cursor</b></td>
  </tr>
  <tr>
    <td>l or right arrow</td>
    <td>Right one character.</td>
  </tr>
  <tr>
    <td>h or left arrow</td>
    <td>Left one character.</td>
  </tr>
  <tr>
    <td>j or down arrow</td>
    <td>Down one line.</td>
  </tr>
  <tr>
    <td>k or up arrow</td>
    <td>Up one line.</td>
  </tr>
  <tr>
    <td>0 (zero)</td>
    <td>To the beginning of the current line.</td>
  </tr>
  <tr>
    <td>^</td>
    <td>To the first non-whitespace character on the current line.</td>
  </tr>
  <tr>
    <td>$</td>
    <td>To the end of the current line.</td>
  </tr>
  <tr>
    <td>w</td>
    <td>To the beginning of the next word or punctuation character.</td>
  </tr>
  <tr>
    <td>W</td>
    <td>To the beginning of the next word, ignoring punctuation characters.</td>
  </tr>
  <tr>
    <td>b</td>
    <td>To the beginning of the previous word or punctuation character.</td>
  </tr>
  <tr>
    <td>B</td>
    <td>To the beginning of the previous word, ignoring punctuation characters.</td>
  </tr>
  <tr>
    <td>Ctrl-F or Page Down</td>
    <td>Down one page.</td>
  </tr>
  <tr>
    <td>Ctrl-B or Page Up</td>
    <td>Up one page.</td>
  </tr>
  <tr>
    <td><i>number</i>G</td>
    <td>To line number. For example, 1G moves to the first line of the file.</td>
  </tr>
  <tr>
    <td>G</td>
    <td>To the last line of the file.</td>
  </tr>
</table>

### 11.2 Line Opening Keys
<table>
  <tr>
    <td><b>Command</b></td>
    <td><b>Opens</b></td>
  </tr>
  <tr>
    <td>o</td>
    <td>The line below the current line</td>
  </tr>
  <tr>
    <td>O</td>
    <td>The line above the current line</td>
  </tr>
</table>

### 11.3 Text Deletion Commands
<table>
  <tr>
    <td><b>Command</b></td>
    <td><b>Deletes</b></td>
  </tr>
  <tr>
    <td>x</td>
    <td>The current character</td>
  </tr>
  <tr>
    <td>3x</td>
    <td>The current charcater and the next two characters</td>
  </tr>
  <tr>
    <td>dd</td>
    <td>The current line</td>
  </tr>
  <tr>
    <td>5dd</td>
    <td>The current line and the next four lines</td>
  </tr>
  <tr>
    <td>dW</td>
    <td>From the current cursor position to the beginning of the next word</td>
  </tr>
  <tr>
    <td>d$</td>
    <td>From the current cursor location to the end of the current line</td>
  </tr>
  <tr>
    <td>d0</td>
    <td>From the current cursor location to the beginning of the next line</td>
  </tr>
  <tr>
    <td>d^</td>
    <td>From the current cursor location to the first non-whitespace character in the line</td>
  </tr>
  <tr>
    <td>dG</td>
    <td>From the current line to the end of the file</td>
  </tr>
  <tr>
    <td>d20G</td>
    <td>From the current line to the twentieth line of the file</td>
  </tr>
</table>

### 11.4 Yanking Commands
<table>
  <tr>
    <td><b>Command</b></td>
    <td><b>Copies</b></td>
  </tr>
  <tr>
    <td>yy</td>
    <td>The current line</td>
  </tr>
  <tr>
    <td>5yy</td>
    <td>The current line and the next four lines</td>
  </tr>
  <tr>
    <td>yW</td>
    <td>From the current cursor position to the beginning of the next word</td>
  </tr>
  <tr>
    <td>y$</td>
    <td>From the current cursor location to the end of the current line</td>
  </tr>
  <tr>
    <td>y0</td>
    <td>From the current cursor location to the beginning of the line</td>
  </tr>
  <tr>
    <td>y^</td>
    <td>From the current cursor location to the first non-whitespace character in the line</td>
  </tr>
  <tr>
    <td>yG</td>
    <td>From the current line to the end of the file</td>
  </tr>
  <tr>
    <td>y20G</td>
    <td>From the current line to the twentieth line of the file</td>
  </tr>
</table>

`:%s/Line/line/g`

### 11.5 Global Search-and-Replace Syntax
<table>
  <tr>
    <td><b>Item</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>:</td>
    <td>The colon character starts an ex command.</td>
  </tr>
  <tr>
    <td>%</td>
    <td>This specifies the range of lines for the operation. % is a shortcut meaning from the first line to the last line. Alternately, the range could have been specified 1,$, which means "from line 1 to the last line in the file." If the range of lines is omitted, the operation is performed only on the current line.</td>
  </tr>
  <tr>
    <td>s</td>
    <td>This specifies the operation. In this case, it's substitution (search-and-replace).</td>
  </tr>
  <tr>
    <td>/Line/line/</td>
    <td>This specifies the search pattern and the replacement text.</td>
  </tr>
  <tr>
    <td>g</td>
    <td>This means "global" in the sense that the search-and-replace is performed on every instance of the search string in the line. If omitted, only the first instance of the search string on each line is replaced.</td>
  </tr>
</table>

### 11.6 Replace Confirmation Keys
<table>
  <tr>
    <td><b>Key</b></td>
    <td><b>Action</b></td>
  </tr>
  <tr>
    <td>y</td>
    <td>Perform the substitution.</td>
  </tr>
  <tr>
    <td>n</td>
    <td>Skip this instance of the pattern.</td>
  </tr>
  <tr>
    <td>a</td>
    <td>Perform the substitution on this and all subsequent instances of the pattern.</td>
  </tr>
  <tr>
    <td>q or Esc</td>
    <td>Quit substituting.</td>
  </tr>
  <tr>
    <td>l</td>
    <td>Perform this subsitution and then quit. This is short for "last."</td>
  </tr>
  <tr>
    <td>Ctrl-E, Ctrl-Y</td>
    <td>Scroll down and scroll up, respectively. This is useful for viewing the context of the proposed substitution.</td>
  </tr>
</table>

## 12. Customizing the Prompt

### 12.1 Escape Codes Used in Shell Prompts
<table>
  <tr>
    <td><b>Sequence</b></td>
    <td><b>Value displayed</b></td>
  </tr>
  <tr>
    <td>\a</td>
    <td>ASCII bell. This makes the computer beep when it is encountered.</td>
  </tr>
  <tr>
    <td>\d</td>
    <td>Current date in day, month, date format. For example, "Mon May 26."</td>
  </tr>
  <tr>
    <td>\h</td>
    <td>Hostname of the local machine minus the trailing domain name.</td>
  </tr>
  <tr>
    <td>\H</td>
    <td>Full hostname.</td>
  </tr>
  <tr>
    <td>\j</td>
    <td>Number of jobs running in the current shell session.</td>
  </tr>
  <tr>
    <td>\l</td>
    <td>Name of the current terminal device.</td>
  </tr>
  <tr>
    <td>\n</td>
    <td>A newline character.</td>
  </tr>
  <tr>
    <td>\r</td>
    <td>A carriage return.</td>
  </tr>
  <tr>
    <td>\s</td>
    <td>Name of the shell program.</td>
  </tr>
  <tr>
    <td>\t</td>
    <td>Current time in 24-hour hours:minutes:seconds format.</td>
  </tr>
  <tr>
    <td>\T</td>
    <td>Current time in 12-hour format.</td>
  </tr>
  <tr>
    <td>\@</td>
    <td>Current time in 12-hour AM/PM format.</td>
  </tr>
  <tr>
    <td>\A</td>
    <td>Current time in 24-hour hours:minutes format.</td>
  </tr>
  <tr>
    <td>\u</td>
    <td>Username of the current user.</td>
  </tr>
  <tr>
    <td>\v</td>
    <td>Version number of the shell.</td>
  </tr>
  <tr>
    <td>\V</td>
    <td>Version and release numbers of the shell.</td>
  </tr>
  <tr>
    <td>\w</td>
    <td>Name of the current working directory.</td>
  </tr>
  <tr>
    <td>\W</td>
    <td>Last part of the current working directory name.</td>
  </tr>
  <tr>
    <td>\!</td>
    <td>History number of the current command.</td>
  </tr>
  <tr>
    <td>\#</td>
    <td>Number of commands entered during this shell session.</td>
  </tr>
  <tr>
    <td>\$</td>
    <td>This displays a $ character unless we have superuser privileges. In that case, it displays a # instead.</td>
  </tr>
  <tr>
    <td>\[</td>
    <td>Signals the start of a series of one or more non-printing characters. This is used to embed non-printing control charcaters that manipulate the terminal emulator in some way, such as moving the cursor or changing text colors.</td>
  </tr>
  <tr>
    <td>\]</td>
    <td>Signals the end of a non-printing character sequence.</td>
  </tr>
</table>

### 12.2 Escape Sequences Used to Set Text Colors
<table>
  <tr>
    <td><b>Sequence</b></td>
    <td><b>Text color</b></td>
    <td><b>Sequence</b></td>
    <td><b>Text color</b></td>
  </tr>
  <tr>
    <td>\033[0;30m</td>
    <td>Black</td>
    <td>\033[1;30m</td>
    <td>Dark gray</td>
  </tr>
  <tr>
    <td>\033[0;31m</td>
    <td>Red</td>
    <td>\033[1;31m</td>
    <td>Light red</td>
  </tr>
  <tr>
    <td>\033[0;32m</td>
    <td>Green</td>
    <td>\033[1;32m</td>
    <td>Light green</td>
  </tr>
  <tr>
    <td>\033[0;33m</td>
    <td>Brown</td>
    <td>\033[1;33m</td>
    <td>Yellow</td>
  </tr>
  <tr>
    <td>\033[0;34m</td>
    <td>Blue</td>
    <td>\033[1;34m</td>
    <td>Light blue</td>
  </tr>
  <tr>
    <td>\033[0;35m</td>
    <td>Purple</td>
    <td>\033[1;35m</td>
    <td>Light purple</td>
  </tr>
  <tr>
    <td>\033[0;36m</td>
    <td>Cyan</td>
    <td>\033[1;36m</td>
    <td>Light cyan</td>
  </tr>
  <tr>
    <td>\033[0;37m</td>
    <td>Light gray</td>
    <td>\033[1;37m</td>
    <td>White</td>
  </tr>
</table>

### 12.3 Escape Sequences Used to Set Background Color
<table>
  <tr>
    <td><b>Sequence</b></td>
    <td><b>Background color</b></td>
  </tr>
  <tr>
    <td>\033[0;40m</td>
    <td>Black</td>
  </tr>
  <tr>
    <td>\033[0;41m</td>
    <td>Red</td>
  </tr>
  <tr>
    <td>\033[0;42m</td>
    <td>Green</td>
  </tr>
  <tr>
    <td>\033[0;43m</td>
    <td>Brown</td>
  </tr>
  <tr>
    <td>\033[0;44m</td>
    <td>Blue</td>
  </tr>
  <tr>
    <td>\033[0;45m</td>
    <td>Purple</td>
  </tr>
  <tr>
    <td>\033[0;46m</td>
    <td>Cyan</td>
  </tr>
  <tr>
    <td>\033[0;47m</td>
    <td>Light gray</td>
  </tr>
</table>

### 12.4 Cursor Movement Escape Sequences
<table>
  <tr>
    <td><b>Escape code</b></td>
    <td><b>Action</b></td>
  </tr>
  <tr>
    <td>\033[<i>l</i>;<i>c</i>H</td>
    <td>Move the cursor to line <i>l</i> and column <i>c</i></td>
  </tr>
  <tr>
    <td>\033[<i>n</i>A</td>
    <td>Move the cursor up <i>n</i> lines</td>
  </tr>
  <tr>
    <td>\033[<i>n</i>B</td>
    <td>Move the cursor down <i>n</i> lines</td>
  </tr>
  <tr>
    <td>\033[<i>n</i>C</td>
    <td>Move the cursor forward <i>n</i> characters</td>
  </tr>
  <tr>
    <td>\033[<i>n</i>D</td>
    <td>Move the cursor backward <i>n</i> characters</td>
  </tr>
  <tr>
    <td>\033[2J</td>
    <td>Clear the screen and move the cursor to the upper-left corner (line 0, column 0)</td>
  </tr>
  <tr>
    <td>\033[K</td>
    <td>Clear from the cursor position to the end of the current line</td>
  </tr>
  <tr>
    <td>\033[s</td>
    <td>Store the current cursor position</td>
  </tr>
  <tr>
    <td>\033[u</td>
    <td>Recall the stored cursor position</td>
  </tr>
</table>

`PS1="\[\033[s\033[0;0H\033[0;41m\033[K\033[1;33m\t\033[0m\033[u\]<\u@\h \W>\$ "`

### 12.5 Breakdown of Complex Prompt String
<table>
  <tr>
    <td><b>Sequence</b></td>
    <td><b>Action</b></td>
  </tr>
  <tr>
    <td>\[</td>
    <td>Begin a non-printing character sequence. The purpose of this is to allow bash to properly calculate the size of the visible prompt. Without an accurate calculation, command line editing features cannot position the cursor correctly.</td>
  </tr>
  <tr>
    <td>\033[s</td>
    <td>Store the cursor position. This is needed to return to the prompt location after the bar and clock have been drawn at the top of the screen. Be aware that some terminal emulators do not recognize this code.</td>
  </tr>
  <tr>
    <td>\033[0;0H</td>
    <td>Move the cursor to the upper-left corner, which is line 0, column 0.</td>
  </tr>
  <tr>
    <td>\033[0;41m</td>
    <td>Set the background color to red.</td>
  </tr>
  <tr>
    <td>\033[K</td>
    <td>Clear from the current cursor location (the top-left corner) to the end of the line. Because the background color is now red, the line is cleared to that color, creating our bar. Note that clearing to the end fo the line does not change the cursor position, which remains in the upper-left corner.</td>
  </tr>
  <tr>
    <td>\033[1;33m</td>
    <td>Set the text color to yellow.</td>
  </tr>
  <tr>
    <td>\t</td>
    <td>Display the current time. While this is a "printing" element, we still include it in the non-printing portion of the prompt since we don't want bash to include the clock when calculating the true size of the displayed prompt.</td>
  </tr>
  <tr>
    <td>\033[0m</td>
    <td>Turn off color. This affects both the text and the background.</td>
  </tr>
  <tr>
    <td>\033[u</td>
    <td>Restore the cursor position saved earlier.</td>
  </tr>
  <tr>
    <td>\]</td>
    <td>End the non-printing characters sequence.</td>
  </tr>
  <tr>
    <td> <\u@\h \W>\$ </td>
    <td>Prompt string.</td>
  </tr>
</table>

# III. Common Tasks and Essential Tools

## 13. Package Management

### 13.1 Major Packaging System Families
<table>
  <tr>
    <td><b>Packaging system</b></td>
    <td><b>Distributions (partial listing)</b></td>
  </tr>
  <tr>
    <td>Debian-style (.deb)</td>
    <td>Debian, Ubuntu, Linux Mint, Raspbian</td>
  </tr>
  <tr>
    <td>Red Hat-style (.rpm)</td>
    <td>Fedora, CentOS, Red Hat Enterprise Linux, OpenSUSE</td>
  </tr>
</table>

### 13.2 Packaging System Tools
<table>
  <tr>
    <td><b>Distributions</b></td>
    <td><b>Low-level tools</b></td>
    <td><b>High-level tools</b></td>
  </tr>
  <tr>
    <td>Debian-style</td>
    <td>dpkg</td>
    <td>apt-get, apt, aptitude</td>
  </tr>
  <tr>
    <td>Fedora, Red Hat Enterprise Linux, CentOS</td>
    <td>rpm</td>
    <td>yum, dnf</td>
  </tr>
</table>

### 13.3 Package Search Commands
<table>
  <tr>
    <td><b>Style</b></td>
    <td><b>Command(s)</b></td>
  </tr>
  <tr>
    <td>Debian</td>
    <td>apt-get update<br/>apt-cache search <i>search_string</i></td>
  </tr>
  <tr>
    <td>Red Hat</td>
    <td>yum search <i>search_string</i></td>
  </tr>
</table>

### 13.4 Package Installation Commands
<table>
  <tr>
    <td><b>Style</b></td>
    <td><b>Command(s)</b></td>
  </tr>
  <tr>
    <td>Debian</td>
    <td>apt-get update</td>
    <td>apt-get install <i>package_name</i></td>
  </tr>
  <tr>
    <td>Red Hat</td>
    <td>yum install <i>package_name</i></td>
  </tr>
</table>


### 13.5 Low-Level Package Installation Commands
<table>
  <tr>
    <td><b>Style</b></td>
    <td><b>Command(s)</b></td>
  </tr>
  <tr>
    <td>Debian</td>
    <td>dpkg -i <i>package_file</i></td>
  </tr>
  <tr>
    <td>Red Hat</td>
    <td>rpm -i <i>package_file</i></td>
  </tr>
</table>

### 13.6 Package Removal Commands
<table>
  <tr>
    <td><b>Style</b></td>
    <td><b>Command(s)</b></td>
  </tr>
  <tr>
    <td>Debian</td>
    <td>apt-get remove <i>package_name</i></td>
  </tr>
  <tr>
    <td>Red Hat</td>
    <td>yum erase <i>package_name</i></td>
  </tr>
</table>

### 13.7 Package Update Commands
<table>
  <tr>
    <td><b>Style</b></td>
    <td><b>Command(s)</b></td>
  </tr>
  <tr>
    <td>Debian</td>
    <td>apt-get update; apt-get upgrade</td>
  </tr>
  <tr>
    <td>Red Hat</td>
    <td>yum update</td>
  </tr>
</table>

### 13.8 Low-Level Package Upgrade Commands
<table>
  <tr>
    <td><b>Style</b></td>
    <td><b>Command(s)</b></td>
  </tr>
  <tr>
    <td>Debian</td>
    <td>dpkg -i <i>package_file</i></td>
  </tr>
  <tr>
    <td>Red Hat</td>
    <td>rpm -U <i>package_file</i></td>
  </tr>
</table>

### 13.9 Package Listing Commands
<table>
  <tr>
    <td><b>Style</b></td>
    <td><b>Command(s)</b></td>
  </tr>
  <tr>
    <td>Debian</td>
    <td>dpkg -l</td>
  </tr>
  <tr>
    <td>Red Hat</td>
    <td>rpm -qa</td>
</table>

### 13.10 Package Status Commands
<table>
  <tr>
    <td><b>Style</b></td>
    <td><b>Command(s)</b></td>
  </tr>
  <tr>
    <td>Debian</td>
    <td>dpkg -s <i>package_name</i></td>
  </tr>
  <tr>
    <td>Red Hat</td>
    <td>rpm -q <i>package_name</i></td>
  </tr>
</table>

### 13.11 Package Information Commands
<table>
  <tr>
    <td><b>Style</b></td>
    <td><b>Command(s)</b></td>
  </tr>
  <tr>
    <td>Debian</td>
    <td>apt-cache show <i>package_name</i></td>
  </tr>
  <tr>
    <td>Red Hat</td>
    <td>yum info <i>package_name</i></td>
  </tr>
</table>

### 13.12 Package File Identification Commands
<table>
  <tr>
    <td><b>Style</b></td>
    <td><b>Command(s)</b></td>
  </tr>
  <tr>
    <td>Debian</td>
    <td>dpkg -S <i>file_name</i></td>
  </tr>
  <tr>
    <td>Red Hat</td>
    <td>rpm -qf <i>file_name</i></td>
  </tr>
</table>


## 14. Storage Media
`mount` Mount a file system<br/>
`umount` Unmount a file system<br/>
`fsck` Check and repair a file system<br/>
`fdisk` Manipulate disk partition table<br/>
`mkfs` Create a file system<br/>
`dd` Convert and copy a file<br/>
`genisoimage (mkisofs)` Create an ISO 9660 image file<br/>
`wodim (cdrecord)` Write data to optical storage media<br/>
`md5sum` Calculate an MD5 checksum<br/>

### 14.1 `/etc/fstab` Fields
<table>
  <tr>
    <td><b>Field</b></td>
    <td><b>Contents</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>1</td>
    <td>Device</td>
    <td>Traditionally, this fields contains the actual name of a device file associated with the physical device, such as <i>/dev/sda1</i> (the first partition of the first detected hard disk). But with today's computers, which have many devices that are hot pluggable (like USB drives), many modern Linux distributions associate a device with a text label instead. This label (which is added to the storage media when it is formatted) can be either a simple text label or a randomly generated UUID (Universallly Unique Identifier). This label is read by the operating system when the device is attached to the system. That way, no matter which device file is assigned to the actual physical device, it can still be correctly identified.</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Mount point</td>
    <td>The directory where the device is attached to the file system tree.</td>
  </tr>
  <tr>
    <td>3</td>
    <td>File system type</td>
    <td>Linux allows many file system types to be mounted. Most native Linux file systems are Fourth Extended File System (ext4), but many others are supported, such as FAT16 (msdos), FAT32 (vfat), NTFS (ntfs), CD-ROM (iso9660), etc.</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Options</td>
    <td>File systems can be mounted with various options. It is possible, for example, to mount file systems as read-only or to prevent any programs from being executed from them (a useful security feature for removable media).</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Frequency</td>
    <td>A single number that specifies if and when a file system is to be backed up with the dump command.</td>
  </tr>
  <tr>
    <td>6</td>
    <td>Order</td>
    <td>A single number that specifies in what order file systems should be checked with the fsck command.</td>
  </tr>
</table>

### 14.2 Linux Storage Device Names
<table>
  <tr>
    <td><b>Pattern</b></td>
    <td><b>Device</b></td>
  </tr>
  <tr>
    <td><i>/dev/fd*</i></td>
    <td>Floppy disk drives.</td>
  </tr>
  <tr>
    <td><i>/dev/hd*</i></td>
    <td>IDE (PATA) dists on older systems. Typical motehrboards contain two IDE connectors or <i>channels</i>, each with a cable with two attachment points for drivers. The first drive on the cable is called the <i>master</i> device, and the second is called the slave device. The device names are ordered such that <i>/dev/hda</i> refers to the master device on the first channel, <i>/dev/hdb</i> is the slave device on the first channel; <i>/dev/hdc</i> is the master device on the second channel, and so on. A trailing digit indicates the partition number on the device. For example, <i>/dev/hda1</i> refers to the first partition on the first hard drive on the system, while <i>/dev/hda</i> refers to the entire drive.</td>
  </tr>
  <tr>
    <td><i>/dev/lp*</i></td>
    <td>Printers.</td>
  </tr>
  <tr>
    <td><i>/dev/sd*</i></td>
    <td>SCSI disks. On modern Linux systems, the kernel treats all disk-like devices (including PATA/SATA hard disks, flash drives, and USB mass storage devices such as portable music players and digital cameras) as SCSI disks. The rest of the naming system is similar to the older <i>/dev/hd*</i> naming scheme previously described.</td>
  </tr>
  <tr>
    <td><i>/dev/sr*</i></td>
    <td>Optical drives (CD/DVD readers and burners).</td>
  </tr>
</table>

## 15. Networking
`ping` Send an ICMP ECHO_REQUEST to network hosts<br/>
`traceroute` Print the route packets trace to a network host<br/>
`ip` Show/manipulate routing, devices, policy routing, and tunnels<br/>
`netstat` Print network connections, routing tables, interface statistics, masquerade connections, and multicast memberships<br/>
`ftp` Internet filel transfer program<br/>
`wget` Non-interactive network downloader<br/>
`ssh` OpenSSH SSH client (remote login program)<br/>

### 15.1 Examples of Interactive `ftp` Commands
<table>
  <tr>
    <td><b>Command</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>ftp fileserver</td>
    <td>Invole the ftp program and have it connect to the FTP sever <i>fileserver</i>.</td>
  </tr>
  <tr>
    <td>anonymous</td>
    <td>Login name. After the login prompt, a password prompt will appear. Some servers will accept a blank password; others will require a password in the form of an email address. In that case, try something like <i>user@example.com</i>.</td>
  </tr>
  <tr>
    <td>cd pub/cd_images/ubuntu-18.04</td>
    <td>Change to the directory on the remote system containing the desired file. Note that on most anonymous FTP servers, the files for public downloading are found somewhere under the <i>pub</i> directory.</td>
  </tr>
  <tr>
    <td>ls</td>
    <td>List the directory on the remote system.</td>
  </tr>
  <tr>
    <td>lcd Desktop</td>
    <td>Change the directory on the local system to <i>~/Desktop</i>. In the example, the ftp program was invoked when the working directory was ~. This command changes the working directory to <i>~/Desktop</i>.</td>
  </tr>
  <tr>
    <td>get ubuntu-18.04-desktop-amd64.iso</td>
    <td>Tell the remote system to transfer the file <i>ubuntu-18.04-desktop-amd64.iso</i> to the local system. Since the working directory on the local system was changed to <i>~/Desktop</i>, the file will be downloaded there.</td>
  </tr>
  <tr>
    <td>bye</td>
    <td>Log off the remote server and end the ftp program session. The commands quit and exit may also be used.</td>
  </tr>
</table>

## 16. Searching for Files
`locate` Find files by name<br/>
`find` Search for files in a directory hierarchy<br/>
`xargs` Build and execute command lines from standard input<br/>
`touch` Change file times<br/>
`stat` Display file or file system status<br/>

### 16.1 `find` File Types
<table>
  <tr>
    <td><b>File type</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>b</td>
    <td>Block special device file</td>
  </tr>
  <tr>
    <td>c</td>
    <td>Character special device file</td>
  </tr>
  <tr>
    <td>d</td>
    <td>Directory</td>
  </tr>
  <tr>
    <td>f</td>
    <td>Regular file</td>
  </tr>
  <tr>
    <td>l</td>
    <td>Symbolic link</td>
  </tr>
</table>

### 16.2 `find` Size Units
<table>
  <tr>
    <td><b>Character</b></td>
    <td><b>Unit</b></td>
  </tr>
  <tr>
    <td>b</td>
    <td>512-byte blocks. This is the default if no unit is specified.</td>
  </tr>
  <tr>
    <td>c</td>
    <td>Bytes.</td>
  </tr>
  <tr>
    <td>w</td>
    <td>2-byte words.</td>
  </tr>
  <tr>
    <td>k</td>
    <td>Kilobytes (units of 1,024 bytes).</td>
  </tr>
  <tr>
    <td>M</td>
    <td>Megabytes (units of 1,048,576 bytes).</td>
  </tr>
  <tr>
    <td>G</td>
    <td>Gigabytes (units of 1,073,741,824 bytes).</td>
  </tr>
</table>

### 16.3 `find` Tests
<table>
  <tr>
    <td><b>Test</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>-cmin <i>n</i></td>
    <td>Match files or directories whose content or attributes were last modified exactly <i>n</i> minutes ago. To specify less than <i>n</i> minutes ago, use -<i>n</i>, and to specify more than <i>n</i> minutes ago, use +<i>n</i>.</td>
  </tr>
  <tr>
    <td>-cnewer <i>file</i></td>
    <td>Match files or directories whose contents or attributes were last modified more recently than those of <i>file</i>.</td>
  </tr>
  <tr>
    <td>-ctime <i>n</i></td>
    <td>Match files or directories whose contents or attributes were last modified <i>n</i>*24 hours ago.</td>
  </tr>
  <tr>
    <td>-empty</td>
    <td>Match empty files and directories.</td>
  </tr>
  <tr>
    <td>-group <i>name</i></td>
    <td>Match file or directories belonging to group <i>name</i>. <i>name</i> may be expressed either as a group name or as a numeric group ID.</td>
  </tr>
  <tr>
    <td>-iname <i>pattern</i></td>
    <td>Like the -name test but cas-insensitive.</td>
  </tr>
  <tr>
    <td>inum <i>n</i></td>
    <td>Match files with inode number <i>n</i>. This is helpful for finding all the hard links to a particular inode.</td>
  </tr>
  <tr>
    <td>-mmin <i>n</i></td>
    <td>Match files or directories whose contents were last modified <i>n</i> minutes ago.</td>
  </tr>
  <tr>
    <td>-mtime <i>n</i></td>
    <td>Match files or directories whose contents were last modified <i>n</i>*24 hours ago.</td>
  </tr>
  <tr>
    <td>-name <i>pattern</i></td>
    <td>Match files and directories with the specified wildcard pattern.</td>
  </tr>
  <tr>
    <td>-newer <i>file</i></td>
    <td>Match files and directories whose contents were modified more recently than the specified <i>file</i>. This is useful when writing shell scripts that perform file backups. Each time you make a backup, update a file (such as a long) and then use find to determine which files have changed since the last update.</td>
  </tr>
  <tr>
    <td>-nouser</td>
    <td>Match file and directories that do not belong to a valid user. This can be used to find files belonging to deleted accounts or to detect activity by attackers.</td>
  </tr>
  <tr>
    <td>-nogroup</td>
    <td>Match files and directories that do not belong to a valid group.</td>
  </tr>
  <tr>
    <td>-perm <i>mode</i></td>
    <td>Match files or directories that have permissions set to the specified <i>mode</i>. <i>mode</i> can be expressed by either octal or symbolic notation.</td>
  </tr>
  <tr>
    <td>-samefile <i>name</i></td>
    <td>Similar to the -inum test. Match files that share the same inode number as file <i>name</i>.</td>
  </tr>
  <tr>
    <td>-size <i>n</i></td>
    <td>Match files of size <i>n</i>.</td>
  </tr>
  <tr>
    <td>-type <i>c</i></td>
    <td>Match files of type <i>c</i>.</td>
  </tr>
  <tr>
    <td>-user <i>name</i></td>
    <td>Match files or directories belonging to user <i>name</i>. The user may be expressed as a username or by a numeric user ID.</td>
  </tr>
</table>

### 16.4 `find` Logical Operators
<table>
  <tr>
    <td><b>Operator</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>-and</td>
    <td>Match if the tests on both sides of the operator are true. This can be shortened to -a. Note that when no operator is present, -and is implied by default.</td>
  </tr>
  <tr>
    <td>-or</td>
    <td>Match if a test on either side of the oeprator is true. This can be shortened to -o.</td>
  </tr>
  <tr>
    <td>-not</td>
    <td>Match if the test following the operator is false. This can be abbreviated with an exclamation point (!).</td>
  </tr>
  <tr>
    <td>( )</td>
    <td>Group tests and operators together to form larger expressions. This is used to control the precedence of the logical evaluations. By default, find evaluates from left to right. It is often necessary to override the default evaluation order to obtain the desired result. Even if not needed, it is helpful sometimes to include the grouping characters to improve the readability of the command. Note that since the parentheses have special meaning to the shell, they must be quoted when using them on the same command line to allow them to be passed as arguments to find. Usually the backslash character is used to escape them.</td>
  </tr>
</table>

### 16.5 `find` AND/OR Logic
<table>
  <tr>
    <td><b>Results of expr1</b></td>
    <td><b>Operator</b></td>
    <td><b>expr2 is ...</b></td>
  </tr>
  <tr>
    <td>True</td>
    <td>-and</td>
    <td>Always performed</td>
  </tr>
  <tr>
    <td>False</td>
    <td>-and</td>
    <td>Never performed</td>
  </tr>
  <tr>
    <td>True</td>
    <td>-or</td>
    <td>Never performed</td>
  </tr>
  <tr>
    <td>False</td>
    <td>-or</td>
    <td>Always performed</td>
  </tr>
</table>

### 16.6 Predefined `find` Actions
<table>
  <tr>
    <td><b>Action</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>-delete</td>
    <td>Delete the currently matching file.</td>
  </tr>
  <tr>
    <td>-ls</td>
    <td>Perform the equivalent of ls -dils on the matching file. Output is sent to standard output.</td>
  </tr>
  <tr>
    <td>-print</td>
    <td>Output the full pathname of the matching file to standard output. This is the default action if no other action is specified.</td>
  </tr>
  <tr>
    <td>-quit</td>
    <td>Quit once a match has been made.</td>
  </tr>
</table>

### 16.7 Commonly Used `find` Options
<table>
  <tr>
    <td><b>Option</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>-depth</td>
    <td>Direct find to process a directory's files before the directory itself. This option is automatically applied when the -delete action is specified.</td>
  </tr>
  <tr>
    <td>-maxdepth <i>levels</i></td>
    <td>Set the maximum number of levels that find will descend into a directory tree when performing tests and actions.</td>
  </tr>
  <tr>
    <td>-mindepth <i>levels</i></td>
    <td>Set the minimum number of levels that find will descend into a directory tree before applying tests and actions.</td>
  </tr>
  <tr>
    <td>-mount</td>
    <td>Direct find not to traverse directories that are mounted on other file systems.</td>
  </tr>
  <tr>
    <td>-noleaf</td>
    <td>Direct find not to optimize its search based on the assumption that it is searching a Unix-like file system. This is neeed when scanning DOS/Windows file systems and CD-ROMs.</td>
  </tr>
</table>

## 17. Archiving and Backup
`gzip` Compress or expand files<br/>
`bzip2` A block sorting file compressor<br/>
`tar` Tape archiving utility<br/>
`zip` Package and compress files<br/>
`rsync` Remote file and directory synchronization<br/>

### 17.1 `gzip` Options
<table>
  <tr>
    <td><b>Option</b></td>
    <td><b>Long Option</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>-c</td>
    <td>--stdout<br/>--to-stdout</td>
    <td>Write output to standard output and keep the original files.</td>
  </tr>
  <tr>
    <td>-d</td>
    <td>--decompress<br/>--uncompress</td>
    <td>Decompress. This causes gzip to act like gunzip.</td>
  </tr>
  <tr>
    <td>-f</td>
    <td>--force</td>
    <td>Force compression even if a compressed version of the original file already exists.</td>
  </tr>
  <tr>
    <td>-h</td>
    <td>--help</td>
    <td>Display usage information.</td>
  </tr>
  <tr>
    <td>-l</td>
    <td>--list</td>
    <td>List compression statistics for each file compressed.</td>
  </tr>
  <tr>
    <td>-r</td>
    <td>--recursive</td>
    <td>If one or more arguments on the command line is a directory, recursively compress files contained within them.</td>
  </tr>
  <tr>
    <td>-t</td>
    <td>--test</td>
    <td>Test the integrity of a compressed file.</td>
  </tr>
  <tr>
    <td>-v</td>
    <td>--verbose</td>
    <td>Display verbose messages while compressing.</td>
  </tr>
  <tr>
    <td>-<i>number</i></td>
    <td></td>
    <td>Set amount of compression. <i>number</i> is an integer in the range of 1 (fastest, least compression) to 9 (slowest, most compression). The values 1 and 9 may also be expressed as --fast and --best, respectively. The default value is 6.</td>
  </tr>
</table>

### 17.2 `tar` Modes
<table>
  <tr>
    <td><b>Mode</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>c</td>
    <td>Create an archive from a list o files and/or directories.</td>
  </tr>
  <tr>
    <td>x</td>
    <td>Extract an archive.</td>
  </tr>
  <tr>
    <td>r</td>
    <td>Append specified pathnames to the end of an archive.</td>
  </tr>
  <tr>
    <td>t</td>
    <td>List the contents of an archive.</td>
  </tr>
</table>

## 18. Regular Expressions

### 18.1 `grep` Options
<table>
  <tr>
    <td><b>Option</b></td>
    <td><b>Long option</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>-i</td>
    <td>--ignore-case</td>
    <td>Ignore case. Do not distinguish between uppercase and lowercase characters.</td>
  </tr>
  <tr>
    <td>-v</td>
    <td>--invert-match</td>
    <td>Invert match. Normally, grep prints lines that contain a match. This option causes grep to print every line that does not contain a match.</td>
  </tr>
  <tr>
    <td>-c</td>
    <td>--count</td>
    <td>Print the number of matches (or non-matches if the -v option is also specified) instead of the lines themselves.</td>
  </tr>
  <tr>
    <td>-l</td>
    <td>--files-with-matches</td>
    <td>Print the name of each file that contains a match instead of the lines themselves.</td>
  </tr>
  <tr>
    <td>-L</td>
    <td>--files-without-match</td>
    <td>Like the -l option, but print only the names of files that do not contain matches.</td>
  </tr>
  <tr>
    <td>-n</td>
    <td>--line-number</td>
    <td>Prefix each matching line with the number of the line within the file.</td>
  </tr>
  <tr>
    <td>-h</td>
    <td>--no-filename</td>
    <td>For multifile searches, suppress the output of filenames.</td>
  </tr>
</table>

### 18.2 POSIX Character Classes
<table>
  <tr>
    <td><b>Character class</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>[:alnum:]</td>
    <td>The alphanumeric characters. In ASCII, equivalent to: [A-Za-z0-9].</td>
  </tr>
  <tr>
    <td>[:word:]</td>
    <td>The same as [:alnum:], with the addition of the underscore (_) character.</td>
  </tr>
  <tr>
    <td>[:alpha:]</td>
    <td>The alphabetic characters. In ASCII, equivalent to: [A-Za-z].</td>
  </tr>
  <tr>
    <td>[:blank:]</td>
    <td>Includes the space and tab characters.</td>
  </tr>
  <tr>
    <td>[:cntrl:]</td>
    <td>The ASCII control codes. Includes the ASCII characters 0 through 31 and 127.</td>
  </tr>
  <tr>
    <td>[:digit:]</td>
    <td>The numerals 0 through 9.</td>
  </tr>
  <tr>
    <td>[:graph:]</td>
    <td>The visible characters. In ASCII, it includes characters 33 through 126.</td>
  </tr>
  <tr>
    <td>[:lower:]</td>
    <td>The lowercase characters.</td>
  </tr>
  <tr>
    <td>[:punct:]</td>
    <td>The puncutation characters. In ASCII, equivalent to: [-!"#$%&'()*+,./:;<=>?@[\\\]_`{|}~].</td>
  </tr>
  <tr>
    <td>[:print:]</td>
    <td>The printable characters. All the characters in [:graph:] plus the space character.</td>
  </tr>
  <tr>
    <td>[:space:]</td>
    <td>The whitespace characters including space, tab, carriage return, newline, vertical tab, and form feed. In ASCII, equivalent to [ \t\r\n\v\f].</td>
  </tr>
  <tr>
    <td>[:upper:]</td>
    <td>The uppercase characters.</td>
  </tr>
  <tr>
    <td>[:xdigit:]</td>
    <td>Characters used to express hexadecimal numbers. In ASCII, equivalent to: [0-9A-Fa-f].</td>
  </tr>
</table>

### 18.3 Specifying the Number of Matches
<table>
  <tr>
    <td><b>Specifier</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>{<i>n</i>}</td>
    <td>Match the preceding element if it occurs exactly <i>n</i> times.</td>
  </tr>
  <tr>
    <td>{<i>n</i>,<i>m</i>}</td>
    <td>Match the preceding element if it occurs at least <i>n</i> times but no more than <i>m</i> times.</td>
  </tr>
  <tr>
    <td>{<i>n</i>,}</td>
    <td>Match the preceding element if it occurs <i>n</i> or more times.</td>
  </tr>
  <tr>
    <td>{,<i>m</i>}</td>
    <td>Match the preceding element if it occurs no more than <i>m</i> times.</td>
  </tr>
</table>

## 19. Text Processing
`cat` Concatenate files and print on the standard output<br/>
`sort` Sort lines of text files<br/>
`uniq` Report or omit repeated lines<br/>
`cut` Remove sections from each line of files<br/>
`paste` Merge lines of files<br/>
`join` Join lines of two files on a common field<br/>
`comm` Compare two sorted files line by line<br/>
`diff` Compare files line by line<br/>
`patch` Apply a diff file to an original<br/>
`tr` Translate or delete characters<br/>
`sed` Stream editor for filtering and transforming text<br/>
`aspell` Interactive spellchecker<br/>

### 19.1 Common `sort` Options
<table>
  <tr>
    <td><b>Option</b></td>
    <td><b>Long option</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>-b</td>
    <td>--ignore-leading-blanks</td>
    <td>By default, sorting is performed on the entire line, starting with the first charcater in the line. This option causes <i>sort</i> to ignore leading spaces in lines and calculates sorting based on the first non-whitespace character on the line.</td>
  </tr>
  <tr>
    <td>-f</td>
    <td>--ignore-case</td>
    <td>Make sorting case-insensitive.</td>
  </tr>
  <tr>
    <td>-n</td>
    <td>--numeric-sort</td>
    <td>Perform sorting based on the numeric evaluation of a string. Using this option allows sorting to be performed on numeric values rather than alphabetic values.</td>
  </tr>
  <tr>
    <td>-r</td>
    <td>--reverse</td>
    <td>Sort in reverse order. Results are in descending rather than ascending order.</td>
  </tr>
  <tr>
    <td>-k</td>
    <td>--key=<i>field1</i>[,<i>field2</i>]</td>
    <td>Sort based on a key field located from <i>field1</i> to <i>field2</i> rather than the entire line. See the following discussion.</td>
  </tr>
  <tr>
    <td>-m</td>
    <td>--merge</td>
    <td>Treat each argument as the name of a presorted file. Merge multiple files into a single sorted result without performing any additional sorting.</td>
  </tr>
  <tr>
    <td>-o</td>
    <td>--output=<i>file</i></td>
    <td>Send sorted output to <i>file</i> rather than standard output.</td>
  </tr>
  <tr>
    <td>-t</td>
    <td>--field-separator=char</td>
    <td>Define the field-separator character. By default, fields are separated by spaces or tabs.</td>
  </tr>
</table>

### 19.2 Common `uniq` Options

<table>
  <tr>
    <td><b>Option</b></td>
    <td><b>Long option</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>-c</td>
    <td>--count</td>
    <td>Output a list of duplicate lines preceded by the number of times the line occurs.</td>
  </tr>
  <tr>
    <td>-d</td>
    <td>--repeated</td>
    <td>Output only repeated lines, rather than unique lines.</td>
  </tr>
  <tr>
    <td>-f <i>n</i></td>
    <td>--skip-fields=<i>n</i></td>
    <td>Ignore <i>n</i> leading fields in each line. Fields are separated by whitespace as they are in <i>sort</i>; however, unlike <i>sort</i>, <i>uniq</i> has no option for setting an alternate field separator.</td>
  </tr>
  <tr>
    <td>-i</td>
    <td>--ignore-case</td>
    <td>Ignore case during the line comparisons.</td>
  </tr>
  <tr>
    <td>-s <i>n</i></td>
    <td>--skip-chars=<i>n</i></td>
    <td>Skip (ignore) the leading <i>n</i> characters of each line.</td>
  </tr>
  <tr>
    <td>-u</td>
    <td>--unique</td>
    <td>Output only unique lines. Lines with duplicates are ignored.</td>
  </tr>
</table>

### 19.3 Cut Selection Options
<table>
  <tr>
    <td><b>Option</b></td>
    <td><b>Long option</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>-c <i>list</i></td>
    <td>--characters=<i>list</i></td>
    <td>Extract the portion of the line defined by <i>list</i>. The list may consist of one or more comma-separated numerical ranges.</td>
  </tr>
  <tr>
    <td>-f <i>list</i></td>
    <td>--fields=<i>list</i></td>
    <td>Extract one or more fields from the line as defined by <i>list</i>. The list may contain one or more fields or field ranges separated by commas.</td>
  </tr>
  <tr>
    <td>-d <i>delim</i></td>
    <td>--delimiter=<i>delim</i></td>
    <td>When -f is specified, use <i>delim</i> as the field delimiting character. By default, fields must be separated by a single tab character.</td>
  </tr>
  <tr>
    <td></td>
    <td>--complement</td>
    <td>Extract the entire line of text, except for those portions specified by -c and/or -f.</td>
  </tr>
</table>

### 19.4 `diff` Change Commands
<table>
  <tr>
    <td><b>Change</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td><i>r1ar2</i></td>
    <td>Append the lines at the position <i>r2</i> in the second file to the position <i>r1</i> in the first file.</td>
  </tr>
  <tr>
    <td><i>r1cr2</i></td>
    <td>Change (replace) the lines at position <i>r1</i> with the liens at the position <i>r2</i> in the second file.</td>
  </tr>
  <tr>
    <td><i>r1dr2</i></td>
    <td>Delete the lines in the first file at position <i>r1</i>, which would have appeared at range <i>r2</i> in the second file.</td>
  </tr>
</table>

### 19.5 `diff` Context Format Change Indicators
<table>
  <tr>
    <td><b>Indicator</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>blank</td>
    <td>A line shown for context. It does nto indicate a difference between the two files.</td>
  </tr>
  <tr>
    <td>-</td>
    <td>A line deleted. This line will appear in the first file but not in the second file.</td>
  </tr>
  <tr>
    <td>+</td>
    <td>A line added. This line will appear in the second file but not in the first file.</td>
  </tr>
  <tr>
    <td>!</td>
    <td>A line changed. The two versions of the line will be displayed, each in its respective section of the change group.</td>
  </tr>
</table>

### 19.6 `diff` Unified Format Change Indicators
<table>
  <tr>
    <td><b>Character</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>blank</td>
    <td>This line is shared by both files.</td>
  </tr>
  <tr>
    <td>-</td>
    <td>This line was removed from the first file.</td>
  </tr>
  <tr>
    <td>+</td>
    <td>This line was added to the first file.</td>
  </tr>
</table>

### 19.7 `sed` Address Notation
<table>
  <tr>
    <td><b>Address</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td><i>n</i></td>
    <td>A line number where <i>n</i> is a positive integer.</td>
  </tr>
  <tr>
    <td>$</td>
    <td>The last line.</td>
  </tr>
  <tr>
    <td>/<i>regexp</i>/</td>
    <td>Lines matching a POSIX basic regular expression. Note that the regular expression is delimited by slash characters. Optionally, the regular expression may be delimited by an alternate character, by specifying the expression with \<i>cregexpc</i>, where <i>c</i> is the alternate character.</td>
  </tr>
  <tr>
    <td><i>addr1</i>,<i>addr2</i></td>
    <td>A range of lines from <i>addr1</i> to <i>addr2</i>, inclusive. Addresses may be any of the single address forms listed earlier.</td>
  </tr>
  <tr>
    <td><i>first</i>~<i>step</i></td>
    <td>Match the line represented by the number <i>first</i> and then each subsequent line at <i>step</i> intervals. For example, <i>1</i>~<i>2</i> refers to each odd numbered line, and <i>5</i>~<i>5</i> referes to the fifth line and every fifth line thereafter.</td>
  </tr>
  <tr>
    <td><i>addr1</i>,+<i>n</i></td>
    <td>Match <i>addr1</i> and the following <i>n</i> lines.</td>
  </tr>
  <tr>
    <td><i>addr!</i></td>
    <td>Match all lines except <i>addr</i>, which may be any of the forms listed earlier.</td>
  </tr>
</table>

### 19.8 `sed` Basic Editing Commands
<table>
  <tr>
    <td><b>Command</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>=</td>
    <td>Output the current line number.</td>
  </tr>
  <tr>
    <td>a</td>
    <td>Append text after the current line.</td>
  </tr>
  <tr>
    <td>d</td>
    <td>Delete the current line.</td>
  </tr>
  <tr>
    <td>i</td>
    <td>Insert text in front of the current line.</td>
  </tr>
  <tr>
    <td>p</td>
    <td>Print the current line. By default, sed prints every line and only edits lines that match a specified address within the file. The default behavior can be overridden by specifying the -n option.</td>
  </tr>
  <tr>
    <td>q</td>
    <td>Exit sed without processing any more lines. If the -n option is not specified, output the current line.</td>
  </tr>
  <tr>
    <td>Q</td>
    <td>Exit sed without processing any more lines.</td>
  </tr>
  <tr>
    <td>s/<i>regexp</i>/<i>replacement</i>/</td>
    <td>Substitute the contents of <i>replacement</i> wherever <i>regexp</i> is found. <i>replacement</i> may include the special character &, which is equivalent to the text matched by <i>regexp</i>. In addition, <i>replacement</i> may include the sequences \1 through \9, which are the contents of the corresponding subexpressions in <i>regexp</i>. After the trailing slash following replacement, an optional flag may be specified to modify the s command's behavior.</td>
  </tr>
  <tr>
    <td>y/<i>set1</i>/<i>set2</i></td>
    <td>Perform transliteration by converting characters from <i>set1</i> to the corresponding characters in <i>set2</i>. Note that unlike tr, sed requires that both sets be of the same length.</td>
  </tr>
</table>

## 20. Formatting Output
`nl` Number lines<br/>
`fold` Wrap each line to a specified length<br/>
`fmt` A simple text formatter<br/>
`pr` Prepare text for printing<br/>
`printf` Format and print data<br/>
`groff` A document formatting system<br/>

### 20.1 `nl` Markup
<table>
  <tr>
    <td><b>Markup</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>\:\:\:</td>
    <td>Start of logical page header.</td>
  </tr>
  <tr>
    <td>\:\:</td>
    <td>Start of logical page body.</td>
  </tr>
  <tr>
    <td>\:</td>
    <td>Start of logical page footer.</td>
  </tr>
</table>

### 20.2 Common `nl` Options
<table>
  <tr>
    <td><b>Option</b></td>
    <td><b>Meaning</b></td>
  </tr>
  <tr>
    <td>-b <i>style</i></td>
    <td>Set body numbering to <i>style</i>, where <i>style</i> is one of the following:<br/>
      a = Number all lines.<br/>
      t = Number only non-blank lines. This is the default.<br/>
      n = None.<br/>
      <i>pregexp</i> = Number only lines matching basic regular expression <i>regexp</i>.</td>
  <tr/>
  <tr>
    <td>-f <i>style</i></td>
    <td>Set footer numbering to <i>style</i>. The default is n (none).</td>
  </tr>
  <tr>
    <td>-h <i>style</i></td>
    <td>Set header numbering to <i>style</i>. The default is n (none).</td>
  </tr>
  <tr>
    <td>-i <i>number</i></td>
    <td>Set page numbering increment to <i>number</i>. The default is 1.</td>
  </tr>
  <tr>
    <td>-n <i>format</i></td>
    <td>Sets numbering format to <i>format</i>, where <i>format</i> is one of the following:<br/>
      ln = Left justified, without leading zeros.<br/>
      rn = Right justified, without leading zeros. This is the default.<br/>
      rz = Right justified, with leading zeros.</td>
  <tr>
    <td>-p</td>
    <td>Do not reset page numbering at the beginning of each logical page.</td>
  </tr>
  <tr>
    <td>-s <i>string</i></td>
    <td>Add <i>string</i> to the end of each line number to create a separator. The default is a single tab character.</td>
  </tr>
  <tr>
    <td>-v <i>number</i></td>
    <td>Set the first line number of each logical page to <i>number</i>. The default is 1.</td>
  </tr>
  <tr>
    <td>-w <i>width</i></td>
    <td>Set the width of the line number field to <i>width</i>. The default is 6.</td>
  </tr>
</table>

### 20.3 `fmt` Options
<table>
  <tr>
    <td><b>Option</b></td>
    <td><b>Description</b></td>
  </tr>
  <tr>
    <td>-c</td>
    <td>Operate in crown <i>margin</i> mode. This preserves the indentation of the first two lines of a paragraph. Subsequent lines are alinged with the indentation of the second line.</td>
  </tr>
  <tr>
    <td>-p <i>string</i></td>
    <td>Format only those lines beginning with the prefix <i>string</i>. After formatting, the contents of <i>string</i> are prefixed to each reformatted line. This option can be used to format text in source code comments. For example, any programming language or configuration file that uses a # character to delineate a comment could be formatted by specifying -p '# ' so that only the comments will be formatted.</td>
  </tr>
  <tr>
    <td>-s</td>
    <td>Split-only mode. In this mode, lines will only be split to fit the specified column width. Short lines will not be joined to fill lines. This mode is useful when formatting text such as code where joining is not desired.</td>
  </tr>
  <tr>
    <td>-u</td>
    <td>Perform uniform spacing. This will apply traditional "typewriter-style" formatting to the text. This means a single space between words and two spaces between sentences. This mode is useful for removing <i>justification</i>, that is, text that has been padded with spaces to force alignment on both the left and right margins.</td>
  </tr>
  <tr>
    <td>-w <i>width</i></td>
    <td>Format text to fit within a column <i>width</i> characters wide. The default is 75 characters. Note: fmt actually formats lines slightly shorter than the specified width to allow for line balancing.</td>
  </tr>
</table>
