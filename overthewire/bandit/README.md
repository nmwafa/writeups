# Bandit

## Level 1

```bash
cat readme
```

## Level 2

```bash
cat ./-
```

## Level 3

```bash
cat ./'--spaces in this filename--'
```

## Level 4

```bash
cat inhere/...Hiding-From-You
```

## Level 5

```bash
grep -r '[a-z]' inhere
```

## Level 6

```bash
cat $(find ./inhere/ -size 1033c -type f)
```

## Level 7

```bash
cat $(find / -size 33c -user bandit7 -group bandit6 2>/dev/null)
```

## Level 8

```bash
grep millionth data.txt
```

## Level 9

```bash
sort data.txt | uniq -u
```

## Level 10

```bash
strings data.txt | grep ==
```

## Level 11

```bash
cat data.txt | base64 -d
```

## Level 12

```bash
cat data.txt | tr '[A-Za-z]' '[N-ZA-Mn-za-m]'
```

## Level 13

```bash
xxd -r data.txt output.txt
file output.txt
mv output.txt output.gz
gunzip output.gz
file output
mv output output.bzip2
bunzip2 output.bzip2
file output.bzip2.out
mv output.bzip2.out output.gz
gunzip output.gz
file output
mv output output.tar
tar xf output.tar
file data5.bin
mv data5.bin data5.tar
tar xf data5.tar
file data6.bin
mv data6.bin data6.bzip2
bunzip2 data6.bzip2
file data6.bzip2.out
mv data6.bzip2.out data7.tar
tar xf data7.tar
file data8.bin
mv data8.bin data8.gz
gunzip data8.gz
cat data8
```

## Level 14

```bash
scp -P 2220 bandit13@bandit.labs.overthewire.org:/home/bandit13/sshkey.private .
chmod 600 sshkey.private
ssh -i sshkey.private bandit14@bandit.labs.overthewire.org -p 2220
cat /etc/bandit_pass/bandit14
```

## Level 15

```bash
echo 'bandit14_password' | nc localhost 30000
```

## Level 16

```bash
openssl s_client -connect localhost:30001
# Then paste Level 15 password
```

## Level 17

```bash
nmap -sV localhost -p31000-32000
openssl s_client -connect localhost:31790 --quiet
# Then paste Level 16 password
ssh -i sshkey.private bandit17@bandit.labs.overthewire.org -p 2220
cat /etc/bandit_pass/bandit17
```

## Level 18

```bash
grep -wvf passwords.old passwords.new
```

## Level 19

```bash
ssh bandit18@bandit.labs.overthewire.org -p 2220 'ls'
ssh bandit18@bandit.labs.overthewire.org -p 2220 'cat readme'
```

## Level 20

```bash
./bandit20-do cat /etc/bandit_pass/bandit20
```

## Level 21

```bash
tmux
on window 0: nc -l -p 9999
on window 1: ./suconnect 9999 -> then paste level 20 password
on window 0: paste level 20 password
```

## Level 22

```bash
cat /etc/cron.d/cronjob_bandit22
cat /usr/bin/cronjob_bandit22.sh
cat /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
```

## Level 23

```bash

```
