# 🧥 Invisible Cloak using Python  
**A fun computer vision project inspired by Harry Potter’s invisibility cloak.
This project uses Python + OpenCV to create an illusion where a selected color (like red) is replaced by the background, making the object "invisible".**  

## 📌 Features

- 🔍 Detects a specific cloak color (e.g., red).
- 🎥 Works in real-time using webcam.
- 🖼️ Uses image masking + background subtraction techniques.
- ⚡ Lightweight and fast with OpenCV.
- 🎮 Interactive — you can try different cloak colors.

##  Tech Stack
- Langugage: 
  - Python
- Libraries:
   - OpenCV (cv2)
   - NumPy
## 🚀 How It Works
1. Capture the background frame (without the cloak).
2. Detect cloak region using color detection (HSV mask).
3. Replace the cloak area with the stored background.
4. Overlay final frames to create the illusion of invisibility.

## 📂 Project Structure
 ``` text
Invisible-Cloak/
│── invisible_cloak.py  # Main code file
│── background.jpg      # Saved background image
│── requirements.txt    # Required Python libraries
│── README.md           # Project documentation
```
## ⚙️ Installation & Usage
 1️. Clone the repository
```text
git clone https://github.com/Akash-Sahani18/Invisible-Cloak.git
cd invisible-cloak
```
2. Install dependencies
```text
  pip install -r requirements.txt
```
3. Run the project
```text
  python Invisible_cloak.py
```
## Wear your red cloak (or chosen color) and watch the magic! ✨
| Without Cloak                                              | With Cloak                                                             |
| ---------------------------------------------------------- | ---------------------------------------------------------------------- |
| ![Normal](https://via.placeholder.com/250x150?text=Person) | ![Invisible](https://via.placeholder.com/250x150?text=Invisible+Cloak) |

## 🧩 Possible Improvements

- Allow multiple cloak colors.
- Add GUI to select custom cloak color.
- Support video file input instead of only webcam.
- Apply smoothing filters for better cloak blending.
## 🤝 Contributing  
  Pull requests are welcome! If you’d like to improve detection or add new features, feel free to fork and submit a PR.
## 📜 License    
  This project is licensed under the MIT License – free to use and modify.

## 🌟 Acknowledgements
- Inspired by Harry Potter & Avengers Infinity War
- Built with OpenCV tutorials & docs
- Idea credits: OpenCV community

## 🧑‍💻 Developer  
*Akash Sahani*  
📫 [GitHub](https://github.com/Akash-Sahani18) | [LinkedIn](https://www.linkedin.com/in/akash-sahani-440147243)
  
   

  
