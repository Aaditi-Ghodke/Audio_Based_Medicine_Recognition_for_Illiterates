# Audio_Based_Medicine_Recognition_for_Illiterates
Illiteracy is a significant barrier in solving 
personal healthcare problems and avoiding risks. Illiterate 
people cannot read labels of the prescribed medicines, and this 
increases the risk of medication misuse and the health risks. To 
address this concern, we proposed an innovative system which 
detects the medicine names from the user’s input images using 
YOLOv9 (You Only Look Once) object detection algorithm. On 
detection, the system provides the audio and text description of 
the uses of the detected medicine in the regional language (here, 
Marathi) of the user, making it highly accessible to an illiterate 
individual. Additionally, if the user inquiries about the potential 
side-effects of the detected medicine, the system responds with 
an audio explanation in Marathi, using Google’s text to speech 
library (gTTS) in the Python programming language. A user
friendly platform is developed using ‘Gradio’ for the deployment 
of the system model, this allows seamless interaction, even for 
users with limited technical knowledge. Notably, the model has 
achieved a highest mAP (mean Average Precision) of 99.5% for 
several commonly used medicines. The system empowers 
illiterate or semi-literate individuals, particularly beneficial in 
rural areas where the illiteracy rate is very high, to take care of 
their personal healthcare problems in their native language. 
