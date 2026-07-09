# FutureTodo システム設計

## 全体構成

FutureTodoはExcel VBAで構築する。

## シート構成予定

- Main
- Todo
- History
- Prediction
- Rules
- Settings

## VBAモジュール予定

- modMain
- modTodo
- modHistory
- modPrediction
- modRuleEngine
- modImport
- modCommon

## データフロー

Todo登録
↓
Todo管理
↓
完了
↓
History保存
↓
分析
↓
Prediction生成