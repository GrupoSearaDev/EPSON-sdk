=========================================================================
                 デバイス制御プログラム用のサンプルプログラム

          Copyright Seiko Epson Corporation 2017-2019 All rights reserved.
=========================================================================

1.本ソフトウェアについて

  デバイス制御プログラム用のサンプルプログラム は、TM-DTシリーズに接続した
  周辺機器を制御するためのプログラムを開発する開発者向けのサンプルプログラ
  ムです。
  詳細は TM-DTシリーズ 周辺機器制御ガイド を参照ください。


2.提供ファイル

  ・GGateway.dll
    デバイス制御プログラムが TM-DT ソフトウェアとデータ送受信するための
    通信ライブラリです。

  ・Sample01.exe
    デバイス制御プログラムのサンプルプログラムです。(プロジェクト一式同梱)

  ・DevCtrlPrgTester.exe
    開発したデバイス制御プログラムの動作確認用ツールです。


3.使用方法

  DevCtrlPrgTester.exeを起動し、ソケット通信開始待ちにします。
  Sample01.exeを起動すると、自動でソケット通信を確立します。
  DevCtrlPrgTester.exeからコマンドを送信します。
  Sample01.exeはコマンドを受信し、応答を返します。
  DevCtrlPrgTester.exeにSample01.exeからの応答が表示されます。
  DevCtrlPrgTester.exeで Delete Device を実行すると、通信が終了します。


4.その他留意点

  Sample01.exeのプロジェクトはMicrosoft Visual C++ 2008で作成しています。
  お客様の開発環境に合わせてご使用ください。


5.制限事項


