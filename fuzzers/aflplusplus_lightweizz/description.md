# aflplusplus

AFL++ fuzzer instance that has the following config active for all benchmarks:
  - PCGUARD instrumentation 
  - cmplog feature
  - dict2file feature
  - "explore" power schedule
  - persistent mode + shared memory test cases

In addition, it uses the new experimental fmtrev mutator inspired by weizz.

Repository: [https://github.com/AFLplusplus/AFLplusplus/](https://github.com/AFLplusplus/AFLplusplus/)

[builder.Dockerfile](builder.Dockerfile)
[fuzzer.py](fuzzer.py)
[runner.Dockerfile](runner.Dockerfile)
