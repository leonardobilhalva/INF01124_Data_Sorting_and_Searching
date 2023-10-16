# First Assignment - Shell Sort

This project aim to implement Shell sort and explore it with different sequences as KNUTH and CIURA.

## The first part

It will read the files entrada1.txt and produce a step by step file of the algorithms named saida1.txt.


## The second part

It will read the file entrada2.txt and produce a timescale for long sequences of random numbers to sort. The results will be written in saida2.txt


## Build 

This project was built in macOS, so it is Unix friendly. However, you can also compile it from Windows using docker :)

There are two ways to build the project. The first option is to use docker to create a virtual environment that will build everything. The other way is to use directly the make file from your environment, if you have already installed g++ compiler and other dependencies.

If you already have a g++ compiler and a Unix system, use last option. If that is not the case, build it from docker with a fresh ubuntu in the first option :)

You can find about docker [here](https://docs.docker.com/get-started/) and how to install it [here](https://docs.docker.com/engine/install/).

<details>
<summary>Build with docker</summary>

1. Clone the project and open the directory

2. Build the dockerfile
```
docker build -t trab01 .
```

3. Run the created container
```
docker run -it --name trab01 trab01 /bin/bash
```

4. Check the created content :)

4. Erase created container and image if needed
```
docker rm trab01 && docker rmi trab01
```
</details>

<details>


<summary>Build directly with makefile </summary>

1. Clone the project and open the directory

2. Build the project
``` bash
make
```

3. Test the program
``` bash
./trab_01
```

4. Check the created content :)

5. Erase created content if needed
``` bash
make clean
```
</details>


