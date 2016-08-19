# command-line-kungfu

grep -E -v "^#|^$" file -E扩展正则表达式,-e是传统正则，-e不能用“|”  多个条件也可以 grep '111\\|222' ,

awk -F : '{print $1,$NF}' /etc/passwd |sort|column -t //format output to table//
