---
layout: default
title: F
has_children: false
nav_order: 4
---

## Fine Tuning Query Representation using Iterative Negative Feedback
__Authors__: Mudit Chaudhary, Dhawal Gupta  
__Venue__: Course Research Project for COMPSCI 646 Information Retrieval at UMass Amherst (Prof. Hamed Zamani)  
__Abstract__: Dense retrieval methods such as DPR are becoming increasingly popular due to their superior performance over traditional retrieval  methods. Furthermore, dense retrieval methods are able to model the semantic meaning of the query and the documents. One of the ways to improve the retrieval performance of these methods is to use a re-ranker. Often, the re-rankers (e.g., cross-encoders)
are computationally expensive and impractical for fast re-ranking
on a large list of documents. Alternative ways to improve the performance is to use query representation refinement methods to re-rank the documents. Majority of the research focuses on using
positive relevance feedback for improving the dense query representation. Work on using negative relevance feedback for dense
query refinement is severely limited. In this paper, we propose a
simple and computationally inexpensive model for query refinement using negative relevance feedback to re-rank documents. We perform experiments on the MS-Marco passage re-ranking task and aim to refine dense query representations from DPR.  
__Report Link__: [Link](/assets/documents/646_NegativeFeedback.pdf)
