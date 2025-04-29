## Installing Docker - Chapter Quiz

#### Question 1 of 3
Which of these statements is true about the docker client?

- [x] On the Mac, the Docker command-line client creates and runs containers in a small Linux-based virtual machine.
- [ ] On Windows 10 Anniversary Edition or later, the Docker command-line client creates and runs containers in a small, Linux-based virtual machine.
- [ ] On Mac and Windows, the Docker command-line client creates and runs containers natively without a virtual machine.
- [ ] Docker only runs natively on Windows 10 Anniversary Edition or higher. On the Mac, Docker creates and starts containers in a small, Linux-based VM.

#### Question 2 of 3
Your co-worker is having issues getting Docker to work on their Mac. They tell you that whenever they try to use docker run, they get an error that looks like this:
Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?
They told you that they installed Docker Desktop recently.
What would you first look for while troubleshooting this issue?

- [ ] Open the "System Information" application to verify that their system has enough installed memory available.
- [x] Check that the Docker whale is visible on their taskbar or system tray and that the boxes on top of it are NOT moving.
- [ ] Run the command env | grep DOCKER_HOST to confirm that the Docker CLI is configured properly.

#### Question 3 of 3
What are some common problems with using Docker Machine to run Docker?

- [ ] slow disk performance when using volume mounts
- [ ] Users need to know how to use and manage Virtualbox for common tasks.
- [x] all of these answers
- [ ] slow network performance while using exposed ports