# Validation Guide Specification

## Folders and Structure 

The validation guides use the rule ID as their filename. 

## Guide Template

```
# Rule: Title
Sigma rule ID : {id of the rule}
## Author
  author or contributor of this file
## Change History
  - yyyy-mm-dd what is done
## Required Log Sources
   What is the source to collect
## Required Audit Policy / Config
  What is need to enable the source
## Description
  How to trigger the rule
## Code
  Code snippet or complete program code
## Example: 
  Expected Event
  link to a json dataset or a evtx
  link to the atomic-red-team test
  - https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1003.001/T1003.001.md#atomic-test-7---lsass-read-with-pypykatz
```
