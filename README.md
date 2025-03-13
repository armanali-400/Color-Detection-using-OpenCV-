# 🎨 Color Detection using OpenCV  

## 📌 Overview  
This is a simple **Color Detection** project built using **OpenCV** and **Pandas**. The program allows users to click on an image, and it will display the color name along with its RGB values.  

## 🚀 Features  
✔ Detects color by clicking on any pixel of an image.  
✔ Displays the closest **color name** and its **RGB values**.  
✔ Uses a **color dataset (colors.csv)** for accurate color matching.  
✔ Simple and interactive UI using **OpenCV**.  

## 🛠️ Technologies Used  
- Python 🐍  
- OpenCV (cv2)  
- Pandas (for handling color dataset)  

## 📂 Project Structure  
```
Color_Detection/
│── app.py              # Main Python script
│── colors.csv          # Color dataset (RGB values with color names)
│── img1.jpg            # Sample image for color detection
│── requirements.txt     # Dependencies list
└── README.md           # Project documentation
```

## 🔧 Installation & Setup  
### 1️⃣ **Clone the Repository**  
```sh
git clone https://github.com/armanali-400/Color-Detection.git
cd Color-Detection
```

### 2️⃣ **Create a Virtual Environment (Optional but Recommended)**  
```sh
python -m venv venv
```
Activate the virtual environment:  
- **Windows**: `venv\Scripts\activate`  
- **Mac/Linux**: `source venv/bin/activate`  

### 3️⃣ **Install Dependencies**  
```sh
pip install -r requirements.txt
```

### 4️⃣ **Run the Application**  
```sh
python app.py
```

## 📌 How It Works  
1️⃣ **Load an Image**: The program opens an image (`img1.jpg`).  
2️⃣ **Click on Any Color**: Double-click on any pixel to get the color name and RGB values.  
3️⃣ **Display Color Information**: A rectangle appears showing the color name and RGB values.  
4️⃣ **Press `ESC` to Exit**: Close the window when done.  

## 📸 Demo Screenshot  
![Color Detection](https://via.placeholder.com/600x300.png?text=Demo+Screenshot)  

## 📝 Notes  
- Ensure `colors.csv` is in the same directory as `app.py`.  
- You can replace `img1.jpg` with any other image for testing.  

## 📜 License  
This project is **free to use** under the **MIT License**.  
