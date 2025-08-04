# Vehicle-cut-in-detection-using-single-dashcam
A  real time adas ( Automatic Driver Assistance system) using single dash cam footage to indentify other vehicles using YOLO  and generate warning signal if there is chance of collision
The sytem is designed in a way that it identifies all the vechiles visible through the dashcam  using YOLO as the object detection model and then calulate their speeds and distance  relative to our vehicle .We are then able to calculate the time it takes in case a collison is to happen.If this time is below a certain threshold that is lower than the average human reaction speed then a warning signal is generated.The warning signal is only generated if the vechicle enters a pre marked zone in front of our vechile inside which a possible collision might happen

