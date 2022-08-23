https://repository.javeriana.edu.co/bitstream/handle/10554/51109/Ramirez%2C%20W.%20Chavarro%2C%20C.%20Arias%2C%20C.%202020.pdf?sequence=1&isAllowed=y
pagina 25

conda create -n Challenge_Airlines python=3.8.13
conda activate Challenge_Airlines
conda install jupyter
pip install numpy pandas
pip install seaborn matplotlib
pip install sklearn
conda install -c conda-forge keras
pip install tensorflow

import seaborn as sns
import matplotlib.pyplot as plt 

git init
git clone https://github.corp.globant.com/jorgeantonio-lopez/Challenge-Data-Scientist-Airline-Dataframe.git

git remote add origin https://github.corp.globant.com/jorgeantonio-lopez/Challenge-Data-Scientist-Airline-Dataframe.git
git branch -M main
git branch -m main jorge
git push -u origin main

git remote set-url origin ssh://github.corp.globant.com/jorgeantonio-lopez/Challenge-Data-Scientist-Airline-Dataframe.git
git remote set-url origin https://github.corp.globant.com/jorgeantonio-lopez/Challenge-Data-Scientist-Airline-Dataframe.git
git push -u origin
git push --set-upstream jorge 
git push origin refs/remotes/origin/development

git remote set-url origin https://github.corp.globant.com/jorgeantonio-lopez/Challenge-Data-Scientist-Airline-Dataframe.git

git add .
git config core.autocrlf true
