# :memo: Disk_Based_Processing_MapReduce

In Disk Based processing we learn to use various Bigdata tools for example: MapReduce,Yarn.. 

Here are the basic implementations of Mapreduce Programs:
  ## 1. [Word Count Program](https://github.com/priyansh19/Disk_Based_Processing_MapReduce/tree/master/WordCount) :
  
We will count the no. of words in a file(in HDFS) and no of occurences we get will be stored in a seperate file in HDFS < [name of Output dir mentioned in command]/part* >  

  ## 2. [Word Count Program Using Tool Runner](https://github.com/priyansh19/Disk_Based_Processing_MapReduce/tree/master/WordCount_Using_ToolRunner) :
We will count the no. of words/occuraces of word in a file using a special function ToolRunner(in HDFS)and the file we getas output will be stored in HDFS < [name of Output dir mentioned in command]/part* >  

  ## 3. [Char_Count](https://github.com/priyansh19/Disk_Based_Processing_MapReduce/tree/master/Char_Count) :
No. of occurances per charachter including all speccial charachters will be counted and stored in a file < [name of Output dir mentioned in command]/part* >  

  ## 4. [Word_Length](https://github.com/priyansh19/Disk_Based_Processing_MapReduce/tree/master/Word_Length) :
Length of each unique word will be counted and stored in output file in HDFS < [name of Output dir mentioned in command]/part* > 

  ## 5. [Avg_Word_Length](https://github.com/priyansh19/Disk_Based_Processing_MapReduce/tree/master/Avg_Word_Lngth) :
Average Length of each unique word on the basis of thier first letter will be counted and stored in output file in HDFS < [name of Output dir mentioned in command]/part* > 

For example- if we have two word in a file named Hadoop and Hive then the output will be 

        hadoop - 6 and hive - 4 => 6+4 => 10/no.of words
        output =>  h    5 
