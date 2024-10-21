**🪄Overview**
While working on creating the dataset for an Automatic Plate Number Recognition (APNR) system, I initially used OpenCV to extract all the given video's frames efficiently. 
This prevented any data loss and increased accuracy in selecting the frames. I manually selected the frames with the most visible plate numbers from different cars. 
I ignored some cars due to poor visibility of their plate numbers or their random appearance in the video, which made capturing their 10 distinct images frames impossible. 
I was able to get 14 folders of detected cars, each folder with 10 visible images of that certain car.

**Challenges:**
I attempted to use the YOLOv7 model to streamline the frame extraction process using OpenCV by only extracting frames with detected cars. 
However, this led to the loss of some useful frames from the video. Consequently, I decided to extract all the frames and manually select the needed ones while discarding the unnecessary ones.
Additionally, the program took quite a long time to extract all the frames,⏱️ so I had to patiently wait until the extraction process was completed.

**Summary**
Throughout this task, I gained valuable experience by staying patient and focused to ensure that I didn't miss any useful details; 
for this case I mean to miss any car which was clearly and significantly recorded in the video. I also had the opportunity to refresh my OpenCV skills, 
which proved to be beneficial for this task. Despite not successfully extracting the frames containing cars using the YOLO model, I gained further experience in working with this powerful recognition model, 🚀You Only Look Once (YOLO) model🚀.
