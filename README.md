# py-space

Welcome to **py-space**, a collection of personal Python notebooks and scripts.

Author: [Mailapalli Purushotham](https://github.com/purus15987)


This repo serves as a hands-on playground where I explore diverse domains such as: DS, ML, CV, NLP, Web Scraping and Creative Coding.


> Each notebook is beginner-friendly, well-commented, and ideal for learning through real-world projects.

---

## Table of Contents

### 1. [`Data_Analysis_and_Machine_Learning_Models_on_RNAseqTPM.ipynb`](./Data_Analysis_and_Machine_Learning_Models_on_RNAseqTPM.ipynb)

- **Description**: Analyze gene expression data (TPM values) from RNA-Seq experiments. Apply machine learning to classify samples.
- **Libraries**: `pandas`, `matplotlib`, `seaborn`, `sklearn`
- **Concepts**:
  - Data preprocessing (handling missing data, normalization)
  - Exploratory Data Analysis (EDA)
  - Feature selection
  - Classification using SVM, Decision Trees, Random Forest etc.
  - Model evaluation (accuracy, confusion matrix)

---

### 2. [`twitter_tweets_analysis.ipynb`](./twitter_tweets_analysis.ipynb)

- **Description**: Analyze and visualize sentiments in tweets. Ideal for real-world NLP beginners.
- **Libraries**: `tweepy`, `nltk`, `textblob`, `pandas`, `matplotlib`, `sklearn`
- **Concepts**:
  - Twitter API integration
  - Sentiment analysis (positive/negative/neutral)
  - Text preprocessing (stopword removal, lemmatization)
  - Word cloud and bar graph visualizations

---

### 3. [`Text_Extraction_from_Images.ipynb`](./Text_Extraction_from_Images.ipynb)

- **Description**: Extract text from images using OCR and visualize bounding boxes.
- **Libraries**: `cv2`, `pytesseract`, `python-docx`, `pymupdf`
- **Concepts**:
  - Optical Character Recognition (OCR)
  - Image thresholding
  - I/O File handling (pdf)
  - Text region visualization with bounding boxes

---

### 4. [`LSB_Steganography_Hide_Secret_Message_in_Image.ipynb`](./LSB_Steganography_Hide_Secret_Message_in_Image.ipynb)

- **Description**: Hide and reveal messages inside images using the LSB (Least Significant Bit) technique.
- **Libraries**: `cv2`, `numpy`, `matplotlib`
- **Concepts**:
  - Bit-level image manipulation
  - Data security through steganography
  - File encoding and decoding

---

### 5. [`Special_one_Animate_image_to_video.ipynb`](./Special_one_Animate_image_to_video.ipynb)

- **Description**: Create a speech video animation from single facial image.
- **Libraries**: `cv2`, `os`, `imageio`, `ffmpeg-python`
- **Concepts**:
  - This project built upon [First Order Motion Model for Image Animation](https://github.com/AliaksandrSiarohin/first-order-model)
  - [Pretrained Checkpoint](https://drive.google.com/uc?id=1L8P-hpBhZi8Q_1vP2KlQ4N6dvlzpYBvZ/vox-adv-cpk.pth.tar) for Image Animation
  - Haar Cascade classifier for face detection
  - Frame capture and sequencing
  - Video writing using OpenCV
  - Frame rate and encoding settings
  - Animation with custom audio

---

### 6. [`Realtime_Memory_Game.ipynb`](./Realtime_Memory_Game.ipynb)

- **Description**: A fun memory game built using Python with real-time feedback.
- **Libraries**: `IPython.display`, `random`, `Pillow`, `google.colab`
- **Concepts**:
  - GUI development with IPython.display and openCV in google colab
  - Event handling
  - Game loop and UI design

---

### 7. [`IRCTC_Ticket_Booking_AUTOMATION_Web_Scraping.ipynb`](./IRCTC_Ticket_Booking_AUTOMATION_Web_Scraping.ipynb)

- **Description**: Automates the process of logging in and searching trains on IRCTC using Selenium.
- **Libraries**: `selenium`, `pytesseract`, `time`, `pandas`
- **Concepts**:
  - Web automation (Connect to IRCTC website, Login, form filling, catchpa entering, button clicks, Train and Coach selection, Proceed to Pay and Confirmation)
  - Whole project done in google colab
  - Handling dynamic elements
  - `pytesseract` for captcha extraction, error handling and re-login.
  - Payment review and default gateway payment through UPI.

---

### 8. [`Youtube_Video_Downloader.ipynb`](./Youtube_Video_Downloader.ipynb)

- **Description**: Download YouTube videos and store them locally using Pytube.
- **Libraries**: `pytube`, `os`
- **Concepts**:
  - Youtube Playlist Video download automation
  - Stream resolution selection
  - File saving and exception handling
  - Attempting to bypass age restrictions. (Education purpose only)

---

### 9. [`compress_pdf.ipynb`](./compress_pdf.ipynb)

- **Description**: Compress large PDF files using PyPDF2.
- **Libraries**: `PyPDF2`, `PyMuPDF`, `fitz`, `pypdf`, `pdf2image`, `os`
- **Concepts**:
  - File I/O
  - PDF compression
  - Reduce quality percentile, Convert each page of the PDF to an image
  - Document automation

---

### 10. [`OpenCV_projects_codes.ipynb`](./OpenCV_projects_codes.ipynb)

- **Description/Projects**: Text Detection/ Face and Eyes Detection/ Remove Background/ Object Detection and Tracking/ 
- **Libraries**: `openCV`, `skimage`, `Haar cascade`, `rembg`, `Pillow`
- **Concepts**:
  - Text Detection using image processing and contour detection.
  - Thresholding and Morphological operations.
  - pre-trained Haar cascade for face detection.
  - Remove Background using `remg` package.
  - Object Detection and Tracking using Shi-Tomasi corner detection, Lucas Kanade Method, optical flow, OpenCV video processsing.

---


### 11. [`OpenCV_projects_2.ipynb`](./OpenCV_projects_2.ipynb)

- **Description/Projects**: Harry Potter’s Invisible Cloak, 
- **Libraries**: `openCV`, `os`
- **Concepts**:
  - Color detection and segmentation
  - Thresholding and Morphological operations.
  - Handling Mouse Events on images using openCV - EVENT_MOUSEMOVE, EVENT_LBUTTONDOWN, EVENT_RBUTTONDOWN, EVENT_LBUTTONUP, EVENT_RBUTTONUP

---


## Technologies & Tools

- **Languages**: Python 3.x
- **Tools**: Jupyter Notebook, Google Colab, OpenCV, Selenium, PyTesseract

---
This repository is intended purely for educational purposes to help learners explore python, Data Science, ML, NLP, OpenCV and Creative Coding through practical examples and hands-on notebooks.

  ⚠️ Note: Many of the contents, images, and resources used here are sourced or adapted from publicly available educational materials, courses, blogs, and books. While efforts have been made to provide attribution, some references may be incomplete or unintentionally omitted. If you identify any such case, feel free to raise an issue or pull request for correction.

Feel free to modify the code, run experiments, and explore various techniques and applications. For specific questions about a notebook (e.g., setup, debugging, or output interpretation), let me know, and I can provide tailored guidance.


---


## Contact

Mailapalli Purushotham

📧 [purus15987@gmail.com](mailto:purus15987@gmail.com)

🔗 GitHub: [https://github.com/purus15987](https://github.com/purus15987)

🔗 LinkedIn: [https://www.linkedin.com/in/purus15987/](https://www.linkedin.com/in/purus15987/)
