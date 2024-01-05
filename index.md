> Email: prajwalnautiyal2003@gmailcom
> Location: GTA, Ontario, Canada
> Phone: +1 (365) 999-3537
> Linkedin: https://www.linkedin.com/in/prajwal-nautiyal-19205624a/

## Who am I?
* * *
I am Prajwal Nautiyal, a Cybersecurity student at Sheridan College. I'm passionate about cybersecurity as it is a domain which has a lot to learn and it keeps challenging me with new and interesting things. I am also very fascinated with computer systems and strive to learn more about them. I am a quick learner and a team player. I am always looking for opportunities to learn and grow. I am eager to explore new things and I am always up for a challenge, and would especially like to delve deeper into the field of cybersecurity and get a chance to develop my skills and knowledge.


## Education
* * *
### Honours Bachelor of Information Sciences (CyberSecurity)
#### Sheridan College, Oakville, Canada ---- 2022 – 2026
* 3.85 CGPA
* Entrance Scholarship recipient


## Professional Experience
* * *
### Student Researcher
#### Centre for Applied AI
#### Sheridan College, Oakville, Canada ---- January 2024 – Present 


## Certifications
* * *
* Google Cybersecurity Specialization Certificate
* Google Technical Support Fundamentals
* ISO/IEC 27001 Information Security Management Systems Awareness On-demand Training Course
* Working towards CompTIA Security+ certification


## Skills
* * *
* Familiarity with fundamental networking principles and protocols such as the OSI model, TCP/IP, Wi-Fi, and ARP.
* Skilled in Python, C/C++, Linux Command Line, and SQL.
* Clear and organized communication, interpersonal, and organizational skills in both oral and written forms.
* Capacity to tackle challenging problems due to good problem solving capabilities and manage stressful situations.
* Positively exceptional customer service abilities, consistently maintaining a professional attitude.


## PROJECTS
* * *
### [ARP spoofer](https://github.com/PrajwalNa/Spoofer)
This project is a Python script that uses the scapy library to spoof the MAC address and IP address of a network device and perform a `man in the middle` attack. It allows the user to intercept and modify the network traffic between a target device and the router. It also has a function to restore the original network configuration when the script is stopped.

#### Features of this project:
* Spoofing the MAC address and IP address of any network interface on the device using scapy.
* Taking user input via the command line using the argparse module to specify the target device and the router.
* Sending and receiving raw network packets using scapy and access and modify the fields in the packets.
* Performing a 'man in the middle' attack by sending spoofed ARP packets to the target device and the router, tricking them to send their traffic to the attacker.
* It can restore the original MAC address and IP address of the network interface and the ARP tables of the target device and the router when the script is terminated.

#### Challenges faced in this project:
* Learning how to use the scapy library to manipulate network packets and protocols at a low level.
* Implementing the logic and algorithm for the MAC address and IP address spoofing and the 'man in the middle' attack techniques.
* Accurately addressing the fields in the network packets and modifying them to perform the attack.
* Handling the exceptions and errors that may occur during the network operations.

#### Learning Outcomes:
* Python programming, especially using the scapy and argparse modules.
* Network security concepts, such as MAC address spoofing, IP address spoofing, and `man in the middle` attacks.
* Network analysis and troubleshooting tools, such as Wireshark and Nmap.
* Project management and documentation best practices in a code.


### [Network Scanner](https://github.com/PrajwalNa/NetScanner)
This project is a network scanning tool that can scan a given IP address or range of addresses for active devices and open ports. It can also identify the manufacturer of the network interface using an external API. The tool is written in Python and uses various concepts such as modularity, object-oriented programming, threading, and regular expressions.

#### Features of this project:
* Taking user input via the command line using the argparse module to specify the target IP address or range of addresses and validating the input.
* Using the scapy library to send and receive ARP packets to identify the active devices on the network.
* Probing for open ports by setting flags in the TCP header as seen in common techniques such as TCP Connect Scan, Stealth Scan (TCP SYN Scan), TCP ACK Scan, TCP Window Scan and UDP Scan.
* Using an external API to identify the manufacturer of the network interface of the active devices.
* Using the threading module to run multiple threads to distribute the workload over multiple threads and speed up the scanning process.
* Usage of regular expressions to validate the user input.

#### Challenges faced in this project:
* Learning about the various network scanning techniques, how they work and how flags are set in a TCP packet header.
* Implementing multithreading and compiling the data receieved from each thread to display it to the user.
* How Class objects work in Python and how to use them to store data and methods.
* Exception Handling for the various errors that may occur during the network operations and due to faulty user input.

#### Learning Outcomes:
* Python programming, especially using the scapy, argparse, threading and re modules.
* Network scanning techniques and how to implement them using Python.
* Multithreading and how to use it to distribute workload.
* Modularity and how to use it to make the code more readable and maintainable.


### [Palindrome Word Checker and other cool little programs in 8086 Assembly](https://github.com/PrajwalNa/ASM)
This is more of an ongoing project/learning adventure. I started learning 8086 microprosser assembly and the genereal x86 ISA since I was curious about how the computer works at a low level. I have written a few programs in assembly, such as a palindrome word checker, a basic encryption algorithm which encrypts a string using one Key if the first character input was 'M' and another Key otherwise. I have also tried looking into modern x86-64 assembly and ARM assembly. I am still learning and exploring this domain and I am very excited to learn more about it.

#### Features of this project:
* Handling I/O operations using the BIOS interrupts (int 16h).
* Using the stack to store and retrieve data.
* Using branching and looping to implement the logic of the program.
* Using Procedures and Macros to make the code more readable and maintainable.
* Handling memory operations and cursor postioning in 16 bit x86 ISA.

#### Challenges faced in this project:
* Different types of memory addressing modes and how to use them, learning about how many ways the processor allows you to access memory in a CISC architechure can really be interesting.
* Proper usage of the stack and how to use it to store and retrieve data, initially I was rather confused in my usage of stack as I was just doing an elaborate version of the `mov` instruction.
* Differnt BIOS interrupts and how to use them to perform I/O operations, I had to go through the pages of documentation to find the right interrupt for the operation I wanted to perform.
* Program Control Flow, it was quite an experience learning about the various conditional and unconditional jump alongside the different kinda of flag setting instructions and how to use them.

#### Learning Outcomes:
* Assembly programming, especially using the x86 ISA.
* How the computer works at a low level, how the processor executes instructions and how the memory is accessed.
* Stack operations and how to use it to store and retrieve data, especially useful in a microprocessor like 8086 which has limited number of registers.
* BIOS interrupts of 8086 microprocessor, modern processors run on kernal syscalls which differ based on the OS.