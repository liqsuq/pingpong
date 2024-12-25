# pingpong
## 概要

ROS2を検証する際に作った色々な実装スタイルでのsend/callbackのコード

- ping/pong\_obsolete: ROS1スタイルの古い書き方
- ping/pong\_timer: whileループでなくtimerを使用した書き方
- ping/pong\_classify: クラスを使用した書き方
- ping/pong\_executor: エグゼキュータを指定する書き方
- ping/pong\_compo: コンポーネントノードとしての実装
- ping/pong\_compose: コンポーネントノードを使用した書き方
- ping/pong\_qt: GUIを作る用に出力を調整した(と思う)

# Build

```
$ source /opt/ros/****/setup.bash
$ colcon build
```
