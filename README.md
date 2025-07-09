# Hand-Gesture-Detection

Hand Gesture Detection using MediaPipe

---

## 📚 Frameworks Used
- OpenCV
- MediaPipe
- TensorFlow
- NumPy

---

## ⚙️ Working

- Using `generating_data.py`, you can **generate your own training data**.  
  🎯 This gives you freedom to create custom gestures — no need for external datasets.  
  So you can train on any gesture you want using your webcam.

- Using `training_model.py`, you can **train your gesture detection model**  
  📁 It will use the data generated in the previous step.

- The model will be saved as `gesture_model.h5`

- Finally, use `testing.py` to **test your model in real-time**

---

## 📂 Files in This Project

| File | Description |
|------|-------------|
| `generating_data.py` | Record gesture images using webcam |
| `training_model.py` | Train the CNN model |
| `testing.py` | Test the model with live webcam |
| `gesture_model.h5` | The trained model |
| `requirements.txt` | Python libraries needed |
| `README.md` | Project description |
