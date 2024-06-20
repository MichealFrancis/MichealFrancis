Pushd and popd are not itself related to c programming but commands used in linux

Pushd- The command is used to push a directory(or path file ) onto the stack or the current working path file 

/home/user
└── projects
    ├── project1
    ├── project2
    └── project3
$ pwd
/home/user

$ pushd projects/project1
~/projects/project1 ~
$ pushd ../project2
~/projects/project2 ~/projects/project1 ~ 

$ pushd ../project3
~/projects/project3 ~/projects/project2 ~/projects/project1 ~ 

Popd: The command is used to pop directories(the path file) off the  stack.
$ popd
~/projects/project2 ~/projects/project1 ~ 

$ popd
~/projects/project1 ~ 

$ popd
~ 


