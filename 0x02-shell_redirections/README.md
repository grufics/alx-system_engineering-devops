SHELL I/O REDIRECTION AND FILTERS



TASK 0: echo "Hello, World"

TASK 1: echo "\"(Ôo)'"

TASK 2: cat /etc/passwd

TASK 3: cat /etc/{passwd,hosts}

TASK 4: tail /etc/passwd

TASK 5: head /etc/passwd

TASK 6: head -3 iacta | tail -1

TASK 7: echo "Best School" > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*:\)

TASK8: ls -la > ls_cwd_content

TASK 9: tail -1 iacta >> iacta

TASK 10: find . -type f -name "*.js" -delete

TASK 11:  find . -mindepth 1 -type d | wc -l

TASK 12: ls -t | head

TASK 13: sort | uniq -u

TASK 14: grep "root" /etc/passwd

TASK 15: grep "bin" /etc/passwd | wc -l

TASK 16: grep -A 3 "root" /etc/passwd

TASK 17: grep -v "bin" /etc/passwd

TASK 18: grep '^[[:alpha:]]' /etc/ssh/sshd_config

TASK 19: tr Ac Ze

TASK 20: tr -d 'cC'

TASK 21: rev

TASK 22: cut -d":" --fields=1,6 /etc/passwd | sort

TASK 23: find . -empty -printf "%f\n"

TASK 24: find . -type f -name "*.gif" -printf "%f\n"| rev | cut -d '.' -f2- | rev | LC_ALL=C sort -f

TASK 25: echo -ne $(cut -c-1 | tr -d '\n')'\n'

TASK 26: tail -n +2 | cut -f1 | sort | uniq -c | sort -nr | head -11 | tr -s ' ' | cut -d' ' -f3


