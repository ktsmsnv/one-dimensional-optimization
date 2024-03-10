Методы одномерной оптимизации C++. 
<p><a name="_Toc69730547"></a>Задание</p>
<p>Вычислить минимум функции f(x)=1,5x^3+e^(-x) на интервале [0;2] с заданной точностью ɛ.</p>
<p><a name="_Toc69730548"></a>Выполнение задания</p>
<p>Целевая функция: f(x)=1,5x^3+e^(-x)</p>
<p>Область неопределенности: [0;2]</p>

![image](https://github.com/ktsmsnv/one-dimensional-optimization/assets/126246369/8a664783-736d-43f2-8170-476168100150)

<p>Рисунок 1 &minus; График функции f(x)=1,5x^3+e^(-x) на интервале [0;2]</p>
<p>В ходе решения были использованы методы</p>
<ol>
<li>Метод перебора</li>
<li>Пассивно-оптимальный метод</li>
<li>Метод деления отрезка пополам</li>
<li>Метод золотого сечения</li>
<li>Метод дихотомии</li>
<li>Метод поразрядного поиска</li>
</ol>
<p><a name="_Toc69730549"></a>Расчетные таблицы</p>
<table width="648">
<tbody>
<tr>
<td colspan="6" width="648"><strong><br /> </strong>
<p>Метод золотого сечения</p>
</td>
</tr>
<tr>
<td width="107">
<p>ɛ</p>
</td>
<td width="107">
<p>x</p>
</td>
<td width="107">
<p>y</p>
</td>
<td width="112">&nbsp;</td>
<td width="106">
<p>N</p>
</td>
<td width="107">&nbsp;</td>
</tr>
<tr>
<td width="107">
<p>0,1</p>
</td>
<td width="107">
<p>0,38196</p>
</td>
<td width="107">
<p>0,76611</p>
</td>
<td width="112">
<p>0,0901699</p>
</td>
<td width="106">
<p>6</p>
</td>
<td width="107">
<p>6</p>
</td>
</tr>
<tr>
<td width="107">
<p>0,01</p>
</td>
<td width="107">
<p>0,385072</p>
</td>
<td width="107">
<p>0,76605</p>
</td>
<td width="112">
<p>0,00813062</p>
</td>
<td width="106">
<p>11</p>
</td>
<td width="107">
<p>11</p>
</td>
</tr>
<tr>
<td width="107">
<p>0,001</p>
</td>
<td width="107">
<p>0,38863</p>
</td>
<td width="107">
<p>0,766029</p>
</td>
<td width="112">
<p>0,000733137</p>
</td>
<td width="106">
<p>16</p>
</td>
<td width="107">
<p>16</p>
</td>
</tr>
<tr>
<td width="107">
<p>0,0001</p>
</td>
<td width="107">
<p>0,388259</p>
</td>
<td width="107">
<p>0,766029</p>
</td>
<td width="112">
<p>6,6107e-05</p>
</td>
<td width="106">
<p>21</p>
</td>
<td width="107">
<p>21</p>
</td>
</tr>
<tr>
<td width="107">
<p>0,00001</p>
</td>
<td width="107">
<p>0,388234</p>
</td>
<td width="107">
<p>0,766029</p>
</td>
<td width="112">
<p>9,64488e-06</p>
</td>
<td width="106">
<p>25</p>
</td>
<td width="107">
<p>25</p>
</td>
</tr>
</tbody>
</table>
<p><strong>&nbsp;</strong></p>
<table width="649">
<tbody>
<tr>
<td colspan="5" width="649">
<p>Метод дихотомии</p>
</td>
</tr>
<tr>
<td width="130">
<p>ɛ</p>
</td>
<td width="130">
<p>x</p>
</td>
<td width="130">
<p>y</p>
</td>
<td width="130">&nbsp;</td>
<td width="130">
<p>N</p>
</td>
</tr>
<tr>
<td width="130">
<p>0,1</p>
</td>
<td width="130">
<p>0,38343</p>
</td>
<td width="130">
<p>0,766077</p>
</td>
<td width="130">
<p>0,00880469</p>
</td>
<td width="130">
<p>14</p>
</td>
</tr>
<tr>
<td width="130">
<p>0,01</p>
</td>
<td width="130">
<p>0,38343</p>
</td>
<td width="130">
<p>0,766077</p>
</td>
<td width="130">
<p>0,0080469</p>
</td>
<td width="130">
<p>14</p>
</td>
</tr>
<tr>
<td width="130">
<p>0,001</p>
</td>
<td width="130">
<p>0,388245</p>
</td>
<td width="130">
<p>0,766029</p>
</td>
<td width="130">
<p>0,000588232</p>
</td>
<td width="130">
<p>22</p>
</td>
</tr>
<tr>
<td width="130">
<p>0,0001</p>
</td>
<td width="130">
<p>0,388251</p>
</td>
<td width="130">
<p>0,766029</p>
</td>
<td width="130">
<p>7,1045e-05</p>
</td>
<td width="130">
<p>28</p>
</td>
</tr>
<tr>
<td width="130">
<p>0,00001</p>
</td>
<td width="130">
<p>0,388238</p>
</td>
<td width="130">
<p>0,766029</p>
</td>
<td width="130">
<p>8,62939e-06</p>
</td>
<td width="130">
<p>34</p>
</td>
</tr>
</tbody>
</table>
<p><strong>&nbsp;</strong></p>
<table width="649">
<tbody>
<tr>
<td colspan="5" width="649">
<p>Метод поразрядного поиска</p>
</td>
</tr>
<tr>
<td width="147">
<p>ɛ</p>
</td>
<td width="125">
<p>x</p>
</td>
<td width="125">
<p>y</p>
</td>
<td width="127">&nbsp;</td>
<td width="125">
<p>N</p>
</td>
</tr>
<tr>
<td width="147">
<p>0,1</p>
</td>
<td width="125">
<p>0,375</p>
</td>
<td width="125">
<p>0,766391</p>
</td>
<td width="127">
<p>0,03125</p>
</td>
<td width="125">
<p>14</p>
</td>
</tr>
<tr>
<td width="147">
<p>0,01</p>
</td>
<td width="125">
<p>0,388184</p>
</td>
<td width="125">
<p>0,766029</p>
</td>
<td width="127">
<p>-0,000488281</p>
</td>
<td width="125">
<p>27</p>
</td>
</tr>
<tr>
<td width="147">
<p>0,001</p>
</td>
<td width="125">
<p>0,388184</p>
</td>
<td width="125">
<p>0,766029</p>
</td>
<td width="127">
<p>-0,000488281</p>
</td>
<td width="125">
<p>27</p>
</td>
</tr>
<tr>
<td width="147">
<p>0,0001</p>
</td>
<td width="125">
<p>0,388245</p>
</td>
<td width="125">
<p>0,766029</p>
</td>
<td width="127">
<p>-3,05176e-05</p>
</td>
<td width="125">
<p>35</p>
</td>
</tr>
<tr>
<td width="147">
<p>0,00001</p>
</td>
<td width="125">
<p>0,388229</p>
</td>
<td width="125">
<p>0,766029</p>
</td>
<td width="127">
<p>7,63939e-06</p>
</td>
<td width="125">
<p>38</p>
</td>
</tr>
</tbody>
</table>
<p><strong>&nbsp;</strong></p>
<p><strong>&nbsp;</strong></p>
<table width="648">
<tbody>
<tr>
<td colspan="6" width="648"><strong><br /> </strong>
<p>Пассивно-оптимальный метод</p>
</td>
</tr>
<tr>
<td width="108">
<p>ɛ</p>
</td>
<td width="108">
<p>x</p>
</td>
<td width="108">
<p>y</p>
</td>
<td width="108">&nbsp;</td>
<td width="108">
<p>N</p>
</td>
<td width="108">&nbsp;</td>
</tr>
<tr>
<td width="108">
<p>0,1</p>
</td>
<td width="108">
<p>0.4</p>
</td>
<td width="108">
<p>0,76632</p>
</td>
<td width="108">
<p>0,1</p>
</td>
<td width="108">
<p>19</p>
</td>
<td width="108">
<p>0,01</p>
</td>
</tr>
<tr>
<td width="108">
<p>0,01</p>
</td>
<td width="108">
<p>0,39</p>
</td>
<td width="108">
<p>0,766035</p>
</td>
<td width="108">
<p>0,01</p>
</td>
<td width="108">
<p>199</p>
</td>
<td width="108">
<p>0,001</p>
</td>
</tr>
<tr>
<td width="108">
<p>0,001</p>
</td>
<td width="108">
<p>0,388</p>
</td>
<td width="108">
<p>0,766029</p>
</td>
<td width="108">
<p>0,001</p>
</td>
<td width="108">
<p>1999</p>
</td>
<td width="108">
<p>0,0001</p>
</td>
</tr>
<tr>
<td width="108">
<p>0,0001</p>
</td>
<td width="108">
<p>0,3882</p>
</td>
<td width="108">
<p>0,766029</p>
</td>
<td width="108">
<p>0,0001</p>
</td>
<td width="108">
<p>19999</p>
</td>
<td width="108">
<p>0,00001</p>
</td>
</tr>
<tr>
<td width="108">
<p>0,00001</p>
</td>
<td width="108">
<p>0,38823</p>
</td>
<td width="108">
<p>0,766029</p>
</td>
<td width="108">
<p>1e-05</p>
</td>
<td width="108">
<p>199999</p>
</td>
<td width="108">
<p>0,000001</p>
</td>
</tr>
</tbody>
</table>
<p><strong>&nbsp;</strong></p>
<table width="647">
<tbody>
<tr>
<td colspan="5" width="647">
<p>Метод деления отрезка пополам</p>
</td>
</tr>
<tr>
<td width="129">
<p>ɛ</p>
</td>
<td width="129">
<p>x</p>
</td>
<td width="129">
<p>y</p>
</td>
<td width="129">&nbsp;</td>
<td width="129">
<p>N</p>
</td>
</tr>
<tr>
<td width="129">
<p>0,1</p>
</td>
<td width="129">
<p>0,375</p>
</td>
<td width="129">
<p>0,766391</p>
</td>
<td width="129">
<p>0,0625</p>
</td>
<td width="129">
<p>9</p>
</td>
</tr>
<tr>
<td width="129">
<p>0,01</p>
</td>
<td width="129">
<p>0,390625</p>
</td>
<td width="129">
<p>0,766041</p>
</td>
<td width="129">
<p>0,0078125</p>
</td>
<td width="129">
<p>15</p>
</td>
</tr>
<tr>
<td width="129">
<p>0,001</p>
</td>
<td width="129">
<p>0,38862</p>
</td>
<td width="129">
<p>0,766029</p>
</td>
<td width="129">
<p>0,000976562</p>
</td>
<td width="129">
<p>21</p>
</td>
</tr>
<tr>
<td width="129">
<p>0,0001</p>
</td>
<td width="129">
<p>0,388245</p>
</td>
<td width="129">
<p>0,766029</p>
</td>
<td width="129">
<p>6,10352e-05</p>
</td>
<td width="129">
<p>29</p>
</td>
</tr>
<tr>
<td width="129">
<p>0,00001</p>
</td>
<td width="129">
<p>0,388229</p>
</td>
<td width="129">
<p>0,766029</p>
</td>
<td width="129">
<p>7,62939e-06</p>
</td>
<td width="129">
<p>35</p>
</td>
</tr>
</tbody>
</table>
<p><strong>&nbsp;</strong></p>
<table width="643">
<tbody>
<tr>
<td colspan="5" width="643">
<p>Метод перебора</p>
</td>
</tr>
<tr>
<td width="129">
<p>ɛ</p>
</td>
<td width="129">
<p>x</p>
</td>
<td width="128">
<p>y</p>
</td>
<td width="129">&nbsp;</td>
<td width="128">
<p>N</p>
</td>
</tr>
<tr>
<td width="129">
<p>0,1</p>
</td>
<td width="129">
<p>0,4</p>
</td>
<td width="128">
<p>0,76632</p>
</td>
<td width="129">
<p>0,1</p>
</td>
<td width="128">
<p>19</p>
</td>
</tr>
<tr>
<td width="129">
<p>0,01</p>
</td>
<td width="129">
<p>0,39</p>
</td>
<td width="128">
<p>0,766035</p>
</td>
<td width="129">
<p>0,01</p>
</td>
<td width="128">
<p>199</p>
</td>
</tr>
<tr>
<td width="129">
<p>0,001</p>
</td>
<td width="129">
<p>0,388</p>
</td>
<td width="128">
<p>0,766029</p>
</td>
<td width="129">
<p>0,001</p>
</td>
<td width="128">
<p>1999</p>
</td>
</tr>
<tr>
<td width="129">
<p>0,0001</p>
</td>
<td width="129">
<p>0,3882</p>
</td>
<td width="128">
<p>0,766029</p>
</td>
<td width="129">
<p>0,0001</p>
</td>
<td width="128">
<p>19999</p>
</td>
</tr>
<tr>
<td width="129">
<p>0,00001</p>
</td>
<td width="129">
<p>0,38823</p>
</td>
<td width="128">
<p>0,766029</p>
</td>
<td width="129">
<p>1e-05</p>
</td>
<td width="128">
<p>199999</p>
</td>
</tr>
</tbody>
</table>
<p><strong>&nbsp;</strong></p>
<p>;</p>
<p>N=N_расчет=(b-a)/ε-1;
N_1=N_(1 расчет)=(2-0)/0,1-1=19,  
N_2=N_(2 расчет)=(2-0)/0,01-1=199,  и т.д.
&nbsp;</p>
<p><a name="_Toc69730550"></a>Графики эффективности пассивных и последовательных методов</p>

![image](https://github.com/ktsmsnv/one-dimensional-optimization/assets/126246369/2c8e3ee7-3a9e-4539-a4bf-0fcf54087ac6)
<p>Рисунок 2 &minus; График эффективности пассивных методов</p>

![image](https://github.com/ktsmsnv/one-dimensional-optimization/assets/126246369/8aefb768-33c3-4144-bbb0-89fc0258e6f8)
<p>Рисунок 3 &minus; График эффективности последовательных методов</p>

<p><a name="_Toc69730551"></a>Код программы</p>
<p>#include &lt;iostream&gt;</p>
<p>using namespace std;</p>
<p>&nbsp;</p>
<p>double f(double x) //заданная функция</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; return 1.5*pow(x, 3) + exp(-x);</p>
<p>}</p>
<p>&nbsp;</p>
<p>void zolotoe_sechenie(double a, double b) //метод молотого сечения</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; int k = 0; //кол-во (вычисл-ых) экспериментов, понадобившихся для достижения заданной точности</p>
<p>&nbsp;&nbsp;&nbsp; double E;</p>
<p>&nbsp;&nbsp;&nbsp; cout &lt;&lt; "Введите точность Е: "; cin &gt;&gt; E;</p>
<p>&nbsp;&nbsp;&nbsp; double t = (1 + sqrt(5)) / 2; //пропорция t золотое сечение</p>
<p>&nbsp;&nbsp;&nbsp; double x1, x2, y1, y2, Eгар, x, y, Np;</p>
<p>&nbsp;&nbsp;&nbsp; Np = ceil((log((b - a) / (2 * E)) / log(t)) + 1); //расчетное число экспериментов для достижения заданной точности</p>
<p>&nbsp;&nbsp;&nbsp; x1 = b - (b - a) / t; //первый выбор точки x, делящей отрезок [a;b] в пропорции золотого сечения</p>
<p>&nbsp;&nbsp;&nbsp; y1 = f(x1);</p>
<p>&nbsp;&nbsp;&nbsp; x2 = a + (b - a) / t;//второй выбор точки x, делящей отрезок [a;b] в пропорции золотого сечения</p>
<p>&nbsp;&nbsp;&nbsp; y2 = f(x2);</p>
<p>&nbsp;&nbsp;&nbsp; k = 2;</p>
<p>&nbsp;&nbsp;&nbsp; do</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; if (y1 &lt; y2) { b = x2; x2 = x1; y2 = y1; x1 = a + b - x2;//определение симметричной точки</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; y1 = f(x1); }</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; else { a = x1; x1 = x2; y1 = y2; x2 = a + b - x1;//определение симметричной точки</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; y2 = f(x2); }</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; k++;</p>
<p>&nbsp;&nbsp;&nbsp; } while ((b - a) &gt; 2 * E * t);</p>
<p>&nbsp;&nbsp;&nbsp; //отрезок локализации:</p>
<p>&nbsp;&nbsp;&nbsp; { if (y1 &lt; y2) b = x2;</p>
<p>&nbsp;&nbsp;&nbsp; else a = x1;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; x = (a + b) / 2; //приближенное решение (середина последнего отрезка локализации)</p>
<p>&nbsp;&nbsp;&nbsp; y = f(x);</p>
<p>&nbsp;&nbsp;&nbsp; Eгар = (b - a) / 2; //достигнутая гарантированная точность решения</p>
<p>&nbsp;&nbsp;&nbsp; cout &lt;&lt; " x = " &lt;&lt; x &lt;&lt; "\n y = " &lt;&lt; y &lt;&lt; "\n N = " &lt;&lt; k &lt;&lt; "\n Nрасчет = " &lt;&lt; Np &lt;&lt;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; "\n Егарант = " &lt;&lt; Eгар &lt;&lt; "\n";</p>
<p>&nbsp;&nbsp;&nbsp; system("pause");</p>
<p>}</p>
<p>&nbsp;</p>
<p>void porazryad_poisk(double a, double b)</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; int k;</p>
<p>&nbsp;&nbsp;&nbsp; double E, h, x0, y0, x1, y1, Eгар, X, Y;</p>
<p>&nbsp;&nbsp;&nbsp; cout &lt;&lt; " Введите точность Е : "; cin &gt;&gt; E;</p>
<p>&nbsp;&nbsp;&nbsp; h = (b - a) / 4; //шаг перехода в следующую точку</p>
<p>&nbsp;&nbsp;&nbsp; x0 = a; //текущая точка</p>
<p>&nbsp;&nbsp;&nbsp; y0 = f(x0);</p>
<p>&nbsp;&nbsp;&nbsp; k = 1; //кол-во (вычисл-ых) экспериментов, понадобившихся для достижения заданной точности</p>
<p>cy:</p>
<p>&nbsp;&nbsp;&nbsp; x1 = x0 + h; //следующая точка</p>
<p>&nbsp;&nbsp;&nbsp; y1 = f(x1);</p>
<p>&nbsp;&nbsp;&nbsp; k++;</p>
<p>&nbsp;&nbsp;&nbsp; if (y0 &gt; y1) //функция убывает</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; x0 = x1;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; y0 = y1;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; else goto sl; //функция начала расти</p>
<p>&nbsp;&nbsp;&nbsp; if ((x0 &gt; a) &amp;&amp; (x0 &lt; b)) //находимся на отрезке</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; goto cy;</p>
<p>sl:</p>
<p>&nbsp;&nbsp;&nbsp; if (abs(h) &lt;= E) //точность достигнута</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; X = x0;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Y = y0;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Eгар = h;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; else //точность не достигнута, меняем направление</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; x0 = x1;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; y0 = y1;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; h = -h / 4;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; goto cy;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; cout &lt;&lt; " х = " &lt;&lt; X &lt;&lt; "\n y = " &lt;&lt; Y &lt;&lt; "\n Егарант = " &lt;&lt; Eгар &lt;&lt; "\n N = " &lt;&lt;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; k &lt;&lt; "\n";</p>
<p>&nbsp;&nbsp;&nbsp; system("pause");</p>
<p>&nbsp;&nbsp;&nbsp; return;</p>
<p>}</p>
<p>&nbsp;</p>
<p>void passiv_optimal(double a, double b)</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; int N, i, k;</p>
<p>&nbsp;&nbsp;&nbsp; double d, * x, * y, X = 0, Y = 0, Eгар = 0;</p>
<p>&nbsp;&nbsp;&nbsp; cout &lt;&lt; " N = "; cin &gt;&gt; N; cout &lt;&lt; " d = "; cin &gt;&gt; d;</p>
<p>&nbsp;&nbsp;&nbsp; x = new double[N];</p>
<p>&nbsp;&nbsp;&nbsp; y = new double[N];</p>
<p>&nbsp;&nbsp;&nbsp; if (N % 2 == 0)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; k = N / 2;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; for (i = 1; i &lt;= k; i++)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; x[2 * i] = a + i * (b - a) / (k + 1);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; x[2 * i - 1] = x[2 * i] - d;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; for (i = 1; i &lt;= N; i++)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; y[i] = f(x[i]);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; double yl = y[1];</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; int l = 1;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; for (i = 1; i &lt;= N; i++)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; if (y[i] &lt; yl)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; yl = y[i];</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; l = i;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; X = x[l];</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Y = y[l];</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Eгар = (x[l + 1] - x[l - 1]) / 2;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; else</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; for (i = 1; i &lt;= N; i++)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; x[i] = a + i * (b - a) / (N + 1);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; for (i = 1; i &lt;= N; i++)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; y[i] = f(x[i]);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; double yl = y[1];</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; int l = 1;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; for (i = 1; i &lt;= N; i++)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; if (y[i] &lt; yl)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;yl = y[i];</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; l = i;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; X = x[l];</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Y = y[l];</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Eгар = (b - a) / (N + 1);</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; cout &lt;&lt; " х = " &lt;&lt; X &lt;&lt; "\n y = " &lt;&lt; Y &lt;&lt; "\n Егарант = " &lt;&lt; Eгар &lt;&lt; "\n";</p>
<p>&nbsp;&nbsp;&nbsp; system("pause");</p>
<p>&nbsp;&nbsp;&nbsp; return;</p>
<p>}</p>
<p>&nbsp;</p>
<p>void delenie_popolam(double a, double b)</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; double E, Eгар;</p>
<p>&nbsp;&nbsp;&nbsp; cout &lt;&lt; "Введите точность Е: "; cin &gt;&gt; E;</p>
<p>&nbsp;&nbsp;&nbsp; double x[5], y[4], yl, xl;</p>
<p>&nbsp;&nbsp;&nbsp; int i, N, l;</p>
<p>&nbsp;&nbsp;&nbsp; x[2] = (a + b) / 2;&nbsp; //середина отрезка неопределенности</p>
<p>&nbsp;&nbsp;&nbsp; y[2] = f(x[2]);</p>
<p>&nbsp;&nbsp;&nbsp; N = 1; //счетчик экспериментов</p>
<p>&nbsp;&nbsp;&nbsp; while (b - a &gt; 2 * E)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; x[0] = a;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; x[4] = b;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; x[1] = (a + x[2]) / 2;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; y[1] = f(x[1]);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; x[3] = (x[2] + b) / 2;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; y[3] = f(x[3]);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; N += 2;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; /*поиск минимума*/</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; yl = y[1]; xl = x[1]; l = 1;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; for (i = 2; i &lt; 4; i++)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; if (yl &gt; y[i]) { yl = y[i]; xl = x[i]; l = i; }</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; a = x[l - 1];</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; b = x[l + 1];</p>
<p>&nbsp;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; x[2] = xl;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; y[2] = yl;</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; Eгар = (b - a) / 2; //достигнутая гарантированная точность решения</p>
<p>&nbsp;&nbsp;&nbsp; cout &lt;&lt; " x = " &lt;&lt; x[2] &lt;&lt; "\n y = " &lt;&lt; y[2] &lt;&lt; "\n N = " &lt;&lt; N &lt;&lt; "\n Егарант = " &lt;&lt; Eгар &lt;&lt; "\n";</p>
<p>&nbsp;&nbsp;&nbsp; system("pause");</p>
<p>}</p>
<p>&nbsp;</p>
<p>void dihotomiya(double a, double b)</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; double E, Eгар;</p>
<p>&nbsp;&nbsp;&nbsp; cout &lt;&lt; "Введите точность Е: "; cin &gt;&gt; E;</p>
<p>&nbsp;&nbsp;&nbsp; double d = E / 10, x, y1, y2;</p>
<p>&nbsp;&nbsp;&nbsp; int N; N = 0; //счетчик экспериментов</p>
<p>&nbsp;&nbsp;&nbsp; while (b - a &gt; 2 * E)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; x = (a + b) / 2;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; y1 = f(x - d);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; y2 = f(x + d);</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; N += 2;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (y1 &lt; y2 ? b = x + d : a = x - d);</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; x = (a + b) / 2;</p>
<p>&nbsp;&nbsp;&nbsp; y1 = f(x);</p>
<p>&nbsp;</p>
<p>&nbsp;&nbsp;&nbsp; Eгар = (b - a) / 2; //достигнутая гарантированная точность решения</p>
<p>&nbsp;&nbsp;&nbsp; cout &lt;&lt; " x = " &lt;&lt; x &lt;&lt; "\n y = " &lt;&lt; y1 &lt;&lt; "\n N = " &lt;&lt; N &lt;&lt; "\n Егарант = " &lt;&lt; Eгар &lt;&lt; "\n";</p>
<p>&nbsp;&nbsp;&nbsp; system("pause");</p>
<p>}</p>
<p>&nbsp;</p>
<p>void perebor(double a, double b)</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; int i, N;</p>
<p>&nbsp;&nbsp;&nbsp; double * x, * y, X = 0, Y = 0, Eгар = 0;</p>
<p>&nbsp;&nbsp;&nbsp; cout &lt;&lt; " N = "; cin &gt;&gt; N;</p>
<p>&nbsp;&nbsp;&nbsp; x = new double[N];</p>
<p>&nbsp;&nbsp;&nbsp; y = new double[N];</p>
<p>&nbsp;</p>
<p>&nbsp;&nbsp;&nbsp; for (i = 1; i &lt;= N; i++)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; x[i] = a + i * ((b - a) / (N + 1));</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; for (i = 1; i &lt;= N; i++)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; y[i] = f(x[i]);</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; double yl = y[1];</p>
<p>&nbsp;&nbsp;&nbsp; int l = 1;</p>
<p>&nbsp;&nbsp;&nbsp; for (i = 1; i &lt;= N; i++)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; if (y[i] &lt; yl)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; yl = y[i];</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; l = i;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; X = x[l];</p>
<p>&nbsp;&nbsp;&nbsp; Y = y[l];</p>
<p>&nbsp;&nbsp;&nbsp; Eгар = (b - a) / (N + 1);</p>
<p>&nbsp;&nbsp;&nbsp; cout &lt;&lt; " х = " &lt;&lt; X &lt;&lt; "\n y = " &lt;&lt; Y &lt;&lt; "\n Егарант = " &lt;&lt; Eгар &lt;&lt; "\n N = " &lt;&lt; N &lt;&lt; "\n";</p>
<p>&nbsp;&nbsp;&nbsp; system("pause");</p>
<p>&nbsp;}</p>
<p>&nbsp;</p>
<p>void main()</p>
<p>{</p>
<p>&nbsp;&nbsp;&nbsp; double a = 0, b = 2;</p>
<p>&nbsp;&nbsp;&nbsp; setlocale(LC_ALL, "Russian");</p>
<p>&nbsp;&nbsp;&nbsp; int j;</p>
<p>&nbsp;&nbsp;&nbsp; while (1)</p>
<p>&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; system("cls");</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cout &lt;&lt; "1. Метод перебора " &lt;&lt; endl;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cout &lt;&lt; "2. Пассивный оптимальный метод " &lt;&lt; endl;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cout &lt;&lt; "3. Поразрядный поиск " &lt;&lt; endl;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cout &lt;&lt; "4. Деление отрезка пополам " &lt;&lt; endl;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cout &lt;&lt; "5. Дихотомия " &lt;&lt; endl;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cout &lt;&lt; "6. Золотое сечение " &lt;&lt; endl;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cout &lt;&lt; "7. Выход из программы." &lt;&lt; endl;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cout &lt;&lt; " Ваш выбор (1-7): ";</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; cin &gt;&gt; j;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; switch (j)</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; case 1:perebor(a, b); break;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; case 2:passiv_optimal(a, b); break;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; case 3:porazryad_poisk(a, b); break;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; case 4:delenie_popolam(a, b); break;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; case 5:dihotomiya(a, b); break;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; case 6:zolotoe_sechenie(a, b); break;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; case 7: cout &lt;&lt; " Конец работы.\n";&nbsp; system("pause"); return;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; default: cout &lt;&lt; " Ошибка: нет такого пункта меню.\n"; break;</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }</p>
<p>&nbsp;&nbsp;&nbsp; }</p>
<p>}</p>
<p>&nbsp;</p>
<p><a name="_Toc69730552"></a>Блок-схемы функций методов</p>

![image](https://github.com/ktsmsnv/one-dimensional-optimization/assets/126246369/c58f9e7d-27d2-4f2d-ad5c-9a66ede67517)
<p>Рисунок 4 &minus; Блок-схема метода перебора</p>

![image](https://github.com/ktsmsnv/one-dimensional-optimization/assets/126246369/d9e3a1a0-5cb3-47b6-b82a-97904be8d196)
<p>Рисунок 5 &minus; Блок-схема пассивно-оптимального метода</p>

![image](https://github.com/ktsmsnv/one-dimensional-optimization/assets/126246369/8e1290d3-7c80-4c66-b262-d7b2f1f2a100)
<p>Рисунок 6 &minus; Блок-схема поразрядного поиска&nbsp;</p>

![image](https://github.com/ktsmsnv/one-dimensional-optimization/assets/126246369/8dc307c1-0a9d-4f2d-a4f6-688c36823851)

<p>Рисунок 7 &minus; Блок-схема метода деления отрезка пополам</p>

![image](https://github.com/ktsmsnv/one-dimensional-optimization/assets/126246369/1530cd80-cd46-418b-a1be-993ab5faef68)
<p>Рисунок 8 &minus; Блок-схема метода дихотомии</p>

![image](https://github.com/ktsmsnv/one-dimensional-optimization/assets/126246369/0cd5b321-a280-43e4-bf95-238d64cfdd0c)
<p>Рисунок 9 &minus; Блок-схема метода золотого сечения</p>

<p><a name="_Toc69730553"></a>Вывод: в ходе данной лабораторной работы было проведено сравнение метода перебора, пассивного оптимального метода, метод поразрядного поиска, метод деления отрезка пополам, метод дихотомия и метод золотого сечения.</p>
<p><em>Для заданной целевой функции на заданном отрезке локализации лучшие результаты дал метод золотого сечения.</em></p>
