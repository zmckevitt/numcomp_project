# numcomp_project

We plan to break the project up into three sections: Background, Experiments, and Analysis and use this structure for our final presentation.

## Background

Read Enzyme and Zygote papers and documentaiton to determine what is going on at the LLVM/compiler level in order to determine other benchmarks besides timing evaluations. This part of the presentation will include presenting on the overall architecture of both platforms as well as giving ideas about what data to collect during experimentation.

Enzyme: https://github.com/EnzymeAD/Enzyme.jl.git
Zygote: https://github.com/FluxML/Zygote.jl.git

## Experiments

Evaluate algorithmic differention for different rootfinding methods using Enzyme and Zygote. Diffrent methods include Halley's, Golbabai-Javidi, Newton's, Noor's, and Zhanlav's Methods. With these differentiations, collect multiple benchmarks (i.e. timing, overhead, LLVM benchmarks?) for each method's differentiation using each tool. Assume correctness of both Enzyme and Zygote. 

## Analysis

After collecting our results, we plan on comparing the effectiveness and efficiency of both Enzyme and Zygote for each type of rootfinding algorithm.
