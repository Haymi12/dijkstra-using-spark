# Dijkstra's Algorithm using Apache Spark (RDD-based)

## Author
Haymanot Haile

## Description
This Spark application computes the shortest paths from a source node to all other nodes in a graph using Dijkstra's algorithm implemented with RDDs.

## Requirements
- Python 3.12
- Apache Spark 3.1.2
- Running Spark cluster (Standalone mode)

## Input Format
Each line in `input_graph.txt` represents a weighted edge in the format:

source destination weight
A B 4
A C 2
B C 5
C D 1

## Usage
spark-submit dijkstra_rdd.py input_graph.txt A

## Output
The shortest paths and distances from the source node will be printed in the output.



