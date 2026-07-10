■ Capture a quick health snapshot (CPU, memory, disk, network)
top : Displays realtime and dynamic CPU and memory usage.
htop :Displays user friendly,color coded and graphical view of processes.
df -h :Displays free and used disk space.
ping :test if a remote server is reachable by sending small data packet.
netstat -tuln:Shows all listing network ports on your system.This is erfect for checking if a service like(web server on port 80)is running correctly.

■ Trace logs for that service
journalctl -u <service> -n 50 :Dispalys the last 50 log entries for a specific systemd processes.

■ Write a mini runbook describing what you did and what you’d do next if things were worse.
dispaly realtime and dynamic CPU and memory usage(top command),dispalys user friendly,color coded and grahical view of processes(htop command),Displays free and used disk space(df -h),practiced some networking commands like ping and netstat -tuln and trace logs for that service by using journalctl -u <sevice> -n 50 command.
If things were worse then i follow three steps:
step1:Restart strategy-Restart strategy in Linux is a set of rules that tell system supervisor like
(systemd) what to do when background application or service crashs or stop unexpectedly.it act like a automated self healing checklist to get the application running again without human intervention.
step2: Increase log verbosity- Increase log verbosity means that tell computer program,website or app to write detail and much longer step by step diary of what it is doing instead of directly showing result or error.Increase log verbosity help developers to find and fix bugs easily. 
step3:collect strace-strace is diagonstic and debuging tool used to monitor how a program interacts with operating system.
