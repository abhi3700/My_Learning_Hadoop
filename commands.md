# Hadoop Commands
* `$ hadoop fs -ls /` - list all the files in root (__/__) directory.

	```console
	/hbase
	/tmp
	/user
	/var
	```

* `$ hadoop fs -ls /user` - list all the files in __user__ directory.
* `$ hadoop fs -mkdir /mydata` - create a folder in the root directory.
* `$ hadoop fs -ls /` - Now, list the files
	```console
	/hbase
	/mydata
	/tmp
	/user
	/var
	```
* `$ hadoop fs -mkdir /mydata/testfolder` - create __testfolder__ in the __mydata__ folder.
* `$ nano testfile.txt` - create a .txt file and save it in this home directory.
* `$ hadoop fs -put testfile.txt /mydata/testfolder/` - copy the file into __testfolder__ folder.
* `$ hadoop fs -get /mydata/testfolder/testfile.txt newfile.txt` - save the __testfile.txt__ as __newfile.txt__ (in linux home directory).
* `$ ls *.txt` - list all the .txt files in the home directory
	```console
	newfile.txt testfile.txt
	```
