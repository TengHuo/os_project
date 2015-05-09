# os_project
All OS projects in 2015 Spring term
##First project 处理机管理项目1:电梯调度项目
###基本任务
某一层楼20层，有五部互联的电梯。基于线程思想，编写一个电梯调度程序。<br>
###功能描述
<ul>
<li>电梯应有一些按键，如：数字键、关门键、开门键、上行键、下行键、报警键等；</li>
<li>有数码显示器指示当前电梯状态；</li>
<li>每层楼、每部电梯门口，有上行、下行按钮、数码显示。</li>
</ul>
###基本需求
<ul>
<li>五部电梯相互联结，即当一个电梯按钮按下去时，其它电梯相应按钮同时点亮，表示也按下去了。</li>
<li>电梯调度算法:
<ul>
<li>所有电梯初始状态都在第一层；</li>
<li>每个电梯没有相应请求情况下，则应该在原地保持不动；</li>
<li>电梯调度算法基于简单的轮转算法，当电梯外部的上下行按钮被按下时产生一个电梯任务，将其放入任务队列，当任务队列不为空时由任务调度算法将任务分配到五部电梯。</li>
</ul>
</li>
</ul>
