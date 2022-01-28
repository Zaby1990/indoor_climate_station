# SparkFun Luftqualitäts-Sensor Breakout, CCS811
[Reference](https://www.berrybase.de/sensoren-module/gas-staub/sparkfun-luftqualit-228-ts-sensor-breakout-ccs811)  

Der CCS811 Air Quality Breakout ist eine digitale Gassensorlösung, die eine breite Palette von flüchtigen organischen Verbindungen (TVOCs), einschließlich äquivalentem Kohlendioxid (eCO2) und Metalloxid (MOX), erfasst. VOCs werden oft als Schadstoffe und/oder sensorische Reizstoffe kategorisiert und können aus einer Vielzahl von Quellen stammen, wie z. B. Baumaterialien (Farbe, Teppich, etc.), Maschinen (Kopierer, Prozessoren, etc.) und sogar Menschen (Atmung, Rauchen, etc.). Dieses Breakout ist für die Überwachung der Luftqualität in Innenräumen in persönlichen Geräten wie Uhren und Telefonen gedacht, aber wir haben es auf ein Breakout-Board gesetzt, damit Sie es als reguläres I2C-Gerät verwenden können.

Der onboard CCS811 unterstützt mehrere Messmodi, die für einen geringen Stromverbrauch während einer aktiven Sensormessung und einen Idle-Modus zur Verlängerung der Batterielebensdauer in tragbaren Anwendungen optimiert wurden. Wir haben jeden notwendigen Pin auf dem CCS811 sowie zusätzliche Pins herausgebrochen, um Ihren eigenen NTC-Thermistor hinzuzufügen, um die Temperatur der Umgebung des CCS811 zu bestimmen, die zur Kompensation der Messwerte verwendet werden kann.

Hinweis: Bitte beachten Sie, dass das Datenblatt des CCS811 eine Einbrennzeit von 48 Stunden und eine Einlaufzeit von 20 Minuten empfiehlt (Sie müssen dem Sensor 20 Minuten Zeit geben, um sich aufzuwärmen und gültige Daten auszugeben).

Hinweis: Die Temperaturkompensation durch einen angeschlossenen NTC-Thermistor wird beim CCS811 nicht mehr unterstützt. Um dem CCS811 eine Umgebungskompensation hinzuzufügen, benötigen Sie einen externen Umgebungssensor wie den SparkFun Atmospheric Sensor Breakout -BME280. Wenn Sie auf der Suche nach einem Board sind, das diese Umweltkompensation eingebaut hat, schauen Sie sich das SparkFun Environmental Combo Breakout - CCS811/BME280 (Qwiic) an.

## Features:
- Total Volatile Organic Compound (TVOC)-Messung von 0 bis 32.768 Teilen pro Milliarde
- eCO2-Erfassung von 400 Teilen pro Million bis 29.206 ppm
- Fünf Betriebsmodi
- Integrierte MCU
- Onboard-Verarbeitung
- Standard I2C-Digitalschnittstelle
- Optimierte Low-Power-Modi
- Optional NTC-Thermistor-Pins

## Documents
[Get Started with the CCS811 Breakout Guide](https://learn.sparkfun.com/tutorials/ccs811-air-quality-breakout-hookup-guide)  
[Circuit Diagram](https://cdn.sparkfun.com/datasheets/BreakoutBoards/SparkFun_CSS811_Breakout.pdf)  
[Eagle-File](https://cdn.sparkfun.com/datasheets/BreakoutBoards/SparkFun_CSS811_Breakout.zip)  
[Assembly Instructions](https://learn.sparkfun.com/tutorials/ccs811-air-quality-breakout-hookup-guide)  
[Measuring Instruction](https://www.sparkfun.com/news/2369)  
[Programming Guide](https://cdn.sparkfun.com/datasheets/BreakoutBoards/CCS811_Programming_Guide.pdf)  
[Data Sheet](https://cdn.sparkfun.com/assets/2/c/c/6/5/CN04-2019_attachment_CCS811_Datasheet_v1-06.pdf)  
[Arduino Library](https://github.com/sparkfun/SparkFun_CCS811_Arduino_Library/archive/master.zip)  
[Github](https://github.com/sparkfun/CCS811_Air_Quality_Breakout)  