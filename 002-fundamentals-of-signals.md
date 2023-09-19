## Components of Signals
* __Amplitude__ - The amplitude of a signal is its strength or loudness.
* __Frequency__ - The frequency of a signal is the number of times it repeats itself in a given amount of time.
* __Phase__ - The phase of a signal is the position of its waveform relative to a reference point.

## Advantages of Digital signals VS Analog
1. Reliability -  Less susceptible to noise than analog signals.
2. Robustness - Easier to store and transmit than analog signals.
3. Efficiency - Representable using a smaller number of bits than analog signals.
4. Security - Encryptable.

## Encoding
* __Encoding__ or __line encoding__ is a method of converting a bit stream into a predefined
__code__.
| Encoding                | Logic 0                       | Logic 1                            |
| ----------------------- | ----------------------------- | ---------------------------------- |
| Manchester              | high–low sequence             | low–high sequence                  |
| Differential Manchester | Invert but return to original | Invert sequence                    |
| NRZ-L                   | goto a level (given)          | goto another level (given)         |
| NRZ-I                   | stay                          | change direction                   |
| Bipolar AMI             | goto neutral                  | invert the direction of previous 1 |

<!--     ┐  
    └
    ┌ 
    ┙  -->

## Keying
1. __Amplitude Shift Keying | ASK__ - A different amplitude is used to represent a value.
2. __Frequency Shift Keying | FSK__ - Frequency of signal is changed
3. __Phase Shift Keying | PSK__ - Angle of signal phase is changed


## Modulation
1. Pulse Code Modulation  | PCM - Conversion of analog signal to digital using sampling.
2. Delta Modulation | DM - PCM but record only difference of previous sample

## Charset
| Info                  | Extended Binary-Coded Decimal Interchange Code | Unicode            |
| --------------------- | ---------------------------------------------- | ------------------ |
| Char Count            | 256                                            | 1.1M               |
| Creator/s             | IBM                                            | Unicode Consortium |
| Status                | Old                                            | Modern             |
| Used in               | IBM System 360                                 | Major OSes         |
| Initial release       | 1963-1964                                      | October 1991       |
| Codepoint Requirement | 8 bits                                         | 16 bits            |

## Terms
* __Data__: Collection of facts.
* __Signal__: A codified message. A physical quantity that conveys information.
* __Specturm__: Frequency Distribution of a signal.
* __Modulation__: The process of varying one or more properties of a carrier signal in accordance with a message signal. The message signal can be either analog or digital.
* __Carrier signal__: A sinusoidal signal that is used to carry the message signal. The carrier signal is typically much higher in frequency than the message signal.
* __Modulating signal__: The signal that is being encoded. The modulating signal can be either analog or digital.
* __Demodulation__: Process of recovering the message signal from the modulated signal.
* __Bandwidth__: Range of frequencies that a signal occupies. The bandwidth of a modulated signal is typically wider than the bandwidth of the modulating signal.
* __Throughput__: Measure of the transfer of bits across the media over a given period of time.
* __Signal-to-noise ratio | SNR__: The ratio of the power of the signal to the power of the noise. A higher SNR means that the signal is less likely to be corrupted by noise.
* __Bit rate__: Number of bits transmitted per second. The bit rate is determined by the modulation technique used.
* __Symbol rate__: Number of symbols transmitted per second. The symbol rate is typically higher than the bit rate.
* __Error rate__: The probability of a bit error. The error rate is determined by the modulation technique used and the SNR.
* __Sampling rate__: Number of times/second an analog signal is sampled.
