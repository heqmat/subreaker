# What is Subreaker?
 ------------------------------------------------------------
Subreaker is a passive information gathering tool. Subdomains can be scanned at the information gathering stage in web pentesting and it can be used for black-box pentesting which generally encompasses bug bounty hunting.
![examples](https://user-images.githubusercontent.com/64712867/83596341-14f76f80-a56d-11ea-9f30-9f74cbe7dc8c.png)
# How to install Subreaker?
Clone subreaker's repository from remote server <br>
`git clone https://github.com/heqmat/subreaker.git` 

# How to use Subreaker?
```
python subreaker.py -h (Show all paramaters)
python subreaker.py -d [DOMAIN ADDRESS] (EXAMPLE: facebook.com,twitter.com)
python subreaker.py -d google.com (Example usage)
python subreaker.py -o (Save output)
python subreaker.py -d google.com -o google_subdomains.txt [Example usage with "-o" parameter.]
```

If you already installed setup.sh file you can write just like that. 
```
subreaker -d kali.org
``` 
<br>

![image](https://user-images.githubusercontent.com/64712867/83640432-c79ef080-a5b4-11ea-9c79-056c2cf6231e.png)


# 

Usage of Subreaker for attacking targets without prior mutual consent is illegal. 
It is the end user's responsibility to obey all applicable local, state and federal laws. 
Developer assume no liability and are not responsible for any misuse or damage caused by this program.
