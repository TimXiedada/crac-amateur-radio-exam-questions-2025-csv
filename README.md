# crac-amateur-radio-exam-questions-2025-csv
将于2025年10月1日生效的[《新版业余无线电台操作技术能力验证题库（2025年版）》](https://mp.weixin.qq.com/s/abWyWXJgkknclMqQG87MrA "微信公众号文章")，由PDF转换为CSV格式，以方便制作模拟考试工具。

## 文件描述
| 文件名 | 描述 |
|------|------|
|class_a.csv|A类题库|
|class_b.csv|B类题库|
|class_c.csv|C类题库|
|full.csv|总题库|
|images.csv|题目附图与标签对照表|
|images/*.jpg|题目附图|
|images_2|以题目标签命名的题目附图文件|

## 表头说明（推测）
CRAC在发布题目时并未说明表头（源文件中为行首的单字母标记）的含义，这只是一个推测。
| 表头 | 含义 |
|------|------|
|J|题目标签<br>（部分题目不唯一）|
|P|题目分类|
|I|题目编号和正解数：`MC<X>-<YYYY>`，<BR>其中X=选项数，Y=题目序号|
|Q|题干|
|T|正解选项，为前X个选项，<BR>实际组卷或机考需要打乱|
|A|选项A|
|B|选项B|
|C|选项C|
|D|选项D|
|F|题目附图文件名（`<J列>.jpg`，本项目CSV格式无，<BR>需要调用文件系统API检测是否存在）|

另外，推荐导入数据库时将J列拆分。
## 特别说明
个别题目有2个题号，使用半角逗号分割。

## 数据集许可

![WTFPL](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-1.png)

本数据集使用WTFPL2.0协议发布，详情请[点击此处](COPYING)。

## 双库联动

GitHub: <https://github.com/timxiedada/crac-amateur-radio-exam-questions-2025-csv>

Gitee: <https://gitee.com/timxiedada/crac-amateur-radio-exam-questions-2025-csv>
