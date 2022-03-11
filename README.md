# cybersecurity
Install docker 

verify docker using using "docker --version"

create a new folder "cyber security"

open terminal in the new folder 

clone the following repo git clone https://github.com/0xrutvij/wpVSkali.git

cd wpVSkali

run the following comand "DOCKER_BUILDKIT=1 docker-compose build" 

mkdir wpFolder ( for assignment 7)

docker-compose up -d but for mac m1, add below line under the db
 platform: linux/x86_64


and run the up -d command again

following is the output. 

[+] Running 7/7
 ⠿ Network wpvskali_default        Created                                                                                                                                                    0.1s
 ⠿ Volume "wpvskali_kaliUser"      Created                                                                                                                                                    0.0s
 ⠿ Volume "wpvskali_kaliRoot"      Created                                                                                                                                                    0.0s
 ⠿ Volume "wpvskali_db"            Created                                                                                                                                                    0.0s
 ⠿ Container wpvskali-wordpress-1  Started                                                                                                                                                    4.3s
 ⠿ Container wpvskali-db-1         Started                                                                                                                                                    4.3s
 ⠿ Container kaliCP                Started                                                                                                                                                    4.1s
➜  wpVSkali git:(main) ✗ 


https://stackoverflow.com/questions/65456814/docker-apple-silicon-m1-preview-mysql-no-matching-manifest-for-linux-arm64-v8/65592942#65592942


run docker ps -a ( you can see all the instances)

run docker exec -it kaliCP bash ( enter the kali mode )

run cat /etc/os-release


name="FirstName LastName"
univ="University of Science"

screenfetch
echo $name'@'$univ
```

Save the file as **screenfetch.gif**.

**Challenges and Problems**: 

### Installing VirtualBox and Kali
<img src="vbox_kali.gif" alt="Virtualbox Installation">
 
### Running screenfetch
<img src="screenfetch.gif" alt="Running screenfetch">


DOCKER_BUILDKIT=1 docker-compose build