# AGAT2.0: Building and evaluating binary partition trees for image segmentation

AGAT is a Java project gathering some useful libraries for efficient construction and evaluation of binary partition trees with a special focus on image segmentation. Some of the main features are:
- smart methods and efficient data structures to handle hierarchical image representations;
- binary partition trees: standard (BPTs) and multi-feature trees (MBPTs);
- image toolbox: special methods dedicated to hierarchical image analysis. 

## Installation

<b>Project architecture and dependencies:</b> </br>
&bull; [Image](https://github.com/yonmi/Image) </br>
&bull; [BinaryPartitionTree](https://github.com/yonmi/BinaryPartitionTree) </br>
&bull; [TreeEvaluation](https://github.com/yonmi/TreeEvaluation) </br>

<b>Language:</b> Java </br>

<b>Supported systems: </b> </br>
 - Java
 - Linux, macOS, Windows

<b>Core classes:</b> </br>
&bull; [BPT](https://github.com/yonmi/BinaryPartitionTree/blob/master/src/standard/sequential/BPT.java):</b> Binary Partition Tree </br>
&bull; [MBPT](https://github.com/yonmi/BinaryPartitionTree/blob/master/src/multi/sequential/MBPT.java):</b> Multi-feature Binary Partition Tree </br>
&bull; [SegReference](https://github.com/yonmi/TreeEvaluation/blob/master/src/evaluation/datastructure/SegReference.java):</b> BPT evaluation </br>
&bull; [IntinsicEval](https://github.com/yonmi/TreeEvaluation/blob/master/src/evaluation/IntrinsicEval.java):</b> Intrinsic evaluation </br>
&bull; [ExtrinsicEval](https://github.com/yonmi/TreeEvaluation/blob/master/src/evaluation/ExtrinsicEval.java):</b> Extrinsic evaluation </br>

## Demonstration and code samples
<b>Getting started:</b> 
- you can start with some [examples](https://github.com/yonmi/BinaryPartitionTree/tree/master/src/examples) to build BPTs
- and then to evluate them with [code samples](https://github.com/yonmi/TreeEvaluation/tree/master/src/experiences/)


