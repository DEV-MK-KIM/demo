# GIT CHEAT SHEET
> <small>author: MK</small><br>
> <small>date: 2020-02-15</small><br>
> <small>All rights reserved</small>
___
## Chapter 1 - GIT 기초
___

***Staged 에서 unstaged 로 바꿀때***
```
git reset HEAD <filename.xx>`
```
```
git restore --staged <filename.xx>`
```
___

***unstaged 에서 clean working tree 로 바꿀때 (수정했던 기록 모두 지우기)***
```
git checkout -- <filename.xx>
```