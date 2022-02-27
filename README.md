# 인공지능을 배우기 위한 가상 학습 환경 만들기 2.
## Intel® Distribution of OpenVINO™ Toolkit  <br> 다운로드 및 설치하기      

  인텔 Digital Readiness programs 중 AI for Youth Program의 <br>
  Stage 4. 소셜임팩트 창출하기 / Module 10, Module 11(Use Cases) 실습을 위한 가상 학습 환경 만들기에 대한 도움 자료입니다. 
  
  <a href="https://www.intel.com/content/www/us/en/corporate/artificial-intelligence/digital-readiness-home.html" target="_blank"> Intel® Digital Readiness Programs </a> <br>
  
 - 설치 프로그램 및 버전 : Intel® OpenVINO 2021.4.LTS    
  <br>

## OpenVINO 다운로드 
  
  아래 이미지를 참고하여 OpenVINO 다운로드 사이트에서 Intel® OpenVINO 2021.4.LTS 를 다운로드합니다.
  
  <img src="https://github.com/BrainAI-Lab/openvino/blob/main/openvino-2021.4.lts.JPG" style="width:1400px;height:500px;">

  <a href="https://www.intel.com/content/www/us/en/developer/tools/openvino-toolkit-download.html?operatingsystem=window&distributions=webdownload&version=2021%204.1%20LTS&options=offline" target="_blank"> 다운로드 사이트 링크 </a>
  
## OpenVINO 설치

 - 다운로드 받은 파일을 찾아 설치합니다.
 - 

## OpenVINO 사용 가상 환경 설치
 - 가상 환경 설치
 - openvino-dev pakage 설치 : 참고사이트 https://pypi.org/project/openvino-dev/ <br>
   * python -m venv openvino_env <br>
   * openvino_env\Scripts\activate <br>
   * python -m pip install --upgrade pip <br>
   * pip install openvino-dev[onnx,tensorflow2] <br>
   * mo -h  <br>
   * python -c "from openvino.inference_engine import IECore" 
 

## OpenVINO 사용하기

  OpenVINO를 사용할 때는 먼저 오픈비노 사용 환경(아래 이미지 참고)을 설정해야 합니다. 
  <img src="https://github.com/BrainAI-Lab/openvino/blob/main/openvino-2021.4.lts-01.JPG" style="width:586px;height:307px;">
  
 - (base) C:\WINDOWS\system32\cd\
 - (base) C:\cd BrainAI
 - (base) C:\BrainAI>python -m venv openvino_env
 - (base) C:\BrainAI>openvino_env\Scripts\activate
 - (openvino_env)(base) C:\BrainAI>python -m pip install --upgrade pip
 - (openvino_env)(base) C:\BrainAI>pip install openvino-dev[onnx,tensorflow2]
 - (openvino_env)(base) C:\BrainAI>mo -h
 - (openvino_env)(base) C:\BrainAI>python -c "from openvino.inference_engine import IECore" 
 - (openvino_env)(base) C:\BrainAI>jupyter lab


## OpenVINO Use Cases 다운로드 

  A collection of ready-to-run Jupyter notebooks for learning and experimenting with the OpenVINO™ Toolkit. 
  
  The notebooks provide an introduction to OpenVINO basics and teach developers how to leverage our API for optimized deep learning inference.
  
  https://github.com/openvinotoolkit/openvino_notebooks
  
  
### 수고하셨습니다.
  
 
