# DOS-Detector-and-IPS-Logs
## TP2 of Algorithms and Data structure

### Denial of service:
Our interest is to detect situations of overload of requests from the same client in a short time on the same server. This type of behavior is called a denial of service (DoS) attack when it is carried out maliciously, with the objective of increasing traffic until it is saturated, making it impossible for other legitimate users to access the services provided by that server.

### Logs: 
For this task, we will have Apache log files. Each log file represents the history of requests from a user to the resources provided by a particular server. These can be any type of files, from web pages (.html) to videos (.avi, .mov).

### Once the file that is passed to the console in log format has been processed, a command will be requested via the console. These commands can be:

- agregar_archivo <file_name>: completely processes a log file.

- ver_visitantes  <from> <to>: shows all the IPs that requested a resource on the server, within the determined IP range.

- ver_mas_visitados  <n>: shows the n most requested resources.

If a command is valid, it should print OK on standard output after being executed. If a command does not belong to those previously listed or has an error, Error in command <command> is printed on stderr and the execution is finished.

The program will not have a command to end. It ends when there are no more lines to process on standard input.
