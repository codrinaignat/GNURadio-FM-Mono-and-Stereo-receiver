# GNURadio-FM-Mono-and-Stereo-receiver

This application was part of my dissertation thesis and it uses the RTL-SDR device, a cheap, popular and versatile SDR device.

Application features: 
- Configuration type selection: mono or stereo receiver, from the interface;
- FM reception in 87 - 108MHz range;
- The option to listen with or without recording the received sound;
- The option to save the sound in a wav file;
- Unprocessed received spectrum display in the tab Raw Frequency Representation;
- Mono and stereo receiver received spectrum display - Frequency Domain tab, after filtering and processing of the signal;
- The possibility to set the reception frequency, the volume and the device gain in dB, to make the reception more qualitative;
- Time domain display of the signal in the Time Domain tab;
- Spectrogram of the received signal, in the Waterfall tab;
- IQ diagram, in the Constellation tab.

The .grc file contains the block diagram made in GNU Radio. The .py file contains the blocks configuration behind the .grc file. The project is created using the RTL-SDR dongle. 

What you need in order to use this application: RTL-SDR device, GNU Radio software installed. 
If you want to find out more information about the RTL-SDR device, you can take a look here: https://usermanual.wiki/Document/The20Hobbyists20Guide20To20RTLSDR2020Carl20Laufer.399886352/view

Full documentation of the project in Romanian:

https://electronicaplicata.wordpress.com/2023/12/03/software-defined-radio-sdr-pentru-incepatori-aplicatii-si-explicatii/
