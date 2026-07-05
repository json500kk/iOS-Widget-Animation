[English](./README.md) | [简体中文](./README.zh-CN.md) | [繁體中文](./README.zh-TW.md) | [日本語](./README.ja.md) | [한국어](./README.ko.md)

# iOS 27 ウィジェットアニメーション

ホーム画面ウィジェット向けの商用 iOS アニメーション SDK。**iOS 27** を完全サポートし、iOS 27 上で **ClockHandRotationKit** が正しく動作しない問題を解決します。さらに、**ClockHandRotationKit** からの移行互換性と、TopWidget 風の **SwingAnimation** エフェクトにも対応しています。

## 概要

`iOS Widget Animation` は、iOS のホーム画面ウィジェット向けに、滑らかで本番利用可能なアニメーションを構築するためのクローズドソース SDK です。

この公開リポジトリはデモおよび紹介用であり、非公開のソースコードは含まれていません。

## ビジュアルエフェクト

![Widget Animation Demo](./demo.gif)

[デモ動画をフルで見る](./demo.mov)

## 特長

- iOS 27 のホーム画面ウィジェットアニメーションに対応
- ClockHandRotationKit と互換性があり、移行が容易
- TopWidget 風の SwingAnimation エフェクトに対応
- 滑らかな時間ベースのアニメーション向けに設計
- シンプルな公開 API により商用導入が可能

## 互換性

### iOS 27 ウィジェットアニメーション

この SDK は、iOS 27 のホーム画面ウィジェットにおけるアニメーション動作をサポートするために設計されており、視覚的に滑らかな遷移に重点を置いています。

### ClockHandRotationKit 移行互換

すでに `ClockHandRotationKit` を利用しているプロジェクトでも、馴染みのある概念を維持しながら、移行時の負担を軽減できるよう設計されています。

### TopWidget SwingAnimation 互換

`TopWidget` の `SwingAnimation` に近いアニメーション表現を実現したい場合、この SDK はそのスタイルに対応したモーション機能を提供します。

### 連絡先

jsonkk500@gmail.com
