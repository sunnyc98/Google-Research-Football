# Google-Research-Football

This code trains an agent to play in the Google Reasearch Football environment. This environment is challenging in that it has stochastic behavior (randomness in both the environment and the AI players' actions), and that it supports multi-agent mode where each player of a team can be simultaneously controlled by its corresponding agents. 
<p align="center">
  <img width="800" height="300" src="https://user-images.githubusercontent.com/97519387/195132179-35b4a49e-506a-4106-bfe8-55ead013e19a.png">
</p>

It supports multiple observation types, such as the simple115 (a (115,) dimensional vector), pixels_gray (simplified pixels) or the SMMWrapper.


We experimented on which observation type showed the best learning results, and chose the SMM wrapper (4 stacked). Our basic settings were as shown below.

<p align="center">
  <img width="800" height="370" src="https://user-images.githubusercontent.com/97519387/195132757-5ca67ba7-ca3a-433e-9fce-657dea8b8023.png">
</p>

After loads of trial and errors, we devised the following final strategies that seemed optimal to train our agent.
<p align="center">
  <img width="700" height="300" src="https://user-images.githubusercontent.com/97519387/195132681-7c9c90a3-9325-4553-85c2-3d86280ecc84.png">
</p>

Some evaluation results are very briefly shown below:
<p align="center">
  <img width="350" height="240" src="https://user-images.githubusercontent.com/97519387/195133440-cae53a75-a52e-41da-908b-366001ca3095.png"> <img width="400" height="240" src="https://user-images.githubusercontent.com/97519387/195133257-d66a3c2d-6d12-425b-a28b-8e5dc7961a01.png">
</p>
