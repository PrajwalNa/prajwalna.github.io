## This is my portfolio website

---

I'm a Cybersecurity student at Sheridan College. I'm passionate about cybersecurity as it is a domain which has a lot to learn and it keeps challenging me with new and interesting things. I am also very fascinated with computer systems and strive to learn more about them. I am a quick learner and a team player. I am always looking for opportunities to learn and grow. I am eager to explore new things and I am always up for a challenge, and would especially like to delve deeper into the field of cybersecurity and get a chance to develop my skills and knowledge.

[My Blog](https://kernelmode0x0.blogspot.com/)

## Education

---

### Honours Bachelor of Information Sciences (CyberSecurity)

Sep '22 – Aug '26 (Expected)

#### Sheridan College, Oakville, Canada

- 3.87 CGPA (Professional)
- Entrance Scholarship recipient

## Professional Experience

---

### CTF Developer

May 2024 – present

#### ISSessions

#### Sheridan College, Oakville, Canada

- Collaborated in a diverse team and created challenges incorporating actual malware techniques to get the challenge takers to experience real world techniques.
- Made both solo challenges and worked together in a team of 3 to create a group experience in form of multi stage challenges.


### Student Researcher

Jan '24 – Sep '24

#### Centre for Applied AI

#### Sheridan College, Oakville, Canada

- Worked in a team of 6 Researcher on the a Research Project titled “Objective Method for Diagnosis of Chronic Pain” in collaboration with Karmy Clinic.
- Conducted research on identifying pain through facial expressions using machine learning.
- Collaborated with a diverse team of researchers, fostering a collaborative environment to drive the project forward.
- Worked with Pytorch and OpenFace for a deep learning model for deception detection.
- Conducted comprehensive research on the software and related projects to deepen my understanding of the underlying technology and to identify innovative ideas for enhancing the software.

## Certifications

---

- [TCM Security Practical Junior Malware Researcher (PJMR)](https://certified.tcm-sec.com/c9fa9d80-317b-4e1f-a1b9-60af76303f84?key=1578e64a22c112f33e494c88b153c0f6298e51152b67cdb15010e96679ecd4a8)
- [Comptia Security+](https://www.credly.com/badges/f1890a8e-71d6-4adf-9846-4a0b9db36f37/linked_in_profile)
- [Google Cybersecurity Specialization Certificate](https://www.coursera.org/account/accomplishments/specialization/577FST5T7YGU)
- Working towards OSED!

## Skills

---

- Familiarity with fundamental networking principles and protocols such as the OSI model, TCP/IP, Wi-Fi, and ARP.
- Skilled in Python, C, Linux Command Line, and SQL.
- Knowlegde of x86 Assembly and Reverse Engineering.
- Clear and organized communication, interpersonal, and organizational skills in both oral and written forms.
- Capacity to tackle challenging problems due to good problem solving capabilities and manage stressful situations.
- Positively exceptional customer service abilities, consistently maintaining a professional attitude.

## Projects

---

### [My Attempts at Creating Shellcode](https://github.com/PrajwalNa/Shellcode)

- There are three different versions, each docmented and having a relevant blog post for them.
- The [first one](https://kernelmode0x0.blogspot.com/2024/08/windows-shellcoding.html) was made by taking inspiration from some samples I analysed while working towards my PJMR certification.
- The [second one](https://kernelmode0x0.blogspot.com/2024/08/windows-shellcoding-2.html) was an improvisation of the my initial attempt.
- Finally, [the last one](https://kernelmode0x0.blogspot.com/2024/09/windows-shellcoding-3-tcp-reverse-shell.html) was made after I researched into shellcoding practices and was able to learn how a null byte free shellcode can actually be achieved, I used a variation of this in one of the CTF challenges I helped create.

### [ARP spoofer](https://github.com/PrajwalNa/Spoofer)

- The project is a Python script that uses the scapy library to perform a **‘man in the middle’** attack by spoofing the MAC and IP addresses of a network device.
- It allows the user to **intercept** network traffic between a target device and the router.
- User input is taken via the command line using the **argparse module** to specify the target device and the router.
- When terminated, the script can restore the original network configuration.
- Challenges faced include learning to use the **scapy library**, implementing the logic for spoofing and the attack techniques, accurately addressing and modifying the fields in the network packets, and handling exceptions and errors.
- The project provided learning outcomes in Python programming, **network security concepts**, network analysis and troubleshooting tools, and project management and documentation best practices.

### [Network Scanner](https://github.com/PrajwalNa/NetScanner)

- The project is a **network scanning tool** written in Python, capable of scanning IP addresses for active devices and open ports.
- It uses the **argparse module** for user input, **scapy library** for sending/receiving ARP packets, and **regular expressions** for input validation.
- The tool probes for open ports using techniques like **TCP Connect Scan, Stealth Scan (TCP SYN Scan), TCP ACK Scan, TCP Window Scan, and UDP Scan**.
- It uses an **external API** to identify the manufacturer of the network interface of active devices.
- The project employs **multithreading** to distribute the workload and speed up the scanning process.
- Challenges faced include learning about network scanning techniques, implementing multithreading, understanding Python Class objects, and handling exceptions.
- The project resulted in learning outcomes in **Python programming**, network scanning techniques, multithreading, and modularity.

### [Palindrome Word Checker and other cool little programs in 8086 Assembly](https://github.com/PrajwalNa/ASM)

- The project is an ongoing learning adventure in understanding how computers work at a low level, focusing on **8086 microprocessor assembly** and the general **x86 ISA**.
- Several programs have been written in **assembly**, including a **palindrome word checker** and a **basic encryption algorithm**.
- The project features include handling **I/O operations** using **BIOS interrupts**, using the **stack** for data storage and retrieval, implementing program logic with **branching and looping**, and making code more readable with **procedures and macros**.
- Challenges faced include understanding different **memory addressing modes**, proper usage of the **stack**, finding the right **BIOS interrupt** for specific operations, and managing **program control flow**.
- The project has led to learning outcomes such as understanding **assembly programming**, **low-level computer operations**, **stack operations**, and **BIOS interrupts** of the 8086 microprocessor.
- The exploration and learning in this domain continue, with interest in **modern x86-64 assembly** and **ARM assembly**.
- Recently made a simple **paint application** in ASM, used **mouse initialisation** in 8086. [Check it out here](https://github.com/PrajwalNa/PaintASM)

### [Linear Regression Model](https://github.com/PrajwalNa/LinearModel)

- The project is a ML model created using PyTorch that implements a **linear regression model** using the **ADAM optimisation algorithm**.
- The model is trained on a dataset of random data points and is capable of predicting the output for new data points.
- The project uses **PyTorch** for creating the model, **matplotlib** for visualising the data and the model, and **cuda tensors** for tensor processing.
- I have learned about **gradient descent**, **backpropagation**, **optimisation algorithms**, **loss functions**, and **model evaluation**.
- The project has provided insights into **machine learning**, **deep learning**, **PyTorch**, and **data visualisation**.

### [Network Packet Sniffer](https://github.com/PrajwalNa/Sniffer)

- A tool made using C and the **socket programming API** that captures network packets and displays their contents.
- The tool uses **raw sockets** to capture packets at the **data link layer** and **packet filtering** to capture specific packets.
- Allows user to filter packets based on **IP address** and **protocol**.
- Helps in understanding the **structure of network packets**, **packet headers**, and **packet data**.
- The project has provided insights into **network programming**, **packet capturing**, **packet analysis**, and **socket programming**.
- Learned a lot about low-level network operations, **packet sniffing**, and **packet filtering** in linux kernel.
