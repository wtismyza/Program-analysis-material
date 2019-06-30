# Program Analysis Resources

_(draft; work in progress)_

See also:

- [Compilers](https://raw.githubusercontent.com/MattPD/cpplinks/master/compilers.md)
  - [correctness](https://raw.githubusercontent.com/MattPD/cpplinks/master/compilers.correctness.md)

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

## Lectures & Courses

- Foundations of Programming Languages
	- M-PS (WS 2014/2015): Concepts of Programming Languages
	- http://sepl.cs.uni-frankfurt.de/2014-ws/m-ps/index.en.html
	- lectures (videos & slides): http://sepl.cs.uni-frankfurt.de/2014-ws/m-ps/sessions.en.html
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
- Program analysis for reverse engineers: from T to ⊥
	- BSides Canberra 2018; Adrian Herrera
	- https://www.youtube.com/watch?v=vOmGmjbVff4
	- slides (not displayed in the video, may be a good idea to watch alongside):
https://drive.google.com/file/d/1j9rfMt14pubi6G9PKK3akddyeet5bf0x/view
- CS 252r: Advanced Topics in Programming Languages
	- http://web-static-aws.seas.harvard.edu/courses/cs252/2011sp/
	- https://www.seas.harvard.edu/courses/cs252/2015fa/schedule.html

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
- Security Research and Development with LLVM - Andrew Reiter
	- https://github.com/roachspray/opcde2017
	- https://github.com/comaeio/OPCDE/tree/master/Security%20Research%20and%20Development%20with%20LLVM%20-%20Andrew%20Reiter
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
- Faster, Stronger C++ Analysis with the Clang Static Analyzer
	- 2018 LLVM Developers’ Meeting; George Karpenkov, Artem Dergachev
	-  https://www.youtube.com/watch?v=4n3l-ZcDJNY
- Introduction to LLVM: Building simple program analysis tools and instrumentation
	- [FOSDEM 2018](https://fosdem.org/2018/schedule/track/llvm_toolchain/) - Mike Shah
	- https://fosdem.org/2018/schedule/event/introduction/
	- https://www.youtube.com/watch?v=VKIv_Bkp4pk
	- slides & code: http://www.mshah.io/fosdem18.html
- [Nick Sumner](https://www.cs.sfu.ca/~wsumner/)'s Examples
	- slides: https://www.cs.sfu.ca/~wsumner/teaching/886/llvm.pdf
	- llvm-demo: A simple example of how LLVM can be used to gather static or dynamic facts about a program.
		- https://github.com/nsumner/llvm-demo
	+ callgraph-profiler-template: A template for an introductory project on dynamic analysis using LLVM
		- https://github.com/nsumner/callgraph-profiler-template
	+ clang-plugins-demo: A simple example of defining custom plugins for Clang and the Clang Static Analyzer
		- https://github.com/nsumner/clang-plugins-demo
	+ llvm-dataflow-analysis: (very simple) static intraprocedural dataflow analyses
		- https://github.com/nsumner/llvm-dataflow-analysis
	+ overflower-template: Template for a project to teach basic static dataflow analysis using LLVM
		- https://github.com/nsumner/overflower-template
	+ path-profiler-template: A template for a path profiling project using LLVM
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
- Writing a basic clang static analysis check
	- https://bbannier.github.io/blog/2015/05/02/Writing-a-basic-clang-static-analysis-check.html
- SeaHorn Verification Framework: A fully automated analysis framework for LLVM-based languages
	- http://seahorn.github.io/
	- https://github.com/seahorn/seahorn
	- A Context-Sensitive Memory Model for Verification of C/C++ Programs
		- Slides: http://seahorn.github.io/papers/sas17_slides.pdf
		- Paper: http://seahorn.github.io/papers/sea-dsa-SAS17.pdf
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
- https://siek.blogspot.com/2012/07/crash-course-on-notation-in-programming.html
- https://siek.blogspot.com/2013/05/type-safety-in-three-easy-lemmas.html
- What is soundness (in static analysis)? - http://www.pl-enthusiast.net/2017/10/23/what-is-soundness-in-static-analysis/
- OPLSS (Oregon Programming Languages Summer School) - https://cs.uoregon.edu/research/summerschool/
	- free video lectures available, including the introductory ones based on Practical Foundations for Programming Languages: http://www.cs.cmu.edu/~rwh/pfpl/
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
