# Concurrent-Dependency-Discoverer

This was a 3rd year computing science project where I was asked to refactor a sequential C++ dependency discoverer into a concurrent program with the same functionality

Set crwler thread count with:
$export CRAWLER_THREADS={number of threads}

Run the program on test folder and print the time (used to compare running speeds of differnt thread counts):
$time ./dependencyDiscoverer -Itest test/*.c test/*.l test/*.y > temp
