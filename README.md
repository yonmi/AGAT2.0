# AGAT2.0: Building and evaluating binary partition trees for image segmentation

AGAT is a Java project gathering some useful libraries for efficient construction and evaluation of binary partition trees (BPT) with a special focus on image segmentation. The binary partition tree (BPT) is a classical data structure for the hierarchical modelling of images at different scales. BPTs belong both to the families of graph-based models and morphological hierarchies. They constitute an efficient way to define sets of nested partitions of image support, that further provide knowledge-guided reduced research spaces for optimization-based segmentation procedures. 

Some of the main features of AGAT are:
- graph-based methods and efficient data structures to handle hierarchical image representations;
- binary partition trees: standard (BPTs) and multi-feature / multi-image trees (MBPTs);
- collaborative strategies to establish a consensus between different metrics, thus enabling to obtain a unified hierarchical segmentation space for MBPTs;
- assesment of the quality of binary partition trees (i.e. their ability to allow further segmentation methods to compute good results) with state-of-the-art methods;
- image toolbox: special methods dedicated to hierarchical image analysis. 

![](https://github.com/yonmi/BinaryPartitionTree/blob/master/fig1.png)

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
- and then to evaluate them with [code samples](https://github.com/yonmi/TreeEvaluation/tree/master/src/experiences/)

## Third-party libraries
AGAT2.0 bundles some third-party libraries:
- [jai_codec](http://svnsis.ethz.ch/repos/cisd/ivy-repository/trunk/sis/sis-jhdf5/14.12.1/), [jai_core](http://svnsis.ethz.ch/repos/cisd/ivy-repository/trunk/sis/sis-jhdf5/14.12.1/), [jai_imageio](http://svnsis.ethz.ch/repos/cisd/ivy-repository/trunk/sis/sis-jhdf5/14.12.1/) are parts of the <b>Java Advanced Imaging API</b> which is a set of image encoder/decoder (codec) classes - [Java Research License (JRL)](https://github.com/mauricio/jai-core/blob/master/LICENSE-JRL.txt)
- [sis-jhdf5](http://svnsis.ethz.ch/repos/cisd/ivy-repository/trunk/sis/sis-jhdf5/14.12.1/) helps to manage <b>HDF5</b> file formats - [Apache License 2.0](
http://www.apache.org/licenses/LICENSE-2.0)

