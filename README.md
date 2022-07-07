# DIGIMAP Group 6 DYNAMIC DEBLUR
Implementation of [Dynamic Scene Deblurring with Parameter Selective Sharing and Nested Skip Connections](https://github.com/firenxygao/deblur) by Hongyun Gao, Xin Tao, Xiaoyong Shen, Jiaya Jia.

### Members:
- Miguelabryne Dela Cruz
- Anna Patricia Desembrana
- Clarissa Mandadero
- Alessandro Miguel Zapanta

### Requirements:
1. Python
2. Numpy
3. Tensorflow
4. Tf_slim
5. opencv-python

### Usage Guide:
We are experiencing issues in the deployment due to the **girth** of the model, so please bear with us and make do with a local version

Make sure you have pip installed. If not, you may run the following in your command line:
1. Run `curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py`
2. Run `python get-pip.py`

Running locally is pretty simple, just follow these steps:
1. Clone the repository.
2. Move to the root directory
3. Run `pip install -r requirements.txt`
3. Run `python app.py --gpu=0` on a terminal
- Feel free to remove `--gpu=0` if you feel that your gpu can run the model, otherwise the default is cpu.
4. Paste `http://127.0.0.1:5000` in your web browser. Please wait as loading the app may take some time. When you see the message: `* Running on https://127.0.0.1:5000` 

----------------**it's very cool we promise, fr fr no cap**----------------

