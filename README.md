# isuckatgit
A test repo to show off my low skills at git.  Indeed this repo is to
publicly shame myself until I learn and become git fluent.


### tips and tricks

### striping out last local commit

`git reset --soft HEAD~1`

### changed the last pushed commit

~~~
git commit --amend
git push --force-with-lease
~~~

### Delete all local commits and start fresh from origin version

~~~
git reset --hard origin/master
~~~
