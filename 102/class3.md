# Class 3 Notes

What I learned:

- Git is A Distributed Version Control systems (DVCS)

- To clone a repository into a directory with another name of your choosing, use the following command format:

  $ git clone https://github.com/test mydirectory

- To determine the state of files, utilize the git status command:

  $ git status

 - "ACP" (Add, Commit, Push) git add filename (single) $ git add * (all)

  $ git commit -m â€œmade change x,y,zâ€ (one or more) $ git commit -a (all)

  $ git push origin master

- By running the git remote command, you can view the short names, such as â€œorigin,â€ of all specified remote handles.

- By using git remote -v, you can view all the remote URLs next to their corresponding short names.

  - Example: $ cd example

    $ git remote -v

     remote1 https://github.com/remote1/example (fetch)

     remote1 https://github.com/remote1/example (push)

     remote2 https://github.com/remote2/example (fetch)

     remote2 https://github.com/remote2/example (push)

     remote3 https://github.com/remote3/example (fetch)

     remote3 https://github.com/remote3/example (push)