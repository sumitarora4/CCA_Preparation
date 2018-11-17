# CCA_Preparation

In this repositor we are using cloudera VM for CCA exams preparation:

HDFS path and port in cloudera VM:
> hdfs://quickstart.cloudera:8020

to get disk utilization of a folder:
> hdfs dfs -du -s -h /user/cloudera/departments

to check block size of any particualr folder and files residing in it:
> hdfs fsck /user/cloudera/departments -files -blocks -locations

Mac shared folder location in cloudera vm
> cd /mnt/hgfs/

