#git commands

🔧 System and Package Management
sudo apt-get update / sudo apt get update – Updates the list of available packages.

sudo apt-get upgrade – Upgrades all upgradable packages.

sudo apt install nginx – Installs the Nginx web server.

sudo apt purge nginx – Removes Nginx along with its configuration files.

🌐 Web Server (Nginx)
sudo vim index.nginx-debian.html – Opens the default Nginx web page file in Vim for editing.

systemctl status nginx – Checks the status of the Nginx service.

systemctl status – Displays status of all systemd services.

👥 User Management
sudo useradd -m user1 / user2 – Creates new users with home directories.

sudo passwd user1 / user2 – Sets passwords for new users.

su user1 – Switches to user1.

whoami – Displays the current user.

📂 Directory and File Navigation
cd, cd .., cd /home, cd ~, cd ubuntu, cd .ssh – Changes directories.

ls, ls -l, ls -a – Lists files in the current directory (detailed or hidden as needed).

pwd – Prints the current directory.

mkdir devops, mkdir git-devops – Creates directories.

tree – Displays directory structure (requires tree to be installed).

🔐 SSH Key Management
ssh-keygen – Generates a new SSH key pair.

cat id_ed25519, cat id_ed25519.pub – Displays private/public SSH key content.

🕒 System Info and Utilities
clear – Clears the terminal screen.

date – Displays the current date and time.

uptime – Shows system uptime.

💻 Git and Version Control
git init – Initializes a new Git repository.

git status – Shows the working tree status.

git add file1.txt file2.txt – Stages files for commit.

git commit -m "..." – Commits changes with a message.

git config --global user.name "name" – Sets the global Git username.

git config --global user.email "email" – Sets the global Git email.

git log, git log --oneline – Shows commit history.

git branch – Lists all Git branches.

git checkout -b dev – Creates and switches to a new branch named dev.

git checkout dev / master – Switches branches.

git switch master – Modern way to switch branches.

📄 File Operations
vim hello.txt, vim file1.txt – Opens file in Vim editor.

touch file1.txt file2.txt file3.txt – Creates empty files.

rm hello.txt, rm hello – Deletes files.

cat hello.txt – Displays contents of the file.

📜 Miscellaneous
snap info tree – Shows Snap package info for tree.

exit – Exits the current shell session.

history – Displays previously entered commands.

