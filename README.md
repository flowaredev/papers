# A Real-time Clustering Scheme using Coordinate Density for 3D Localization

## Abstract

The demand for indoor localization technology in the field of automation is growing at a very high rate. Typical examples include logistics automation and construction safety management. In general, the most used technique in the real-time localization field is trilateration. However, when the trilateration method is used, the performance of the sensing data is greatly affected by the radio frequency environment of the surrounding environment, so errors occur a lot in the measured data. If these errors can be eliminated, the performance of localization will be improved. In this paper, we propose a real-time clustering scheme using coordinate density for 3D localization in order to improve this problem.

## 수정사항 리스트

- [x] 중반까지 실내위치측위 이야기를 죽 하다가 3D Localization용 Real-time Clustering Scheme을 제안한다고 했는데, 실내 또는 실외 모두 적용되는 것인지 아니면 실내용에 적용되는 것인지에 대해 불분명합니다. 논조로 보았을때 실내용 인듯 한데 확인바랍니다.
- [x] 기본적으로 Clustering Scheme이 왜 필요한지에 대한 논리적 배경설명이 전혀 없습니다. (간단한 정도로..)
- [x] 기존의 방법의 문제점을 구체적으로 정의하고, INTRODUCTION에서 설명한 Clustering Scheme을 이용한 설계 기본 방향을 제시해주기 바람
- [x] 그림이 전반적으로 너무 크니 축소해주기 바랍니다.
- [x] Fig. 6-9는 본문에서 설명은 거의 없고, 기계적으로 표시만 하였습니다. 이 그림에 대한 충분한 의미에 대한 설명을 해주기 바랍니다.
- [x] 레퍼런스 3개면 너무 작으로 적어도 7개 정도는 확보 바랍니다.
- [x] II. RELATED STUDIES 추가: 참고문헌에 있는 자료 중 본인의 논문에 관련된 가장 중요한 내용을 요약
- [ ] Clustering method using the density of coordinates 부분이 제일 핵심인데, Fig. 2는 너무 단순한 개념에 대한 그림입니다. 기본적으로 제안하려는 scheme의 모델을 제시해야 합니다.
- [ ] Figure 4의 설명이 거의 없는데 설명을 충분히 해주기 바랍니다.
- [ ] 3.A. The developed localization system가 갑자기 등장하는데, 앞의 Introduction이나 어디에도 설명이 없으니 추가바랍니다
- [ ] 3.B. Performance results of localization method -> Experimentation Results
- [ ] Table I를 설명하면서 결과만 제시하였는데, 이 결과의 의미가 무엇인지를 충분히 설명바랍니다.
- [x] 3.B. Performance results of localization method 에서 "The performance evaluation of localization techniques is 1) when there is no evaluation method; 2) when only the clustering method is applied; 3) The clustering method and the minimum distance method were divided into three cases."는 왜 있나요?
- [ ] 그리고 영어내용에 문법적으로 맞지 않는 부분이 많습니다. 문장 하나하나 읽어보고 수정해야 합니다.

## How to compile

- Install MikTex (<https://miktex.org/howto/install-miktex>)
  - Option
    - Install Visual Studio Code & LaTex Workshop Extension
