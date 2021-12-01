# Test Plan
## High level test plan

|Test ID | Description | Exp I/P | Exp O/P | Actual Out | Type of Test
|--------|-------------|---------|---------|------------|-------------
| HLT_01 | Power ON | Power | Display ON | SUCCESS | Requirement Based 
| HLT_02 | User Input | Input Value | Return Output to the User | SUCCESS | Scenario Based            
| HLT_03 | Return Output from Input | Inputed Value by User | Shows Output in Display | SUCCESS | Requirement Based

## Low level test plan

|Test ID | Description | Exp I/P | Exp O/P | Actual Out | Type of Test
|--------|-------------|---------|---------|------------|-------------
| LLR_01 | '+' operation | (40, 50) | 90 | 90 | Requirement Based        
| LLR_02 | '-' operation | (70, 20) | 50 | 50 | Requirement Based        
| LLR_03 | '*' operation | (5, 5) | 25 | 25 | Requirement Based         
| LLR_04 | '/' operation | (24, 2) | 12 | 12 | Requirement Based
