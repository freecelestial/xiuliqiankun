# Play Console 曝光設定（品牌站入口）

品牌站：`https://freecelestial.github.io/xiuliqiankun/`

三個條目各做兩件事：

## 1. 開發人員網站欄

Play Console → 該 App →「商店資訊和設定 › 商店設定 › 商店資訊聯絡資料 › 網站」
填入 `https://freecelestial.github.io/xiuliqiankun/`。商店頁會顯示「開發人員網站」連結。

| App | applicationId |
|-----|---------------|
| 梅花易占（袖裡乾坤） | com.freecelestial.yizhan |
| 飛星風水 | com.maxroles.feng_shui_star |
| 紫微推命 | com.maxroles.fate_app |

## 2. 完整說明末段加一行

放在免責聲明段**之前**、〈其他〉段末尾。梅花易占四語文案已改在 `divination/docs/store/listing_*.md`，直接整段貼。飛星／紫微文案不在 repo，依語系補下面這行：

| 語系 | 飛星風水 | 紫微推命 |
|------|----------|----------|
| zh-TW | 更多作品：袖裡乾坤官網 https://freecelestial.github.io/xiuliqiankun/ | 同左 |
| zh-CN | 更多作品：袖里乾坤官网 https://freecelestial.github.io/xiuliqiankun/ | 同左 |
| en | More from Xiuli Qiankun — Meihua I-Ching and Purple Star Astrology: https://freecelestial.github.io/xiuliqiankun/ | More from Xiuli Qiankun — Meihua I-Ching and Feng Shui Stars: https://freecelestial.github.io/xiuliqiankun/ |
| ja | 同シリーズのアプリ（梅花易占・紫微推命）：袖裏乾坤 https://freecelestial.github.io/xiuliqiankun/ | 同シリーズのアプリ（梅花易占・飛星風水）：袖裏乾坤 https://freecelestial.github.io/xiuliqiankun/ |
| ko | 같은 시리즈 앱(매화역점·자미추명): 수리건곤 https://freecelestial.github.io/xiuliqiankun/ | 같은 시리즈 앱(매화역점·비성풍수): 수리건곤 https://freecelestial.github.io/xiuliqiankun/ |

注意：
- 梅花易占目前封測中，飛星／紫微文案提「梅花易占」沒問題（品牌站上標示「即將上線」）。
- 改商店資訊不需重送 APK，儲存後走一般商店審查（通常數小時～數日）。
- 完整說明上限 4000 字元，貼前確認沒超。
