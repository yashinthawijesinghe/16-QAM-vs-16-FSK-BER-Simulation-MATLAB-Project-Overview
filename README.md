16-QAM vs 16-FSK BER Simulation (MATLAB)

 Project Overview

This project presents a MATLAB simulation that compares the **Bit Error Rate (BER)** performance of **16-QAM (Quadrature Amplitude Modulation)** and **16-FSK (Frequency Shift Keying)** over an **Additive White Gaussian Noise (AWGN) channel**.

The simulation evaluates how both modulation techniques perform under different **Eb/N0 values**, and visualizes the results using **constellation diagrams**, **signal plots**, and **BER performance curves**.



## Objectives

The main objectives of this project are:

* Generate random binary input data
* Perform **16-QAM modulation**
* Perform **16-FSK modulation**
* Transmit signals through an **AWGN channel**
* Demodulate the received signals
* Calculate **Bit Error Rate (BER)**
* Compare the performance of both modulation techniques

---

##  Concepts Used

This project is based on key **Digital Communication** concepts:

* Digital Modulation Techniques
* Quadrature Amplitude Modulation (QAM)
* Frequency Shift Keying (FSK)
* Additive White Gaussian Noise (AWGN)
* Constellation Diagrams
* Bit Error Rate (BER) Analysis
* Signal Processing using MATLAB

---

##  Simulation Parameters

| Parameter            | Value     |
| -------------------- | --------- |
| Modulation Order (M) | 16        |
| Bits per Symbol      | 4         |
| Number of Bits       | 100000    |
| Eb/N0 Range          | 0 – 20 dB |
| Sampling Frequency   | 100 Hz    |
| Samples per Symbol   | 100       |
| Channel              | AWGN      |

---

##  Simulation Output

The MATLAB simulation generates the following results:

### 1 Input Binary Signal

Shows the randomly generated binary sequence used for transmission.

### 2️ Transmitted Signals

* 16-QAM transmitted signal
* 16-FSK transmitted signal

### 3️ Constellation Diagram

The constellation diagram visualizes the symbol mapping of the **16-QAM modulation scheme**.

### 4️ BER Performance Comparison

A **BER vs Eb/N0 plot** comparing:

* 16-QAM
* 16-FSK

This helps evaluate which modulation technique performs better under noisy conditions.

### 5️ Noisy Constellation

The received **16-QAM constellation at 10 dB Eb/N0** showing the effect of noise on symbol detection.

---

##  Expected Observations

* **16-QAM** generally achieves **better spectral efficiency**
* **16-FSK** can be **more robust in noisy environments**
* As **Eb/N0 increases**, the **Bit Error Rate decreases**

---

## Requirements

To run this project, you need:

* **MATLAB**
* **MATLAB Communications Toolbox**

---

##  How to Run the Simulation

1. Clone this repository

```
git clone https://github.com/your-username/16-QAM-vs-16-FSK-BER-Simulation-MATLAB-Project-Overview.git
```

2. Open MATLAB

3. Run the script

```
qam_fsk_ber_simulation.m
```

4. MATLAB will generate:

* Signal plots
* Constellation diagrams
* BER comparison graph

---

##  Repository Structure

```
16-QAM-vs-16-FSK-BER-Simulation-MATLAB-Project-Overview
│
├── qam_fsk_ber_simulation.m
├── README.md
└── results (optional)
    ├── BER_plot.png
    ├── constellation.png
    └── signals.png
```

---

##  Author

**Yashintha Wijeshinghe**

Electrical & Information Engineering Undergraduate

---

##  License

This project is created for **educational and academic purposes**.
