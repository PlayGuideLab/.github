# PlayGuideLab

出海英文 **SEO 游戏指南 / Codes / Wiki 站群**（模板造站 → 精品日更 → 外链发现 → 后期变现）。

## 一句话（防歧义 · 必读）

**两个模板仓造站；[janvas.xyz](https://janvas.xyz/) 才是唯一对外 Emberville 练手实例；Hub（playguide-ops）只看板，不是生产线。**

| 角色 | 仓 | 是什么 | 不是什么 |
| --- | --- | --- | --- |
| 模板 A | [anvilwiki-next](https://github.com/PlayGuideLab/anvilwiki-next) | Codes/Wiki 热词站**工厂** | ≠ 线上产品站 |
| 模板 B | [game-sites](https://github.com/PlayGuideLab/game-sites) | 长文 guide/DB **工厂**（GK2） | ≠ janvas |
| 练手真站 | [emberville-patch-preview](https://github.com/beyondchenlin/emberville-patch-preview) → CF Pages → **janvas.xyz** | 唯一对外实例（练手） | ≠ 模板仓本身 |
| Hub | [playguide-ops](https://github.com/PlayGuideLab/playguide-ops) | 汇总 / 复盘 / 单站 P&L | ≠ 生产线；≠ `ops-platform` |
| Spoke | [content-pipeline](https://github.com/PlayGuideLab/content-pipeline) · [backlink-workbench](https://github.com/PlayGuideLab/backlink-workbench) | 证据→稿 / 外链发现台账 | **发现 ≠ 真投** |
| 未建 | SignalNexus · NarrativeFlow | 选题 / 文案（契约 stub） | 仓尚不存在 |
| 范围外 | skillzine · Magpie · ops-platform · xlink777* · anvil-e2e-fixture-preview | — | **勿当游戏主线** |

## 术语表

- **Anvil** = `anvilwiki-next` = 模板 A 工厂  
- **game-sites** = 模板 B 工厂  
- **Emberville @ janvas.xyz** = 练手真站（源仓在 personal：`beyondchenlin/emberville-patch-preview`）  
- **playguide-ops** = Hub  
- **content-pipeline / backlink-workbench** = Spokes  
- **SignalNexus / NarrativeFlow** = 未建 Spoke  
- **skillzine / Magpie / ops-platform / xlink*** = 范围外  

每仓根目录有 **`PURPOSE.md`**（Role / Not / Live URL / Fail-closed）。操作真相源见 Hub：  
[`docs/HANDOVER-2026-10-16.md`](https://github.com/PlayGuideLab/playguide-ops/blob/main/docs/HANDOVER-2026-10-16.md)

## Fail-closed（硬闸门）

| 允许 | 须 吱 书面/口头批准 |
| --- | --- |
| 发现 / 台账 / dry-run / 文档 / 模板改 | **买域** · **开索引** · **挂 AdSense** · **真投外链** · `BW_SUBMISSION_ENABLED=true` · 新号硬发 |
| 精品日更（约 1 篇/天，开站初期禁同晚连发） | 恢复 Lxx 浏览器慢采（用户曾停） |

**发现 ≠ 真投。** 预览域名（`*.pages.dev`）应收口 **noindex**；生产 **janvas.xyz** 已开索引（已批准），勿擅自改回 noindex。

## Repo map

- Hub: https://github.com/PlayGuideLab/playguide-ops  
- Template A: https://github.com/PlayGuideLab/anvilwiki-next  
- Template B: https://github.com/PlayGuideLab/game-sites  
- Live practice: https://janvas.xyz/ · src https://github.com/beyondchenlin/emberville-patch-preview  
- Content Spoke: https://github.com/PlayGuideLab/content-pipeline  
- Backlink Spoke: https://github.com/PlayGuideLab/backlink-workbench  

给其他大模型：先读本页 → 各仓 `PURPOSE.md` → Hub HANDOVER，再动手。
