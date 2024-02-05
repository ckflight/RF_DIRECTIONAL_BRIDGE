# RF_DIRECTIONAL_BRIDGE

300 KHz to 13.5 GHz Directional Bridge with 16 dB coupling and 1dB Insertion Loss

The source of design is: https://ieeexplore.ieee.org/document/7345756

IEEE pdf file can be seen as ieee_paper.pdf

R1^2 = R2 x Zo 

S21 = R1 / (Zo + R1)

S32 = R1 / (R2 + R1)

For 16dB coupling and 1dB insertion loss calculated values are:

R1 = 50 Ohm (transmission line impedance), R2 = 230 Ohm, Zo = 6.17 Ohm (Connect 4 parallel 24-25 Ohm)

As a balun transformer use RG405 Coax cable with 77, 43 and T46 toroids on it.

![Untitled](https://user-images.githubusercontent.com/61315249/82236528-e35f9100-993c-11ea-8cd1-2eb6c83bc6b7.png)

![Untitled](https://user-images.githubusercontent.com/61315249/82236989-a1831a80-993d-11ea-985f-b71b47b31147.png)

![coupling](https://user-images.githubusercontent.com/61315249/82422966-d1d8cf00-9a8b-11ea-9405-b840bdf3217c.png)

![directivity](https://user-images.githubusercontent.com/61315249/82422969-d2716580-9a8b-11ea-84a5-4aa10b4e602f.png)

# VNA Measurements:

S-parameters with a commercial VNA up to 10 GHz. Coupler was measured as a two port with third port terminated with a high quality termination from the VNA calibration kit.

![directional_coupler](https://github.com/ckflight/RF_DIRECTIONAL_BRIDGE/assets/61315249/c36a93ea-0fbc-4b53-89ea-8a578bf6d872)

