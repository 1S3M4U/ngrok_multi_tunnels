<h3 align="center" font-size="20">
HI..<img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" width="30px"> welcome to my Github!!
</h3>
<br><br>
<h3>This short tips about how to use multiple tunnels in one command</h3>

<h4>Step 1 :</h4>

```
Download NGROK from https://ngrok.com/
```

<h4>Step 2 :</h4>

```
Register your account and login to ngrok dashboard
```

<h4>Step 3 : </h4>

```
 Copy Authentication token from your dashboard and paste your terminal to configure ngrok
```
<h4>Step 4 :</h4>

```
Now open configuration file
```
<ul>
  <li>For linux</li>  
  
  ``` ~/home/user/.ngrok2/filename.yml```
  <li>For Windows</li>
  
  ```C:/Users/username/.ngrok2/filename.yml```
</ul>

<h4>Step 5 :</h4>

```
Open filename.yml file in any editor and copy paste Step6
```
<h4>Step 6 :</h4>

```
authentoken:<your-auth-token>
tunnels:
  web:
      addr: 80
      proto: http
  rdp:
      addr: 3389
      proto: tcp
  ssh:
      addr: 22
      proto: tcp
```
<h5>Tips: here you can change the port in TCP and HTTP what you want</h5>

<h4>Step 7 :</h4>

```
Now save the file and close
```

<h4>Step 8 :</h4>

```
Open terminal or cmd and type step 9
```

<h4>Step 9 :</h4>
<ul>
  <li>For linux</li>
  
  ```./ngrok start --all``` or ```ngrok start --all```
  <li>For windows</li>
  
  ```ngrok.exe start --all```
</ul>

<h4>Step 10 : </h4>
<h3> Now you can see TCP and HTTP tunnels Works in same time</h3>


<p>GITHUB  :  https://github.com/1S3M4U</p>
<p>WEB     :  www.paladotkodotau</p>
<p>Email   :  isemau@uruskon.com</p>
