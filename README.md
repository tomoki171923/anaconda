# anaconda

## OS

macOS Catalina 10.15.7

## install anaconda

```
brew install pyenv
pyenv install anaconda3-5.3.1
pyenv global anaconda3-5.3.1
echo 'source ~/.pyenv/versions/anaconda3-5.3.1/etc/profile.d/conda.sh' >> ~/.zshrc
source ~/.zshrc
```

### create anaconda environment

e.g. python3.8
```
conda create -n py38 python=3.8 anaconda environment
```

### install depended packages into 

e.g.
```
conda install boto3
conda install pyyaml
conda install pandas
conda install termcolor
conda install -c conda-forge python-dotenv
```
confirm
```
conda list -n py38
```

### boot anaconda environment
```
conda activate py38
```

### down anaconda environment
```
conda deactivate
```
