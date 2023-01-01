# DRL-Model-to-Optimize-Routing
This code is a application of Graph Neural Network (GNN) to train Agent in Reinfoecment Learning to find best path under SDN network scenario 
To run this code follow the setps 

step 1: 
!pip3 install virtualenv
!virtualenv /content/myenv

step 2 :
import os
path ='/content/myenv'
os.chdir(path)

step 3:
!source /content/myenv/bin/activate 

step 4:
!pip install -r /content/myenv/DRL-Model-to-Optimize-Routing/requirements.txt

step 5:
!pip install -e /content/myenv/DRL-Model-to-Optimize-Routing/gym-environments

step 6:
!python /content/myenv/DRL-Model-to-Optimize-Routing/train_DQN.py

step 7:
!python /content/myenv/DRL-Model-to-Optimize-Routing/parse.py -d ./Logs/expsample_DQN_agentLogs.txt

step 8:
!python /content/myenv/DRL-Model-to-Optimize-Routing/evaluate_DQN.py -d ./Logs/expsample_DQN_agentLogs.txt
