# Raised Cosine bonus

# List of required modulation schemes
- **[BPSK](#BPSK-Binary-Phase-Shift-Keying)**
- **[QPSK](#QPSK-Quadrature-phase-shift-keying)**
- **[FSK](#FSK-Frequency-shift-keying)**
- **[QAM16](#QAM16-Quadrature-amplitude-modulation)**
- **[QAM64](#QAM64-Quadrature-amplitude-modulation)**

# General Scheme
    just different modulator block for each scheme
![General scheme](RaisedCosine.PNG)

# BPSK Binary Phase Shift Keying
## After Modulator
![After Modulator](BPSK_RC/AfterModulator.PNG)
## After Modulator
![Before Channel](BPSK_RC/BeforeChannel.PNG)
## After Reciever
![After Reciever](BPSK_RC/AfterReciever.PNG)



# QPSK Quadrature phase shift keying

## After Modulator
![After Modulator](QPSK/AfterModulator.PNG)
## After Modulator
![Before Channel](QPSK/BeforeChannel.PNG)
## After Reciever
![After Reciever](QPSK/AfterReciever.PNG)

# FSK Frequency shift keying

## After Modulator
![After Modulator](FSK/AfterModulator.PNG)
## After Modulator
![Before Channel](FSK/BeforeChannel.PNG)
## After Reciever
![After Reciever](FSK/AfterReciever.PNG)


# QAM16 Quadrature amplitude modulation

## After Modulator
![After Modulator](QAM16/AfterModulator.PNG)
## After Modulator
![Before Channel](QAM16/BeforeChannel.PNG)
## After Reciever
![After Reciever](QAM16/AfterReciever.PNG)



# QAM64 Quadrature amplitude modulation

## After Modulator
![After Modulator](QAM64/AfterModulator.PNG)
## After Modulator
![Before Channel](QAM64/BeforeChannel.PNG)
## After Reciever
![After Reciever](QAM64/AfterReciever.PNG)


#### Refrences:
https://www.mathworks.com/help/comm/ug/filter-using-simulink-raised-cosine-filter-blocks.html?fbclid=IwAR3Xu2_ZgBEm2Q08Cu3tKDj-UzaLIz3nFKxNjiEPBVjVNqoviO-5BePcXAo

The matlab model doc_rrcfiltercompare that can be loaded by typing the following at the MATLAB command line.

    `doc_rrcfiltercompare`