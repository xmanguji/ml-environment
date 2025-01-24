# ml-environment
##
```
cd /Users/eugene/Desktop/python-data-processing/opencv
conda activate cv
```


```
conda create --name xxx python=3.9
conda activate xxx
```
```
pip install -r requirements.txt
```
### Create virtual env in Mac OS
```
python3 -m venv myenv1
virtualenv myenv
source myenv/bin/activate
```
```
conda activate myenv
conda deactivate
```

### How to run python fastapi project
```
conda activate myenv
uvicorn main:app --host 127.0.0.1 --port 8000 --reload
```
