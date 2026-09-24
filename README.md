## Hi, I'm Anna

PhD in probability theory. I analyse experiments and business data, and I care most
about one question: **is this result real, and what is it worth?**

Most A/B tests are read wrong. Checking results five times during a test pushes the
false-positive rate from 5% to 26%; testing ten metrics at once gives a 40% chance
that at least one looks "significant" by chance alone. A platform will hand you a
number either way. My work is knowing when to believe it.

---

### Selected work

**[A/B Testing: should we ship the new landing page?](https://github.com/Reshetenko/AB-testing)**
Control 12.04% vs treatment 11.88%, p = 0.190, 95% CI [−0.394, +0.078] pp — no
significant improvement. The project doesn't stop at the p-value: it translates the
result into money under stated assumptions, giving −$142k expected, −$354k downside
and +$70k upside per month. Recommendation: do not roll out. The upside is small and
uncertain; the downside is not.
*Python · hypothesis testing · confidence intervals · decision-risk modelling · PDF report*
[Live dashboard →](https://reshetenko.github.io/AB-testing/dashboard/)

**[Superstore: where a growing business loses money](https://github.com/Reshetenko/superstore-sales-analysis)**
51,290 rows, 25,035 orders, four years, seven markets. Sales grew from $2.26M to
$4.30M, but margin held at 11.6% — and **24.5% of all order lines were loss-making**.
The analysis isolates which markets, categories and discount policies destroy profit,
and what to change.
*Python · pandas · profitability analysis · customer and product segmentation · LaTeX report*
[Live dashboard →](https://reshetenko.github.io/superstore-sales-analysis/dashboard/)

Both repositories include the data, the scripts, a written report and a dashboard,
and both reproduce from a single command.

---

### What I work on

Experiment design and analysis — power, sample size, stopping rules, multiple
comparisons. Turning analysis into a decision with the cost of being wrong attached.
Building the data pipeline underneath when the data isn't ready to be analysed.

**Tools** — Python (pandas, NumPy, SciPy) · SQL · statistical modelling · data
extraction from documents and the web · LaTeX and automated report generation

📫 anna@explicitmathematicsprogram.com
