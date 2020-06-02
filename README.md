# Java-MapReduce-using-Cloudera-Hadoop
Big Data Ecosystem, HDFS, MapReduce

Hadoop MapReduce is a software framework for easily writing applications which process vast amounts 
of data (multi-terabyte data-sets) in-parallel on large clusters (thousands of nodes) of commodity
hardware in a reliable, fault-tolerant manner. 
A MapReduce job usually splits the input data-set into independent chunks which are processed by the
map tasks in a completely parallel manner. The framework sorts the outputs of the maps, which are
then input to the reduce tasks. Typically both the input and the output of the job are stored in a file -
system. The framework takes care of scheduling tasks, monitoring them and re-executes the failed tasks.
 
-Hadoop Map Reduce 

MapReduce program executes in three stages, namely map stage, shuffle stage, and reduce stage . 
Map stage- The text from the input text file is tokenized into words to form a key value pair with all the        
words present in the input text file. The key is the word from the input file and value is ‘1’.  
Shuffle stage- The key-value pairs generated in the map phase are taken as input and then sorted in
alphabetical order and map output from Mapper to Reducer.  
Reducer stage- It takes the output of shuffle phase as input and then reduces the key-value pairs to
unique keys with values added up. 

- The sourcecode is provided alongside the documentation of implementing a MapReduce.
