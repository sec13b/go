<p># go<br />go version go1.23.2 linux/amd64&lt;br&gt;</p>
<p>┌──(kali㉿kali)-[~]<br />└─$ ls -at /usr/local/ <br />lib share sbin bin .. . etc man src include libexec games<br /> <br />┌──(kali㉿kali)-[~]<br />└─$ sudo tar -C /usr/local -xzf go1.23.2.linux-amd64.tar.gz<br /> <br />┌──(kali㉿kali)-[~]<br />└─$ ls -at /usr/local/ <br />. lib share sbin go bin .. etc man src include libexec games<br /> <br />┌──(kali㉿kali)-[~]<br />└─$ export PATH=$PATH:/usr/local/go/bin<br /> <br />┌──(kali㉿kali)-[~]<br />└─$ go <br />Go is a tool for managing Go source code.</p>
<p>Usage:</p>
<p>go &lt;command&gt; [arguments]</p>
<p>The commands are:</p>
<p>bug start a bug report<br /> build compile packages and dependencies<br /> clean remove object files and cached files<br /> doc show documentation for package or symbol<br /> env print Go environment information<br /> fix update packages to use new APIs<br /> fmt gofmt (reformat) package sources<br /> generate generate Go files by processing source<br /> get add dependencies to current module and install them<br /> install compile and install packages and dependencies<br /> list list packages or modules<br /> mod module maintenance<br /> work workspace maintenance<br /> run compile and run Go program<br /> telemetry manage telemetry data and settings<br /> test test packages<br /> tool run specified go tool<br /> version print Go version<br /> vet report likely mistakes in packages</p>
<p>Use "go help &lt;command&gt;" for more information about a command.</p>
<p>Additional help topics:</p>
<p>buildconstraint build constraints<br /> buildmode build modes<br /> c calling between Go and C<br /> cache build and test caching<br /> environment environment variables<br /> filetype file types<br /> go.mod the go.mod file<br /> gopath GOPATH environment variable<br /> goproxy module proxy protocol<br /> importpath import path syntax<br /> modules modules, module versions, and more<br /> module-auth module authentication using go.sum<br /> packages package lists and patterns<br /> private configuration for downloading non-public code<br /> testflag testing flags<br /> testfunc testing functions<br /> vcs controlling version control with GOVCS</p>
<p>Use "go help &lt;topic&gt;" for more information about that topic.</p>
<p><br />┌──(kali㉿kali)-[~]<br />└─$ go version<br />go version go1.23.2 linux/amd64</p>
<p>┌──(kali㉿kali)-[~]</p>
<p>&nbsp;</p>
