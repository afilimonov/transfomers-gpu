## Transformers with M1 GPU


### Pre Requisites

```
conda create -n trnasfomers-m1
conda activate transfomers-m1


### Install pytourch
conda install pytorch torchvision torchaudio -c pytorch-nightly

### Install transformers
curl — proto ‘=https’ — tlsv1.2 -sSf https://sh.rustup.rs | sh
pip install sentence-transformers
```