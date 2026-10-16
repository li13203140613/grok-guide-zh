# Grok Imagine 提示词怎么写？2026 官方写法和 10 个范例

**写 Grok Imagine 提示词，按官方指南的顺序来：先用一句话写清楚“画的是什么”，再写细节和角度、道具、光线、颜色，最后写构图。单张图 4～6 句就够。要写“想看到什么”，别列一长串“不要什么”。主体画错了就重新生成；主体对了只差 1～3 处细节，就用编辑功能改。Imagine 从 Plus 档开始有，免费版只能少量生图、不能生成视频。本文附 10 个中英双语范例，可以直接复制使用。**

> 最后核对：2026-10-16｜依据：xAI 官方图片提示词指南、Grok 官方 FAQ、价格页（链接见文末）｜本文非官方

## 目录

- [Grok Imagine 是什么？哪个会员能用？](#grok-imagine-是什么哪个会员能用)
- [官方推荐的提示词结构：6 个部分](#官方推荐的提示词结构6-个部分)
- [5 条写法规则](#5-条写法规则)
- [10 个提示词范例（中英双语）](#10-个提示词范例中英双语)
- [生成还是编辑？改不好怎么办？](#生成还是编辑改不好怎么办)
- [视频生成要注意什么？](#视频生成要注意什么)
- [常见问题](#常见问题)

## Grok Imagine 是什么？哪个会员能用？

Grok Imagine 是 Grok 里生成和编辑图片、视频的功能，在 grok.com、Grok App 里都能用。

| 档位 | 图片 | 视频 |
|---|---|---|
| Free（免费） | 有限 | 不包含 |
| Plus（$8/月） | 有 | 官方价格页没有单独写明 |
| Premium（$30/月）及以上 | 有 | 有（官方写明“AI 图片和视频生成”） |

几条规则先知道：

- 付费用户的 Imagine 和聊天、语音等功能共用**每周额度**，官方说生成高质量视频比聊天扣得多得多。额度规则见 [Grok 次数用完了怎么办](grok-usage-limits.md)。
- 生成的图片和视频**都带 Grok 水印**，没有关闭选项，去掉或遮挡水印违反官方使用规则。
- 价格和档位区别见 [Grok 会员多少钱](grok-pricing-plans.md)。

## 官方推荐的提示词结构：6 个部分

xAI 官方的图片提示词指南里说，判断一张图成不成功，**最重要的是画出来的主体和你写的是不是同一个东西**，配色、颗粒感这些风格都排在后面。所以它推荐按这个顺序写：

1. **主体**：画的是什么，是什么状态，放在什么东西上，在什么环境里。
   例：“一只哑光灰绿色的陶瓷手冲滤杯，架在装了一半咖啡的玻璃壶上，放在浅色橡木台面上，背后是白色方砖墙。”
2. **细节和焦点**：每个关键元素叫什么、长什么样、有几个、从什么角度看。
   例：“两个马克杯”“一本翻开的笔记本”“从台面高度、45 度斜侧面看过去”。
3. **美术方向**：画面里的大块颜色，加两三个道具，每个都点名。
   例：“橡木台面、白瓷砖、一条亚麻布、一把黄铜小勺”。
4. **光线**：光从哪里来、什么方向、硬光还是柔光，并且要求**亮度足够看清主体**。
   例：“左边照来的下午阳光，硬光，加一点正面补光”。
5. **颜色**：主体的颜色和背景的颜色分开写。
   例：“灰绿色、深琥珀色、浅橡木色、白色”。
6. **构图**：怎么裁切、画面边缘切掉什么、哪些地方要清晰。整张图只写一个场景。

官方还提醒：如果一开头就写氛围、胶片质感或一串“不要”，画出来的往往是风格对了、主体却是个“替身”。

## 5 条写法规则

**1. 写你想看到的，不写你不想要的。**
“拉丝不锈钢，表面有细细的横纹”能让模型知道该画什么；“不要反光”什么信息都没给。一长串“不要”还容易被忽略，甚至把你不想要的东西画进去。只有在限定数量或者特定物品时才写限制，而且要配上你想要的，比如“托盘上只放一把不锈钢勺子”。

**2. 东西要叫准名字。**
盘子、碗、平底锅是三样不同的东西；托特包、邮差包、双肩包也是。区别很重要的时候，就把它的特征写出来，比如平底锅是“奶油色搪瓷锅壁围着食物，锅柄被画面边缘切掉一截”。

**3. 质感只写一次。**
同一个质感词写好几遍，模型会把它画到别的东西上。比如反复强调“颗粒感”，结果连包着食物的饼皮都变得坑坑洼洼。

**4. 光线要让主体看得清。**
“明亮、鲜艳、硬阳光、闪光灯、暖色阴影里有纹理”这种写法效果稳定；“稍微欠曝”“压暗阴影”会把整张图拉暗。“色差、灰尘、划痕”这类词也别加，模型会把它们当成瑕疵画出来。

**5. 写成一张照片的描述，不要写成修改指令。**
“把外套颜色调深一点”这种话，模型没有“修改前”的图可以对照。直接描述成品：“深炭灰色的厚斜纹呢外套，能看见织纹”。

## 10 个提示词范例（中英双语）

每个范例都按上面的 6 部分结构来写。官方指南是英文的，**官方没有说明中文提示词的效果是否和英文一样**，所以每个范例都给了中文版和英文版，你可以都试一下，看哪个效果更好。

人物范例全部是**虚构人物**。用真人的名字或照片生成图片，涉及肖像和隐私问题，详见 [Grok 图片被审核怎么办](grok-image-moderated.md)。

### 范例 1：电商产品图（保温杯）

> 一只哑光雾蓝色的不锈钢保温杯立在浅灰色水泥台面上，背后是暖白色墙面。杯身有细细的磨砂纹理，杯盖是原木色竹盖，杯身前面放着一片新鲜柠檬。从略低于杯子的高度、斜侧面四分之三角度拍摄。右侧上午的阳光是硬光，在台面上投下清晰的长影子，左侧有柔和补光。画面是 50mm 产品照，杯子完整清晰，裁切到杯子上方留一点空白。

> A matte dusty-blue stainless steel tumbler standing on a pale gray concrete counter against a warm off-white wall. The body has a fine frosted texture, the lid is natural bamboo, and one fresh lemon slice rests in front of it. Shot from a low three-quarter angle, slightly below the cup. Hard morning sun from the right casts a long, crisp shadow across the counter, with soft fill from the left. 50mm product photograph, the tumbler fully sharp, cropped with a little space above the lid.

**为什么这样写**：第一句就把主体、材质、放在哪、背景交代完；道具只放一片柠檬；光线写了方向和软硬。

### 范例 2：小红书风格美食图（牛肉面）

> 一碗红烧牛肉面装在米白色粗陶碗里，从斜上方 45 度俯拍。面条上铺着五六块炖得发亮的牛腱子肉，切面能看到纹理，旁边是一小撮翠绿的葱花和两棵烫过的小油菜，汤面浮着一层红油。碗放在深色胡桃木桌上，左边露出一双竹筷和一个小碟子，碟子里是腌萝卜。左侧窗户照进来柔和的自然光，汤面上有清晰的高光，画面明亮温暖。主体颜色是红褐色、翠绿、米白，背景是深胡桃木色。碗占画面三分之二，牛肉和葱花清晰。

> A bowl of braised beef noodle soup in a rough off-white stoneware bowl, shot from a 45-degree overhead angle. Five or six glossy slices of braised beef shank with visible grain sit on the noodles, next to a small pile of bright green scallions and two blanched bok choy, with a layer of chili oil floating on the broth. The bowl sits on a dark walnut table, with bamboo chopsticks and a small dish of pickled radish at the left edge. Soft daylight from a window on the left, clear highlights on the broth, bright and warm. Red-brown, bright green and off-white on the subject, dark walnut in the background. The bowl fills two-thirds of the frame, beef and scallions in sharp focus.

**为什么这样写**：数量写具体（五六块肉、两棵菜），每样东西叫准名字（粗陶碗、牛腱子肉），避免模型随便发挥。

### 范例 3：人像（虚构人物，咖啡店店主）

> 一位虚构的三十多岁女性咖啡店店主，齐肩黑色短发，穿着燕麦色亚麻围裙，站在吧台后面正在用手冲壶往滤杯里注水，脸上带着专注的微笑。吧台是浅色木头的，旁边有一台银色磨豆机和一个装着咖啡豆的玻璃罐。从吧台对面平视拍摄，画面取到腰部以上。右侧大窗户照进来柔和的午后光线，脸部明亮，阴影柔和。主体颜色是燕麦色、黑色、银色，背景是浅木色和虚化的绿植。35mm 人像照片，脸和手部清晰。

> A fictional woman in her thirties who owns a coffee shop, with shoulder-length black hair and an oatmeal linen apron, standing behind the counter pouring water from a gooseneck kettle into a pour-over dripper, smiling with focus. The counter is pale wood, with a silver coffee grinder and a glass jar of coffee beans beside her. Shot at eye level from across the counter, framed from the waist up. Soft afternoon light from a large window on the right, her face bright with gentle shadows. Oatmeal, black and silver on the subject, pale wood and blurred green plants behind. 35mm portrait photograph, face and hands in sharp focus.

**为什么这样写**：明确写“虚构”；动作写得能看得见（正在注水），而不是写“很有氛围感”。

### 范例 4：头像风格插画（虚构人物）

> 一张方形的扁平插画头像，画的是一个虚构的年轻男生，圆框眼镜，蓬松的棕色卷发，穿着一件墨绿色连帽卫衣，戴着白色头戴式耳机，正面看向画面。背景是一个干净的浅橙色圆形色块。线条简洁，没有渐变，用大块的纯色。柔和的正面平光，没有明显阴影。主体颜色是墨绿、棕色、白色，背景是浅橙色和米白色。人物从肩膀以上居中，脸部占画面一半。

> A square flat-illustration avatar of a fictional young man with round glasses, fluffy brown curly hair, a dark green hoodie and white over-ear headphones, facing the viewer. The background is a clean pale orange circle. Simple lines, no gradients, large blocks of solid color. Soft, even front lighting with no strong shadows. Dark green, brown and white on the subject, pale orange and cream in the background. Centered from the shoulders up, the face filling half of the frame.

**为什么这样写**：插画也一样先写主体，再写风格；“没有渐变，用大块纯色”是在写想要的效果，而不是写“不要写实”。

### 范例 5：风景（江南水乡）

> 清晨的江南水乡，一条窄窄的河道从画面下方延伸到远处，两岸是白墙黑瓦的老房子，一座单孔石拱桥横跨在河道中间。河面上停着一条乌篷船，船头挂着一盏红灯笼，水面上有房子和石桥的倒影。从河边略高的位置向远处看。左侧刚升起的太阳照出淡金色的光，河面上飘着一层薄雾，画面明亮清透。主体颜色是白、黑、红，背景是淡金色和浅灰蓝。横版构图，石桥在画面中间偏上，近处的船和远处的桥都清晰。

> A Jiangnan water town at dawn. A narrow canal runs from the bottom of the frame into the distance, lined on both sides by old houses with white walls and black tiled roofs, with a single-arch stone bridge crossing the middle of the canal. A black-awning boat is moored on the water with a red lantern hanging at its bow, and the houses and bridge are reflected in the water. Viewed from slightly above the canal bank. The rising sun on the left gives a pale gold light, a thin mist floats over the water, bright and clear. White, black and red on the subject, pale gold and light gray-blue in the background. Landscape frame, the bridge just above center, both the nearby boat and the distant bridge in focus.

**为什么这样写**：近景（船）、中景（桥）、远景（河道尽头）各有位置；薄雾和晨光用来写氛围，比写“意境感”更具体。

### 范例 6：节日海报（中秋）

> 一张竖版的中秋节海报插画。画面中央是一轮又大又圆的暖黄色满月，月亮前面是一只白色的玉兔，坐在一枝开着桂花的树枝上，旁边放着一块切开的莲蓉月饼。画面下半部分是深蓝色的夜空和起伏的远山剪影。画面上方留出三分之一的空白，方便之后加标题文字。整体是柔和的国风插画风格，月光从中间往外晕开，玉兔和月饼边缘清晰。主体颜色是暖黄、白色、桂花的浅金色，背景是深蓝和墨蓝。

> A vertical Mid-Autumn Festival poster illustration. In the center is a large, round warm-yellow full moon, with a white jade rabbit in front of it sitting on a branch of blooming osmanthus, next to a cut lotus-paste mooncake. The lower half is a deep blue night sky with silhouettes of rolling distant mountains. The top third of the frame is left empty for a title. Soft Chinese-style illustration, moonlight glowing outward from the center, the rabbit and mooncake with clean edges. Warm yellow, white and pale osmanthus gold on the subject, deep blue and ink blue in the background.

**为什么这样写**：先留好放文字的空白位置。**AI 生成图片里的文字可能会写错或变形**，海报标题建议之后自己用修图软件加。

### 范例 7：室内设计效果图

> 一间朝南的小客厅，一张燕麦色布艺三人沙发靠着白墙摆放，沙发上有两个灰绿色靠枕和一条折好的米色针织毯。沙发前面是一张圆形浅橡木茶几，上面放着一个白色陶瓷花瓶，插着三枝尤加利叶。地上铺着一块浅灰色羊毛地毯，左边是一盏黑色金属落地灯。从房间门口、站立高度斜着看过去。右侧落地窗照进来明亮的上午阳光，在地毯上留下窗框的影子。主体颜色是燕麦色、灰绿色、浅橡木色，背景是白墙和浅灰。广角室内照片，整个沙发区域清晰。

> A small south-facing living room. An oatmeal fabric three-seat sofa stands against a white wall, with two sage-green cushions and a folded beige knit throw. In front of it is a round pale oak coffee table holding a white ceramic vase with three eucalyptus stems. A light gray wool rug covers the floor, and a black metal floor lamp stands on the left. Viewed at standing height from the doorway at an angle. Bright morning sun from a floor-to-ceiling window on the right casts window-frame shadows across the rug. Oatmeal, sage green and pale oak on the subject, white walls and light gray behind. Wide-angle interior photograph, the whole sofa area in focus.

**为什么这样写**：每件家具都写了材质、颜色和位置，相当于给模型一张“摆放清单”。

### 范例 8：宠物写真（橘猫）

> 一只胖胖的橘色虎斑猫趴在窗台上的一块米色坐垫上，前爪交叠，眯着眼睛晒太阳。能看清它橘色和奶白色相间的条纹、白色的胡须和粉色的鼻头。窗台是白色的木头，旁边放着一盆小小的绿萝。从和猫平视的高度、侧前方拍摄。左边窗户照进来暖暖的午后阳光，猫的毛边被照出一圈亮光，背景是虚化的窗外绿树。主体颜色是橘色、奶白、粉色，背景是白色和柔和的绿色。猫占画面一半，眼睛和胡须清晰。

> A chubby orange tabby cat lying on a beige cushion on a windowsill, front paws crossed, eyes half-closed in the sun. Its orange and cream stripes, white whiskers and pink nose are clearly visible. The windowsill is white-painted wood, with a small pothos plant beside it. Shot at the cat's eye level from the front-side. Warm afternoon sun from the window on the left creates a bright rim light along its fur, with blurred green trees outside the window. Orange, cream and pink on the subject, white and soft green in the background. The cat fills half of the frame, eyes and whiskers in sharp focus.

**为什么这样写**：写清楚姿势（前爪交叠、眯眼），写清楚“哪里要清晰”（眼睛和胡须），宠物图就不容易糊。

### 范例 9：科普示意插画

> 一张横版的扁平科普插画，从侧面展示植物光合作用。画面中间是一株有五片叶子的绿色小植物，种在棕色的土壤里。左上角是一个黄色的太阳，三条黄色箭头从太阳指向叶子；右侧有蓝色箭头表示水从根部往上走，灰色小圆点表示二氧化碳进入叶子，浅蓝色小圆点表示氧气离开叶子。背景是干净的浅米色，没有其他装饰。柔和平光，线条清晰，颜色分明。主体颜色是绿色、黄色、蓝色、灰色，背景是浅米色。植物在画面中间，所有箭头完整可见。

> A horizontal flat educational illustration showing plant photosynthesis from the side. In the center is a small green plant with five leaves growing in brown soil. A yellow sun sits in the top-left corner, with three yellow arrows pointing from the sun to the leaves; on the right, blue arrows show water moving up from the roots, small gray dots show carbon dioxide entering the leaves, and small light blue dots show oxygen leaving them. The background is clean pale beige with no other decoration. Soft even light, clear lines, distinct colors. Green, yellow, blue and gray on the subject, pale beige background. The plant centered, all arrows fully visible.

**为什么这样写**：数量和颜色一一对应（几条箭头、什么颜色代表什么）。如果需要“二氧化碳”“氧气”这类标注文字，同样建议之后自己加。

### 范例 10：编辑已有图片（换配件）

这个范例用在**已经生成了一张满意的手表照片，只想换表带**的时候：

> 把金属表带换成棕色皮革表带，表带上有奶白色的缝线。保持同一只手腕、同样的衬衫袖口、同样的角度和同一张桌子。

> Replace the metal watch strap with a brown leather strap with cream stitching. Keep the same wrist, the same shirt cuff, the same angle, and the same desk.

**为什么这样写**：这是官方指南里的编辑写法：**先写要改的 1～3 个地方，再用一句话说明哪些保持不变。**

## 生成还是编辑？改不好怎么办？

官方指南给的判断方法：

| 情况 | 用什么 |
|---|---|
| 还没有图 | 生成 |
| 主体画错了：画成了别的东西、少了关键元素、数量不对 | 重新生成 |
| 主体和布局都对，只差 1～3 个细节 | 编辑 |

编辑时要注意：

- **别用“保持所有内容不变”开头**，这样图几乎不会变。
- **别把一整段新提示词贴进去**，那样会重新布置整个场景：主体会跑偏，道具可能多出一份，甚至一样东西变成另一样（比如盘子变成平底锅）。

改不好的时候：

1. **换说法，别重复。** 一直写“更真实一点”，模型会在错的地方加新质感。要指出具体部位，比如“切面能看到一块块分开的土豆”“皮革在表带弯折处有褶皱”。
2. **每次都对照最开始的提示词检查**：主体对不对？提示词里写的每样东西都在吗、样子对吗？数量对吗？每样东西是不是你写的那样东西？亮度够不够看清主体？背景对了、主体错了，也算失败。
3. **把满意的提示词和图存在一起。** 下一轮只改没做好的那一处，其余保持原样，主体和布局就不会乱跑。

## 视频生成要注意什么？

官方公开的视频规则不多，能确定的是这几条：

- **免费版不能生成视频**；Premium 及以上的档位明确包含视频生成。
- 官方说生成高质量视频**比聊天扣的额度多得多**，额度用得快很正常。
- **720p 视频用到你所在档位的上限后，会自动降到 480p。** 视频突然变模糊，多半是这个原因。
- 视频同样带 Grok 水印。

写视频提示词时，可以沿用上面图片的思路：先写清楚主体和场景，再写动作。官方面向普通用户的帮助文档里没有公开视频时长、分辨率选项等更多参数，本文就不展开了。

## 常见问题

### Grok Imagine 免费吗？

免费版可以少量生成图片，官方没有公布具体张数，不能生成视频。Plus（$8/月）起正式包含 Imagine，Premium（$30/月）起明确包含视频生成。

### Grok 提示词用中文还是英文？

两种都可以试。官方的提示词指南是英文写的，没有说明中文提示词的效果是否一样，所以本文每个范例都给了中英两个版本。如果中文效果不稳定，可以换成英文版试试。

### 为什么生成的图里文字总是写错？

AI 生成图片里的文字可能写错或变形。海报、封面这类需要标题的图，建议在提示词里留出空白位置，之后用修图软件自己加字。

### 生成的图片能去掉水印吗？

不能。官方没有关闭水印的选项，去掉、修改或遮挡水印违反官方使用规则。

### 图片一直提示“已审核”怎么办？

先确认内容没有涉及真人色情化、侵权、暴力等禁止内容，再用中性的描述改写。具体方法见 [Grok 图片视频被审核怎么办](grok-image-moderated.md)。

### 一张图要写多长的提示词？

官方建议单张图 4～6 句：主体和细节 → 场景 → 光线 → 构图。系列图片要保持每一条提示词的结构顺序一致，画幅比例也固定，这样一组图放在一起才统一。

## 相关阅读

- [Grok 图片视频被审核怎么办](grok-image-moderated.md)
- [Grok 次数用完了怎么办](grok-usage-limits.md)
- [Grok 会员多少钱？四档价格和区别](grok-pricing-plans.md)
- [推特（X）里的 Grok 怎么用](grok-on-x.md)

## 官方来源

- xAI 官方图片提示词指南（Image Prompting Guide）：https://docs.x.ai/developers/model-capabilities/images/prompting-guide
- Grok 官方 FAQ（水印、视频清晰度）：https://docs.x.ai/grok/faq
- xAI 官方价格页（各档位功能）：https://x.ai/pricing
- 每周用量规则：https://docs.x.ai/x-subscription/usage-limits
- 使用规则（AUP）：https://x.ai/legal/acceptable-use-policy

---

> **关于付款**：官方网页结账只支持银行卡、Apple Pay、Google Pay、Link 等方式，没有列出支付宝和微信支付。没有境外支付方式的读者，可以了解第三方代开通服务 [xsub.ai](https://xsub.ai/)。请注意，xAI 官方声明订阅只由 X Subscription Corp. 直接销售，不授权任何经销商或第三方，通过其他渠道购买的账号可能被暂停。是否使用请自行判断。
>
> 本文由 [Grok 中文指南](../README.md) 整理，与 xAI、SpaceXSI、X Corp. 无关联。发现内容过时，欢迎提 Issue。
