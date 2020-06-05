<h1>Smart Suspect Tracking</h1>

<h3>Instruction to run the Project:</h3>

<b>Initialize Website</b>
<ol>
<li>Install XAMPP</li>
<li>Copy the Web folder to htdocs folder in XAMPP root</li>
<li>Open XAMPP Control Panel and turn on Apache Server</li>
<li>Now go to 127.0.0.1/Web or localhost/Web/.</li>
<li>The website is functional</li>
</ol>

<b>Face Detection</b>
<ol>
<li>Open the face detection module</li>
<li>Install all dependencies (face_detection, cv2, etc.)</li>
<li>Run the module</li>
<li>You can see updates in the website</li>
</ol>

<b>Anomaly Detection</b>
<ol>
<li>Download the dataset from https://visionlab.uncc.edu/download/summary/60-data/477-ucf-anomaly-detection-dataset or https://www.dropbox.com/sh/75v5ehq4cdg5g5g/AABvnJSwZI7zXb8_myBA0CLHa?dl=0</li>
<li>Save in the same target folder</li>
<li>Change the path files in training.py, testing.py and gui.py</li>
<li>Run training.py and testing.py consequtively (PS: We have already stored trained model in weights_L1L2.mat so you need not train and test again).</li>
<li>Run gui.py</li>
<li>Select the example video from dataset whose c3d features are aready extracted. (A few samples with c3d features already extracted are present in the SampleVideos folder).</li>
</ol>