# command-line-kungfu

grep -E -v "^#|^$" file -E扩展正则表达式,-e是传统正则，-e不能用“|”  多个条件也可以 grep '111\\|222' ,
------
awk -F : '{print $1,$NF}' /etc/passwd |sort|column -t //format output to table//
------
grep -e "kw\|kw2\|kw3"
------
cp file{,.bak} ###quickly backup file###
-------
E:cp /etc/passwd{,.bak}
-----
  mkdir -p ~/home/{xiaowan,xianli,xiaoqian,xiaogou}
------
  echo 10.0.0.{0..8}
-----
mv file{.old,new}###quickly change a file'Extension###
-------
E: mv test.{txt,doc}
------- 
  mv test{,.doc}
-------
df -h |awk'{sum += $3} END {print sum}'###sum all the numbers in a given column of a text###

