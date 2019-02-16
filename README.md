"# resume"

Convert woed document to .md file

Reference: 
https://gist.github.com/vzvenyach/7278543

unoconv utility

 http://dag.wiee.rs/home-made/unoconv/
 
 https://www.maketecheasier.com/automate-document-conversion-with-unoconv/
 
 https://www.howtoinstall.co/en/ubuntu/xenial/unoconv
 
 

pandoc utility
 http://www.pandoc.org/installing.html

Example: 

Bash (Ubuntu)

unoconv -f html RobertLukawiecki.doc


CMD (Windows)

pandoc -f html -t markdown -o RobertLukawiecki.md RobertLukawiecki.html
