# 1.0 更新日志

##### 2019年03月13日

##### App 1.0 已完成

建議用戶刪除舊版本，再次安裝新版本

##### App（Build 50）

- 增加繁體、簡體中文
- 加入反饋意見功能
- 追加手動刷新型號功能
- 修正由於代碼錯誤而導致的 VPS 無法被 SSH 調用
- 增加背景刷新功能

##### App（Build 44）

- App 更新后，將會刷新緩存數據
- 完善化 Setting
- 重寫 Connect Config
- Screen 支持分配對應 SSH 連線
- Screen 下的命令可以被 VPS 調用了

##### 2019年03月12日

##### App（Build 43）

- 追加nvram get model在外部顯示
- nvram get model 移除無效字符，嘗試排除型號識別錯誤
- nvram get model 暫時關閉 Cache，正在排除型號識別問題

##### 2019年03月11日

##### App（Build 41）

- 減少了請求登入的發送次數
- 修改 Bundle Indentifier 的大小寫錯誤
- JSONView 增加 **Remove Screen** 功能
- 增加 **nvram get model** 的 Cache 模式，提升性能
- 推送功能也可用於與 Shadowsock 梅林面板進行協同，在自動更新訂閱之後推送亦可
- 增加推送功能，未來用於推送腳本更新 / Shadowsock 更新 / App 更新的提醒信息
- 追加完整的**添加** / **編輯** / **刪除**節點功能
- 追加 **HND 機型**支持
- 修復由於網速數據格式無效而導致的閃退
- 修改部分錯誤的英文單詞

##### 2019年03月10日

##### App（Build 30）

- In Process 頁面加入自動滾動功能
- SS 應用後回到主界面

##### 2019年03月9日

##### App（Build 28）

- **「進行中」**多個 SSH 正在支持到 VPS 分配上。
- 修正用戶儲存使用的 URL 函數
- 嘗試修正之前版本在部分路由器上，可能讀取訂閱設置失敗而閃退

##### 2019年03月06日

##### App（Build 27）

- 修正移除訂閱服務器后，由於運行中的服務器不存在列表上而閃退
- 使用新的用戶配置儲存模式，現在可支持多個 SSH 儲存
- Setting 界面完成 90%
- IQKeyboardManager 更新到最新版本

##### 2019年03月04日

##### App（Build 24）

- 修正 Terminal 在無服務器設定下的閃退

##### 2019年03月03日

##### 脚本源

**修改** Shadowsock 相关脚本修改来源版本

**增加** L2TP/IPSec VPN 一键安装脚本

**增加** 系统操作脚本

##### App（Build 23）

- 增加更新日誌
- 使用 SSH 模式讀取配置，嘗試改善兼容性。
- 嘗試修正 R6300V2 機型閃退

##### App（Build 21）

Build 21 版本發佈

- 增加了歡迎界面
- 改善 JSON Screen 載入性能
- 改善 iPhone SE 兼容性

##### 早期發佈（Build 21 之前）

- 支援 ACL（訪問控制）設定
- 支援線路切換
- 支援 Status（國外連線狀態）顯示
- 基於 JSON 調用 Terminal 以及 UI 呈現的 JSON Screen
- JSON Screen Add List