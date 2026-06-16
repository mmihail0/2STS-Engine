## Pretext
A semi-Thue system, at its core, is a string rewriting system from a finite alphabet. Since string rewriting systems are Turing complete, then so must be this system. Using Python, I will create a semi-Thue system, and then use that system to create another semi-Thue system. This will create 3 "layers" of complexity (the code doesn't actually work this way but for the sake of visualisation lets assume it does). Instead of wholly relying on Python, I will be employing the 2 systems I defined such that the 3 "layers" are interdependent.

## Structure
**VERY UNFINISHED, basics are provided**  
Layer 0 = Python, handles flow of execution, loops, etc  
Layer 1 = STS created from Python, holds and transforms the world state; string transformation  
Layer 2 = STS created from STS (Layer 1), handles logic, comparisons, rules, etc  

The layers interact in the following structure  
Layer 0 -> Layer 2 -> Layer 1
