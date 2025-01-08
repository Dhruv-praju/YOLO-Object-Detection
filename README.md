##### Part 1: Object Detection
- Dataset:
  - SKU-110k Dataset is used
  - The [SKU-110k](https://docs.ultralytics.com/datasets/detect/sku-110k/) dataset is a collection of 11,762 densely packed retail shelf images and the dataset contains over 110,000 unique store keeping unit (SKU) categories with densely packed objects, often looking similar or even identical, positioned in proximity.
- Model:
 - pretrained Yolo11 model is used
 - input is an image containing products on the self and output is image with bounding boxes of products on the self
   
##### Part 3: Augmented Reality
AR Effects:
- Color Manipulation:
 - The image is converted to the HSV color space using cv2.cvtColor.
 - The hue channel is shifted by adding 60 (to simulate a cool tone or any desired effect).
   
- Dynamic Color Effect:
 - The hue shift changes the overall appearance of the image, giving it an AR-style filter.
 - This can simulate effects like a night vision filter or thermal imaging.
