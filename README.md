# Discord 読み上げbotです

## 起動方法

```
$ sudo docker compose up -d --build
```

## 読み上げ使い方

### 読み上げるチャンネルを登録する

現在のテキストチャンネルを登録する  
/set_read_channel 

現在のテキストチャンネルの登録を解除する  
/unset_read_channel

### VCにbotを参加させる

現在のVCに参加する、/set_read_channelの機能を内包している  
/join

VCから退出する、ユーザーがVCから退出した場合も自動で退出する  
/leave

### 読み上げる
VCにbotが参加している状態で、登録したテキストチャンネルにメッセージを送信すると読み上げます。


### 読み上げ設定

読み上げの音声を変更する  
/set_voice <音声名>  

読み上げの音声のスタイルを変更する  
/set_voice_style <スタイル名>

読み上げの速度を変更する  
/set_speed <速度>  
