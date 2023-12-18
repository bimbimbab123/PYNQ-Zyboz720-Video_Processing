# PYNQ Zybo-Z7-20 Video Processing
PYNQ를 사용하여 Zybo z7-20 보드로 영상처리를 수행하는 프로젝트이다.
<br>

---

## 프로젝트 개요
사용자 정의 영상을 입력받아 HDMI로 영상을 출력한다. 주 프로젝트 주제는 opencv에서 제공하는 Haar Cascades 모델을 사용한 face&eyes detection 영상처리이다.

---

### 1. PYNQ 2.7 이미지
* sd card image 출처:
<https://discuss.pynq.io/t/pynq-2-7-for-zybo-z7/4124>
<br>

### 2. Zybo-z7-20 보드 연결 사진
![1702878263 7377648IMG_8132](https://github.com/bimbimbab123/PYNQ-Zyboz720-Video_Processing/assets/154115694/249471c5-fdab-4a5f-91b1-818d719bda96)

### 3. Haar Cascades를 이용한 얼굴과 눈 검출 처리
- 실행파일: final_face_detection_Video.ipynb

#### * 결과 사진
![ClipboardImage_2023-12-18_144624](https://github.com/bimbimbab123/PYNQ-Zyboz720-Video_Processing/assets/154115694/29d7704d-e7f5-4163-a3da-a59c0120d272)

#### * 결과 gif 파일
facedetection_output.gif

---

### 번외.  Canny Edge Detection 필터를 이용한 영상처리
- 실행파일: final_face_detection_Video.ipynb
- 참고사이트: <https://github.com/Xilinx/PYNQ/blob/master/boards/Pynq-Z1/base/notebooks/video/opencv_face_detect_hdmi.ipynb>
  
#### * 결과 사진
![1702623024 2062569IMG_8483](https://github.com/bimbimbab123/PYNQ-Zyboz720-Video_Processing/assets/154115694/ebc8c215-6289-4162-a336-55f4e6007bee)

---

#### - 참고 사이트
1. https://pynq.readthedocs.io/en/v2.1/pynq_overlays/base_overlay.html
2. https://gitlab.com/dorfell/fer_sys_dev/-/tree/master/01_hw/Pynq_Zybo-Z7
3. https://github.com/Xilinx/PYNQ/blob/master/boards/Pynq-Z1/base/notebooks/video/opencv_face_detect_webcam.ipynb
4. https://github.com/Xilinx/PYNQ/blob/master/boards/Pynq-Z1/base/notebooks/video/opencv_filters_hdmi.ipynb
5. https://github.com/ptoupas/amd-open-hardware-23
