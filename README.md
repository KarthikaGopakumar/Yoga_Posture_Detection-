🧘 **Yoga Posture Detection Using Mediapipe (Image-Based)**

This project detects yoga postures from images using **Mediapipe**’s pose estimation model. Instead of using live webcam input, it processes a set of images stored in a folder and identifies body landmarks to evaluate posture.

🧠 **Project Overview**

The main steps involved in this project are:

1. **Load Images from a Folder**
   - The project reads a set of yoga posture images stored locally.
   - Each image is processed one by one using a loop.

2. **Detect Body Landmarks with Mediapipe**
   - Mediapipe's pose model identifies 33 key landmarks on the body (like shoulders, elbows, hips, knees, etc.).
   - These landmarks are the foundation for understanding the posture in each image.

3. **Analyze Landmarks to Identify Yoga Poses**
   - Angles and positions between joints are calculated using the landmark data.
   - These measurements are compared to known pose patterns to identify which yoga posture is being performed.

4. **Provide Visual Feedback**
   - Landmarks and skeleton lines are drawn on each image.
   - This helps visualize the detected pose and assess its correctness.
   - You can extend this with pose names or accuracy messages for user guidance.

🧰 **Technologies Used**

- **Python**
- **OpenCV** – For image loading and drawing.
- **Mediapipe** – For human pose estimation.
- **NumPy** – For calculations involving landmark coordinates.

🗂️ **How to Use**

1. Put your yoga posture images in a folder (e.g., `images/`).
2. Run the notebook `Yoga.ipynb`.
3. The code will:
   - Loop through each image.
   - Detect pose landmarks.
   - Draw and optionally save the output images with annotations.

🧪 **Features**

- Works with still images (not real-time webcam).
- Detects and visualizes body landmarks.
- Prepares the base for pose classification or correction feedback.
- Easy to test and extend with more advanced pose logic.

🧭 **Future Improvements**

- Add classification logic for more specific yoga poses.
- Compare detected poses with reference poses for scoring.
- Export feedback or pose data to CSV or JSON.
- Build a small web or desktop app interface.

👩‍💻 **Author**

Karthika Gopakumar
Email: karthikagopakumar303@gmail.com
LinkedIn: https://www.linkedin.com/in/karthika-gopakumar-1- 


