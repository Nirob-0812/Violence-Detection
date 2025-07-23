<h1>Deep Learning based approach to detect violence</h1>
<h4>We develop a violence detection system using deep learning and Flask. The system processes video footage, identifies violent behavior, and sends an alert email. We created a unique dataset comprising 1000 videos, evenly split between violence and non-violence categories, providing a balanced basis for model training. Frames were extracted from each video, resized to standard dimensions, and normalized, forming the feature set for our models. We employed various models including VGG19, VGG16, MobileNet-v2+LSTM, ResNet-50, and CNN+LSTM. Our best performing model was CNN+LSTM with an accuracy of 98%, closely followed by MobileNet-V2+LSTM at 95%. We developed a Flask application as an interface for our system, enabling real-time violence detection and enhancing user interaction. Our system identifies violent incidents, sends alert emails with detected frames and also violence location, and significantly improves response times.<br><br>
    
Dataset: You can find our [Dataset](https://www.kaggle.com/datasets/mehedihasannirob/violence-detection-1000-videos) on kaggle.
</h4>
<h3>Accuracy Analysis of Different models</h3>
<h5>The results are visualized in a bar chart, making it easy to compare the performance of the different models. Each bar represents a model, and the height of the bar corresponds to the accuracy of that model.</h5>
<div style="text-align:center;">
    <img src="https://github.com/Nirob-0812/Violence-Detection/assets/75689692/1fca968a-b7ab-46ef-a114-7d451a8f6c8a" alt="Image Preview" width="700" height="400">
</div>
<h3>Home page of our flask application</h3>
<h5>when we run our project then we can show this interface</h5>
<div style="text-align:center;">
    <img src="https://github.com/Nirob-0812/Violence-Detection/assets/75689692/53c78495-62de-49af-ab06-8f278a1ddc12" alt="Image Preview" width="700" height="400">
</div>

<h3>This is the Preview page of our Flask application</h3>
<h5>On our flask application we have feature where we can preview any uploaded video</h5>
<div style="text-align:center;">
    <img src="https://github.com/Nirob-0812/Violence-Detection/assets/75689692/4fe54f72-dfca-45b0-887e-457b7c3da108" alt="Image Preview" width="700" height="400">
</div>
<h3>In this interface we can see realtime result of violence of non-violence from each frame</h3>
<h5>On our application we have a submit button. when we press this button then our model starting to detect violence or non violence from the uploaded video</h5>
<div style="text-align:center;">
    <img src="https://github.com/Nirob-0812/Violence-Detection/assets/75689692/d03514ac-5d15-42e0-af84-312e2ea76900" alt="Image Preview" width="700" height="400">
</div>
<h3>Automate Mail alert system</h3>
<h5>When our model detect violence and count 10 violence frame for safety then it will send a mail to the author with violence situation and location</h5>
<div style="text-align:center;">
    <img src="https://github.com/Nirob-0812/Violence-Detection/assets/75689692/7719e947-b187-4ce8-b3da-34364545584c" alt="Image Preview" width="700" height="400">
</div>
<h3>For trail I use laptop's webcam</h3>
<h5>This is the main feature of our project that is detect violence or non violence from webcam</h5>
<div style="text-align:center;">
    <img src="https://github.com/Nirob-0812/Violence-Detection/assets/75689692/793c8995-3c7b-4d11-b600-c93d9c931380" alt="Image Preview" width="700" height="400">
</div>


