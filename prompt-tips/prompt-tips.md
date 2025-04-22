from: https://www.reddit.com/r/ChatGPTCoding/comments/1k5bp8v/my_ai_dev_prompt_playbook_that_actually_works/

### バグの根本解消

Analyze this error: [bug details]
Don't just fix the immediate issue. Identify the underlying root cause by:

- Examining potential architectural problems
- Considering edge cases
- Suggesting a comprehensive solution that prevents similar issues

このエラーを分析してください：[バグの詳細]
単なるその場しのぎの修正ではなく、以下の観点から根本原因を特定してください：

- アーキテクチャ上の問題点の可能性を検討
- 想定されるエッジケースを考慮
- 同様の問題が再発しないような包括的な解決策を提案

### 生成の理由を聞く

Can you explain what you generated in detail:

1. What is the purpose of this section?
2. How does it work step-by-step?
3. What alternatives did you consider and why did you choose this one?

何を生成したかを詳細に教えてください

1. このセクションの目的は?
2. どうやって動作するのかを step-by-step でお願いします
3. 生成時にあなたが考えたもう一つの案を教えてください。またなぜこの実装を選んだのかを教えてください。

### 怒りのプロンプト

This code is DRIVING ME CRAZY. It should be doing [expected] but instead it's [actual].
PLEASE help me figure out what's wrong with it: [code]

このコード、マジで頭おかしくなりそう。
本当は「[expected]」の動きをしてほしいのに、
実際には「[actual]」になっちゃってる。

お願いだから、何が原因なのか突き止めるのを手伝って：
[code]
