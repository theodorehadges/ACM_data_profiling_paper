# ACM-style paper for profiling big datasets project

## Status: DRAFT

### [View PDF of draft](https://github.com/theodorehadges/ACM_data_profiling_paper/blob/master/project_files/generic_and_semantic_profiling_of_big_datasets.pdf)

### [View source code](https://github.com/theodorehadges/big_data_course_project)

<hr>

We call ourselves **CreaTAK**  
**T** is for [Theodore](https://github.com/theodorehadges)  
**A** is for [Ankush](https://github.com/ankushjain2001)  
**K** is for [Kat](https://github.com/ruinanzhang)  
...and we all like to **create** stuff.


In this study, we ran [Apache Spark](https://spark.apache.org/) over [NYU’s 48-node Hadoop cluster](https://wikis.nyu.edu/display/NYUHPC/Clusters+-+Dumbo), running [Cloudera CDH 5.15.0](https://www.cloudera.com/products/open-source/apache-hadoop/key-cdh-components.html), to generically and semantically profile 1159 datasets from [NYC Open Data](https://opendata.cityofnewyork.us/). We refer to these two profiling methods as Task 1 and Task 2, respectively.

Of the 1159 files we profiled in Task 1, we found 11674 integer columns, 13646 text
columns, 1137 date/time columns, and 4527 real number columns. For Task 2, we
analyzed 260 columns and we were able to identify the semantic types for 210 columns
with a precision of 72.40%.




