runtime: java -jar benchmark.jar -r 1500000 10 50000 20 filename
memory: java -jar benchmark.jar -m 1500000 10 50000 20 filename

******** parameters ********
-r = measure runtime
-m = measure memory
10 = trials in the sense number of iterations that each process should run(play with this numner)
50000 = increment value in the sense number of integers that gets added into the list at each step(play with this number)
20 = number of increment steps(play with this number)
filename = name of the output file