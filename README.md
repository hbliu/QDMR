README for QDMR
----------------
*Time-stamp: <2020-06-15 Hongbo Liu>*

Introduction
------------
**QDMR** (Quantitative Differentially Methylated Regions) is a quantitative approach to **quantify methylation difference and identify DMRs** from genome-wide methylation profiles by **adapting Shannon entropy**. The platform-free and species-free nature of QDMR makes it potentially applicable to various methylation data. This approach provides an effective tool for the high-throughput identification of the functional regions involved in epigenetic regulation.

The current version of QDMR provide users three both online platform and standalone software for methylation data. And the command line version of QDMR is also launched recently to facilitate the analysis of massive methylation data.
QDMR works from the imported methylation data across a number of samples. It performs all of the steps in following the workflow in Tutorial, including Import Data, **Quantify Difference**, **Identify DMRs**, **Measure Specificity** and Export All Results. Its graphical tools also allow the user to manually inspect the raw methylation levels across samples any time.

Detailed information about QDMR is available at http://fame.edbc.org/qdmr.


Features of QDMR
----------------------
- **Quantify Difference** *~~~~~~~~Quantify methylation variance among different samples (i.e. cell types, time points) based on adapting Shannon entropy.*
- **Identify DMRs** *~~~~~~~~Identify DMRs by threshold determined for given sample size.*
- **Measure Specificity** *~~~~~~~Caculate categorical specificity for each DMR in each sample.*
- **Cross-platform** *~~~~~~~Support almost any operating system, including Windows, MacOS, Linux and Solaris with a suitable version of Java is installed.*
- **Friendly Interface** *~~~~~~~Identify DMRs in a friendly interface.*
- **Online version** *~~~~~~~Identify DMRs directly only on your web browser.*
- **Command line version** *~~~~~~~Command line version of QDMR enables high-throughput analysis.*

Install
-------
Installation is not needed for most users by visiting http://fame.edbc.org/qdmr/QDMR.jnlp

QDMR also supports installation pacages at http://fame.edbc.org/qdmr/Downloads.jsp

`Please make sure a suitable version of Java is installed on your system.`

Usage of QDMR
---------------
Detailed usage guide is available at http://fame.edbc.org/qdmr/Tutorial.jsp

Example data
-------
The example data can be found in the import interface.


Output Files
------------
The results will be saved in a folder containing Entropy Table, DMR Table, N-DMR Table, Specificity Table and Statistics.
- **Entropy Table** ~ *Methylation variance of each region among different samples*
- **DMR Table** ~ *DMRs identified by QDMR*
- **N-DMR Table** ~ *Regions are not differentially methylated*
- **Specificity Table** ~ *Categorical specificity for each DMR in each sample*
- **Statistics** ~ *Summary of QDMR job*

Other useful links
------------------
:QDMR:  http://fame.edbc.org/qdmr/

:Forum: https://groups.google.com/forum/#!forum/qdmr

:SMART: http://fame.edbc.org/smart/


Citation
--------
Yan Zhang, Hongbo Liu, Jie Lv, Xue Xiao, Jiang Zhu, Xiaojuan Liu, Jianzhong Su, Xia Li, Qiong Wu, Fang Wang and Ying Cui (2011) *QDMR: a quantitative method for identification of differentially methylated regions by entropy*. Nucleic Acids Res, 39, e58. https://academic.oup.com/nar/article-lookup/doi/10.1093/nar/gkr053

Contact
-------
:For any help:  you are welcome to write to Hongbo Liu (hongbo919@gmail.com) at http://cce.edbc.org/members/HongboLiu.html.
