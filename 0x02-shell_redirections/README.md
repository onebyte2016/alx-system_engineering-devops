this is i\o shell redirection readme
#echo "\"(Ôo)'" :Write a script that displays a confused smiley "(Ôo)'.
#cat /etc/passwd : Display the content of the /etc/passwd file
#echo /etc/passwd /etc/hosts : Display the content of /etc/passwd and /etc/hosts
#tail /etc/passwd : Display the last 10 lines of /etc/passwd
#head /etc/passwd : Display the first 10 lines of /etc/passwd
#head -3 iacta | tail -1 :Write a script that displays the third line of the file i
#echo "Best School" > "\*\\\'\"Best\ School\"\'\\\*$\?\*\*\*\*\*:)" :Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
#ls -la > ls_cwd_content : Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it
#tail -1 iacta >> iacta :Write a script that duplicates the last line of the file iacta
#find . -type f -name *.js -delete : Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
#find . -mindepth 1 -type d | wc -l : Write a script that counts the number of directories and sub-directories in the current directory.
#ls -t | head : A script that displays the 10 newest files in the current directory.
#sort | uniq -u :Create a script that takes a list of words as input and prints only words that appear exactly once.
#grep "root" /etc/passwd : Display lines containing the pattern “root” from the file /etc/passwd
#grep "bin" /etc/passwd | wc -l : Display the number of lines that contain the pattern “bin” in the file /etc/pass
#grep -A 3 | 'root' /etc/passwd : Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd
#grep -v "bin" /etc/passwd | wc -l :Display all the lines in the file /etc/passwd that do not contain the pattern “bin”
#grep '^[[:alpha:]]' /etc/ssh/sshd_config : Display all lines of the file /etc/ssh/sshd_config starting with a letter.
#tr Ac Ze : Replace all characters A and c from input to Z and e respectively.
#tr -d 'cC' : 20. Without C, you would live in hiag
#rev : Write a script that reverse its input.
#cut -d ':' -f1,6 /etc/passwd | sort :Write a script that displays all users and their home directories, sorted by users.
#find . -empty -printf '%f\n' : Write a command that finds all empty files and directories in the current directory and all sub-directories.
#find -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d '.' -f 2- | rev | LC_ALL=C sort -f  :Write a script that lists all the files with a .gif extension in the current directory and all its sub-directories.
#cut -c l | paste -s -d '' : Create a script that decodes acrostics that use the first letter of each line.
#tail -n +2 | cut -f 1 | sort -k 1 | uniq -c | sort -rnk 1 | head -n 11 | rev |cut -d ' ' -f 1 | rev  : Write a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
