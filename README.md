# command-line-kungfu

*grep -E -v "^#|^$" file 

awk -F : '{print $1,$NF}' /etc/passwd |sort|column -t //format output to table//
