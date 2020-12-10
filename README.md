## Virtual-Assistant(Python)

- Description: <br>
     A simple virtual assistant that can take order over voice. It can tell current date, time and can give description about a person through        wikipedia.<br>
     
- Libraries used: <br>
 ```speech_recognition```<br>
 ```gtts```<br>
 ```os```<br>
 ```wikipedia```<br>
 ```datetime```<br>
 ```calendar```<br>
 ```random```<br>
 ```warnings```<br>

- Pre Installations: <br>
 ```pip install SpeechRecognition```<br>
 ```pip install PyAudio``` or ```conda install PyAudio```<br>
 ```pip install gTTS```<br>
 ```pip install wikipedia```<br>
 
- <a href="https://pypi.org/project/SpeechRecognition/">SpeechRecognition</a>: 
     Library for performing speech recognition, with support for several engines and APIs, online and offline.<br>
- <a href="https://pypi.org/project/gTTS/">gTTS</a>: 
     gTTS (Google Text-to-Speech), a Python library and CLI tool to interface with Google Translate text-to-speech API<br> 
- <a href="https://pypi.org/project/PyAudio/">PyAudio</a>: 
     Bindings for PortAudio v19, the cross-platform audio input/output stream library.<br>
- <a href="https://pypi.org/project/wikipedia/">Wikipedia</a>: 
     Wikipedia API for Python<br>
     
<img src="speech_recog.png"/><br><br>

- Working: <br>
     Wake up immediately on saying 'hey' **or** 'jarvis'.
     Give commands like 'time','date' or 'who is' whatever you want to know.
     **Close** by saying 'bye' or 'close'.<br>
------------------------------------------------------------------------------------------------------------------------------------------------

- Checking: <br>

**You:** Hey what is time right now.<br> 

**Response:** Hello Time is: 8:16:50<br> 

**You:** Hey what is date today.<br> 

**Response:** Hey Today is Saturday 17th october, 2020<br>

**You:** Jarvis who is albert einstein.<br>

**Response:** Albert Einstein (/ˈaɪnstaɪn/ EYEN-styne;[4] German: [ˈalbɛʁt ˈʔaɪnʃtaɪn] (About this soundlisten); 14 March 1879 – 18 April 1955)        was a German-born theoretical physicist[5] who developed the theory of relativity, one of the two pillars of modern physics (alongside          quantum mechanics).[3][6]:274 His work is also known for its influence on the philosophy of science.[7][8] He is best known to the general      public for his mass–energy equivalence formula E = mc2, which has been dubbed "the world's most famous equation".<br>

**You:** Jarvis bye<br>
