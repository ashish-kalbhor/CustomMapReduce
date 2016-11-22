# CustomMapReduce
A customized bundle of Map Reduce Framework


PRE-REQUISITE:
Oracle JDK version 1.8
AWS CLI + Configuration
Folder structure on local host
Files to be included before running make file 
How folder structure is created on EC2 – master and slave nodes
AWS configuration

JAVA Files - 

Package-> custom.mr
Configuration.java 
FileInputFormat.java
FileOutputFormat.java
IntWritable.java 
Job.java
LocalJobClient.java
Mapper.java
PartitionHelper.java
Path.java
Reducer.java
ReducerDriver.java
SlaveDriver.java 
Text.java

Package-> custom.mr.utils
FileChunkLoader.java
FileIO.java
ProcessUtils.java
RunShellScript.java
TextSocket.java	

Bash Scripts -

start-cluster
stop-cluster
my-mapreduce
makessh
installjava.sh
run-jar.sh
config
awsSetup.sh 
exportTos3.sh
mergeMapperOutput
createReducerInput
startSlaves.sh
dataShipper.sh 
splitFileList.sh
