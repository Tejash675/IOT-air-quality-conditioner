# IOT-air-quality-conditioner
COMPANY : CODTECH IT SOLUTIONS

NAME : SINGAMPALLI TEJASH VARDHAN

INTERN ID : CT04DF1943

DOMAIN : INTERNET OF THINGS

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH KUMAR

The *IoT Air Quality Monitor* project is a simple yet effective system designed to detect and monitor the air quality in a specific environment using an Arduino Uno and a gas sensor. The core objective of this project is to measure the level of pollutants or harmful gases in the air and interpret this data using a microcontroller. This system is highly relevant in today’s context where air pollution is a growing concern in urban areas, and there is a need for real-time monitoring solutions. The project was built and simulated using *Tinkercad*, an online platform that allows users to design circuits and test Arduino codes without the need for physical hardware.

In this project, the primary component used for sensing air quality is a *gas sensor* such as the MQ135 or MQ2. These sensors are capable of detecting gases like carbon monoxide (CO), ammonia (NH₃), nitrogen dioxide (NO₂), alcohol, benzene, and smoke. The sensor outputs an analog voltage that varies depending on the concentration of these gases in the environment. This analog signal is then read by the *Arduino Uno* through one of its analog input pins, typically *A0*.

The circuit setup is straightforward. The gas sensor has three essential pins: *VCC, **GND, and **Analog Output (A0). The VCC pin is connected to the **5V* pin on the Arduino to provide power, the GND pin goes to *ground, and the analog output is connected to **analog pin A0* on the Arduino Uno. This allows the Arduino to continuously read the sensor’s output and process it in real time. Though the image shows only the analog connection, a complete setup must include proper power and ground connections for the sensor to function correctly.

Using *Tinkercad*, we can simulate this circuit virtually. Tinkercad provides a powerful simulation environment where users can place components, make connections, and run Arduino code to test their designs. It eliminates the need for physical components during the prototyping phase, which is especially beneficial for students and beginners. In Tinkercad, we can write and upload Arduino code to the virtual board, monitor the serial output, and even simulate changes in sensor readings by modifying the environment settings.

The Arduino code for this project reads the analog values from the gas sensor and prints them to the *serial monitor*, which helps users understand the air quality in numerical terms. These readings can be further calibrated to indicate specific pollutant levels or thresholds. In a real-world scenario, this data could be sent to the cloud using Wi-Fi modules like ESP8266 or displayed on an LCD screen. Alerts could also be generated if the air quality drops below a certain standard.

In summary, this IoT Air Quality Monitor project provides a basic yet functional model for monitoring environmental pollution using Arduino and a gas sensor. The use of Tinkercad as a simulation tool enhances the learning process and allows for quick testing without any hardware investment. This project can serve as a foundation for more advanced IoT-based environmental monitoring systems.
