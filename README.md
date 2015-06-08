# cloudera-onramp
Cross-product examples for getting started with CDH and related technologies.

The goal here is to try out different ways to implement simple solutions using Cloudera technologies. I'll blaze the trail and keep notes of what I do. I hope to receive collaboration and comments to improve and expand upon my examples. When they are vetted and verified, I can add them to mainstream documentation.

## Sentiment Analysis

This example builds on the basic Hadoop Word Count tutorial using custom counters to filter and sum up positive words versus negative words and return a relative score. The algorithm is not robust, but it shows the place where a more savvy developer might add more compelling code.

## Flume to HDFS

This example shows how to use Flume on the QuickStart VM, first to use the standard configuration to capture log info, then to capture Telnet communication to HDFS. It shows how the information you enter can be used for Sentiment Analysis.


