# PneumoniaPrediction
A predictive model designed to discern the presence or absence of pneumonia in a chest X-ray image

Statement : When converted to greyscale, pneumonic images appear to be more cloudy and fuzzy whereas non-pneumonic images are more clear.
The model predicts the fuzziness and classifies it as pneumonia


NORMAL SET OF LUNGS
![NormalLungs](https://github.com/Pule720/PneumoniaPrediction/assets/85259364/b4c3faf3-600d-40ac-a9c8-bb5810c53e5a)



PNEUMONIC SET OF LUNGS
![pneumonicLungs3](https://github.com/Pule720/PneumoniaPrediction/assets/85259364/975680e0-f983-4f99-8b5b-a0b5ed2b2efd)


An interface was designed using gradio to allow users to submit images (chest x-rays) to heck for the presence of Pneumonia. The probability of the presence of Pneumonia is 
returned as json or python dictionary

INTERFACE
<img width="930" alt="Screenshot 2023-04-10 015104" src="https://github.com/Pule720/PneumoniaPrediction/assets/85259364/b4452d96-e452-44f9-88c7-358f2c9499ba">



