# Time Series Analysis with Pandas

19년 1월 24일 T-Academy 에서 진행한 강좌에 사용된 자료입니다. 해당 강좌는 [Youtube](https://www.youtube.com/playlist?list=PLfknNs5QQyrXp7yuslfB5g_Yylj3Rz2fy) 에서 보실 수 있습니다. 

## Requirements for running tutorial

- Python version 3
- `pandas` version or later
- `numpy` version 1.15.4 or later
- `matplotlib` version 3.0.2 or later
- `seaborn` version 0.9.0 or later
- `pandas` version 0.23.4 or later
- `scikit-learn` 0.20.2 or later
- `jupyter` version 1.0.0 or later
- `statsmodels` version 0.9.0 or later

위 패키지들을 [conda](http://conda.pydata.org/docs/intro.html)를 통해 설치하길 권장합니다. conda 설치 후 아래 커맨드를 실행하면 필요한 모든 패키지들이 설치된 파이썬 환경을 만들 수 있습니다.

```bash
conda create --name tsa python=3
conda install pandas jupyter seaborn scikit-learn statsmodels
```


## Setup instruction

1. 프로젝트를 clone 합니다:
    ```bash
    git clone https://github.com/midnightradio/tsa-tutorial.git
    ```

2. Python 3 환경이 필요합니다. 되도록 [conda](http://conda.pydata.org/docs/intro.html)를 설치하길 권장합니다.

3. 아래 커맨드로 After that, install the environment for this hands-on by running:
    ```bash
    cd tsa-tutorial/
    conda env create --file environment.yml
    ```

4. Anaconda 를 사용하면 이미 Jupyter Notebook 이 설치되어있으므로 다음 단계로 넘어갑니다. (_Miniconda users only_) 생성된 환경(`tsa`)에서 `conda install jupyter` 를 실행해서 Jupyter Notebook 을 설치할 수 있습니다. 

5. 생성한 환경을 활성화하기 위해 `source activate tsa` 또는 `conda activate tsa` 를 실행합니다. 그리고 아래 커맨드를 실행해서 새로운 `iptyhon` 커널을 설치합니다:
    ```bash
    python -m ipykernel install --name tsa --user
    ```

6. 마지막으로 Jupyter Notebook 을 실행합니다.
    ```bash
    jupyter notebook --port=8888
    ```
그리고 URL `localhost:8888` 을 브라우져에 입력해서 노트북에 접속합니다. (`8888` 포트가 이미 점유되었다면 Jupyter Notebook 은 자동으로 다른 포트를 이용하게 됩니다. 시작 시 로그를 살펴보세요.)

## Index

- [01. Datatime Index](http://nbviewer.ipython.org/github/midnightradio/tsa-tutorial/blob/master/01.%20Datetime%20Index.ipynb)
- [02. Time Resampling](http://nbviewer.ipython.org/github/midnightradio/tsa-tutorial/blob/master/02.%20Time%20Resampling.ipynb)
- [03. Time Shifting](http://nbviewer.ipython.org/github/midnightradio/tsa-tutorial/blob/master/03.%20Time%20Shifting.ipynb)
- [04. Rolling and Expanding](http://nbviewer.ipython.org/github/midnightradio/tsa-tutorial/blob/master/04.%20Rolling%20and%20Expanding.ipynb)
- [05. Bollinger Bands](http://nbviewer.ipython.org/github/midnightradio/tsa-tutorial/blob/master/05.%20Bollinger%20Bands.ipynb)
- [06. Timezone](http://nbviewer.ipython.org/github/midnightradio/tsa-tutorial/blob/master/06.%20Timezone.ipynb)
- [07. Visualizaing Time Series Data](http://nbviewer.ipython.org/github/midnightradio/tsa-tutorial/blob/master/07.%20Visualizing%20Time%20Series%20Data.ipynb)
- [08. ETS Decomposition](http://nbviewer.ipython.org/github/midnightradio/tsa-tutorial/blob/master/08.%20ETS%20Decomposition.ipynb)
- [09. Forecasting Models](http://nbviewer.ipython.org/github/midnightradio/tsa-tutorial/blob/master/09.%20Forecasting%20Models.ipynb)
- [10. ARIMA and Seasonal ARIMA](http://nbviewer.ipython.org/github/midnightradio/tsa-tutorial/blob/master/10.%20ARIMA%20and%20Seasonal%20ARIMA.ipynb)
- [11. ARIMA and Rolling Forecast](http://nbviewer.ipython.org/github/midnightradio/tsa-tutorial/blob/master/11.%20ARIMA%20and%20Rolling%20Forecast.ipynb)
