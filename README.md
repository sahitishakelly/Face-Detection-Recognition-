##  Description

This project uses OpenCV and face_recognition library to detect and recognize faces in real-time using a webcam.

---

##  Features

* Real-time face detection
* Face recognition using trained dataset
* Supports multiple faces
* Easy addition of new users

---

##  Installation

```bash
pip install -r requirements.txt
```

---

##  How to Run

### Step 1: Add Faces

```bash
python add_faces.py
```

### Step 2: Train Model

```bash
python train_model.py
```

### Step 3: Start Recognition

```bash
python recognize.py
```

---

##  Controls

* Press **'s'** → Save face image
* Press **'q'** → Quit

---

##  Dataset Structure

```
dataset/
 ├── person_name/
 │   ├── image1.jpg
 │   └── image2.jpg
```

---

##  Output

* Faces are detected with bounding boxes
* Recognized faces show names
* Unknown faces labeled as "Unknown"

---

