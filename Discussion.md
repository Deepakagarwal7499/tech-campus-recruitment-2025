## Solutions Considered
1. **Load Entire File into Memory**: Not feasible for 1 TB file.
2. **Stream Processing**: Efficient and memory-friendly.

## Final Solution Summary
The final solution uses a streaming approach with line-by-line processing to filter logs based on the specified date.

## Steps to Run
1. Compile the code using a C++ compiler:
   ```bash
   g++ -o extract_logs src/extract_logs.cpp
