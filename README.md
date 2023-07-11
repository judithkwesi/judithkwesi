### Introduction
Hello everyone! I'm Judith Kwesiga, currently undergoing an exciting training program at RENU in Uganda. With a focus on software development, I'm expanding my skills in areas like [mention specific areas or technologies]. In this GitHub repository, I'll be documenting my progress, sharing projects, and offering insights into my learning journey. Join me as I embrace challenges, collaborate with peers, and explore the endless possibilities of technology.

Throughout this training, I'm grateful for the support and guidance provided by the RENU team and my fellow participants. Together, we're embarking on a journey of exploration and growth, pushing the boundaries of our understanding and capabilities. This repository serves as a resource for anyone curious about the training experience at RENU or interested in the technologies we're studying. Feel free to explore, provide feedback, or connect with me for questions, suggestions, or collaboration opportunities. Let's learn, code, and make a positive impact together!

### 3rd/July/2023

Today,we had a session on operating systems and version control, we delved into the fascinating world of Linux derivatives and Git. It was an enlightening session that explored the foundations of operating systems and the importance of version control in software development.

We began by discussing Linux derivatives, which are operating systems based on the Linux kernel. We examined popular distributions such as Ubuntu, Fedora, and CentOS, understanding their unique features, package managers, and user interfaces. Through interactive discussions and demonstrations, we explored the versatility, stability, and vast software ecosystem that Linux derivatives offer. Participants had the opportunity to gain hands-on experience with different distributions, installing them on virtual machines and exploring their functionalities.

Moving on to version control, we dived into the essential tool known as Git. We explored the concept of version control and its significance in managing changes to source code and collaborating with a team. Through practical examples and exercises, I learned the fundamental Git commands, including initialization, staging, committing and branching. We also explored remote repositories and the process of pushing and pulling changes using Git.

Throughout the session, we actively engaged in discussions, asking questions, and shared our experiences with Linux derivatives and Git. By the end of the session, we had a solid understanding of Linux derivatives and were equipped with the foundational knowledge of Git version control.

This session on operating systems and version control served as a stepping stone in building a strong technical foundation. I left with newfound knowledge and skills that will undoubtedly benefit them in their future endeavors as software developers or system administrators.

### 4th/July/2023

#### Ubuntu Server Installation on Virtual Machine with VNC Viewer and SSH Configuration.

Details:

1. Setting Up VNC Viewer:
   - Installed VNC Viewer on my physical machine.
   - Configured the virtual machine's network settings to enable VNC access.
   - Obtained the IP address of the virtual machine.
   - Launched VNC Viewer and entered the IP address of the virtual machine to establish a VNC connection.
   - Authenticated with the appropriate credentials when prompted, gaining graphical access to the virtual machine via VNC Viewer.

2. Ubuntu Server Installation:

   - Started the virtual machine and initiated the Ubuntu Server installation process.
   - Followed the installation prompts, providing necessary details such as language, location, and user credentials.
   - Completed the installation, allowing the virtual machine to boot into the Ubuntu Server environment.

3. Configuring SSH Without a Password:
   - Opened the terminal within the Ubuntu Server virtual machine.
   - Ran the command `ssh-keygen` to generate an SSH key pair.
   - Followed the prompts to generate the keys and saved them in the default location.
   - Used the `ssh-copy-id` command, along with my physical machine's IP address, to copy the public SSH key to the Ubuntu Server.
   - Entered my password when prompted to establish a secure connection without the need for a password.

Outcome:
The installation of Ubuntu Server on the virtual machine using VNC Viewer was successful. I can now access the Ubuntu Server interface graphically from my physical machine via VNC Viewer. Furthermore, by configuring SSH without a password, I am able to establish a secure SSH connection to the Ubuntu Server from my physical machine without the need for manual password entry.

Reflection:
The combination of Ubuntu Server, VNC Viewer, and SSH provides me with flexible remote access to the server. This setup allows me to efficiently manage and configure the Ubuntu Server environment from my physical machine. The elimination of password prompts during SSH authentication streamlines the remote access process, enhancing security and convenience. Overall, today's progress has significantly improved my ability to work with Ubuntu Server in a virtualized environment.

### 5th/July/2023

#### Installation of Docker on Ubuntu Server and Configuration of Pi-hole Using Docker Compose.

Details:

1. Docker Installation:
   - Started by updating the Ubuntu Server's package lists using the command `sudo apt update`.
   - Installed Docker using the snapd command `sudo snap install docker`.
   - Verified the installation by running `sudo docker run hello-world`.

2. Pi-hole Configuration Using Docker Compose:
   - Created a directory for the Pi-hole configuration and navigated to it using `mkdir pihole && cd pihole`.
   - Created a `docker-compose.yml` file to define the Pi-hole and its dependencies using Docker Compose.
   - Configured the necessary settings in the `docker-compose.yml` file, such as DNS server, time zone, and web admin password.
   - Ran the command `docker-compose up -d` to start the Pi-hole container and its dependencies in detached mode.

3. Accessing Pi-hole Web Interface:
   - Opened a web browser on my local machine and entered the IP address of the Ubuntu Server running Pi-hole.
   - Navigated to the Pi-hole web interface by appending `admin` to the IP address (e.g., `http://<server_ip_address>/admin`).
   - Successfully accessed the Pi-hole web interface, gaining control over network-wide ad-blocking and privacy settings.

Outcome:
The installation of Docker on Ubuntu Server and the configuration of Pi-hole using Docker Compose were successfully completed. The setup allowed me to access the Pi-hole web interface through my web browser, granting control over network-wide ad-blocking and privacy settings.

Reflection:
By utilizing Docker, I simplified the deployment and management of Pi-hole, enabling convenient access to its web interface. This setup offers a centralized ad-blocking solution for my network. The combination of Docker, Ubuntu Server, and Pi-hole through Docker Compose provides a flexible and scalable solution for managing network-wide ad-blocking and DNS resolution.

### 6th/July/2023

#### Installation of Windows Server 2016 on a Virtual Machine with Active Directory Configuration and User Creation.

Details:

1. Windows Server 2016 Installation:
   - Started the virtual machine using vnc viewer and initiated the Windows Server 2016 installation process.
   - Followed the installation prompts, providing necessary details such as language, location, and user credentials.
   - Completed the installation, allowing the virtual machine to boot into the Windows Server 2016 environment.

2. Active Directory Configuration:
   - Accessed the Windows Server 2016 virtual machine and logged in using the administrator credentials.
   - Opened the Server Manager and navigated to the "Manage" menu.
   - Selected the "Add Roles and Features" option to launch the installation wizard.
   - Chose the Active Directory Domain Services (AD DS) role and proceeded with the installation.
   - Configured the domain name, forest functional level, and additional AD DS options as per requirements.
   - Completed the installation process, allowing the server to function as an Active Directory domain controller.

3. User Account Creation:
   - Accessed the Active Directory Users and Computers management console.
   - Navigated to the appropriate organizational unit (OU) or created a new one.
   - Right-clicked on the OU and selected "New" -> "User" to create a new user account.
   - Provided the necessary user details, including username, password, and other optional information.
   - Repeated the previous step to create a second user account.

Outcome:
The installation of Windows Server 2016 on the virtual machine, configuration of the Active Directory, and creation of two user accounts were successfully completed. This enabled me to establish an Active Directory environment and effectively manage user accounts within the Windows Server 2016 system.

Reflection:
The installation and configuration process for Windows Server 2016 and Active Directory allowed me to explore and experience the functionalities of a Windows domain controller. The creation of user accounts demonstrated how the Active Directory simplifies user management and centralizes authentication and authorization within a network environment. Understanding these concepts and gaining hands-on experience with Windows Server 2016 and Active Directory broadened my knowledge of Windows-based server systems.

### 7th/July/2023

#### Creation of TryHackMe Account and Introduction to Pre-Security and Vulnerabilities

Details:

1. Creating a TryHackMe Account:
   - Visited the TryHackMe website at tryhackme.com.
   - Clicked on the "Sign Up" button to initiate the account creation process.
   - Provided the required details, including username, email address, and password.
   - Completed the registration process by following the on-screen prompts.
   - Verified the account through the email confirmation link sent by TryHackMe.
   - Logged into the TryHackMe platform using the newly created credentials.

2. Introduction to Pre-Security:
   - Pre-Security refers to the proactive measures and strategies implemented to identify and mitigate potential security risks before they are exploited by attackers.
   - Pre-Security involves activities such as risk assessment, vulnerability scanning, security awareness training, and implementing best practices.
   - By adopting a pre-security mindset, individuals and organizations can better protect their systems and data from potential threats.

3. Understanding Vulnerabilities:
   - Vulnerabilities are weaknesses or flaws within software, systems, or networks that can be exploited by attackers to gain unauthorized access or compromise data.
   - Common types of vulnerabilities include software bugs, misconfigurations, weak passwords, and unpatched systems.
   - Vulnerabilities can be categorized as low, medium, or high severity based on their potential impact and likelihood of exploitation.
   - It is essential to identify and address vulnerabilities through regular patching, security updates, and implementing secure coding practices.

Outcome:
The creation of a TryHackMe account provided me with a platform to engage in practical cybersecurity learning and exercises. Additionally, the introduction to pre-security and vulnerabilities enhanced my understanding of proactive security measures and the importance of addressing potential weaknesses to protect systems and data.

Reflection:
Creating a TryHackMe account opened up a world of hands-on learning opportunities in the realm of cybersecurity. By immersing myself in practical exercises and challenges, I can gain valuable experience in identifying vulnerabilities and implementing pre-security measures. This knowledge is crucial in the ever-evolving landscape of cybersecurity, where proactive defense is vital to staying ahead of potential threats. The TryHackMe platform serves as an excellent resource to develop and enhance my skills in this dynamic field.
<!--
**judithkwesi/judithkwesi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.


Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

-->
