# VideoAnalytics
Finding emotions and sentiments of a speaker from a recorded video.

Video comprises of two components - image and audio.

I am analysing each of them separately.

### Audio Analytics
1. Separates Audio from the video
2. Uses STT (Speech to Text) to convert audio to text
3. Finds Sentiment of the text

### Image Analytics
1. Extracts an image every 2 seconds from the video
2. Finds if the image has a detectable face. If yes, extracts the face
3. Uses Emotion Detection CNN model trained in Emotion_Classifier_Modelling_.ipynb file
4. Aggregates and tell percentage of each of the emotion in the video

