# Processes and Signals

In this project, I learned about handling process ID's and signals in Bash with `ps`, `pgrep`, `pkill`, `exit`, and `trap`.

## Tasks :page_with_curl:
0. What is my PID
	- [0-what-is-my-pid](https://github.com/SamuelIbanga5/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/0-what-is-my-pid): Bash script that displays its own PID.
1. List your processes
	- [1-list_your_processes](https://github.com/SamuelIbanga5/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/1-list_your_processes): Bash script that displays a list of currently runnin processes.
2. Show your Bash PID
	- [2-show_your_bash_pid](https://github.com/SamuelIbanga5/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/2-show_your_bash_pid): Bash script that displays lines containing the `bash` word, thus allowing you to easily get the PID of your Bash process.
3. Show your Bash PID made easy
	- [3-show_your_bash_pid_made_easy](https://github.com/SamuelIbanga5/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/3-show_your_bash_pid_made_easy): Bash script that displays the PID, along with the process name, of processes whose name contain the word `bash`.
4. To infinity and beyond
	- [4-to_infinity_and_beyond](https://github.com/SamuelIbanga5/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/4-to_infinity_and_beyond): Bash script that displays `To infinity and beyond` indefinitely.
5. Don't stop me now!
	- [5-dont_stop_me_now](https://github.com/SamuelIbanga5/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/5-dont_stop_me_now): Bash script that stops `4-to_infinity_and_beyond` process.
6. Stop me if you can
	- [6-stop_me_if_you_can](https://github.com/SamuelIbanga5/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/6-stop_me_if_you_can): Bash script that stops `4-to_infinity_and_beyond` process.
7. Highlander
	- [7-highlander](https://github.com/SamuelIbanga5/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/7-highlander): Bash script that displays: `To infinity and beyond` indefinitely with a `sleep 2` in between each iteration and `I am invincible!!!` wen receiving a `SIGTERM` signal.
8. Beheaded process
	- [8-beheaded_process](https://github.com/SamuelIbanga5/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/8-beheaded_process): Bash script that kills the process `7-highlander`.
9. Process and PID file
	- [100-process_and_pid_file](https://github.com/SamuelIbanga5/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/100-process_and_pid_file): Bash script that creates the file `/var/run/myscript.pid` containing its PID, displays `To infinity and beyond` indefinitely, displays `I hate the kill command` when receiving a SIGTERM signal, displays `Y U no love me?!` when receiving a SIGINT signal and deletes the file `/var/run/myscript.pid` and terminates itself when receiving a SIGQUIT or SIGTERM signal.
10. Manage my process
	- [101-manage_my_process](https://github.com/SamuelIbanga5/alx-system_engineering-devops/blob/master/0x05-processes_and_signals/101-manage_my_process): Bash script that indefinitely writes `Iam alive!` to the file `/tmp/my_process` and in between every `I am alive!` message, the program should pause for 2 seconds.
