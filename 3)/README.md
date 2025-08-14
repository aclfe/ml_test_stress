# Project Problem and Solution

## Proof of run:
You can see the cached ran python files in here:
`https://github.com/aclfe/proj1/`
`links`

## Problem Encountered
- CUDA compatibility issues with PyTorch installation
- GPU version of PyTorch was not working properly on the system
- Standard pip install commands were failing for GPU version

## Solution Implementation
1. Used CPU version of PyTorch instead
2. Installation was done using specific URLs from https://download.pytorch.org
3. Made a new conda enviornment for  
### Additional Notes
- This CPU version works as a viable alternative when CUDA compatibility issues arise
- Performance may be slower compared to GPU version but ensures stability
- Solution is particularly useful for development and testing environments

## References
- [PyTorch Installation Guide](https://pytorch.org/get-started/locally/)