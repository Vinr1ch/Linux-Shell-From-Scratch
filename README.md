# Shell
Introduction
The goal of this project is to build a shell interpreter which combines behavior from common shells including bash and csh. The project has been divided into parts. Some skeleton code has been provided, so you will not be starting from scratch.


Section
Test Output in command table. Half point each.
ls 
ls -al
ls -al aaa bbb cc
ls -al aaa bbb cc > outfile
ls | cat | grep
ls | cat | grep > out < inp
ls aaaa | grep cccc | grep jjjj ssss dfdffdf
sleep 10 &
ls aaaa | grep cccc | grep jjjj ssss dfdffdf >& out < in
ls aaaa | grep cccc | grep jjjj ssss dfdffdf >>& out < in

Run commands manually
      ls
      ls -al
      ls -al | grep cc
      ls -al > out   (cat out)
      grep shell < shell.cc
      
 look at test file and run via 
  ./testall p1
  ./testall p2	


