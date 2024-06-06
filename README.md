# TFHub Aimbot

This project is an aimbot for the game Counter-Strike 2, developed using TensorFlow Hub and YOLO object detection.

## Prerequisites

To run this project, the following dependencies need to be installed:

- OpenCV (`pip install opencv-python`)
- Pillow (`pip install pillow`)
- Ultralytics (`pip install ultralytics`)
- win32gui (`pip install pywin32`)

## Instructions

1. Make sure Counter-Strike 2 is running.
2. Execute the file `WORK100% und schneller.py`.
3. The aimbot captures the screen of Counter-Strike 2, performs object detection, and moves the mouse to aim at the target.
4. The aimbot automatically clicks when a target is detected.

## Customizations

You can customize the following parameters to change the behavior of the aimbot:

- `window_title`: The title of the Counter-Strike 2 window.
- `size_scale`: The scaling of the captured screen.
- `scale_factor`: The scaling factor for mouse movements.

## Notes

- This project was developed for demonstration purposes only and should not be used for unfair gameplay practices.
- The accuracy of the aimbot depends on the performance of the YOLO model and the quality of the captured screen.

## License

This project is licensed under the MIT License. For more information, see the [License file](LICENSE).
