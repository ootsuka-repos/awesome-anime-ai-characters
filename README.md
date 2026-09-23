# Awesome Anime AI Characters

アニメ・二次元系の**会話できるAIキャラクター**を作る／動かすためのGitHubリポジトリ集。Live2DやVRMの姿を持つデスクトップ伴侶・AI VTuberを中心に、キャラクター対話とアバター実装に直接役立つものを選んでいます。

- [Live2D・2Dキャラクターとの対話](#live2d2dキャラクターとの対話)
- [AI VTuber・配信](#ai-vtuber配信)
- [VRM・3Dキャラクターとの対話](#vrm3dキャラクターとの対話)
- [キャラクター会話・ロールプレイ](#キャラクター会話ロールプレイ)
- [アバター表示・アニメーション部品](#アバター表示アニメーション部品)
- [探し方・掲載基準](#探し方掲載基準)

> **注意**: リンク先のコード・モデル・音声・キャラクター素材の権利はそれぞれ別です。掲載は動作・安全性・商用利用の保証ではありません。導入前に各リポジトリのライセンス、同梱素材と外部APIの利用条件を確認してください。特に版権キャラクターのモデルや声の再利用には注意が必要です。

## Live2D・2Dキャラクターとの対話

- [Project AIRI](https://github.com/moeru-ai/airi) — Live2D/VRMを表示し、音声で会話できるAIキャラクタープロジェクト。Webとデスクトップ向けで、ゲーム連携も扱う。
- [Open-LLM-VTuber](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber) — Live2DアバターとLLM・音声認識・音声合成をつなぐ会話アプリ。Web/デスクトップ、ローカルモデル構成やデスクトップペット表示に対応。
- [Soul of Waifu](https://github.com/jofizcd/Soul-of-Waifu) — Live2D/VRMのキャラクターとテキスト・音声で交流するWindows向けアプリ。キャラクター記憶とRPGモードも備える。
- [ChatWaifu Mobile](https://github.com/Voine/ChatWaifu_Mobile) — Android向けの二次元キャラクター会話アプリ。Live2D表示、端末上のVITS音声合成とSherpa音声認識を組み合わせる。付属モデルの商用利用は禁止と明記されている。
- [my-neuro](https://github.com/morettt/my-neuro) — 交換可能なLive2Dモデル、音声・性格を持つAIデスクトップ伴侶の制作ワークベンチ。ローカルLLM、音声会話、配信連携を扱う。
- [Persona Engine](https://github.com/elevenyellow/handcrafted-persona-engine) — マイク入力→LLM→TTS→Live2Dの発話・表情同期を統合。透明デスクトップオーバーレイとOBS向け出力があり、Windows x64とNVIDIA CUDAが必要。
- [Project N.E.K.O.](https://github.com/Project-N-E-K-O/N.E.K.O) — Live2D/VRM/MMDなどのキャラ表示にテキスト・音声・画像入力、持続記憶とエージェント機能を組み合わせる。機能ごとの環境・モデル対応は異なる。
- [EchoBot](https://github.com/KdaiP/EchoBot) — Live2DキャラとのWeb音声対話と、別系統で動くファイル操作などのエージェントを統合。QQ/Telegramにも接続できる。
- [Miru](https://github.com/kiyotakali/Miru) — Live2Dデスクトップペット。許可した画面情報、日誌・長期記憶を使って自発的に話しかける。会話用モデルAPIは利用者が設定する。
- [Waifu Companion](https://github.com/waifuai/waifu-companion) — ブラウザ上でLive2Dキャラを切り替え、人格設定・表情・会話要約と音声入出力を使える。LLMとの通常会話には外部API設定が必要。
- [小凡AI (virtual-person)](https://github.com/ptghb/virtual-person) — Live2Dの表情・動作とLLM対話、TTS、長期記憶を統合。カメラによる手ぶり・視線連動やデスクトップ表示にも対応。

## AI VTuber・配信

- [Luna AI (AI-Vtuber)](https://github.com/Ikaros-521/AI-Vtuber) — LLM・TTSとLive2Dなどのアバターを接続し、配信コメントへの応答やローカル会話を行う。READMEには商用時の別条件が記載されている。
- [Super Agent Party](https://github.com/heshengtao/super-agent-party) — VRMデスクトップ伴侶、Live2D拡張・VTube Studio連携、キャラクターカードでの複数人会話や配信ボットを備える。
- [z-waif](https://github.com/SugarcaneDefender/z-waif) — ローカルLLMやWhisper/RVCとVTube Studioを連携させるAIキャラ環境。音声会話、ロアブック、過去会話検索を備える。外部ソフトの準備が必要。

## VRM・3Dキャラクターとの対話

2DのLive2Dとは異なる3Dアバターですが、アニメ調キャラクターの対話実装に役立つため分けて掲載します。

- [ChatdollKit](https://github.com/uezo/ChatdollKit) — Unity/VRMで音声対話できるキャラクターを組み立てるSDK。LLM、音声入出力、表情・モーション・リップシンクを統合。
- [ChatVRM](https://github.com/pixiv/ChatVRM) — ブラウザでVRMキャラクターと音声会話するデモ。音声認識、ChatGPT API、音声合成を利用。**2024年にアーカイブ済み**。
- [LocalChatVRM](https://github.com/pixiv/local-chat-vrm) — ChromeのBuilt-in AIとKokoro.jsでブラウザ内のVRM会話を試す技術デモ。**アーカイブ済み**で、対応するChrome環境が必要。
- [Utsuwa](https://github.com/JuiceBoxxGames/utsuwa) — VRMアバターとの会話に音声、意味検索できる記憶、気分・関係性の変化を組み合わせたブラウザ／デスクトップ伴侶。デスクトップ版はベータ。
- [ChatVRM Agent](https://github.com/badhope/ChatVRM-Agent) — VRMをブラウザに読み込み、マイク入力→LLM→TTSの会話を表情・口パクとともに表示。音声入力はWeb Speech API対応ブラウザに依存。

## キャラクター会話・ロールプレイ

アバターがなくても、人格・設定や物語を伴うキャラクター対話を作れるフロントエンドです。

- [SillyTavern](https://github.com/SillyTavern/SillyTavern) — キャラクターの説明・人格・シナリオや会話例を定義してLLMと対話するフロントエンド。単体でLive2D/VRMを表示するアプリではない。
- [Irori](https://github.com/hikariming/irori) — アニメ調キャラクターカードの人格・記憶を持つデスクトップ作業パートナー。文章作成やコーディングに対応。**音声とLive2Dはロードマップ段階**。

## アバター表示・アニメーション部品

**以下はAI会話アプリではありません。** 上のプロジェクトと組み合わせて二次元キャラクターの表示・動きを実装するための部品です。

- [pixi-live2d-display](https://github.com/guansss/pixi-live2d-display) — PixiJS v6からLive2Dモデルを表示・操作するライブラリ。Cubism Coreは別途必要。
- [live2d-widget](https://github.com/stevenjoezhang/live2d-widget) — WebページにLive2D看板娘を表示するウィジェット。モデルは同梱されない。
- [Inochi2D](https://github.com/Inochi2D/inochi2d) — レイヤー分割した2Dイラストをリアルタイムで変形するパペットのSDK・仕様。Live2Dとは別方式。
- [Talking Head Anime 2 Demo](https://github.com/pkhungurn/talking-head-anime-2-demo) — 1枚のアニメキャラ画像から表情・顔向きを操作する研究デモ。音声対話機能はない。

## 探し方・掲載基準

調査の入口: [live2d](https://github.com/topics/live2d) · [vtuber](https://github.com/topics/vtuber) · [anime](https://github.com/topics/anime) · [waifu](https://github.com/topics/waifu) · [virtualassistant](https://github.com/topics/virtualassistant) · [ai-companion](https://github.com/topics/ai-companion) · [chatbot](https://github.com/topics/chatbot) · [digital-human](https://github.com/topics/digital-human)。トピックが付いているだけでは掲載せず、各プロジェクトのREADMEやドキュメントで用途を確認しています（2026-09-23）。

- 対象: アニメ調のキャラクターとAIで会話できる完成アプリ、AI VTuber実装、キャラクター対話環境、およびそのアバター実装に直接使う部品。
- 対象外: 一般的なチャットボット、アニメ作品データベース、画像生成だけのツール、写実的な人物動画専用のデジタルヒューマン。AI非搭載の部品は専用の節に明示。
- 同じプロジェクトは複数トピックにあっても一度だけ掲載。機能は上流の記述に沿った要約であり、ベンチマークや動作検証の結果ではありません。

追加・修正はIssueまたはPull Requestへ。候補のURL、どんなキャラクター対話／アバター機能があるかを示すREADME等の根拠、利用条件の注意点を添えてください。
