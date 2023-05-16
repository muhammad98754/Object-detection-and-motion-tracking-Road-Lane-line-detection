# Object-detection-and-motion-tracking-Road-Lane-line-detection


In my project, I utilized OpenCV to implement object detection and tracking algorithms, which played a crucial role in various computer vision applications. By leveraging the HSV (Hue, Saturation, Value) color space, I ensured accurate identification of objects in real-time video streams or images.

For object detection, I employed the HSV color space to effectively isolate and segment specific objects of interest. This approach proved to be highly advantageous, as it provided better discrimination capabilities compared to other color spaces. By setting appropriate color ranges in the HSV color space, I was able to detect objects with precision and robustness.

To track objects over time, I adopted contour analysis techniques. By identifying and tracking the contours of objects, I could accurately determine their motion and trajectory. This allowed me to track moving objects even in complex scenes with occlusions or background clutter.

![windowkk](https://github.com/muhammad98754/Object-detection-and-motion-tracking-Road-Lane-line-detection/assets/130402856/9fcda5bf-f47c-485a-832d-e96beeb4042c)

In addition to contour analysis, I incorporated the Camshift (Continuously Adaptive Mean Shift) algorithm from OpenCV for object tracking. This algorithm not only tracks objects based on their appearance but also dynamically adapts its tracking window size and position, ensuring accurate tracking even when objects undergo scale or orientation changes.

Furthermore, I extended my project to include road lane line detection, which is crucial for autonomous driving systems. By analyzing video frames, I developed algorithms to extract and track lane lines, enabling autonomous vehicles to stay within designated lanes. This contributed to enhancing the safety and reliability of autonomous driving technologies.

                                    Road Lane Line Detection

![Figure_1](https://github.com/muhammad98754/Object-detection-and-motion-tracking-Road-Lane-line-detection/assets/130402856/aaef0281-f158-403c-9f54-29e322c0b9da)

Overall, this project showcased my proficiency in utilizing OpenCV for object detection and tracking using the HSV color space, contour analysis, and the Camshift algorithm. Additionally, the development of road lane line detection added value to autonomous driving systems by enhancing their ability to perceive and navigate the road environment.

                                    Background Subtraction method (original image)
                             
![window](https://github.com/muhammad98754/Object-detection-and-motion-tracking-Road-Lane-line-detection/assets/130402856/408b0a7f-b27a-4e94-a7ea-a449e859e1e3)                             
                                      Background Subtraction method (result)
                             
![fgmask](https://github.com/muhammad98754/Object-detection-and-motion-tracking-Road-Lane-line-detection/assets/130402856/c1a37357-a86d-415f-bd1b-aa62f45ca641)

                         
                             
                             
