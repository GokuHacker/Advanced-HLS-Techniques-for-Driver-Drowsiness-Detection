Advanced HLS Techniques for Driver Drowsiness Detection
This project focuses on optimizing a Convolutional Neural Network (CNN) model for driver drowsiness detection by leveraging advanced High-Level Synthesis (HLS) techniques. The goal is to enhance the performance and resource utilization of the model, making it suitable for real-time safety-critical applications.

Project Overview
Driver drowsiness detection is crucial for preventing accidents and ensuring road safety. In this project, we refactor the CNN model code to make it error-free and compatible with HLS. By doing so, we enable efficient hardware implementation, which is critical for deploying the model in real-world environments.

Optimization Techniques
To achieve significant improvements in performance and resource efficiency, we applied the following HLS optimization techniques:

Loop Tiling: Breaks down loops into smaller chunks to improve data locality and reduce memory access latency.
Loop Unrolling: Expands loop iterations to execute multiple iterations in parallel, reducing the overall loop execution time.
Array Partitioning: Splits arrays into smaller sub-arrays to allow parallel access, improving memory bandwidth utilization.
Loop Merging: Combines multiple loops into a single loop to minimize loop overhead and increase efficiency.
Performance Improvements
The optimizations led to notable reductions in latency and overall execution time:

HLS4ML Report:

Minimum Latency: 88,483,224 clocks
Clock Period: 4.3 ns
Total Execution Time: 38,507,899,084.8 ns
Optimized Model:

Minimum Latency: 15,390,244 clocks
Clock Period: 42.905 ns
Total Execution Time: 66,031,841,882 ns
Despite the longer clock period in the optimized model, the reduced latency results in a more efficient execution, making the model more suitable for real-time applications.

Conclusion
This project demonstrates the effectiveness of applying advanced HLS techniques to optimize CNN models for hardware implementation. The resulting improvements in performance and resource utilization make this approach viable for deploying driver drowsiness detection systems in safety-critical environments.
