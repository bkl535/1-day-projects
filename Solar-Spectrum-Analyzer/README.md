# Solar-Spectrum-Analyzer
This device uses the not so well known fact that cheap LEDs are photosensitive (at a wavelenth close to the light emitted by an LED connected to a power source). Multi-chromatic light (ex: Sunlight) intensity is measured in real-time using 8 different wavelength LEDs. A python programs grabs the serial data via usb/bluetooth and generates a real time graph of wavelenth vs intensity. The device can be taken outside to see a graph of the solar spectrum. The temperature of the sun can be approximated by fitting Weins displacement law.