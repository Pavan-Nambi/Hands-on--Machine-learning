okay so in book they used virtualenv pythn

i am using conda


so first as i dont let conda be default i need to activate it

ah see in zsh file last comment if u forgot command (note for myself)


now create new env
```bash
conda create -n hands-on-ml

```

activate it
```bash
conda activate hands-on-ml
```

install pip
```bash
conda install pip
```

install other packages( i use full path idk if it works without it also? idk never tried it)
```bash
/home/pavan/anaconda3/envs/hands-on-ml/bin/pip install jupyter matplotlib numpy pandas scipy scikit-learn
```

run jupyter notebook
```bash
jupyter notebook
```
