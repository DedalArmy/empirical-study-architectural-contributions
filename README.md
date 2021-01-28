# empirical-study-architectural-contributions

This repository contains data related to empirical study about architectural contributions.

# How to get data ? 

To get data you can use this command in a Linux terminal: 
```bash
$ mkdir paper_77 && \ 
cd paper_77 && \ 
wget -r https://anonymous.4open.science/r/a390e5b2-fb34-4f2f-b8ed-d758c4430b8c/ && \ 
cd anonymous.4open.science/repository/a390e5b2-fb34-4f2f-b8ed-d758c4430b8c/ && \
mv * ../../.. && \
cd ../../.. && \
rm -rf anonymous.4open.science
```

# What is the data format ?

In order to reduce the size of our data, we have compressed them in gzip format.
Hence data have an extension json.gz. To extract data you can use the following command in a linux terminal: 

```bash
$ cd data && \
gunzip *.json.gz
``` 