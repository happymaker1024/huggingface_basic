# hugging_face_ex
hugging_face_ex

# 가상환경 만들기
```
conda create -n hf_env python=3.10
conda activate hf_env
```
# 라이브러리 설치
```
pip install transformers
pip install sentencepiece
pip install fsspec==2023.5.0
pip install pillow
pip install python-dotenv
```
# 가상환경과 jupyter lab 연동
```
pip install ipykernel
python -m ipykernel install --user --name hf_env --display-name "hf_env"
```