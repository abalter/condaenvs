# condaenvs
Config files for my conda envs.

for i in *.txt; do echo $i; envname=${i%%.txt}; echo $envname; conda env update -n $envname -f $i; done
