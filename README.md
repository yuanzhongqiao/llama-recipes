<div class="Box-sc-g0xbh4-0 QkQOb js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="107350334" _msthash="234">Llama 食谱：开始使用 Meta 的 Llama 模型的示例</h1><a id="user-content-llama-recipes-examples-to-get-started-using-the-llama-models-from-meta" class="anchor" aria-label="永久链接：Llama 食谱：开始使用 Meta 的 Llama 模型的示例" href="#llama-recipes-examples-to-get-started-using-the-llama-models-from-meta" _mstaria-label="3936998" _msthash="235"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>

<p dir="auto" _msttexthash="3845683855" _msthash="236">'llama-recipes' 存储库是 <a href="https://github.com/meta-llama/llama-models" _istranslated="1">Meta Llama</a> 模型的配套版本。我们在此存储库中支持最新版本 <a href="https://github.com/meta-llama/llama-models/blob/main/models/llama3_2/MODEL_CARD_VISION.md" _istranslated="1">Llama 3.2 Vision</a> 和 <a href="https://github.com/meta-llama/llama-models/blob/main/models/llama3_2/MODEL_CARD.md" _istranslated="1">Llama 3.2 Text</a>。此存储库包含示例脚本和笔记本，用于在各种使用案例中开始使用模型，包括微调域适应以及使用 Llama 和 LLM 生态系统中的其他工具构建基于 LLM 的应用程序。此处的示例在本地、云中和本地使用 Llama。</p>
<div class="markdown-alert markdown-alert-tip" dir="auto"><p class="markdown-alert-title" dir="auto"><svg class="octicon octicon-light-bulb mr-2" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="M8 1.5c-2.363 0-4 1.69-4 3.75 0 .984.424 1.625.984 2.304l.214.253c.223.264.47.556.673.848.284.411.537.896.621 1.49a.75.75 0 0 1-1.484.211c-.04-.282-.163-.547-.37-.847a8.456 8.456 0 0 0-.542-.68c-.084-.1-.173-.205-.268-.32C3.201 7.75 2.5 6.766 2.5 5.25 2.5 2.31 4.863 0 8 0s5.5 2.31 5.5 5.25c0 1.516-.701 2.5-1.328 3.259-.095.115-.184.22-.268.319-.207.245-.383.453-.541.681-.208.3-.33.565-.37.847a.751.751 0 0 1-1.485-.212c.084-.593.337-1.078.621-1.489.203-.292.45-.584.673-.848.075-.088.147-.173.213-.253.561-.679.985-1.32.985-2.304 0-2.06-1.637-3.75-4-3.75ZM5.75 12h4.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5ZM6 15.25a.75.75 0 0 1 .75-.75h2.5a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1-.75-.75Z"></path></svg><font _mstmutation="1" _msttexthash="5552768" _msthash="237">提示</font></p><p dir="auto" _msttexthash="68087877" _msthash="238">通过以下新配方开始使用 Llama 3.2：</p>
<ul dir="auto">
<li><a href="https://github.com/meta-llama/llama-recipes/blob/main/recipes/quickstart/finetuning/finetune_vision_model.md" _msttexthash="6216522" _msthash="239">微调 Llama 3.2 Vision</a></li>
<li><a href="https://github.com/meta-llama/llama-recipes/blob/main/recipes/quickstart/inference/local_inference/README.md#multimodal-inference" _msttexthash="72835503" _msthash="240">使用 Llama 3.2 Vision 进行多模态推理</a></li>
<li><a href="https://github.com/meta-llama/llama-recipes/blob/main/recipes/responsible_ai/llama_guard/llama_guard_text_and_vision_inference.ipynb" _msttexthash="139578205" _msthash="241">Llama Guard 1B 上的推理 + Llama Guard 11B-Vision 上的多模态推理</a></li>
</ul>
</div>

<div class="markdown-alert markdown-alert-note" dir="auto"><p class="markdown-alert-title" dir="auto"><svg class="octicon octicon-info mr-2" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8Zm8-6.5a6.5 6.5 0 1 0 0 13 6.5 6.5 0 0 0 0-13ZM6.5 7.75A.75.75 0 0 1 7.25 7h1a.75.75 0 0 1 .75.75v2.75h.25a.75.75 0 0 1 0 1.5h-2a.75.75 0 0 1 0-1.5h.25v-2h-.25a.75.75 0 0 1-.75-.75ZM8 6a1 1 0 1 1 0-2 1 1 0 0 1 0 2Z"></path></svg><font _mstmutation="1" _msttexthash="5121168" _msthash="242">注意</font></p><p dir="auto"><font _mstmutation="1" _msttexthash="481311233" _msthash="243">Llama 3.2 遵循与 Llama 3.1 相同的提示模板，其中有一个新的特殊标记表示多模态模型的输入图像。</font><code>&lt;|image|&gt;</code></p>
<p dir="auto" _msttexthash="370242808" _msthash="244">有关图像推理、工具调用和代码解释器的提示模板的更多详细信息<a href="https://llama.meta.com/docs/model-cards-and-prompt-formats/llama3_2" rel="nofollow" _istranslated="1">，请访问文档网站</a>。</p>
</div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="5308706" _msthash="245">目录</h2><a id="user-content-table-of-contents" class="anchor" aria-label="永久链接：目录" href="#table-of-contents" _mstaria-label="634764" _msthash="246"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="#llama-recipes-examples-to-get-started-using-the-llama-models-from-meta" _msttexthash="107350334" _msthash="247">Llama 食谱：开始使用 Meta 的 Llama 模型的示例</a>
<ul dir="auto">
<li><a href="#table-of-contents" _msttexthash="5308706" _msthash="248">目录</a></li>
<li><a href="#getting-started" _msttexthash="4603768" _msthash="249">开始</a>
<ul dir="auto">
<li><a href="#prerequisites" _msttexthash="9792913" _msthash="250">先决条件</a>
<ul dir="auto">
<li><a href="#pytorch-nightlies" _msttexthash="9270963" _msthash="251">PyTorch 夜播</a></li>
</ul>
</li>
<li><a href="#installing" _msttexthash="5773755" _msthash="252">安装</a>
<ul dir="auto">
<li><a href="#install-with-pip" _msttexthash="14586624" _msthash="253">使用 pip 安装</a></li>
<li><a href="#install-with-optional-dependencies" _msttexthash="38526371" _msthash="254">使用可选依赖项安装</a></li>
<li><a href="#install-from-source" _msttexthash="16426956" _msthash="255">从源码安装</a></li>
</ul>
</li>
<li><a href="#getting-the-llama-models" _msttexthash="14685580" _msthash="256">获取 Llama 模型</a>
<ul dir="auto">
<li><a href="#model-conversion-to-hugging-face" _msttexthash="15508584" _msthash="257">模型转换为 Hugging Face</a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#repository-organization" _msttexthash="12370267" _msthash="258">仓库组织</a>
<ul dir="auto">
<li><a href="#recipes"><code>recipes/</code></a></li>
<li><a href="#src"><code>src/</code></a></li>
</ul>
</li>
<li><a href="#supported-features" _msttexthash="16014466" _msthash="259">支持的功能</a></li>
<li><a href="#contributing" _msttexthash="6354283" _msthash="260">贡献</a></li>
<li><a href="#license" _msttexthash="9675445" _msthash="261">许可证</a></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="4603768" _msthash="262">开始</h2><a id="user-content-getting-started" class="anchor" aria-label="永久链接： 开始使用" href="#getting-started" _mstaria-label="591461" _msthash="263"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="841502922" _msthash="264">这些说明将为您提供项目的副本，并在本地计算机上运行，以便进行开发和测试。有关如何在实时系统上部署工程的说明，请参阅部署。</p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="9792913" _msthash="265">先决条件</h3><a id="user-content-prerequisites" class="anchor" aria-label="永久链接：先决条件" href="#prerequisites" _mstaria-label="566982" _msthash="266"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto" _msttexthash="9270963" _msthash="267">PyTorch 夜播</h4><a id="user-content-pytorch-nightlies" class="anchor" aria-label="永久链接：PyTorch Nightlies" href="#pytorch-nightlies" _mstaria-label="675051" _msthash="268"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="428047854" _msthash="269">如果您想使用 PyTorch nightlies 而不是稳定版本，请转到<a href="https://pytorch.org/get-started/locally/" rel="nofollow" _mstmutation="1" _istranslated="1">本指南</a>以检索平台上命令的正确参数。</font><code>--extra-index-url URL</code><code>pip install</code></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="5773755" _msthash="270">安装</h3><a id="user-content-installing" class="anchor" aria-label="永久链接：安装" href="#installing" _mstaria-label="440128" _msthash="271"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="458979781" _msthash="272">Llama-recipes 提供了一个 pip 发行版，便于在其他项目中安装和使用。或者，可以从源安装它。</p>
<div class="markdown-alert markdown-alert-note" dir="auto"><p class="markdown-alert-title" dir="auto"><svg class="octicon octicon-info mr-2" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8Zm8-6.5a6.5 6.5 0 1 0 0 13 6.5 6.5 0 0 0 0-13ZM6.5 7.75A.75.75 0 0 1 7.25 7h1a.75.75 0 0 1 .75.75v2.75h.25a.75.75 0 0 1 0 1.5h-2a.75.75 0 0 1 0-1.5h.25v-2h-.25a.75.75 0 0 1-.75-.75ZM8 6a1 1 0 1 1 0-2 1 1 0 0 1 0 2Z"></path></svg><font _mstmutation="1" _msttexthash="5121168" _msthash="273">注意</font></p><p dir="auto"><font _mstmutation="1" _msttexthash="480081797" _msthash="274">确保在安装 PyTorch 轮时使用正确的 CUDA 版本 （从 ）。这里我们使用 11.8 作为 .
H100 GPU 与 CUDA &gt;12.0 配合使用效果更好</font><code>nvidia-smi</code><code>cu118</code></p>
</div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto" _msttexthash="14586624" _msthash="275">使用 pip 安装</h4><a id="user-content-install-with-pip" class="anchor" aria-label="永久链接：使用 pip 安装" href="#install-with-pip" _mstaria-label="607802" _msthash="276"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>pip install llama-recipes
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install llama-recipes" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto" _msttexthash="38526371" _msthash="277">使用可选依赖项安装</h4><a id="user-content-install-with-optional-dependencies" class="anchor" aria-label="永久链接：使用可选依赖项安装" href="#install-with-optional-dependencies" _mstaria-label="1517100" _msthash="278"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="765003304" _msthash="279">Llama-recipes 提供可选包的安装。有三个可选的依赖项组。
要运行单元测试，我们可以使用以下命令安装所需的依赖项：</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>pip install llama-recipes[tests]
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install llama-recipes[tests]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="314466997" _msthash="280">对于 vLLM 示例，我们需要额外的要求，这些要求可以通过以下方式安装：</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>pip install llama-recipes[vllm]
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install llama-recipes[vllm]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="199878653" _msthash="281">要使用敏感主题安全检查器，请通过以下方式进行安装：</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>pip install llama-recipes[auditnlg]
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install llama-recipes[auditnlg]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="607492990" _msthash="282">某些配方需要 langchain 的存在。要安装软件包，请按照配方描述进行操作，或者使用以下方式进行安装：</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>pip install llama-recipes[langchain]
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install llama-recipes[langchain]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="106307227" _msthash="283">可选依赖项也可以与 [option1，option2] 结合使用。</p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto" _msttexthash="16426956" _msthash="284">从源码安装</h4><a id="user-content-install-from-source" class="anchor" aria-label="永久链接：从源码安装" href="#install-from-source" _mstaria-label="741247" _msthash="285"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="491026796" _msthash="286">要从源码安装，例如用于开发，请使用以下命令。我们使用 hatchling 作为构建后端，这需要最新的 pip 以及 setuptools 包。</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>git clone git@github.com:meta-llama/llama-recipes.git
cd llama-recipes
pip install -U pip setuptools
pip install -e .
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone git@github.com:meta-llama/llama-recipes.git
cd llama-recipes
pip install -U pip setuptools
pip install -e ." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="271179727" _msthash="287">对于开发和为 llama-recipes 做出贡献，请安装所有可选的依赖项：</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>git clone git@github.com:meta-llama/llama-recipes.git
cd llama-recipes
pip install -U pip setuptools
pip install -e .[tests,auditnlg,vllm]
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone git@github.com:meta-llama/llama-recipes.git
cd llama-recipes
pip install -U pip setuptools
pip install -e .[tests,auditnlg,vllm]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="14685580" _msthash="288">获取 Llama 模型</h3><a id="user-content-getting-the-llama-models" class="anchor" aria-label="永久链接：获取 Llama 模型" href="#getting-the-llama-models" _mstaria-label="913029" _msthash="289"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="1905301151" _msthash="290">您可以<a href="https://huggingface.co/meta-llama" rel="nofollow" _istranslated="1">在此处</a>的 Hugging Face 中心上找到 Llama 模型，<strong _istranslated="1">其中名称中带有 <code _istranslated="1">hf</code> 的模型已经转换为 Hugging Face 检查点，因此无需进一步转换</strong>。下面的转换步骤仅适用于 Meta 的原始模型权重，这些权重也托管在 Hugging Face 模型中心。</p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto" _msttexthash="15508584" _msthash="291">模型转换为 Hugging Face</h4><a id="user-content-model-conversion-to-hugging-face" class="anchor" aria-label="永久链接： 模型转换为 Hugging Face" href="#model-conversion-to-hugging-face" _mstaria-label="1290796" _msthash="292"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="322259080" _msthash="293">如果您从 Meta 网站下载了模型检查点，则可以使用以下方法将其转换为 Hugging Face 格式：</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span># Install Hugging Face Transformers from source</span>
pip freeze <span class="pl-k">|</span> grep transformers <span class="pl-c"><span class="pl-c">#</span># verify it is version 4.45.0 or higher</span>

git clone git@github.com:huggingface/transformers.git
<span class="pl-c1">cd</span> transformers
pip install protobuf
python src/transformers/models/llama/convert_llama_weights_to_hf.py \
   --input_dir /path/to/downloaded/llama/weights --model_size 3B --output_dir /output/path</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="## Install Hugging Face Transformers from source
pip freeze | grep transformers ## verify it is version 4.45.0 or higher

git clone git@github.com:huggingface/transformers.git
cd transformers
pip install protobuf
python src/transformers/models/llama/convert_llama_weights_to_hf.py \
   --input_dir /path/to/downloaded/llama/weights --model_size 3B --output_dir /output/path" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="12370267" _msthash="294">仓库组织</h2><a id="user-content-repository-organization" class="anchor" aria-label="永久链接：仓库组织" href="#repository-organization" _mstaria-label="992433" _msthash="295"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="193565762" _msthash="296">大多数处理 Llama 使用的代码都组织在 2 个主要文件夹中：和 。</font><code>recipes/</code><code>src/</code></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><code>recipes/</code></h3><a id="user-content-recipes" class="anchor" aria-label="永久链接： recipes/" href="#recipes" _mstaria-label="355797" _msthash="297"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="90065469" _msthash="298">包含按主题在文件夹中组织的示例：</p>
<markdown-accessiblity-table data-catalyst=""><table>
<thead>
<tr>
<th _msttexthash="10164648" _msthash="299">子文件夹</th>
<th _msttexthash="6157333" _msthash="300">描述</th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="/meta-llama/llama-recipes/blob/main/recipes/quickstart" _msttexthash="13498394" _msthash="301">快速入门</a></td>
<td _msttexthash="288673606" _msthash="302">使用 Llama 的“Hello World”，如果您是使用 Llama 的新手，请从这里开始。</td>
</tr>
<tr>
<td><a href="/meta-llama/llama-recipes/blob/main/recipes/use_cases" _msttexthash="136305" _msthash="303">use_cases</a></td>
<td _msttexthash="64051975" _msthash="304">显示 Meta Llama3 常见应用的脚本</td>
</tr>
<tr>
<td><a href="/meta-llama/llama-recipes/blob/main/recipes/3p_integrations" _msttexthash="290719" _msthash="305">3p_integrations</a></td>
<td _msttexthash="149285955" _msthash="306">合作伙伴拥有的文件夹，显示 Meta Llama3 的常见应用程序</td>
</tr>
<tr>
<td><a href="/meta-llama/llama-recipes/blob/main/recipes/responsible_ai" _msttexthash="257855" _msthash="307">responsible_ai</a></td>
<td _msttexthash="81612440" _msthash="308">使用 PurpleLlama 保护模型输出的脚本</td>
</tr>
<tr>
<td><a href="/meta-llama/llama-recipes/blob/main/recipes/experimental" _msttexthash="9798750" _msthash="309">实验的</a></td>
<td _msttexthash="42009058" _msthash="310">实验性 LLM 技术的 Meta Llama 实现</td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><code>src/</code></h3><a id="user-content-src" class="anchor" aria-label="永久链接： src/" href="#src" _mstaria-label="235469" _msthash="311"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="60931052" _msthash="312">包含支持示例配方的模块：</p>
<markdown-accessiblity-table data-catalyst=""><table tabindex="0">
<thead>
<tr>
<th _msttexthash="10164648" _msthash="313">子文件夹</th>
<th _msttexthash="6157333" _msthash="314">描述</th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="/meta-llama/llama-recipes/blob/main/src/llama_recipes/configs" _msttexthash="6777615" _msthash="315">配置</a></td>
<td _msttexthash="224578731" _msthash="316">包含PEFT方法、FSDP、数据集、权重和偏差实验跟踪的配置文件。</td>
</tr>
<tr>
<td><a href="/meta-llama/llama-recipes/blob/main/src/llama_recipes/datasets" _msttexthash="5010304" _msthash="317">数据</a></td>
<td _msttexthash="121995575" _msthash="318">包含每个数据集要下载和处理的单独脚本。注意</td>
</tr>
<tr>
<td><a href="/meta-llama/llama-recipes/blob/main/src/llama_recipes/inference" _msttexthash="5410600" _msthash="319">推理</a></td>
<td _msttexthash="61318153" _msthash="320">包括用于微调模型的推理模块。</td>
</tr>
<tr>
<td><a href="/meta-llama/llama-recipes/blob/main/src/llama_recipes/model_checkpointing" _msttexthash="419471" _msthash="321">model_checkpointing</a></td>
<td _msttexthash="47005205" _msthash="322">包含 FSDP 检查点处理程序。</td>
</tr>
<tr>
<td><a href="/meta-llama/llama-recipes/blob/main/src/llama_recipes/policies" _msttexthash="5642325" _msthash="323">政策</a></td>
<td _msttexthash="786103994" _msthash="324">包含 FSDP 脚本以提供不同的策略，例如混合精度、transformer 包装策略和激活检查点以及任何精度优化器（用于以纯 bf16 模式运行 FSDP）。</td>
</tr>
<tr>
<td><a href="/meta-llama/llama-recipes/blob/main/src/llama_recipes/utils" _msttexthash="65481" _msthash="325">utils</a></td>
<td><font _mstmutation="1" _msttexthash="1585600159" _msthash="326">实用程序文件：<br _mstmutation="1" _istranslated="1">- 提供 training/eval loop 和更多 train utils。<br _mstmutation="1" _istranslated="1"> - 获取预处理的数据集。<br _mstmutation="1" _istranslated="1"> - 覆盖从 CLI 接收的配置。<br _mstmutation="1" _istranslated="1"> - 为 PEFT 方法提供 FSDP 包装策略。<br _mstmutation="1" _istranslated="1"> - 上下文管理器，用于跟踪 Train Loop 中的不同内存统计信息。</font><code>train_utils.py</code><code>dataset_utils.py</code><code>config_utils.py</code><code>fsdp_utils.py</code><code>memory_utils.py</code></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="16014466" _msthash="327">支持的功能</h2><a id="user-content-supported-features" class="anchor" aria-label="永久链接：支持的功能" href="#supported-features" _mstaria-label="731887" _msthash="328"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="103255620" _msthash="329">此存储库中的配方和模块支持以下功能：</p>
<markdown-accessiblity-table data-catalyst=""><table>
<thead>
<tr>
<th _msttexthash="5209451" _msthash="330">特征</th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td _msttexthash="24055980" _msthash="331">HF 对推理的支持</td>
<td _msttexthash="908999" _msthash="332">✅</td>
</tr>
<tr>
<td _msttexthash="15433483" _msthash="333">HF 支持微调</td>
<td _msttexthash="908999" _msthash="334">✅</td>
</tr>
<tr>
<td _msttexthash="33566" _msthash="335">PEFT</td>
<td _msttexthash="908999" _msthash="336">✅</td>
</tr>
<tr>
<td _msttexthash="42725475" _msthash="337">延迟初始化 （ meta init）</td>
<td _msttexthash="908999" _msthash="338">✅</td>
</tr>
<tr>
<td _msttexthash="20680881" _msthash="339">多 GPU 的低 CPU 模式</td>
<td _msttexthash="908999" _msthash="340">✅</td>
</tr>
<tr>
<td _msttexthash="11685167" _msthash="341">混合精度</td>
<td _msttexthash="908999" _msthash="342">✅</td>
</tr>
<tr>
<td _msttexthash="16686332" _msthash="343">单节点量化</td>
<td _msttexthash="908999" _msthash="344">✅</td>
</tr>
<tr>
<td _msttexthash="12636429" _msthash="345">闪现关注</td>
<td _msttexthash="908999" _msthash="346">✅</td>
</tr>
<tr>
<td _msttexthash="16286036" _msthash="347">激活检查点 FSDP</td>
<td _msttexthash="908999" _msthash="348">✅</td>
</tr>
<tr>
<td _msttexthash="58955546" _msthash="349">混合分片数据并行 （HSDP）</td>
<td _msttexthash="908999" _msthash="350">✅</td>
</tr>
<tr>
<td _msttexthash="26825968" _msthash="351">数据集打包和填充</td>
<td _msttexthash="908999" _msthash="352">✅</td>
</tr>
<tr>
<td _msttexthash="45213506" _msthash="353">BF16 优化器（纯 BF16）</td>
<td _msttexthash="908999" _msthash="354">✅</td>
</tr>
<tr>
<td _msttexthash="19995313" _msthash="355">分析和 MFU 跟踪</td>
<td _msttexthash="908999" _msthash="356">✅</td>
</tr>
<tr>
<td _msttexthash="12766078" _msthash="357">梯度累积</td>
<td _msttexthash="908999" _msthash="358">✅</td>
</tr>
<tr>
<td _msttexthash="8055021" _msthash="359">CPU 卸载</td>
<td _msttexthash="908999" _msthash="360">✅</td>
</tr>
<tr>
<td _msttexthash="69001738" _msthash="361">FSDP 检查点转换为 HF 以进行推理</td>
<td _msttexthash="908999" _msthash="362">✅</td>
</tr>
<tr>
<td _msttexthash="24653005" _msthash="363">W&amp;B实验追踪器</td>
<td _msttexthash="908999" _msthash="364">✅</td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="6354283" _msthash="365">贡献</h2><a id="user-content-contributing" class="anchor" aria-label="永久链接： 贡献" href="#contributing" _mstaria-label="521066" _msthash="366"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="361622820" _msthash="367">请阅读 <a href="/meta-llama/llama-recipes/blob/main/CONTRIBUTING.md" _istranslated="1">CONTRIBUTING.md</a>，详细了解我们的行为准则以及向我们提交拉取请求的流程。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="9675445" _msthash="368">许可证</h2><a id="user-content-license" class="anchor" aria-label="永久链接：许可证" href="#license" _mstaria-label="331903" _msthash="369"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>

<p dir="auto" _msttexthash="238316780" _msthash="370"><a href="https://github.com/meta-llama/llama-models/blob/main/models/llama3_2/LICENSE" _istranslated="1">请在此处</a>查看 Meta Llama 3.2 的许可文件，<a href="https://github.com/meta-llama/llama-models/blob/main/models/llama3_2/USE_POLICY.md" _istranslated="1">在此处</a>查看可接受使用政策</p>
<p dir="auto" _msttexthash="244775895" _msthash="371"><a href="https://github.com/meta-llama/llama-models/blob/main/models/llama3_1/LICENSE" _istranslated="1">在此处</a>查看 Meta Llama 3.1 的许可证文件，在此处查看可接受<a href="https://github.com/meta-llama/llama-models/blob/main/models/llama3_1/USE_POLICY.md" _istranslated="1">使用政策</a></p>
<p dir="auto" _msttexthash="230686560" _msthash="372"><a href="https://github.com/meta-llama/llama-models/blob/main/models/llama3/LICENSE" _istranslated="1">在此处</a>查看 Meta Llama 3 的许可证文件，在此处查看可接受<a href="https://github.com/meta-llama/llama-models/blob/main/models/llama3/USE_POLICY.md" _istranslated="1">使用政策</a></p>
<p dir="auto" _msttexthash="230686287" _msthash="373"><a href="https://github.com/meta-llama/llama-models/blob/main/models/llama2/LICENSE" _istranslated="1">在此处</a>查看 Meta Llama 2 的许可证文件，<a href="https://github.com/meta-llama/llama-models/blob/main/models/llama2/USE_POLICY.md" _istranslated="1">在此处</a>查看可接受使用政策</p>

</article></div>
