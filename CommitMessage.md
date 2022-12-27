### Title

* **new**: 新機能  
* **update**: コードの変更(動作の変更, コードの変更を伴うパフォーマンスの向上など)  
* **style**: コードのスタイルの変更(動作に大きな影響を及ぼさない)  
* **fix**:　バグ修正  
* **docs**: コード以外のファイル（ドキュメント等)の変更  
* **other**: その他  
  
### Description
commitに含まれる内容を簡潔に記載する。  
ライブラリなどを変更している場合、その旨も記載する(依存関係によるバグが発生することがあるため)。  
必要な場合はissueにタグ付けする。  
  
### Example
new: ステータスの表示機能  
update: curl->gdownへの変更により、実行速度向上  
style: インデント整理  
fix: {issue} 同期のタイミングの調整  
docs: index.mdの改訂  
other: .gitignoreに.DS_Storeを追加  
  
### References
https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#type
