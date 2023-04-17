# tmc_wrs_gazebo

## 前提条件
Tidy UpのGazebo環境になります。

## 前提条件
[docker_hsr_ws](https://github.com/TeamSOBITS/docker_hsr_ws)のコンテナであること。 

## 動作確認（シミュレータ）
以下のコマンドをコンテナの端末で実行してください。
```
$ roslaunch tmc_wrs_gazebo_launch tidyup_wrs2020.launch
```
> ** Warning ** \
> 実環境とGazeboで初期位置の座標が異なります。\
> 実機で開発を行う場合はmapとlocation_poseを別に作成してください。
