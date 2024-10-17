# source_control_test
Tonight, I'm learning how to use source control from github.
It's like a google docs, where people access the same file, and make changes together in real time.

Difference is, the changes from person A, and person B may be conflicting to the script. The source control aims to be the middle man, having both A and B discuss amongst themselves to find the compromise with the changes, and get the same resulting codes.


1. Click the green **code<>** button, and copy the link for **https**.
2. In command prompt, go to your correct file directory, and write `git clone https://github.com/Tenatic-X/source_control_test.git` It creates a folder with this `README` file, and has a hidden folder where github communicates with the computer.
3. Change directory to the source control folder github created, and type `git status` shows whether the file is not the same in github.
4. Use `git add (filename)` to add the files you've edited/changed on your computer in the source control folder, into the repository. P.S. Use `git add .` to add all file changes
5. Use `git commit` to commit that the changes you've made is published into the github repository. `git commit -m 'this place adds a message for the changes you've made'`
6. Use `git push` to push the changes you've made into the actual repository. The changes can be seen on the commits in the repository.
7. Use `git pull` pulls the current github repository into your current computer files. Whenever updates happen on the repository, you can get its latest version by pulling it in.
