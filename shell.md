# basic usage

- date
- echo hello (print)
- echo 'hello world'
- echo hello\ world

# path

- echo $PATH (show all the path of computer)
- which echo
- pwd (corrent working directory)
- cd /home (change wording directory)
- cd ..(go to root(/))
- cd ./home
- ../../../bin/echo world
- ls (show all the files in corrent path)
- cd ~ (to home directory)
- cd ~/dev/pdos/classes/
- cd - (go to the last directory, do it again to go back)

# ls

- ls --help
- ls -l

# about file

- mv dotfiles.md foo.md
- cp dotfiles.md ../food.md
- rm ../food.md 
- rmdir (remove path)
- mkdir "my path" (make path)
- man ls

- ctrl_L (clear terminal and go back to the top)

# stream

- echo hello > hello.txt
- cat hello.txt (cat: print the context of file)
- cat < hello.txt
- cat < hello.txt > hello2.txt (overwrite)
- cat < hello.txt >> hello2.txt (append)

|: take the output of left and as the input of the right
- ls -l / | tail -n1 > ls.txt

# root

- sudo (guanliyuanmoshi)
- cd /sys (to kernal parameters)
- cd backlight/
- echo 500 > brightness
- sudo echo 500 > brightness
- sudo su (from $ to # (root))
- echo 1060 | sudo tee brightness (tee capter output and input it)

# tools

- foo=bar
- echo $foo
- echo "value is $foo"
- vim msd.sh
- source mcd.sh
- mcd test

- cp project{1,2}

- vim script.py
- python script.py a b c
- ./script.py a b c

- ls 
- ls project1
- ls priject1/src
- find . -name src -type d
- find . -path '**/test/*.py' -type f

- grep 

- history

- tree

- broot



