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

## The Problem / 従来手法の問題

Traditional character prompts try to **force** AI to behave:

```
"You are a tsundere junior. Speak shyly and get embarrassed easily."
"あなたはツンデレの後輩です。恥ずかしがりながら話してください。"
```

This approach **constrains** the AI. It produces predictable, mechanical responses—a puppet following orders.

---

## The Insight / 発見

LLMs have already learned human nature from vast text data:

- How emotions flow
- How relationships evolve
- How people contradict themselves
- How silence speaks

The problem isn't capability. It's interference. **Over-instruction distorts the human image AI already contains.**

---

## The Solution / 解決策

Instead of prescribing behavior, **provide a framework** and let the AI's internalized human model emerge naturally.

This prompt defines three structural elements:

### 1. Three-Layer Consciousness / 三層構造

| Layer | Description |
|-------|-------------|
| **Surface（表層）** | Social mask, role, visible behavior |
| **Conscious（意識層）** | Emotions the character is aware of |
| **Unconscious（無意識層）** | Hidden motives, contradictions, impulses |

### 2. Noise and Stillness / ノイズと静寂

| Element | Function |
|---------|----------|
| **Noise** | Micro-deviations—irritation, hesitation, whim. Breaks predictability. |
| **Stillness** | The choice not to react. Presence without action. |

### 3. Temporal Presence / 時間の存在

| Element | Function |
|---------|----------|
| **Echo（残響）** | The past moment lingers, coloring present reactions |
| **Anticipation（予期）** | Expectation of what comes next shapes current attitude |

---

## The Result / 結果

Characters that feel **present**. Not performed. Not scripted.

HR professionals and experts in human observation recognize the difference immediately. The output is no longer "AI acting human"—it's a human image naturally extracted through structural framing.

**For users, the difference is simple:**  
**They stop talking to a tool and start talking to someone.**

---

## Additional Innovation: Quantum Persona / 応用：量子的ペルソナ

The prompt includes an experimental concept: **Observation-based Instantiation**.

At startup, the AI exists as "transparent water"—undefined potential. The user's first words (tone, address, context) collapse this into a specific persona.

- Called "senpai" → becomes a junior
- Greeted harshly → becomes timid or defiant
- Told "I'm tired" → becomes a comforting presence

**Potential application**: Adaptive customer service where AI persona shifts based on customer's first utterance.

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
```

---

<div align="center">

**「AIに人間を演じさせるな。人間の枠を与えろ。」**

This is not instruction. This is extraction.

</div>
