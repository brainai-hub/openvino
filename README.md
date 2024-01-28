# What is the Pre-trained model?
- Let's think about below the questions:
1. How Green is Large Language Model (LLM) Training? LLM(대형 언어 모델) 훈련은 얼마나 친환경적인가요?
2. How to use AI Sustainably? AI를 지속 가능하게 사용하는 방법은 무엇입니까?
3. How Generative AI affecting Human values? 생성형 AI는 인간 가치에 어떤 영향을 미칠까요?
- What is the pre-trained model?
- What are the benefits of using pre-trained models?

## Intel® Distribution of OpenVINO™ Toolkit      

<a href="https://www.intel.com/content/www/us/en/corporate/artificial-intelligence/digital-readiness-home.html" target=_blank> Intel® Digital Readiness Programs </a>  중 AI for Youth Program의 <br>
  Stage 4. 소셜임팩트 창출하기 / Module 10, Module 11(Use Cases) 실습에 활용되고 있습니다. 
  
 - 설치 프로그램 및 버전 : Intel® OpenVINO 2023.3.3  참고 사이트: [https://docs.openvino.ai/2023.3.3/index.html](https://docs.openvino.ai/2023.3/home.html target="_blank")
 
   <img src="https://docs.openvino.ai/2023.3/_images/ov_homepage_diagram.png">

 1. OpenVINO 다운로드
 2. OpenVINO 설치
 3. OpenVINO 환경 초기화
 4. OpenVINO 모델 및 Use Cases(OpenVINO notebook) 다운로드
 
  <br>

## 1. OpenVINO 다운로드 
  
  아래 이미지를 참고하여 OpenVINO 다운로드 사이트에서 Intel® OpenVINO 2021.4.LTS 를 다운로드합니다.
  
  <a href="https://drive.google.com/file/d/1KecP36hWjV-hvbm8CaO77UzxKElRhxej/view?usp=sharing" target="_blank"> 다운로드 링크 </a>
  
## 2. OpenVINO 설치

 - 다운로드 받은 파일을 찾아 설치합니다.
 - 참고 링크: https://docs.openvino.ai/2021.4/openvino_docs_install_guides_installing_openvino_windows.html#install-openvino 

  <img src="https://docs.openvino.ai/2021.4/_images/openvino-install-windows-01.png">


## 3. OpenVINO 환경 초기화(OpenVINO environment initialized)

   오픈 비노를 사용할 때는 오픈비노 환경 초기화가 되어 있어야 합니다. 다음 순서대로 오픈비노 환경 초기화 후 Jupyter lab을 실행합니다. <br>
   참고 링크: https://docs.openvino.ai/2021.4/openvino_docs_install_guides_installing_openvino_windows.html#set-the-environment-variables
   
   <b>선택 1.</b> 아래 이미지 내용과 설정 과정을 참고하여 직접 오픈비노 환경을을 초기화할 수 있습니다.
   
 <img src="https://github.com/BrainAI-Lab/openvino/blob/main/openvino-2021.4.lts-01.JPG" style="width:633px;height:268px;">
 
 
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
 - (BrainAI) C:\BrainAI\jupyter lab

  <b>선택 2.</b> 제공되는 배치 파일을 다운 받아 사용할 수 있습니다. 
  
  * 파일 다운 로드 링크: https://github.com/BrainAI-Lab/openvino/blob/main/openvino_initialize.zip 
 
 - 다운로드 파일을 압축을 풀어 C:\BrainAI\ 폴더로 옮긴다. 
   가상 환경 Command 창에서 
 - (BrainAI) C:\WINDOWS\system32>cd\
 - (BrainAI) C:\>cd BrainAI
 - (BrainAI) C:\>cd BrainAI\openvino_initialize.bat <br>
   * 아래 내용이 출력되면 아무 키나 누릅니다. <br>
    Python 3.8.12 <br>
    [setupvars.bat] OpenVINO environment initialized <br>
    계속하려면 아무 키나 누르십시오 . . .
    
 - (BrainAI) C:\BrainAI>jupyter lab
  * Jupyter lab에서 다음 명령 실행 후 에러 없으면 정상적으로 설치된 것입니다.<br>
  [  from openvino.inference_engine import IECore  ] <br>
  
<img src="https://github.com/BrainAI-Lab/openvino/blob/main/openVINO.JPG" style="width:586px;height:268px;">
  

## 4. OpenVINO 모델 및 Use Cases(OpenVINO notebook) 다운로드

  - OpenVINO™ Toolkit을 활용한 Use Cases를 다운로드 받아 직접 배워볼 수 있습니다.    
    * 추후 제공
    * 참고 사이트: https://github.com/openvinotoolkit/openvino_notebooks/tree/2021.4/notebooks

  - OpenVINO 모델을 다운받을 수 있습니다. 
    * 참고 링크: https://storage.openvinotoolkit.org/repositories/open_model_zoo/
  
### 수고하셨습니다.
  
 
