# HKUST-OWL-Co-simulation-Platform
Supervised by Professor C. Patrick Yue, We developed this co-simulation platform for high frequency RF and mm-Wave transceiver systems dealing with complex modulated signals
Traditionally, a continuous-wave (CW) signal is used to evaluate and simulate RF and millimeter-wave (mm-wave) circuits during the design procedure, while fabricated circuits are measured by modulated signals in the test phase, because complex modulated signals are used in reality. It is almost impossible to use a CW signal to predict system performance, such as error vector magnitude (EVM), bit error rate (BER), etc., of RF and mm-wave circuits when dealing with complex modulated signals. This paper presents a mixed-mode transistor-level simulation platform to evaluate the system performances of a wireless communication transceiver or its sub-circuits. This simulation platform is based on Matlab, Advanced Design System (ADS), and Cadence simulators to link the baseband digital signals and RF frond-end. An orthogonal frequency division multiplex (OFDM) modem is implemented in Matlab for the system performance check. Each sub-carrier of the OFDM signal can adopt quadrature amplitude modulation (QAM). The modulated baseband signal from Matlab is dynamically fed into ADS, which includes PCB level components or mm-wave transceiver integrated circuits (IC) for simulation. The sub-block circuits of the transceiver system can be implemented using ADS and Cadence simulators. After system-level circuit simulation in ADS, the output signal is dynamically delivered to Matlab for demodulation and further processing. 
