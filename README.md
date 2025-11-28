To make new environment and download all of the python libraries:  
```
conda create -n dct python=3.10  
conda activate dct  
pip install -r requirements.txt
```

Make jupyter kernel from environment  
`python -m ipykernel install --user --name=dct --display-name "DCT"`

then run using  
`jupyter notebook`
