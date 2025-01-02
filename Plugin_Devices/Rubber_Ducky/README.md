<h1>Hak5 Plugins</h1>

<h2>Description</h2>
Here we'll configure the USB Rubber Ducky to disable Windows Defender and make an HTTP request for a reverse shell script. View my demo here --><a href="https://youtu.be/Lwp7VJKKu5w?si=COM60IkqX5ZO7TK9">Demo Video</a><--<br />

<b>Step 1: Payload Development</b><br/>
For the USB Rubber Ducky there are several preconfigured payload that can perform singular task. They can be found <a href="https://github.com/hak5/usbrubberducky-payloads/tree/master/payloads">here</a>. 
<p align="center">
  <img src="./imgs/ducky_script_home.png"/>
</p>
<b>Step 2: Image SD</b><br/>
Next, we need to image the SD card. Preferrably with the Raspberry Pi Imager<br/><br/>
<b>Step 3: Connect to the P4wn_Pi Network</b><br/>
Once, connected to a device the P4wn Pi A.L.O.A will create it's own Wifi network that you can connect to. Once connected you can navigate to the GUI on http://172.24.0.1:8000:
<p align="center">
  <img src="./imgs/gui.png"/>
</p>
<b>Step 4: Execute the Attack</b><br/>
Now the you can input your custom HID script to execute your attack:
<p align="center">
  <img src="./imgs/attack.png"/>
</p>


<h2>Languages and Utilities Used</h2>
 
- <b>USB Rubber Ducky</b>
- <b>DuckyScript</b>
- <b>PowerShell</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Kali Linux</b>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
