# MemoryAllocationSimulator

This is a C# GUI Application that enables the user to simulate the OS Memory Allocation process based on three different methodologies:
1. First Fit
2. best Fit
3.Worst Fit


Our project is mainly devided into two parts:
  1. GUI
  2. Back-end

##1. GUI functions:
  a. parse inputs
  b. draw memory vector
  c. de-allocate a process
  d. compact
  e. reset
  
##2. Back-end functions:
  a. init-memory() // with holes and old processes based on the user input
  b. allocate_process_firt_fit(process p1)
  c. allocate_process_best_fit(process p1)
  d. allocate_process_worst_fit(process p1)
  e. de-allocate_process(p1)
  f. compact_memory()

