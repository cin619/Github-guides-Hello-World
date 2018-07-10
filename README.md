# Hello-World

<p><strong>A translation of github guides--hello world</strong></p>

## Step 1.创建一个仓库（repository）

<p><strong>repository</strong>通常用于组织一个项目。repositories 可以包含文件和文件夹、图片、视频、电子表格和数据集等 - 任何项目需要的东西。我们推荐在其中创建一个<strong>README</strong>，或者其它描述你的项目的信息。GitHub可以在创建新存储库的同时轻松添加一个。同时你也可以创建其它通用设置 - 例如<strong>license</strong> 文件</p>

<p>你的<code class="highlighter-rouge">hello-world</code>repository可以成为你储备ideas、源代码的地方，你也可以和别人分享与讨论。</p>
  
### 创建一个新的repository

<ol>
  <li>1. 在右上角，靠近你的头像旁边，点击<span class="octicon octicon-plus"></span>，然后选择<strong>New repository</strong></p></li>
  <li>2. 命名你的repository - <code class="highlighter-rouge">hello-world</code></p></li>
  <li>3. 写一个简短的描述</p></li>
  <li>4. 选择<strong>Initialize this repository with a README</strong></p></li>
</ol>

<p><img src="https://github.com/cin619/Github-guides-Hello-World/blob/master/images/create-new-repo.png" alt="new-repo-form"></p>

<p>点击<strong>Create repository</strong></p>
  
## Step 2.创建一个分支（Branch）

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

### 创建一个新的branch

<ol>
  <li>1. 进入你的新的repository<code class="highlighter-rouge">hello-world</code></p></li>
  <li>2. 点击顶部文件的下拉列表 <strong>branch:master</strong></p></li>
  <li>3. 在新分支文本框输入一个branch名，<code class="highlighter-rouge">readme-edits</code></p></li>
  <li>4. 选择蓝色的<strong>Create branch</strong>框 或者 按“Enter”键</p></li>
</ol>

<p><img src="https://github.com/cin619/Github-guides-Hello-World/blob/master/images/readme-edits.gif" alt="branch gif"></p>

<p>这样你就有两个分支了，<code class="highlighter-rouge">master</code>和<code class="highlighter-rouge">readme-edits</code>。它们看起来是一样的，但之后就不是了，因为我们需要在新分支中进行编辑</p>

## 制作和提交（commit）修改

<p>哇喔！现在你在你的 <code class="highlighter-rouge">readme-edits</code> 分支的代码视图，它是<code class="highlighter-rouge">master</code>分支的副本。我们可以对其进行编辑</p>

<p>在GitHub上，保存更改叫做<em>commits</em>。每个commit都有一个<em>commit message</em>，这是用来解释为什么要做这样的更改。Commit messages显示了更改的历史，这样其他人就可以理解你做了什么改变以及为什么这么做</p>

### 制作和提交修改

<ol>
  <li>点击<code class="highlighter-rouge">README.md</code>文件</li>
  <li>点击文件视图右上角的铅笔图标进入编辑</li>
  <li>在编辑器中写一点关于你自己的情况</li>
  <li>写一个commit message描述你的更改</li>
  <li>点击<strong>Commit changes</strong>按钮</li>
</ol>

<p><img src="https://github.com/cin619/Github-guides-Hello-World/blob/master/images/commit.png" alt="commit"></p>

<p>这些更改只会应用于你的<code class="highlighter-rouge">readme-edits</code>branch中的README文件，所以现在这个分支包含的内容不同于<code class="highlighter-rouge">master</code>分支了</p>

## Step 4. 打开一个Pull Request

<p>这样你就修改了<code class="highlighter-rouge">master</code>下的一个分支了，然后你可以打开<em>pull request</em></p>

<p>Pull Request是在GitHub中进行合作的核心。当你打开一个<em>pull request</em>，你就是在提出你的修改并希望其他人审核并提取（pull in）你的贡献，然后将其合并到他们的branch中。Pull requests显示了两个branch的<em>diffs</em>，或differences。修改、添加和删减以绿色和红色显示</p>

<p>只要你有不同的版本（修改），不管代码是否完成，你都可以打开一个pull request并开始讨论</p>

<p>通过在你的pull request信息中使用GitHub的<a href="https://help.github.com/articles/about-writing-and-formatting-on-github/#text-formatting-toolbar">@mention system</a>，你可以从一些特定的人或团队得到反馈，不论他们是在大厅还是10个时区之外</p>

<p>你甚至可以在你自己的repository中打开pull request并合并他们。在进行大项目之前，这是学习GitHub Flow的好方法</p>

### 为README的修改打开一个Pull Request

<p><em>点击图片以获得大图</em></p>

<table>
  <thead>
    <tr>
      <th>步骤</th>
      <th>截图</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>点击<strong>Pull Request</strong>标签然后在Pull Request页，点击绿色的<strong>New pull request</strong>按键.</td>
      <td><a href="pr-tab.gif"><img src="https://github.com/cin619/Github-guides-Hello-World/blob/master/images/pr-tab.gif" alt="pr-tab"></a></td>
    </tr>
    <tr>
      <td>在<strong>示例比较（Example Comparisons）</strong>框中，选择你生成的branch，<code class="highlighter-rouge">readme-edits</code>，与<code class="highlighter-rouge">master</code>比较(原始版本).</td>
      <td><a href="pick-branch.png"><img src="https://github.com/cin619/Github-guides-Hello-World/blob/master/images/pick-branch.png" alt="branch"></a></td>
    </tr>
    <tr>
      <td>在比较页面查看你的更改，确保它们是你想提交的内容</td>
      <td><a href="diff.png"><img src="https://github.com/cin619/Github-guides-Hello-World/blob/master/images/diff.png" alt="diff"></a></td>
    </tr>
    <tr>
      <td>当你确认之后，点击绿色<strong>Create Pull Request</strong>按钮.</td>
      <td><a href="create-pr.png"><img src="https://github.com/cin619/Github-guides-Hello-World/blob/master/images/create-pr.png" alt="create-pull"></a></td>
    </tr>
    <tr>
      <td>为你的pull request添加一个标题，并对你的修改进行简短的描述</td>
      <td><a href="pr-form.png"><img src="https://github.com/cin619/Github-guides-Hello-World/blob/master/images/pr-form.png" alt="pr-form"></a></td>
    </tr>
  </tbody>
</table>

<p>When you’re done with your message, click <strong>Create pull request</strong>!</p>

<hr>

<blockquote>
  <p><strong>Tip</strong>: You can use <a href="https://help.github.com/articles/basic-writing-and-formatting-syntax/#using-emoji">emoji</a> and <a href="https://help.github.com/articles/file-attachments-on-issues-and-pull-requests/">drag and drop images and gifs</a> onto comments and Pull Requests.</p>
</blockquote>

<p><a id="merge" title="Merge Pull Request" class="toc-item"></a></p>

<h2>Step 5. Merge your Pull Request</h2>

<p>In this final step, it’s time to bring your changes together – merging your <code class="highlighter-rouge">readme-edits</code> branch into the <code class="highlighter-rouge">master</code> branch.</p>

<ol>
  <li>Click the green <strong>Merge pull request</strong> button to merge the changes into <code class="highlighter-rouge">master</code>.</li>
  <li>Click <strong>Confirm merge</strong>.</li>
  <li>Go ahead and delete the branch, since its changes have been incorporated, with the <strong>Delete branch</strong> button in the purple box.</li>
</ol>

<p><img src="/activities/hello-world/merge-button.png" alt="merge">
<img src="/activities/hello-world/delete-button.png" alt="delete"></p>

<h3>Celebrate!</h3>

<p>By completing this tutorial, you’ve learned to create a project and make a pull request on GitHub! <img class="emoji" title=":tada:" alt=":tada:" src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f389.png" height="20" width="20"> <img class="emoji" title=":octocat:" alt=":octocat:" src="https://assets-cdn.github.com/images/icons/emoji/octocat.png" height="20" width="20"> <img class="emoji" title=":zap:" alt=":zap:" src="https://assets-cdn.github.com/images/icons/emoji/unicode/26a1.png" height="20" width="20"></p>

<p>Here’s what you accomplished in this tutorial:</p>

<ul>
  <li>Created an open source repository</li>
  <li>Started and managed a new branch</li>
  <li>Changed a file and committed those changes to GitHub</li>
  <li>Opened and merged a Pull Request</li>
</ul>

<p>Take a look at your GitHub profile and you’ll see your new <a href="https://help.github.com/articles/viewing-contributions">contribution squares</a>!</p>

<p>To learn more about the power of Pull Requests, we recommend reading the <a href="http://guides.github.com/overviews/flow/">GitHub Flow Guide</a>. You might also visit <a href="http://github.com/explore">GitHub Explore</a> and get involved in an Open Source project <img class="emoji" title=":octocat:" alt=":octocat:" src="https://assets-cdn.github.com/images/icons/emoji/octocat.png" height="20" width="20"></p>

<hr>

<blockquote>
  <p><strong>Tip</strong>: Check out our other <a href="http://guides.github.com">Guides</a>, <a href="http://youtube.com/githubguides">YouTube Channel</a> and <a href="https://services.github.com/on-demand/">On-Demand Training</a> for more on how to get started with GitHub.</p>
</blockquote>









