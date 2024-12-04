# Hikari-TV-EPG
XML EPG for Hikari TV channels

## Overview

This repository contains the XML EPG (Electronic Program Guide) for Hikari TV channels. The EPG provides a schedule of the current and upcoming TV programs, enabling users to easily see what's on and plan their viewing.

Preview: https://dbghelp.github.io/epg.html?file=https://raw.githubusercontent.com/dbghelp/Hikari-TV-EPG/refs/heads/main/hikaritv.xml

## Features

- XML formatted EPG for Hikari TV channels
- Up-to-date information on channel programming
- Easy integration with various applications and services

## Usage

To use the EPG data, you can fetch the XML file from this repository and parse it in your application to display the program schedule.

In your M3U8 playlist, 

1. Change your url-tvg to "https://raw.githubusercontent.com/dbghelp/Hikari-TV-EPG/refs/heads/main/hikaritv.xml":

```#EXTM3U url-tvg="https://raw.githubusercontent.com/dbghelp/Hikari-TV-EPG/refs/heads/main/hikaritv.xml" refresh="3600"```

2. Change your tvg-id to the following for the respective channels:
  
| tvg-id                | Channel Name                                                        |
|-----------------------|---------------------------------------------------------------------|
| hikaritv-ch101        | ひかりＴＶチャンネル                                                |
| hikaritv-ch150        | ショップチャンネル                                                  |
| hikaritv-ch151        | ＱＶＣ                                                             |
| hikaritv-ch153        | ジュエリー☆ＧＳＴＶ                                                |
| hikaritv-ch154        | セレクトショッピング                                                |
| hikaritv-ch155        | ベターライフチャンネル                                              |
| hikaritv-ch181        | ＮＨＫワールド ＪＡＰＡＮ                                           |
| hikaritv-ch182        | 中国テレビ★大富チャンネル                                           |
| hikaritv-ch251        | WOWOWプラス 映画・ドラマ・スポーツ・音楽                           |
| hikaritv-ch252        | ザ・シネマ                                                         |
| hikaritv-ch260        | 日本映画専門チャンネル                                             |
| hikaritv-ch261        | 映画・チャンネルＮＥＣＯ                                            |
| hikaritv-ch280        | スターチャンネル                                                  |
| hikaritv-ch290        | 衛星劇場                                                         |
| hikaritv-ch291        | 東映チャンネル                                                    |
| hikaritv-ch292        | Ｖ☆パラダイス                                                    |
| hikaritv-ch350        | アニマックス                                                     |
| hikaritv-ch351        | キッズステーション                                                |
| hikaritv-ch352        | カートゥーン ネットワーク 海外アニメ国内アニメ                     |
| hikaritv-ch380        | アニメシアターX(AT-X)                                            |
| hikaritv-ch451        | スーパー！ドラマＴＶ　#海外ドラマ☆エンタメ                         |
| hikaritv-ch452        | アクションチャンネル                                              |
| hikaritv-ch455        | ミステリーチャンネル                                              |
| hikaritv-ch460        | ホームドラマチャンネル 韓流・時代劇・国内ドラマ                   |
| hikaritv-ch461        | 時代劇専門チャンネル                                             |
| hikaritv-ch470        | TBSチャンネル1 最新ドラマ・音楽・映画                              |
| hikaritv-ch471        | TBSチャンネル2 名作ドラマ・スポーツ・アニメ                       |
| hikaritv-ch552        | KBS World                                                       |
| hikaritv-ch553        | アジアドラマチックTV（アジドラ）                                   |
| hikaritv-ch554        | MONDO TV                                                       |
| hikaritv-ch555        | 日テレプラス　ドラマ・アニメ・音楽ライブ                          |
| hikaritv-ch556        | テレ朝チャンネル１                                                |
| hikaritv-ch557        | テレ朝チャンネル２                                                |
| hikaritv-ch558        | ファミリー劇場                                                   |
| hikaritv-ch559        | エンタメ〜テレ☆シネドラバラエティ                                 |
| hikaritv-ch560        | フジテレビＯＮＥ スポーツ・バラエティ                              |
| hikaritv-ch561        | フジテレビＴＷＯ ドラマ・アニメ                                    |
| hikaritv-ch562        | フジテレビＮＥＸＴ ライブ・プレミアム                              |
| hikaritv-ch570        | ＫＮＴＶ                                                       |
| hikaritv-ch571        | Mnet                                                          |
| hikaritv-ch650        | スペースシャワーＴＶ                                             |
| hikaritv-ch651        | 100％ヒッツ！スペースシャワーTV プラス                            |
| hikaritv-ch653        | MUSIC ON! TV（エムオン!）                                        |
| hikaritv-ch655        | 歌謡ポップスチャンネル                                           |
| hikaritv-ch750        | ＧＡＯＲＡ ＳＰＯＲＴＳ                                           |
| hikaritv-ch751        | スカイＡ                                                       |
| hikaritv-ch752        | 日テレジータス                                                  |
| hikaritv-ch753        | スポーツライブ＋                                                |
| hikaritv-ch754        | ゴルフネットワーク                                              |
| hikaritv-ch757        | J SPORTS 1                                                    |
| hikaritv-ch758        | J SPORTS 2                                                    |
| hikaritv-ch759        | J SPORTS 3                                                    |
| hikaritv-ch760        | J SPORTS 4                                                    |
| hikaritv-ch761        | ＦＩＧＨＴＩＮＧ ＴＶ サムライ                                    |
| hikaritv-ch766        | CNN U.S.                                                     |
| hikaritv-ch770        | グリーンチャンネル                                             |
| hikaritv-ch771        | グリーンチャンネル２                                           |
| hikaritv-ch772        | ＳＰＥＥＤチャンネル１（競輪ライブ）                             |
| hikaritv-ch773        | ＳＰＥＥＤチャンネル２（競輪ライブ）                             |
| hikaritv-ch774        | 南関東地方競馬チャンネル                                        |
| hikaritv-ch775        | 地方競馬ナインSELECT                                            |
| hikaritv-ch776        | レジャーチャンネル                                              |
| hikaritv-ch812        | ヒストリーチャンネル 日本・世界の歴史＆エンタメ                  |
| hikaritv-ch820        | ディスカバリーチャンネル                                         |
| hikaritv-ch830        | 旅チャンネル                                                   |
| hikaritv-ch831        | ダンスチャンネル by エンタメ〜テレ                                |
| hikaritv-ch832        | 囲碁・将棋チャンネル                                            |
| hikaritv-ch840        | 釣りビジョン                                                   |
| hikaritv-ch841        | パチ・スロ サイトセブンＴＶ                                      |
| hikaritv-ch842        | パチンコ★パチスロＴＶ！                                         |
| hikaritv-ch843        | 刺激ストロングチャンネル                                        |
| hikaritv-ch860        | TBS NEWS                                                     |
| hikaritv-ch861        | BBCニュース                                                  |
| hikaritv-ch862        | 日テレNEWS24                                                 |
| hikaritv-ch863        | CNNj                                                        |
| hikaritv-ch876        | フランス国際放送TV5MONDE                                       |
| hikaritv-ch877        | 日経ＣＮＢＣ                                                  |
