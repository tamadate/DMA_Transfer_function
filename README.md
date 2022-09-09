# Transfer_function_calculater
This is simple calculater for transfer function of Differential Mobility Analyzer (DMA).  

# DEMO
![Figure_1-3](https://user-images.githubusercontent.com/75816343/108619820-beb7bd00-746a-11eb-8c36-09a9662c243c.png)

# Features
 This calculater is easy to use and simple. I supose that this is useful to understand the DMA transfer function.

# Requirement
* Python 2.7 (Perhaps, it can move on Python 3 series, but it haven't tried yet)
* Numpy
* Matplotlib
* Tkinter
* Scipy

# Installation
No

# Usage
1. When you perform "python DMA_calculater.py", a input window will open.
2. You need to fill out DMA parameters (Rin, Rout, Vmin, Vout, Qsh and Qa), specific particle diameter and output file name. You can use Nano DMA and Long DMA parameters as a sample parameter by pushing the each named button.
3. By pushing "Total transfer function", 4 relationships based on the input parameters can be obtained (Particle diameter-Voltage, Peak hight-Particle diameter, NFWHM-Particle diameter and Transfer function-Zp/ZP*, see #DEMO).
4. At the same time as No.3, output file will be generated which lines mean voltage, particle diameter, electrical mobility, sigma (a parameter of transfer function), peak height and NFWHM.

# Note

## Author
* Dr. Tomoya Tamadate
* [LinkedIn](https://www.linkedin.com/in/tomoya-tamadate-953673142/)/[ResearchGate](https://www.researchgate.net/profile/Tomoya-Tamadate)/[Google Scholar](https://scholar.google.com/citations?user=XXSOgXwAAAAJ&hl=ja)
* University of Minnesota / Kanazawa University
* tamalab0109[at]gmail.com
