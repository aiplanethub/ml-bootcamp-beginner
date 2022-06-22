<h5><strong>Instructions</strong></h5>

<ul>
	<li>Strongly recommended to use Google Colab Notebook in order to answer the quizzes.</li>
	<li>If you are using Jupyter Notebook, make sure the scikit-learn version is 0.23.1.</li>
	<li>To install scikit-learn run the below command in your jupyter notebook :
	<pre>
<code>!pip&nbsp;install&nbsp;scikit-learn==0.23.1</code></pre>
	</li>
	<li>Or you can use command prompt or conda prompt to install scikit-learn</li>
</ul>

<hr />
<h5><strong>About the Data</strong></h5>

<p>The dataset contains information about US taxpayers. There are 10 independent columns and 1 dependent column. This dataset includes attributes like household income, household debt level, if the taxpayer is married or not, how many cars their household has, if they filed their taxes in the last three years or not.</p>

<p><strong>Data Description</strong></p>

<ul>
	<li>HHI: Household income</li>
	<li>HHDL: Household debt level</li>
	<li>Married: If the taxpayer is married or not</li>
	<li>PoliticalParty: Name of the political party</li>
	<li>CollegeGrads: Grade in College out of 5</li>
	<li>AHHAge: Average household age</li>
	<li>cars: number of cars in house</li>
	<li>Filed in YYYY: Tax filed in given year YYYY</li>
</ul>

<p>To load the dataset execute the given command:</p>

<pre>
<code>import&nbsp;pandas&nbsp;as&nbsp;pd
data&nbsp;=&nbsp;pd.read_csv(&quot;https://raw.githubusercontent.com<a href="https://colab.research.google.com/drive/1Z3KRveCq86w5aGNsYRt3GmRyJ0GShZt1?authuser=1#">/dphi-official/Datasets/master/tax_payers/train</a>_set_label.csv&quot;)</code></pre>

<hr />
<p><strong>Note: Do not perform any operations other than asked in the quiz questions.</strong></p>