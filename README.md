# Current-Noise-Reduction-Matlab

This MATLAB project tackles the challenge of noise reduction in current signals within power electronics systems. By comparing two powerful techniques – polynomial fitting (`polyfit`) and Variational Mode Decomposition (VMD) – it aims to find the best way to accurately estimate current slopes even when the signals are noisy.

**Why is this important?**

Accurate current measurement is essential for the efficient and reliable operation of power electronics systems. But noise from IGBT switching can mess up these measurements. This project explores smart ways to clean up those noisy signals and get accurate results.

**What's inside?**

* **Two noise reduction methods:**  We put `polyfit` and VMD head-to-head to see which one performs better.
* **Real-world data:**  The analysis uses 200 real current datasets from an IGBT-based power converter.
* **Statistical analysis:**  We dive deep into the results with MAE, RMSE, and R^2 to compare the accuracy of each method.

**Want to learn more?**

Check out the code and results to see how we tackled this challenge and which method came out on top. You might even find some useful techniques for your own power electronics projects!

## Usage

1. Make sure you have MATLAB with the Signal Processing and VMD toolboxes.
2. Clone the repository.
3. Run `analyze_currents.m` and `statistical_analysis.m`.

## License

MIT License
