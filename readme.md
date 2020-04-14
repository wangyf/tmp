m0 is working directory which contains the error message (xxx.error)

To rerun the code:

1. recompile the code: 
	cd src 
	make -f makefile_mpi

2. Into working directory (required input files are in in/)
	cd ../m0
	rm out/* prof/* stats/*

3. Submit job
	sh queue.sh
