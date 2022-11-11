# 0x05. Processes and signals
### Bash scripts:
* [0-what-is-my-pid](./0-what-is-my-pid) &larr; displays its own PID
* [1-list_your_processes](./1-list_your_processes) &larr; displays a list of currently running processes
  - Must show all processes, for all users, including those which might not have a TTY
  - Display in a user-oriented format
  - Show process hierarchy

* [2-show_your_bash_pid](./2-show_your_bash_pid) &larr; displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.
  - You cannot use pgrep
  - The third line of your script must be # shellcheck disable=SC2009 (for more info about ignoring shellcheck error here)

* [3-show_your_bash_pid_made_easy](./3-show_your_bash_pid_made_easy) &larr; displays the PID, along with the process name, of processes whose name contain the word bash.
  - You cannot use ps

* [4-to_infinity_and_beyond](./4-to_infinity_and_beyond) &larr; displays "To infinity and beyond indefinitely".
  - In between each iteration of the loop, add a sleep 2

* [5-dont_stop_me_now](./5-dont_stop_me_now) &larr; stops 4-to_infinity_and_beyond process.
  - You must use kill

* [6-stop_me_if_you_can](./6-stop_me_if_you_can) &larr; stops 4-to_infinity_and_beyond process.
  - You cannot use kill or killall

* [7-highlander](./7-highlander) &larr; displays:
  - To infinity and beyond indefinitely
  - With a sleep 2 in between each iteration
  - I am invincible!!! when receiving a SIGTERM signal

* [8-beheaded_process](./8-beheaded_process) &larr; kills the process 7-highlander.
