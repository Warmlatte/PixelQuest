# PixelQuest - Battle System ⚔️
>一款受《寶可夢》啟發的 2D RPG 遊戲戰鬥系統！
目前仍在開發階段，包含基本的戰鬥機制，如角色攻擊、血量控制、戰敗處理等。

## 🎮 介紹

PixelQuest 是一款 2D RPG 遊戲，玩家可操控自己的角色進行戰鬥。目前已經實作：
	
- 基本主角走路動畫
- 地圖碰撞箱機制
- 戰鬥區域觸發機制
- 基本的 戰鬥 UI
- 攻擊機制（選擇技能並對敵人造成傷害）
- 敵方 AI（敵人會隨機選擇攻擊）
- 戰鬥結束狀態（角色血量歸零時的戰敗動畫）

未來計劃擴充更多遊戲內容，包括道具、技能系統，以及更豐富的戰鬥動畫！🔥


## 🛠️ 專案架構
這個專案主要使用 JavaScript 和 HTML Canvas API 來呈現 2D 遊戲畫面。

## 🚀 如何執行
### 本地執行方式

**下載專案**
```bash
git clone https://github.com/your-repo/PixelQuest.git

cd PixelQuest
```
**使用 Live Server 啟動**

如果使用 VS Code，可安裝 Live Server 擴充套件
右鍵 index.html，選擇 "Open with Live Server"
或者直接開啟 index.html 來執行遊戲

## ⚔️ 遊戲機制
- 戰鬥開始
    - 角色與敵人進入戰鬥畫面
    - 生命條 (#enemyHealthBar & #playerHealthBar) 會顯示當前血量

- 玩家回合
    - 選擇攻擊技能 (#attackBox 內的按鈕)
    - 觸發攻擊動畫，對敵人造成傷害

- 敵人回合
    - 敵人隨機選擇一個技能攻擊玩家

- 戰鬥結束
    - 角色血量歸零時播放 faint() 動畫並結束戰鬥
轉場回到地圖 (animate())


## 📝 待開發功能
✅ = 已完成 | ⏳ = 開發中 | ❌ = 尚未開始

✅ 基本攻擊與戰鬥機制<br/>
✅ 敵人 AI<br/>
✅ 生命條 UI<br/>
⏳ 動畫 & 特效<br/>
⏳ 戰鬥對話框<br/>
❌ 道具系統<br/>
❌ 經驗值 & 升級系統<br/>
❌ 更多怪物種類<br/>
❌ 地圖探索互動（例如進入房子)<br/>
❌ 增加隨機 NPC<br/>


## 👥 貢獻方式
如果你想幫幫我這個小菜雞ＱＱ，歡迎參與！💡<br/>
你可以：

1. Fork 這個專案並開發新功能
2. 提交 Pull Request（PR）
3. 報告 Bug 或提出建議
