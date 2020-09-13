Documentation:
Python: cv2.VideoCapture(filename) → <VideoCapture object>

Open video file for video playing

Parameters:          

filename – name of the opened video file (eg. video.avi) or image sequence (eg. img_%02d.jpg, which will read samples like img_00.jpg, img_01.jpg, img_02.jpg, …)
Python: cv2.imwrite(filename, img[, params]) → retval

Saves an image to a specified file.

Parameters:          
filename – Name of the file.
image – Image to be saved.
params –
Format-specific save parameters encoded as pairs paramId_1, paramValue_1, paramId_2, paramValue_2,
Steps:
Load the video file using cv2.VideoCapture()
Read video frames using cv2.VideoCapture.read()
Write each frame using cv2.imwrite()
Release the VideoCapture object using cv2.VideoCapture.release()
Exit window and destroy all windows using cv2.destroyAllWindows()

