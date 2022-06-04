# How to install Anaconda on Ubuntu 20.4
~ Sarath Kamal | Basis of learning, Task-1

**1. Download the anaconda package for linux through-** [anaconda](https://www.anaconda.com/download/#linux)

**2. This step is optional-**
- [Verify data integrity with sha-256](https://docs.anaconda.com/anaconda/install/hashes/) - on this website look for the hash code for the specific anaconda package you just downloaded. In my case, I searched for 'Anaconda3-2022.05-Linux-x86_64.sh'
- Now go to your ubuntu terminal and type
```sh
sha256sum /path/filename
``` 
- this will generate hash code for your package.
- in my case, it was-
```sh
sha256sum ~/Downloads/Anaconda3-2022.05-Linux-x86_64.sh
```
- Now match the hash code generated with that on the website you searched on. It should be the same

**3. Install Ananconda-** 
```sh
bash /path/filename
```
- in my case it was-
```sh
bash ~/Downloads/Anaconda3-2022.05-Linux-x86_64.sh
```
- Nicee! you are almost done- just press enter to view the license and type yes for all the propmts coming up during the installation. Going with defaults is recommended.
- close the terminal and open it again

**4. Open anaconda navigator to play with it!**
```sh 
anaconda-navigator
```

