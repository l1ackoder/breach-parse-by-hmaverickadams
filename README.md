# breach-parse
A tool for parsing breached passwords

---

Download breached password list from magnet located here: `magnet:?xt=urn:btih:7ffbcd8cee06aba2ce6561688cf68ce2addca0a3&dn=BreachCompilation&tr=udp%3A%2F%2Ftracker.openbittorrent.com%3A80&tr=udp%3A%2F%2Ftracker.leechers-paradise.org%3A6969&tr=udp%3A%2F%2Ftracker.coppersurfer.tk%3A6969&tr=udp%3A%2F%2Fglotorrents.pw%3A6969&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337`

---

# problems:

1. I dont see any use of the 'install.sh', so I removed it.
2. breach-parse.sh script limitation - the 41 GB complition folder need to be on /opt/breach-parse folder otherwise the script will not work. / you need to specify the directory every time.
   we often dont have that much space in main or C: drive. so that's a problem for me atlist.

---

# solution

Assuming you breach_complition folder is on /Example-drive/breach-parse

so just copy the 'breach-parse.sh' file to /Example-drive/breach-parse then just do:
`./breach-parse.sh @domain.com output.txt`

---

Original repo: https://github.com/hmaverickadams/breach-parse
