# 素材接入說明

把你自己取得的素材放進 `assets/private/`，這個目錄已被 .gitignore 排除，不會被提交或推送。

## 目錄
- audio/voice：角色台詞音檔（建議每句獨立檔，mp3 或ogg）
- audio/bgm：背景音樂（大廳、牌桌、緊張段落各一）
- audio/sfx：短音效（反轉、打臉、籌碼、翻牌等）
- images/characters：角色立繪或頭像（建議去背 png）
- images/backgrounds：牌桌背景、場景圖

## 命名建議
`角色代號_事件_序號`，例如 `ken_dealer_start_01.mp3`、`weiwei_allin_02.mp3`。

## 清單
填寫 `assets/manifest.template.json`，另存為 `assets/private/manifest.json`。
每一筆把「素材檔」對應到「牌桌事件」，事件名稱見 docs/GAME_DESIGN.md 第 7 章。

## 注意
- 素材只放本機，不要上傳到 GitHub、雲端公開連結或公開伺服器。
- 若要讓朋友連線遊玩，素材會經由你的伺服器傳給對方，屬於散布，請自行評估。
