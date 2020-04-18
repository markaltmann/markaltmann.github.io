---
title: "Portfolio Rebalancing"
excerpt: "Cash Flow Rebalancing of your Portfolio with Google Spreadsheets"
layout: single
author_profile: true
read_time: true
share: true
related: true
# toc: true
# toc_label: "table of contents"
# toc_icon: "cog"
categories:
  - Blog
tags:
  - finance
  - portfolio
classes: wide
---
## Portfolio Rebalancing

When you have your asset portfolio in your brokerage depot, you would probably want to rebalance your portfolio once in a while. The motivation behind that is to uphold your risk distribution in your portfolio and follow anti-cyclical investment decisions.  
The rationale is that growth equals out over long terms.

As a good general overview on Portfolio Rebalancing on [justetf.com](https://www.justetf.com/de-en/academy/what-is-portfolio-rebalancing.html).

Many brokers do offer portfolio rebalancing, however that usually comes at a price. Couldn't be so hard, i thought myself and created a Google Spreadsheet...

### Rebalancing Approaches

There are 2 well known approaches to portfolio rebalancing:

1. Classic Rebalancing
2. Cash Flow Rebalancing

The main difference is, that you only buy and not sell any assets in the cash flow approach. The classic rebalancing approach works with selling/buying at the same time to reach the target distribution. Check out the following picture for explanation:

![Portfolio Rebalancing](/assets/images/cash-flow-rebalancing-en.jpg){:class="img-responsive"}

### Preparation

The first thing we need is a kind of export of your portfolio with all the necessary data to make the calculation. We need the assets, current price, amount, savings rate, item distribution etc...

![Portfolio Import](/assets/images/portfolio_import.png){:class="img-responsive"}

Use the following spreadsheet as a template: <https://docs.google.com/spreadsheets/d/1Lc1U3VXlsYPMxnCoAKxJSRJ92Z6olWBUA3U1ve67kxA/edit?usp=sharing>

The usage is pretty simple:

1. Import your portfolio balance as a CSV and import it into the "import" sheet:
    - ![Portfolio Import Finalize](/assets/images/portfolio_import_finalize.png){:class="img-responsive"}
2. Set the savings rate in the first sheet
3. Distribute savings rate among the assets you want
4. Finished!

### Calculation

Now that we have imported the portfolio and pre-configured our desired distribution, we can go to the rebalancing sheet.  
There you will then see, in a cash flow rebalancing, how much from what asset you would need to buy in order to achieve your target distribution:

![Portfolio Rebalancing](/assets/images/portfolio_rebalancing.png){:class="img-responsive"}

The sheet can also easily be adapted to calculate the classic rebalancing, which includes also selling assets.

---

Hope that was helpful. Feedback welcome.
