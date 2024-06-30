
# CPU Scheduling Algorithms Visualizer

### Overview :

The CPU Scheduling Algorithms Visualizer is a C++ based tool that showcases the internal workings of various CPU scheduling algorithms. This tool helps in understanding and visualizing how different scheduling algorithms manage processes in an operating system. The supported algorithms include:


- First-Come, First-Served (FCFS)
- Round Robin (RR)
- Shortest Process Next (SPN)
- Shortest Remaining Time (SRT)
- Highest Response Ratio Next (HRRN)
- Feedback (FB)
- Feedback with Varying Quantum (FBV)
- Aging
## Features

- Algorithm Visualization: Detailed visualization of various CPU scheduling algorithms.

- Interactive Interface: User-friendly interface to interact with and observe the scheduling process.

- Comparative Analysis: Compare the performance and efficiency of different scheduling algorithms.

- Educational Tool: Ideal for students and professionals to learn and understand CPU scheduling.

## Installation

### Prerequisites
Ensure you have the following installed on your system:

- C++ compiler (e.g., g++)
- Git


## Steps

### 1. Clone the Repository
```bash
  git clone https://github.com/Mr-Ajay-Rathod/CPUSchedulingVisualizer.git

```
    
### 2. Navigate to the Project Directory

```bash
cd CPUSchedulingVisualizer
```
### 3. Compile the Code

```bash
g++ main.cpp -o CPUSchedulingVisualizer
```
### 4. Run the Visualizer
```
bash
./CPUSchedulingVisualizer
```

## Usage
### Visualizing an Algorithm
1. #### Choose an Algorithm

- At the start of the program, you will be prompted to choose an algorithm from the list.

2. #### Input Process Details

- Enter the details of the processes (e.g., arrival time, burst time) as prompted.

3. #### Observe the Visualization

- The tool will display the scheduling process, allowing you to observe the behavior and performance of the chosen algorithm.


### Example
Here is an example of how to use the tool for visualizing the FCFS algorithm:
```
#include <iostream>
#include "CPUSchedulingVisualizer.h"

int main() {
    CPUSchedulingVisualizer visualizer;
    visualizer.chooseAlgorithm("FCFS");
    visualizer.addProcess(1, 0, 5); // Process 1, Arrival Time: 0, Burst Time: 5
    visualizer.addProcess(2, 2, 3); // Process 2, Arrival Time: 2, Burst Time: 3
    visualizer.run();
    return 0;
}

```

## Documentation
For detailed documentation and advanced usage examples, please refer to the [CPU Scheduling Algorithms Visualizer Documentation](#).

## Contributions
We welcome contributions from the community! If you have suggestions for improvements or new features, please submit an issue or a pull request.

### How to Contribute
1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes.
4. Commit your changes (git commit -am 'Add new feature').
5. Push to the branch (git push origin feature-branch).
6. Create a new Pull Request.

## License
This project is licensed under the MIT
 License. See the [LICENSE](https://github.com/Mr-Ajay-Rathod/Operating-System-Based-Tool-CPU-Scheduling-Algorithm-/blob/main/LICENSE) file for details.

## Acknowledgements
Thanks to the open-source community for their invaluable contributions and support.
Feel free to reach out if you have any questions or need further assistance!

Contact: ajayrathod.workplace@gmail.com

GitHub Repository: [CPU Scheduling Algorithms Visualizer](#)