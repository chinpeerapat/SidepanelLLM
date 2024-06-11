[日本語](#日本語) | [English](#english)
#### english
# Chrome Extension - Chrome AI Chat

A Chrome extension that allows you to use AI Chat in the Chrome sidepanel. Currently, it only supports the OpenAI API.

I made this because I prefer knowing what prompts are being used.

![alt text](doc/sidepanel1.gif) 

You can insert selected text into the form and chat with it.

![alt text](doc/sidepanel2.gif) 

When you open a YouTube video page and press the button, you can use the subtitle information of the video to chat. This is useful for understanding the summary of the video.

![alt text](doc/sidepanel3.gif)

You can drag and drop images to chat using the images.

There are also features to take screenshots of the screen and insert prompts with a button.

### Requirements

* OpenAI API key and usage fees

### Current Features

* Insert selected text on the screen with a button
* Insert subtitle information from YouTube videos with a button
* Insert all text information from the page with a button
* Insert a screenshot of the screen with a button
* Insert simple prompts with a button

### Limitations

* Cannot read videos or PDFs
* No audio-related features
* Cannot use other AIs like Google's Gemini
* No history functionality

and more...

### Boilerplate Used - Thanks
Chrome Extension Boilerplate with
React + Vite + TypeScript 
https://github.com/Jonghakseo/chrome-extension-boilerplate-react-vite

## Usage

1. Install the extension

2. Right-click the extension button and open the options

![option](doc/option_view.png)

3. Set the API key issued by OpenAI in the API Key field in the options. To prevent key theft, it is recommended to set a limit on the API key.

## Screen Buttons

![sidepanel](<doc/スクリーンショット 2024-06-02 143002.png>)

You can chat from the form at the bottom of the screen.
When you press the buttons above the form, you can embed information from the currently open tab into the form.
From the left, the buttons allow you to insert the selected text, subtitle information from YouTube videos, all text information from the page, and a screenshot of the screen.


#### 日本語
# Chrome Extension - Chrome AI Chat

Chrome のサイドバーでAI Chatができるようになる拡張機能です。現在OpenAIのAPIのみ対応。

どういうプロンプトを入れているかわかりやすいほうが好みなので作りました。

![alt text](doc/sidepanel1.gif) 

ドラッグ選択した文章をフォームに差し込んで会話できます。

![alt text](doc/sidepanel2.gif) 

Youtubeの動画ページを開いてボタンを押すと、動画の字幕情報を使って会話できます。動画の概要なんかを把握するのに使えます。

![alt text](doc/sidepanel3.gif)

画像をドラッグアンドドロップで、画像を使って会話できます。

また他にも画面のスクリーンショットを撮る機能、プロンプトをボタンで差し込む機能があります。

### 使うのに必要なもの

* OpenAIのAPIキーとその使用料金

### 現在できること

* 画面上でドラッグした部分をボタンで挿入
* 動画の字幕情報をボタンで挿入
* 画面全体の文字情報をボタンで挿入
* 画面のスクリーンショットをボタンで挿入
* 簡単なPromptをボタンで挿入

### できないこと

* 動画とかpdfの読み込み
* 音声関連の機能
* GoogleのGeminiなど他のAIの使用
* 履歴機能

等々

### 使用ボイラープレート ありがとう
Chrome Extension Boilerplate with
React + Vite + TypeScript 
https://github.com/Jonghakseo/chrome-extension-boilerplate-react-vite

## 使い方

1. 拡張機能をいれる

2. 拡張のボタンを右クリック、オプションを開く
![option](doc/option_view.png)

3. オプションのAPI KeyにOpen AIで発行したAPIキーを設定する。キーの盗難に備え、APIキーには上限を設定することをお勧めします。


## 画面のボタン

![sidepanel](<doc/スクリーンショット 2024-06-02 143002.png>)

画面下のフォームからチャットができます。
フォーム上部のボタンを押すと、現在開いているタブから情報をフォームに埋め込むことができます。
ボタンは左から、選択部分、Youtube動画の字幕情報、ページ全体のテキスト情報、スクリーンショットを取得できます。

