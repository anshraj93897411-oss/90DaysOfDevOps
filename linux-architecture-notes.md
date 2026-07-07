■ The core components of Linux (kernel, user space, init/systemd).
Kernel- It is core of Operating System(OS).Kernel has acess to talk directly to Hardware.
User space- User space also known as userland is a restricted memory region and execution environment where application,libraries and background services runs.
init/systemd- It is a first program that runs and it is responsible for booting process of OS. init is also known as parent of all programs.

■ How processes are created and managed.
In Linux,Processes are created by two distinct fork() and exec() system call and they are managed by kernel.

■ What systemd does and why it matters.
Systemd is first program that runs and it is responsible for booting process of OS. its quality of parallel execution process make it faster than init.Most of the modern distribution of Linux uses systemd.It matters because it is responsible for booting process.
