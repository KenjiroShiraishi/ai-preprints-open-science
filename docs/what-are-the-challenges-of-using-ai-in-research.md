# 🤖 What Are the Challenges of Using AI in Research? / 研究におけるAI使用の課題とは？

## 🌐 English

Generative AI is powerful at pattern recognition across vast text datasets. As a result, it performs well at structural tasks such as drafting text, correcting grammar, summarizing content, and even assisting with medical diagnosis from images.  
However, it tends to struggle with factual accuracy, deep contextual understanding, and ethical reasoning—areas involving meaning and value.  
The six challenges below reflect these limitations in the context of academic research.

### ⚠️ Six Overlooked Challenges

- **Hallucinated Citations**  
  AI often generates plausible but non-existent references. Without input logs, authors cannot be held accountable or correct such errors transparently.  
  *Ref: Maynez et al. 2020*

- **Unclear Intellectual Contribution**  
  When AI drafts or structures content, who takes responsibility for accuracy and ethics? Without documentation, the line between AI and human authorship is blurred.  
  *Ref: Flanagin et al. 2023 (JAMA)*

- **Reinforcement of Hidden Biases**  
  Prompts and outputs can contain stigmatizing associations inherited from training data.

- **Barriers to Reproducibility**  
  Prompts act like algorithmic inputs. Saving them aligns with FAIR principles and supports open science.

- **Opaque Multi-AI Workflows**  
  Authors often combine GPT for summarization, Claude for translation, etc. Without documentation, it’s impossible to trace which model did what.

- **Erosion of Editorial Trust**  
  Editors and reviewers may doubt authorial integrity. Showing prompts can clarify the human/AI boundary and foster transparency.

### 💡 Proposed Practice: Prompt Preservation

- Save both prompts and AI outputs as timestamped PDF files.  
- PDFs preserve timestamps and resist post-hoc editing better than markdown or text.  
- Public templates and examples available:

📁 https://github.com/KenjiroShiraishi/ai-use-policy-in-scholarly-writing  
📄 [Prompt PDF Example](https://github.com/KenjiroShiraishi/ai-use-policy-in-scholarly-writing/blob/main/prompt-example.pdf)

---

## 🇯🇵 日本語

生成AIには、膨大なテキストデータからパターンを抽出する力があります。そのため、文章の構成や文法、要約、画像から病気を発見する診断補助といった「形式的な処理」は得意です。  
一方で、事実の正確性や深い文脈理解、倫理的判断といった「意味や価値に関わる処理」は不得意とされています。  
以下では、こうしたAIの特性をふまえ、研究利用時に見落とされやすい課題を6点に整理します。

### ⚠️ 見落とされがちな6つの課題

- **存在しない引用の生成（ハルシネーション）**  
  実在しない文献をもっともらしく生成することがあり、プロンプト記録がなければ責任追跡ができません。  
  *参考：Maynez et al. 2020*

- **知的貢献の所在が不明瞭になる**  
  AIが構成や文案を作成した場合、倫理的・事実的な責任の所在が曖昧になります。  
  *参考：Flanagin et al. 2023（JAMA）*

- **見えにくいバイアスの温存**  
  精神疾患＝犯罪性などのステレオタイプが、無意識に出力に含まれる場合があります。

- **再現性（reproducibility）の欠如**  
  プロンプトは一種の「入力アルゴリズム」と見なすべきです。FAIR原則に基づく保存が必要です。

- **複数AIツールの利用履歴が追えない**  
  GPTで要約し、Claudeで翻訳し、Geminiで構造化…という使い方が増える中、どの部分に何を使ったか分からなくなります。

- **編集者・査読者の信頼低下**  
  「これは本当に著者が書いたのか？」という疑念に対して、プロンプト提示は境界を明確にし、信頼構築に寄与します。

### 💡 解決策：PDFによるプロンプト保存

- MarkdownやTXTでは改変履歴が残りにくい  
- PDFはタイムスタンプ保存と改ざん防止に適している  
- GitHubで実例・テンプレートを公開中：

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
