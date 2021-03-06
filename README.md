<body><div class="wrapper">
	<header>
		<h1><a href="https://jerkwin.github.io/gmxtool/">gmxtool</a></h1>
		<p>scripts/programs/utilities/tools for GROMACS</p>
		<p class="view"><a href="#Introduction">Introduction</a></p>
		<p class="view"><a href="#Tools">Tools</a></p>
	</header>

<h2 id="Introduction">Introduction</h2>

<p>This is a collection of the tools I used for GROMACS. Hope it helps for you as well.</p>

<h2 id="Tools">Tools</h2></p>

<table>
<th>名称<br>NAME</th><th>说明<br>INSTRUCTION</th> <th>代码<br>CODE</th> <th>示例<br>EXAMPLE</th>

<tr>
<td>calc</td>
<td><a href="https://jerkwin.github.io/2019/11/19/%E5%9C%A8%E7%BA%BF%E8%AE%A1%E7%AE%97%E5%85%BC%E5%8D%95%E4%BD%8D%E6%8D%A2%E7%AE%97%E5%99%A8/">在线计算兼单位换算器</a></td>
<td><a href="./calc/calc.html">calc</a></td>
<td>N/A</td>
</tr>

<tr>
<td>wvmd</td>
<td><a href="https://jerkwin.github.io/2017/02/11/%E8%87%AA%E5%8A%A8%E8%B0%83%E6%95%B4VMD%E7%AA%97%E5%8F%A3%E7%9A%84%E4%BD%8D%E7%BD%AE%E5%92%8C%E5%A4%A7%E5%B0%8F/">自动调整VMD窗口的位置和大小</a></td>
<td><a href="./wvmd/wvmd.zip">wvmd.zip</a></td>
<td>N/A</td>
</tr>

<tr>
<td>graphene</td>
<td><a href="http://jerkwin.github.io/2014/05/09/%E7%9F%B3%E5%A2%A8%E7%83%AF-%E5%BB%BA%E6%A8%A1-%E5%87%A0%E4%BD%95%E6%80%A7%E8%B4%A8%E5%8F%8A%E5%8A%9B%E5%9C%BA%E6%A8%A1%E6%8B%9F/">石墨烯：建模, 几何性质及力场模拟</a><br>
<a href="https://jerkwin.github.io/2014/12/24/%E7%9F%B3%E5%A2%A8%E7%83%AF%E5%9C%A8%E7%BA%BF%E5%88%9B%E5%BB%BA%E5%B7%A5%E5%85%B7/">石墨烯在线创建工具</a><br>
<a href="https://jerkwin.github.io/GMX/GMXtut-8/">创建周期性体系的拓扑文件：以石墨烯为例</a><br>
<a href="https://jerkwin.github.io/2020/04/05/%E6%B0%A7%E5%8C%96%E7%9F%B3%E5%A2%A8%E7%83%AF%E7%9A%84%E7%BB%93%E6%9E%84%E4%B8%8E%E5%BB%BA%E6%A8%A1/">氧化石墨烯的结构与建模</a><br>
<a href="https://jerkwin.github.io/2020/06/03/%E7%9F%B3%E5%A2%A8%E7%83%AF%E5%B9%B3%E9%9D%A2%E7%9A%84%E5%8D%B7%E6%9B%B2%E4%B8%8E%E6%89%AD%E6%9B%B2/">石墨烯平面的卷曲与扭曲</a><br>
</td>
<td><a href="./model/graphene.html">graphene</a></td>
<td>N/A</td>
</tr>

<tr>
<td>pipistack</td>
<td><a href="https://jerkwin.github.io/2018/08/29/Pi-Pi%E5%A0%86%E7%A7%AF%E8%B7%9D%E7%A6%BB%E5%92%8C%E5%A0%86%E7%A7%AF%E8%A7%92%E5%BA%A6%E7%9A%84%E8%AE%A1%E7%AE%97/">Pi-Pi堆积距离和堆积角度的计算</a></td>
<td><a href="./pipistack/pipistack.tcl">pipistack.tcl</a><br>
<a href="./pipistack/pipistack_linalg.tcl">pipistack_linalg.tcl</a></td>
<td><a href="./pipistack/ph2.zip">ph2.zip</a></td>

</td>

<tr>
<td>fitmol</td>
<td><a href="./fitmol/README.md.html">README</a></td>
<td><a href="./fitmol/FitMol.f90">FitMol.f90</a></td>
<td><a href="./fitmol/ch4.xyz">ch4.xyz</a><br>
<a href="./fitmol/ch4_ch3oh.xyz">ch4_ch3oh.xyz</a>
</td>

<tr>
<td>xpm2all</td>
<td><a href="https://jerkwin.github.io/2018/05/09/xpm%E6%96%87%E4%BB%B6%E5%A4%84%E7%90%86%E8%84%9A%E6%9C%AC/">xpm文件处理脚本</a><br>
<a href="https://jerkwin.github.io/2020/02/29/%E5%88%86%E5%AD%90%E6%A8%A1%E6%8B%9F%E5%91%A8%E5%88%8A-%E7%AC%AC_8_%E6%9C%9F/">xpm2all: xpm文件转换工具</a>
</td>
<td><a href="./xpm2all/xpm2all.bsh">xpm2all.bsh</a><br>
<a href="./xpm2all/xpm2all.bat">xpm2rgb.bat</a>
</td>
<td><a href="./xpm2all/ss.xpm">ss.xpm</a><br>
<a href="./xpm2all/gibbs.xpm">gibbs.xpm</a>
</td>

<tr>
<td>gmx_mmpbsa</td>
<td><a href="https://jerkwin.github.io/2019/07/31/gmx_mmpbsa%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E/">gmx_mmpbsa使用说明</a></td>
<td><a href="./gmx_mmpbsa/gmx_mmpbsa.bsh">gmx_mmpbsa.bsh</a></td>
<td><a href="./gmx_mmpbsa/1ebz.zip">1ebz.zip</a></td>
</tr>

</tr>

</table>

<h2 id="Questions">Questions?</h2></p>

If you have any quesiotns about these tools, please let me know.

<ul>
<li><a href="https://groups.google.com/forum/#!forum/gmxtool">Google Forum</a></li>
<li><a href="https://github.com/Jerkwin/gmxtool/issues">GitHub issues</a></li>
</ul>

</div></body>