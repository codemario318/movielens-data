# MovieLens 데이터셋 구조 확인

Grouplens의[MovieLens](https://grouplens.org/datasets/movielens/latest/)을 이용하여 프로젝트를 구성하기 전 구조를 확인합니다.  

데이터셋의 기본적인 설명은 [링크](https://files.grouplens.org/datasets/movielens/ml-latest-small-README.html)에 상세히 나와있습니다.   


## 데이터 셋 준비
[MovieLens](https://grouplens.org/datasets/movielens/latest/) 데이터를 내려받아 `dataset` 디렉터리에 압축 해제 해주세요.
```bash
mkdir dataset
unzip {file_path}/archive.zip -d ./dataset
```

## 분석 환경

Jupyter notebook을 활용하여 기본적인 데이터들을 확인했습니다.  

의존성 파일도 첨부하였으니 직접 코드를 실행해보고 싶다면, 이용하여 환경을 구성하시면 됩니다.  

참고를 위해 저의 개발 환경을 어떻게 구성하면 되는지 남깁니다.  

### 분석 환경 준비

저는 Anaconda를 이용해서 분석 환경을 구성하였습니다.

> Miniconda 환경으로 설치하셔도 충분합니다.
- [Installing miniconda](https://docs.anaconda.com/free/miniconda/miniconda-install/)

```bash
conda env create -f requirements.txt
conda activate movies
```

### notebook 실행

환경 구성과 데이터 셋이 준비되었다면 아래 명령을 실행하여 Jupyter Notebook을 이용해 확인할 수 있습니다.

```bash
jupyter notebook
```

VSCode, Pycharm 같은 IDE는 `.ipynb` 파일을 즉시 실행할 수 있어서 의존성 설치를 완료하셨다면 IDE를 통해 바로 확인할 수 있습니다.

나머지 이용법은 [Jupyter Notebook](https://docs.jupyter.org/en/latest/)을 확인해주세요.
