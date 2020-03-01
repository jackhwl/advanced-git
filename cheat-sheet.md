
# combine two repository 2020 with dev
https://labs.consol.de/development/git/2017/09/08/reunite-separate-git-repositories.html

git clone http://videvc001/Git/viDesktopDev.git viDesktop
cd viDesktop
git remote add viDesktop2020 http://videvc001/Git/viDesktop2020.git
git fetch viDesktop2020
git checkout -b viDesktop2020 viDesktop2020/master

git filter-branch --commit-filter '
if [ $# -eq 1 ]; then
git commit-tree -p da7f66ed00bf7baad4cc53a92cd8dcf95e881cd7 $1;
else
git commit-tree "$@";
fi' HEAD

https://stackoverflow.com/questions/10228760/fix-a-git-detached-head
git log -n 1;
git checkout master 
git branch v2 sha1   

