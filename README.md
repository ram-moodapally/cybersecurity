# cybersecurity

Week 7 and 8 , kali vs Docker 

Vulnerability 1. 

. In my blog, out of all the pages i have , I had a few particular set of pages which I am intended to show only to a few people. 


I also have one generic page with the following URL: http://localhost:8080/?page_id=4

Now as a hacker, I can keep trying to change the id number and in a lucky situation, I had landed on a page which is not intended to design me. 

http://localhost:8080/?page_id=2. 

This is a URL manipulation vulnerability. 

Wordpress version 4.1



create a API in 

-url http://127.0.0.1:8080 --usernames username.txt --passwords p

https://wpscan.com/profile 

get the API token

run the command wpscan --url http://127.0.0.1:8080 --api-token our_token_goes_here

wpscan --url http://127.0.0.1:8080 --api-token YOUR_TOKEN -e u vp 

get the users detaisl
create username.txt and password.txt  (with relevant usernames and passwords)

wpscan --url http://127.0.0.1:8080 --usernames username.txt --passwords password.txt

check the console message we will get the success message of the compromised  username and password


try login with the username and the password.  bazingaaaa... 


Vulnerability 3.

open any page
go the body, select text mode
write some xss scripting and then save the page.
in my case, i have writen redirect logic and it will be going to the new page (it can be any where the session and cookies might get stolen)



