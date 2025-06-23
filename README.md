
# FireDataset(火焰数据集)


### **Introduction to the Global Best Fire Visual Detection Dataset and Framework**

**Project Overview**  
Addressing fire detection through machine vision technology is a highly meaningful and practical direction. This project introduces a **global-leading fire detection dataset** and an **open-source detection framework** to empower developers, enterprises, and communities worldwide to deploy intelligent fire detection systems efficiently.

- **Dataset**: [https://github.com/yuanzhongqiao/FireDataset](https://github.com/yuanzhongqiao/FireDataset)  
- **Detection Framework**: [https://www.gitpp.com/detection/project2025062390902](https://www.gitpp.com/detection/project2025062390902)  

---

### **Significance of Machine Vision-Based Fire Detection**

1. **Global Problem, Technological Inclusivity**  
   - Fire is a universal safety hazard, affecting both developed and developing countries.  
   - Machine vision technology, through open-source datasets and collaborative development, can be rapidly deployed globally, reducing fire-related losses and promoting technological equity.  

2. **Efficient and Accurate Detection**  
   - Traditional fire detection methods (e.g., smoke detectors, temperature sensors) may suffer from delays or false alarms.  
   - Machine vision analyzes video streams in real time, enabling earlier and more accurate detection of fires and smoke, thus improving response speed.  

3. **Continuous Learning and Optimization**  
   - Machine learning models can improve detection accuracy through continuous training and optimization.  
   - Global data sharing and model iteration accelerate technological progress, making systems smarter and more reliable.  

---

### **Technical Implementation Path**

1. **Dataset Sharing**  
   - Establish a global fire detection dataset containing images/videos of fires and smoke in various scenarios (e.g., factories, warehouses, forests, residential areas).  
   - Open-sourcing and sharing the dataset lower the barriers to model training and accelerate technology adoption.  

2. **Model Training and Optimization**  
   - Use deep learning models (e.g., YOLO, Faster R-CNN) for fire and smoke detection.  
   - Through continuous learning, models can adapt to fire characteristics in different regions (e.g., color, shape, smoke density), enhancing generalization capabilities.  

3. **Edge Computing and Real-Time Deployment**  
   - Deploy models on edge devices (e.g., cameras, NVRs) to enable real-time detection and alarming.  
   - Edge computing reduces data transmission latency and improves system responsiveness.  

4. **Multimodal Fusion**  
   - Integrate data from other sensors (e.g., temperature, humidity, gas concentration) to enhance detection accuracy and reliability.  

---

### **Value of Open Source and Collaboration**

1. **"From Each According to Their Ability, to Each According to Their Need"**  
   - Open-source projects encourage global developers to participate, contributing code, data, and algorithms.  
   - Every contribution enhances the system, ultimately benefiting all users.  

2. **Lowering Technological Barriers**  
   - Open-source projects provide free code and tools, reducing the technological barriers for enterprises and institutions.  
   - Small and medium-sized enterprises (SMEs) and communities can easily deploy intelligent fire detection systems, improving safety levels.  

3. **Accelerating Technological Iteration**  
   - Collaboration among global developers accelerates technological iteration, driving the application of machine vision in fire detection.  

---

### **Balancing Commercialization and Social Value**

1. **Free Basic Services, Paid Value-Added Services**  
   - Basic functions (e.g., fire detection, alarming) can be open-sourced and free for global users.  
   - Value-added services (e.g., data analysis, customized development, advanced alarming features) can be charged to support the project's sustainability.  

2. **Commercialization in High-Risk Areas**  
   - Provide customized, paid solutions in high-risk areas such as factories, warehouses, and data centers.  
   - Commercial revenue can be reinvested into open-source projects to drive technological progress.  

---

### **Future Outlook**

1. **Technological Proliferation**  
   - With the maturity of machine vision technology and the promotion of open-source projects, intelligent fire detection systems will gradually become ubiquitous globally.  

2. **Significant Societal Benefits**  
   - Reduce life and property losses caused by fires, enhancing overall societal safety levels.  

3. **Ecosystem Co-Creation**  
   - Establish a global community of developers, enterprises, and users to jointly drive the advancement and application of fire detection technology.  

---

### **Conclusion**

Addressing fire detection through machine vision technology is a direction with profound societal significance. Open-sourcing datasets and frameworks can accelerate technology adoption, lower deployment barriers, and benefit global users. Through continuous learning and optimization, model accuracy will improve, ultimately achieving a virtuous cycle of "from each according to their ability, to each according to their need." We hope more developers, enterprises, and institutions will join this endeavor to contribute to global fire safety!  

**Open-Source License**: PKU Open-Source License  
[https://www.gitpp.com/pkuLicense/pku-open-source-license](https://www.gitpp.com/pkuLicense/pku-open-source-license)


# FireDataset(火焰数据集)
___
用于训练火灾和帧检测 AI 的图像数据集
___
<strong> FireDataset 数据集 </strong> 是一个数据集，用于训练机器学习模型识别 Fire、smoke 和 neutral（没有火或烟雾的图像）。这是一个包含大约 105200 张图像和 3 个类的数据集，其中包括：<br>
* Fire 
* Smoke
* neutral 
<br>

### 下载、训练和预测
___
FireDataset数据集 在此存储库的发布部分提供供下载。您可以通过此链接[FireDataset](https://github.com/wengjinfang/FireDataset/releases/tag/v1)跳转下载压缩包.
<br>
或者可以在[Google Drive](https://drive.google.com/file/d/11rN8gLIalZ0RsVuxTMO9FFHX_doLmZ5w/view?usp=drive_link)
### Reqirements
___
* Python 3
* Pytorch
* Numpy
* Matplotlib
* TorchFussion

