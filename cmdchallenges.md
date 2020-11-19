### Solution to Cmd Challenge

[cmd challenge](https://cmdchallenge.com) 

***

Solution1: 
- echo "hello world"

Solution2:
- pwd

Solution3: 
- ls

Solution4: 
- cat access.log 

Solution5: 
- tail -n 5 access.log 

Solution6:
- touch take-the-command-challenge

Solution7: 
- mkdir -p touch/files

Solution8:
- cp take-the-command-challenge tmp/files

Solution9:
- mv take-the-command-challenge tmp/files

Solution10:
- ln -s tmp/files/take-the-command-challenge take-the-command-challenge 

Solution11:
- find . -type f -delete

Solution12:
- find . -type f -name *.doc -exec rm -rf {} \;

Solution13:
- cat access.log | grep "GET"

Solution14: 
- egrep -r "500" | awk -F":" '{print $1}' | sort |uniq

Solution15:
- find . -type f -name access.log*
- find . -maxdepth 1 -type f -name "access.log*" -printf "%f\n" 

Solution16: 
- grep -hr 500 

Solution17:
- cat $(find . -type f -name "access.log*") | cut -d" " -f1

Solution18:
- find . -type f | wc -l 

Solution19:
- cat access.log | sort 

Solution20:
- grep GET access.log | wc -l 

Solution21:
- sed 's/\;/\n/g' split-me.txt

Solution22:
- echo {1..100}

Solution23:
- sed 's/challenges are difficult//g' -i **/*.txt   

Solution24:
-

Solution25:
- 

Solution26:
- 

Solution27:
- 

Solution28:
- 

Solution29:
- 

Solution30:
-

Solution31:
- 




