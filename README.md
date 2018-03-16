## Some useful functions I use in linux

1. put all contents into one file called all.R
`cat * >> all.R`

2. remove all lines in all.R starting with "source"
`grep -v '^source' all.R allstripped.R`

3. remove all files in current directory except allstripped.R
`find . ! -name 'file.txt' -type f -exec rm -f {} +`