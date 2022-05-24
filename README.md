<p align="center"> <img src="https://user-images.githubusercontent.com/91356865/144049159-1ebbd095-87d2-4a3c-81cb-277cc1d4c7b7.png" width="300"> </p> <p align="center"> Starting Up the AI Environment on a "Full-of-Beans" SandBox </p>

***

# nvidia-sandbox  
nvidia-sandbox は、NVIDIAの学習済みAIモデルの稼働環境・追加学習環境を利用するためのリソースをまとめたリポジトリです。  
nvidia-sandbox の 「sandbox」は、Netflix 韓国ドラマ 「START-UP」 より、すべての開発者のための 地ならし になればという想いから命名されました。  

## 前提条件  
nvidia-sandbox は、 AIモデル最適化を行うための[NVIDIA TAO Toolkit](https://developer.nvidia.com/ja-jp/tao-toolkit)、AIモデル動作環境の[NVIDIA DeepStream SDK](https://developer.nvidia.com/deepstream-sdk)・[NVIDIA TensorRT](https://developer.nvidia.com/tensorrt)の利用を前提としています。  

## Latona における NVIDIAのAIモデル関連リソース整備状況    
下の図において、チェックマークが付いているリソースが、Latonaにおいて(少なくとも1次の)整備が行われたものであり、github上に公開されています。  

![リソース整備状況](documents/NVIDIA_SANDBOX_20220524.drawio.png)

## 各リソースの所在  
各リソースの所在は、次の箇所です。DeepStreamのリソースには、TensorRTが含まれます。  

##### TrafficCamNet

* [trafficcamnet-on-tao-toolkit](https://github.com/latonaio/trafficcamnet-on-tao-toolkit)
* [trafficcamnet-on-deepstream](https://github.com/latonaio/trafficcamnet-on-deepstream)

##### PeopleNet

* [peoplenet-on-tao-toolkit](https://github.com/latonaio/peoplenet-on-tao-toolkit)
* [peoplenet-on-deepstream](https://github.com/latonaio/peoplenet-on-deepstream)

##### DashCamNet

* [dashcamnet-on-tao-toolkit](https://github.com/latonaio/dashcamnet-on-tao-toolkit)
* [dashcamnet-on-deepstream](https://github.com/latonaio/dashcamnet-on-deepstream)

##### FaceDetectIR

* [facedetectir-on-tao-toolkit](https://github.com/latonaio/facedetectir-on-tao-toolkit)
* [facedetectir-on-deepstream](https://github.com/latonaio/facedetectir-on-deepstream)

##### VehicleMakeNet

* [vehiclemakenet-on-tao-toolkit](https://github.com/latonaio/vehiclemakenet-on-tao-toolkit)
* [vehiclemakenet-on-deepstream](https://github.com/latonaio/vehiclemakenet-on-deepstream)

##### VehicleTypeNet

* [vehicletypenet-on-tao-toolkit](https://github.com/latonaio/vehicletypenet-on-tao-toolkit)
* [vehicletypenet-on-deepstream](https://github.com/latonaio/vehicletypenet-on-deepstream)

##### PeopleSegNet

* [peoplesegnet-on-tao-toolkit](https://github.com/latonaio/peoplesegnet-on-tao-toolkit)
* [peoplesegnet-on-deepstream](https://github.com/latonaio/peoplesegnet-on-deepstream)

##### PeopleSemSegNet

* [peoplesemsegnet-on-tao-toolkit](https://github.com/latonaio/peoplesemsegnet-on-tao-toolkit)
* [peoplesemsegnet-on-deepstream](https://github.com/latonaio/peoplesemsegnet-on-deepstream)

##### LPDNet

* [lpdnet-on-tao-toolkit](https://github.com/latonaio/lpdnet-on-tao-toolkit)
* [lpdnet-on-deepstream](https://github.com/latonaio/lpdnet-on-deepstream)

##### LPRNet

* [lprnet-on-tao-toolkit](https://github.com/latonaio/lprnet-on-tao-toolkit)
* [lprnet-on-deepstream](https://github.com/latonaio/lprnet-on-deepstream)

##### FacialLandmarksEstimation

* [facial-landmarks-estimation-on-tao-toolkit](https://github.com/latonaio/facial-landmarks-estimation-on-tao-toolkit)
* [facial-landmarks-estimation-on-deepstream](https://github.com/latonaio/facial-landmarks-estimation-on-deepstream)

##### FaceDetect

* [facedetect-on-tao-toolkit](https://github.com/latonaio/facedetect-on-tao-toolkit)
* [facedetect-on-deepstream](https://github.com/latonaio/facedetect-on-deepstream)

##### BodyPoseNet

* [bodyposenet-on-tao-toolkit](https://github.com/latonaio/bodyposenet-on-tao-toolkit)
* [bodyposenet-on-deepstream](https://github.com/latonaio/bodyposenet-on-deepstream)

##### Multi-Human Parsing

* [multihumanparsing-on-tensorrt](https://github.com/latonaio/multihumanparsing-on-tensorrt)

##### PoseNet Body

* [posenet-body-on-tensorrt](https://github.com/latonaio/posenet-body-on-tensorrt)

##### PoseNet Hand

* [posenet-hand-on-tensorrt](https://github.com/latonaio/posenet-hand-on-tensorrt)

