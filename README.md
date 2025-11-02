# ECG_Digitization
ECG Digitization – Week 1 Summary
Day 1 – Introduction to ECG

Learnt about what ECG represents (electrical activity of heart).

Understood P Q R S T waves and what each spike means.

Difference between normal, high, and low spikes.

Day 2 – Understanding ECG Concepts

Learnt about ions (positive & negative) and how they affect spikes.

Understood why ECG is also called EKG.

Day 3 – Setting up the Environment

Installed Anaconda + Jupyter Notebook.

Installed OpenCV (4.12.0) and managed NumPy version conflicts.

Successfully ran first image load and grayscale conversion script.

Day 4 – Grayscale Conversion

Converted color ECG image to grayscale using OpenCV.

Learnt how to save processed images using cv2.imwrite().

Day 5 – Edge Detection (Canny)

Applied Gaussian blur and Canny edge detection.

Understood the purpose of thresholds and how they clarify ECG trace.

Observed differences between morphological, adaptive, and final Canny outputs.

Day 6 – Visual Comparison

Displayed two ECG images side by side for visual analysis.

Noted differences in brightness / contrast and ECG lead types (V1–V6, aVR, aVL, aVF).

Day 7 – Reflection

Key takeaway: Image preprocessing (grayscale → edge → morphology) helps isolate ECG signal.

Learnt that understanding the physical meaning (leads & heart areas) is equally important.

Next goal: Start extracting signal points programmatically.

🧱 Step 3. Add Visuals (optional)

If you’re doing it in Word, you can paste:

Original ECG image

Grayscale image

Edge-detected image

If in Markdown, just reference them like:

![Grayscale ECG](images/ecg_gray.pn)
![Edge Detected ECG](images/ecg_edges.png)
