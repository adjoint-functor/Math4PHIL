# 署名与材料许可

研究构想：**Adjoint Functor**。  
建模与实验辅助、文稿撰写：**GPT 6 Astra、GPT 6.1 Sol**。

Math4PHIL 项目维护与本报告发布： [Adjoint Functor](https://github.com/adjoint-functor)。报告题名为《目的、条件与泛性质：亚里士多德幸福论的一个局部重构》，版本 v0.1.9，日期 2026-10-28。建议引用信息见仓库根目录的 `CITATION.cff`。

## 希腊文数字底本

Aristotle, *Ἠθικὰ Νικομάχεια*; Ingram Bywater (ed.), *Aristotelis Ethica Nicomachea*, Clarendon Press, Oxford, 1894. Digital text: Perseus Digital Library Project / Trustees of Tufts University, Perseus 2.0 (1996) and subsequent revisions.

来源：[PerseusDL/canonical-greekLit](https://github.com/PerseusDL/canonical-greekLit)，`data/tlg0086/tlg010/tlg0086.tlg010.perseus-grc2.xml`。固定 Git blob：`e8a43ddc7d643fca148f1dda18dc6d34528a9b2b`；完整 XML 的 SHA-256：`a203a8d2e793b06884b135c23a5726ce36fc4796a6651589becb7cdf86ee42ae`。

数字底本声明采用 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)；证据包保留其原始字节、完整头部和编制责任者。希腊文分析读法与摘录沿用该许可：按文档顺序拼接，保留 `add`、排除 `del` 并另存删补记录，只合并空白，不改变字母、重音、标点或 Unicode 正规形。上述处理属于派生读法，未对原始 XML 作改写。

## 项目原创内容

Copyright (c) 2026 Adjoint Functor，限于依法享有并有权许可的部分。

报告的原创论述、模型说明、证明和项目图示采用 [CC BY-NC-ND 4.0（署名—非商业性使用—禁止演绎）](../../LICENSES/CC-BY-NC-ND-4.0.txt)。项目独立编写的说明和提示文本，未另行标明时适用同一许可。允许按条款注明署名、题名、来源和许可的非商业转载；公开分享改编作品（通常包括译文）及商业使用不在该许可的授权范围内。必要的格式转换不因此构成改编；依法允许的引用等使用不受影响。

本项目采用的贡献署名为：

> 研究构想：Adjoint Functor  
> 建模与实验辅助、文稿撰写：GPT 6 Astra、GPT 6.1 Sol

引用建议：Adjoint Functor，《目的、条件与泛性质：亚里士多德幸福论的一个局部重构》，Math4PHIL，v0.1.9，2026-10-28。转载时请保留上述贡献说明与许可信息。

## 复核软件

完整证据包中项目自有的 Python 复核程序与 JSON Schema 采用 [MIT](../../LICENSES/MIT.txt)：`code/verify_evidence.py`、`code/verify_models.py`、`evidence/diagnostic-I5/verify_offline.py`、`evidence/diagnostic-I5/interface/validate.py` 及同目录的 `annotation.schema.json`、`packet.schema.json`。转载或分发软件时须保留 MIT 版权和许可声明。

## 原典与衍生材料的许可边界

前述 **CC BY-SA 4.0** 继续适用于数字底本、希腊文摘录、分析读法，以及受该许可约束的翻译、释义和结构化转录。附录 A 的原文与对应中文释义、正文明确标识的原文及对应译述、证据索引与结构化记录中的相应内容，均不受项目新增的非商业、禁止演绎条件覆盖。使用者可以依其原许可使用这些材料，并保留 Aristotle、Bywater、Perseus／Tufts 等原署名及处理说明。

原始证据文件保持记录时的字节，不为更新署名或许可而改写。包内历史的“许可待定”等描述反映记录当时的状态；项目自有内容在本次发布时按本说明许可，第三方原许可保持。

辅助译本、现代论文和教材通过书目及原站链接提供，未打包镜像；其引文及其他单独署名材料保留各自权利与许可。本声明仅涉及许可方有权授权的内容，不为公有领域材料、思想、事实或数学方法创设新的限制。

完整适用范围见[仓库许可说明](../../LICENSE.md)。
