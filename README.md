# Soundwire Server, a sound enhancer installation

# First Download SoundWire tarball
Goto `https://georgielabs.net/` and Choose The Linux 64-bit or whatever your os is.

![image](https://github.com/user-attachments/assets/870226b3-9459-46fc-add1-196763796a1a)

and Download the tarball. You will get something like this `SoundWire_Server_linux64.tar.gz`
Extract it and Run These Commands to install required dependencies

```
sudo apt-get install pavucontrol
suod apt-get update
suod apt update
sudo apt-get update
sudo apt-get install libportaudio2
sudo apt-get install sox
sudo apt-get install libqt5widgets5
sudo apt install libcurl4-openssl-dev
```

After that Goto `Firewall Configuration` from Linux Search Bar


![image](https://github.com/user-attachments/assets/149321b0-dc66-4b36-9910-72550eba5f5e)

and Turn off the `Firewall`

or open `59010 & 59011 UDP Ports` from firewall using `Terminal`.

# Install SoundWire App on Android
Run the ``/SoundWireServer/SoundWireServer` file and copy the address like `192.16.1.102` etc and paste in the `SoundWire Android App` and it will be connected 

# Change The Built-in Audio Profile
Click `Open Pulse Audio Volume Controle` button and goto configuration tab and change the `2nd` Built-in Audio Profile to Output if you only want Only Listen to Laptop Sound or Duplex if you want the input/output to be from Mobile
