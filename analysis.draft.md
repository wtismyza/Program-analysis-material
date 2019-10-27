# Program Analysis Resources

_(draft; work in progress)_

See also:

- [Compilers](https://github.com/MattPD/cpplinks/blob/master/compilers.md)
  - [correctness](https://github.com/MattPD/cpplinks/blob/master/compilers.correctness.md)

## General

- Program Analysis Reading List - Rolf Rolles - http://www.msreverseengineering.com/program-analysis-reading-list/
- Reading for graduate students in static analysis - http://matt.might.net/articles/books-papers-materials-for-graduate-students/#analysis
- Program Analysis Resources - http://reversing.io/resources/
- Conferences on Software Verification and Analysis - https://github.com/soarlab/conferences
- Static Analysis Roadmap - https://tpiazza.me/posts/2017-11-01-static-analysis-roadmap.html

### Symbolic Execution

- Awesome Symbolic Execution - https://github.com/ksluckow/awesome-symbolic-execution
- Symbolic execution history timeline: https://github.com/enzet/symbolic-execution
- Symbolic Execution: Intuition and Implementation - http://www.usrsb.in/symbolic-execution-intuition-and-implementation.html
- A bibliography of papers related to symbolic execution - https://github.com/saswatanand/symexbib
- A Survey of Symbolic Execution Techniques
	- ACM Computing Surveys 51(3) 2018
	- Roberto Baldoni, Emilio Coppa, Daniele Cono D'Elia, Camil Demetrescu, Irene Finocchi
	- https://github.com/season-lab/survey-symbolic-execution
	- https://arxiv.org/abs/1610.00502
- Systematic Comparison of Symbolic Execution Systems: Intermediate Representation and its Generation
	- Annual Computer Security Applications Conference (ACSAC) 2019
	- Sebastian Poeplau and Aurélien Francillon
	- http://s3.eurecom.fr/tools/symbolic_execution/
	- http://s3.eurecom.fr/docs/acsac19_poeplau.pdf
	- https://hal.archives-ouvertes.fr/hal-02305914/

## Lectures & Courses

- Foundations of Programming Languages
	- M-PS (WS 2014/2015): Concepts of Programming Languages
	- http://sepl.cs.uni-frankfurt.de/2014-ws/m-ps/index.en.html
	- http://web.archive.org/web/http://sepl.cs.uni-frankfurt.de/2014-ws/m-ps/index.en.html
	- lectures (videos & slides):
		- https://www.youtube.com/channel/UCpSoGwyH5yHHvQut3x6c_2g/playlists
		- http://sepl.cs.uni-frankfurt.de/2014-ws/m-ps/sessions.en.html
		- http://web.archive.org/web/http://sepl.cs.uni-frankfurt.de/2014-ws/m-ps/sessions.en.html
- Static Program Analysis
	- Anders Møller and Michael I. Schwartzbach
	- https://cs.au.dk/~amoeller/spa/
	- PLISS 2019 - Anders Møller 
		- Static Program Analysis (part 1/2) - https://www.youtube.com/watch?v=Lr4cMmaJHrg
		- Static Program Analysis (part 2/2) - https://www.youtube.com/watch?v=6QQSIIvH-F0
- 25 Years of Program Analysis
	- DEF CON 25 (2017) - Yan Shoshitaishvili (Zardus)
	- https://www.youtube.com/watch?v=XL9kWQ3YpLo
	- https://media.defcon.org/DEF%20CON%2025/DEF%20CON%2025%20presentations/DEFCON-25-Zardus-25-Years-of-Program-Analysis-UPDATED.pdf
- Software Analysis and Testing - [Mayur Naik](http://www.cis.upenn.edu/~mhnaik/)
	- http://rightingcode.org/
	- http://www.cis.upenn.edu/~mhnaik/edu/cis700/
	- https://www.youtube.com/channel/UCvwqRhlkE_Wm2FF9qzvHfJw
- Program Analysis and Reliability - Nick Sumner, CMPT 886, Spring 2015, SFU
	- Playlist: https://www.youtube.com/playlist?list=PLNC6lmsIySCOPjY8IwKBtD2cqe-MMgIGM
	- Schedule & Slides: http://www.cs.sfu.ca/~wsumner/teaching/886/15/schedule.html
- Program analysis for reverse engineers: from T to ⊥
	- BSides Canberra 2018; Adrian Herrera
	- https://www.youtube.com/watch?v=vOmGmjbVff4
	- slides (not displayed in the video, may be a good idea to watch alongside):
https://drive.google.com/file/d/1j9rfMt14pubi6G9PKK3akddyeet5bf0x/view
- CS 252r: Advanced Topics in Programming Languages
	- http://web-static-aws.seas.harvard.edu/courses/cs252/2011sp/
	- https://www.seas.harvard.edu/courses/cs252/2015fa/schedule.html
- A Gentle Introduction to Program Analysis
	- Programming Languages Mentoring Workshop 2014
	- Isıl Dillig (University of Texas)
	- https://www.cis.upenn.edu/~alur/CIS673/isil-plmw.pdf

## Software

- SPARTA: a library that provides the basic blocks for building high-performance static code analyzers based on Abstract Interpretation
	- https://github.com/facebookincubator/SPARTA
	- SPARTA: a C++ library of software components for building high-performance static analyzers
	- https://code.fb.com/open-source/sparta/
- Bill Torpey - [static analysis posts](http://btorpey.github.io/blog/categories/static-analysis/)
	- Static Analysis with Clang - http://btorpey.github.io/blog/2015/04/27/static-analysis-with-clang/
	- Mo' Static - http://btorpey.github.io/blog/2016/04/07/mo-static/
	- Even Mo' Static - http://btorpey.github.io/blog/2016/11/12/even-mo-static/
	- Lots o' static - http://btorpey.github.io/blog/2017/09/17/lotso-static/

### LLVM

- awesome-llvm: A curated list of awesome LLVM related docs, tools, and other resources
	- https://github.com/HongxuChen/awesome-llvm
- LLVM Weekly - http://llvmweekly.org/
- https://eli.thegreenplace.net/tag/llvm-clang
- Security Research and Development with LLVM - Andrew Reiter
	- https://github.com/roachspray/opcde2017
	- https://github.com/comaeio/OPCDE/tree/master/2017/Security%20Research%20and%20Development%20with%20LLVM%20-%20Andrew%20Reiter
	- Examples - https://github.com/roachspray/opcde2017/tree/master/code
- Building a Checker in 24 hours
	- 2012 LLVM Developers’ Meeting; Anna Zaks, Jordan Rose
	- https://llvm.org/devmtg/2012-11/Zaks-Rose-Checker24Hours.pdf
	- https://www.youtube.com/watch?v=kdxlsP5QVPw
- Code transformation and analysis using Clang and LLVM
	- Static and Dynamic Analysis
	- HPC Summer School 2017; Hal Finkel
	- https://llvm.org/devmtg/2017-06/2-Hal-Finkel-LLVM-2017.pdf
	- https://github.com/hfinkel/llvm-ss-2017
- Compiler-assisted Performance Analysis
	- 2016 LLVM Developers’ Meeting; Adam Nemet
	- https://github.com/llvm-mirror/llvm/tree/master/tools/opt-viewer
	- https://llvm.org/devmtg/2016-11/Slides/Nemet-Compiler-assistedPerformanceAnalysis.pdf
	- https://www.youtube.com/watch?v=qq0q1hfzidg
- clang-llvm-tutorial
	- Clang and LLVM Tutorial Examples (AST Interpreter, Function Pointer Analysis, Value Range Analysis, Data-Flow Analysis, Andersen Pointer Analysis, LLVM Backend)
	- https://github.com/lijiansong/clang-llvm-tutorial/
- Custom Alias Analysis in LLVM
	- https://blog.tartanllama.xyz/llvm-alias-analysis/
- Dg: LLVM Static Slicer
	- Dependence graph for programs. A set of generic program analyses and a static slicer for LLVM bitcode
	- https://github.com/mchalupa/dg
- Faster, Stronger C++ Analysis with the Clang Static Analyzer
	- 2018 LLVM Developers’ Meeting; George Karpenkov, Artem Dergachev
	- https://www.youtube.com/watch?v=4n3l-ZcDJNY
- FPSCEV: Floating-Point Scalar Evolution in LLVM
	- https://github.com/sheredom/fpscev
	- http://www.duskborn.com/posts/fpscev/
	- http://www.duskborn.com/posts/fpscev-fast-math-propagation/
	- http://www.duskborn.com/posts/fpscev-inst-simplify/
	- http://www.duskborn.com/posts/fpscev-improved-range/
- Introduction to LLVM: Building simple program analysis tools and instrumentation
	- [FOSDEM 2018](https://fosdem.org/2018/schedule/track/llvm_toolchain/) - Mike Shah
	- https://fosdem.org/2018/schedule/event/introduction/
	- https://www.youtube.com/watch?v=VKIv_Bkp4pk
	- slides & code: http://www.mshah.io/fosdem18.html
- LLVM Debugging Tips and Tricks
	- http://bholt.org/posts/llvm-debugging.html
- LLVMPlayground: Small sample programs that use LLVM and Clang APIs.
	- https://github.com/modocache/LLVMPlayground
- Mapping High Level Constructs to LLVM IR
	- https://github.com/f0rki/mapping-high-level-constructs-to-llvm-ir
	- https://mapping-high-level-constructs-to-llvm-ir.readthedocs.io/
- [Nick Sumner](https://www.cs.sfu.ca/~wsumner/)'s Examples
	- slides: https://www.cs.sfu.ca/~wsumner/teaching/886/llvm.pdf
	- llvm-demo: A simple example of how LLVM can be used to gather static or dynamic facts about a program.
		- https://github.com/nsumner/llvm-demo
	- callgraph-profiler-template: A template for an introductory project on dynamic analysis using LLVM
		- https://github.com/nsumner/callgraph-profiler-template
	- clang-plugins-demo: A simple example of defining custom plugins for Clang and the Clang Static Analyzer
		- https://github.com/nsumner/clang-plugins-demo
	- llvm-dataflow-analysis: (very simple) static intraprocedural dataflow analyses
		- https://github.com/nsumner/llvm-dataflow-analysis
	- overflower-template: Template for a project to teach basic static dataflow analysis using LLVM
		- https://github.com/nsumner/overflower-template
	- path-profiler-template: A template for a path profiling project using LLVM
		- https://github.com/nsumner/path-profiler-template
- KLEE Symbolic Virtual Machine
	- http://klee.github.io/
	- http://klee.github.io/publications/
	- https://github.com/klee/klee
- Phasar - A LLVM-based static code analysis framework
	- http://phasar.org/
	- https://github.com/secure-software-engineering/phasar
	- Static Analysis for C++ with Phasar
	- https://pldi18.sigplan.org/event/pldi-2018-pldi-tutorials-static-analysis-for-c-with-phasar
	- PhASAR: An Inter-Procedural Static Analysis Framework for C/C++
		- TACAS 2019
		- Philipp D. Schubert, Ben Hermann, Eric Bodden
		- http://www.thewhitespace.de/publications/shb19-phasar.pdf
- Quarkslab blog
	- https://blog.quarkslab.com/global-dead-code-elimination-for-llvm-revisited.html
	- https://blog.quarkslab.com/turning-regular-code-into-atrocities-with-llvm-the-return.html
	- https://blog.quarkslab.com/turning-regular-code-into-atrocities-with-llvm.html
- Writing a basic clang static analysis check
	- https://bbannier.github.io/blog/2015/05/02/Writing-a-basic-clang-static-analysis-check.html
- SeaHorn Verification Framework: A fully automated analysis framework for LLVM-based languages
	- http://seahorn.github.io/
	- https://github.com/seahorn/seahorn
	- A Context-Sensitive Memory Model for Verification of C/C++ Programs
		- Slides: http://seahorn.github.io/papers/sas17_slides.pdf
		- Paper: http://seahorn.github.io/papers/sea-dsa-SAS17.pdf
	- Crab-llvm: Abstract Interpretation of LLVM bitcode
		- https://github.com/seahorn/crab-llvm
- SVF: Interprocedural Static Value-Flow Analysis in LLVM 
	- Pointer Analysis and Program Dependence Analysis for C and C++ Programs
	- http://unsw-corg.github.io/SVF/
	- https://github.com/unsw-corg/SVF
	- SVF: Interprocedural Static Value-Flow Analysis in LLVM
		- Compiler Construction (CC '16)
		- Yulei Sui and Jingling Xue
		- https://yuleisui.github.io/publications/cc16.pdf
		- 2016 EuroLLVM Developers' Meeting: Y. Sui "SVF: Static Value-Flow Analysis in LLVM"
		- https://www.youtube.com/watch?v=nD-i-enA8rc
- LLVM IR Tutorial - Phis, GEPs and other things, oh my!
	- 2019 EuroLLVM Developers’ Meeting; Vince Bridgers, Felipe de Azevedo Piovezan (Intel)
	- https://www.youtube.com/watch?v=m8G_S5LwlTo
- Intrinsics, Metadata, and Attributes: The story continues!
	- 2016 LLVM Developers’ Meeting
	- Hal Finkel, Argonne National Laboratory
	- https://www.youtube.com/watch?v=jII0AcgU_5c
- Northeastern+MIT LLVM Seminar
	- 2019; Mike Shah
	- http://www.mshah.io/#Talks
	- https://www.youtube.com/playlist?list=PLvv0ScY6vfd8NDoT7qUab4VVAWV67oH-N
	- Introduction to LLVM 
		- https://www.youtube.com/watch?v=KTMk45Q0d-8&list=PLvv0ScY6vfd8NDoT7qUab4VVAWV67oH-N
		- http://www.mshah.io/LLVM/NortheasternMITIntroduction%20to%20LLVM.pdf
		- http://www.mshah.io/LLVM/llvm_6_3_19.zip
	- Introduction to Clang 
		- https://www.youtube.com/watch?v=RAzre6PA-WI&list=PLvv0ScY6vfd8NDoT7qUab4VVAWV67oH-N
		- http://www.mshah.io/LLVM/NortheasternMITIntroductiontoClang.pdf
	- Introduction to Program Analysis using LLVM
		- http://www.mshah.io/LLVM/NortheasternMITIntroductiontoProgramAnalysisusingLLVM.pdf
		- https://www.youtube.com/watch?v=w6SD3ramrwI&list=PLvv0ScY6vfd8NDoT7qUab4VVAWV67oH-N

#### Instrumentation

- Creating an LLVM Sanitizer from Hopes and Dreams
	- https://blog.trailofbits.com/2019/06/25/creating-an-llvm-sanitizer-from-hopes-and-dreams/
	- llvm-sanitizer-tutorial and documentation
		- https://github.com/trailofbits/llvm-sanitizer-tutorial
- Loom: LLVM instrumentation library
	- https://github.com/cadets/loom
- QBDI (QuarkslaB Dynamic binary Instrumentation): A Dynamic Binary Instrumentation framework based on LLVM
	- https://qbdi.quarkslab.com
	- https://github.com/quarkslab/QBDI
	- 34C3 (2017) Implementing an LLVM based Dynamic Binary Instrumentation framework: https://events.ccc.de/congress/2017/Fahrplan/events/9006.html
	- Example: plugging Triton on top of QBDI - http://shell-storm.org/repo/Notepad/qbdi_with_triton.txt
	- A Preliminary Test of QBDI - https://www.johnfxgalea.com/2018/01/13/a-preliminary-test-of-qbdi/
	- Example: SRAC - a Simple Return Address Checker - https://github.com/johnfxgalea/SRAC
- sbt-instrumentation: Configurable instrumentation of LLVM bitcode
	- https://github.com/staticafi/sbt-instrumentation
	- Instrumentation of LLVM IR - https://is.muni.cz/th/409920/fi_m/?lang=en

#### Lifting

Lifting: Disassembly, Decompilation, Recompilation, Reverse Engineering

- McSema: Framework for lifting x86, amd64, and aarch64 program binaries to LLVM bitcode
	- https://www.trailofbits.com/research-and-development/mcsema/
	- https://github.com/trailofbits/mcsema
	- Decompiling Binaries into LLVM IR Using McSema and Dyninst
		- https://is.muni.cz/th/pxe1j/?lang=en
- llvm-mctoll
	- This tool statically (AOT) translates (or raises) binaries to LLVM IR.
	- https://github.com/Microsoft/llvm-mctoll
	- Raising binaries to LLVM IR with MCTOLL
		- LCTES 2019 (WIP paper)
		- S. Bharadwaj Yadavalli, Aaron Smith
		- https://dl.acm.org/citation.cfm?id=3326354
		- https://conf.researchr.org/details/LCTES-2019/LCTES-2019-papers/15/Raising-Binaries-to-LLVM-IR-with-MCTOLL-Work-in-progress-
- Remill:  Library for lifting of x86, amd64, and aarch64 machine code to LLVM bitcode
	- https://github.com/trailofbits/remill
- RetDec: a retargetable machine-code decompiler based on LLVM
	- https://retdec.com/
	- https://github.com/avast-tl/retdec
- revng: a static binary translator
	- revng is a static binary translator. Given a input ELF binary for one of the supported architectures (currently MIPS, ARM and x86-64) it will analyze it and emit an equivalent LLVM IR. To do so, revng employs the QEMU intermediate representation (a series of TCG instructions) and then translates them to LLVM IR.
	- https://rev.ng/
	- https://github.com/revng/revng

#### Passes

- Building, Testing and Debugging a Simple out-of-tree LLVM Pass
	- 2016 EuroLLVM Developers' Meeting
	- Serge Guelton & Adrien Guinet
	- http://llvm.org/devmtg/2016-03/Tutorials/Tutorial.pdf
	- https://github.com/quarkslab/llvm-dev-meeting-tutorial-2015
	- https://blog.quarkslab.com/goto-llvm_dev_meeting.html
	- https://www.youtube.com/watch?v=Z5KcwVaak3s
- llvm-tutor: Basic LLVM passes for learning the API
	- https://github.com/banach-space/llvm-tutor

##### Legacy Pass Manager

- 2007 LLVM Developer's Meeting
	- http://llvm.org/devmtg/2007-05/03-Patel-Passmanager.pdf
	- LLVM Pass Manager Demystified (1 of 3) - https://www.youtube.com/watch?v=dZOrlikTaik
	- LLVM Pass Manager Demystified (2 of 3) - https://www.youtube.com/watch?v=PaUWxVLGBg0
	- LLVM Pass Manager Demystified (3 of 3) - https://www.youtube.com/watch?v=4HEy5EtVdCA

##### New Pass Manager

- New PM: taming a custom pipeline of Falcon JIT
	- 2018 EuroLLVM Developers’ Meeting - Fedor Sergeev, Azul Systems
	- https://www.youtube.com/watch?v=6X12D46sRFw
	- http://llvm.org/devmtg/2018-04/slides/Sergeev-Taming%20a%20custom%20pipeline%20of%20Falcon%20JIT.pdf
- The LLVM Pass Manager, Part 2
	- 2014 LLVM Developers' Meeting
	- Chandler Carruth, Google
	- https://llvm.org/devmtg/2014-10/#talk11
	- https://llvm.org/devmtg/2014-10/Slides/Carruth-TheLLVMPassManagerPart2.pdf
	- Video: http://web.archive.org/web/20160718071630/http://llvm.org/devmtg/2014-10/Videos/The%20LLVM%20Pass%20Manager%20Part%202-720.mov
- Passes in LLVM, Part 1
	- 2014 European LLVM Conference
	- Chandler Carruth
	- https://www.youtube.com/watch?v=rY02LT08-J8
	- https://llvm.org/devmtg/2014-04/PDFs/Talks/Passes.pdf
- Writing LLVM Pass in 2018
	- Preface - https://medium.com/@mshockwave/writing-llvm-pass-in-2018-preface-6b90fa67ae82
	- Part I: Write a new HelloWorld Pass in new pass manager fashion
		- https://medium.com/@mshockwave/writing-llvm-pass-in-2018-preface-6b90fa67ae82
	- Part II - AnalysisManager - https://medium.com/@mshockwave/writing-llvm-pass-in-2018-part-ii-640f680978ec
	- Part III - In-Tree Pass Integration - https://medium.com/@mshockwave/writing-llvm-pass-in-2018-part-iii-d44cd0c2c354

## Readings

- A Few Billion Lines of Code Later: Using Static Analysis to Find Bugs in the Real World
	- Communications of the ACM, Vol. 53 No. 2, 2010
	- Al Bessey, Ken Block, Ben Chelf, Andy Chou, Bryan Fulton, Seth Hallem, Charles Henri-Gros, Asya Kamsky, Scott McPeak, Dawson Engler
	- https://cacm.acm.org/magazines/2010/2/69354-a-few-billion-lines-of-code-later/fulltext
- All You Ever Wanted to Know About Dynamic Taint Analysis and Forward Symbolic Execution (but might have been afraid to ask)
	- Security and Privacy (SP), 2010
	- Edward J. Schwartz, Thanassis Avgerinos, David Brumley
	- Paper: https://edmcman.github.io/papers/oakland10.pdf
	- Slides: https://edmcman.github.io/pres/oakland10.pdf
- Analysing the Program Analyser
	- https://srg.doc.ic.ac.uk/publications/analyse-analyser-icse-v2025.html
- Continuous Reasoning: Scaling the Impact of Formal Methods
	- Logic in Computer Science (LISC) 2018; Peter O'Hearn
	- https://research.fb.com/publications/continuous-reasoning-scaling-the-impact-of-formal-methods/
- From Start-ups to Scale-ups: Opportunities and Open Problems for Static and Dynamic Program Analysis
	- IEEE International Working Conference on Source Code Analysis and Manipulation (SCAM) 2018
	- Mark Harman, Peter O'Hearn
	- https://research.fb.com/publications/from-start-ups-to-scale-ups-opportunities-and-open-problems-for-static-and-dynamic-program-analysis/
- Lessons from Building Static Analysis Tools at Google (2018)
	- https://cacm.acm.org/magazines/2018/4/226371-lessons-from-building-static-analysis-tools-at-google/fulltext
- Pointer analysis: haven't we solved this problem yet?
	- PASTE 2001
	- https://dl.acm.org/citation.cfm?id=379665
	- http://www.cs.trinity.edu/~mlewis/CSCI3294-F01/Papers/p54-hind.pdf
- Righting Software
	- IEEE Software,  May 2004
	- https://www.microsoft.com/en-us/research/publication/righting-software/
- Source Code Analysis: A Road Map
	- Future of Software Engineering (FOSE) 2007
	- David Binkley
	- https://dl.acm.org/citation.cfm?id=1254713
- Static versus dynamic analysis---an illusory distinction?
	- https://www.cs.kent.ac.uk/people/staff/srk21/blog/research/static-and-dynamic-analyses.html

## Background

- https://blog.acolyer.org/2018/01/26/a-practitioners-guide-to-reading-programming-languages-papers/
- Crash Course on Notation in Programming Language Theory
	- Jeremy G. Siek
	- LambdaConf 2018
	- Part 1: https://www.youtube.com/watch?v=vU3caZPtT2I
	- Part 2: https://www.youtube.com/watch?v=MhuK_aepu1Y …
	- Slides: https://www.dropbox.com/s/joaq7m9v75blrw5/pl-notation-lambdaconf-2018.pdf?dl=1
	- 2012 blog post: http://siek.blogspot.com/2012/07/crash-course-on-notation-in-programming.html
- Type Safety in Three Easy Lemmas 
	- https://siek.blogspot.com/2013/05/type-safety-in-three-easy-lemmas.html
- On the Relationship Between Static Analysis and Type Theory 
	- https://semantic-domain.blogspot.com/2019/08/on-relationship-between-static-analysis.html
- Soundness and completeness: with precision
	- https://bertrandmeyer.com/2019/04/21/soundness-completeness-precision/
- What is soundness (in static analysis)? - http://www.pl-enthusiast.net/2017/10/23/what-is-soundness-in-static-analysis/
- OPLSS (Oregon Programming Languages Summer School)
	- https://cs.uoregon.edu/research/summerschool/
	- 2018-2017, 2003: https://www.youtube.com/channel/UCDe6N9R7U-RYWA57wzJQ2SQ/playlists
	- 2016-2015: https://www.youtube.com/channel/UCsON_8vogp4nCQFTnfu43kA/playlists
	- free video lectures available, including the introductory ones based on Practical Foundations for Programming Languages: http://www.cs.cmu.edu/~rwh/pfpl/
- Programming Language Implementation Summer School (PLISS)
	- https://pliss2019.github.io/talks.html
	- https://www.youtube.com/channel/UCofC5zis7rPvXxWQRDnrTqA/playlists 
- SSA book - http://ssabook.gforge.inria.fr/latest/
- Intermediate Representations in Imperative Compilers: A Survey
	- ACM Computing Surveys, Vol. 45, No. 3, Article 26, 2013
	- James Stanier, Des Watson
	- http://dx.doi.org/10.1145/2480741.2480743
	- http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.885.5223&rep=rep1&type=pdf
- Modern Intermediate Representations (IR)
	- Introduction to LLVM - David Chisnall (Cambridge University)
	- [HPC Summer School 2017](https://llvm.org/devmtg/2017-06/)
	- https://llvm.org/devmtg/2017-06/1-Davis-Chisnall-LLVM-2017.pdf
- Testing Intermediate Representations for Binary Analysis
	- https://softsec.kaist.ac.kr/~soomink/paper/ase17main-mainp491-p.pdf
	- https://github.com/SoftSec-KAIST/MeanDiff
	- https://softsec-kaist.github.io/MeanDiff/
- CS 7194 - Great works in Programming Languages - https://www.cs.cornell.edu/courses/cs7194/2019sp/
- Type Systems - Neel Krishnaswami
	- https://www.cl.cam.ac.uk/teaching/1819/Types/materials.html
	- https://www.cl.cam.ac.uk/teaching/1819/Types/handout.pdf
- http://jschuster.org/blog/2016/11/29/getting-started-in-programming-languages/
- Programming Languages: Application and Interpretation by Shriram Krishnamurthi
  - http://cs.brown.edu/~sk/Publications/Books/ProgLangs/
- SIGPLAN Awards - http://www.sigplan.org/Awards/
- Great Works in Programming Languages
  - Collected by Benjamin C. Pierce
  - https://www.cis.upenn.edu/~bcpierce/courses/670Fall04/GreatWorksInPL.shtml
- 10PL: 10 papers that all PhD students in programming languages ought to know, for some value of 10
  - Northeastern University Programming Research Lab 
  - https://github.com/nuprl/10PL
- Best of PLDI 2004
  - https://dblp.uni-trier.de/db/conf/pldi/pldi2004best.html
- Classic Papers in Programming Languages and Logic
  - Karl Crary
  - https://www.cs.cmu.edu/~crary/819-f09/
- What Type Soundness Theorem Do You Really Want to Prove?
	- https://blog.sigplan.org/2019/10/17/what-type-soundness-theorem-do-you-really-want-to-prove/
	- Milner Award Lecture: The Type Soundness Theorem That You Really Want to Prove (and now you can)
		- POPL 2018; Derek Dreyer
		- https://www.youtube.com/watch?v=8Xyk_dGcAwk
