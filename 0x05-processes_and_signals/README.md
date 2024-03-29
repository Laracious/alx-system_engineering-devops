# 0x05. Processes and signals

## Resources:books:
Read or watch:
* [Linux PID](https://intranet.hbtn.io/rltoken/FcpEdqz8hau7eEB0Pi8Ong)
* [Linux process](https://intranet.hbtn.io/rltoken/hX_t2YK0erLPbdTq0-uKwQ)
* [Linux signal](https://intranet.hbtn.io/rltoken/SojW4zvL8j1yaoa7_NM6rA)

---
## Learning Objectives:bulb:
What you should learn from this project:

* What is a PID
* What is a process
* How to find a process’ PID
* How to kill a process
* What is a signal
* What are the 2 signals that cannot be ignored

---

### [0. What is my PID](./0-what-is-my-pid)
* Write a Bash script that displays its own PID.


### [1. List your processes](./1-list_your_processes)
* Write a Bash script that displays a list of currently running processes.


### [2. Show your Bash PID](./2-show_your_bash_pid)
* Using your previous exercise command, write a Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.


### [3. Show your Bash PID made easy](./3-show_your_bash_pid_made_easy)
* Write a Bash script that displays the PID, along with the process name, of processes whose name contain the word bash.


### [4. To infinity and beyond](./4-to_infinity_and_beyond)
* Write a Bash script that displays To infinity and beyond indefinitely. 


### [5. Stop me now](./5-dont_stop_me_now)
* We stopped our 4-to_infinity_and_beyond process using ctrl+c in the previous task, there is actually another way to do this.


### [6. Stop me if you can](./4-to_infinity_and_beyond)
* Write a Bash script that stops 4-to_infinity_and_beyond process.


### [7. Highlander](./7-highlander)
* Write a Bash script that displays:
	* To infinity and beyond indefinitely
	* With a sleep 2 in between each iteration
	* I am invincible!!! when receiving a SIGTERM signal 


### [8. Beheaded process](./8-beheaded_process)
* Write a Bash script that kills the process 7-highlander.


### [9. Process and PID file](./100-process_and_pid_file)
* Write a Bash script that: 


### [10. Manage my process](./101-manage_my_process)
* Write a manage_my_process Bash script that:

	* Indefinitely writes I am alive! to the file /tmp/my_process
	* In between every I am alive! message, the program should pause for 2 seconds


### [11. Zombie](./102-zombie.c)
* Write a C program that creates 5 zombie processes.
