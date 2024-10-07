<p>wget https://go.dev/dl/go1.23.2.linux-amd64.tar.gz</p>
<p>┌──(kali㉿kali)-[~]<br />└─$ ls -at /usr/local/ <br />lib share sbin bin .. . etc man src include libexec games<br /> <br />┌──(kali㉿kali)-[~]<br />└─$ sudo tar -C /usr/local -xzf go1.23.2.linux-amd64.tar.gz<br /> <br />┌──(kali㉿kali)-[~]<br />└─$ ls -at /usr/local/ <br />. lib share sbin go bin .. etc man src include libexec games<br /> <br />┌──(kali㉿kali)-[~]<br />└─$ export PATH=$PATH:/usr/local/go/bin<br /> <br />┌──(kali㉿kali)-[~]<br />└─$ go version<br />go version go1.23.2 linux/amd64</p>

<p>&nbsp;</p>
