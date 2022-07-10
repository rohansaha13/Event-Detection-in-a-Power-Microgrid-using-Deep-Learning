# Event-Detection-in-a-Power-Microgrid-using-Deep-Learning
Greetings!

We’re Rishav Singh, Rohan Saha & Souvik Karmakar of the Department of Electrical Engineering [B.Tech’2020-24], Indian Institute of Technology, (Banaras Hindu University) Varanasi. 

This is the README.doc for this Drive : Event Detection in a Power Microgrid using Deep Learning-EE272 Exploratory Project-RishavRohanSouvik

This Drive contains all the Resources utilized in our Exploratory Project EE272 - Event Detection in a Power Microgrid using Deep Learning. The purpose of this README.doc is to familiarize the user/viewer with this Drive & its Contents, so they can understand our Project better.

Contents of this Drive :

[1]. Exploratory Project PDF - 
This PDF contains all of our Ideas, Approaches, Reasoning & Models. We’ve explained our Entire Project, Models & Codes in detail and this PDF was pitched in front of a Panel of 3 Professors from the Department of Electrical Engineering, IIT(BHU), Varanasi, for Evaluation.
Event Detection in a Power Microgrid using Deep Learning-EE272 Exploratory Project-RishavRohanSouvik.pdf

[2]. Simulink Model -
Our Modelled Small Scale Power Microgrid consists of a Power Grid, Pole-mounted Transformer, Solar Panels, Battery Control, ordinary houses, Scopes for Plots, Circuit Breakers etc. Our Simulink Models are realistic & are based on Simplified Model of a Small Scale Micro-Grid on MATLAB.
We’ve 2 similar Simulink files in our project-
(2i). Exploratory.slx
With the basic Power Grid, Pole-mounted Transformer, Solar Panels, Battery Control, ordinary houses and Scopes for Plots which gives us the Data & Plots of Power, Power Secondary, Power Load [PL], Power Battery & SOC wrt. Time, and
(2ii). Exploratory 2.slx
3 Circuit Breakers are added to the 3 ordinary houses to simulate Events of Fault. We see instantaneous spikes of Secondary Current [Isec] & Power Load [PL] & re-record all the data for these faults with & without Battery Control, which becomes our Dataset to feed to our Deep Learning Model.

[3]. Dataset obtained from Simulink Model -
Dataset Obtained from MATLAB Micro-Grid Model by introducing Sudden Changes in Isec & PL using Circuit Breakers. The Dataset feeds the other Data Points such as Power, Power Secondary, Power Load [PL], Power Battery & SOC wrt. Time to the Deep Learning Model-
     
      (3i).  RawDataset.xlsx
      (3ii). FeaturesToBeTrained.xlsx

[4]. Codebase for Deep Learning Model - 
Exploratory Project Code SRR.ipynb
Our Deep Learning Model Codebase is uploaded on a Google Colab Repository. Our Deep Learning Model consists of basic importing packages, packages to read & train Dataset from Excel/Spreadsheet Format, Data Framing & Appending, Swish Activation Function, our Artificial Neural Network, a Standard Scaler & basic matplotlib.

[5]. Research Papers for Reference -
This Folder contains all the Research Papers we’ve referred to during our Project. These Papers are very well-written & we’re really grateful to their respective well-distinguished Authors.
      (5i). Artificial Neural Network Based Fault Detection and Fault Location in the DC Microgrid
      (5ii). Artificial Neural Network Method for Fault Detection on Transmission Line
      (5iii). Deep Learning based Techniques to Enhance the Performance of Microgrids: A Review
      (5iv). Power flow adjustment for smart microgrid based on edge computing and multi-agent deep reinforcement learning
      (5v). Deep reinforcement learning for energy management in a microgrid with flexible demand



Links of all Resources/References :

[1]. Simplified Model of a Small Scale Micro-Grid on MATLAB

[2]. Dataset Obtained from MATLAB Micro-Grid Model by introducing Sudden Changes in Isec & PL using Circuit Breakers-
      (2i).  RawDataset.xlsx
      (2ii). FeaturesToBeTrained.xlsx

[3]. Artificial Neural Network [ANN] Model Codebase -
      Exploratory Project Code SRR.ipynb

[4]. Research Papers relevant to our Project-
      (4i). Artificial Neural Network Based Fault Detection and Fault Location in the DC Microgrid
      (4ii). Artificial Neural Network Method for Fault Detection on Transmission Line
      (4iii). Deep Learning based Techniques to Enhance the Performance of Microgrids: A Review
      (4iv). Power flow adjustment for smart microgrid based on edge computing and multi-agent deep reinforcement learning
      (4v). Deep reinforcement learning for energy management in a microgrid with flexible demand

[5]. Drive Link with all the Resources Compiled (README.doc, Codebase, Simulink Model, Papers, etc.)
Event Detection in a Power Microgrid using Deep Learning-EE272 Exploratory Project-RishavRohanSouvik

