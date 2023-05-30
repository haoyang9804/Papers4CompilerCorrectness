# An Ever-growing Paper List for Compiler Correctness

[View on GitHub](https://github.com/haoyang9804/Papers4CompilerCorrectness)

## Target Compiler

### GCC/LLVM

+ Practical Testing of a C99 Compiler Using Output Comparison [2007]
+ An Automatic Testing Approach for Compiler Based on Metamorphic Testing Technique [Asia Pacific Software Engineering Conference '10]
+ Finding and understanding bugs in C compilers [PLDI '11]
+ Swarm Testing [ISSTA '12]
+ Random Testing of C Compilers Targeting Arithmetic Optimization [IPSJ Transactions on System LSI Design Methodology 2012]
+ Test-Case Reduction for C Compiler Bugs [PLDI 2012]
+ Compiler Testing via a Theory of SoundOptimisations in the C11/C++11 Memory Model [PLDI '13]
+ Taming Compiler Fuzzers [PLDI '13]
+ Compiler Validation via Equivalence Modulo Inputs [PLDI '14]
+ Reinforcing Random Testing of Arithmetic Optimization of C Compilers by Scaling up Size and Number of Expression [IPSJ Transactions on System LSI Design Methodology '14]
+ Finding Deep Compiler Bugs via Guided Stochastic Program Mutation [OOPSLA '15]
+ Randomized Stress-Testing of Link-Time Optimizers [ISSTA '15]
+ Toward understanding compiler bugs in GCC and LLVM [ISSTA '16]
+ Finding compiler bugs via live code mutation [OOPSLA '16]
+ Generating Focused Random Tests Using Directed Swarm Testing [ISSTA '16]
+ Finding and Analyzing Compiler Warning Defects [ICSE '16]
+ Random Testing of Compilers’ Performance Based on Mixed Static and Dynamic Code Comparison [A-TEST '18]
+ DeepFuzz: Automatic Generation of Syntax Valid C Programs for Fuzz Testing [AAAI '19]
+ History-Guided Configuration Diversification for Compiler Test-Program Generation [ASE '19]
+ DSmith: Compiler Fuzzing through Generative Deep Learning Model with Attention [IJCNN '20]
+ Random testing for C and C++ compilers with YARPGen [OOPSLA '20]
+ An Empirical Study of Optimization Bugs in GCC and LLVM [Journal of Systems and Software '21]
+ CsmithEdge: more effective compiler testing by handling undefined behaviour less conservatively [Empirical Software Engineering '22]
+ Boosting Compiler Testing via Compiler Optimization Exploration [TOSEM '22]
+ Enriching Compiler Testing with Real Program from Bug Report
[ASE '22]

### JVM (JVM implementations & Compilers for JVM langauges)

+ Coverage-Directed Differential Testing of JVM Implementations [PLDI '16]
+ Deep Differential Testing of JVM Implementations [ICSE '19]
+ Well-typed programs can go wrong: A study of typing-related bugs in JVM compilers [OOPSLA '21]
+ History-Driven Test Program Synthesis for JVM Testing [ICSE '22]
+ Compiler Testing using Template Java Programs [ASE '22]

### Python Interpreters

+ An Empirical Study on Bugs in Python Interpreters [IEEE Transactions on Reliability '22]

### JavaScript Interpreter

+ Fuzzing with Code Fragments [USENIX '12]

### Deep Learning Compilers

+ A comprehensive study of deep learning compiler bugs [FSE '21]
+ An Empirical Study on Common Bugs in Deep Learning Compilers [ISSRE '21]
+ NNSmith: Generating Diverse and Valid Test Cases for Deep Learning Compilers [ASPLOS '23]
+ Fuzzing Deep Learning Compilers with HirGen [ISSTA '23]

### Parallel Programming Language Compilers

+ Many-core compiler fuzzing [PLDI '15]
+ Compiler Fuzzing through Deep Learning [ISSTA '18]
+ CUDAsmith: A Fuzzer for CUDA Compilers [COMPSAC '20]

### Graphics Shader Compiler

+ Automated Testing of Graphics Shader Compilers [OOPSLA '17]
+ Test-Case Reduction and Deduplication Almost for Free with Transformation-Based Compiler Testing [PLDI '21]

### Simulink Compiler

+ CyFuzz: A Differential Testing Framework for Cyber-Physical Systems Development Environments [2017] 
+ Automatically Finding Bugs in a Commercial Cyber-Physical System Development Tool Chain With SLforge [ICSE '18]
+ SLEMI:Equivalence Modulo Input (EMI) Based Mutation of CPS
Models for Finding Compiler Bugs in Simulink [ICSE '20]
+ Detecting Simulink compiler bugs via controllable zombie blocks mutation [FSE '22]

### Compiler Component

+ Randomized Stress-Testing of Link-Time Optimizers [ISSTA '15] -> Optimizer of GCC/LLVM
+ Practical Validation of Bytecode to Bytecode JIT Compiler Dynamic Deoptimization [2016] -> Dynamic Deoptimization of JIT compilers
+ RandIR: Differential Testing for Embedded Compilers [SCALA '16] -> Embedded DSL Compiler for Scala
+ Fuzzing Deep Learning Compilers with HirGen [ISSTA '23] -> High-level optimization of TVM


## Survey

+ Toward understanding compiler bugs in GCC and LLVM [ISSTA '16]
+ A Survey of Compiler Testing [ACM Computing Surveys2019]
+ Well-typed programs can go wrong: A study of typing-related bugs in JVM compilers [OOPSLA '21]
+ A comprehensive study of deep learning compiler bugs [FSE '21]
+ An Empirical Study on Common Bugs in Deep Learning Compilers [ISSRE '21]
+ An Empirical Study of Optimization Bugs in GCC and LLVM [Journal of Systems and Software '21]
+ An Empirical Study on Bugs in Python Interpreters [IEEE Transactions on Reliability '22]

## Program Construction

### Generation-based

+ Finding and understanding bugs in C compilers [PLDI '11]
+ Random Testing of C Compilers Targeting Arithmetic Optimization [IPSJ Transactions on System LSI Design Methodology '12]
+ Fuzzing with Code Fragments [USENIX '12]
+ Compiler Testing via a Theory of SoundOptimisations in the C11/C++11 Memory Model [PLDI '13]
+ Many-core compiler fuzzing [PLDI '15]
+ Automatically Finding Bugs in a Commercial Cyber-Physical System Development Tool Chain With SLforge [ICSE '18]
+ Random testing for C and C++ compilers with YARPGen [OOPSLA '20]
+ CUDAsmith: A Fuzzer for CUDA Compilers [COMPSAC '20]
+ CsmithEdge: more effective compiler testing by handling undefined behaviour less conservatively [Empirical Software Engineering '22]
+ NNSmith: Generating Diverse and Valid Test Cases for Deep Learning Compilers [ASPLOS '23]
+ Fuzzing Deep Learning Compilers with HirGen [ISSTA '23]

### Generation Optimization

+ Swarm Testing [ISSTA '12]
+ Generating Focused Random Tests Using Directed Swarm Testing [ISSTA '16]
+ History-Guided Configuration Diversification for Compiler Test-Program Generation [ASE '19]
+ Boosting Compiler Testing via Compiler Optimization Exploration [TOSEM '22]

### Transformation-based

#### Semantics-preserving

+ Compiler Validation via Equivalence Modulo Inputs [PLDI '14]
+ Finding Deep Compiler Bugs via Guided Stochastic Program Mutation [OOPSLA '15]
+ Many-core compiler fuzzing [PLDI '15]
+ Finding compiler bugs via live code mutation [OOPSLA '16]
+ Automated Testing of Graphics Shader Compilers [OOPSLA '17]
+ SLEMI:Equivalence Modulo Input (EMI) Based Mutation of CPS
Models for Finding Compiler Bugs in Simulink [ICSE '20]
+ CUDAsmith: A Fuzzer for CUDA Compilers [COMPSAC '20]
+ Test-Case Reduction and Deduplication Almost for Free with Transformation-Based Compiler Testing [PLDI '21]
+ Detecting Simulink compiler bugs via controllable zombie blocks mutation [FSE '22]
+ Fuzzing Deep Learning Compilers with HirGen [ISSTA '23]

#### Non-semantics-preserving

+ Fuzzing with Code Fragments [USENIX '12]
+ Reinforcing Random Testing of Arithmetic Optimization of C Compilers by Scaling up Size and Number of Expression [IPSJ Transactions on System LSI Design Methodology '14]
+ Coverage-Directed Differential Testing of JVM Implementations [PLDI '16]
+ Automated Testing of Graphics Shader Compilers [OOPSLA '17]
+ History-Driven Test Program Synthesis for JVM Testing [ICSE '22]

### Deep-learning-based

+ Compiler Fuzzing through Deep Learning [ISSTA '18]
+ DeepFuzz: Automatic Generation of Syntax Valid C Programs for Fuzz Testing [AAAI '19]
+ DSmith: Compiler Fuzzing through Generative Deep Learning Model with Attention [IJCNN '20]




## Testing Acceleration 

### Test Program Reduction

+ Yesterday, My Program Worked. Today, It Does Not. Why? [ACM SIGSOFT Software Engineering Notes '99]
+ Simplifying and Isolating Failure-Inducing Input [TSE '02]
+ Test-Case Reduction for C Compiler Bugs [PLDI '12]
+ Cause Reduction: Delta Debugging, Even without Bugs [Software Testing, Verification & Reliability '16]
+ Automatic Test Case Reduction for OpenCL [IWOCL '16]
+ Probabilistic Delta Debugging [FSE '21]
+ Test-Case Reduction and Deduplication Almost for Free with Transformation-Based Compiler Testing [PLDI '21]

## Test Oracle

### Differential Testing

+ Practical Testing of a C99 Compiler Using Output Comparison [2007]
+ Finding and understanding bugs in C compilers [PLDI '11]
+ Will you still compile me tomorrow? static cross-version compiler validation [FSE '13]
+ Compiler Testing via a Theory of Sound Optimisations in the C11/C++11 Memory Model [PLDI '13]
+ Randomized Stress-Testing of Link-Time Optimizers [ISSTA '15]
+ Many-core compiler fuzzing [PLDI '15]
+ Practical Validation of Bytecode to Bytecode JIT Compiler Dynamic Deoptimization [The Journal of Object Technology 2016]
+ RandIR: Differential Testing for Embedded Compilers [SCALA '16]
+ Finding and Analyzing Compiler Warning Defects [ICSE '16]
+ CyFuzz: A Differential Testing Framework for Cyber-Physical Systems Development Environments [2017] 
+ SLEMI:Equivalence Modulo Input (EMI) Based Mutation of CPS
Models for Finding Compiler Bugs in Simulink [ICSE '20]
+ Random Testing of Compilers’ Performance Based on Mixed Static and Dynamic Code Comparison [A-TEST '18]
+ Random testing for C and C++ compilers with YARPGen [OOPSLA '20]
+ CUDAsmith: A Fuzzer for CUDA Compilers [COMPSAC '20]
+ CsmithEdge: more effective compiler testing by handling undefined behaviour less conservatively [Empirical Software Engineering '22]
+ Boosting Compiler Testing via Compiler Optimization Exploration [TOSEM '22]
+ Enriching Compiler Testing with Real Program from Bug Report
[ASE '22]
+ Detecting Simulink compiler bugs via controllable zombie blocks mutation [FSE '22]
+ NNSmith: Generating Diverse and Valid Test Cases for Deep Learning Compilers [ASPLOS '23]
+ Fuzzing Deep Learning Compilers with HirGen [ISSTA '23]

### Metamorphic Testing

+ Compiler Validation via Equivalence Modulo Inputs [PLDI '14]
+ Finding Deep Compiler Bugs via Guided Stochastic Program Mutation [OOPSLA '15]
+ Many-core compiler fuzzing [PLDI '15]
+ Finding compiler bugs via live code mutation [OOPSLA '16]
+ Automated Testing of Graphics Shader Compilers [OOPSLA '17]
+ SLEMI:Equivalence Modulo Input (EMI) Based Mutation of CPS
Models for Finding Compiler Bugs in Simulink [ICSE '20]
+ CUDAsmith: A Fuzzer for CUDA Compilers [COMPSAC '20]
+ An Automatic Testing Approach for Compiler Based on Metamorphic Testing Technique [Asia Pacific Software Engineering Conference 2010]
+ Detecting Simulink compiler bugs via controllable zombie blocks mutation [FSE '22]
+ Fuzzing Deep Learning Compilers with HirGen [ISSTA '23]

## Test Program Prioritization

+ Taming Compiler Fuzzers [PLDI '13]
