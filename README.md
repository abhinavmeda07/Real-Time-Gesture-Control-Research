# Real-Time Gesture Control: Coordinate-Based Landmark Extraction vs. Pixel CNNs
**Academic Research Capstone Project | Semester 5 AI Curriculum (Topic 7)**

## Abstract
This repository contains the complete implementation, empirical evaluation, and benchmark documentation for Research Topic 7. We investigate the core research question: *"Can a lightweight landmark-based approach (e.g., MediaPipe + MLP/LSTM) outperform traditional pixel-based CNN architectures in latency (ms) and accuracy (%) for a 5-class HCI gesture system?"*

## Key Empirical Findings
| Evaluation Metric | Pipeline A (Coordinate MLP) | Pipeline B (Pixel-Based CNN) |
| :--- | :--- | :--- |
| **Test Accuracy (%)** | **98.26%** | 96.81% |
| **Inference Latency** | **0.62 ms / frame** | 8.45 ms / frame |
| **Memory Footprint** | **0.45 MB** | 52.10 MB |
| **Training Duration** | **3.4 seconds** | 48.2 seconds |

## Project Structure
- `notebooks/`: Executable Google Colab research notebooks.
- `outputs/`: High-resolution comparative plots and loss curves (`research_topic_7_plots.png`).
- `report/`: Formal IEEE conference-formatted research paper.

## Author
**Meda Abhinav**  
Department of Artificial Intelligence and Machine Learning  
GitHub: [@abhinavmeda07](https://github.com/abhinavmeda07)[cite: 1]
