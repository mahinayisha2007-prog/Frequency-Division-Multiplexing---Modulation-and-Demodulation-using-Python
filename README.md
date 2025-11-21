# Frequency-Division-Multiplexing---Modulation-and-Demodulation-using-Python

__Aim__:

To generate an FDM signal by multiplexing multiple baseband message signals on different carrier frequencies, transmit (sum) them, optionally add channel noise, then recover each message by bandpass filtering and coherent demodulation in Python (Google Colab). Observe time & frequency domain signals and measure recovery quality.


__Apparatus Required__:

Google Colab (or any Python environment)

Python libraries: numpy, matplotlib, scipy (scipy.signal)


__Theory__:

FDM places different message signals in separate, non-overlapping frequency bands by modulating each message onto a distinct carrier frequency. The multiplexed signal is the sum of all modulated channels. At the receiver, bandpass filters (or tuned filters) isolate each channel; then each isolated carrier is demodulated (coherently multiplied by a synchronized carrier) and low-pass filtered to recover the original baseband.

__Procedure__:

1 — Imports and parameters

2 — Create message signals and carriers

3 — Modulate each message (standard AM DSB-SC) and form FDM signal

4 — Frequency domain (spectrum) of FDM signal

5 — (Optional) Add AWGN noise to FDM signal

6 — Receiver: isolate each channel with bandpass filter

7 — Demodulate each isolated channel (coherent) and low-pass filter to recover baseband

__Output_:

<img width="1280" height="1280" alt="517228471-082751ce-785e-4228-812d-1073d8755546" src="https://github.com/user-attachments/assets/34c81932-50cf-4abd-99f5-742d12756e33" />
<img width="1022" height="1280" alt="517228550-61d31403-2fd4-463c-a206-fdaf1da7927c" src="https://github.com/user-attachments/assets/5bdd4e2a-7990-432b-8083-46fababf43a0" />
<img width="1280" height="595" alt="517228640-3eaf3f59-fdc8-4a41-947c-7fc88ca2a4e3" src="https://github.com/user-attachments/assets/1175841f-e66d-4f61-a2ab-546fbe793a5b" />


__Result__:

Thus the FDM signal by multiplexing multiple baseband message signals on different carrier frequencies, transmit (sum) them, optionally add channel noise, then recover each message by bandpass filtering and coherent demodulation in Python (Google Colab) was successfully executed and the output is verified.
