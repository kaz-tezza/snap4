# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added
- nothing.

## [4.1.0] - 2024-09-30
### Added
- TesseractOCR機能ツールを追加
- Editor2, Editor3をOption設定に追加。
- グリップサイズ、背景色をOpthion設定に追加。
- ２値化フィルタを追加。
- フィルタ設定変更時に変更内容を一定時間表示。

## [4.0.10] - 2023-06-25
### Added
- グリップサイズをパラメータ化。iniの[Option]GripSize=5
### Fixed
- マウスカーソル非表示で起動するとカーソル表示ができないバグ修正

## [4.0.9] - 2023-02-23
### Added
- 表示言語 日本語対応
- オプションにてスタートアップ登録設定を追加
- SelfTimerモードのカウント表示を追加
### Changed
- 画像ポップアップ表示の拡大縮小時の高画質化(GDI+)
- Realtimeモードで非アクティブを判別できるようつまみの色をグレー化。
- Helpをiniで指定するように変更
- 不随exe等をbinフォルダに移動
### Fixed
- 数字キーショートカット優先されSelftimer数字入力ができないバグ

## [4.0.8] - 2023-01-15
### Changed
- RealTime表示の背景を全透過に変更。WebMeeting等での使用想定し範囲外もマウス操作が利くように。
- 非Realtimeモードのときタスクバーに表示しない。

## [4.0.7] - 2023-01-14
### Added
- 画像ポップアップ表示機能を追加。一時的な画面メモ表示に。
- SnapAreaを保存ができるようにした。(1～5キー)。<br>2か所以上の領域を繰り返しコピーするときに使う。
- MagnifyingGlassで表示する範囲をマウスホイールで増減できるように改良。<br>5 pixelごとにマス目表示。
### Changed
- 拡大率はCtrl＋ホイールで増減できるようにした。
- サイズ指定をCtrl+F→F2に変更。座標指定もできるように変更。
### Fixed
- キャプチャ領域クリア後、マウスドラッグ中のカーソルキーの共同不具合修正。

## [4.0.6] 
### Added
- リアルタイムモードを完全透過にした。
- マウスカーソル表示のON/OFF機能追加。Mキー
### Changed
- ショートカット割り当て変更。ZoomWinをM→Z
### Fixed
- メインデスクトップが右側にある場合(スクリーン左がマイナス座標)の不具合修正

## [4.0.5] 
### Added
- キャプチャ領域サイズの数値指定の機能を追加。
### Fixed
- アプリ保存先パスに半角スペースが含まれていた時にCtrl＋E機能での不具合修正

## [4.0.4] 
### Added
- オプションにマウスカーソルもキャプチャする設定を追加。
### Fixed
- RealTimeモードにて、Nega,白黒反転を設定すると無効であることをメッセージ出力するようにした。
- RealTimeモードにて、保存時の画像取得タイミング変更：保存ダイアログOKクリック時→保存ダイアログ表示直前

## [4.0.3] 
### Added
- キャプチャエリアに、領域サイズを表示するモードを実装。(Sキー)
- 保存してキャプチャ継続するモードを実装。「Save and Continue (Ctrl+Shift+S)」。<br>
  RealTimeモードと併用し、動画やWeb会議画面などの任意のタイミングでキャプチャする。
- 保存してキャプチャ継続での保存先をオプション設定に追加。
- タスクトレイメニューに上記保存先を開く「Open SaveFolder」メニューを追加。
- 同一色領域モード(Spaceキー）中に、Shiftキー+ドラッグでの範囲拡張を実装。
### Fixed
- キャプチャ領域のリサイズ時にマウスカーソルが別モニターに移動する不具合を修正。
- 未選択状態でコピーなどを行うと、リソースエラーが発生する不具合を修正。
     

[Unreleased]: https://github.com/kaz-tezza/snap4/compare/v4.1.0...HEAD
[4.1.0]: https://github.com/kaz-tezza/snap4/compare/v4.0.9...v4.1.0
[4.0.9]: https://github.com/kaz-tezza/snap4/compare/v4.0.8...v4.0.9
[4.0.8]: https://github.com/kaz-tezza/snap4/compare/v4.0.7...v4.0.8
[4.0.7]: https://github.com/kaz-tezza/snap4/compare/v4.0.6...v4.0.7
[4.0.6]: https://github.com/kaz-tezza/snap4/compare/v4.0.5...v4.0.6
[4.0.5]: https://github.com/kaz-tezza/snap4/compare/v4.0.4...v4.0.5
[4.0.4]: https://github.com/kaz-tezza/snap4/compare/v4.0.3...v4.0.4
[4.0.3]: https://github.com/kaz-tezza/snap4/compare/v4.0.0...v4.0.3
