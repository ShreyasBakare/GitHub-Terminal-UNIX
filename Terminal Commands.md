# VVVIMP https://www.freecodecamp.org/news/the-linux-commands-handbook/
# 1. whoami
<img width="681" alt="image" src="https://user-images.githubusercontent.com/56884503/187026860-1dcd0add-0768-4555-b346-ebd9e214195b.png">

# 2. man
<img width="559" alt="image" src="https://user-images.githubusercontent.com/56884503/187026915-fc70e519-5e25-440f-87cc-719430950832.png">
## Options 
In Man page [] denotes different options for tha command!

Arrow for one line
Space for one pahe 
h for help
q for quit

# 3. clear
## clear -x OR Cntrl L
## cmd L for one line clear

# 4. pwd
<img width="648" alt="image" src="https://user-images.githubusercontent.com/56884503/187032745-2c61bfae-0e11-40ae-b07e-1a5373fad193.png">

<img width="468" alt="image" src="https://user-images.githubusercontent.com/56884503/187033308-04de0d7f-13fa-49bf-8f25-90c8a96b4798.png">

Here / is Volumes--> Macintosh HD 

In which the whole Mac OS is situated


# 5. ls
<img width="817" alt="image" src="https://user-images.githubusercontent.com/56884503/187036084-dff78109-a8b2-48f2-8a56-8dbb8235dac7.png">

## ls Argument {A LOT OF OPTIONS IN man ls}

Here ~ ==> /users/shreyasbakare (Home)
/ is root directory
<img width="1257" alt="image" src="https://user-images.githubusercontent.com/56884503/187044670-3e3397b3-6e54-4985-ae6f-660f142d1483.png">

Here 
Total 
File permissions
Owner of file 
Group Owner
File Size
Modification date 
File Name

# 6. cd

No man cd 
but help cd

cd {location}
only cd takes you to /users/shreyasbakare
cd . == this
cd .. == previous

# 7. mkdir

<img width="628" alt="image" src="https://user-images.githubusercontent.com/56884503/187048847-271ef8db-333b-4a75-83b3-773cef071891.png">

Space for multiple
name/name to more inside 
but more than 2 -p

# 8. touch

<img width="624" alt="image" src="https://user-images.githubusercontent.com/56884503/187048912-ca1254f6-712d-4c27-b1c6-e93b35ec7701.png">

with or without extension files

Space for multiple 
# 9. rmdir
Only works for empty directories
<img width="599" alt="image" src="https://user-images.githubusercontent.com/56884503/187049069-47c9b089-0f73-4e7a-86c7-05e229087e32.png">

# 10. rm
Completely delete files
Not directories

# 11. rm -r 
for deleting directories with files

# 12. rm -ri
Interactive way to delete directory

# 13. rm -rv 
Delete a bunch of things

# 14. open

Open a folder

## Open . 
will open that directory in finder

# 15. mv 
<img width="545" alt="image" src="https://user-images.githubusercontent.com/56884503/187049586-5a9da0bc-27de-4f8a-85ce-eeec377df8e3.png">

Last one should be file for transferring
if not directory name then renamed
ALSO RENAME DIR

# 16. cp
<img width="575" alt="image" src="https://user-images.githubusercontent.com/56884503/187049722-4b4b19c1-a053-49e0-97b4-8d1004f21d1f.png">

cp -r inside things 

cp file dir/file 
copy to different dir 

# 17. head 
outputs first 10 lines

head -n 100 
100 lines

# 18. tail 

outputs last 10 lines

tail -n 100 
100 lines

# 19. redirect output to file >
replaces the data
date > time.txt

# 20. >>
Appends the data
pwd >> time.txt

# 21. cat 
<img width="592" alt="image" src="https://user-images.githubusercontent.com/56884503/187050033-810ee4e6-2101-4928-ba9d-25c684c959a1.png">

# 22. less
 consize open files
 
 ## /search 
 
 
 # 23. echo
 <img width="652" alt="image" src="https://user-images.githubusercontent.com/56884503/187050173-02504733-8735-46ba-b0c1-20a56537dc57.png">

# 24. wc
<img width="630" alt="image" src="https://user-images.githubusercontent.com/56884503/187050211-6db77dc0-d6e8-4b1c-bd73-8b26e2466a0d.png">

lines words bytes

# 25. piping |

output of 1 as input of 2nd and we can again redirect this 

# 26. sort 
<img width="550" alt="image" src="https://user-images.githubusercontent.com/56884503/187050335-ce3cab5d-7696-4c9a-86ee-c6ef57aad71e.png">
-n
-r
-u unique



# 27. uniq
only adjacent duplicates

<img width="768" alt="image" src="https://user-images.githubusercontent.com/56884503/187055347-6beb7d2e-1b0d-4880-b0ad-8c38f96e4a54.png">

-d for only duplicate entries
-u only uniq
-c count


# 28. expansion

<img width="885" alt="image" src="https://user-images.githubusercontent.com/56884503/187055441-5fbe2987-e4b8-4207-af26-6bec13b852ab.png">

## WILD CARDS 
* --> for unknown string
* .ppt
? --> for unknown letter
python.??

