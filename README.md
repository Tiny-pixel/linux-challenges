Task 1:

recruit@recruit-Mecer-X102:~$ ls
Desktop  Documents  Downloads  Music  Pictures  Public  Templates  Videos
recruit@recruit-Mecer-X102:~$ pwd
/home/recruit
recruit@recruit-Mecer-X102:~$ mkdir workspace 
recruit@recruit-Mecer-X102:~$ cd workspace 
recruit@recruit-Mecer-X102:~/workspace$ ls 
recruit@recruit-Mecer-X102:~/workspace$ touch README.md
recruit@recruit-Mecer-X102:~/workspace$ cp README.md mv CHANGELOG.md 
cp: target 'CHANGELOG.md' is not a directory
recruit@recruit-Mecer-X102:~/workspace$ cp README.md
cp: missing destination file operand after 'README.md'
Try 'cp --help' for more information.
recruit@recruit-Mecer-X102:~/workspace$ cp README.md CHANGELOG.md
recruit@recruit-Mecer-X102:~/workspace$ 

Task 2:

recruit@recruit-Mecer-X102:~/workspace/tmp$ cd workspace
bash: cd: workspace: No such file or directory
recruit@recruit-Mecer-X102:~/workspace/tmp$ cd ~
recruit@recruit-Mecer-X102:~$ cd workspace
recruit@recruit-Mecer-X102:~/workspace$ touch exercise.md
recruit@recruit-Mecer-X102:~/workspace$ ls
CHANGELOG.md  exercise.md  README.md  tmp
recruit@recruit-Mecer-X102:~/workspace$ mv exercise.md tmp
recruit@recruit-Mecer-X102:~/workspace$ ls
CHANGELOG.md  README.md  tmp
recruit@recruit-Mecer-X102:~/workspace$ cd tmp
recruit@recruit-Mecer-X102:~/workspace/tmp$ ls
exercise.md
recruit@recruit-Mecer-X102:~/workspace/tmp$ rm exercise.md
recruit@recruit-Mecer-X102:~/workspace/tmp$ ls
recruit@recruit-Mecer-X102:~/workspace/tmp$ 

Task 3:

recruit@recruit-Mecer-X102:~/workspace/tmp$ cd ~
recruit@recruit-Mecer-X102:~$ cd workspace 
recruit@recruit-Mecer-X102:~/workspace$ ls
CHANGELOG.md  README.md  tmp
(1) recruit@recruit-Mecer-X102:~/workspace$ touch umuzi.md recruits.md cohort.md 
      recruit@recruit-Mecer-X102:~/workspace$ ls
     CHANGELOG.md  cohort.md  README.md  recruits.md  tmp  umuzi.md
(2) recruit@recruit-Mecer-X102:~/workspace$ echo "poetry can be hard, but MUB somehow made it better" >> umuzi.md 
(2) recruit@recruit-Mecer-X102:~/workspace$ echo "meeting new people can put you out of your comfort zone yet friends can be made here" >> recruits.md 
(2) recruit@recruit-Mecer-X102:~/workspace$ echo "being part of a cohortcan be inclusive, think i'm the only person whose part of 3!!!" >> cohort.md
echo "being part of a cohortcan be inclusive, think i'm the only person whose part of 3echo "meeting new people can put you out of your comfort zone yet friends can be made here" >> recruits.md !" >> cohort.md
recruit@recruit-Mecer-X102:~/workspace$ ls
CHANGELOG.md  cohort.md  README.md  recruits.md  tmp  umuzi.md
(3)  recruit@recruit-Mecer-X102:~/workspace$ cat umuzi.md recruits.md cohort.md
       poetry can be hard, but MUB somehow made it better 
      meeting new people can put you out of your comfort zone yet friends can be made here
      being part of a cohortcan be inclusive, think i'm the only person whose part of 3echo meeting                   new people can put you out of your comfort zone yet friends can be made here >> recruits.md !
recruit@recruit-Mecer-X102:~/workspace$ 
recruit@recruit-Mecer-X102:~/workspace$ 
recruit@recruit-Mecer-X102:~/workspace$ cat umuzi.md recruits.md cohort.md
poetry can be hard, but MUB somehow made it better
meeting new people can put you out of your comfort zone yet friends can be made here
being part of a cohortcan be inclusive, think i'm the only person whose part of 3!
(4)  recruit@recruit-Mecer-X102:~/workspace$ touch summary.md
recruit@recruit-Mecer-X102:~/workspace$ ls
CHANGELOG.md  cohort.md  README.md  recruits.md  summary.md  tmp  umuzi.md
recruit@recruit-Mecer-X102:~/workspace$ 
recruit@recruit-Mecer-X102:~/workspace$ 
(4)   recruit@recruit-Mecer-X102:~/workspace$ cat umuzi.md recruits.md cohort.md > summary.md 
recruit@recruit-Mecer-X102:~/workspace$ ls
CHANGELOG.md  cohort.md  README.md  recruits.md  summary.md  tmp  umuzi.md
recruit@recruit-Mecer-X102:~/workspace$ 
recruit@recruit-Mecer-X102:~/workspace$ 
recruit@recruit-Mecer-X102:~/workspace$ cat summary
cat: summary: No such file or directory
(4) recruit@recruit-Mecer-X102:~/workspace$ cat summary.md
poetry can be hard, but MUB somehow made it better
meeting new people can put you out of your comfort zone yet friends can be made here
being part of a cohortcan be inclusive, think i'm the only person whose part of 3!
(5) recruit@recruit-Mecer-X102:~/workspace$ echo "The End" >> summary.md
recruit@recruit-Mecer-X102:~/workspace$ 
recruit@recruit-Mecer-X102:~/workspace$ 
(5) recruit@recruit-Mecer-X102:~/workspace$ cat summary.md
poetry can be hard, but MUB somehow made it better
meeting new people can put you out of your comfort zone yet friends can be made here
being part of a cohortcan be inclusive, think i'm the only person whose part of 3!
The End
recruit@recruit-Mecer-X102:~/workspace$ 

Task 4:

recruit@recruit-Mecer-X102:~/workspace$ ls
CHANGELOG.md  cohort.md  README.md  recruits.md  search_result.md  summary.md  tmp  umuzi.md
recruit@recruit-Mecer-X102:~/workspace$ touch umuzi
recruit@recruit-Mecer-X102:~/workspace$ ls
CHANGELOG.md  cohort.md  README.md  recruits.md  search_result.md  summary.md  tmp  umuzi  umuzi.md
recruit@recruit-Mecer-X102:~/workspace$ locate umuzi
recruit@recruit-Mecer-X102:~/workspace$ 
recruit@recruit-Mecer-X102:~/workspace$ ls
CHANGELOG.md  cohort.md  README.md  recruits.md  search_result.md  summary.md  tmp  umuzi  umuzi.md
recruit@recruit-Mecer-X102:~/workspace$ locate umuzi > search_results.md
recruit@recruit-Mecer-X102:~/workspace$ cat search_results.md
recruit@recruit-Mecer-X102:~/workspace$ locate "umuzi"
recruit@recruit-Mecer-X102:~/workspace$ 
recruit@recruit-Mecer-X102:~/workspace$ locate umuzi > seacrh_results.md 
recruit@recruit-Mecer-X102:~/workspace$ ls
CHANGELOG.md  README.md    seacrh_results.md  search_results.md  tmp    umuzi.md
cohort.md     recruits.md  search_result.md   summary.md         umuzi
recruit@recruit-Mecer-X102:~/workspace$ cat seacrh_results.md
recruit@recruit-Mecer-X102:~/workspace$ sudo updatedb
[sudo] password for recruit:        
recruit@recruit-Mecer-X102:~/workspace$ locate umuzi
/home/recruit/workspace/umuzi
/home/recruit/workspace/umuzi.md
/home/recruit/workspace/tmp/umuzi
recruit@recruit-Mecer-X102:~/workspace$ locate umuzi > search_result.md
recruit@recruit-Mecer-X102:~/workspace$ cat search_result.md
/home/recruit/workspace/umuzi
/home/recruit/workspace/umuzi.md
/home/recruit/workspace/tmp/umuzi
recruit@recruit-Mecer-X102:~/workspace$ 

Task 5:

recruit@recruit-Mecer-X102:~/workspace$ cd ~
recruit@recruit-Mecer-X102:~$ ls
Desktop  Documents  Downloads  Music  Pictures  Public  Templates  Videos  workspace
recruit@recruit-Mecer-X102:~$ cd dovuments
bash: cd: dovuments: No such file or directory
recruit@recruit-Mecer-X102:~$ cd documents
bash: cd: documents: No such file or directory
recruit@recruit-Mecer-X102:~$ cd Documents
recruit@recruit-Mecer-X102:~/Documents$ touch pad.md
recruit@recruit-Mecer-X102:~/Documents$ ls
 Assessment%20Agreement%20IT.docx_1.odt   pad.md
'Assessment Agreement IT-2.pdf'          'Research & User Interviews - HI.docx'
'Human Intelligence - MUB.docx'          'Tinyiko Hlungwani_Personal Details.docx'
recruit@recruit-Mecer-X102:~/Documents$ 
recruit@recruit-Mecer-X102:~/Documents$ cd ~ Desktop
bash: cd: too many arguments
recruit@recruit-Mecer-X102:~/Documents$ cd ~Desktop
bash: cd: ~Desktop: No such file or directory
recruit@recruit-Mecer-X102:~/Documents$ cd ~
recruit@recruit-Mecer-X102:~$ cd Desktop
recruit@recruit-Mecer-X102:~/Desktop$  touch work
recruit@recruit-Mecer-X102:~/Desktop$ ls
'Assessment Agreement IT.pdf'   IMG-20191021-WA0004.jpg   IMG-20191021-WA0005.jpg   work
recruit@recruit-Mecer-X102:~/Desktop$ cp pad.md pad_copy.md
cp: cannot stat 'pad.md': No such file or directory
recruit@recruit-Mecer-X102:~/Desktop$ cd ~
recruit@recruit-Mecer-X102:~$ cp pad.md Desktop pad_copy.md
cp: target 'pad_copy.md' is not a directory
recruit@recruit-Mecer-X102:~$ cp pad.md pad_copy.md Desktop
cp: cannot stat 'pad.md': No such file or directory
cp: cannot stat 'pad_copy.md': No such file or directory
recruit@recruit-Mecer-X102:~$ cd Documents
recruit@recruit-Mecer-X102:~/Documents$ 
recruit@recruit-Mecer-X102:~/Documents$ 
recruit@recruit-Mecer-X102:~/Documents$ ls
 Assessment%20Agreement%20IT.docx_1.odt   pad.md
'Assessment Agreement IT-2.pdf'          'Research & User Interviews - HI.docx'
'Human Intelligence - MUB.docx'          'Tinyiko Hlungwani_Personal Details.docx'
recruit@recruit-Mecer-X102:~/Documents$ 
recruit@recruit-Mecer-X102:~/Documents$ 
recruit@recruit-Mecer-X102:~/Documents$ pad.md copy_pad.md Desktop
pad.md: command not found
recruit@recruit-Mecer-X102:~/Documents$ cp pad.md copy_pad.md Desktop
cp: target 'Desktop' is not a directory
recruit@recruit-Mecer-X102:~/Documents$ cd Desktop
bash: cd: Desktop: No such file or directory
recruit@recruit-Mecer-X102:~/Documents$ cd ~
recruit@recruit-Mecer-X102:~$ 
recruit@recruit-Mecer-X102:~$ cd Desktop
recruit@recruit-Mecer-X102:~/Desktop$ cp pad.md copy_pad.md
cp: cannot stat 'pad.md': No such file or directory
recruit@recruit-Mecer-X102:~/Desktop$ ls
'Assessment Agreement IT.pdf'   IMG-20191021-WA0004.jpg   IMG-20191021-WA0005.jpg   work
recruit@recruit-Mecer-X102:~/Desktop$ mkdir work
mkdir: cannot create directory ‘work’: File exists
recruit@recruit-Mecer-X102:~/Desktop$ rm work
recruit@recruit-Mecer-X102:~/Desktop$ ls
'Assessment Agreement IT.pdf'   IMG-20191021-WA0004.jpg   IMG-20191021-WA0005.jpg
recruit@recruit-Mecer-X102:~/Desktop$ mkdir work
recruit@recruit-Mecer-X102:~/Desktop$ ls
'Assessment Agreement IT.pdf'   IMG-20191021-WA0004.jpg   IMG-20191021-WA0005.jpg   work
recruit@recruit-Mecer-X102:~/Desktop$ 
recruit@recruit-Mecer-X102:~/Desktop$ 
recruit@recruit-Mecer-X102:~/Desktop$ cd ~
recruit@recruit-Mecer-X102:~$ cp pad.md copy_pad.md Desktop
cp: cannot stat 'pad.md': No such file or directory
cp: cannot stat 'copy_pad.md': No such file or directory
recruit@recruit-Mecer-X102:~$ 
recruit@recruit-Mecer-X102:~$ locate pad.md
recruit@recruit-Mecer-X102:~$ cd Documents
recruit@recruit-Mecer-X102:~/Documents$ ls
 Assessment%20Agreement%20IT.docx_1.odt   pad.md
'Assessment Agreement IT-2.pdf'          'Research & User Interviews - HI.docx'
'Human Intelligence - MUB.docx'          'Tinyiko Hlungwani_Personal Details.docx'
recruit@recruit-Mecer-X102:~/Documents$ 
recruit@recruit-Mecer-X102:~/Documents$ cd ~
recruit@recruit-Mecer-X102:~$ cd Desktop
recruit@recruit-Mecer-X102:~/Desktop$ 
recruit@recruit-Mecer-X102:~/Desktop$ cp ~/Documents/pad.md . copy_pad.md
cp: target 'copy_pad.md' is not a directory
recruit@recruit-Mecer-X102:~/Desktop$ cp ~/Documents/pad.md .
recruit@recruit-Mecer-X102:~/Desktop$ ls 
'Assessment Agreement IT.pdf'   IMG-20191021-WA0004.jpg   IMG-20191021-WA0005.jpg   pad.md   work
recruit@recruit-Mecer-X102:~/Desktop$ mv pad.md copy_pad.md
recruit@recruit-Mecer-X102:~/Desktop$ ls
'Assessment Agreement IT.pdf'   IMG-20191021-WA0004.jpg   work
 copy_pad.md                    IMG-20191021-WA0005.jpg
recruit@recruit-Mecer-X102:~/Desktop$ 
recruit@recruit-Mecer-X102:~/Desktop$ locate updatedb
/etc/updatedb.conf
/etc/alternatives/updatedb
/etc/alternatives/updatedb.8.gz
/usr/bin/updatedb
/usr/bin/updatedb.mlocate
/usr/share/man/man5/updatedb.conf.5.gz
/usr/share/man/man8/updatedb.8.gz
/usr/share/man/man8/updatedb.mlocate.8.gz
recruit@recruit-Mecer-X102:~/Desktop$ cd -
/home/recruit
recruit@recruit-Mecer-X102:~$ locate pad_copy.md
recruit@recruit-Mecer-X102:~$ sudo updatedb
[sudo] password for recruit:        
recruit@recruit-Mecer-X102:~$ locate pad_copy.md
recruit@recruit-Mecer-X102:~$ cd Desktop/
recruit@recruit-Mecer-X102:~/Desktop$ ls
'Assessment Agreement IT.pdf'   copy_pad.md   IMG-20191021-WA0004.jpg   IMG-20191021-WA0005.jpg   work
recruit@recruit-Mecer-X102:~/Desktop$ mv copy_pad.md pad_copy.md
recruit@recruit-Mecer-X102:~/Desktop$ ls
'Assessment Agreement IT.pdf'   IMG-20191021-WA0004.jpg   IMG-20191021-WA0005.jpg   pad_copy.md   work
recruit@recruit-Mecer-X102:~/Desktop$ locate pad
recruit@recruit-Mecer-X102:~/Desktop$ _locate pad_copy.md

Command '_locate' not found, did you mean:

  command 'dlocate' from deb dlocate
  command 'mlocate' from deb mlocate
  command 'locate' from deb mlocate
  command 'locate' from deb locate
  command 'zlocate' from deb zephyr-clients

Try: sudo apt install <deb name>

recruit@recruit-Mecer-X102:~/Desktop$ locate pad_copy.md
recruit@recruit-Mecer-X102:~/Desktop$ sudo updatedb
recruit@recruit-Mecer-X102:~/Desktop$ locate pad_copy.md
/home/recruit/Desktop/pad_copy.md
recruit@recruit-Mecer-X102:~/Desktop$ 

Task 6:

recruit@recruit-Mecer-X102:~$ locate -name *.pdf
locate: invalid value `ame' of --limit
recruit@recruit-Mecer-X102:~$ find -name *.pdf
./Desktop/Assessment Agreement IT.pdf
./Downloads/WELLNESS WORKSHOP.pdf
./Documents/Assessment Agreement IT-2.pdf
recruit@recruit-Mecer-X102:~$ find -name *.pdf -exec mv {} ../Search_results
find: missing argument to `-exec'
recruit@recruit-Mecer-X102:~$ find -name *.pdf mv {} ../Search_results
find: paths must precede expression: `mv'
recruit@recruit-Mecer-X102:~$ mv $(fine -name *.pdf) ../Search_results

Command 'fine' not found, did you mean:

  command 'xine' from deb xine-ui
  command 'file' from deb file
  command 'ifne' from deb moreutils
  command 'find' from deb findutils
  command 'wine' from deb wine-development
  command 'wine' from deb wine-stable

Try: sudo apt install <deb name>

mv: missing destination file operand after '../Search_results'
Try 'mv --help' for more information.
recruit@recruit-Mecer-X102:~$ 
recruit@recruit-Mecer-X102:~$ 
recruit@recruit-Mecer-X102:~$ mv $(find -name *.pdf) ../Search_results
mv: target '../Search_results' is not a directory
recruit@recruit-Mecer-X102:~$ mv $(find -name *pdf) ../tmp
mv: target '../tmp' is not a directory
recruit@recruit-Mecer-X102:~$ mv $(find -name *.pdf) tmp
mv: target 'tmp' is not a directory
recruit@recruit-Mecer-X102:~$ mv $(find -name *.pdf) workspace
mv: cannot stat './Desktop/Assessment': No such file or directory
mv: cannot stat 'Agreement': No such file or directory
mv: cannot stat 'IT.pdf': No such file or directory
mv: cannot stat './Downloads/WELLNESS': No such file or directory
mv: cannot stat 'WORKSHOP.pdf': No such file or directory
mv: cannot stat './Documents/Assessment': No such file or directory
mv: cannot stat 'Agreement': No such file or directory
mv: cannot stat 'IT-2.pdf': No such file or directory
recruit@recruit-Mecer-X102:~$ find -name *.pdf >> Search_results
bash: Search_results: Is a directory
recruit@recruit-Mecer-X102:~$ find -name *.pdf >> wor
recruit@recruit-Mecer-X102:~$ ls
Desktop    Downloads  my_files   Pictures  Search_results  Videos  work
Documents  Music      nano.save  Public    Templates       wor     workspace
recruit@recruit-Mecer-X102:~$ 

Task 7:

recruit@recruit-Mecer-X102:~$ mkdir my_files
recruit@recruit-Mecer-X102:~$ ls
Desktop    Music      nano.save  Search_results  work
Documents  my_bio.md  Pictures   Templates       workspace
Downloads  my_files   Public     Videos
recruit@recruit-Mecer-X102:~$ mv my_bio.md my_files
recruit@recruit-Mecer-X102:~$ ls
Desktop    Downloads  my_files   Pictures  Search_results  Videos  workspace
Documents  Music      nano.save  Public    Templates       work
recruit@recruit-Mecer-X102:~$ 





