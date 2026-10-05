# 逐日神弓美术

使用 Codex 内置 imagegen 生成，未使用 CLI。原图保存在本目录。

- `heroine_generated.png`：32 帧透明持弓角色，4 列 × 8 行；按原角色动画的格子尺寸缩放成游戏用 444 × 888 图集。
- `bow_generated.png`：透明武器原画；生成 64 × 64 背包图标及 96 × 96 地面掉落图。
- 游戏用图：`mods/empyrean_campaign/images/avatar/chibi/sunbow_heroine.png`、`images/icons/sunbow.png`、`images/loot/sunbow.png`。
- 物品 1702 用 `gfx_hero=sunbow_hero` 切换完整主角图层；装备栏预览同步切换，卸下恢复原角色。其他装备的外观显示规则保留。
- 动画沿用原角色的站立、移动、射击及其他状态，八方向和脚底锚点保持一致。火焰为图集内光效。

## 角色图集生成提示词

Edit this exact transparent pixel-art game sprite sheet. Preserve the canvas aspect ratio 1:2 and exact 4 columns by 8 rows grid, 32 separate characters, every original character position, scale, feet anchor, facing direction and walking pose. Do not add borders, background, text or rearrange cells. Character is the same adorable brown-haired chibi heroine in teal clothes. Add the legendary Sun-Chasing Divine Bow to EVERY character's hands, naturally held at waist/chest height pointing consistently with each facing direction. Spectacular compact ornate golden crescent bow with sun-disc gemstone at grip, pointed phoenix wing limbs, luminous amber bowstring, small orange flame tips, restrained bright gold sun halo sparkles around weapon. Weapon fits entirely within each cell, no overlap across cells, no ground glow. Retain clear readable faces, teal costume, hair, pixel-art outlines. Match existing pixel art rendering and palette, crisp pixels, no painted blur. Make bow clearly visible and impressive when sprites are small. No arrows piercing character. Transparent background with clean alpha. Return ONLY complete edited sprite sheet.

## 武器原画生成提示词

Create ONE transparent background pixel art inventory weapon asset for a cute chibi fantasy RPG: Sun-Chasing Divine Bow. A spectacular ornate golden phoenix crescent bow with symmetric sweeping feather-like limbs, bright circular sun gemstone grip at center, glowing golden amber bowstring connecting ends, orange flame at each tip and a few small gold sparkles. Match rich crisp pixel art of a teal-costumed brown-haired chibi RPG heroine. Isolated bow only, no character, no hands, no words, no ground, no frame, no background. Show full bow diagonally from lower left to upper right, with all flame/glow comfortably inside canvas and generous transparent margins. Readable simple bold silhouette even when resized to 64x64 inventory icon. Polished legendary-tier game asset, warm metallic gold shading, luminous orange-red accents, clean transparent alpha.

