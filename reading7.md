# Ops Reading

## Reading 7

SSH Protocol:
This topic is important because we are accessing our lab computer remotely. This explains the process of what exactly is happening, instead of connecting and not understanding why.

What is the Secure Shell (SSH) Protocol? The SSH protocol is a method for secure remote login from one computer to another.  It provides several alternative options for strong authentication, and it protects communications security and integrity with strong encryption. It is a secure alternative to the non-protected login protocols (such as telnet, rlogin) and insecure file transfer methods (such as FTP).

What are the typical uses of the SSH protocol? The protocol is used in corporate networks for providing secure access for users and automated processes, interactive and automated file transfers, issuing remote commands, and managing network infrastructure and other mission-critical system components.

How does the SSH protocol work? The protocol works in the client-server model, which means that the connection is established by the SSH client connecting to the SSH server. The SSH client drives the connection setup process and uses public key cryptography to verify the identity of the SSH server. After the setup phase the SSH protocol uses strong symmetric encryption and hashing algorithms to ensure the privacy and integrity of the data that is exchanged between the client and server.

How is the data kept safe when transmitted between the SSH client and server? Data is kept safe by having strong authentifcation with SSH keys. Without these keys you are unable to access the data.

What is SFTP? SFTP is "SSH File Transfer Protocol" and it is used for secure file transfer protocol today. It runs over SSH, and is currently documented indraft-ietf-secsh-filexfer-02.

What is RDP? And how to use it: 
This is a part of our cirriculum and a tool we will be using in our careers. 

What is Windows Remote Desktop Connection? The Windows Remote Desktop Connection tool gives users the ability to connect to a remote Windows PC or server over the internet or on a local network, giving them full access to the tools and software installed on it.

What is RDP? RDP stands for "Remote Desktop Protocol", which allows remote users to see and use Windows on a device in another location. Key peripherals like your keyboard and mouse are shared with the remote machine, allowing you to use and control it as if you were sat right in front of it.

What is the RDP port number? Port number is 3389.

References:
https://www.comparitech.com/net-admin/what-is-rdp/

https://www.ssh.com/academy/ssh/protocol

## Things I want to know more about

