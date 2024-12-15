<h1>Hak5 Plugins</h1>

<h2>Description</h2>
Here we'll configure the USB Rubber Ducky to disable Windows Defender and make an HTTP request for a reverse shell script.<br />

<b>Step 1: Payload Development</b><br/>
For the USB Rubber Ducky there are several preconfigured payload that can perform singular task. They can be found <a href="https://github.com/hak5/usbrubberducky-payloads/tree/master/payloads">here</a>. 
<p align="center">
  <img src="./imgs/ducky_script_home.png"/>
</p>
<b>Step 2: Modify Code</b><br/>
Like I said the code is premade so we need to alter it to feed our needs. In my case, I want the script to disable Windows Defender and give my Kali Machine a reverse shell. I've made the modifications and saved the code in this repository <a href="./Disable_AV_RevShell.txt">(HERE)</a>

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
