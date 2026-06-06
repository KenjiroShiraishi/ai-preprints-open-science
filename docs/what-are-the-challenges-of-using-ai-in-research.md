# 🤖 What Are the Challenges of Using AI in Research? / 研究におけるAI使用の課題とは？

---

## 🌐 English

Generative AI is powerful at recognizing patterns across large text and multimodal datasets.  
As a result, it can support structural and linguistic tasks such as drafting text, correcting grammar, summarizing content, translating documents, organizing ideas, and assisting with image-based analysis in medicine.

However, AI systems may struggle with factual accuracy, deep contextual understanding, source verification, and ethical reasoning — especially in areas involving meaning, values, and responsibility.

The six challenges below reflect these limitations in the context of academic research.

---

## ⚠️ Six Overlooked Challenges

### 1. Hallucinated Citations

AI may generate plausible but non-existent references.  
This is especially problematic in academic writing, where citations are not decorative but part of the evidential structure of an argument.

Without prompt and output records, authors may find it difficult to identify how such errors entered the manuscript or to correct them transparently.

*Ref: Maynez et al. 2020*

---

### 2. Unclear Intellectual Contribution

When AI helps draft, summarize, structure, translate, or revise academic content, it can become unclear which parts reflect human judgment and which parts were generated or shaped by AI.

This does not mean AI should be treated as an author.  
Rather, it means that human authors must remain responsible for accuracy, interpretation, ethical judgment, and final decisions.

Documentation helps clarify the boundary between AI assistance and human intellectual contribution.

*Ref: Flanagin et al. 2023; Nature 2023; Thorp 2023*

---

### 3. Reinforcement of Hidden Biases

AI outputs may reproduce or amplify biases embedded in training data, prompts, or institutional assumptions.

For example, outputs may unintentionally include stigmatizing associations related to illness, disability, gender, race, age, socioeconomic status, or professional hierarchy.

Because these biases may appear in fluent and confident language, they can be difficult to detect without careful human review.

---

### 4. Barriers to Reproducibility and Auditability

Prompts act as structured inputs to AI systems.  
Although AI outputs may not be perfectly reproducible because models change over time, preserving prompts and outputs improves auditability, transparency, and accountability.

Prompt preservation can help others understand:

- What was asked
- What the AI produced
- What the human author accepted, rejected, or revised
- How AI contributed to the development of the final work

This aligns with the broader spirit of open science and FAIR-oriented research practices.

---

### 5. Opaque Multi-AI Workflows

Researchers may use multiple AI tools in the same project.  
For example, one model may be used for summarization, another for translation, another for structure, and another for literature exploration.

Without documentation, it becomes difficult to trace which tool contributed to which stage of the work.

This opacity can weaken transparency, accountability, and editorial confidence.

---

### 6. Erosion of Editorial and Peer-Review Trust

Editors and reviewers may question whether a manuscript reflects the author’s own judgment, whether citations were verified, or whether AI-generated content was responsibly reviewed.

Preserving prompts and outputs can help clarify the human/AI boundary and support trust between authors, editors, reviewers, and readers.

The goal is not to expose every minor interaction with AI, but to preserve meaningful records when AI substantially contributes to writing, analysis, translation, interpretation, or scholarly reasoning.

---

## 💡 Proposed Practice: Prompt Preservation

Prompt preservation is a practical method for documenting AI use in research and academic writing.

Recommended practices include:

- Save prompts and AI outputs as timestamped records, preferably in PDF format.
- Preserve them together with repository timestamps, version histories, DOIs, or OSF/GitHub records when possible.
- Record which AI tool was used, including the model name and date of use.
- Clearly distinguish between AI-generated suggestions and final human decisions.
- Preserve meaningful AI interactions, especially when they affect the structure, interpretation, argument, translation, or wording of scholarly work.

PDFs are not tamper-proof.  
However, when combined with transparent archiving practices, they can serve as stable and shareable records.

Prompt preservation does not guarantee perfect reproducibility, because AI models may change over time.  
However, it improves transparency, auditability, and accountability.

Public templates and examples are available:

📁 https://github.com/KenjiroShiraishi/ai-use-policy-in-scholarly-writing  
📄 [Prompt PDF Example](https://github.com/KenjiroShiraishi/ai-use-policy-in-scholarly-writing/blob/main/prompt-example.pdf)

---

## 🇯🇵 日本語

生成AIには、大規模なテキストデータやマルチモーダルデータからパターンを抽出する力があります。  
そのため、文章の下書き、文法修正、要約、翻訳、構成案の作成、医学画像の解析補助など、形式的・構造的な作業を支援することができます。

一方で、AIは事実の正確性、深い文脈理解、出典確認、倫理的判断といった領域では限界があります。  
特に、意味、価値、責任が関わる場面では、人間による確認と判断が不可欠です。

以下では、研究利用時に見落とされやすい課題を6点に整理します。

---

## ⚠️ 見落とされがちな6つの課題

### 1. 存在しない引用の生成（ハルシネーション）

AIは、実在しない文献をもっともらしく生成することがあります。  
学術論文において、引用は単なる飾りではなく、主張を支える証拠構造の一部です。

プロンプトや出力の記録がなければ、その誤りがどの段階で入ったのかを確認したり、透明性をもって修正したりすることが難しくなります。

*参考：Maynez et al. 2020*

---

### 2. 知的貢献の所在が不明瞭になる

AIが文章の下書き、要約、構成、翻訳、修正を支援した場合、どの部分が人間の判断で、どの部分がAIによって生成・形成されたのかが不明瞭になることがあります。

これは、AIを著者として扱うべきだという意味ではありません。  
むしろ、人間の著者が、正確性、解釈、倫理的判断、最終決定に責任を持つ必要があるということです。

記録を残すことで、AIによる補助と人間の知的貢献の境界を明確にしやすくなります。

*参考：Flanagin et al. 2023、Nature 2023、Thorp 2023*

---

### 3. 見えにくいバイアスの温存

AIの出力には、学習データ、プロンプト、制度的前提に含まれるバイアスが反映・増幅されることがあります。

たとえば、疾患、障害、性別、人種、年齢、社会経済的地位、職業的階層などに関する偏見や固定観念が、無意識に出力へ含まれる可能性があります。

しかも、それらは流暢で自信のある文章として提示されるため、人間が注意深く確認しなければ見落とされることがあります。

---

### 4. 再現性と監査可能性の不足

プロンプトは、AIシステムへの構造化された入力と見なすことができます。  
ただし、AIモデルは更新されるため、同じプロンプトを用いても出力が完全に再現されるとは限りません。

それでも、プロンプトと出力を保存することで、監査可能性、透明性、説明責任を高めることができます。

プロンプト保存により、後から以下の点を確認しやすくなります。

- 何をAIに尋ねたのか
- AIが何を出力したのか
- 人間の著者が何を採用し、何を却下し、何を修正したのか
- AIが最終成果物の形成にどのように関与したのか

これは、オープンサイエンスやFAIR志向の研究実践とも親和性があります。

---

### 5. 複数AIツールの利用履歴が追えない

研究者は、一つのプロジェクト内で複数のAIツールを使うことがあります。  
たとえば、あるモデルを要約に使い、別のモデルを翻訳に使い、さらに別のモデルを構成案や文献探索に使うといった形です。

しかし記録がなければ、どのツールがどの段階に関与したのかを後から確認することが難しくなります。

この不透明さは、透明性、説明責任、編集上の信頼を弱める可能性があります。

---

### 6. 編集者・査読者の信頼低下

編集者や査読者は、原稿が著者自身の判断を反映しているのか、引用が確認されているのか、AI生成部分が適切に検証されているのかを懸念する場合があります。

プロンプトと出力を保存することで、人間とAIの関与の境界を明確にし、著者、編集者、査読者、読者のあいだの信頼形成を支援できます。

目的は、AIとのすべての細かなやり取りを公開することではありません。  
重要なのは、AIが文章作成、分析、翻訳、解釈、学術的推論に実質的に関与した場合、その意味のある記録を残すことです。

---

## 💡 解決策：プロンプト保存

プロンプト保存は、研究や学術執筆におけるAI使用を記録するための実践的な方法です。

推奨される実践は以下の通りです。

- プロンプトとAI出力を、できればPDF形式でタイムスタンプ付きの記録として保存する。
- 可能であれば、GitHub、OSF、DOI、バージョン履歴などと組み合わせて保存する。
- 使用したAIツール、モデル名、使用日を記録する。
- AIが生成した提案と、人間による最終判断を区別する。
- 構成、解釈、主張、翻訳、表現に影響した重要なAI利用については記録を残す。

PDF自体は完全な改ざん防止手段ではありません。  
しかし、透明なアーカイブ方法と組み合わせることで、後から確認可能な安定した記録として利用できます。

また、AIモデルは更新されるため、プロンプト保存によって完全な再現性が保証されるわけではありません。  
しかし、透明性、監査可能性、説明責任を高めることができます。

GitHubで実例・テンプレートを公開中です。

📁 https://github.com/KenjiroShiraishi/ai-use-policy-in-scholarly-writing  
📄 [プロンプトPDF保存例](https://github.com/KenjiroShiraishi/ai-use-policy-in-scholarly-writing/blob/main/prompt-example.pdf)

---

## 📚 References / 参考文献

- Shiraishi K. *AI Is Not an Author, but Its Instructions Should Be Preserved.* 2025.  
  https://github.com/KenjiroShiraishi/ai-use-policy-in-scholarly-writing

- Nature. *Tools such as ChatGPT threaten transparent science; here are our ground rules.* Nature. 2023;613(7945):612.  
  https://doi.org/10.1038/d41586-023-00191-1

- Thorp HH. *ChatGPT is fun, but not an author.* Science. 2023;379(6630):313.  
  https://doi.org/10.1126/science.adg7879

- NEJM AI. *Editorial Policies: Use of AI-Assisted Technologies.*  
  https://ai.nejm.org/about/editorial-policies

- Flanagin A et al. *Nonhuman “Authors” and Implications for the Integrity of Scientific Publication and Medical Knowledge.* JAMA. 2023;329(8):637–639.  
  https://doi.org/10.1001/jama.2023.1344

- Maynez J et al. *On Faithfulness and Factuality in Abstractive Summarization.* ACL 2020.  
  https://arxiv.org/abs/2005.00661
