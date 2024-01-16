So this basically does the same as the serial connection, but uses a Bluetooth to serial module (HC-06)
(check the original project at https://github.com/joaosantos7614/Arduino-8x8-serial)

Achieved:
- Control the matrix using a bluetooth connection

Not achieved:
- Replace the Web Serial API with the Web Bluetooth API (for some reason the connection dialog does not display this specific device)
- Be able to use as a web app (depends on the previous item)
- Connect directly to the device, without the connection dialod (just need the device UUID)


Keywords:
- arduino
- 8x8 led matrix
- web serial API
- web bluetooth API (work in progress)
