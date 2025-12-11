# solar-microgrid-monitor
IoT Solar Microgrid Monitor built with Flutter, ESP8266 (MicroPython). Tracks Voltage, Current, and Power with live alerts.

<img width="681" height="1223" alt="image" src="https://github.com/user-attachments/assets/de3922a6-3a67-4908-9649-1f4f3f3b714d" />

This image shows the artificial demonstration of how the hardware works.

<img width="732" height="1465" alt="image" src="https://github.com/user-attachments/assets/19189c70-af4d-42ff-b22d-3bb31658c1d2" />



Built this basic app on flutter which recieves data from the esp8266 and displays it to the app through a local wifi access point.

While this system successfully demonstrates local monitoring, the integration of Firebase for cloud syncing is currently pending. This feature was part of the original architectural design but was not implemented in v1.0 due to hackathon time limitations.

I am actively learning Firebase integration patterns and plan to push an update soon that will enable Global Remote Access, making this a truly "smart" IoT solution.



