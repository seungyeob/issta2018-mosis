# Test Case Prioritization for Acceptance Testing of Cyber Physical Systems: A Multi-Objective Search-Based Approach


## Contributors 
    
* Seung Yeob Shin (shin@svv.lu), SnT Centre, University of Luxembourg, Luxembourg  
* Shiva Nejati (nejati@svv.lu), SnT Centre, University of Luxembourg, Luxembourg  
* Mehrdad Sabetzadeh (sabetzadeh@svv.lu), SnT Centre, University of Luxembourg, Luxembourg  
* Lionel C. Briand (briand@svv.lu), SnT Centre, University of Luxembourg, Luxembourg  
* Frank Zimmer (frank.zimmer@ses.com), SES Networks, Luxembourg  

## Project artifacts

### Reference test suite by engineers
* ./reference_test_suite/test_specification.xlsx  
  Anonymized 7 test specifications
* ./reference_test_suite/test_suite.xlsx  
  Anonymized 242 test cases
* ./reference_test_suite/execution_time.xlsx  
  Selected time-log analysis results

### Experiment results
* ./experiments/search_results  
  Search outputs (Pareto-optimal test suites) of the following algorithms:  
    NSGAII with ReduceTestSuite (NR)  
    Random with ReduceTestSuite (RR)  
    NSGAII without ReduceTestSuite (NX)  
    Random without ReduceTestSuite (RX)  
* ./experiments/search_qualities  
  Search qualities (GD, SP, and HV) for the following comparisons:  
    NR vs. RR  
    NX vs. RX  
    NR vs. NX
* ./experiments/time_limits  
  Values of the crt function and the length of test suites obtained by NR, RR, NX, and RX algorithms for the time limits (8h, 16h, and 24h).
* ./experiments/size_limits  
  Values of the risk function of the test suites obtained by NR, RR, NX, and RX algorithms for the size limits (50, 100, and 150).
 

