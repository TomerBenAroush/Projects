# Hardware–Software Acceleration (HwSw)

**My Fork:** [TomerBenAroush/HwSw](https://github.com/TomerBenAroush/HwSwProject)  
**Original Repo:** [barar953/HwSw](https://github.com/barar953/HwSw)  

## 📌 Overview
This project explores hardware–software co-design techniques to accelerate Python workloads, with a focus on serialization and logging.

## 🚀 Highlights
- Benchmarked and optimized Python’s `json.dumps` and `logging` functions.
- Profiled performance using **perf** and **FlameGraph** to identify CPU bottlenecks.
- Explored hardware acceleration for:
  - **String escaping**  
  - **Float formatting**
- Compared baseline Python, optimized versions, and drop-in replacements (e.g., `orjson`).

## 🛠 Tech Stack
- Python (PyPerformance, custom benchmarks)
- Linux `perf` + FlameGraph
- Hardware–Software co-design concepts

## 📂 Structure
The full implementation and experiments are in my forked repo:  
👉 [TomerBenAroush/HwSw](https://github.com/TomerBenAroush/HwSwProject)
