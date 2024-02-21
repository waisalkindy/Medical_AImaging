<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->


<img src="https://raw.githubusercontent.com/rkassila/Medical_AImaging/master/aimaging/interface/images/title_image.png" alt="Medical AImaging" width="1280" align="right">

# Medical AImaging

_A deep learning solution designed for the detection of diseases in Magnetic Resonance (MR) and Computed Tomography (CT) images, utilizing Convolutional Neural Networks (CNN)._

## Project Overview

Trained on the [Rad Image Net dataset](https://www.radimagenet.com), this project is an exploration into medical diagnostics using deep learning. 
Medical AImaging was our Le Wagon bootcamp project focused on detecting 36 diseases across 5 organs. 

### Demo

[Click here](https://youtu.be/I43Ln32OAMs?t=1076&si=Rjq8IJsQYe_u5sY1) to watch the demo.

---
### Built With

- **Tensorflow:** Leveraged as a foundational framework for developing and implementing advanced CNNs.

- **FastAPI:** Independently incorporated to optimize functionality and enhance overall application performance.

- **Streamlit:** Chosen for deployment, providing a user-friendly interface and facilitating a smooth deployment process.

---
## Images

<table>
  <tr>
    <td align="top"><img src="https://raw.githubusercontent.com/rkassila/Medical_AImaging/master/aimaging/interface/images/shap_image.png" alt="Shap" width="500"></td>
    <td align="top"><img src="https://raw.githubusercontent.com/rkassila/Medical_AImaging/master/aimaging/interface/images/ai_vision.png" alt="AI Vision" width="500"></td>
  </tr>
  <tr>
    <td align="center">Organ Detection</td>
    <td align="center">Disease Detection</td>
  </tr>
</table>

--
## How to use ?
<p>
  <i>To be able to test the app, I've created small models : to be able to upload on GitHub, original models being > 2 Gb in total. Those small models performance is poor (46-70% accuracy) and don't perform with GradCAM (AI Vision). I will try to create intermediate versions in the future that will allow better performances and upload in GitHub while maintaining sufficient performance. Normal detection is heavily impacted (see below change in model use). Images displayed on this ReadMe have been made with original models.</i>

- Download the repository
- In terminal : 'pip install -r requirements.txt'
- In terminal : 'run-api' to start the api
- In terminal : 'streamlit run aimaging/interface/main.py' to start the interface and be able to test the app

</p>

<br/>

<p><b>Original models : </b> Organ Classifier (99.9% accuracy) > Disease detection (90~99% accuracy) > Disease classifier (55~90% accuracy)</p>
<p><b>Small models : </b> Organ Classifier (99.9% accuracy) > Disease classifier (46~70% accuracy)</p>

<footer>
</footer>
