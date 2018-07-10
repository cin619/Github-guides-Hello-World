# Hello-World
<strong>A translation of github guides--hello world</strong>

# Step 1.创建一个仓库（repository）
<p><strong>repository</strong>通常用于组织一个项目。repositories 可以包含文件和文件夹、图片、视频、电子表格和数据集等 - 任何项目需要的东西。我们推荐在其中创建一个<strong>README</strong>，或者其它描述你的项目的信息。GitHub可以在创建新存储库的同时轻松添加一个。同时你也可以创建其它通用设置 - 例如<strong>license</strong> 文件</p>

<p>你的<code class="highlighter-rouge">hello-world</code>repository可以成为你储备ideas、源代码的地方，你也可以和别人分享与讨论。</p>
  
## 创建一个新的repository
<p>1. 在右上角，靠近你的头像旁边，点击<span class="octicon octicon-plus"></span>，然后选择<strong>New repository</strong></p>

<p>2. 命名你的repository - <code class="highlighter-rouge">hello-world</code></p>

<p>3. 写一个简短的描述</p>

<p>4. 选择<strong>Initialize this repository with a README</strong></p>

<p><img src="https://github.com/cin619/Github-guides-Hello-World/blob/master/images/create-new-repo.png" alt="new-repo-form"></p>

<p>点击<strong>Create repository</strong></p>
  
# Step 2.创建一个分支（Branch）
<p><strong>Branching</strong>是在同一时间编辑不同版本的repository的工作方式</p>

<p>默认情况下，你的repository有一个名为<code class="highlighter-rouge">master</code>的branch，它被认为是权威branch。在将更改提交给<code class="highlighter-rouge">master</code>之前，我们可以使用branches进行实验和编辑</p>

<p>当你从<code class="highlighter-rouge">master</code>分支创建分支时，你其实是在给<code class="highlighter-rouge">master</code>分支创建那个时间点的副本或快照。如果其他人在你编辑分支时更改了<code class="highlighter-rouge">master</code>分支，你可以引入（pull in）这些更新</p>

<p>下面这个示意图展示了：</p>

<ul>
  <li><code class="highlighter-rouge">master</code>分支</li>
  <li>一个新的名为<code class="highlighter-rouge">feature</code>的分支（因为正在这个分支上完成‘feature’相关的工作）</li>
  <li><code class="highlighter-rouge">feature</code>被合并（merged）到<code class="highlighter-rouge">master</code>之前经历的过程</li>
</ul>

<p><img src="https://github.com/cin619/Github-guides-Hello-World/blob/master/images/branching.png" alt="a branch"></p>

<p>你曾经保存过一个文件的不同版本吗？就像：</p>

<ul>
  <li><code class="highlighter-rouge">story.txt</code></li>
  <li><code class="highlighter-rouge">story-joe-edit.txt</code></li>
  <li><code class="highlighter-rouge">story-joe-edit-reviewed.txt</code></li>
</ul>

<p>Branches在GitHub中完成类似的目标</p>

<p>在GitHub中，开发者、作者、设计师们使用branches使得bug的修复，细节的完善工作独立于<code class="highlighter-rouge">master</code>（产品）分支之外。只有当所有修改都已经完成了，它们才会被合并（merge）到<code class="highlighter-rouge">master</code>中</p>
