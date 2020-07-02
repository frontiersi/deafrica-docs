# deafrica-docs
Manuals for Digital Earth Africa

To build a copy:
```
git clone https://github.com/frontiersi/deafrica-docs.git
cd deafrica-docs
conda create -c conda-forge -n deafrica-docs --file requirements.txt
conda activate deafrica-docs
pip install -r requirements.txt
make html
open _build/html/index.html
```
