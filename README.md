# roundcubebruter
Bruteforce script for Roundcube webmail client. Can be applied during the pentest as part of webmail password spraying.


# Installation & Usage
```
git clone https://github.com/elkokc/roundcubebruter.git
cd roundcubebruter
pip install requests
python3 bruter.py -u http://192.168.179.145  -p P@ssw0rd --usernames usernames.txt -t 20
```


# Options
```
usage: bruter.py [-h] [--url URL] [--threads THREADS] [--usernames USERNAMES]
                 [--password PASSWORD]

Command line mode

optional arguments:
  -h, --help            show this help message and exit
  --url URL, -u URL     roundcube application URL
  --threads THREADS, -t THREADS
                        Number of Threads".
  --usernames USERNAMES
                        username file
  --password PASSWORD, -p PASSWORD
                        password to brute
```
