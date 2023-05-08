# simple-shell-in-C
Simple implementation of a shell in C

# Running
Use gcc -o lsh src/main.c to compile, and then ./lsh to run. If you would like to use the standard-library based implementation of lsh_read_line(), then you can do: gcc -DLSH_USE_STD_GETLINE -o lsh src/main.c.
