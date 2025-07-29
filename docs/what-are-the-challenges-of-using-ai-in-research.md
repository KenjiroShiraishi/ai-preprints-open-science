# 🤖 What Are the Challenges of Using AI in Research? / 研究におけるAI使用の課題とは？

---

## 🌐 English

Generative AI tools like ChatGPT, Claude, and Gemini are increasingly used in academic writing and research. While journals such as Nature and NEJM AI now require AI use disclosure, deeper ethical and practical concerns remain underaddressed.

This section outlines **six key risks of undocumented AI use** in research and proposes a practical, open-access solution: **saving prompts and outputs as timestamped PDFs**.

### ⚠️ Six Overlooked Challenges

1. **Hallucinated Citations**  
   AI often generates plausible but non-existent references. Without input logs, authors cannot be held accountable or correct such errors transparently.

2. **Unclear Intellectual Contribution**  
   When AI drafts or structures content, who takes responsibility for accuracy and ethics? Without documentation, the line between AI and human authorship is blurred.

3. **Reinforcement of Hidden Biases**  
   Prompts and outputs can contain stigmatizing associations inherited from training data. Understanding bias requires access to the full prompt-output record.

4. **Barriers to Reproducibility**  
   Prompts act like algorithmic inputs. Saving them aligns with FAIR principles (Findable, Accessible, Interoperable, Reusable) and supports open science.

5. **Opaque Multi-AI Workflows**  
   Authors often combine GPT for summarization, Claude for translation, etc. Without documentation, it’s impossible to trace which model did what.

6. **Erosion of Editorial Trust**  
   Editors and reviewers may doubt authorial integrity. Showing prompts can clarify the human/AI boundary and foster transparency.

### 💡 Proposed Practice: Prompt Preservation  
Save both prompts and AI outputs as timestamped PDF files. Unlike markdown or text, PDFs are harder to alter post hoc and can retain timestamps.  
This practice enables:

- Authorship traceability  
- Journal compliance (NEJM AI, BMJ, JAMA)  
- Reproducibility and auditability  
- Cultural shift toward transparent AI use  

📁 See examples here:  
🔗 https://github.com/KenjiroShiraishi/ai-use-policy-in-scholarly-writing  
📄 [Example PDF](https://github.com/KenjiroShiraishi/ai-use-policy-in-scholarly-writing/blob/main/prompt-example.pdf)

---

## 🇯🇵 日本語

ChatGPT、Claude、Geminiなどの生成AIは、研究や論文執筆において急速に普及しています。しかし、AI使用を「開示するだけ」でよいのかという点については、まだ十分な議論がされていません。

ここでは、**AI使用の課題6点**を整理し、その解決策として**プロンプトと出力のPDF保存**を提案します。

### ⚠️ 見落とされがちな6つの課題

1. **存在しない引用の生成（ハルシネーション）**  
   実在しない文献をもっともらしく生成することがあり、プロンプト記録がなければ責任追跡ができません。

2. **知的貢献の所在が不明瞭になる**  
   AIが構成や文案を作成した場合、倫理的・事実的な責任の所在が曖昧になります。

3. **見えにくいバイアスの温存**  
   精神疾患＝犯罪性などのステレオタイプが、無意識に出力に含まれる場合があります。

4. **再現性（reproducibility）の欠如**  
   プロンプトは一種の「入力アルゴリズム」と見なすべきです。FAIR原則に基づく保存が必要です。

5. **複数AIツールの利用履歴が追えない**  
   GPTで要約し、Claudeで翻訳し、Geminiで構造化…という使い方が増える中、どの部分に何を使ったか分からなくなります。

6. **編集者・査読者の信頼低下**  
   「これは本当に著者が書いたのか？」という疑念に対して、プロンプト提示は境界を明確にし、信頼構築に寄与します。

### 💡 解決策：PDFによるプロンプト保存

- MarkdownやTXTでは改変履歴が残りにくい  
- PDFはタイムスタンプ保存と改ざん防止に適している  
- GitHubで実例・テンプレートを公開中：

📁 https://github.com/KenjiroShiraishi/ai-use-policy-in-scholarly-writing  
📄 [プロンプトPDF保存例](https://github.com/KenjiroShiraishi/ai-use-policy-in-scholarly-writing/blob/main/prompt-example.pdf)

---

## 📚 References / 参考文献

- Shiraishi K. *AI Is Not an Author, but Its Instructions Should Be Preserved: Ethical and Practical Considerations for Saving Prompts in Scholarly Writing.* 2025.  
  https://github.com/KenjiroShiraishi/ai-use-policy-in-scholarly-writing

- Nature. *Tools such as ChatGPT threaten transparent science; here are our ground rules.* Nature. 2023;613(7945):612.  
  doi:10.1038/d41586-023-00191-1

- Thorp HH. *ChatGPT is fun, but not an author.* Science. 2023;379(6630):313.  
  doi:10.1126/science.adg7879

- NEJM AI. *Editorial Policies: Use of AI-Assisted Technologies.*  
  https://ai.nejm.org/about/editorial-policies

- Flanagin A et al. *Nonhuman “Authors” and Implications for the Integrity of Scientific Publication and Medical Knowledge.* JAMA. 2023;329(8):637–639.  
  doi:10.1001/jama.2023.1344

---

✅ *Preserving prompts is not a burden—it’s the future of responsible scholarship.*
