## troubleshooting

if sst: error while loading shared libraries: libmpi.so.40: cannot open shared object file: No such file or directory
export LD_LIBRARY_PATH=/PATH_TO_OPENMPI/lib:$LD_LIBRARY_PATH

this worked for compute-1

### update: sst and now be run from every node
