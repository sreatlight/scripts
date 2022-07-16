# scripts - metoca
Remove special characters from file then outputs in terminal

USAGE:
> metoca \<file>

EXAMPLE:
> metoca bad_file > much_better_file

  
# scripts - target-term
credit goes to @Jacob Vlijm ( stack overflow )

USAGE:
> target-term -set \<num>                      creates x terminal ( must be executed first )<br />
> target-term -run \<num> <command>            runs command in created terminal x<br />
> target-term -lbatch \<num> <linux_file>      runs command in created terminal x<br />
> target-term -wbatch \<num> <windows_file>    runs command in created terminal x<br />

EXAMPLE:
> target-term -set 1<br />
> target-term -run 1 hostname<br />
  
# scripts - basq
SQLi test with bash and curl - now with help inside ;)
Also OSCP friendly ... is just a curl

