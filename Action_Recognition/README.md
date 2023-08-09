# ComputerVisionProjects
Mix of small computer vision projects

Action Recognition Project : 

to run :

pip install mediapipe tensorflow opencv-python numpy matplotlib 

<h2>run cells one per one </h2>
<h1>TO CHANGE THE TYPE OF ACTIONS</h1> 
<p> cell number 7 <p>
DATA_PATH = os.path.join('THENAMEOFTHEFOLDERYOUWANTTOSAVETHENUMPYARRAYS') 
actions = np.array(["ACTION1","ACTIONS2","etc...."])
no_sequences = 30 # IS NOT A FIX NUMBER 
sequence_length = 15 # AVG NUMBER OF FRAME FOR EACH ACTION !!! IMPORTANT TO THINK WITCH NUMBER IS THE BEST !!!


THE INPUT SHAPE DEPENDS ON THE NUMBER OF KEYPOINTS ( HERE 1662 HORISTIC MEDIAPIPE )
BUT ALSO IMPORTANT sequence_length 
input_shape = (15, 1662)


ENJOY 
