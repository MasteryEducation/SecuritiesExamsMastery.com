---
canonical: "https://securitiesexamsmastery.com/7/4/4/2"

title: "Bond Pricing: Clean Price vs. Dirty Price Explained"
description: "Explore the differences between clean and dirty prices in bond trading, understand their calculation, importance in transactions, and market practices."
linkTitle: "4.4.2 Clean Price vs. Dirty Price"
categories:
- Fixed Income Securities
- Bond Markets
- Investment Strategies
tags:
- Bonds
- Clean Price
- Dirty Price
- Accrued Interest
- Bond Pricing
date: 2024-11-23
type: docs
nav_weight: 44200
license: "© 2024 Tokenizer Inc. CC BY-NC-SA 4.0"

---

## 4.4.2 Clean Price vs. Dirty Price

When dealing with bonds, understanding the distinction between clean price and dirty price is crucial for both investors and finance professionals. These concepts are fundamental to bond pricing and trading, and they play a significant role in determining the amount paid or received during bond transactions. This section will provide a comprehensive examination of clean and dirty prices, their calculation, and their importance in the bond market.

### Clean Price

#### Definition and Usage

The **clean price** of a bond is the quoted price that excludes any accrued interest. It is the price that reflects the bond's principal value and the present value of its future coupon payments. This price is often used in financial reporting and price quotations, providing a clear view of the bond's value without the influence of interest that has accumulated since the last coupon payment.

- **Financial Reporting:** Clean prices are used to present bond prices in financial statements, offering a consistent basis for comparison.
- **Price Quotations:** In many markets, bond prices are quoted as clean prices, making it easier for investors to compare bonds without considering accrued interest.

#### Calculation

The clean price is determined by the present value of the bond's future cash flows, which include the principal repayment at maturity and the periodic coupon payments. The formula for calculating the clean price is:

{{< katex >}}
Clean\ Price = \sum_{t=1}^{n} \frac{C}{(1+y)^t} + \frac{M}{(1+y)^n}
{{< /katex >}}

Where:
- \\( C \\) = Coupon payment
- \\( y \\) = Yield to maturity
- \\( t \\) = Time period
- \\( M \\) = Maturity value
- \\( n \\) = Number of periods

### Dirty Price (Full Price or Invoice Price)

#### Definition and Usage

The **dirty price**, also known as the full price or invoice price, is the total price paid for a bond, including accrued interest. It represents the actual amount that a buyer pays to a seller on the settlement date. The dirty price is crucial for transactions as it ensures that the seller is compensated for the interest earned since the last coupon payment.

- **Total Outlay for Buyers:** Buyers need to be aware of the dirty price to understand the total financial commitment required for purchasing a bond.
- **Compensation for Sellers:** Sellers receive the dirty price, which includes compensation for the interest accrued up to the transaction date.

#### Calculation

The dirty price is calculated by adding the accrued interest to the clean price:

{{< katex >}}
Dirty\ Price = Clean\ Price + Accrued\ Interest
{{< /katex >}}

**Accrued Interest Calculation:**

Accrued interest is the interest that has accumulated on a bond since the last coupon payment. It is calculated as follows:

{{< katex >}}
Accrued\ Interest = \frac{C \times (Days\ Since\ Last\ Coupon)}{Days\ in\ Coupon\ Period}
{{< /katex >}}

Where:
- \\( C \\) = Coupon payment
- \\( Days\ Since\ Last\ Coupon \\) = Number of days since the last coupon payment
- \\( Days\ in\ Coupon\ Period \\) = Total number of days in the coupon period

### Importance in Transactions

Understanding the distinction between clean and dirty prices is essential for anyone involved in bond transactions. Here’s why these concepts matter:

- **Pricing Transparency:** Clean prices provide a clear view of the bond's intrinsic value, while dirty prices reflect the actual transaction cost.
- **Financial Planning:** Investors can make informed decisions about their financial commitments and returns by understanding both prices.
- **Market Comparisons:** Clean prices allow for easier comparison between bonds, while dirty prices ensure fair compensation in transactions.

### Market Practices

In the bond market, the practice of quoting prices can vary:

- **Clean Price Quotation:** In markets like the U.S., bond prices are typically quoted as clean prices. This practice simplifies the comparison of bond prices by excluding the variable of accrued interest.
- **Dirty Price Quotation:** Some markets might quote dirty prices, which include accrued interest, providing a complete picture of the transaction cost.

### Practical Example

Consider a bond with the following characteristics:

- **Clean Price:** $980
- **Coupon Payment:** $20
- **Days Since Last Coupon:** 30
- **Days in Coupon Period:** 180

**Accrued Interest Calculation:**

{{< katex >}}
Accrued\ Interest = \frac{20 \times 30}{180} = \$3.33
{{< /katex >}}

**Dirty Price Calculation:**

{{< katex >}}
Dirty\ Price = \$980 + \$3.33 = \$983.33
{{< /katex >}}

In this example, the dirty price of $983.33 is the amount the buyer pays on the settlement date, which includes the clean price of the bond and the accrued interest of $3.33.

### Glossary

- **Clean Price:** The price of a bond excluding accrued interest.
- **Dirty Price (Full Price):** The total price including accrued interest; the amount paid by the buyer.

### References

- Investopedia – [Clean Price vs. Dirty Price](https://www.investopedia.com/terms/c/cleanprice.asp)
- Financial Industry Regulatory Authority (FINRA) – [Understanding Bond Prices](https://www.finra.org/investors/insights/understanding-bonds)

---

## Bonds and Fixed Income Securities Quiz: Clean Price vs. Dirty Price

{{< quizdown >}}

### What does the clean price of a bond exclude?

- [x] Accrued Interest
- [ ] Coupon Payments
- [ ] Principal Amount
- [ ] Market Yield

> **Explanation:** The clean price excludes accrued interest, representing the bond's value without considering interest accumulated since the last coupon payment.

### How is the dirty price of a bond calculated?

- [ ] Clean Price minus Accrued Interest
- [x] Clean Price plus Accrued Interest
- [ ] Coupon Payment plus Principal
- [ ] Principal minus Market Yield

> **Explanation:** The dirty price is calculated by adding accrued interest to the clean price, reflecting the total amount paid by the buyer.

### In which market are bond prices typically quoted as clean prices?

- [x] U.S. Bond Markets
- [ ] European Bond Markets
- [ ] Asian Bond Markets
- [ ] Emerging Markets

> **Explanation:** In the U.S., bond prices are generally quoted as clean prices, excluding accrued interest for clarity in pricing.

### What is the primary purpose of quoting bond prices as clean prices?

- [ ] To include accrued interest
- [ ] To reflect the total transaction cost
- [x] To provide a clear view of the bond's intrinsic value
- [ ] To ensure compensation for sellers

> **Explanation:** Clean prices provide a clear view of the bond's intrinsic value by excluding accrued interest, facilitating easier comparison between bonds.

### What is the accrued interest for a bond with a $50 coupon, 45 days since the last coupon, and a 180-day coupon period?

- [ ] $10
- [x] $12.50
- [ ] $15
- [ ] $20

> **Explanation:** Accrued interest is calculated as \(\frac{50 \times 45}{180} = \$12.50\).

### Why is the dirty price important for sellers?

- [ ] It excludes accrued interest
- [x] It ensures compensation for accrued interest
- [ ] It reflects the bond's market yield
- [ ] It simplifies financial reporting

> **Explanation:** Sellers receive the dirty price, which includes accrued interest, ensuring they are compensated for the interest earned since the last coupon payment.

### What is the clean price of a bond if the dirty price is $1,020 and the accrued interest is $20?

- [x] $1,000
- [ ] $1,040
- [ ] $1,010
- [ ] $980

> **Explanation:** The clean price is calculated by subtracting accrued interest from the dirty price: \(1,020 - 20 = \$1,000\).

### Which of the following best describes the dirty price?

- [ ] The quoted price excluding accrued interest
- [x] The total price including accrued interest
- [ ] The price based on the bond's market yield
- [ ] The price excluding coupon payments

> **Explanation:** The dirty price includes accrued interest, representing the total amount paid by the buyer.

### How does accrued interest affect the bond's dirty price?

- [x] It increases the dirty price
- [ ] It decreases the dirty price
- [ ] It has no effect on the dirty price
- [ ] It only affects the clean price

> **Explanation:** Accrued interest is added to the clean price to calculate the dirty price, increasing the total amount paid.

### What is the dirty price of a bond with a clean price of $950 and accrued interest of $15?

- [ ] $935
- [ ] $945
- [x] $965
- [ ] $975

> **Explanation:** The dirty price is calculated by adding accrued interest to the clean price: \(950 + 15 = \$965\).

{{< /quizdown >}}

---

This comprehensive section provides an in-depth understanding of clean and dirty prices, essential for anyone involved in bond trading and investment. By mastering these concepts, you can make informed decisions and optimize your bond investment strategies.
