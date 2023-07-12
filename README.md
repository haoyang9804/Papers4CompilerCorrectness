# An Ever-growing Paper List for Compiler Correctness

The following list outlines research endeavors focused on maintaining the correctness of modern compilers, primarily covering the following three areas:

  - [Formal Verification of Realistic Compilers](#formal-verification-of-realistic-compilers)
  - [Translation Validation for Compilers](#translation-validation-for-compilers)
  - [Compiler Fuzzing](#compiler-fuzzing)

As for other research efforts such as _test program reduction_, _test program deduplication_, _compiler debugging_, please refer to [this paper](https://dl.acm.org/doi/abs/10.1145/3363562).
You can also find some early research efforts on the testing of _"ancient"_ compilers (Ada compiler, Fortran compiler, etc) in this paper.


[view on GitHub](https://github.com/haoyang9804/Papers4CompilerCorrectness)


## Formal Verification of Realistic Compilers

+ A Formally Verified Compiler Back-end [Journal of Automated Reasoning '09]
+ Formal Verification of a Realistic Compiler [Communications of the ACM '09]
+ CompCert - A Formally Verified Optimizing Compiler [ERTS '16]
+ Closing the Gap -- The Formally Verified Optimizing Compiler CompCert [SSS '17]
+ CompCert: Practical Experience on Integrating and Qualifying a Formally Verified Optimizing Compiler [ERTS '18]

## Translation Validation for Compilers

+ Translation Validation for an Optimizing Compiler [PLDI '00]
+ Compiler-agnostic Translation Validation [ISEC '18]
+ Language-Parametric Compiler Validation with Application to LLVM [ASPLOS '21]
+ Alive2: Bounded Translation Validation for LLVM [PLDI '21]
+ End-to-End Translation Validation for the Halide Language [OOPSLA '22]

## Compiler Fuzzing

+ Practical Testing of a C99 Compiler Using Output Comparison [Software—Practice & Experience '07]
+ Volatiles are miscompiled, and what to do about it [EMSOFT '08]
+ An Automatic Testing Approach for Compiler Based on Metamorphic Testing Technique [Asia Pacific Software Engineering Conference '10]
+ Finding and understanding bugs in C compilers [PLDI '11]
+ Swarm Testing [ISSTA '12]
+ Random Testing of C Compilers Targeting Arithmetic Optimization [IPSJ Transactions on System LSI Design Methodology '12]
+ Test-Case Reduction for C Compiler Bugs [PLDI '12]
+ Fuzzing with Code Fragments [USENIX '12]
+ Will you still compile me tomorrow? static cross-version compiler validation [FSE '13]
+ Compiler Testing via a Theory of SoundOptimisations in the C11/C++11 Memory Model [PLDI '13]
+ Taming Compiler Fuzzers [PLDI '13]
+ Compiler Validation via Equivalence Modulo Inputs [PLDI '14]
+ Reinforcing Random Testing of Arithmetic Optimization of C Compilers by Scaling up Size and Number of Expression [IPSJ Transactions on System LSI Design Methodology '14]
+ Finding Deep Compiler Bugs via Guided Stochastic Program Mutation [OOPSLA '15]
+ Randomized Stress-Testing of Link-Time Optimizers [ISSTA '15]
+ Fuzzing the Rust Typechecker Using CLP (T) [ASE '15]
+ Many-core compiler fuzzing [PLDI '15]
+ Toward understanding compiler bugs in GCC and LLVM [ISSTA '16]
+ Coverage-Directed Differential Testing of JVM Implementations [PLDI '16]
+ Finding compiler bugs via live code mutation [OOPSLA '16]
+ Generating Focused Random Tests Using Directed Swarm Testing [ISSTA '16]
+ Finding and Analyzing Compiler Warning Defects [ICSE '16]
+ Practical Validation of Bytecode to Bytecode JIT Compiler Dynamic Deoptimization [The Journal of Object Technology '16]
+ RandIR: Differential Testing for Embedded Compilers [SCALA '16]
+ Metamorphic testing for (graphics) compilers [MET '16]
+ Automated Testing of Graphics Shader Compilers [OOPSLA '17]
+ CyFuzz: A Differential Testing Framework for Cyber-Physical Systems Development Environments [Conference: International Workshop on Design, Modeling, and Evaluation of Cyber Physical Systems '17] 
+ Random Testing of Compilers’ Performance Based on Mixed Static and Dynamic Code Comparison [A-TEST '18]
+ Finding missed compiler optimizations by differential testing [CC '18]
+ Automatically Finding Bugs in a Commercial Cyber-Physical System Development Tool Chain With SLforge [ICSE '18]
+ Compiler Fuzzing through Deep Learning [ISSTA '18]
+ FuzzIL: Coverage guided fuzzing for JavaScript engines [Master’s thesis, Karlsruhe Institute of Technology '18]
+ Evaluating Fuzz Testing [CCS '18] (Not Compiler Fuzzing, but the evaluation for general fuzzing.)
+ DeepFuzz: Automatic Generation of Syntax Valid C Programs for Fuzz Testing [AAAI '19]
+ Deep Differential Testing of JVM Implementations [ICSE '19]
+ History-Guided Configuration Diversification for Compiler Test-Program Generation [ASE '19]
+ CodeAlchemist: Semantics-Aware Code Generation to Find Vulnerabilities in JavaScript Engines [NDSS '19]
+ DSmith: Compiler Fuzzing through Generative Deep Learning Model with Attention [IJCNN '20]
+ Random testing for C and C++ compilers with YARPGen [OOPSLA '20]
+ Montage: A Neural Network Language Model-Guided JavaScript Fuzzer [USENIX '20]
+ Fuzzing JavaScript Engines with Aspect-preserving Mutation [S&P '20]
+ SLEMI: Equivalence Modulo Input (EMI) Based Mutation of CPS Models for Finding Compiler Bugs in Simulink [ICSE '20]
+ CUDAsmith: A Fuzzer for CUDA Compilers [COMPSAC '20]
+ SoFi: Reflection-Augmented Fuzzing for JavaScript Engines [CCS '21]
+ JEST: N+1-Version Differential Testing of Both JavaScript Engines and Specification [ICSE '21]
+ Automated conformance testing for JavaScript engines via deep compiler fuzzing [PLDI '21]
+ An Empirical Study of Optimization Bugs in GCC and LLVM [Journal of Systems and Software '21]
+ Well-typed programs can go wrong: A study of typing-related bugs in JVM compilers [OOPSLA '21]
+ A comprehensive study of deep learning compiler bugs [FSE '21]
+ An Empirical Study on Common Bugs in Deep Learning Compilers [ISSRE '21]
+ Graph-based fuzz testing for deep learning inference engines [ICSE '21]
+ Test-Case Reduction and Deduplication Almost for Free with Transformation-Based Compiler Testing [PLDI '21]
+ CsmithEdge: more effective compiler testing by handling undefined behaviour less conservatively [Empirical Software Engineering '22]
+ JIT-Picking: Differential Fuzzing of JavaScript Engines [CCS '22]
+ History-Driven Test Program Synthesis for JVM Testing [ICSE '22]
+ Compiler Testing using Template Java Programs [ASE '22]
+ Finding Typing Compiler Bugs [PLDI '22]
+ Detecting Simulink compiler bugs via controllable zombie blocks mutation [FSE '22]
+ Boosting Compiler Testing via Compiler Optimization Exploration [TOSEM '22]
+ Detecting Compiler Warning Defects Via Diversity-Guided Program Mutation [TSE '22]
+ Enriching Compiler Testing with Real Program from Bug Report [ASE '22]
+ An Empirical Study on Bugs in Python Interpreters [IEEE Transactions on Reliability '22]
+ Coverage-Guided Tensor Compiler Fuzzing with Joint IR-Pass Mutation [OOPSLA '22]
+ Metamorphic Testing of Deep Learning Compilers [POMACS '22]
+ Revisiting the Evaluation of Deep Learning-Based Compiler Testing [IJCAI '23]
+ FUZZILLI: Fuzzing for JavaScript JIT Compiler Vulnerabilities [NDSS '23]
+ FuzzJIT: Oracle-Enhanced Fuzzing for JavaScript Engine JIT Compiler [USENIX '23]
+ NNSmith: Generating Diverse and Valid Test Cases for Deep Learning Compilers [ASPLOS '23]
+ Fuzzing Deep Learning Compilers with HirGen [ISSTA '23]
+ RustSmith: Random Differential Compiler Testing for Rust [ISSTA Tool '23]
+ Vectorizing Program Ingredients for Better JVM Testing [ISSTA '23]

