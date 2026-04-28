# Sturdy-Octo-Disco-Adding-Sunglasses-for-a-Cool-New-Look

# Sturdy Octo Disco - Sunglass Overlay Project

Welcome to **Sturdy Octo Disco**, a fun and creative computer vision project that transforms ordinary photos into stylish ones by adding sunglasses using image processing techniques!

This project demonstrates how OpenCV and NumPy can be used to perform image manipulation, masking, and blending to achieve realistic overlays.

---

## Features

- Applies image processing techniques (masking & blending)
- Adds sunglasses overlay on face images
- Accurate positioning using ROI (Region of Interest)
- Works well with passport-style / front-facing images
- Easy to customize with different sunglass images

---

## Technologies Used

- **Python**
- **OpenCV** – for image processing
- **NumPy** – for numerical operations
- **Matplotlib** – for displaying results

---

## How It Works

1. Load the face image and sunglass PNG (with alpha channel)
2. Extract the alpha mask from the sunglass image
3. Resize the sunglass to match eye region
4. Select ROI (eye area) from face image
5. Apply masking and blending:
   - Background = Face × (1 - Mask)
   - Foreground = Glass × Mask
6. Combine both to get final realistic output 

---

## output :

# original image
<img width="695" height="426" alt="image" src="https://github.com/user-attachments/assets/391bcc83-b87d-4156-ba04-eef3215833c6" />

# modified image
<img width="813" height="314" alt="image" src="https://github.com/user-attachments/assets/035fbf44-4c45-4ed9-b953-5fef0ea220de" />

