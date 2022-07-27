# Setup

```
conda create --name huggingface python=3.8
conda activate huggingface
pip install --upgrade pip
pip install .
pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu113
cd examples/pytorch/language-modeling
pip install -r requirements.txt
conda deactivate
```
