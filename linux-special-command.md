## Search in file special field (such as nginx log)
1. 'cat /var/log/nginx/access.log | awk {'print $1'} | sort -n | uniq -c'
2. 'stat filename': for fine special describe for any file we can use
3. 'rm {*.pdf,*.txt}' : remove all pdf and txt file
4. 'touch file{1..100}' : create file1 to file100
5. 'find /Location -iname *.pdf -exec rm -rf {} \;' :(find pdf file and then remove that)
6. 'find /etc/ -type file -size +1k -size -5k' :find all file in /etc by size between 1k and 5k
7. 'find /etc/ -type f -empety' : find all of emepty file
8. 'dd if=file.txt of=/tmp/file_dd.txt' : dd create a file or copy file
9. 'dd if=/dev/sda of=/dev/sdb' : copy disk to disk "we are using dd for check hdd read or writes speed"
10. 'dd if=/dev/zero of=/tmp/file_zero bs=1M count=1000' : (یک فایل می سازد با بلاک سایز 1MB و تعداد 1000 که می شود  1GB)
