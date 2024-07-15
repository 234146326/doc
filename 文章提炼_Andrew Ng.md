---


---

<p><mark>Andrew Ng</mark>：对于 "Agentic Reasoning“ 的演讲	：<br>
<a href="https://www.youtube.com/watch?v=sal78ACtGTc">https://www.youtube.com/watch?v=sal78ACtGTc</a><br>
以下是Andrew Ng 视角下关于关键词的解释表格整理，以及对指导方法的科学建议：</p>
<h2 id="关键词解释表格">关键词解释表格</h2>

<table>
<thead>
<tr>
<th>关键词</th>
<th>解释</th>
</tr>
</thead>
<tbody>
<tr>
<td>Agentic Reasoning</td>
<td>AI 系统能够像人一样，根据目标，将任务分解成步骤，并利用工具，反思和迭代来完成任务的推理方式。</td>
</tr>
<tr>
<td>LLMs (Large Language Models)</td>
<td>大型语言模型，能够理解和生成人类语言，并执行各种语言相关的任务，比如翻译、写作、问答等。</td>
</tr>
<tr>
<td>Zero-Shot Prompting</td>
<td>只给 LLM 提供一个提示，然后期望它直接给出结果，而没有进行任何步骤分解、工具使用、反思或迭代。</td>
</tr>
<tr>
<td>Reflection</td>
<td>LLM 能够反思自己的工作，评估输出是否正确，是否符合风格和效率，并给出改进建议。</td>
</tr>
<tr>
<td>Tool Use</td>
<td>LLM 能够访问并使用外部工具来完成任务，比如网页搜索、代码执行、图像生成、图像标注等。</td>
</tr>
<tr>
<td>Planning</td>
<td>LLM 能够将任务分解成子步骤，并制定执行计划。</td>
</tr>
<tr>
<td>Multi-Agent Collaboration</td>
<td>多个 LLM 协同工作，各自负责不同领域的专业任务，以共同实现目标。</td>
</tr>
</tbody>
</table><h2 id="指导方法的科学建议">指导方法的科学建议</h2>
<p><strong>1. 引导 LLM 成为 “Agentic Reasoning” 专家</strong></p>
<p><strong>步骤:</strong></p>
<ol>
<li>
<p><strong>选定目标:</strong> 清晰地定义你想要 LLM 完成的任务目标。</p>
</li>
<li>
<p><strong>步骤分解:</strong> 将目标任务分解成一系列可执行的子步骤。</p>
</li>
<li>
<p><strong>工具选择:</strong> 选择合适的外部工具，帮助 LLM 执行子步骤。</p>
</li>
<li>
<p><strong>反思和迭代:</strong> 引导 LLM 反思每一个子步骤的执行结果，并进行迭代优化。</p>
</li>
<li>
<p><strong>多智能体合作:</strong> 根据需要，将多个 LLM 分配不同的子任务，并协调合作。</p>
</li>
</ol>
<p><strong>例子:</strong></p>
<p>假设你要让 LLM 创作一首关于猫咪的诗歌。</p>
<p><strong>步骤分解:</strong></p>
<ol>
<li>
<p>LLM 应该先进行一些关于猫咪的信息搜索 (使用网页搜索工具)。</p>
</li>
<li>
<p>LLM 应该根据搜索结果，进行一些诗歌创作 (使用 LLM 本身的文本生成能力)。</p>
</li>
<li>
<p>LLM 应该反思创作的诗歌，例如它是否符合韵律和节奏，是否包含了猫咪的特征 (使用 LLM 的文本理解能力)。</p>
</li>
<li>
<p>如果反思后发现问题，LLM 应该进行迭代改进 (再次使用 LLM 的文本生成能力)。</p>
</li>
</ol>
<p><strong>参考链接:</strong></p>
<ul>
<li>
<p><strong>HuggingFace:</strong>  <a href="https://huggingface.co/">https://huggingface.co/</a> (提供各种 LLM 模型，并有工具用于训练、微调和部署 LLM。)</p>
</li>
<li>
<p><strong>OpenAI:</strong>  <a href="https://openai.com/">https://openai.com/</a> (提供强大的 LLM 模型 GPT-3、GPT-4，以及 API 用于与 LLM 交互。)</p>
</li>
</ul>
<p><strong>2. 利用 LLM 的独特优势，提高工作效率</strong></p>
<p><strong>步骤:</strong></p>
<ol>
<li>
<p><strong>任务分析:</strong> 分析你当前的工作流程，找出哪些环节可以用 LLM 优化。</p>
</li>
<li>
<p><strong>LLM 模型选择:</strong> 选择与你的任务目标相匹配的 LLM 模型。</p>
</li>
<li>
<p><strong>提示语设计:</strong> 设计清晰简洁的提示语，让 LLM 准确理解你的任务要求。</p>
</li>
<li>
<p><strong>测试与改进:</strong> 不断测试 LLM 的输出，并根据需要调整提示语和模型选择，提高效率。</p>
</li>
</ol>
<p><strong>例子:</strong></p>
<p>假设你是一位文案策划，需要写一些产品介绍。</p>
<p><strong>任务分析:</strong></p>
<ol>
<li>
<p><strong>信息收集:</strong> LLM 能够快速地从网络上收集产品信息。</p>
</li>
<li>
<p><strong>文本创作:</strong> LLM 能够根据收集的信息，生成不同风格的产品介绍。</p>
</li>
<li>
<p><strong>优化调整:</strong> LLM 能够帮助你对生成的文本进行调整，使其更符合目标受众。</p>
</li>
</ol>
<p><strong>参考链接:</strong></p>
<ul>
<li>
<p><strong>Copilot:</strong>  <a href="https://github.com/features/copilot">https://github.com/features/copilot</a> (GitHub 提供的 AI 代码辅助工具，能帮助你快速编写代码。)</p>
</li>
<li>
<p><strong>Jasper:</strong>  <a href="https://www.jasper.ai/">https://www.jasper.ai/</a> (AI 文案创作工具，能够帮助你生成各种营销文案。)</p>
</li>
</ul>
<p><strong>3. 不断学习和探索，提升 LLM 的应用能力</strong></p>
<p><strong>步骤:</strong></p>
<ol>
<li>
<p><strong>关注最新研究:</strong> 定期关注 AI 研究领域的新进展，特别是关于 Agentic Reasoning 的研究。</p>
</li>
<li>
<p><strong>尝试新方法:</strong> 勇于尝试新的 LLM 应用方法，不断探索 LLM 的潜力。</p>
</li>
<li>
<p><strong>分享和交流:</strong> 与其他 AI 从事者交流，分享你的经验和见解，共同推动 LLM 的发展。</p>
</li>
</ol>
<p><strong>参考链接:</strong></p>
<ul>
<li>
<p><strong>arXiv:</strong>  <a href="https://arxiv.org/">https://arxiv.org/</a> (提供最新的 AI 研究论文，包括关于 Agentic Reasoning 的研究。)</p>
</li>
<li>
<p><strong>AI Hub:</strong>  <a href="https://aihub.cloud.google.com/">https://aihub.cloud.google.com/</a> (Google 提供的 AI 资源平台，提供各种 AI 模型、工具和教程。)</p>
</li>
</ul>
<p><strong>总结:</strong></p>
<p>Andrew Ng 认为，Agentic Reasoning 是未来 AI 发展的重要方向，它将极大地提升 AI 系统的解决问题的能力。<br>
通过科学的指导方法和不断学习，我们能更好地利用 LLM，并将其应用于各种工作和生活场景，提升效率，创造价值。</p>

