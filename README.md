<h1>Hello All👋</h1>
<hr>
I made a Console ssh linux installation program from google cloud 
<img src="https://i.ibb.co/GcwjPJC/IMG-20230102-224608.jpg" width="330px" height="303px" />
<h1>GConsole</h1>
Google Console in terminal with ssh google cloud.
But it's still under development, be the first to try it :)<br>
Web site : <a href="https://warceuproject.dev">Warceu Project Dev</a>
<br>
<hr>
<h1>Screenshots</h1>
<img src="https://raw.githubusercontent.com/baphomate-inc/GConsole/main/img/IMG_20230103_003921.jpg" width="80px" height="80px" />  <img src="https://raw.githubusercontent.com/baphomate-inc/GConsole/main/img/IMG_20230103_003909.jpg" width="80px" height="80px" /> <img src="https://raw.githubusercontent.com/baphomate-inc/GConsole/main/img/IMG_20230103_003851.jpg" width="80px" height="80px" />   

<h1>Installations for termux</h1>

```bash
pkg install git -y
git clone https://github.com/WarceuProject/GConsole
cd GConsole 
chmod +x *
bash main.sh 
```
<br>
<b>Note: </b>
<br>
after the installation process is complete open a new tab or new session on the terminal (in order to reload the terminal).
Authenticate the ssh account from google cloud with the command:

```
gcloud auth login 
```

after that setup your ssh phrase key (follow the form provided) then
input command to start a console session: 

```
gcloud alpha cloud-shell 
```

if the above command has an error then use the command below:

```
gcloud alpha cloud-shell ssh --authorize-session
```
<hr>
<a href="https://saweria.co/baphomate">Donate via Saweria dana,ovo,gopay</a>

BTC address: 
``` 
15PgLTco7eBqFyCMy97Tm9wKKnYqQKsfNX
```
