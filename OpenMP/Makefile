all: helloworld parallel_00 parallel_01 parallel_02 parallelblock_00 parallelfor_00 pi montecarlopi


helloworld:
	gcc -omp helloworld.c -o helloworld

parallel_00:
	gcc -omp parallel_00.c -o parallel_00

parallel_01:
	gcc -omp parallel_01.c -o parallel_01

parallel_02:
	gcc -omp parallel_02.c -o parallel_02

parallelblock_00:
	gcc -omp parallelblock_00.c -o parallelblock_00

parallelfor_00:
	gcc -omp parallelfor_00.c -o parallelfor_00

pi:
	gcc -omp pi.c -o pi

montecarlopi:
	gcc -omp montecarlopi.c -o montecarlopi


clean:
	rm -f helloworld parallel_00 parallel_01 parallel_02 parallelblock_00 montecarlopi parallelfor_00 pi montecarlopi
