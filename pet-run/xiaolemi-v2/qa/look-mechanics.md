# 小蕾米 look mechanics

## Natural motion

小蕾米是坐姿、圆润的 Q 版天使。下半身、双膝、脚和画板下沿保持稳定，视线由眼睛和眼睑先引导，头部和刘海轻微跟随，肩膀与翅膀只做很小的跟随变化。画板保持贴在腿上；羽毛笔保持握在手中，转头时允许轻微滞后，但不能脱离手或改变道具设计。

## Cardinal pose families

- `000` up: pupils and eyelids clearly move upward; chin and上脸部轻微抬起，身体下半部与画板基准不动。
- `090` screen-right: nose、双眼和脸部朝观察者的屏幕右侧移动，头部轻微向右转，右侧脸部更明显；画板仍贴在腿上，羽毛笔随手部轻微跟随。
- `180` down: pupils and eyelids clearly move downward; chin and上身轻微下压，画板和腿部锚点保持稳定。
- `270` screen-left: nose、双眼和脸部朝观察者的屏幕左侧移动，头部轻微向左转，左侧脸部更明显；画板仍贴在腿上，羽毛笔随手部轻微跟随。

## Interpolation and limits

Rows 9 and 10 form one clockwise loop in 22.5-degree steps. Interpolate eyes, eyelids, head, bangs, wings, and prop follow-through gradually between the approved cardinals. Keep the lower-body anchor, seated baseline, board attachment, face proportions, outline, palette, and identity stable. Do not rotate, skew, or tilt the whole sprite to fake looking; do not add new eyes, pupils, labels, arrows, clocks, shadows, glow, scenery, or detached effects. Every direction must differ visibly from neutral at normal pet size while remaining a subtle, natural look-around motion.
