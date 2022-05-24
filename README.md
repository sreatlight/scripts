# scripts - metoca
Remove special characters from file then outputs in terminal

USAGE:
  metoca <file>

EXAMPLE:
  metoca bad_file > much_better

  
# scripts - target-term
 # credit goes to @Jacob Vlijm ( stack overflow )

USAGE:
  target-term -set <num>                      creates x terminal ( must be executed first )
  target-term -run <num> <command>            runs command in created terminal x
  target-term -lbatch <num> <linux_file>      runs command in created terminal x
  target-term -wbatch <num> <windows_file>    runs command in created terminal x

EXAMPLE:
  target-term -set 1
  target-term -run 1 hostname
  
