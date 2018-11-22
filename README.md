# masteruah
Master Business Intelligence and Data Science

Comandos usados hasta ahora:

Miguel@Miguel-PC MINGW64 ~
$ git config --global user.name 'Miguel Rodríguez Lozano'

Miguel@Miguel-PC MINGW64 ~
$ git config --global user.email 'migrodloz@gmail.com'

Miguel@Miguel-PC MINGW64 ~
$ ls -al ~/.ssh
ls: cannot access '/c/Users/Miguel/.ssh': No such file or directory

Miguel@Miguel-PC MINGW64 ~
$

Miguel@Miguel-PC MINGW64 ~
$

Miguel@Miguel-PC MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C "migrodloz@gmail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/Miguel/.ssh/id_rsa): y
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in y.
Your public key has been saved in y.pub.
The key fingerprint is:
SHA256:wLNcHhVvbOTAT2D4VtF4knwigxE++9HG2GhkuKjCSkk migrodloz@gmail.com
The key's randomart image is:
+---[RSA 4096]----+
|        o**+o=   |
|     . .o++*O +  |
|      + *.o**=   |
|     . B BoO.    |
| E    + S.= =    |
|...  .   o o     |
| oo .     .      |
|.. .             |
|.                |
+----[SHA256]-----+

Miguel@Miguel-PC MINGW64 ~
$ ls -al ~/.ssh
ls: cannot access '/c/Users/Miguel/.ssh': No such file or directory

Miguel@Miguel-PC MINGW64 ~
$ ls -la /ssh
ls: cannot access '/ssh': No such file or directory

Miguel@Miguel-PC MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Could not open a connection to your authentication agent.

Miguel@Miguel-PC MINGW64 ~
$ eval $(ssh-agent -s)
Agent pid 4600

Miguel@Miguel-PC MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
/c/Users/Miguel/.ssh/id_rsa: No such file or directory

Miguel@Miguel-PC MINGW64 ~
$ pwd
/c/Users/Miguel

Miguel@Miguel-PC MINGW64 ~
$ ls -la
total 6283
drwxr-xr-x 1 Miguel 197121       0 nov 22 18:31  ./
drwxr-xr-x 1 Miguel 197121       0 oct 30  2010  ../
drwxr-xr-x 1 Miguel 197121       0 nov 16 22:57  .codemix/
-rw-r--r-- 1 Miguel 197121     104 nov 16 22:49  .codemix.properties
drwxr-xr-x 1 Miguel 197121       0 nov 12 21:55  .conda/
drwxr-xr-x 1 Miguel 197121       0 nov 16 22:44  .eclipse/
-rw-r--r-- 1 Miguel 197121     195 nov 22 18:16  .gitconfig
drwxr-xr-x 1 Miguel 197121       0 nov 12 23:03  .idlerc/
drwxr-xr-x 1 Miguel 197121       0 nov 14 18:47  .matplotlib/
drwxr-xr-x 1 Miguel 197121       0 nov 19 19:53  .p2/
drwxr-xr-x 1 Miguel 197121       0 nov 14 20:37  .spyder2/
drwxr-xr-x 1 Miguel 197121       0 nov 16 22:44  .tooling/
drwxr-xr-x 1 Miguel 197121       0 nov 21 18:45  .VirtualBox/
drwxr-xr-x 1 Miguel 197121       0 oct 30  2010  AppData/
-rw-r--r-- 1 Miguel 197121    7192 ene  8  2012  compxlib.cfg
-rw-r--r-- 1 Miguel 197121  180076 ene  8  2012  compxlib.log
-rw-r--r-- 1 Miguel 197121  381594 ene  8  2012  compxlib.log.bak
lrwxrwxrwx 1 Miguel 197121      29 oct 30  2010 'Configuración local' -> /c/Users/Miguel/AppData/Local/
drwxr-xr-x 1 Miguel 197121       0 nov 19 23:25  Contacts/
lrwxrwxrwx 1 Miguel 197121      57 oct 30  2010  Cookies -> /c/Users/Miguel/AppData/Roaming/Microsoft/Windows/Cookies/
lrwxrwxrwx 1 Miguel 197121      31 oct 30  2010 'Datos de programa' -> /c/Users/Miguel/AppData/Roaming/
drwxr-xr-x 1 Miguel 197121       0 nov 22 16:30  Desktop/
drwxr-xr-x 1 Miguel 197121       0 nov 19 23:25  Documents/
drwxr-xr-x 1 Miguel 197121       0 nov 22 18:33  Downloads/
drwxr-xr-x 1 Miguel 197121       0 nov 17 15:36  eclipse-workspace/
lrwxrwxrwx 1 Miguel 197121      67 oct 30  2010 'Entorno de red' -> '/c/Users/Miguel/AppData/Roaming/Microsoft/Windows/Network Shortcuts'/
drwxr-xr-x 1 Miguel 197121       0 nov 19 23:25  Favorites/
lrwxrwxrwx 1 Miguel 197121      67 oct 30  2010  Impresoras -> '/c/Users/Miguel/AppData/Roaming/Microsoft/Windows/Printer Shortcuts'/
drwxr-xr-x 1 Miguel 197121       0 nov 19 23:25  Links/
lrwxrwxrwx 1 Miguel 197121      60 oct 30  2010 'Menú Inicio' -> '/c/Users/Miguel/AppData/Roaming/Microsoft/Windows/Start Menu'/
lrwxrwxrwx 1 Miguel 197121      25 oct 30  2010 'Mis documentos' -> /c/Users/Miguel/Documents/
-rw-r--r-- 1 Miguel 197121   54959 ene  8  2012  modelsim.ini
-rw-r--r-- 1 Miguel 197121   54910 ene  8  2012  modelsim.ini.bak
drwxr-xr-x 1 Miguel 197121       0 nov 19 23:25  Music/
-rw-r--r-- 1 Miguel 197121 2621440 nov 22 18:37  ntuser.dat
-rw-r--r-- 1 Miguel 197121  262144 nov 22 18:37  ntuser.dat.LOG1
-rw-r--r-- 1 Miguel 197121       0 oct 30  2010  ntuser.dat.LOG2
-rw-r--r-- 1 Miguel 197121   65536 oct 30  2010  NTUSER.DAT{016888bd-6c6f-11de-8d1d-001e0bcde3ec}.TM.blf
-rw-r--r-- 1 Miguel 197121  524288 oct 30  2010  NTUSER.DAT{016888bd-6c6f-11de-8d1d-001e0bcde3ec}.TMContainer00000000000000000001.regtrans-ms
-rw-r--r-- 1 Miguel 197121  524288 oct 30  2010  NTUSER.DAT{016888bd-6c6f-11de-8d1d-001e0bcde3ec}.TMContainer00000000000000000002.regtrans-ms
-rw-r--r-- 1 Miguel 197121   65536 ene  6  2012  ntuser.dat{43b8bc73-389b-11e1-ae5e-005056c00008}.TM.blf
-rw-r--r-- 1 Miguel 197121  524288 ene  6  2012  ntuser.dat{43b8bc73-389b-11e1-ae5e-005056c00008}.TMContainer00000000000000000001.regtrans-ms
-rw-r--r-- 1 Miguel 197121  524288 ene  6  2012  ntuser.dat{43b8bc73-389b-11e1-ae5e-005056c00008}.TMContainer00000000000000000002.regtrans-ms
-rw-r--r-- 1 Miguel 197121      20 oct 30  2010  ntuser.ini
drwxr-xr-x 1 Miguel 197121       0 nov 19 23:25  Pictures/
lrwxrwxrwx 1 Miguel 197121      59 oct 30  2010  Plantillas -> /c/Users/Miguel/AppData/Roaming/Microsoft/Windows/Templates/
lrwxrwxrwx 1 Miguel 197121      56 oct 30  2010  Reciente -> /c/Users/Miguel/AppData/Roaming/Microsoft/Windows/Recent/
drwxr-xr-x 1 Miguel 197121       0 nov 19 23:25 'Saved Games'/
drwxr-xr-x 1 Miguel 197121       0 nov 19 23:25  Searches/
lrwxrwxrwx 1 Miguel 197121      56 oct 30  2010  SendTo -> /c/Users/Miguel/AppData/Roaming/Microsoft/Windows/SendTo/
drwxr-xr-x 1 Miguel 197121       0 sep 16  2011  Tracing/
drwxr-xr-x 1 Miguel 197121       0 nov 19 23:25  Videos/
drwxr-xr-x 1 Miguel 197121       0 nov 16 19:26 'VirtualBox VMs'/
drwxr-xr-x 1 Miguel 197121       0 may 12  2015  workspace/
-rw-r--r-- 1 Miguel 197121    3326 nov 22 18:31  y
-rw-r--r-- 1 Miguel 197121     745 nov 22 18:31  y.pub

Miguel@Miguel-PC MINGW64 ~
$ ls -la | grep ssh

Miguel@Miguel-PC MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C "migrodloz@gmail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/Miguel/.ssh/id_rsa):
Created directory '/c/Users/Miguel/.ssh'.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/Miguel/.ssh/id_rsa.
Your public key has been saved in /c/Users/Miguel/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:wbo/htem0IVPNohsJBxhAKbHizcoCJtWRrTHBt9by6I migrodloz@gmail.com
The key's randomart image is:
+---[RSA 4096]----+
|.oo=+.           |
|o..o=...         |
|o o+o=..o.       |
|o*o.o+ o++.      |
|B.+   =oSo=      |
|o. . ..o.= .     |
|     Eo....      |
|      .o+ o      |
|       oo+       |
+----[SHA256]-----+

Miguel@Miguel-PC MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Enter passphrase for /c/Users/Miguel/.ssh/id_rsa:
Identity added: /c/Users/Miguel/.ssh/id_rsa (/c/Users/Miguel/.ssh/id_rsa)

Miguel@Miguel-PC MINGW64 ~
$ ls -la | grep ssh
drwxr-xr-x 1 Miguel 197121       0 nov 22 18:39 .ssh/

Miguel@Miguel-PC MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

Miguel@Miguel-PC MINGW64 ~
$ ssh -T git@github.com
The authenticity of host 'github.com (140.82.118.3)' can't be established.
RSA key fingerprint is SHA256:nThbg6kXUpJWGl7E1IGOCspRomTxdCARLviKw6E5SY8.
Are you sure you want to continue connecting (yes/no)? y
Please type 'yes' or 'no': yes
Warning: Permanently added 'github.com,140.82.118.3' (RSA) to the list of known hosts.
Hi migrodloz! You've successfully authenticated, but GitHub does not provide shell access.

Miguel@Miguel-PC MINGW64 ~
$ cd Desktop

Miguel@Miguel-PC MINGW64 ~/Desktop
$ ls
'Códigos Matlab - Aplicación'/   Diario_ejercicios_master.txt  'Ejercicios Master'/                     Entrega_Bloques_2_3_4.docx   Inglés/               'Rodriguez Lozano_Miguel_CV.pdf'
 desktop.ini                    'Documentación TFC'/           'Ejercicios propuestos1 - Bloque1.pdf'  'GitHub Desktop.lnk'*         masteruah/             TestResponse.docx
 Diario_apuntes_Master.txt       Eclipse.lnk*                  'Ejercicios propuestos2.pdf'            'Google Chrome.lnk'*          querys_peliculas.txt   Thumbs.db

Miguel@Miguel-PC MINGW64 ~/Desktop
$ cd masteruah

Miguel@Miguel-PC MINGW64 ~/Desktop/masteruah (master)
$ ls -la
total 13
drwxr-xr-x 1 Miguel 197121  0 nov 22 19:10 ./
drwxr-xr-x 1 Miguel 197121  0 nov 22 19:10 ../
drwxr-xr-x 1 Miguel 197121  0 nov 22 19:10 .git/
-rw-r--r-- 1 Miguel 197121 60 nov 22 19:10 README.md

Miguel@Miguel-PC MINGW64 ~/Desktop/masteruah (master)
$
