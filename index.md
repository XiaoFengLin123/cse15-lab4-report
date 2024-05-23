**Lab Report 4**

Step 4: ssh into the ieng6 server.

![image](https://github.com/XiaoFengLin123/cse15-lab4-report/assets/146484956/fb4abeed-4d90-4461-959c-db23b6b3f8f0)

I typed the command `ssh xil245@ieng6.ucsd..edu` to remotely access the ieng6 server with my username xil245. 

Step 5: git clone https://github.com/ucsd-cse15l-s24/lab7

![image](https://github.com/XiaoFengLin123/cse15-lab4-report/assets/146484956/1dd55a4a-b6d6-47f4-9a67-17f180801b26)

Copy the existing repository from https://github.com/ucsd-cse15l-s24/lab7 and create a local version within my local server. `<CTRL-C>` `<CTRL-V>` `git clone` command from lab 7 instructions. 

Step 6: Cd into lab7 and compile the test 

![image](https://github.com/XiaoFengLin123/cse15-lab4-report/assets/146484956/61a50122-1cd9-4d75-83a7-00943c87774d)
![image](https://github.com/XiaoFengLin123/cse15-lab4-report/assets/146484956/89f72d7e-5a23-4b33-961b-53085a07d379)

Keys pressed: `ls` `<enter>` `cd lab7` `<enter>` `CTRL-C` javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java `CTRL-V` `<enter>` `CTRL-C` java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore `CTRL-V`
`<space>` ListExamplesTests `<enter>`
