## Samba in omrežna povezljivost

Opomba: ta članek je “work in progress” (bl4z)

Za nastavljanje deljivih map na Ubuntu Linnuxu in Windows XP sem uporabil sistemska orodja, na Mac OS-u pa program SharePoints http://www.hornware.com/sharepoints/

Uporaba deljivih map
Linux
mount -t smbfs //hp/free /mnt/free (windows disk d: prikljucim na /mnt/free)
Mac OS
mount -t smbfs //lucija/lucija /Volumes/lucija (linux mapo /home/lucija prikljucim na /Volumes/lucija)
Windows
net use g: \\g5\test (mac os mapo /Users/bl4z/Documents prikljucim na g:)
