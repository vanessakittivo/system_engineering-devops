# 0x02-shell_redirections

This directory contains shell scripts focused on **I/O redirections**, file display, creation, manipulation, and filtering in Linux using Bash.

### Scripts:

- **0-hello_world**         → Prints “Hello, World” followed by a new line to stdout  
- **1-confused_smiley**     → Displays the confused smiley "(Ôo)'  
- **2-hellofile**           → Displays the content of `/etc/passwd`  
- **3-twofiles**            → Displays the content of `/etc/passwd` and `/etc/hosts`  
- **4-lastlines**           → Displays the last 10 lines of `/etc/passwd`  
- **5-firstlines**          → Displays the first 10 lines of `/etc/passwd`  
- **6-third_line**          → Displays the third line of the file `iacta` (without using `sed`)  
- **7-file**                → Creates a file named `\*\'"Best School"\'\\*$\?*****:)` containing the text `Best School`  
- **8-cwd_state**           → Writes the result of `ls -la` into the file `ls_cwd_content` (overwrites if exists)  
- **9-duplicate_last_line** → Duplicates the last line of the file `iacta`  
- **10-no_more_js**         → Deletes all regular files (not directories) with a `.js` extension in the current directory and all subdirectories  
