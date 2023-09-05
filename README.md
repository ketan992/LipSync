# LipSync using Wav2Lip
## Video Trimming 
The provided output audio was only 67sec long, so it was necessary for the video to be trimmed and remove the unnecessary frames that didn't contain faces. Wav2Lip works only for videos that contain a face.
Wav2Lip_video_trim_only_Face.ipynb shows how the video trimming was done using Pretrained Haar Cascade Classfier Model and open-cv to detect faces in the video.

## LipSync
The simplified pretrained model by justinjohn-03 was used for lip syncing the audio to the video
The colab notebook contains 3 steps
1. Setup
2. Lip Sync Youtube video
3. Lip Sync your video

For this task only step 1 and 3 were used as the video need to be trimmed to match the length of the audio
In step 3 it is possible to add custom path of the video and audio, after adding the path runs the cells in order to get the output video.
