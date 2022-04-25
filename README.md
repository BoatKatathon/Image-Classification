# image-classification
- BY.Katathron Lapwong ชั้นปีที่ 3 
# Thanks
- ขอขอบคุณ Jeff Heaton ที่สอนวิธีการใช้งาน Tensorflow ติดตั้ง library ต่าง ๆ ขอขอบคุณอาจารย์พงศกร เจริญเนตรกุล ในส่วนของตัวอย่าง Code และเป็นที่ปรึกษาขณะ Error 
# ข้อควรระวังในการลง CUDA & CUDNN
- Error ในส่วน Cuda และ cudnn ที่เวอร์ชั่นตรงกันแต่มันไม่ซัพพอร์ทกันให้เปลี่ยนไปใช้ Ver.Cuda 11.2 และ Cudnn เป็น 8.1.1 for 11.2 บางครั้งถึงเวอร์ชั่นจะเหมือนกันแต่มันเข้ากันไม่ได้ถ้าใครติด Error ตอน    กำลัง TrainModel ให้ทำการลองเปลี่ยน Version Cuda และ Cudnn ดูนะครับ 
- จากที่ทำเวอร์ชั่นที่เหมือนกันแต่เข้ากันไม่ได้จะมี Cuda 11.5 Cudnn 8.3.3 for 11.5 
# Video learning Tensorflow Win10-11
- [credit : Jeff Heaton](https://www.youtube.com/watch?v=OEFKlRSd8Ic)
# Software Installation 
- คลาสนี้เน้นทางเทคนิค นักเรียนที่ประสบความสำเร็จจะต้องสามารถคอมไพล์และรันโค้ด Python ที่ใช้ประโยชน์จาก TensorFlow เพื่อการเรียนรู้เชิงลึก
- ติดตั้ง Python, TensorFlow และ IDE บางตัว (Jupyter, TensorFlow และอื่นๆ)
- Use Google CoLab in the cloud
# Step 1: NVIDIA Video Driver
- [NVIDIA Video Driver](https://www.nvidia.com/Download/index.aspx?lang=th)
# Step 2: Visual Studio, C++
- [Visual Studio](https://visualstudio.microsoft.com/)
- ทำการติดตั้ง .NET desktop development
# Step 3: CUDA
- ดูคู่มือการติดตั้ง TensorFlow เพื่อดูว่าต้องใช้ CUDA เวอร์ชันใด
- [Tensorflow](https://www.tensorflow.org/install/gpu)
- จากนั้นดาวน์โหลด CUDA เวอร์ชันนั้น (หรือใหม่กว่า) จากเว็บไซต์ต่อไปนี้
- [CUDA](https://developer.nvidia.com/cuda-toolkit-archive)
# Step 4: CuDNN
- ดูเวอร์ชั่น CUDA ของเราว่าเราติดตั้งเป็นเวอร์ชั่นอะไรแล้วมันลองรับเวอร์ชั่นอะไร
- [CuDNN](https://developer.nvidia.com/rdp/cudnn-archive)
# Step 5: Anaconda/Miniconda3
- สามารถดาวน์โหลด Anaconda ได้จากสิ่งนี้
- [Miniconda3](https://docs.conda.io/en/latest/miniconda.html)
# Step 6: Jupyter
- เปิด Anaconda Prompt(miniconda3) 
- conda install -y jupyter
# Step 7: Environment
- conda create -y --name tensorflow python=3.9
- conda activate tensorflow
# Step 8: Jupyter Kernel
- mkdir project
- cd project 
- mkdir deep_learning
- cd deep_learning
- conda install ipykernel
- python -m ipykernel install --user --name tensorflow --display-name "Python 3.9 (tensorflow)"
- jupyter notebook
# Step 9: Install TensorFlow/Keras
- pip install tensorflow
# Step 10: Testing
- python
 ```javascript
import tensorflow as tf 
print(tf.__version__)
print(len(tf.config.list_physical_devices('GPU'))>0)
 ```
# Step 11: Visual Studio code
- [Visual Studio code](https://visualstudio.microsoft.com/)
## ลง Extensions
 - python
 - pylance
 - jupyter
 - Jupyter Keymap
 - Jupyter Notebook Renderers
### ของตกแต่งใน Vscode
  - vscode-icons
  - Color Highlight
  - One Dark Pro
  - Bootstrap 4, Font awesome 4, Font Awesome 5 Free & Pro snippets
  - Doxygen Documentation Generator
# PIP Installation activate tensorflow
- pip install opencv-contrib-python 
- pip install keras 
- pip install glob 
- pip install matplotlib 
- pip install sklearn 
- pip install seaborn 
- pip install pandas 
- pip install pydot
- pip install graphviz
- conda install graphviz
- conda install python-graphviz
