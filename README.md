[![Contributors][contributors-shield]][contributors-url]
[![Stargazers][stars-shield]][stars-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<br />
<p align="center">
  <a href="https://github.com/tanglaoji/tanglaoji.github.io">
    <img src="readme-imgs/toji.png" alt="Logo" width="80" height="80">
  </a>
</p>
<h3 align="center">赛尔不求人(SeerHelp) 是一款以赛尔号手游数据为基础的综合型工具</h3>

<p align="center">
  注意：因为使用到 CDN 和 UNPKG ，所以需要进行联网才能正常使用
</p>


<h2>目录</h2>
<ol>
<li><a href="#preface">前言</a></li>
<li><a href="#frame">框架</a></li>
<li><a href="#usage">用法</a></li>
</ol>
<br />

<h2 id="preface">前言</h2>

基于对赛尔号手游的热爱，填补童年的缺口，设计之初的开发语言为原生JavaScript，最早的上线时间为2021年3月31日，并开始在群聊、网盘等渠道进行传播，收到褒贬不一的评价，最大的缺陷是未能进行一个线上服务，只能从文件中找到后打开使用，不够方便。现将代码进行开源，希望有能力的赛尔能够将该工具进行发布上线。

该工具从单一的计算器功能拓展至8个功能，从原生迁移至Vue框架下，历经多个版本的更迭，时间跨度历经5个月之久，实际的开发时间不超过14天，现已实现稳定版本发布，所有功能均可完美使用。在后续的版本更新中，将主要更新赛尔号手游新增精灵的数据，现有功能在短期内将不会再有大的改变。

<h2 id="frame">框架</h2>

本项目所使用的所有主要框架。
* [Vue](https://cn.vuejs.org/)
* [Element-UI](https://element.eleme.cn/)

<h2 id="usage">用法</h2>

<p align="center">
	<ol>
		<li>个体计算：支持模糊搜索，输入一个字即可开始联想</li>
		<li>个体潜力：在搜索功能的基础下，选择精灵后即可计算出个体潜力和发展方向</li>
		<li>数据分析：展示当前版本精灵数量、进攻类 / 防御类数量等信息</li>
		<li>瞻前顾后：展示当前版本之最的精灵名字</li>
		<li>活动规律：该计算器的基础为赛尔号手游的数据，活动规律可自动推算出活动日期，方便赛尔规划发展</li>
		<li>伤害模拟：隐性功能为计算克制关系，显性功能为计算对战伤害，提供最高、最低、平均伤害的数值</li>
		<li>名词解释：主要用来解释个体潜力的名词</li>
		<li>更新预告：可直接查看官方更新文章，当前功能仅为iframe展示页，不能自动获取，后续更新方向为自动获取</li>
	</ol>
	<br />
	<img src="readme-imgs/seerhelp-demo.png" alt="flexrabbit-demo">
</p>

_查看更多，请[立即下载](https://github.com/tanglaoji/SeerHelp/archive/refs/heads/main.zip)_

<!-- Markdown 链接/图片 -->
[contributors-shield]: https://img.shields.io/github/followers/tanglaoji?style=for-the-badge
[contributors-url]: https://github.com/----------/Best-README-Template/graphs/contributors

[stars-shield]: https://img.shields.io/github/stars/tanglaoji?style=for-the-badge
[stars-url]: https://github.com/tanglaoji/tanglaoji.github.io/stargazers

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://tanglaoji.github.io/
