<a id="case-25"></a>

# Simulação de buraco negro em rotação

[Assistir ao vídeo completo](https://x.com/i/videos/tweet/2125386093797478565) · [Publicação original](https://x.com/RJasonHA/status/2125386093797478565) · [Voltar à galeria](../../README_pt.md#case-25)

- **Categoria:** Cenas e simulações 3D
- **Conta que publicou:** [@RJasonHA](https://x.com/RJasonHA)

<a href="https://x.com/i/videos/tweet/2125386093797478565"><img src="https://pbs.twimg.com/amplify_video_thumb/2125385738829340672/img/2Tmh7s1GYLPTrJFi.jpg" alt="Simulação de buraco negro em rotação"></a>



## Prompt publicado

[Abrir o prompt do criador](https://x.com/YxzRainy/status/2125244696146702605)

```
请用单文件 HTML + WebGL2 + 纯 GLSL Raymarching 光线弯曲着色器，制作一个可实时交互的旋转黑洞。视觉参考电影《星际穿越》中的卡冈图雅：漆黑的中心、被引力折到上下两侧的炽热吸积盘，以及一座缓慢旋转的残破外星金属环。黑洞一开始就要足够大，让观众能看清中心附近的气流在转。
1. 真实光线弯曲。 在 GLSL 步进循环中，根据射线相对黑洞的位置持续更新传播方向。让光线的捕获与偏折自然形成黑洞阴影、纤细明亮的光子环，以及吸积盘背面被折出的上下双拱。禁止用普通黑球和发光圆环拼出黑洞。
2. 看得见的高速旋转。 用 3D FBM 分形噪声生成有厚度的湍流等离子体，沿弯曲光路累积发光与吸收。给内盘一股容易辨认的亮流，带着不规则的亮头和逐渐散开的尾迹。即使固定镜头，也能用眼睛跟着它绕过黑洞。 保留多普勒明暗差，迎面一侧呈亮金、白蓝，远离一侧呈深橙、暗红。使用 ACES Filmic 色调映射，亮处仍能看到气流纹理。
3. 金属骨架与真实星空。 用 SDF 雕刻环绕黑洞的巨型约束骨架，做出断裂的桁架、缺失的装甲板和裸露的横梁。让骨架比内盘转得慢，暗铁色棱边偶尔掠过一道吸积盘的暖光。背景使用细密、有疏有密的星野和隐约可见的银河尘带，靠近黑洞轮廓的星光随引力弯成弧线。
4. 30 秒电影运镜。 开场快速追近正在横掠的黑洞，随后沿逐渐收紧的螺旋绕着它下坠。靠近后，镜头仍在被吸向深处，周围气流和星光的运动却越来越慢，像时间正在停住。最后让黑洞阴影占满视野，只剩一线金光，随后陷入彻底的黑暗，片尾留出短暂的纯黑。具体角度、圈数和转场时刻可自由发挥。
5. 交互与输出。 支持鼠标阻尼拖拽 360° 环绕、滚轮缩放，右下角保留「自旋 / 引力强度」和「吸积盘曝光度」两个滑块。交付可离线打开的单文件 HTML，并输出 30 秒、2560 × 1440、60 fps 的 MP4。
```

## Notas

A conta credita o prompt a @YxzRainy e afirma que o usou sem ajustes. A gravação mostra o resultado.

**Atribuição do modelo:** A conta responsável pela publicação menciona o Opus 5.6. O modelo exato ainda precisa de verificação.

[Complemento da fonte](https://x.com/RJasonHA/status/2125480569261936992)
