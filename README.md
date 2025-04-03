# project-Flow

# BRD- BUSINESS RESOURCES DOCUMENT.

# Tools & Libraries Used
- Video Processing: moviepy, cv2 (OpenCV)
- Audio Extraction & Transcription: ffmpeg, whisper (OpenAI Whisper)
- Text Summarization: openai (GPT-4), transformers (Hugging Face)
- OCR for Image Text: pytesseract (Tesseract OCR)
- Storage & Cloud: boto3 (AWS S3), os (Local File Handling)

# System Flow
- User Uploads Video → Stored in AWS S3 / Local
- Extract Audio from Video → Using FFmpeg, moviepy
- Convert Speech to Text → Using Whisper AI
- Extract Key Video Frames → Via OpenCV (cv2)
- Perform OCR on Extracted Frames → Using Tesseract (pytesseract)
- Summarize Extracted Text → With GPT-4 / Hugging Face Transformers
- Return Summarized Output → As JSON/Text File

# Use Cases
- Corporate Knowledge Transfer Videos → Summarized Reports
- Automated Meeting Transcription & Highlights
- Lecture Summarization for Students
- Content Indexing for Large Video Archives
