**Lab Report 4**

Step 4: ssh into the ieng6 server.

![image](https://github.com/XiaoFengLin123/cse15-lab4-report/assets/146484956/fb4abeed-4d90-4461-959c-db23b6b3f8f0)

I typed the command `ssh xil245@ieng6.ucsd..edu` to remotely access the ieng6 server with my username xil245. 

Step 5: git clone https://github.com/XiaoFengLin123/lab7

![image](https://github.com/XiaoFengLin123/cse15-lab4-report/assets/146484956/1dd55a4a-b6d6-47f4-9a67-17f180801b26)

Copy the existing repository from https://github.com/ucsd-cse15l-s24/lab7 and create a local version within my local server. `<CTRL-C>` `<CTRL-V>` `git clone` command from lab 7 instructions (https://github.com/ucsd-cse15l-s24/lab7). 

Step 6: Cd into lab7 and compile the test 

![image](https://github.com/XiaoFengLin123/cse15-lab4-report/assets/146484956/61a50122-1cd9-4d75-83a7-00943c87774d)
![image](https://github.com/XiaoFengLin123/cse15-lab4-report/assets/146484956/89f72d7e-5a23-4b33-961b-53085a07d379)

Keys pressed: `ls` `<enter>` `cd lab7` `<enter>` `CTRL-C` `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` `CTRL-V` `<enter>` `CTRL-C` java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore `CTRL-V`
`<space>` ListExamplesTests `<enter>`

I want to `cd` into the `lab7` directory and use `ls` to see if I can. I copy and paste the `javac` to compile all of the java files within the `lab7` directory and then use `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests` will run/execute the tests within the ListExamplesTests. 

Step 7: Edit ListExamples.java using vim swap index1 with index2.  

![image](https://github.com/XiaoFengLin123/cse15-lab4-report/assets/146484956/59cebe16-fc5e-4950-98db-6f26cf536cc4)

Keys pressed: 

`ls` `<enter>` `vim ListExamples.java` `<enter>` `43j` `<k>` `<k>` `<k>` `<k>` `<k>` `<k>`
`ce` <esc> :wq <enter>

Used `ls` to locate the `ListExamples.java` file. then use `gg` and then the `43j` command to move the cursor from the top of the file down to the line that requires changing. Click k 6 times to move the cursor to the first letter in index1 and do ce to delete and change it to index2. I then save the file by `esc` and then use the command `:wq` to save the file. 

Step 8: Recompile and run the code with the correct code.

![image](https://github.com/XiaoFengLin123/cse15-lab4-report/assets/146484956/212444fb-3bf2-47f0-8f45-c10b896ebf32)


Keys Pressed: <up><up><up><up> <enter> <up><up><up><up> <enter>. 

The `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` was 4 up in the search history so I used the up arrow to access it. The `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests` was 4 up in history, so I accessed it and ran the code. All of the tests passed. 

Step 9: Git clone

![image](https://github.com/XiaoFengLin123/cse15-lab4-report/assets/146484956/e1e55a43-d710-444a-93f5-bedd192cab51)
![image](https://github.com/XiaoFengLin123/cse15-lab4-report/assets/146484956/590d081b-3d78-43c1-a4ed-08fd0b5c4981)

Keys Pressed: git add . <enter> git commit -m "newcode" <enter> git push <enter>


I use `git add` to save my changes, then I commit my files with my changes and then push them to my forked git repository.

