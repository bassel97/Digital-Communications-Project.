# Raised Cosine bonus

# List of required modulation schemes
- **[BPSK](#BPSK-Binary-Phase-Shift-Keying)**
- **[QPSK](#QPSK-Quadrature-phase-shift-keying)**
- **[FSK](#FSK-Frequency-shift-keying)**
- **[QAM16](#QAM16-Quadrature-amplitude-modulation)**
- **[QAM64](#QAM64-Quadrature-amplitude-modulation)**

# General Scheme
    just different block for each scheme
![General scheme](RaisedCosine.PNG)

# BPSK Binary Phase Shift Keying
## After Modulator
![After Modulator](BPSK_RC/AfterModulator.png)
## After Modulator
![Before Channel](BPSK_RC/BeforeChannel.png)
## After Reciever
![After Reciever](BPSK_RC/AfterReciever.png)



# QPSK Quadrature phase shift keying

## After Modulator
![After Modulator](QPSK/AfterModulator.png)
## After Modulator
![Before Channel](QPSK/BeforeChannel.png)
## After Reciever
![After Reciever](QPSK/AfterReciever.png)

# FSK Frequency shift keying

## After Modulator
![After Modulator](FSK/AfterModulator.png)
## After Modulator
![Before Channel](FSK/BeforeChannel.png)
## After Reciever
![After Reciever](FSK/AfterReciever.png)


# QAM16 Quadrature amplitude modulation

## After Modulator
![After Modulator](QAM16/AfterModulator.png)
## After Modulator
![Before Channel](QAM16/BeforeChannel.png)
## After Reciever
![After Reciever](QAM16/AfterReciever.png)



# QAM64 Quadrature amplitude modulation

## After Modulator
![After Modulator](QAM64/AfterModulator.png)
## After Modulator
![Before Channel](QAM64/BeforeChannel.png)
## After Reciever
![After Reciever](QAM64/AfterReciever.png)


#### Refrences:
https://www.mathworks.com/help/comm/ug/filter-using-simulink-raised-cosine-filter-blocks.html?fbclid=IwAR3Xu2_ZgBEm2Q08Cu3tKDj-UzaLIz3nFKxNjiEPBVjVNqoviO-5BePcXAo

The matlab model doc_rrcfiltercompare that can be loaded by typing the following at the MATLAB command line.

    `doc_rrcfiltercompare`