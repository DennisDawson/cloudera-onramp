# cloudera-onramp
Cross-product examples for getting started with CDH and related technologies.

The goal here is to try out different ways to implement simple solutions using Cloudera technologies. I'll hack through keep notes of what I do. Collaboration and comments will help me improve and expand upon my examples. When they are vetted and verified, I can add them to mainstream documentation.

## Sentiment Analysis

This example builds on the basic Hadoop Word Count tutorial using custom counters to filter and sum up positive words versus negative words and return a relative score. The algorithm is not robust, but it shows the place where a more savvy developer might add more compelling code.

## Flume to HDFS

This example shows how to use Flume on the QuickStart VM, first with the standard configuration to capture log info, then to capture log entries in HDFS. You can use the information you enter with the Sentiment Analysis example.
