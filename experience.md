---
layout: page
title: Experience
---

<p class="message">
  Hey there! This page is a brief introduction of my previous experience.
</p>

My first job in [Qulab](http://home.ustc.edu.cn/~jyh1/) was to maintain a pipeline for analyzing iCLIP-seq data.
The pipeline basically performs some pre-processing on raw sequencing files, aligns the processed sequences to the genome and calculates per-base reverse transcription stop counts, and finally detects peaks on each transcript.
At first, I was very confused by the way the pipeline is structured: every part of the pipeline is a stand-alone program, they read files from disk, perform some computation, and output the result back to disk.
As a former informatics olympiad contestant, I was very concerned about the efficiency of this approach. Every part of the pipeline communicates with each other in a unstructured way, i.e. in text format, and even worse, the communication happened through the hard disk, which is extremely slow considering the sequencing data are usually quite large. 
