# Who Holds U.S. Federal Debt: A Sourced Breakdown

Compiled 2026-10-02 from primary sources: Treasury Fiscal Data, Treasury TIC, Federal Reserve (H.4.1, H.8, Z.1, Combined Quarterly Financial Report), FFIEC/FDIC call reports, the FDIC Quarterly Banking Profile, and SEC 10-Q filings.

## How to read this report

- **Units.** Billions of U.S. dollars unless noted. Figures are rounded, so components may not add exactly to totals.
- **As-of dates.** Each table states its own as-of date. Sources publish on different schedules, so dates differ between tables. Data from different dates are never combined in one figure.
- **No estimates.** Where a source does not publish a figure, it is marked **not disclosed**. Some figures are marked *calculated*. These are plain arithmetic on the cited primary data: sums, differences, shares, and amount-weighted averages over Treasury's security-level file. Nothing is modelled, interpolated or estimated.
- **Valuation bases differ.** Treasury and H.4.1 report par or face value. Z.1 and TIC report market value. Call reports, 10-Qs and the Fed's financial report give both amortized cost and fair value. The basis is stated wherever it matters.

### Data vintages used

| Source | Latest period used | Release / retrieval |
|---|---|---|
| Treasury, Debt to the Penny | 2026-09-30 | daily dataset |
| Treasury, Monthly Statement of the Public Debt (MSPD) | 2026-08-31 | latest month published (Sept-30 MSPD not yet out) |
| Treasury, Monthly Treasury Statement (MTS) Tables 6-D and 8 | 2026-08-31 | latest month published |
| Treasury Bulletin, OFS-2 | detail 2026-03-31 (June 2026 has totals only) | Fiscal Data record date 2026-09-30 |
| Federal Reserve Z.1, table L.210 | 2026-06-30 (2026:Q2) | released 2026-09-11 |
| Federal Reserve H.4.1 | Wednesday 2026-09-30 | released 2026-10-01 |
| Federal Reserve H.8 | week ending 2026-09-16 (not seasonally adjusted) | released 2026-09-25 |
| Federal Reserve Banks Combined Quarterly Financial Report | 2026-06-30 | report file dated 2026-08-28 |
| Treasury TIC, SLT Tables 3 and 5 | July 2026 | latest month published as of 2026-10-02 |
| Call reports (FFIEC 031/041/051), bulk data | 2026-06-30 | FFIEC CDR data as processed 2026-09-15 |
| FDIC Quarterly Banking Profile | 2026 Q2 | Q2 2026 edition |
| SEC Form 10-Q, 12 bank holding companies | 2026-06-30 | filed 2026-07-28 to 2026-08-07 |

---

## 1. Total and structure

### 1.1 Total public debt outstanding (as of 2026-09-30, the last day of fiscal year 2026)

| Component | 2026-09-30 ($B) | Share | 2025-09-30 ($B) | Change ($B) |
|---|--:|--:|--:|--:|
| Total public debt outstanding | 40,171.8 | 100.0% | 37,637.6 | +2,534.3 |
| Debt held by the public | 32,425.0 | 80.7% | 30,277.8 | +2,147.2 |
| Intragovernmental holdings | 7,746.8 | 19.3% | 7,359.8 | +387.0 |

Source: [Treasury Fiscal Data, Debt to the Penny](https://fiscaldata.treasury.gov/datasets/debt-to-the-penny/debt-to-the-penny) ([API](https://api.fiscaldata.treasury.gov/services/api/fiscal_service/v2/accounting/od/debt_to_penny?filter=record_date:in:(2025-09-30,2026-09-30))).

### 1.2 Composition by security type and holder class (as of 2026-08-31)

| Security type | Held by public ($B) | Intragovernmental ($B) | Total ($B) |
|---|--:|--:|--:|
| Marketable: Bills | 7,247.9 | 0.2 | 7,248.1 |
| Marketable: Notes | 16,214.7 | 3.7 | 16,218.4 |
| Marketable: Bonds | 5,512.7 | 12.6 | 5,525.3 |
| Marketable: Treasury Inflation-Protected Securities | 2,152.0 | 0.7 | 2,152.7 |
| Marketable: Floating Rate Notes | 679.9 | 0.1 | 680.0 |
| Marketable: Federal Financing Bank | 0.0 | 3.6 | 3.6 |
| **Total Marketable** | 31,807.1 | 20.9 | 31,828.0 |
| Nonmarketable: Domestic Series | 10.7 | 0.0 | 10.7 |
| Nonmarketable: State and Local Government Series | 78.9 | 0.0 | 78.9 |
| Nonmarketable: United States Savings Securities | 146.9 | 0.0 | 146.9 |
| Nonmarketable: Government Account Series | 366.4 | 7,739.8 | 8,106.2 |
| Nonmarketable: Other | 4.9 | 0.0 | 4.9 |
| **Total Nonmarketable** | 607.8 | 7,739.8 | 8,347.6 |
| **Total Public Debt Outstanding** | 32,415.0 | 7,760.7 | 40,175.6 |

Source: [Treasury Fiscal Data, MSPD Table I](https://fiscaldata.treasury.gov/datasets/monthly-statement-public-debt/summary-of-treasury-securities-outstanding) (endpoint `v1/debt/mspd/mspd_table_1`).

Almost all intragovernmental holdings ($7,739.8B of $7,760.7B) are non-marketable Government Account Series (GAS) securities. These are special-issue securities that federal trust funds and other accounts hold at Treasury. They are not traded in the market.

### 1.3 Largest intragovernmental holders (as of 2026-08-31)

| # | Account | MTS classification | Holdings 2026-08-31 ($B) | Share of all federal-account holdings | MTS line |
|--:|---|---|--:|--:|---|
| 1 | Federal Old-Age and Survivors Insurance Trust Fund (Social Security) | Trust fund | 2,209.4 | 28.6% | 6D l.86 |
| 2 | Military Retirement Fund | Trust fund | 2,125.5 | 27.5% | 6D l.76 |
| 3 | Civil Service Retirement and Disability Fund | Trust fund | 1,146.2 | 14.8% | 6D l.82 |
| 4 | Uniformed Services Retiree Health Care Fund | Federal fund | 507.6 | 6.6% | 6D l.27 |
| 5 | Federal Hospital Insurance Trust Fund (Medicare Part A) | Trust fund | 260.5 | 3.4% | Table 8 |
| 6 | Federal Disability Insurance Trust Fund (Social Security) | Trust fund | 257.6 | 3.3% | 6D l.87 |
| 7 | Federal Housing Administration Fund | Federal fund | 195.1 | 2.5% | 6D l.11 |
| 8 | Federal Supplementary Medical Insurance Trust Fund (Medicare B/D) | Trust fund | 186.3 | 2.4% | 6D l.55 |
| 9 | FDIC Deposit Insurance Fund | Federal fund | 139.7 | 1.8% | 6D l.33 |
| 10 | Unemployment Trust Fund | Trust fund | 93.9 | 1.2% | 6D l.60 |
| 11 | Employees Life Insurance Fund (FEGLI) | Trust fund | 60.4 | 0.8% | 6D l.83 |
| 12 | Highway Trust Fund | Trust fund | 49.9 | 0.6% | 6D l.67 |
| 13 | Airport and Airway Trust Fund | Trust fund | 22.7 | 0.3% | 6D l.66 |
| 14 | Foreign Service Retirement and Disability Fund | Trust fund | 22.2 | 0.3% | 6D l.63 |
| | **All federal accounts (MTS Table 6 Schedule D grand total)** | | **7,735.7** | 100.0% | 6D l.99 |

Sources: [Treasury Fiscal Data, Monthly Treasury Statement](https://fiscaldata.treasury.gov/datasets/monthly-treasury-statement/): Table 6 Schedule D, "Investments of Federal Government Accounts in Federal Securities" (`v1/accounting/mts/mts_table_6d`, line numbers shown), and Table 8, "Trust Fund Impact on Budget Results and Investment Holdings" (`v1/accounting/mts/mts_table_8`).

Notes:
- **Medicare Part A (row 5).** Table 6-D does not show the Federal Hospital Insurance Trust Fund as its own line; it falls inside "Health and Human Services: Other" ($265.4B). Its $260.5B figure is therefore taken from MTS Table 8.
- **Federal funds (rows 4, 7 and 9).** The MTS classifies these accounts as federal funds, not trust funds. They are listed because they are among the largest intragovernmental holders.
- **Totals.** The MTS 6-D grand total ($7,735.7B) and the MSPD intragovernmental total ($7,760.7B) are different Treasury presentations with different scope. Both are shown as published; neither is adjusted.

---

## 2. Holders of debt held by the public

### 2.1 Holders of marketable Treasury securities, by sector (as of 2026-06-30)

| Holder (Z.1 L.210 sector) | 2026-06-30 ($B) | Share of identified holdings | 2025-06-30 ($B) | Change ($B) |
|---|--:|--:|--:|--:|
| Rest of the world (foreign holders) | 9,269.2 | 31.9% | 9,094.0 | +175.2 |
| Federal Reserve (market value) | 4,082.7 | 14.1% | 3,811.0 | +271.7 |
| Money market funds † | 3,281.6 | 11.3% | 2,614.0 | +667.5 |
| Households and nonprofits (Fed: "largely residual") | 2,831.1 | 9.8% | 2,642.3 | +188.9 |
| U.S.-chartered depository institutions (US banks & thrifts) | 1,799.1 | 6.2% | 1,637.1 | +162.0 |
| Mutual funds | 1,741.2 | 6.0% | 1,541.4 | +199.9 |
| State and local governments (ex-SLGS) | 1,647.6 | 5.7% | 1,573.6 | +74.0 |
| Pension funds: total | 1,175.1 | 4.1% | 1,044.5 | +130.7 |
| &nbsp;&nbsp;Private pension funds | 590.2 | 2.0% | 532.1 | +58.2 |
| &nbsp;&nbsp;State & local govt. DB pension funds | 561.6 | 1.9% | 490.8 | +70.8 |
| &nbsp;&nbsp;Federal govt. pension funds (incl. TSP F Fund) | 23.3 | 0.1% | 21.6 | +1.7 |
| Exchange-traded funds | 807.6 | 2.8% | 635.7 | +171.9 |
| Insurers: total | 609.4 | 2.1% | 535.5 | +73.9 |
| &nbsp;&nbsp;Property-casualty insurers | 380.2 | 1.3% | 341.0 | +39.2 |
| &nbsp;&nbsp;Life insurers | 229.2 | 0.8% | 194.5 | +34.7 |
| Broker-dealers (net) | 566.7 | 2.0% | 513.2 | +53.5 |
| Government-sponsored enterprises | 274.2 | 0.9% | 257.9 | +16.2 |
| Nonfinancial corporate business | 218.6 | 0.8% | 226.5 | -8.0 |
| Foreign banking offices in the US | 140.0 | 0.5% | 122.3 | +17.7 |
| Holding companies | 129.4 | 0.4% | 131.0 | -1.6 |
| Domestic hedge funds (net of shorts) | 123.5 | 0.4% | 106.2 | +17.3 |
| Central clearing counterparties † | 99.3 | 0.3% | 86.3 | +13.0 |
| Nonfinancial noncorporate business (all US govt securities) | 94.8 | 0.3% | 87.7 | +7.1 |
| Credit unions | 73.6 | 0.3% | 64.6 | +9.0 |
| Banks in US-affiliated areas | 28.2 | 0.1% | 24.9 | +3.2 |
| ABS issuers † | 18.6 | 0.1% | 20.4 | -1.8 |
| Closed-end funds | 2.0 | 0.0% | 2.0 | +0.1 |
| **All identified holders (L.210 line 4)** | **29,013.6** | **100.0%** | 26,772.3 | +2,241.4 |
| Memo: marketable Treasury securities outstanding, liability side (line 1) | 30,878.3 | | 28,518.3 | |
| Memo: instrument discrepancy (line 46) | 1,864.7 | | 1,746.1 | |

Source: [Federal Reserve, Financial Accounts of the United States (Z.1), table L.210 "Treasury Securities", 2026:Q2 release of 2026-09-11](https://www.federalreserve.gov/releases/z1/20260911/html/default.htm) ([CSV package](https://www.federalreserve.gov/releases/z1/20260911/z1_csv_files.zip), file `F3_2_s.csv`). Shares and changes are *calculated*.

How to read this table:
- **Coverage and valuation.** L.210 covers *marketable* Treasuries only. Savings bonds, SLGS and GAS are excluded. Most holder rows are at **market value**.
  - Rows marked † are not at market value: money market funds, central counterparties and ABS issuers.
  - The total supply on the liability side is at **par**: $30,878.3B.
  - The $1,864.7B gap between par supply and the market-value holdings of identified sectors is shown by the Fed as an "instrument discrepancy". It is not allocated to any holder.
- **Shares** are of the $29,013.6B held by identified sectors.
- **Households.** The Fed states that household-sector estimates are "largely residual, derived from other sectors' data" ([Z.1 release, "Description of Most Recent Data Available"](https://www.federalreserve.gov/releases/z1/20260911/z1.pdf)). The $2,831.1B is therefore not a direct survey of households.
- **Federal Reserve.** The $4,082.7B is market value at 2026-06-30. It equals the Fed's own reported fair value (see §6.1). At **face value** the Fed held $4,564.2B on 2026-09-30 ([H.4.1, 2026-10-01](https://www.federalreserve.gov/releases/h41/20261001/)). That is bills $560.2B, nominal notes and bonds $3,618.0B, and TIPS $280.0B plus $106.0B of inflation compensation.
- **Foreign holders.** Z.1 shows $9,269.2B at 2026-06-30. TIC shows $9,298.5B for June 2026 and $9,248.1B for July 2026; see §3.
- **US banks.** This row is U.S.-chartered depository institutions at market value. The bank-by-bank call-report view in §4 counts Treasuries at AFS fair value plus HTM amortized cost: $1,663.3B at 2026-06-30, plus $235.9B in trading accounts.

### 2.2 Treasury's own ownership estimate (OFS-2; latest detailed quarter 2026-03-31)

| Owner (Treasury OFS-2) | 2026-03-31 ($B) | Share of total public debt |
|---|--:|--:|
| Total Public Debt | 39,065.4 | 100.0% |
| Federal Reserve And Government Accounts | 12,024.3 | 30.8% |
| Total Privately Held | 27,041.1 | 69.2% |
| Depository Institutions | 2,169.5 | 5.6% |
| U.S. Savings Bonds | 148.8 | 0.4% |
| Pension Funds - Private | 607.0 | 1.6% |
| Pension Funds - State And Local Governments | 573.9 | 1.5% |
| Insurance Companies | 597.9 | 1.5% |
| Mutual Funds | 5,122.8 | 13.1% |
| State And Local Governments | 1,641.6 | 4.2% |
| Foreign And International | 9,355.0 | 23.9% |
| Other Investors | 6,824.7 | 17.5% |

Source: [Treasury Fiscal Data, Treasury Bulletin table OFS-2, "Estimated Ownership of U.S. Treasury Securities"](https://fiscaldata.treasury.gov/datasets/treasury-bulletin/) (`v1/accounting/tb/ofs2_estimated_ownership_treasury_securities`).

How OFS-2 differs from Z.1:
- It covers *total* public debt, including non-marketable securities.
- It combines the Fed with government accounts.
- Its "Mutual funds" row includes money market funds.
- "Other investors", which includes households, is a residual.
- For 2026-06-30, only the top-line totals are published so far. The holder detail for that quarter is **not disclosed** yet.

### 2.3 Weekly bank aggregates (week ending 2026-09-16, not seasonally adjusted)

| Bank group | Treasury and agency securities ($B) | of which MBS ($B) | of which non-MBS: Treasuries **plus** agency debt ($B) |
|---|--:|--:|--:|
| All commercial banks in the U.S. | 4,784.6 | 2,729.4 | 2,055.2 |
| Domestically chartered banks | 4,561.0 | 2,665.5 | 1,895.5 |
| &nbsp;&nbsp;Large domestically chartered | 3,649.1 | 1,997.6 | 1,651.5 |
| &nbsp;&nbsp;Small domestically chartered | 911.9 | 668.0 | 244.0 |
| Foreign-related institutions | 223.5 | 63.8 | 159.7 |

Source: [Federal Reserve H.8, release of 2026-09-25](https://www.federalreserve.gov/releases/h8/20260925/), Tables 3, 5, 7, 9 and 11, line 5. H.8 reports Treasuries and non-MBS agency debt together in the "Non-MBS" line, so Treasury-only holdings are **not disclosed** in H.8. For the Treasury-only split, see the call-report data in §4.

---

## 3. Country level

### 3.1 Major Foreign Holders of Treasury Securities (July 2026 vs. July 2025)

| # | Country (as listed by Treasury) | Jul 2026 ($B) | Jul 2025 ($B) | Change ($B) | Change (%) | Share of foreign total | of which notes & bonds ($B) | of which bills ($B) | Custody/financial-center caveat |
|--:|---|--:|--:|--:|--:|--:|--:|--:|---|
| 1 | Japan | 1,103.9 | 1,155.4 | -51.5 | -4.5% | 11.9% | 1,023.8 | 80.2 |  |
| 2 | United Kingdom | 998.3 | 895.9 | +102.4 | +11.4% | 10.8% | 887.6 | 110.8 | Yes (global custody center) |
| 3 | China, Mainland | 618.0 | 695.6 | -77.6 | -11.2% | 6.7% | 578.3 | 39.7 |  |
| 4 | Belgium | 470.7 | 425.4 | +45.3 | +10.6% | 5.1% | 393.8 | 76.9 | Yes (Euroclear, an international central securities depository) |
| 5 | Cayman Islands | 460.1 | 436.8 | +23.3 | +5.3% | 5.0% | 248.9 | 211.2 | Yes (fund domicile) |
| 6 | Luxembourg | 442.1 | 403.8 | +38.3 | +9.5% | 4.8% | 353.7 | 88.3 | Yes (Clearstream; fund domicile) |
| 7 | Canada | 426.3 | 381.8 | +44.5 | +11.7% | 4.6% | 389.2 | 37.2 |  |
| 8 | Ireland | 350.2 | 320.2 | +30.0 | +9.4% | 3.8% | 239.3 | 110.9 | Yes (fund domicile) |
| 9 | France | 348.4 | 391.0 | -42.6 | -10.9% | 3.8% | 329.5 | 18.9 |  |
| 10 | Taiwan | 296.1 | 308.8 | -12.7 | -4.1% | 3.2% | 289.6 | 6.5 |  |
| 11 | Switzerland | 284.8 | 303.2 | -18.4 | -6.1% | 3.1% | 228.3 | 56.6 | Yes (custody center) |
| 12 | Singapore | 277.7 | 252.4 | +25.3 | +10.0% | 3.0% | 258.8 | 18.9 | Possible (regional financial center) |
| 13 | Hong Kong | 258.3 | 247.5 | +10.8 | +4.4% | 2.8% | 221.5 | 36.8 | Possible (regional financial center) |
| 14 | Norway | 206.9 | 208.0 | -1.1 | -0.5% | 2.2% | 206.3 | 0.6 |  |
| 15 | India | 202.6 | 219.7 | -17.1 | -7.8% | 2.2% | 182.9 | 19.7 |  |
| 16 | Brazil | 168.0 | 201.8 | -33.8 | -16.7% | 1.8% | 167.0 | 1.0 |  |
| 17 | Saudi Arabia | 142.4 | 131.6 | +10.8 | +8.2% | 1.5% | 110.2 | 32.2 |  |
| 18 | Korea, South | 131.5 | 132.3 | -0.8 | -0.6% | 1.4% | 106.7 | 24.8 |  |
| 19 | United Arab Emirates | 110.1 | 107.7 | +2.4 | +2.2% | 1.2% | 43.5 | 66.7 |  |
| 20 | Bermuda | 109.1 | 97.3 | +11.8 | +12.1% | 1.2% | 64.0 | 45.1 | Yes (insurer and fund domicile) |
|  | **All Other** | 1,842.4 | 1,793.2 | +49.2 | +2.7% | 19.9% | not published | not published |  |
|  | **Grand Total** | 9,248.1 | 9,109.5 | +138.6 | +1.5% | 100.0% | 7,783.3 | 1,464.9 |  |

Sources:
- Holdings: [Treasury TIC, SLT Table 5, "Major Foreign Holders of Treasury Securities"](https://ticdata.treasury.gov/resource-center/data-chart-center/tic/Documents/slt_table5.txt).
- Bills / notes-and-bonds split: [TIC SLT Table 3](https://ticdata.treasury.gov/resource-center/data-chart-center/tic/Documents/slt_table3.txt). "Notes & bonds" means long-term securities by original maturity, reported on Form SLT. "Bills" means short-term securities, reported on Form BL-2.
- Changes and shares are *calculated*.
- The table names exactly 20 countries plus "All Other". Long-term holdings are market values; TIC publishes a monthly "valuation change" column for them.

### 3.2 Official vs. private foreign holders

| Holder type | Jul 2026 total ($B) | Notes & bonds ($B) | Bills ($B) | Jul 2025 total ($B) | Change ($B) | Share of foreign total (Jul 2026) |
|---|--:|--:|--:|--:|--:|--:|
| Foreign official (governments, central banks, official institutions) | 3,773.1 | 3,418.8 | 354.4 | 3,886.5 | -113.3 | 40.8% |
| Foreign private (non-official) | 5,475.0 | 4,364.5 | 1,110.5 | 5,223.1 | +251.9 | 59.2% |
| Total foreign | 9,248.1 | 7,783.3 | 1,464.9 | 9,109.5 | +138.6 | 100.0% |

Source: [TIC SLT Table 3](https://ticdata.treasury.gov/resource-center/data-chart-center/tic/Documents/slt_table3.txt), rows "Of Which: Foreign Official" and "Of Which: Foreign Non-Official".

- **By country:** the official vs. private split is **not disclosed**. Treasury publishes it only for the all-country total.
- **Fed custody accounts:** the Fed reports $2,582.4B of marketable Treasuries held in custody at the Federal Reserve Bank of New York for foreign official and international accounts. That is the Wednesday level on 2026-09-30. The week-average was $2,594.8B, down $203.5B from the week ended 2025-10-01 ([H.4.1, 2026-10-01](https://www.federalreserve.gov/releases/h41/20261001/), table 1A memo). This is a subset of official holdings, since official holders also use private custodians. It is not split by country.

### 3.3 Custody location vs. true ownership

Treasury's own caveat on the table reads: *"The data in this table are collected primarily from U.S.-based custodians and broker-dealers. Since U.S. securities held in overseas custody accounts may not be attributed to the actual owners, the data may not provide a precise accounting of individual country ownership of Treasury securities."*

What this means for the table:
- **Treasury does not identify which countries' figures are custody-driven.** The flags in the last column of §3.1 are this report's characterization, not a Treasury statistic.
- **"Yes" rows** are jurisdictions that host international central securities depositories or are major custody or fund-domicile centers: Belgium (Euroclear), Luxembourg (Clearstream and funds), the United Kingdom, Switzerland, the Cayman Islands, Ireland and Bermuda.
  - Together these seven account for **$3,115.3B (33.7%)** of the July 2026 foreign total (*calculated*).
  - For these rows, the published figure reflects where the securities are held in custody or where the fund is domiciled. It does not show the nationality of the ultimate owner.
- **"Possible" rows** are regional financial centers: Hong Kong and Singapore.
- **Rows with no flag** are not free of custody distortion either. A country's investors may hold through custodians elsewhere. Treasury does not publish how much this applies to any country, including China and Japan.
- **Bills share is consistent with fund domiciles.** Short-term holdings are concentrated in several flagged jurisdictions: Cayman Islands 45.9% bills, Bermuda 41.4%, Ireland 31.7%. Several large holder countries hold far fewer bills: Japan 7.3%, China 6.4%, Taiwan 2.2%, Norway 0.3%. The UAE (60.5% bills) is the exception among unflagged rows. All shares are *calculated* from SLT Table 3.

---

## 4. Bank level: 15 largest U.S. banks by Treasury holdings (as of 2026-06-30)

| # | Bank (call report filer) | Parent | Treasuries, carrying value ($B) | AFS at fair value ($B) | HTM at amortized cost ($B) | AFS share | Memo: Treasuries in trading account ($B) | Agency debt, non-MBS ($B) | MBS, all ($B) | of which agency MBS ($B) | Total AFS+HTM securities ($B) | Treasuries as % of securities |
|--:|---|---|--:|--:|--:|--:|--:|--:|--:|--:|--:|--:|
| 1 | JPMorgan Chase Bank, N.A. | JPMorgan Chase & Co. | 483.3 | 341.0 | 142.4 | 71% | 86.3 | 0.3 | 196.7 | 173.7 | 804.6 | 60% |
| 2 | Bank of America, N.A. | Bank of America Corp. | 298.3 | 177.0 | 121.3 | 59% | 23.9 | 0.0 | 474.1 | 471.2 | 834.8 | 36% |
| 3 | Citibank, N.A. | Citigroup Inc. | 128.3 | 52.5 | 75.9 | 41% | 40.1 | 0.0 | 115.8 | 113.7 | 423.2 | 30% |
| 4 | Goldman Sachs Bank USA | Goldman Sachs Group | 111.3 | 86.3 | 25.0 | 78% | 52.6 | 0.0 | 24.4 | 24.4 | 137.4 | 81% |
| 5 | Wells Fargo Bank, N.A. | Wells Fargo & Co. | 81.3 | 77.5 | 3.8 | 95% | 24.6 | 0.0 | 311.7 | 308.4 | 442.3 | 18% |
| 6 | Morgan Stanley Bank, N.A. | Morgan Stanley | 48.7 | 43.2 | 5.5 | 89% | 0.0 | 0.0 | 29.8 | 28.4 | 82.6 | 59% |
| 7 | PNC Bank, N.A. | PNC Financial Services | 44.1 | 27.1 | 17.0 | 61% | 2.3 | 3.1 | 93.1 | 92.0 | 149.4 | 30% |
| 8 | TD Bank, N.A. | TD Group US (Toronto-Dominion Bank, Canada) | 41.1 | 41.1 | 0.0 | 100% | 0.0 | 0.2 | 53.0 | 42.8 | 130.4 | 32% |
| 9 | The Bank of New York Mellon | BNY (Bank of New York Mellon Corp.) | 36.0 | 29.9 | 6.1 | 83% | 0.1 | 4.1 | 60.2 | 56.7 | 155.5 | 23% |
| 10 | Banco Popular de Puerto Rico | Popular, Inc. | 25.3 | 19.2 | 6.2 | 76% | 0.0 | 0.0 | 4.1 | 4.1 | 29.6 | 86% |
| 11 | State Street Bank and Trust Co. | State Street Corp. | 24.3 | 24.0 | 0.3 | 99% | 0.0 | 0.0 | 45.7 | 43.0 | 107.1 | 23% |
| 12 | U.S. Bank N.A. | U.S. Bancorp | 24.1 | 23.4 | 0.6 | 97% | 0.0 | 4.7 | 112.3 | 112.3 | 162.5 | 15% |
| 13 | BMO Bank N.A. | BMO Financial Corp. (Bank of Montreal, Canada) | 22.6 | 22.6 | 0.0 | 100% | 0.0 | 1.0 | 35.1 | 35.1 | 64.7 | 35% |
| 14 | HSBC Bank USA, N.A. | HSBC USA Inc. (HSBC Holdings, UK) | 21.4 | 15.4 | 6.0 | 72% | 4.5 | 0.5 | 26.8 | 26.8 | 53.3 | 40% |
| 15 | City National Bank | Royal Bank of Canada | 13.8 | 9.5 | 4.3 | 69% | 0.3 | 0.4 | 3.3 | 3.3 | 20.0 | 69% |
| | **All 4,297 call-report filers** | | **1,663.3** | 1,223.5 | 439.8 | 74% | 235.9 | 113.2 | 2,949.8 | 2,850.4 | 5,802.6 | 29% |

Sources: Consolidated Reports of Condition and Income (call reports) for 2026-06-30, [FFIEC Central Data Repository bulk download](https://cdr.ffiec.gov/public/PWS/DownloadBulkData.aspx) ("Call Reports – Single Period", 06/30/2026, all schedules).

Column definitions:
- **Treasuries.** Schedule RC-B item 1: RCFD/RCON 0211 (HTM amortized cost) and 1287 (AFS fair value).
- **Agency debt.** Item 2, codes HT50/HT53.
- **MBS.** Items 4.a–4.c. Agency MBS uses the GNMA, FNMA and FHLMC lines G300–G307, G312–G319, K142–K145 and K150–K153.
- **Trading account.** Schedule RC-D item 1 (code 3531). It is shown as a memo and is **not** included in the ranking.
- **Shares and totals** are *calculated*.

Ranking rules:
- Banks are ranked by Treasury carrying value, i.e. AFS at fair value plus HTM at amortized cost.
- The ranking is of individual insured bank charters. That makes it consistent across all banks and is the only level at which Treasuries are separated from agency debt and MBS for every institution.
- "U.S. banks" means U.S.-chartered, FDIC-insured call-report filers. That includes U.S. bank subsidiaries of foreign groups (TD, BMO, HSBC, City National/RBC) and a Puerto Rico bank (Banco Popular).
- Excluding foreign-owned charters, the next five are:

  | Bank | Treasuries ($B) |
  |---|--:|
  | First-Citizens Bank & Trust | 13.7 |
  | Morgan Stanley Private Bank, N.A. | 13.2 |
  | Truist Bank | 13.1 |
  | Huntington National Bank | 10.9 |
  | Capital One, N.A. | 10.2 |

- The top 15 hold **84.4%** of all banks' AFS+HTM Treasuries.
- Affiliate charters not shown in the top 15: Morgan Stanley Private Bank, N.A. ($13.2B) and TD Bank USA, N.A. ($5.1B). Charles Schwab Bank, SSB holds $7.0B of Treasuries.

Does each source separate Treasuries from agency and MBS?
- **Call report: yes, for all 15 banks.**
- **10-Qs: only five tag a Treasury-only category.** They are Citigroup, Morgan Stanley, BNY, Popular and HSBC USA.
- **Seven 10-Qs combine Treasuries with agency debt.**
  - JPMorgan, Bank of America, Goldman Sachs (AFS), Wells Fargo, PNC and U.S. Bancorp tag "U.S. Treasury and government" (`USTreasuryAndGovernmentMember`).
  - State Street tags "U.S. Treasury and federal agencies – direct obligations".
  - For these banks, the filing alone does not allow a Treasury-only figure, which is why the call-report data is used here.
- **No 10-Q at all:** TD Bank, BMO Bank and City National Bank. Their parents are foreign banks that do not file 10-Qs.

Holding-company 10-Q amounts can differ from the bank-level figures above because they include non-bank subsidiaries. For example, Goldman Sachs Group's AFS+HTM Treasury and government holdings are $195.1B at amortized cost, while Goldman Sachs Bank USA's Treasuries are $111.3B.

---

## 5. Maturity

### 5.1 Outstanding marketable debt by type and remaining maturity (as of 2026-08-31)

| Type | Under 1 year | 1–5 years | 5–10 years | Over 10 years | Total unmatured ($B) | Share of marketable | WAM (years) | WAM (months) |
|---|--:|--:|--:|--:|--:|--:|--:|--:|
| Bills | 7,248.1 | 0.0 | 0.0 | 0.0 | 7,248.1 | 22.8% | 0.18 | 2.2 |
| Notes (nominal) | 2,915.1 | 9,648.7 | 3,654.6 | 0.0 | 16,218.4 | 51.0% | 3.36 | 40.3 |
| Bonds (nominal) | 29.6 | 100.7 | 26.4 | 5,368.5 | 5,525.3 | 17.4% | 20.29 | 243.5 |
| TIPS (incl. inflation adj.) | 222.8 | 939.7 | 555.1 | 435.0 | 2,152.7 | 6.8% | 7.42 | 89.1 |
| Floating rate notes | 353.1 | 326.9 | 0.0 | 0.0 | 680.0 | 2.1% | 1.01 | 12.1 |
| **All marketable** | **10,768.7** | **11,016.0** | **4,236.1** | **5,803.6** | **31,824.3** | 100.0% | **5.80** | **69.6** |
| Share of marketable | 33.8% | 34.6% | 13.3% | 18.2% | 100.0% | | | |

Source: [Treasury Fiscal Data, MSPD Table III, "Detail of Marketable Treasury Securities Outstanding"](https://fiscaldata.treasury.gov/datasets/monthly-statement-public-debt/detail-of-marketable-treasury-securities-outstanding) (`v1/debt/mspd/mspd_table_3_market`, 888 rows). Remaining-maturity buckets, shares and weighted average maturity (WAM) are *calculated*.

Method:
- Each security's outstanding amount is issued + inflation adjustment + redeemed (redemptions are negative), as published.
- Remaining maturity is measured from 2026-08-31 to the maturity date. The buckets are ≤1 year, >1–5, >5–10 and >10 years.
- WAM is amount-weighted.
- FRNs are bucketed by final maturity, although their coupons reset weekly.
- Excluded: the Federal Financing Bank ($3.6B, no maturity date) and matured-but-unredeemed notes and bonds ($0.06B). This is why the total is $31,824.3B rather than the $31,828.0B in §1.2.
- The by-type totals match MSPD Table I.

**Weighted average maturity: 69.6 months (5.80 years)** for all marketable debt, calculated as above. Treasury also publishes its own WAM in its quarterly refunding materials. That page could not be retrieved, so the official figure is **not reproduced here**.

**Share maturing in the next 12 months: 33.8% ($10,768.7B)** of marketable debt (*calculated*). Of that amount, $7,248.1B is bills and $2,915.1B is notes.

### 5.2 Maturity profile by holder group

Federal Reserve (the only sector aggregate in the specified sources with a published remaining-maturity profile; individual banks follow in §5.3):

| Holder | Basis / as of | Under 1 year | 1–5 years | 5–10 years | Over 10 years | Total ($B) |
|---|---|--:|--:|--:|--:|--:|
| Federal Reserve (SOMA) | Face value incl. TIPS inflation comp., H.4.1 Table 2, 2026-09-30 | 1,020.9 (22.4%) | 1,436.0 (31.5%) | 482.1 (10.6%) | 1,625.1 (35.6%) | 4,564.2 |
| All marketable Treasuries (for comparison) | MSPD, 2026-08-31 | 10,768.7 (33.8%) | 11,016.0 (34.6%) | 4,236.1 (13.3%) | 5,803.6 (18.2%) | 31,824.3 |

Source: [H.4.1, 2026-10-01, Table 2](https://www.federalreserve.gov/releases/h41/20261001/). The three sub-1-year buckets (≤15 days $107.4B, 16–90 days $372.6B, 91 days–1 year $540.9B) are summed. The Fed's WAM is **not disclosed** in H.4.1.

Bills vs. longer-dated Treasuries (the only maturity split published for other sectors; as of 2026-06-30):

| Holder | Treasury bills ($B) | Other Treasuries: notes, bonds, TIPS, FRNs ($B) | Bills share |
|---|--:|--:|--:|
| Federal Reserve (market value) | 485.3 | 3,597.4 | 11.9% |
| Money market funds | 2,317.6 | 964.0 | 70.6% |
| Mutual funds | 13.0 | 1,728.3 | 0.7% |
| Property-casualty insurers | 183.2 | 197.0 | 48.2% |
| Life insurers | 25.5 | 203.7 | 11.1% |
| Rest of the world | 1,419.7 | 7,849.5 | 15.3% |
| Total marketable outstanding (liability side, par) | 6,690.1 | 24,188.2 | 21.7% |

Source: [Z.1 L.210, 2026-09-11](https://www.federalreserve.gov/releases/z1/20260911/html/default.htm), lines 2–3, 10–11, 17–18, 20–21, 30–31, 33–34 and 44–45. Bills shares are *calculated*.

| Holder group | Remaining-maturity split (<1 / 1–5 / 5–10 / >10 years) | What *is* published |
|---|---|---|
| Foreign holders (TIC, Jul 2026) | **not disclosed** | Bills $1,464.9B (15.8%) vs. notes & bonds $7,783.3B, by original maturity. Official: bills 9.4%. Private: bills 20.3%. See §3. |
| U.S. banks, industry (call reports, 2026-06-30) | **not disclosed** for Treasuries alone | RC-B Memorandum item 2 reports remaining maturity for Treasuries *combined with* agency, municipal and other non-mortgage debt. Treasury-only maturity is not separated. |
| U.S. banks, H.8 / FDIC QBP | **not disclosed** | none |
| Money market funds, mutual funds, P&C and life insurers | **not disclosed** | bills vs. other only (table above) |
| Pension funds, state & local governments, households, ETFs | **not disclosed** | no maturity split at all |
| WAM for any holder group | **not disclosed** | none |

### 5.3 Maturity of Treasury holdings at individual banks (10-Q, as of 2026-06-30)

| Holding company (10-Q, 2026-06-30) | What the filing's XBRL category covers | Basis | Under 1 year ($B) | 1–5 years ($B) | 5–10 years ($B) | Over 10 years ($B) | Total ($B) | Share under 1 year | Share over 5 years |
|---|---|---|--:|--:|--:|--:|--:|--:|--:|
| [JPMorgan Chase & Co.](https://www.sec.gov/Archives/edgar/data/19617/000162828026054343/jpm-20260630.htm) | Treasury + agency debt combined (USTreasuryAndGovernmentMember) | AC | 40.9 | 357.5 | 80.2 | 6.4 | 484.9 | 8.4% | 17.9% |
| [Bank of America Corp.](https://www.sec.gov/Archives/edgar/data/70858/000007085826000394/bac-20260630.htm) | Treasury + agency debt combined (USTreasuryAndGovernmentMember) | AC* | 16.3 | 281.4 | 22.4 | 0.0 | 320.2 | 5.1% | 7.0% |
| [Citigroup Inc.](https://www.sec.gov/Archives/edgar/data/831001/000083100126000045/c-20260630.htm) | Treasury only (USTreasurySecuritiesMember) | AC | 39.8 | 70.1 | 19.5 | 0.0 | 129.4 | 30.8% | 15.1% |
| [Goldman Sachs Group](https://www.sec.gov/Archives/edgar/data/886982/000088698226000297/gs-20260630.htm) | Combined: AFS USTreasuryAndGovernmentMember; HTM USGovernmentDebtSecuritiesMember | AC | 16.6 | 107.0 | 68.8 | 2.7 | 195.1 | 8.5% | 36.6% |
| [Wells Fargo & Co.](https://www.sec.gov/Archives/edgar/data/72971/000007297126000302/wfc-20260630.htm) | Treasury + agency debt combined (USTreasuryAndGovernmentMember) | AC | 2.5 | 18.1 | 59.7 | 4.6 | 84.9 | 2.9% | 75.7% |
| [Morgan Stanley](https://www.sec.gov/Archives/edgar/data/895421/000089542126000212/ms-20260630.htm) | Treasury only (USTreasurySecuritiesMember) | AC | 34.2 | 48.7 | 0.1 | 1.6 | 84.5 | 40.5% | 1.9% |
| [PNC Financial Services](https://www.sec.gov/Archives/edgar/data/713676/000162828026053170/pnc-20260630.htm) | Treasury + agency debt combined (USTreasuryAndGovernmentMember) | AC | 8.0 | 34.2 | 2.2 | 3.1 | 47.5 | 16.8% | 11.2% |
| [BNY](https://www.sec.gov/Archives/edgar/data/1390777/000139077726000086/bk-20260630.htm) | Treasury only (USTreasurySecuritiesMember) | FV (AFS) | 4.8 | 29.1 | 0.1 | 1.9 | 36.0 | 13.4% | 5.7% |
| [Popular, Inc.](https://www.sec.gov/Archives/edgar/data/763901/000076390126000019/bpop-20260630.htm) | Treasury only (USTreasurySecuritiesMember) | AC | 16.0 | 10.7 | — | — | 26.7 | 59.8% | 0.0% |
| [State Street Corp.](https://www.sec.gov/Archives/edgar/data/93751/000009375126000397/stt-20260630.htm) | Treasury + agency direct obligations combined (UsTreasuryAndFederalAgenciesDirectObligationsMember) | AC | 3.8 | 20.9 | 0.0 | 0.0 | 24.7 | 15.2% | 0.1% |
| [U.S. Bancorp](https://www.sec.gov/Archives/edgar/data/36104/000003610426000044/usb-20260630.htm) | Treasury + agency debt combined (USTreasuryAndGovernmentMember) | AC | 0.7 | 21.6 | 8.5 | 0.0 | 30.8 | 2.1% | 27.7% |
| [HSBC USA Inc.](https://www.sec.gov/Archives/edgar/data/83246/000008324626000022/hsbcusa-20260630.htm) | Treasury only (USTreasurySecuritiesMember) | AC | 0.2 | 12.6 | 6.3 | 2.4 | 21.5 | 1.1% | 40.3% |

Sources: each company's Q2 2026 Form 10-Q, linked in the table. The data are the XBRL facts tagged in the investment-securities note's contractual-maturity table. AFS and HTM are combined, and totals and shares are *calculated*.

How to read this table:
- **Level.** These are holding-company figures, so totals differ from the bank-charter figures in §4.
- **"AC"** means amortized cost.
- **Bank of America (AC\*)** discloses maturities for all "debt securities carried at fair value" ($198.9B at cost; AFS is $195.2B of that) rather than AFS alone.
- **BNY** tags AFS maturities at fair value only.
- **"—"** means no amount was reported in that bucket.
- **Wells Fargo:** its entire HTM Treasury book ($3.8B) matures after 10 years.
- **Not disclosed** (no 10-Q filed): TD Bank N.A., BMO Bank N.A., City National Bank.

---

## 6. Underwater positions: amortized cost vs. fair value

### 6.1 Federal Reserve (SOMA, as of 2026-06-30)

| Security | Amortized cost ($B) | Fair value ($B) | Unrealized gain/(loss) ($B) | Loss % of cost |
|---|--:|--:|--:|--:|
| Treasury bills | 485.4 | 485.3 | (0.1) | 0.02% |
| Treasury notes | 2,233.2 | 2,144.2 | (89.0) | 3.99% |
| Treasury bonds | 1,925.7 | 1,453.2 | (472.4) | 24.53% |
| **Total Treasury securities** | **4,644.2** | **4,082.7** | **(561.5)** | **12.09%** |
| Memo: agency MBS | 1,984.6 | 1,668.0 | (316.6) | 15.95% |
| Memo: total domestic SOMA securities | 6,631.3 | 5,753.3 | (878.0) | 13.24% |
| Memo: total Treasury securities, 2025-12-31 | 4,390.2 | 3,854.9 | (535.3) | 12.19% |

Source: [Federal Reserve Banks Combined Quarterly Financial Report, June 30, 2026 (unaudited)](https://www.federalreserve.gov/aboutthefed/files/quarterly-report-20260828.pdf), Table 3. Loss percentages are *calculated*.

Per the report, SOMA securities are carried at amortized cost, and changes in unrealized gains and losses are not recorded in the Combined statements of operations. The Treasury loss widened by $26.3B in the first half of 2026 (report Table 11).

### 6.2 Banking industry (all FDIC-insured call-report filers, as of 2026-06-30)

| Portfolio | Amortized cost ($B) | Fair value ($B) | Unrealized gain/(loss) ($B) | Loss % of cost | Source |
|---|--:|--:|--:|--:|---|
| **All AFS + HTM securities** | 5,912.4 | 5,585.7 | (326.7) | 5.5% | FDIC QBP; call reports |
| &nbsp;&nbsp;AFS securities | 3,843.0 | 3,733.2 | (109.8) | 2.9% | FDIC QBP; call reports |
| &nbsp;&nbsp;HTM securities | 2,069.4 | 1,852.5 | (216.9) | 10.5% | FDIC QBP; call reports |
| **U.S. Treasury securities only** | 1,670.5 | 1,636.4 | (34.1) | 2.04% | call reports (*calculated*) |
| &nbsp;&nbsp;Treasuries, AFS | 1,230.7 | 1,223.5 | (7.2) | 0.58% | call reports (*calculated*) |
| &nbsp;&nbsp;Treasuries, HTM | 439.8 | 412.9 | (27.0) | 6.13% | call reports (*calculated*) |
| Non-Treasury securities (MBS, agency, municipal, other) | 4,241.9 | 3,949.3 | (292.6) | 6.9% | *calculated* difference |

Sources:
- [FDIC Quarterly Banking Profile, Q2 2026](https://www.fdic.gov/quarterly-banking-profile/quarterly-banking-profile-2q-2026) ([PDF](https://www.fdic.gov/quarterly-banking-profile/quarterly-banking-profile-second-quarter-2026.pdf)). It reports unrealized losses of $326.7B (5.5%), AFS $109.8B (2.9%) and HTM $216.9B (10.5%).
- [FFIEC CDR call-report bulk data, 2026-06-30](https://cdr.ffiec.gov/public/PWS/DownloadBulkData.aspx), RC-B summed over all 4,297 filers.
- Summing the call-report totals reproduces the QBP figures exactly. The QBP itself does not separate Treasuries.
- Treasuries account for **$34.1B (10.4%) of the industry's $326.7B** unrealized securities loss.

### 6.3 Each of the 15 banks (bank-charter level, as of 2026-06-30)

| # | Bank | Treasuries amortized cost ($B) | Treasuries fair value ($B) | Unrealized gain/(loss) ($B) | Loss % of cost | AFS: cost / fair / (loss) ($B) | HTM: cost / fair / (loss) ($B) | Memo: all AFS+HTM securities (loss) ($B) and % of cost |
|--:|---|--:|--:|--:|--:|---|---|---|
| 1 | JPMorgan Chase Bank, N.A. | 484.67 | 476.02 | -8.65 | 1.78% | 342.29 / 340.95 / -1.34 | 142.38 / 135.07 / -7.31 | -20.9 (2.6%) |
| 2 | Bank of America, N.A. | 298.91 | 285.24 | -13.67 | 4.57% | 177.65 / 176.99 / -0.66 | 121.26 / 108.25 / -13.01 | -84.2 (10.1%) |
| 3 | Citibank, N.A. | 128.41 | 125.72 | -2.69 | 2.10% | 52.56 / 52.49 / -0.07 | 75.85 / 73.23 / -2.62 | -11.3 (2.7%) |
| 4 | Goldman Sachs Bank USA | 111.76 | 111.07 | -0.70 | 0.62% | 86.79 / 86.30 / -0.49 | 24.97 / 24.77 / -0.20 | -0.5 (0.4%) |
| 5 | Wells Fargo Bank, N.A. | 81.23 | 79.55 | -1.69 | 2.07% | 77.43 / 77.50 / +0.07 | 3.80 / 2.04 / -1.76 | -35.5 (8.0%) |
| 6 | Morgan Stanley Bank, N.A. | 48.72 | 48.24 | -0.48 | 0.98% | 43.23 / 43.20 / -0.03 | 5.48 / 5.04 / -0.44 | -4.1 (4.9%) |
| 7 | PNC Bank, N.A. | 44.39 | 43.76 | -0.64 | 1.44% | 27.41 / 27.12 / -0.29 | 16.98 / 16.63 / -0.35 | -5.1 (3.3%) |
| 8 | TD Bank, N.A. | 41.11 | 41.12 | +0.002 | gain (+0.004%) | 41.11 / 41.12 / +0.00 | 0.00 / 0.00 / +0.00 | -0.6 (0.5%) |
| 9 | The Bank of New York Mellon | 36.12 | 35.85 | -0.27 | 0.73% | 29.99 / 29.89 / -0.10 | 6.12 / 5.96 / -0.16 | -3.6 (2.3%) |
| 10 | Banco Popular de Puerto Rico | 25.41 | 25.32 | -0.09 | 0.35% | 19.26 / 19.19 / -0.07 | 6.16 / 6.13 / -0.02 | -0.9 (3.1%) |
| 11 | State Street Bank and Trust Co. | 24.27 | 24.30 | +0.03 | gain (+0.12%) | 24.00 / 24.03 / +0.03 | 0.27 / 0.27 / -0.00 | -4.1 (3.9%) |
| 12 | U.S. Bank N.A. | 24.65 | 24.08 | -0.57 | 2.31% | 24.00 / 23.44 / -0.56 | 0.65 / 0.64 / -0.01 | -13.9 (8.3%) |
| 13 | BMO Bank N.A. | 23.75 | 22.59 | -1.16 | 4.89% | 23.75 / 22.59 / -1.16 | 0.00 / 0.00 / +0.00 | -2.4 (3.5%) |
| 14 | HSBC Bank USA, N.A. | 21.50 | 21.30 | -0.20 | 0.93% | 15.52 / 15.39 / -0.13 | 5.98 / 5.91 / -0.07 | -2.1 (3.8%) |
| 15 | City National Bank | 13.87 | 13.82 | -0.06 | 0.42% | 9.56 / 9.49 / -0.06 | 4.32 / 4.32 / +0.01 | -0.6 (2.9%) |
| | **All call-report filers** | **1,670.50** | **1,636.37** | **-34.12** | **2.04%** | 1,230.65 / 1,223.48 / -7.17 | 439.84 / 412.89 / -26.96 | -326.7 (5.5%) |

Source: call reports for 2026-06-30, Schedule RC-B items 1 (Treasuries) and 8 (totals). Codes: 0211/0213 (HTM cost/fair), 1286/1287 (AFS cost/fair), 1754/1771/1772/1773 (all securities). [FFIEC CDR](https://cdr.ffiec.gov/public/PWS/DownloadBulkData.aspx). Gains and losses are *calculated*.

A few portfolio-level details:
- **TD Bank and State Street** show small net gains on Treasuries: +$1.8 million and +$29 million.
- **Wells Fargo** has a 46.2% loss on its small HTM Treasury book ($3.80B cost vs. $2.04B fair value). Its 10-Q places all of that book beyond 10 years.
- **Bank of America's** HTM Treasuries are $13.0B (10.7%) underwater.
- **Cross-check with the 10-Qs.** At holding-company level, the 10-Qs give similar Treasury losses where Treasuries are tagged separately.
  - Citigroup: AFS (0.08), HTM (2.63).
  - Morgan Stanley: AFS (0.04), HTM (0.70).
  - BNY: AFS (0.10), HTM (0.16).
  - HSBC USA: AFS (0.13), HTM (0.07).

### 6.4 Ranking: most to least underwater (by unrealized loss as % of amortized cost)

| Rank | Holder | Amortized cost ($B) | Fair value ($B) | Unrealized gain/(loss) ($B) | Loss % of cost |
|--:|---|--:|--:|--:|--:|
| 1 | Federal Reserve (SOMA Treasuries, 2026-06-30) | 4,644.2 | 4,082.7 | -561.54 | 12.09% |
| 2 | BMO Bank N.A. | 23.7 | 22.6 | -1.16 | 4.89% |
| 3 | Bank of America, N.A. | 298.9 | 285.2 | -13.67 | 4.57% |
| 4 | U.S. Bank N.A. | 24.7 | 24.1 | -0.57 | 2.31% |
| 5 | Citibank, N.A. | 128.4 | 125.7 | -2.69 | 2.10% |
| 6 | Wells Fargo Bank, N.A. | 81.2 | 79.5 | -1.69 | 2.07% |
| 7 | Banking industry total (all call-report filers) | 1,670.5 | 1,636.4 | -34.12 | 2.04% |
| 8 | JPMorgan Chase Bank, N.A. | 484.7 | 476.0 | -8.65 | 1.78% |
| 9 | PNC Bank, N.A. | 44.4 | 43.8 | -0.64 | 1.44% |
| 10 | Morgan Stanley Bank, N.A. | 48.7 | 48.2 | -0.48 | 0.98% |
| 11 | HSBC Bank USA, N.A. | 21.5 | 21.3 | -0.20 | 0.93% |
| 12 | The Bank of New York Mellon | 36.1 | 35.9 | -0.27 | 0.73% |
| 13 | Goldman Sachs Bank USA | 111.8 | 111.1 | -0.70 | 0.62% |
| 14 | City National Bank | 13.9 | 13.8 | -0.06 | 0.42% |
| 15 | Banco Popular de Puerto Rico | 25.4 | 25.3 | -0.09 | 0.35% |
| 16 | TD Bank, N.A. | 41.1 | 41.1 | +0.002 | gain (+0.004%) |
| 17 | State Street Bank and Trust Co. | 24.3 | 24.3 | +0.03 | gain (+0.12%) |

Ranking by **dollar** loss:

| Rank | Holder | Unrealized loss ($B) |
|--:|---|--:|
| 1 | Federal Reserve | 561.5 |
| 2 | Banking industry total | 34.1 |
| 3 | Bank of America | 13.7 |
| 4 | JPMorgan Chase | 8.7 |
| 5 | Citibank | 2.7 |
| 6 | Wells Fargo | 1.7 |
| 7 | BMO | 1.2 |
| 8 | Goldman Sachs Bank USA | 0.7 |
| 9 | PNC | 0.6 |
| 10 | U.S. Bank | 0.6 |
| 11 | Morgan Stanley Bank | 0.5 |
| 12 | BNY | 0.3 |
| 13 | HSBC Bank USA | 0.2 |
| 14 | Banco Popular | 0.1 |
| 15 | City National | 0.1 |
| 16 | TD Bank | gain |
| 17 | State Street | gain |

Amortized cost vs. fair value is **not disclosed** in the specified sources for:
- foreign official and private holders (TIC collects market values only)
- money market funds, mutual funds and ETFs
- insurers
- private, state and local, and federal pension funds
- state and local governments
- households
- broker-dealers, hedge funds and GSEs

Z.1 gives only their market values. These holders therefore cannot be placed in the ranking.

---

## Summary: who carries the most interest-rate risk, and why

1. **The Federal Reserve is the largest by far.** It is $561.5B (12.1% of cost) underwater on Treasuries alone as of 2026-06-30. That is more than 16 times the entire banking industry's Treasury loss.
   - Its book is long: 35.6% of its Treasuries mature in more than 10 years, versus 18.2% of all marketable debt. Its bond holdings are 24.5% below cost.
   - Under its accounting, SOMA is carried at amortized cost, and unrealized losses do not run through its income statement. The exposure is real in market-value terms, but nothing forces the Fed to realize it.

2. **Other large holders of long-dated Treasuries are exposed, but their losses cannot be measured from these sources** because their cost basis is not published.
   - Foreign official holders: $3.77T, 90.6% notes and bonds by original maturity.
   - Mutual funds: 99.3% non-bills.
   - Life insurers: 88.9% non-bills.
   - Pension funds: $1.18T, no maturity split published.
   - These portfolios are valued at market, so rate moves pass straight through to their owners: fund shareholders, policyholders and plan beneficiaries.

3. **Banks carry modest Treasury rate risk; most of their rate risk is in MBS.**
   - The industry's Treasuries are only 2.0% underwater ($34.1B). Treasuries are just 10.4% of the $326.7B total unrealized securities loss.
   - The two largest bank Treasury books sit mainly in the 1–5 year bucket: 73.7% at JPMorgan and 87.9% at Bank of America, at holding-company level (*calculated* from 10-Qs).
   - Among banks, **Bank of America** carries the largest Treasury loss in dollars ($13.7B, 4.6%), almost all of it in HTM. Its all-securities book is 10.1% underwater, with large agency MBS holdings.
   - **BMO Bank** has the highest Treasury loss rate (4.9%).
   - **Wells Fargo** holds the longest Treasury book among the 10-Q filers: 75.7% beyond 5 years.

4. **Least exposed:**
   - Money market funds: 70.6% bills.
   - Banks with very short Treasury books, at holding-company level: Popular 59.8% under 1 year, Morgan Stanley 40.5% under 1 year.
   - State Street and TD Bank, whose Treasury books are at small net gains.

5. **On the issuer side**, 33.8% of marketable debt ($10.8T) matures within 12 months, and the computed WAM is 69.6 months. The federal government is therefore heavily exposed to refinancing at prevailing rates. Holders of the long end, led by the Fed and foreign official accounts, bear the market-value risk. The Treasury bears the rollover-cost risk on the short end.

---

## Source index

| Data | Link |
|---|---|
| Debt to the Penny | https://fiscaldata.treasury.gov/datasets/debt-to-the-penny/debt-to-the-penny |
| MSPD Tables I and III | https://fiscaldata.treasury.gov/datasets/monthly-statement-public-debt/ |
| MTS Tables 6-D and 8 | https://fiscaldata.treasury.gov/datasets/monthly-treasury-statement/ |
| Treasury Bulletin OFS-2 | https://fiscaldata.treasury.gov/datasets/treasury-bulletin/ |
| TIC SLT Table 5 (Major Foreign Holders) | https://ticdata.treasury.gov/resource-center/data-chart-center/tic/Documents/slt_table5.txt |
| TIC SLT Table 3 (Treasuries held by foreign residents) | https://ticdata.treasury.gov/resource-center/data-chart-center/tic/Documents/slt_table3.txt |
| Federal Reserve H.4.1 (2026-10-01) | https://www.federalreserve.gov/releases/h41/20261001/ |
| Federal Reserve H.8 (2026-09-25) | https://www.federalreserve.gov/releases/h8/20260925/ |
| Federal Reserve Z.1 (2026-09-11) | https://www.federalreserve.gov/releases/z1/20260911/html/default.htm |
| Federal Reserve Banks Combined Quarterly Financial Report (2026-06-30) | https://www.federalreserve.gov/aboutthefed/files/quarterly-report-20260828.pdf |
| FFIEC CDR call-report bulk data (2026-06-30) | https://cdr.ffiec.gov/public/PWS/DownloadBulkData.aspx |
| FDIC Quarterly Banking Profile, Q2 2026 | https://www.fdic.gov/quarterly-banking-profile/quarterly-banking-profile-2q-2026 |
| SEC 10-Q filings (Q2 2026) | linked individually in §5.3 |
