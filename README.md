# Remote-Control-Linux-VNC

### Langkah 1 : Install Remmina
```code
sudo apt install remmina remmina-plugin-vnc
```
### Langkah 2 : Open Remmina
### Langkah 3 : Create New Connection 
    Name: Server Rust
    Protocol : Remmina VNC Plugin
    Server : 192.168.1.3
    Password : 1
    Show remote cursor : true
![Screenshot from 2023-08-16 06-36-24](https://github.com/jsmile631/remote-control-linux/assets/136232449/40cb678b-37c3-47ba-a356-7c6fa1e31fcc)
![Screenshot from 2023-08-16 06-38-59](https://github.com/jsmile631/remote-control-linux/assets/136232449/721dc4dc-d988-4707-9490-2edf4edf796d)
### Langkah 4 : Click Connect
------------------------------------------------------------------------------------
# Remote-Control-Linux-RDP
### Langkah 1 : Create New Connection 
    Basic:
        Name: Server Rust
        Protocol : RDP - Remote Desktop Protocol
        Server : 192.168.1.3
        Password : 1
    Advanced:
        Relax order Checks = true
        Glyph cache = true
![Screenshot from 2023-08-17 20-26-33](https://github.com/jsmile631/remote-control-linux/assets/136232449/f3294d91-5ec2-4903-b9d6-88b503bf934f)
![Screenshot from 2023-08-17 20-27-25](https://github.com/jsmile631/remote-control-linux/assets/136232449/fa4f6770-173e-4b55-84ae-d380ec270aa9)
### Langkah 2 : Login to Server Rust
    Session : Local Active Session
    Password : 1
![Screenshot from 2023-08-17 20-30-53](https://github.com/jsmile631/remote-control-linux/assets/136232449/93d829b5-003d-4ee3-9384-47199a636344)

----------------------------------------

# Transfer File via FileZilla

### Langkah 1 : Install FileZilla
    sudo apt-get install filezilla
### Langkah 2 : Open FileZilla
### Langkah 3 : Create New Site Connection
    File -> Site Manager -> New Site
### Langkah 3 : Settings for New Site
    Protocol : SFTP-SSH File Transfer Protocol
       Host  : 192.168.1.3
    
       Logon : Normal
        User : username
    Password : password
Connect!
    
