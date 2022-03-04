# Pre-trained 모델 활용하기
## Intel® Distribution of OpenVINO™ Toolkit      

  인텔 Digital Readiness programs 중 AI for Youth Program의 <br>
  Stage 4. 소셜임팩트 창출하기 / Module 10, Module 11(Use Cases) 실습을 위한 도움 자료입니다. 
  
  <a href="https://www.intel.com/content/www/us/en/corporate/artificial-intelligence/digital-readiness-home.html" target="_blank"> Intel® Digital Readiness Programs </a> <br>
  
 - 설치 프로그램 및 버전 : Intel® OpenVINO 2021.4.LTS  참고 사이트: https://docs.openvino.ai/2021.4/index.html
 
   <img src="https://docs.openvino.ai/2021.4/_static/images/ov_chart.png">

 1. OpenVINO 다운로드
 2. OpenVINO 설치
 3. OpenVINO 환경 초기화
 4. OpenVINO 모델 및 Use Cases(OpenVINO notebook) 다운로드
 
  <br>

## 1. OpenVINO 다운로드 
  
  아래 이미지를 참고하여 OpenVINO 다운로드 사이트에서 Intel® OpenVINO 2021.4.LTS 를 다운로드합니다.
  
  <img src="https://github.com/BrainAI-Lab/openvino/blob/main/openvino-2021.4.lts.JPG" style="width:1400px;height:500px;">

  <a href="https://www.intel.com/content/www/us/en/developer/tools/openvino-toolkit-download.html?operatingsystem=window&distributions=webdownload&version=2021%204.1%20LTS&options=offline" target="_blank"> 다운로드 사이트 링크 </a>
  
## 2. OpenVINO 설치

 - 다운로드 받은 파일을 찾아 설치합니다.
 - 참고 링크: https://docs.openvino.ai/2021.4/openvino_docs_install_guides_installing_openvino_windows.html#install-openvino 

  <img src="https://docs.openvino.ai/2021.4/_images/openvino-install-windows-01.png">


## 3. OpenVINO 환경 초기화(OpenVINO environment initialized)

   오픈 비노를 사용할 때는 오픈비노 환경 초기화가 되어 있어야 합니다. 다음 순서대로 오픈비노 환경 초기화 후 Jupyter lab을 실행합니다. <br>
   참고 링크: https://docs.openvino.ai/2021.4/openvino_docs_install_guides_installing_openvino_windows.html#set-the-environment-variables
   
 <img src="https://github.com/BrainAI-Lab/openvino/blob/main/openvino-2021.4.lts-01.JPG" style="width:586px;height:307px;">
 
 - (BrainAI) C:\WINDOWS\system32>cd\
 - (BrainAI) C:\>cd "Program Files (x86)"
 - (BrainAI) C:\Program Files (x86)>cd Intel
 - (BrainAI) C:\Program Files (x86)\Intel>cd openvino_2021.4.689
 - (BrainAI) C:\Program Files (x86)\Intel\openvino_2021.4.689>cd bin
 - (BrainAI) C:\Program Files (x86)\Intel\openvino_2021.4.689\bin>setupvars.bat <br>
    Python 3.8.12
    <b>[setupvars.bat] OpenVINO environment initialized    </b>
 - (BrainAI) C:\Program Files (x86)\Intel\openvino_2021.4.689\bin>cd\
 - (BrainAI) C:\>cd BrainAI
 - (BrainAI) C:\BrainAI>jupyter lab


## 4. OpenVINO 모델 및 Use Cases(OpenVINO notebook) 다운로드

  - OpenVINO™ Toolkit을 활용한 Use Cases를 다운로드 받아 직접 배워볼 수 있습니다.    
    * 참고 링크: https://github.com/openvinotoolkit/openvino_notebooks
  - OpenVINO 모델을 다운받을 수 있습니다. 
    * 참고 링크: https://storage.openvinotoolkit.org/repositories/open_model_zoo/
  
### 수고하셨습니다.
  
 
