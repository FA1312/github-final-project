# GitHub Final Project

## Description
A simple calculator that computes **Simple Interest** based on the given principal amount, annual rate of interest, and time period in years.

## Formula
\[
\text{Simple Interest} = P \times T \times R
\]
Where:
- **P** = Principal amount  
- **T** = Time period in years  
- **R** = Annual rate of interest (in decimal or percentage format)  

## Input
- `p`: Principal amount  
- `t`: Time period in years  
- `r`: Annual rate of interest  

## Output
- **Simple Interest** calculated as `p * t * r`

## Example Usage
```python
# Example calculation
p = 1000  # Principal
t = 5     # Time period in years
r = 0.05  # Annual rate of interest (5%)

simple_interest = p * t * r
print(f"Simple Interest: {simple_interest}")
