nmapcolor
==========

To use, just pipe nmap into `sed -f /path/to/nmapcolor`:

`./nmap -p80,53,22,23 127.0.0.1 192.168.1.1 | sed -f /path/to/nmapcolor`
