# **Money Supply**
#### **Purpose:** 
Python code that uses an API to pull money supply data directly from the Federal Reserve Economic Data (FRED)  <br>
I graph the latest data and offer comments on fiscal policy pandemic stimulus that drove up the money supply and subsequent record level inflation 
that **peaked in June 2022** at **9.1% YoY**. <br>

A 12 month inflation rate we haven't seen in *over 40 years* since 1981.

- **M1 Money Supply:** The most liquid forms of money, including currency, demand deposits, and other checkable deposits.
- **Use:** The money supply is a critical factor in monetary policy, influencing interest rates, inflation, and economic stability.

The output generates a m1 money supply graph with pointers of 3 waves of pandemic stimulus that rivaled World War II.

![image](https://github.com/user-attachments/assets/a98d08d6-1465-4b70-802f-e37968cadc74)

### How much was paid in each of the three rounds?

[Pandemic Oversight](https://www.pandemicoversight.gov/data-interactive-tools/data-stories/update-three-rounds-stimulus-checks-see-how-many-went-out-and)

- Round 1, March 2020: $1,200 per income tax filer, $500 per child (CARES Act)
- Round 2, December 2020: $600 per income tax filer, $600 per child (Consolidated Appropriations Act, 2021)
- Round 3, March 2021: $1,400 per income tax filer, $1,400 per child (American Rescue Plan Act)

In March 2022, the Fed reversed course with a period of quantitative tightening to bring down inflation by raising the federal funds rate amongst other means of administering monetary policy transmission.

# <h1><center>**APPENDIX**</center></h1>
Requirements: VS Code, Anaconda distribution for Python, Python 3.11.5, API Key from FRED

### **M1 Money Supply:**

**M1** is a category of the money supply that includes the most liquid and easily accessible forms of money. It represents the money that is readily available for spending and includes:

1. **Currency in Circulation:** This is the physical money (coins and paper currency) that is held by the public (excluding the currency held by the U.S. Treasury and Federal Reserve banks).
   
2. **Demand Deposits:** These are the balances in checking accounts that can be accessed on demand without any restrictions. These include traditional checking accounts as well as NOW (Negotiable Order of Withdrawal) accounts that allow interest to be earned.

3. **Other Checkable Deposits:** This includes deposits in credit unions, savings and loans, and mutual savings banks that can also be accessed using checks or debit cards.

4. **Traveler's Checks (Non-Bank Issued):** These are a small component of M1 but are included as they represent funds that can be easily converted to cash or used for transactions.



### **How Is the Money Supply Measured in the US?**

The money supply in the U.S. is measured by several aggregates, which include different categories of money based on liquidity. The Federal Reserve (the central bank of the U.S.) monitors and publishes these aggregates regularly.

#### **1. M1 (Narrow Money):**
   - **Definition:** As described above, M1 includes the most liquid forms of money—currency in circulation, demand deposits, other checkable deposits, and traveler's checks.
   - **Importance:** M1 is a measure of the money supply that reflects the money most easily accessible for transactions.

#### **2. M2 (Broad Money):**
   - **Definition:** M2 includes all of M1 plus additional forms of money that are less liquid but still can be converted into cash or used for transactions relatively easily.
   - **Components:**
     - **Savings Deposits:** Money in savings accounts, which can be withdrawn or transferred to checking accounts, although less easily than demand deposits.
     - **Time Deposits (Under $100,000):** These are certificates of deposit (CDs) with a fixed term and interest rate, which are less liquid than savings deposits.
     - **Retail Money Market Funds:** These are mutual funds that invest in short-term debt securities and are considered liquid assets.
   - **Importance:** M2 is a broader measure of the money supply that includes near-money (money that isn't as liquid as M1 but can still be quickly converted into cash).

#### **3. M3 (No Longer Published by the Federal Reserve):**
   - **Definition:** M3 used to include all of M2 plus larger time deposits, institutional money market funds, and other large liquid assets.
   - **Importance:** Although M3 was discontinued in 2006, it was a broader measure that included very large and less liquid assets. Some economists still monitor similar aggregates independently.

#### **4. Other Measures:**
   - **Monetary Base (M0):** This is the sum of currency in circulation and reserves held by banks at the Federal Reserve. It represents the foundation upon which the money supply is built.
   - **L (Liquid Money):** This is a very broad measure of money that includes all assets that can quickly be turned into cash.
