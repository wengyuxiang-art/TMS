ssh

ssh tsp journalctl (journal ctl to check system journal)
ssh tsp journal | grep ssh
ssh tsp journal | grep ssh | grep "Disconnect from"
ssh tsp 'journal | grep --line-buffer ssh | grep --line-buffer "Disconnect from"' > ssh.log
vim ssh.log

cat ssh.log | sed 's/.*Disconnect from//' | less
echo 'abaca' | sed 's/[ab]//'
echo 'abaca' | sed 's/[ab]//g'
echo 'abaca' | sed -E 's/(ab)*//g'

cat ssh.log | head -n5

cat ssh.log | sed 's/.*Disconnect from//' | wc -l (wc: word count; -l: by line)
cat ssh.log | sed 's/.*Disconnect from//' | sort  (sort: order)
cat ssh.log | sed 's/.*Disconnect from//' | sort | uniq -c (print unic item and count it)





