
#INSTALL UNZIP
<pre><code>apt update -y && apt upgrade -y && apt install unzip && apt install pip3</code></pre>
#Bot Digital Ocean
<pre><code>wget https://github.com/bowowiwendi/backup/raw/main/DigitalOcean-TeleBot-main.zip && unzip DigitalOcean-TeleBot-main.zip && pip install -r /root/DigitalOcean-TeleBot-main/requirements.txt</code></pre>
#CHANGE BOT TOKEN N ID
<pre><code>nano /root/DigitalOcean-TeleBot-main/config.json</code></pre>
#RUN
<pre><code>cd DigitalOcean-TeleBot-main</code></pre>
<pre><code>python3 main.py</code></pre>
