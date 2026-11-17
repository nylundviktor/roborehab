conda env export > system-analysis.yml

conda env create -f system-analysis.yml



conda activate system-analysis

jyputer notebook









conda activate labelstudio

conda env export > label.yml



pip install label-studio

label-studio

