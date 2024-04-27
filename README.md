# Nema 17 testbench
Welcome to this NEMA 17 Stepper Motor Test Bench repository!

This 3D printable test bench offers precision, reliability, and efficiency for testing NEMA 17 stepper motors. This platform is designed to streamline your testing process, providing accurate results with ease. Whether you're fine-tuning performance or ensuring quality control.

![Nema 17 bench](https://github.com/ProjectObservo/Nema-17-testbench/assets/168192722/36e27eb7-3f1a-4110-8c3c-3b6001f76f54)

## 3D printing list

You can find all the printable files in the CAD directory.
Use 15 to 25% infill for good results.

| Name                  | Amount | Comment                                                                 |
| --------------------- | ------ | ----------------------------------------------------------------------- |
| Nema 17 motor mount   | 1      | -                                                                       |
| Limit switch          | 1      | -                                                                       |
| Limit switch (Mirror) | 1      | -                                                                       |
| Belt holder           | 1      | 2mm is the default.<br /> Pick 2.5mm if the belt does not fit.      |
| Belt holder (Mirror)  | 1      | 2mm is the default.<br /> Pick 2.5mm if the belt does not fit.      |
| Carriage runner       | 1      | -                                                                       |
| Bearing cage          | 2      | 11.05mm is the default.<br /> Pick 11.2mm if the bearing does not fit. |


When you still have trouble to print the belt holder or bearing cage try to change the print scale e.g to 100.1% (bigger) or 99.9% (smaller) to slightly change the dimensions. 

## Buy list

| Name                | Amount | Comment                                                                                |
| ------------------- | ------ | -------------------------------------------------------------------------------------- |
| MGN12H slider       | 1      | Pick any length you want. (Image shows 400mm)                                          |
| GT2 open belt       | 1      | Length = (Slider length[mm] * 3) +  160 mm <br />(Belt in image is ~1360mm long) |
| GT2 T30 pulley      | 2      |                                                                                        |
| GT2 T16 IDLE pulley | 2      | No teeth !                                                                             |
| Brass insert        | 14     | M3 x 5 (outer diameter 5mm)                                                      |
| Micro switch        | 2      | SS-5GL or similar                                                                      |
| M3 x 10 bolt        | 20     | For motor, MGN12H slider and all brass insert mounts.                                  |
| M3 x 20 bolt        | 2      | Idler pulley                                                                           |
| Bearing 685         | 2      |                                                                                        |
| M5 x 50 theaded rod | 1      | used as an axle[^1]                                                                    |
| M5 Nut              | 2      |                                                                                        |

Assembled            |  Disassembled
:-------------------------:|:-------------------------:
![IMG_20240427_172804](https://github.com/ProjectObservo/Nema-17-testbench/assets/168192722/ea1ccc1b-5375-4196-a47e-09dde4f51acc) | ![IMG_20240427_173647](https://github.com/ProjectObservo/Nema-17-testbench/assets/168192722/e6c08a00-aaac-4d29-9f25-47518029cb27)

Note that the Bearing cage should be facing outward so that the bearing is visable (on both sides) when using a threaded rod instead of a solid axle.

[^1]:A solid axle can also be used but requires a lathe to create a slot to lock it in place with C retainer clips.
