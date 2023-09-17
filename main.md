# Operating Manual for Decentralized Stablecoins
1st ed.

adcv, aes, hasu, sebventures

Decentralized stablecoins, like Dai, are a new kind of digital money. They let people around the world save and borrow dollars without reliance on a central authority like a bank. But, people are still trying to understand exactly how these decentralized stablecoins should work. This confusion comes from a few places:
Not understanding what people value in a stablecoin: USDT and USDC dominate the market even though decentralized stablecoins seem more robust.
Not understanding how stablecoin scalability works: Stablecoins like LUSD have had trouble growing and scaling up.
Not understanding what makes some stablecoins safe and others fundamentally unsafe: Certain types of "stablecoins," such as UST, have consistently failed because they are not backed by enough collateral.
In this article, we want to learn from traditional banking to see how it might help us understand decentralized stablecoins better. We're not saying that decentralized stablecoins are just like banks – there are lots of differences, and we'll explore those in future discussions. But, banks have been a key part of the world's financial system for centuries, so we believe studying them can give us some valuable insights for running decentralized stablecoins.

# What is the fundamental business model of a bank?
_“We must remember that at the core of all capital markets activity lies the need to bring together the suppliers of capital with the borrowers of capital. There is much other activity surrounding this basic function in the markets, but this need is paramount. Hence a key ingredient in bank strategy is the management of its assets and liabilities.”_
Prof. Moorad Choudhry “Bank Asset and Liability Management” 

Banks do many things, which can make them hard to understand. But all banks have one thing in common: they accept deposits (money individuals wish to save) and issue loans (money individuals wish to borrow).
In essence, banks accumulate funds from individuals wishing to save and lend out those funds to borrowers wishing to spend. Their profit stems from the interest earned on loans exceeding the interest paid to savers. For banks, money is not merely a business tool; it is their primary product.
To grasp the concept of banking, familiarity with balance sheets is beneficial. A balance sheet details a business's possessions (assets) and how these assets were financed or who ultimately has a claim on these assets (liabilities and equity).
Most businesses own tangible assets such as inventory, machinery, or furnishings, financed through borrowed money or profits earned. However, banks operate differently, considering money as both an asset and a liability - it's what they lend and owe. This concept may appear peculiar, but this is the banking business model.
On a bank's balance sheet, the right side represents the individuals who possess surplus funds they wish to safeguard or can't efficiently utilize. In contrast, the left side represents those in need of borrowed money for their ventures. A bank's role is to bridge the gap between these two groups, making a profit that can be distributed among its shareholders.
By creating this financial marketplace, banks fulfill three key economic roles:
Liquidity agents: Banks facilitate the efficient and cost-effective conversion of assets into cash and vice versa.
Capital markets: Banks help businesses invest and expand, creating jobs by channeling surplus money from savers to borrowers.
Trade enablers: By serving as a trusted intermediary, banks boost both local and international trade, ensuring businesses can transact without fear of financial loss.
A bank's revenue stems from the interest charged on its loans, while expenses include interest on borrowed funds and operational costs such as rent, IT systems, and staff salaries.
To increase profits, a bank aims to:
Increase lending to earn more interest.
Secure lower borrowing rates to reduce expenses.
Cut operational costs.
Simultaneously, a bank must find an appropriate balance of:
Leverage: Determining the ratio of borrowed funds to equity. While more borrowed funds can lead to higher profits, it also carries greater risk if the loans default.
Risk: Deciding the amount of risk it should assume on its loans. Higher risk may lead to larger rewards but can also result in losses if those risks materialize.
The interplay of these factors will dictate whether the bank records a profit or a loss. Banks are subject to stringent regulations, limiting their business choices and typically ensuring moderate profitability.
A bank must balance the duration it anticipates holding a deposit against the expected return period of its investments. While individuals theoretically can withdraw their deposits at any moment, they often retain the money in the bank for extended periods. Therefore, the bank must meticulously decide its investments; an investment with a long return period may lead to difficulties in fulfilling withdrawal requests. 
Banks are fundamentally in the business of maturity transformation–the carry trade of borrowing on shorter durations at lower rates and lending out on longer terms at higher rates. This is a formidable challenge since banks are dependent on the trust of individuals who believe they can retrieve their money at any time. The moment this trust is compromised, the bank's reputation may be irreparably damaged.

## What is the fundamental equation of a stablecoin business model?
The primary concern for bank shareholders is the return on equity (ROE), representing the financial return on their investment. ROE is calculated by dividing net income by equity. This fundamental equation can be further deconstructed into specific factors that highlight various levers for return:
Profitability drivers:
Net Income Margin: This measures how much of the bank's earnings are retained as profit after accounting for all expenses
(Interest income - interest expense) / Earning assets
Efficiency drivers:
Return on Assets (ROA): This demonstrates how profitable a bank is relative to its total assets.
(Net Income Margin x Earning assets - Non-interest income - Provisions for credit losses - Operating expenses) / Total assets
Leverage drivers:
ROE: ROA x Total assets / Equity = Net Income / Equity
Hence, the return on equity can be viewed as a composite of profitability, efficiency, and leverage.
In the context of a decentralized stablecoin, it's important to increase the surplus because, generally speaking, a larger surplus acts as a protective shield for stablecoin users. This shield safeguards against potential losses or the devaluation of assets backing the stablecoin, ensuring the stablecoin's stability and credibility. When a decentralized stablecoin takes less risk on its loans (for e.g. through overcollateralization), the amount of surplus can be reduced. The size of the surplus should depend on the risk assumed on the loans.

## Fundamental Principles for Decentralized Stablecoins
Before getting into the plumbing for optimizing the return on equity, a stablecoin must find a way to meet three key strategic imperatives in order:
Make a product people want to use
Manage liquidity and solvency as primordial constraints
Match assets against liabilities

### 1. Make a product people want to use
A lot of people have a tendency to focus on the asset side of a stablecoin and in designing new mechanisms. At a recent stablecoin summit in France in July 2023 (the excellent Stable Summit) an overwhelming majority of new product presentations focused very heavily on new collateral rebalancing mechanisms, new liquidation mechanisms or new integrations and features. However, very few presentations thought to mention why a user would want to hold their stablecoin in the first place.
Ultimately, the growth of a stablecoin can only really come from the demand side. Every holder of a stablecoin has both monetary and non-monetary benefits to using a stablecoin. The monetary benefits are clear to quantify: They want to earn a yield on their capital, and a coin that pays a 2% rate is more interesting than a coin that pays a 1% or 0% rate. 
Non-monetary benefits are more difficult to pin down. In banks, these could include the range of services that are bundled into a product (payments, credit cards, savings accounts, and so forth). They may also represent the benefits of integrations with card networks or service providers that are attractive and widely accepted. 
The attractiveness of a banking product is a combination of the two and one can offset the other. For example, all else being equal, a bank that has partnerships with fewer or less attractive card issuers will be much less attractive for some users than a bank with better partnerships even at a better savings yield. Similarly, a higher savings rate on a stablecoin can only go so far to make a stablecoin with fewer integrations more attractive than one that has wider adoption.
The overarching, single most important feature a bank or stablecoin can offer is brand value, which is a proxy signal for a combination of features including robustness, trust, reliability and lindyness. Brand value by itself is not a sufficient replacement for actual robustness or actual trust, but is accumulated over time and can differentiate relative to a new competitor. 
For example, HSBC has a longer and more storied history than Revolut. More people are aware of it due to its age, its presence in airports and probably having crossed it in some business transaction around the world, whether in New York, London or Ciudad Juárez. This slowly accumulating effect of awareness drives recognition over time. Of course, what takes decades to build can be undone in mere days with the wrong decisions. 
Demand for a stablecoin therefore largely comes as a result of trust in the stablecoin, materialized through a lower risk premium from the stablecoin user to the stablecoin issuer, and a convenience yield from using it. The combination of trust and a benefit to holding the stablecoin even if it offered 0% monetary returns, produces organic demand for a stablecoin.

### 2. Manage liquidity and solvency as primordial constraints
A significant commonality between a decentralized stablecoin and a bank lies in their liquidity profiles. A liquidity profile emerges whenever a user or a bank customer makes a deposit. Often, a discrepancy exists between the liquidity traits of an investment and the liquidity demands of the depositor. This discrepancy presents an opportunity to generate a return on equity, but it also represents a stringent requirement, as liquidity must be accessible for the user nearly instantly.
Both banks and decentralized stablecoins can experience so-called "bank runs," which occur when investments are tied up in illiquid assets that cannot be readily liquidated and a large number of depositors request their money back simultaneously. This situation tests the bank or stablecoin's ability to fulfill redemptions promptly.
Importantly, a liquidity crunch doesn't necessarily mean that depositors have lost their money. Instead, they may be compelled to accept a delayed liquidation timeline for their deposits. This differs from a solvency crisis, wherein the value of a bank's assets is impaired to the extent that depositors cannot recover their balances regardless of the timeframe. Either crisis can occur individually or concurrently, and a single occurrence is typically enough to irreversibly damage confidence.
Like banks, stablecoins are subject to liquidity and solvency constraints. To function, a stablecoin must meet both of these hard constraints. For example, US Terra (UST) / Luna was a caricature of a stablecoin, as the entire value of its assets was backed by the LUNA token, which only retained its value so long as people believed in its ability to support the UST's value. This structure can be seen as fundamentally insolvent by design. Liquidity constraints also play a critical role as most decentralized stablecoins allow users to redeem the stablecoin for the underlying collateral.
There are two differences between liquidity and solvency constraints in stablecoins relative to banks. 
Firstly, when the solvency of a stablecoin is called into question, the value of the token usually maps the market expectation for the level of recovery that might be possible. When Circle, the issuers of USDC, lost track of $3.3bn it had deposited in the insolvent Silicon Valley Bank, USDC depegged by about 10%. Given that a substantial amount of Dai used to be backed by USDC, Dai also depegged by slightly less than 10%. However, depositors of Silicon Valley Bank had to wait for the weekend to pass to understand how much their Silicon Valley Bank Dollars were worth. The fact that a deposit is ‘tokenized’ provides much quicker feedback on the market sentiment around a specific protocol relative to a black box bank.
Secondly, provided a stablecoin is solvent, a pure liquidity redemption event can eventually theoretically be resolved, even if the immediate amount of collateral available to redeem on 0 notice is reduced through illiquidity. During a stablecoin wind down by depositors, the amount of liquidity that’s withdrawable on short notice changes throughout the withdrawal process from start to 0. When you map the amount of immediate liquidity on notice with the amount the stablecoin has withdrawn, you can draw what’s called a redemption curve.
Banks have different redemption curves for different people. When a depositor whose assets are under a government guaranteed limit tries to withdraw during a bank run, their redemption curve will look closest to the red line above. Although the underlying reality may in fact be the blue line, taxpayers will chip in for the difference through deposit insurance. 
Large depositors will experience curved or discontinuous (stepped) redemption curves if they try to withdraw all at once. Cypriot bank depositors discovered, in 2013, that the government had shifted their redemption curve down in parallel. 
Stablecoins do not generally differentiate between users and therefore users experience the same redemption curve all at once. In practice they are more likely to be stepped functions than curves, as collateral is more likely to be pulled from assets in order of liquidity than across all assets. This theoretically rewards fast movers relative to users who withdraw later. New designs for redemption curves, such as in the Gyroscope protocol, propose intentionally reducing the amount of collateral depositors can withdraw in a short period of time to disincentivize a rush to the exits. 

### 3. Match assets against liabilities
The method of aligning the properties of a liability with those of an asset is known as asset-liability management. When done correctly, it permits secure investment of assets to yield a return while minimizing the risk of a liquidity crisis.
Traditional banks must rely on guesswork and behavioral analysis to approximate their liability maturity profiles. They have several tools at their disposal to modulate these profiles. For instance, when a bank issues a certificate of deposit (CD), the deposits are typically locked in for a specific time period. This assures the bank that the deposit will stay put for the agreed-upon duration. The trade-off is that it usually necessitates a higher cost, reflected in the savings rates on the CD.
In contrast, decentralized stablecoins can continuously monitor the behavior of their users on-chain. By studying these on-chain transfers, stablecoin communities can estimate their liability maturities more accurately compared to traditional banks.
To model a bank or stablecoin's liquidity profile, you could classify each investment by its speed of conversion to cash without significant value loss. For instance, U.S. treasury bonds can be sold within a day, whereas selling a home mortgage might take a year or more.
Comparing the liquidity of a set of assets against the liquidity of liabilities can demonstrate the available liquidity at various maturity ranges. For example, with real data from MakerDAO, it appears that most liabilities (i.e., stablecoins issued) are estimated to be fixed for a year or longer, while most assets can be liquidated within a day. Therefore, MakerDAO's liquidity model is heavily skewed towards greater liquidity, which might come at the expense of return.

## Profitability drivers
Provided the above constraints are satisfied, the below equation breaks down the drivers of how a balance sheet can work to find an equilibrium point where revenues are maximized and expenses are minimized. These forces interact with the market – the amount of interest income is constrained by competition for investable opportunities, for example. In the drivers below we focus exclusively on execution drivers on the part of the issuing balance sheet, as these are the variables that are actually hardest to manage for a governance-driven decentralized stablecoin. To wit, they’re often hard to manage even for centralized companies.
The profitability of a balance sheet is fundamentally down to:
Increase interest income
Decrease interest expense

### Increase interest income
How well are you able to generate a return on your portfolio of invested assets? Interest income is the total amount of interest an asset generates in a period. Earning assets is the value of the assets that are earning interest. For instance, just holding cash usually does not generate interest income, but extending a loan to a homebuyer does. 
Interest income over earning assets shows, on a total level, what the effective interest rate the bank is able to generate from the assets that it’s investing. All else being equal, banks and stablecoins should prefer assets with a higher yield than assets with a lower yield. The confounding variables are that higher yields are often accompanied by higher risk or greater illiquidity. 
MakerDAO has two fundamental asset types: crypto collateral for loans and real-world assets. Increasing the interest income over earning assets means either increasing stability fees on crypto lending, increasing interest income on real-world assets or both. Indeed, by increasing stability fees (when they were lower than the prevailing risk-free rate) and deploying assets into US treasuries at a time when short-term rates exceeded 4-5% significantly increased interest income over earning assets.

### Decrease interest expense
How cheaply are you able to source capital to feed your portfolio of assets? Interest expense is the total interest cost required to raise all of the capital needed to run the bank. When it’s divided by the amount of earning assets, you can see the effective ‘cost of goods’ of a portfolio of productive assets
Most stablecoins have near-zero interest expense, as the overwhelming majority do not pay any interest or savings rate. However, there is a credible theory that this is not a long-term stable equilibrium, as the benefits of crypto infrastructure accrue when most of the rent captured by intermediaries can be unbundled and returned to users.
Banks have to compete amongst themselves with variables including the savings rate offered on deposits to customers. When two banks are hard to differentiate and differ by the savings rate, the expectation is that the higher rate will attract more customers. The interest expense therefore represents the cost of ‘growing’ the balance sheet with new users or depositors. It’s also possible to offset interest expense with non-monetary benefits to deposits or to holding a stablecoin. As mentioned above, if a product offers sufficiently compelling reasons to use a product over a competing bank, the user may be acquired without having to pay an actual monetary cost for their deposit. 
For instance, Revolut’s entire strategy is around outcompeting on non-monetary benefits relative to incumbent banks, with better user experiences, newer technology and broader integrations with services Revolut customers are more likely to favor. This should allow them to get away with paying a lower interest expense compared to HSBC, for example. Another example is USDT, which pays 0% yield and is notoriously tricky to redeem for fiat (minimums of $100,000 and 0.1% fees), but is still the world’s largest and most used stablecoin. 

## Efficiency drivers
Efficiency refers to how much of the balance sheet can a stablecoin effectively monetize and at what cost. It is also a representation of what the impact of the liquidity and solvency constraints are on the balance sheet. The lower the earning assets over total assets ratio is, the more likely it is that a balance sheet will have liquidity available for redemptions. However, this will lower the balance sheet’s net interest income since a lower proportion of assets will be earning fees. 
Provisions for credit losses are a representation of how well the decentralized stablecoin has been able to select for risk. Crypto-collateral loans can also be exposed to bad debt, if liquidations fail to remove collateral for example.
Finally any non-interest income that the balance sheet can generate will help diversify exposure to rate sensitivity and provide new revenue streams. Banks rely on fees or trading and advisory businesses to generate non-interest revenue, stablecoins can functionally replicate some of these but the overwhelming majority of revenues can and probably should be from interest alone.

### Increase earning assets over total assets
How many of your assets are you able to put to work? Earning assets are the percentage of a bank’s assets that are generating an interest earning. This is fundamentally a liquidity versus return optimization. 
Balance sheets with more liquid cash on hand are better able to meet the demands of their depositors. However, in doing so they decrease the amount of assets that are earning an interest rate. For the same level of earning assets over total assets, in order to increase the NIM, one would have to take on more risk to earn more interest income (potentially compromising solvency) or lower interest expense (potentially compromising market attractiveness). This is a delicate balance to optimize for, as the relation can be flipped on its head without contradiction, i.e. for the same level of net income, having more liquid cash on hand is safer than having less.
The recommendations we made to MakerDAO throughout 2022 and 2023 essentially amounted to allocate a greater proportion of its total assets into earning assets, largely by decreasing the proportion of USDC held. This USDC was in turn invested in a variety of public credit and private credit vehicles through off-chain structures. Just by increasing the percentage of assets that the balance sheet was able to ‘put to work’ significantly expanded the ability of the protocol to earn a positive return.

### Increase net interest income
Increasing the NIM and increasing the proportion of earning assets over total assets has the effect of increasing the net interest income. Effectively, the net ‘gross margin’ that a balance sheet is able to generate over its earning assets multiplied by the amount of earning assets.
The most important rate limiter to growth for both banks and decentralized stablecoins is the size of the balance sheet, and therefore the amount of earning assets the balance sheet is able to allocate from the total. The size of the balance sheet is determined by the attractiveness of the product for depositors, in the case of a bank, or stablecoin users, in the case of a decentralized stablecoin.

### Increase non-interest income
How much revenue can you generate from other sources in relation to interest income? All other sources of income as a percentage of total assets, as a measure of adjacent or ancillary business activities. Many banks generate substantial amounts of revenue from trading activities, fees or advisory, which do not have a direct relationship to the size of the assets of the bank.
Non-interest income has useful diversification benefits. When interest rate conditions are low, fees provide an important and uncorrelated source of income for many banks.
Stablecoins have various levers for increasing non-interest income. MakerDAO, for instance, has liquidation fees. Whenever crypto collateral is liquidated through an auction, the protocol repossesses 13% of the value of the collateral for its surplus automatically. In volatile periods, this provides a substantial source of revenues to the protocol. Furthermore, on peg-stability vaults, such as USDC:DAI that exchange stablecoins against one another 1:1, the protocol can charge a small fee for mints and withdrawals, similar to a one-time fee for using the liquidity facility. 

### Decrease and mitigate against credit losses
How many losses will the assets incur? Banks are regularly exposed to the possibility of losses through loan defaults or asset value impairments. Banks can build a reserve to cushion against these losses by expensing a provision for expected losses in a period. Losses are usually incurred through non-repayment of loans issued. 
Stablecoins are similarly exposed to credit losses through bad debt accruals on crypto collateral (i.e. debt that can never be profitably repaid), losses on real-world collateral or through tail-risk events such as a centralized stablecoin losing track of $3.3bn worth of its deposits or a hostile government seizing collateral and writing down the value of those vaults to 0 instantly.
Mitigation is a combination of diversification (of credit risks, jurisdictions and counterparties) and intelligent structuring or on-chain design. However, given that decentralized stablecoins tend to move slowly on account of intricate governance processes, the best mitigant to potential losses for a stablecoin is holding a large enough surplus to cushion against potential losses. 

### Decrease operating expenses
How much overhead will the bank incur to run its balance sheet? 
Blockchain protocols are, in theory, able to replace previously complicated changes in opaque and centralized databases with simple open-source function calls on smart-contracts running on public blockchains. In other words, just rails, or infrastructure, for other agents and counterparties to transact with each other, rather than a counterparty itself. This means that over time, they should be able to return the overwhelming majority of return on assets to the users of the stablecoin in the pursuit of a better product. 
Banks, on the other hand, are obligated to maintain a large amount of fixed costs to keep the lights on. New fixed costs tend to be required to expand the size of the balance sheet, as more risk underwriting is required for new investments and more compliance overhead is required for new deposits. 
The performance of a balance sheet in relation to its fixed costs is known as the efficiency ratio (i.e. cost over revenue, so lower efficiency ratios are better). Theoretically, a protocol’s efficiency ratio should decline over time, as the balance sheet grows, as either more balance sheet size can be supported with the same amount of expenses, or expenses are set to decline over time as more and more of the protocol is automated at the smart contract level, and can therefore ‘ossify’.

## Leverage drivers
Finally, when profitability and efficiency are combined, the return to the balance sheet surplus is measured as how much leverage over the equity is taken. The surplus’ primary stabilizing role is to cover the balance sheet for potential losses. Banks are typically regulated to how much leverage they can take with some amount of capital. In other words, all else being equal, for $10 in capital, a bank would not be allowed by regulators to take more than $90 in deposits unless they found a way to increase their capital, either by issuing new equity or by increasing it through profits. 
Decentralized stablecoins do not have such restrictions and to some extent, this is reasonable provided the level of risk in the balance sheet is adequate.

### Increase leverage multiple
How much does debt represent in amount over equity on the balance sheet? The more levered the balance sheet, the riskier the exposure. However, it also magnifies the return to the equity layer. The theory is that a higher degree of automation can allow protocols to function at higher levels of leverage relative to an ordinary bank. However, there are risks associated with the investments in assets that no amount of automation can mitigate. The question token holders need to resolve, therefore, is what level of risk is appropriate for a decentralized stablecoin at higher turns of leverage, or whether a larger equity buffer might be required to sustain existing levels of risk.

## Simplified side-by-side financial statements

The above are simplified financial statements and relative-basis financial ratios for FakeBank, a well-regarded institution favored by the US tech industry, and Maker, a decentralized stablecoin. One version of Maker's statements is from the end of 2022 and the other projects the next twelve months, reflecting changes due to maturing investment programs.
For Maker, non-interest income primarily comes from revenue generated by the automatic closing of crypto-loans. In contrast, FakeBank's non-interest income might include transaction fees, advisory fees, or trading profits.
A significant distinction is the level of transparency: Maker is built on a public blockchain and is auditable in real-time by anyone with internet access. In contrast, FakeBank's operations can't be independently verified in this manner. If significant changes occurred at FakeBank between December 31, 2022, and the present, they wouldn't be immediately discernible from a static balance sheet. Furthermore, you would have to assume the balance sheet was accurate to begin with.
The two notable columns to compare are the regular bank for 2022 and the NTM statements for MakerDAO for May 2023. On the whole, for similar levels of net interest margin, the two substantial differentiating factors are lower operating expenses and higher leverage. 
Similar levels of net interest margin: Both FakeBank and MakerDAO appear to be capable of targeting a similar level of top-line profitability by borrowing short and lending long.
Lower operating expenses: To maintain this borrowing and lending activity, FakeBank requires a much larger level of operating expenses, largely concentrated in line items such as people to serve in branch offices, cost of real estate to put people in or the running expenses of computer servers to run outdated bank software. MakerDAO is a smart contract protocol, which can abstract all of this organizational complexity into simple functions that allocate value. This results in a notably lower level of ongoing operating expenses. Furthermore, to some degree MakerDAO’s operating expenses and grants have as many features of research & development as they do of ongoing costs.
Higher leverage: FakeBank is limited by regulation to the amount of deposits it can borrow from customers in relation to its equity. A smart contract protocol, however, does not have the same limitations and can offer much higher degrees of balance sheet leverage without necessarily undertaking higher levels of risk. MakerDAO’s next 12mo leverage is 7x higher than FakeBank for a few reasons:
Crypto-loans are overcollateralized and reduce the amount of capital necessary to buffer against potential losses
The degree to which MakerDAO is exposed to duration or credit risk is lower than at FakeBank, reducing its requirement to hold capital to buffer against potential losses

## Conclusions and further developments
Decentralized stablecoins are not banks. However, banks can offer useful lessons that can be applicable to the management and operations of a decentralized stablecoin. 
The most important lessons are:
Manage liquidity and solvency as primordial constraints
Match assets against liabilities
Make a product people want to use
The key differentiator decentralized stablecoins offer in relation to banks is higher utility, as deposits are effectively tokenized and can be transferred permissionlessly. 
Following the above three rules, decentralized stablecoins can also optimize on the two areas where they are the most unlike banks, lower operating expenses and higher leverage through overcollateralization and automated risk-management at the smart contract level.
We leave open a few questions to the reader and for future editions, notably around selection of leverage and expectation for return:
What level of risk is appropriate for a decentralized stablecoin at higher leverage multiples? -> i.e. what level of return on assets should decentralized stablecoins target?
Is it sufficient to rely on short-term treasuries and similar low-risk instruments?
Can these balance sheets take longer duration risk?
What level of surplus is suitable for the level of risk exposure today? -> i.e. what leverage multiple should decentralized stablecoins target?
Keeping the balance sheet equal in composition, should token holders require higher levels of surplus to mitigate risk?

## About Steakhouse Financial
Steakhouse Financial is a boutique crypto-native advisory firm specialized in stablecoins of various types and backings.
If you are a stablecoin builder -> hopefully these principles can be useful to you! If you want to talk more about them, please reach out to us for a chat
If you are a regulator -> hopefully this article will help you understand the benefits of decentralized stablecoins and their differences with respect to banks. If you want to understand them a bit deeper, please reach out to us for a chat
If you are a crypto user -> hopefully these principles will be helpful to help you navigate a wide landscape of stablecoins. If you want to provide thoughts or comments, please reach out to us for a chat
If you are a steak enthusiast -> please reach out to us no matter what
chefs@steakhouse.financial

Follow @SteakhouseFi for more grilling tips
Steakhouse.financial
dune.com/steakhouse
Disclaimers: steakhouse.financial/disclaimers