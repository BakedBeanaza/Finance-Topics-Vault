# Structure / Layout
**C H A P T E R   1**
**What Is an Investment**
- Investment Defined

**Measures of Return and Risk**
- Measures of Historical Rates of Return
- Computing Mean Historical Returns
- Calculating Expected Rates of Return
- Measuring the Risk of Expected Rates of Return
- Risk Measures for Historical Returns

**Determinants of Required Rates of Return**
- The Real Risk-Free Rate
- Factors Influencing the Nominal Risk-Free Rate (NRFR)
- Risk Premium
- Risk Premium and Portfolio Theory
- Fundamental Risk versus Systematic Risk
- Summary of Required Rate of Return

**Relationship between Risk and Return**
- Movement along the SML
- Changes in the lope of the SML
- Changes in Capital Market Conditions or Expected Inflation
- Summary of Changes in the Required Rate of Return
# What is an Investment?
- **Systematic Risk** - the risk that prevails when an asset is part of a diversified portfolio.
- trade-off of *present* consumption for a higher level of *future* consumption is the **reason for saving**.
- **Pure rate of interest** - rate of exchange between *future consumption* (future dollars) and *current consumption* (current dollars)
- **Pure time value of money** - people's willingness to pay this difference for borrowed funds and their desire to receive a surplus on their savings
## Investment Defined
- **Investment** - current commitment of dollars for a period of time in order to derive future payments that will compensate the investor for:
	1. the time the funds are committed
	2. the expected rate of inflation during this time period
	3. the uncertainty of the future payments (***risk***)
- ''**Investor**" can be:
	- individual
	- government
	- a pension fund
	- a corporation
- "**Investments**" being referred to are all types of investments such as:
	- investments by corporations like:
		- Plants (Factories, etc.)
		- Equipments
	- investments by individuals like:
		- Stocks (Shares)
		- Bonds
		- Commodities
		- Real Estate
- **Required Rate of Return** - a rate of return that compensates them for the: 
	1. time period of the investment
	2. expected rate of inflation
	3. uncertainty of future cash flows
# Measures of Return and Risk
### Measure of Historical Rates of Return
#### HPR
- **Holding period** - the period during which you own an investment
- **Holding period return (HPR)** - the return for the holding period

$$HPR=\frac{Ending\ Value\ of\ Investment}{Beginning\ Value\ of\ Investment}$$

Example, if you were to commit \$200 to an investment at the beginning of the year and you get back \$220 at the end of the year, ***what is your return for the period***?

$$HPR=\frac{Ending\ Value\ of\ Investment}{Beginning\ Value\ of\ Investment}$$

$$HPR=\frac{\$220}{\$200}=1.10$$

The HPR for that period is **1.10**. 
- The HPR value will always be zero or greater
- HPR Value can never be negative
- HPR Value > 1 = increase in wealth (profit)
- HPR Value < 1 = decline in wealth (loss)
- HPR is a **measure of return**

---

#### HPY
- investors generally evaluate returns in **PERCENTAGE TERMS** on an **ANNUAL BASIS**
- **Holding Period Yield (HPY)** - HPR that is converted to a percentage rate (not yet annual)

$$ HPY=HPR-1$$

In the example earlier:

$$HPY=1.10-1$$

$$HPY=0.10$$

$$HPY=10\%$$

To derive an annual HPY, you compute and annual HPR and then subtract by 1 (this means that the HPR Formula itself adjusts)

$$Annual\ HPR=HPR^{1/n}$$

where $n$ = number of years an investment is held

---

**Consider an investment that cost \$250 and is worth \$350 after being held for two years:**

$HPR=\frac{Ending\ Value\ of\ Investment}{Beginning\ Value\ of\ Investment}=\frac{\$350}{\$250}$

$HPR=1.40$

$Annual\ HPR=1.40^{1/n}$

$Annual\ HPR=1.40^{1/2}$

$Annual\ HPR=1.1832$

$Annual\ HPY=1.1832-1=0.1832$

$Annual\ HPY=18.32\%$

---

**Another investment that cost \$500 but declined to \$400 after being held for a year:**

$HPR=\frac{Ending\ Value\ of\ Investment}{Beginning\ Value\ of\ Investment}=\frac{\$400}{\$500}$

$HPR=0.80$

$HPY=0.80-1=0.20$

$HPY=20\%$

---

**A multiple-year loss over two years would look like so:**

$HPR=\frac{Ending\ Value\ of\ Investment}{Beginning\ Value\ of\ Investment}=\frac{\$750}{\$1,000}=0.75$

$Annual\ HPR=1.40^{1/n}=1.40^{1/2}=0.866$

$Annual\ HPY=0.866-1=-0.134=-13.4\%$

---

**Consider an investment of \$100 for only six months ($n$ = 0.5)that earned a return of \$12:**

$HPR=\frac{\$112}{\$100}=1.12$

$Annual\ HPR=1.12^{1/n}$

$Annual\ HPR=1.40^{1/.5}$

$Annual\ HPR=1.40^{2}$

$Annual\ HPR=1.2544$

$Annual\ HPY=1.2544-1=0.2544$

$Annual\ HPY=25.44\%$

---

### Computing Mean Historical Returns
- When we compute the mean of historical returns, we consider solving the mean rates of return for:
	- a **Single Investment** or,
	- a **Portfolio of Investments**
#### Single Investments
There are two summary measure of return performance:
- **Arithmetic Mean Return**
- **Geometric Mean Return**

---

**Arithmetic Mean (AM) Return**

$$AM=\sum HPY/n$$

where:

$\sum HPY$ = sum of **annual** holding period yields

$n$ = number of years

---

**Geometric Mean (GM) Return**

$$GM=[\prod HPR]^{1/n}-1$$

where:

$\prod HPR$ = product of the annual holding period returns

$n$ = number of years

---

Example:

| Year | Beginning Value | Ending Value | HPR  |  HPY  |
| :--: | :-------------: | :----------: | :--: | :---: |
|  1   |      100.0      |    115.0     | 1.15 | 0.15  |
|  2   |      115.0      |    138.0     | 1.20 | 0.20  |
|  3   |      138.0      |    110.4     | 0.80 | -0.20 |

$AM=[(0.15)+(0.20)+(-0.20)]/3$

$AM=0.15/3$

$AM=0.05=5\%$

$GM=[(1.15)\times(1.20)\times(0.80)]^{1/3}-1$

$GM=(1.104)^{1/3}-1$

$GM=1.03353-1$

$GM=0.03353=3.353\%$

> [!note] Arithmetic Mean or Geometric Mean? Which is Better?
> **Side note from Vince**: As I have studied with CFA Materials in anticipation for ICFC, usually the Geometric Mean (GM) Return is a superior measure than Arithmetic Mean (AM) Return as GM anticipates the compounding of values as well as negative values and thus delivers a more realistic result and a closer outcome to the actual ending balance.
> 
> Meanwhile AM is more like a summarized/easier measure to understand but does not really consider compounding and negative values hence when there are negative values included in the computation of AM, usually the resulting return is far off from the actual outcome of ending balance. However, I would still suggest to utilize AM as a measure of "volatility" or "movement" of an investment, as it would accurately show how much an investment "moves" up and down.

---

Example 2:

| Year | Beginning Value | Ending Value | HPR  |  HPY  |
| :--: | :-------------: | :----------: | :--: | :---: |
|  1   |       50        |     100      | 2.00 | 1.00  |
|  2   |       100       |      50      | 0.50 | -0.50 |

$AM=[(1.00)+(-0.50)]/2=0.50/2$

$AM=0.25=25\%$

- **Do you see how weird it is?**
	- there is no change in return (well... there is if computed per year, but when computed during ALL of its holding periods then there is none) and thus therefore no return yet AM is computed to be 25%. From what I've said earlier, we can use AM not as an accurate measure of return (since it does not consider compounding and negative values) but rather as a measure of volatility, where we can see that the movement of the values are in can be computed as a mean of 25%

$GM=(2.00\times0.50)^{1/2}-1=(1.00)^{1/2}-1$

$GM=1.00-1=0\%$

- **Now it is accurate...when using GM...**
	- This is why the GM measure is more accurate. That single investment truly never garnered any return within its 2 years of holding, that is why GM returns 0%... because it never really changed/there truly was never any returns.

---

#### A Portfolio of Investments

| Investment | No. of Shares | Beg. Price | Beg. Market Value | End. Price | End. Market Value | HPR  | HPY | Market Weight<sup>a</sup> | Weighted HPY<sup>b</sup> |
| :--------: | :-----------: | :--------: | :---------------: | :--------: | :---------------: | :--: | :-: | :-----------------------: | :----------------------: |
|     A      |    100,000    |    $10     |    $1,000,000     |    $12     |    $1,200,000     | 1.20 | 20% |           0.05            |           0.01           |
|     B      |    200,00     |    $20     |    $4,000,000     |    $21     |    $4,200,000     | 1.05 | 5%  |           0.20            |           0.01           |
|     C      |    500,00     |    $30     |    $15,000,000    |    $33     |    $16,500,000    | 1.10 | 10% |           0.75            |          0.075           |
|   Total    |               |            |    $20,000,000    |            |    $21,900,000    |      |     |           1.00            |          0.095           |

<sup>a</sup>Weights are based on beginning values

<sup>b</sup>Weighted HPY = $HPY\times Market\ Weight$

$$HPR=\frac{21,900,000}{20,000,000}=1.095$$

$$HPY=1.095-1=0.095=9.5\%$$

---

### Calculating Expected Rates of Return
- **Risk** - is the uncertainty that an investment will earn its expected rate of return
- "*point estimate*" = an investors *most likely* estimate

#### Expected Return

$$Expected\ Return=\sum_{i=1}^{n}(Probability\ of\ Return)\times(Possible\ Return)$$

$$E(R_i)=[(P_1)(R_1)+(P_2)(R_2)+(P_3)(r_3)+...+(P_n)(R_n)]$$

$$E(R_i)=\sum_{i=1}^{n}(P_i)(R_i)$$

Example \[Probability is 100% (1.0), Possible Return is 5% (0.05)]:

$$E(R_i)=(1.0)(0.05)=0.05=5\%$$

There are cases where investors try to estimate probabilities for multiple economic scenarios:

| Economic Conditions          | Probabilty | Rate of Return |
| ---------------------------- | ---------- | -------------- |
| Strong Econ, No Inf          | 0.15       | 0.20           |
| Weak Econ, Above-average Inf | 0.15       | -0.20          |
| No Major Change in Econ      | 0.70       | 0.10           |

$$E(R_i)=[(0.15)(0.20)]+[(0.15)(-0.20)]+[(0.70)(0.10)]$$

$$E(R_i)=0.07=7\%$$

---

Another Example:
![[Pasted image 20260726021030.png]] 

Solution:
![[Pasted image 20260726021118.png]]

(*I ain't typing allat*) but anyway answer is 5%.

### Measuring the Risks of Expected Rates of Return
There are two possible measures of risk (uncertainty):
- **Variance**
	- the larger the variance for the expected rate of return, the **greater the dispersion of expected returns** and the **GREATER THE UNCERTAINTY** or **risk** of the investment.
- **Standard Deviation**
	- square root of variance
	- its final outcome can be converted into percentage and thus it serves as "**how far will results deviate from my expectations**"

---

#### Variance

$$Variance\ (\sigma^2)=\sum_{i=1}^{n}(Probability)\times(Possible\ Return-Expected\ Return)^2$$

$$Variance\ (\sigma^2)=\sum_{i=1}^{n}(P_i)[R_i-E(R_i)]^2$$

Under perfect certainty the variance would be 0:
$$(\sigma^2)=\sum_{i=1}^{n}(P_i)[R_i-E(R_i)]^2$$

$$(\sigma^2)=1.0(0.05-0.05)^2=1.0(0.0)=0$$

Following the Second Example:

| Economic Conditions          | Probabilty | Rate of Return |
| ---------------------------- | ---------- | -------------- |
| Strong Econ, No Inf          | 0.15       | 0.20           |
| Weak Econ, Above-average Inf | 0.15       | -0.20          |
| No Major Change in Econ      | 0.70       | 0.10           |

Recall that this example has an expected return of 0.07 or 7%:

$$E(R_i)=[(0.15)(0.20)]+[(0.15)(-0.20)]+[(0.70)(0.10)]$$

$$E(R_i)=0.07=7\%$$

Now solving for its variance would go like so:

$$(\sigma^2)=\sum_{i=1}^{n}(P_i)[R_i-E(R_i)]^2$$

$\sigma^2=[(0.15)(0.20-0.07)^2+(0.15)(-0.20-0.07)^2+(0.70)(0.10-0.07)^2]$

$\sigma^2=[0.010935+0.002535+0.00063]$

$\sigma^2=0.0141$

---

#### Standard Deviation

$$Standard\ Deviation=\sqrt{\sum_{i=1}^{n}P_i[R_i-E(R_i)]^2}$$

continuing from the earlier example:

$$\sigma=\sqrt{0.0141}$$

$$\sigma=0.11874=11.874\%$$

Therefore when describing this investment example:

| Economic Conditions          | Probabilty | Rate of Return |
| ---------------------------- | ---------- | -------------- |
| Strong Econ, No Inf          | 0.15       | 0.20           |
| Weak Econ, Above-average Inf | 0.15       | -0.20          |
| No Major Change in Econ      | 0.70       | 0.10           |

***You can interpret it as an investment where I expect a 7% return but results could deviate from my expectations by 11.87%.***
This "11.874%" is the magnitude or "*how far*" can something deviate
Other interpretations could be as such:
- "While I expect a 7% return on average, the actual return is likely to fluctuate by about **11.87 percentage points** above or below that mean."
- "The investment has an expected return of 7% with a volatility (risk) of 11.87%."
- "I expect a 7% return, but because of the risk involved, it is common for the actual return to fall anywhere between **-4.87%** (7%−11.87%) and **18.87%** (7%+11.87%)."

---

#### Coefficient of Variation
Variance ($\sigma^2$) and Standard Deviation ($\sigma$) are usually used with the assumption that conditions are similar (similar expected rate of return), **however**, in cases where conditions for two or more investment alternatives are not similar—that is if there are major differences in expected  rate of return then it is necessary to use a measure of *relative variability* to indicate **risk per unit of expected return** (***how much risk you are taking for every unit of return you expect to get***). Thus we use **coefficient of variation (CV)**:

$$Coefficient\ of\ Variation\ (CV)=\frac{Standard\ Deviation\ of\ Returns}{Expected\ Rate\ of\ Returns}$$

$$Coefficient\ of\ Variation\ (CV)=\frac{\sigma_i}{E(R)}$$

Using earlier example:

$$Coefficient\ of\ Variation=\frac{0.11874}{0.07}=1.696$$

This measure of relative variability and risk is used by financial analysts to compare alternative investments with widely different rates of return and standard deviations of returns. Consider another example:

|                    | Investment A | Investment B |
| ------------------ | ------------ | ------------ |
| Expected Return    | 0.07         | 0.12         |
| Standard Deviation | 0.05         | 0.07         |

$$CV_A=\frac{0.05}{0.07}=0.714$$

$$CV_B=\frac{0.07}{0.12}=0.583$$

It seems that Investment B is much more worth it than Investment A as it shows lesser relative variability or lower risk per unit of expected return because it has a substantially higher expected rate of return. Therefore the Lesser the CV, means the lower the risk per unit of expected return, means the lesser risk you are taking for every percent/unit of return, means the more bang for your back
> [!note] What is really going on with this example of Coefficient of Variance (CV)?
> To try and dumb this example down even more. It is said that Investment B is much more worth it or in a different a better "bang-for-your-buck" scenario. Why? Although Investment B has higher risk (a Standard Deviation of 7%) but it also has higher returns which is 12%, that is 5% more returns for only 2% more risk.
> 
> As compared to Investment A where you have lesser risk of 5% sure, but your expected returns aren't a lot (7%) for 2% lesser risk you only get 2% more returns.
> 
> So for you, which is better? 2% more risk for 5% more returns OR 2% lesser risk for 2% more returns, pick your gamble.
> 
> *Hala i-pm nalang jud ko kung wa gihapon ka kasabot. Try nato nig tabangan.*

### Risk Measures for Historical Returns
To measure the risk for a series of historical rates of returns
$$\sigma^2=[\sum_{i=1}^n[HPY_i-E(HPY)]^2]/n$$
where:
$\sigma^2$ = variance of the series
$HPY_i$ = holding period during period $i$
$E(HPY)$ = expected value of the holding period yield that is equal to the arithmetic mean (AM) of the series
$n$ = number of observations

# Determinants of Required Rates of Return
Recall that since you are deferring current consumption for a higher value of future consumption (*saving*), we must have a process that will provide us a rate of return that compensates us for:
	1. time value of money during the period of the investment (the holding period)
	2. the expected inflation rate during that period
	3. the risk involved (uncertainty of cash flows)

The summation of these three components is called the ***required rate of return***

- **Required Rate of Return** - the minimum rate of return that one should accept from an investment to compensate us for deferring consumption

Note that:
- analysis and estimation of the required rate of return is complicated by the behavior of market over time
	- a wide range of rates is available for alternative investments at any point in time
	- rates of return on specific assets change dramatically over time
	- the differences between the rates available on different assets changes over time

### The Real Risk-Free Rate
- **Real Risk-Free Rate (RRFR)**
	- the basic interest rate
	- assumes:
		- no inflation
		- no uncertainty
	- one subjective and one objective factor/s influence this rate
		- subjective: the individual's: time preference of individuals for the consumption of income
			- "how much consumption do they want a year from now to compensate for the deferring/sacrifice"
		- objective: the set of investment opportunities available in the economy
			- investment opportunities available are determined in turn by the long-run real growth of the economy; rapidly growing economy, demands a higher positive rate of return.

### Factors Influencing the Nominal Risk-Free Rate
- nominal rates of interest = real rates of interest + expected inflation rate
- there are **two factors** that influence nominal rate of interest:
	- the relative ease or tightness in the capital markets
	- expected rate of inflation

#### the relative ease or tightness in the capital markets
- recall that the **purpose of capital markets** is to bring together investors who want to invest savings (lenders) with companies that need capital to expand or to governments that need to finance budget deficits (borrowers)
- the cost of these funds that are being lent (the savings of the lenders) is the price that equates the current supply and demand for capital
- but sometimes these costs can change (relative ease or tightness) due to
	- temporary disequilibrium in the capital markets caused by unexpected/sudden change in monetary policy or fiscal policy

#### expected rate of inflation
- if an investor expects that there would be an inflation rate during the holding period of his/her investment, the investor also expects to be compensated for the expected inflation rate.

As such, the investor's nominal required rate of return on a risk-free investment should be:

$$NRFR=[(1+RRFR)\times(1+Expected\ Rate\ of\ Inflation)]-1$$

You can also rearrange the formula to solve for the **Real Risk-Free Rate (RRFR)**:

$$RRFR=[\frac{1+NRFR\ of Return}{1+Rate\ of\ Inflation}]-1$$

Example:
- The nominal return on a U.S. Government T-bills was 9%
- The rate of inflation was 5%
- **What is the RRFR of return on these T-Bills?**

$RRFR=[(1+0.09)/(1+0.05)]-1$
$RRFR=1.038-1$
$RRFR=0.038=3.8\%$

**The RRFR of return on those T-Bills is 3.8%**

- All in all, the NRFR of return is not that good of an estimate because the nominal rate can change drastically in the short run to temporary ease or tightness in the capital markets or the expected inflation rate.

### Risk Premium
- Oftentimes, investors perceive that there is uncertainty about their expected rates of return. This uncertainty comes from other factors beside relative ease or tightness of capital markets and expected inflation rate. 
- **Risk Premium (RP)** - the increase in required rate of return over the NRFR; represents a composite of all uncertainty:
	- Business Risk
	- Financial Risk (Leverage)
	- Liquidity Risk
	- Exchange Rate Risk
	- Country (Political) Risk

#### Business Risk
- the uncertainty of income flows caused by the nature of a firm's business
- the less certain the income flows of the firm, the less certain the income flows to the investors
- therefore investors demand a risk premium for that uncertainty

#### Financial Risk
- the uncertainty introduced by the method by which the firm finances its investments.
- If a firm borrows money from financial institutions that lend, it must pay fixed financing charges (in the form of interest) to its creditors prior to providing income to the common stockholders.
- This increases uncertainty on how much an investor could actually receive, hence there is demand in a risk premium in regards to this.

#### Liquidity Risk
- the uncertainty introduced by the secondary market for an investment.
- When an investor acquires an asset, he or she will expect this investment to mature, but we are unsure as to how fast we can convert this investment in to pure liquid cash
- This asset in the form of an investment can turn into liquid cash immediately or not depending on whether someone else would like to purchase it. There comes uncertainty with how fast this investment can be converted into cash.
- Therefore investors also demand a risk premium for this uncertainty.
- An investor asks the following questions:
	- How long will it take to convert this investment into cash?
	- How certain is the price to be received?
- Likewise, those that like to acquire this investment asks:
	- How long will it take to acquire the investment?
	- How uncertain is the price to be paid?

#### Exchange Rate Risk
- uncertainty of returns to an investor who acquires securities denominated in a currency different from his or her own.
- This risk becomes bigger as investors purchase and deal with assets not only within their own countries but also outside of theirs. As market environments, and inflation rates of those countries differ, the value could also differ accordingly. This makes the exchange rate between the two currencies more uncertain and this investors demand a risk premium for that.
- The more volatile the exchange rate between two countries, the less certain you would be regarding the exchange rate, which gives you a greater exchange rate risk, and the larger the exchange rate risk premium you would require.

#### Country (Political) Risk
- uncertainty of returns cause by the possibilities of a major change in political or economic environment of a country.
- When investing globally, investors tend to ask:
	- How liquid are the secondary markets for stocks and bonds in the country?
	- Are any of the country's securities traded on major stock exchanges in the United States, London, Tokyo, or Germany?
	- What will happen to exchange rates during the investment period?
	- What is the probability of a political or economic change that will adversely affect your rate of return?
- A good measure of an exchange rate risk would be the absolute variability of a country's exchange rate relative to a composite exchange rate.

**This discussion of risk components can be considered a security's *fundamental risk* because it deals with intrinsic factors that should affect a security's volatility of returns over time.**

$$Risk\ Premium=f(Business\ Risk,\ Financial\ Risk,\ Liquidity\ Risk,\ Exchange\ Rate\ Risk,\ Country\ Risk)$$

### Risk Premium and Portfolio Theory
- investors should use an *external market* measure of risk
- **Portfolio Theory** (Markowitz, 1952, 1959)
	- all rational, profit-maximizing investors would **want to hold a completely diversified market portfolio of risky assets** they then **borrow and lend to arrive at a risk level that is consistent with their risk preferences**
- **Capital Market Theory** (Sharpe, 1964)
	- the relevant risk measure for an individual assets is its ***comovement with the market portfolio***
	- this is an asset's covariance with the market portfolio—Asset's **Systematic Risk**
	- there are also individual assets that have variance that is unrelated to the market portfolio—Asset's **Unsystematic Risk**
	- *The only risk that matters at this point is the **Systematic Risk** \[how the stock moves with the market (beta $\beta$ )]*
		- a $\beta$ = 1 means that an investment or security moves alongside the market: the market increases 10%, the investment also increases 10%
		- a $\beta$ > 1 means that the sensitivity of an investment or security is more than the market (example with $\beta$ = 2, if market increases 10%, investment increases 20%, likewise with losses)
		- a $\beta$ < 1 means that the security or investment is not as sensitive towards the movement of the market.
	- Therefore the ***risk premium for an individual earning asset is a function of the asset's systematic risk with the aggregate market portfolio of risky assets***. The measure of an asset's systematic risk is referred to as its beta:

$$Risk\ Premium=f(Systematic\ Market\ Risk)$$

### Fundamental Risk vs Systematic Risk
One must not confuse:
- market measure of risk (systematic risk)
- fundamental determinants of risk (business risk, financial risk, liquidity risk and so on)
- According to Thompson, 1976, there is a significant relationship between market measure of risk (systematic risk) and fundamental measures of risk, therefore the two can be complementary
- as such one can specify that the risk premium of an asset is either:

$$Risk\ Premium=f(Business\ Risk,\ Financial\ Risk,\ Liquidity\ Risk,\ Exchange\ Rate\ Risk,\ Country\ Risk)$$ 

or

$$Risk\ Premium=f(Systematic\ Market\ Risk)$$

### Summary of Required Rate of Return
# Relationship between Risk and Return
### Movements along the SML
### Changes in the Slope of the SML
### Changes in Capital Market Conditions or Expected Inflation
### Summary of Changes in the Required Rate of Return

