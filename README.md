# Rubber-ducky
Instructions:

1. Clone the repo
2. Download CircuitPython for Raspberry Pi Pico 8.0.0: https://adafruit-circuit-python.s3.amazonaws.com/bin/raspberry_pi_pico/en_GB/adafruit-circuitpython-raspberry_pi_pico-en_GB-8.0.0.uf2
3. Plug the microcontroller into the computer while holding down the BOOTSEL button, it should show up as a mass storage device name "RPI-RP2".
4. Paste the Adafruit .uf2 file into the microcontroller. It will reboot, now named "CIRCUITPY".
5. Rename it to "DUCKY"
6. Replace all the file in the microcontroller with the ones from the cloned repo. The contents of the controller should look the same as the contents of the repo.
WARNING: payload.dd will be executed once the files are copied over.

Thats it. You now have a rubber ducky that functions the same as the one made for my course work.
