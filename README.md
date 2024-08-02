
#INSTALL UNZIP
<pre><code>apt update -y && apt upgrade -y && apt install unzip && apt install python3 && apt install wget</code></pre>
#Bot Digital Ocean
<pre><code>wget https://github.com/bowowiwendi/backup/raw/main/DigitalOcean-TeleBot-main.zip && unzip DigitalOcean-TeleBot-main.zip && pip install -r /root/DigitalOcean-TeleBot-main/requirements.txt</code></pre>
#CHANGE BOT TOKEN N ID
<pre><code>nano /root/DigitalOcean-TeleBot-main/config.json</code></pre>
#RUN
<pre><code>python3.8 /root/DigitalOcean-TeleBot-main/main.py</code></pre>
