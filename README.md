# Hive-cmd

## bin folder

This folder contains all .cmd files needed to run Apache Hive on windows (taken from https://svn.apache.org/repos/asf/hive/trunk/bin/)

**You can download the whole bin folder and copy it on the top of the current Hive\bin folder.**

## guava-27.0-jre.jar

This file is taken from an Apache Hadoop 3.2.1 installation. It is needed to solve a [Bug within Apache Hive 3.1.2](https://issues.apache.org/jira/browse/HIVE-22718):
It should replace the guava-19.0.jar located in *apache-hive-3.1.2-bin\lib* folder.

