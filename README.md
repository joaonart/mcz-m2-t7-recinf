# MCZ-M2-T7-RECINF

<a href="https://colab.research.google.com/github/joaonart/mcz-m2-t7-recinf/blob/master/notebooks/MCZ_M2_T7_RECINF_Python.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

Export Jupyter Notebook to HTML

```bash
from google.colab import drive
drive.mount('/content/drive')
```

```python
!jupyter nbconvert --to html /content/drive/MyDrive/Colab\ Notebooks/MCZ_M2_T7_RECINF_Python.ipynb
```

Export Jupyter Notebook to PDF

```python
!sudo apt-get install texlive-xetex texlive-fonts-recommended texlive-plain-generic
```

```python
!jupyter nbconvert --to pdf /content/drive/MyDrive/Colab\ Notebooks/MCZ_M2_T7_RECINF_Python.ipynb
```
