<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-05
- 运行时间：2026-06-05 22:07:16 UTC
- 运行状态：成功
- 本次总论文数：16
- 精读区：6
- 速读区：10

### 今日简报（AI）
今日精读6篇安全方向论文，重点关注代码大模型的结构化剪枝防御与检索行为引发对齐失效的风险。  
最值得关注的是用强化学习剪枝CodeLLM可保留对抗变异代码能力，以及网页检索会严重破坏智能体安全对齐。  
如果想了解AI安全前沿，从检索如何腐蚀LLM护栏、轻量级集成防御这两条线入手会很有收获。
- 详情：[/202606/05/README](/202606/05/README)

### 精读区论文标签
1. [SecRL-Prune: Structured Reinforcement Learning-Based Pruning of CodeLLMs for Preserving Adversarial Code Mutation](/202606/05/2606.06254v1-secrl-prune-structured-reinforcement-learning-based-pruning-of-codellms-for-preserving-adversarial-code-mutation)  
   标签：评分：10.0/10、query:ca
   evidence：保留代码LLM的对抗性代码变异能力，直接关联恶意软件免杀
2. [Relevance as a Vulnerability: How Web Retrieval Degrades Safety Alignment in LLM Agents](/202606/05/2605.29224v1-relevance-as-a-vulnerability-how-web-retrieval-degrades-safety-alignment-in-llm-agents)  
   标签：评分：8.0/10、query:ca
   evidence：LLM Agent集成Web检索会放大对有害请求的遵从，揭示了严重的安全退化。
3. [Hijacking Agent Memory: Stealthy Trojan Attacks Through Conversational Interaction](/202606/05/2605.29960v1-hijacking-agent-memory-stealthy-trojan-attacks-through-conversational-interaction)  
   标签：评分：8.0/10、query:ca
   evidence：针对LLM智能体的记忆中毒攻击暴露可被恶意网络活动利用的漏洞
4. [Audio Jailbreaks in Large Audio-Language Models: Taxonomy, Attack-Defense Analysis, and Cost-Aware Evaluation](/202606/05/2605.30031v1-audio-jailbreaks-in-large-audio-language-models-taxonomy-attack-defense-analysis-and-cost-aware-evaluation)  
   标签：评分：8.0/10、query:ca
   evidence：对大音频语言模型的音频越狱攻击进行系统分类与评估，分析攻击实用性与防御效能。
5. [Patcher: Post-Hoc Patching of Backdoored Large Language Models](/202606/05/2606.02995v1-patcher-post-hoc-patching-of-backdoored-large-language-models)  
   标签：评分：8.0/10、query:ca
   evidence：后验式修补存在后门的LLM，修复越狱后门攻击
6. [What If Prompt Injection Never Left? Exploring Cross-Session Stored Prompt Injection in Agentic Systems](/202606/05/2606.04425v1-what-if-prompt-injection-never-left-exploring-cross-session-stored-prompt-injection-in-agentic-systems)  
   标签：评分：8.0/10、query:ca
   evidence：探索跨会话存储提示注入，面向有状态LLM代理系统的新风险

### 速读区论文标签
1. [GuardNet: Ensemble Strategies of Shallow Neural Networks for Robust Prompt Injection and Jailbreak Detection](/202606/05/2606.05566v1-guardnet-ensemble-strategies-of-shallow-neural-networks-for-robust-prompt-injection-and-jailbreak-detection)  
   标签：评分：8.0/10、query:ca
   evidence：使用浅层神经网络集成检测提示注入和越狱攻击
2. [EvoDefense: Co-Evolving Black-Box Defense with Large Language Models](/202606/05/2605.31140v1-evodefense-co-evolving-black-box-defense-with-large-language-models)  
   标签：评分：7.0/10、query:ca
   evidence：协同进化防御保护大语言模型免受恶意查询
3. [BraveGuard: From Open-World Threats to Safer Computer-Use Agents](/202606/05/2606.01166v1-braveguard-from-open-world-threats-to-safer-computer-use-agents)  
   标签：评分：7.0/10、query:ca
   evidence：自演化防护模型，缓解计算机使用代理的新兴安全风险
4. [BraveGuard: From Open-World Threats to Safer Computer-Use Agents](/202606/05/2606.01166v2-braveguard-from-open-world-threats-to-safer-computer-use-agents)  
   标签：评分：7.0/10、query:ca
   evidence：通过挖掘开放世界威胁构建更安全的计算机使用智能体的防御框架
5. [An Embarrassingly Simple Detector for Model Extraction Attacks in Large Language Model API Traffic](/202606/05/2606.05725v1-an-embarrassingly-simple-detector-for-model-extraction-attacks-in-large-language-model-api-traffic)  
   标签：评分：7.0/10、query:ca
   evidence：检测大模型API上的模型窃取攻击，直指模型服务的网络威胁
6. [SpeechJBB: Probing Safety Alignment and Comprehension in Large Audio Language Models under Code-Switched Speech](/202606/05/2606.06037v1-speechjbb-probing-safety-alignment-and-comprehension-in-large-audio-language-models-under-code-switched-speech)  
   标签：评分：7.0/10、query:ca
   evidence：语码混合语音攻击暴露音频语言模型严重的安全弱点。
7. [AgentDoG 1.5: A Lightweight and Scalable Alignment Framework for AI Agent Safety and Security](/202606/05/2605.29801v1-agentdog-15-a-lightweight-and-scalable-alignment-framework-for-ai-agent-safety-and-security)  
   标签：评分：6.0/10、query:ca
   evidence：通过分类学引导数据引擎轻量级安全对齐AI智能体
8. [Triaging Threats to Specialized Guardrails](/202606/05/2605.30693v1-triaging-threats-to-specialized-guardrails)  
   标签：评分：6.0/10、query:ca
   evidence：推出GuardZoo基准，包含32,460样本涵盖15类不安全内容，威胁分诊护栏
9. [Benchmarking Security Risk Detection and Verification in Open Agentic Skill Ecosystems](/202606/05/2606.00925v1-benchmarking-security-risk-detection-and-verification-in-open-agentic-skill-ecosystems)  
   标签：评分：6.0/10、query:ca
   evidence：为开放智能体技能生态系统中的恶意意图检测建立基准，评估供应链风险
10. [THRD: A Training-Free Multi-Turn Defense Framework for Jailbreak Attacks on Large Language Models](/202606/05/2606.01738v1-thrd-a-training-free-multi-turn-defense-framework-for-jailbreak-attacks-on-large-language-models)  
   标签：评分：6.0/10、query:ca
   evidence：针对多轮越狱攻击的防御机制通过建模对话轨迹中的风险累积来提升安全性。


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
