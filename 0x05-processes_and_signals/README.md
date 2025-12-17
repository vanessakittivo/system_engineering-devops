# 0x05-processes_and_signals

This directory contains Bash scripts focused on **Linux processes, PIDs, signals, process management, and signal handling**.

### Scripts:

- **0-what-is-my-pid**              → Displays the PID of the current script  
- **1-list_your_processes**         → Displays all running processes in a user-oriented hierarchical format  
- **2-show_your_bash_pid**          → Displays lines containing "bash" from the process list (finds Bash PIDs)  
  → Includes `# shellcheck disable=SC2009`  
- **3-show_your_bash_pid_made_easy** → Displays PID and process name for all processes containing "bash" (using `pgrep`)  
- **4-to_infinity_and_beyond**      → Displays "To infinity and beyond" indefinitely with a 2-second pause between iterations  
- **5-dont_stop_me_now**            → Stops the `4-to_infinity_and_beyond` process using `kill`  
- **6-stop_me_if_you_can**          → Stops the `4-to_infinity_and_beyond` process **without** using `kill` or `killall`  
- **7-highlander**                  → Displays "To infinity and beyond" indefinitely  
  → On receiving `SIGTERM`, prints "I am invincible!!!" and continues running  
- **8-beheaded_process**            → Forcibly kills the `7-highlander` process using `SIGKILL` (signal 9)
