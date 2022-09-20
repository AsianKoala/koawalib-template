## koawalib-template
The purpose of this repo is to lower the learning curve of koawalib...
(and make it easier on me when I create new repos lol)  

### Usage
Simply clone this repository to use the standard version of koawalib, published through Jitpack.  

### Local koawalib module
If you want to modify the koawalib source code/have instant updates through git, follow these steps.  
This will setup koawalib as a local repository, and as a dependency to your fork.   
When new updates are pushed to koawalib, the user can choose how/when to upgrade through git.
 
1. Fork this repository
2. Clone [koawalib](https://github.com/AsianKoala/koawalib) in the same directory
3. cd into the fork
4. Add this template repo as a remote
5. Fetch 
6. Merge with the local-koawalib branch of this repository
7. Check if koawalib is working as intended
8. Update changes on your own repo

Here is an example of me following the above steps with my personal repository.

```
git clone git@github.com:AsianKoala/koawalib-template.git PP-Public
git clone git@github.com:AsianKoala/koawalib.git
cd PP-Public
git merge origin/local-koawalib
git remote remove origin
git remote add origin git@github.com:ftc-noteam/PP-Public.git
git push -u origin master
```
