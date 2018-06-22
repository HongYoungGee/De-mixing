# De-mixing algorithm

This code is a paper experiment submitted to te [ACM AsiaCCS'18 BCC Workshop](https://dl.acm.org/citation.cfm?id=3205234).
It is a function that matches input and output of mixing service.


## Generate_test_data
Input : Helix mixing service data obtained by using the Chainalysis tool.

I put 'Chainalysis_Helix_Mixer_input_June' as sample data.
Result files are created according to the set parameters.
Parameters can be set in main.

## De-mixing
Input : Inputs are output files obtained using Generate_test_data.

When the code is executed, the input and output are matched and print.

## Notice
The set_time function did not consider the date concept.
(The results are not affected at all.)
