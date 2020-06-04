# NuTA
NuSMV Transition Analyzer
NuTa is a tool that analyzes NuSVM files. It is dedicated to analyze modules in contrainst-based style and detects the presence of Vacuous Rules, Total transitions and Inconsistent Rules.

# Use of the tool
The tool call is as follows: 
> NuTA [NuSMV file]

The file name (or path) must be without spaces or quoted. 

# File Requirements
The file must comply with the following conditions in order for the tool to work properly: 
1. It must contain at least one module (main). 
2. All modules must be written in contrain-based style. 
3. Each transition rule must be on a single line. 
4. Parentheses must be placed as follows in each of the rules: 
> (([formula]) -> ([formula])) &

> (...)

> (([formula]) -> ([formula])) ;

