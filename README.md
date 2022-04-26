# ft_irc
> Project for 42's school

Team's members : [Ala-Na](https://github.com/Ala-Na) and [opacaud](https://github.com/opacaud)

[![cboutier's 42 ft_irc Score](https://badge42.vercel.app/api/v2/cl1f9y1k8000609jsc4a29jay/project/2548071)](https://github.com/JaeSeoKim/badge42)

Validated on April 26th, 2022
100/100

Developing an IRC server in C++98. We chose *Irssi* as a client reference.  

**Commands implemented:**  
- Pass
- Nick
- User
- Oper
- Join
- Topic
- Mode for channels and users
- Part
- Names
- List
- Invite
- Kick
- Privmsg or msg with irssi
- Notice
- Kill
- Quit
- Whois
- Away
- Wallops
- Userhost
- MOTD
- Users
- Time
- Version

Usage:  
`make`  
`./ircserv <port_number> <password>`
`port_number` is the port number on which our IRC server will be listening to.  
`password` is the connection password needed by any IRC client trying to connect to our server.  
on *irssi*:  
`/connect localhost <port_number> <password> <nickname>`  

# Notes

RFC documentation: https://datatracker.ietf.org/doc/html/rfc2812  
References and notes on [this document](https://docs.google.com/document/d/16xAoAmThZic3RlpyD9NeFntM09t04uHakvTRUlIBTe4/edit)
