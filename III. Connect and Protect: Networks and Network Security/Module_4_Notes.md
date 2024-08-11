# Security Hardening

**Security Hardening**: the process of strengthening a system to reduce the vulnerability and attack surface.
- operated on:
  - Hardware
  - OS
  - applications
  - computer networks
  - Databases 

**Attack Surface**: all the possible vulnerabilities and threat actor could exploit.
**Penetration Testing** (Pen testing): a simulated attack that helps identify vulnerabilities in systems, networks, websites, applications, and processess.

Security professionals will regularly maintain security hardening procedures to keep devices secure.
- physical security includes areas with security cameras or guards
- software updates (Patches) are common
- Pen testing
- remove unused ports, applications, or services and minimized access to reduce attack surface.

# OS Hardening

**Operating System (OS):** Interface between hardware and the user.
- The first program loaded when a PC turns on.

**Hardening tasks:**
- Performed only once as part of preliminary safety measures.
- Performed at regular intervals:
  - **Patch Update:** A software and operating system update that addresses security vulnerabilities within a program or product.
  - **Hardware and software disposal**
  - **Strong password policy**
  
**Baseline configuration (baseline image):** A documented set of specifications within a system that is used as a basis for future builds, releases, and updates.

**Multifactor authentication (MFA):** A security measure that requires a user to verify their identity in two or more ways to access a system or network.
- Something you know
- Something you have
- Something unique about you

# Brute force attacks and OS hardening

Brute force attack: a trial and error process of discovering private information
- simple: guessing
- dictionary: list of commonly used passwords and stolen credentials from previous breaches

Virtual machines (VMs): are software versions of physical computers.
- Add a layer of security from their ability to run code in an isolated environment
  - can be deleted and replaced with new VM image after testing malware
- useful to investigate infected machines or to run malware.
- ability to revert to previous states
- small risk a malicious program can escape virtualization and access the host machine

Sandbox environments: are for testing software or programs seperately from your network. They can be either physical PCs or cloud based VMs.
- test patches
- identifying bugs
- detecting cybersecurity vulnerabilities
- evaluating suspicious software or malicious code
- simulate attack scenarios

NOTE: attackers can program their malware to behave as harmless software when run inside sandbox environments via certain detection methods.

Prevention measures:
- hashing: converts info into a unique value that can be used to determine its integrity. A one way function, making decryption impossible.
- salting:  adds random characters to hashed passwords, increasing their complexity and thus security
- MFA / 2FA: requires several verifications a user is who they say they are in order to access a system or network
- CAPTCHA: Completely Automated Public Turing test to tell Computers and Humans Apart.
- reCAPTCHA: free CAPTCHA service from  Google that helps protect websites from bots and malicious software.
- Password policies: guidelines on how long or complex a password is, when to update it, and login attempts max.


