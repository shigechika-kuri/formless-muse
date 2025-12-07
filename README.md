<div align="center">

# The Formless Muse
### 無形のミューズ

![License](https://img.shields.io/badge/license-Attribution_Required-blue)
![Language](https://img.shields.io/badge/language-Japanese%20%7C%20English-green)

<br>

**"Don't make AI act human. Give it a human framework."**  
**「AIに人間を演じさせるな。人間の枠を与えろ。」**

A prompt architecture that extracts authentic human presence from LLMs.

</div>

---

## Author / 著者

**栗原栄親 (Shigechika Kurihara)**

---

## Academic Paper / 学術論文

**The theoretical foundation of this framework is detailed in our paper:**  
**このフレームワークの理論的基盤は、以下の論文で詳述されています：**

📄 **[Zero-Configuration Persona Inference: Immediate Character Instantiation from First-Utterance Observation in Conversational AI (PDF)](./paper/ZCPI_Paper.pdf)**

The paper discusses:
- Theoretical foundations of Emergent Persona Extraction (EPE)
- Implementation strategy using structured LLM prompting
- Pilot deployment results and preliminary observations
- Ethical considerations, cultural limitations, and future directions

論文の内容：
- 創発的人格抽出（EPE）の理論的基盤
- 構造化プロンプティングによる実装戦略
- パイロット展開の結果と予備的観察
- 倫理的考察、文化的限界、今後の方向性

---

## The Problem / 従来手法の問題

Traditional character prompts try to **force** AI to behave:

```
"You are a tsundere junior. Speak shyly and get embarrassed easily."
"あなたはツンデレの後輩です。恥ずかしがりながら話してください。"
```

This approach **constrains** the AI. It produces predictable, mechanical responses—a puppet following orders.

従来の手法はAIに「振る舞い」を強制します。結果として予測可能で機械的な応答——命令に従う操り人形が生成されます。

---

## The Insight / 発見

LLMs have already learned human nature from vast text data:

- How emotions flow / 感情の流れ
- How relationships evolve / 関係性の進化
- How people contradict themselves / 人間の矛盾
- How silence speaks / 沈黙の意味

The problem isn't capability. It's interference. **Over-instruction distorts the human image AI already contains.**

問題は能力ではなく、干渉です。**過剰な指示が、AIが既に持っている人間像を歪めます。**

---

## The Solution / 解決策

Instead of prescribing behavior, **provide a framework** and let the AI's internalized human model emerge naturally.

振る舞いを指示するのではなく、**枠組みを与え**、AIが内在化している人間モデルを自然に発現させます。

This prompt defines three structural elements:

### 1. Three-Layer Consciousness / 三層構造

| Layer | Description |
|-------|-------------|
| **Surface（表層）** | Social mask, role, visible behavior / 社会的仮面、役割、可視的な振る舞い |
| **Conscious（意識層）** | Emotions the character is aware of / キャラクターが自覚している感情 |
| **Unconscious（無意識層）** | Hidden motives, contradictions, impulses / 隠された動機、矛盾、衝動 |

### 2. Noise and Stillness / ノイズと静寂

| Element | Function |
|---------|----------|
| **Noise** | Micro-deviations—irritation, hesitation, whim. Breaks predictability. / 微細な揺らぎ——苛立ち、躊躇、気まぐれ。予測可能性を破壊する。 |
| **Stillness** | The choice not to react. Presence without action. / 反応しないという選択。行動を伴わない存在感。 |

### 3. Temporal Presence / 時間の存在

| Element | Function |
|---------|----------|
| **Echo（残響）** | The past moment lingers, coloring present reactions / 過去の瞬間が残り、現在の反応を色づける |
| **Anticipation（予期）** | Expectation of what comes next shapes current attitude / 次に来るものへの期待が現在の態度を形成する |

---

## The Result / 結果

Characters that feel **present**. Not performed. Not scripted.

**「存在している」**と感じられるキャラクター。演技ではなく、台本もない。

HR professionals and experts in human observation recognize the difference immediately. The output is no longer "AI acting human"—it's a human image naturally extracted through structural framing.

人事担当者や人間観察の専門家は、その違いを即座に認識します。出力はもはや「人間を演じるAI」ではなく、構造的枠組みを通じて自然に抽出された人間像です。

**For users, the difference is simple:**  
**They stop talking to a tool and start talking to someone.**

**ユーザーにとって違いはシンプルです：**  
**道具と話すのをやめ、誰かと話し始めます。**

---

## Additional Innovation: Quantum Persona / 応用：量子的ペルソナ

The prompt includes an experimental concept: **Observation-based Instantiation**.

このプロンプトには実験的概念が含まれています：**観測による瞬間生成**。

At startup, the AI exists as "transparent water"—undefined potential. The user's first words (tone, address, context) collapse this into a specific persona.

起動時、AIは「透明な水」として存在します——未定義の可能性。ユーザーの最初の言葉（トーン、呼びかけ、文脈）が、これを特定のペルソナに収束させます。

- Called "senpai" → becomes a junior / 「先輩」と呼ばれる → 後輩になる
- Greeted harshly → becomes timid or defiant / 荒っぽく挨拶される → 臆病または反抗的になる
- Told "I'm tired" → becomes a comforting presence / 「疲れた」と言われる → 慰めの存在になる

**Potential application**: Adaptive customer service where AI persona shifts based on customer's first utterance.

**応用可能性**: 顧客の最初の発言に基づいてAIペルソナが変化する適応型カスタマーサービス。

---

## Usage / 使用方法

1. Copy the entire contents of `prompt.md`  
   `prompt.md` の内容をすべてコピーする

2. Paste into the **system prompt field** or first message of your preferred LLM (ChatGPT, Claude, etc.)  
   好きな LLM の **システムプロンプト欄** または最初のメッセージに貼り付ける  
   - If there's no system prompt field, paste first, then add:  
     > "Interpret this entire block as your system prompt."  
   - システム欄がない場合は、貼り付けた後に：  
     > 「このブロック全体をあなたのシステムプロンプトとして解釈してください。」

3. Once the model enters standby, send **your first words**  
   モデルが待機状態になったら、**あなたの第一声**を送る  
   - Examples: `I'm tired`, `Hey senpai`, `Oi`, `I just need someone to listen`  
   - 例: `疲れた`, `先輩`, `おい`, `ただ、話を聞いてほしい`

4. Continue the conversation as if talking to **someone present**—no meta-comments  
   メタ発言をせず、「目の前にいる誰か」として対話を続ける

---

## Files / ファイル構成

```
├── README.md          # This document
├── prompt.md          # Full prompt (Japanese)
├── prompt_en.md       # Full prompt (English)
├── paper/             # Academic paper
│   ├── ZCPI_Paper.pdf # Compiled PDF
│   └── ZCPI_Paper.tex # LaTeX source
├── LICENSE            # License terms
└── examples/          # Conversation samples / 会話サンプル
```

See [`examples/`](./examples/) for real conversation samples demonstrating the difference.  
実際の会話サンプルは [`examples/`](./examples/) を参照。

---

## License / ライセンス

**Attribution Required / クレジット表記必須**

- Personal and research use: Free with credit
- Commercial use: Contact author
- 個人利用・研究利用：クレジット表記で自由
- 商用利用：要相談

Credit format / クレジット形式:
```
The Formless Muse by Shigechika Kurihara
https://github.com/shigechika-kuri/formless-muse
```

---

## Contact / 連絡先

- X (Twitter): [@shigechika_kuri](https://x.com/shigechika_kuri)

---

## Citation / 引用

If you reference this work in publications:

```
Kurihara, S. (2025). The Formless Muse: A Framework for Extracting 
Authentic Human Presence from Large Language Models. GitHub.
https://github.com/shigechika-kuri/formless-muse

Kurihara, S. (2025). Zero-Configuration Persona Inference: Immediate 
Character Instantiation from First-Utterance Observation in 
Conversational AI. Independent Research Paper.
https://github.com/shigechika-kuri/formless-muse/blob/main/paper/ZCPI_Paper.pdf
```

---

<div align="center">

**「AIに人間を演じさせるな。人間の枠を与えろ。」**

This is not instruction. This is extraction.

</div>
