| Encoding                | Logic 0                       | Logic 1                            |
| ----------------------- | ----------------------------- | ---------------------------------- |
| Manchester              | high–low sequence             | low–high sequence                  |
| Differential Manchester | Invert but return to original | Invert sequence                    |
| NRZ-L                   | goto a level (given)                  | goto another level (given)                 |
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
