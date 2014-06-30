[user]

name = MRHwick

email = MatthewRHardwick@gmail.com

[push]

default = simple

[alias]

ls = log --pretty=format:"%C(yellow)%h\\ %Cgreen%cr\\ %Cred%d\\ %Creset%s%Cblue\\ [%cn]" --decorate 

ll = log --pretty=format:"%C(yellow)%h\\ %Cred%d\\ %Creset%s%Cblue\\ [%cn]" --decorate --numstat

ld = log --pretty=format:"%C(yellow)%h\\ %Cred%d\\ %Creset%s%Cblue\\ [%cn]" --decorate --stat

ci = commit

st = status -s

co = checkout

down = pull

up = push

