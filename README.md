# Replication Package for "Mining Co-change Information to Understand When Build Changes Are Necessary"

Shane McIntosh, Bram Adams, Meiyappan Nagappan, and Ahmed E. Hassan  
[Published at the International Conference on Software Maintenance and Evolution - ICSME 2014](http://dx.doi.org/10.1109/ICSME.2014.46)

Abstract. As a software project ages, its source code is modified to add new features, restructure existing ones, and fix defects. These source code changes often induce changes in the build system, i.e., the system that specifies how source code is translated into deliverables. However, since the internal structure of a build system is known to be complex, and developers typically are not familiar with the (occasionally archaic) build technology, they may not be able to identify source code changes that require changes to the build system. This can cause build breakages that slow development progress and impact other developers, testers, and even customers. In this paper, we mine the source code changes that required accompanying build changes to better understand the nature of build system evolution. We build random forest classifiers using language-agnostic and language-specific code change characteristics to predict when build changes are necessary based on historical trends. Case studies of the Mozilla and Eclipse open source systems, as well as the IBM Jazz proprietary system show that our classifiers can accurately predict when build changes are necessary with up to 81%-83% AUC. However, an analysis of defects that impact Java build systems shows that the factors that drive Java build changes are often not code-related, and hence are harder to predict. Code change characteristics can accurately explain several types of build changes that can assist developers in maintaining build systems. However, further study is needed to assist other software team members, such as quality assurance and release engineering personnel with build maintenance. 

## Bibtex

```bibtex
@INPROCEEDINGS{Mcintosh14,
author={S. Mcintosh and B. Adams and M. Nagappan and A. E. Hassan},
booktitle={2014 IEEE International Conference on Software Maintenance and Evolution},
title={Mining Co-change Information to Understand When Build Changes Are Necessary},
year={2014},
pages={241-250},
doi={10.1109/ICSME.2014.46},
ISSN={1063-6773},
month={Sept},
}
```

## Data and Scripts

- Case Study Setup
  - [File type classifications (Eclipse-core, Mozilla)](https://github.com/SAILResearch/replication-build_cochanges/releases/latest)

