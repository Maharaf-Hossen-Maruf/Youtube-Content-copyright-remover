# Youtube-Content-copyright-remover Automation & Telegram Notification Bot



A Python-based automation system that downloads videos from YouTube, processes them, republishes to another channel, and sends notifications via Telegram. This project demonstrates **video processing automation, API integration, and workflow optimization**.

## 🔹 Features

- Download videos from specified YouTube channels.
- Process videos: resizing, watermark overlay, subtitle burn-in, color adjustments.
- Re-publish processed videos to another YouTube channel.
- Send Telegram notifications after video publication.
- Optimized performance using FFmpeg and OpenCV for video processing.
- Modular design: separate scripts for main workflow and video processing.

## 🔹 Tech Stack

- **Programming Language:** Python  
- **Video Processing:** OpenCV, FFmpeg, NumPy  
- **Automation:** Python scripts with scheduling support  
- **Notification:** Telegram Bot API  

## 🔹 File Structure



youtube-automation/
│
├── main_remainder.py # Main script to handle workflow, scheduling, and notification
├── process.py # Script for video processing (resize, watermark, etc.)
├── requirements.txt # Required Python packages
└── README.md # Project documentation


## 🔹 Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/youtube-automation.git


Navigate to the project folder:

cd youtube-automation


Create a virtual environment:

python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate


Install dependencies:

pip install -r requirements.txt


Configure API keys:

Add YouTube API credentials.

Add Telegram Bot token and chat ID.

Run the scripts in order:

python main_remainder.py
python process.py


Note: main_remainder.py handles the workflow and triggers notifications, while process.py performs all video processing tasks.

🔹 Future Enhancements

Add multi-channel support to process videos from multiple sources simultaneously.

Implement logging and error handling for smoother automation.

Add GUI to manage channels, videos, and notifications easily.

🔹 Author

Maharaf Hossen
