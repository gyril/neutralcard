Table of Contents
=================

1. [Why do we have credit cards?](#why-do-we-have-credit-cards)
    - [Historical perspective](#historical-perspective)
    - [Usage today](#usage-today)
2. [Difference between debit & credit cards](#difference-between-debit-credit-cards)
    - ["Owned" vs. "borrowed" money](#owned-vs-borrowed-money)
    - [Why France has such a small credit card market](#why-france-has-such-a-small-credit-card-market)
3. [How the networks came to be](#how-the-networks-came-to-be)
    - [4-party networks (Visa & MasterCard)](#4-party-networks)
        + How they work
        + Origins & special relationship with banks
        + Examples
    - [3-party networks (American Express, Discover, etc.)](#3-party-networks)
        + How they work
        + Examples
4. [Credit card economics](#credit-card-economics)
    - Transactions
        + The interchange fee: how much, to who, and why?
        + Difference between credit cards and debit cards transactions
        + Regulatory environment, in the US and Europe
    - Fees
    - Loan interests
5. [Launching a new credit card](#launching-a-new-credit-card)
    - Partnering with a bank
        + Examples
        + Cost and conditions
        + Know Your Customer, the bane of innovation
        + Playbook
    - Being the bank
    - Other paths
        + Integrate with existing cashback cards
6. [Carbon neutral](#carbon-neutral)
    - How to offset carbon emissions
    - Models to estimate the cost to offset 100% of emissions
    - Models to estimate the demand & market for this product
    - Charities, donations and credit-cards    


Unanswered questions:
+ Is there a different way to get the same result?
+ What else can be appealing about this product? (personal branding, credit building)
+ What else can be appealing about this company?


#Why do we have credit cards?

##Historical perspective
**Origins in customer loyalty programs**

At the beginning of the 20th century most transactions were conducted in cash. Big brands in retail (department stores, automotive/fuel companies, etc.) or hotel chains, looking for ways to improve customer loyalty, decided to extend credit to some of them. At first each store was keeping a direct credit relationship, as the goal was to keep customers loyal to their brand, but overtime some brands decided to mutualize their credit records to improve their customer's experience. At this point the relationship was still pretty direct between merchants and consumers, with no banking intermediary or processing entity in between. 

**An innovation for bookkeepers**

In the 1920s in the United States, various stores started issuing cards for their customers to facilitate bookkeeping. The user experience was as follows: a metal-card with user information (name, city, state) embossed was printed and kept at the store. When a customer came in for a purchase, they signed a paper, the clerk would compare signature to the one on the card, and if it matched, they would use the embossement to print their information on the ledger. The idea was to reduce copying errors, and that's why are cards are still embossed today.

**Payments on the road**

First with fuel, then quickly with plane tickets, the transportation industry was quick to harness the power of the credit cards. "Buy now, pay later". The difficulty of making payments when away from home, coupled with the naturally well-connected organization of the travel industry, allowed the credit card market to really take off.

American Express, which was originally operating railroads and mail routes but already involved in money movement through their Traveler's Cheques, saw the opportunity and started issuing cards in 1958. It's no surprise that today Amex is both a credit institution and a travel services provider, as the two activities still benefit from many synergies today.

**Networks effects**

While many attempts were made to launch nation-wide, general credit cards available to consumers, the chicken-and-egg problem (not enough people carrying a card, not enough merchants accepting the card) prevented any of them from becoming durably successful. In the 1950s, Bank of America took a different approach: they targeted specifically the city of Fresno, California, where they had a high customer penetration, and sent all 60,000 of them, for free, overnight, a BankAmericard. This was the first "drop" in history (mass unsolicited mailing of payment cards), a technique that proved to be the most effective one at generating adoption (it's now forbidden to send working cards in the mail, so credit card companies now send unsolicited applications). From there, the usage spread and the BankAmericard, through mergers, associations and acquisitions, eventually became the Visa network that we know today.

##Usage today

General stats: # of cards in circulation (credit & debit), average # of cards per holder, per household, amounts transacted daily, amount of debt carried
* There are 144 million cardholders in the US.
* A cardholder has an average of 5 credit cards. The competition is big between credit card issuers and they all fight for the "top of wallet" spot, the card that will be used for most spending.
* A family has an average of 8 credit cards. 
* Visa claims 2,550 billion cards in circulation, of which 930 are credit cards and 1620 are debit cards.
* There are roughly 6800 chartered banks in the United States, and all of them can issue payment cards.
* Usage of credit cards is decreasing amongst younger generations, in part because credit cards are more regulated than debit cards, in part because they're already in debt from student loans, and in part because campaigns fighting "financial illiteracy" might have caused some disaffection for consumer credit.


#Difference between debit & credit cards

##"Owned" vs. "borrowed" money
**It's your money this time, and it makes all the difference**

Credit cards have historically allowed you to spend someone else's money, usually loaned to you by a bank or a credit institution. As for all loans, there is an interest attached to credit cards, called the APR, the "Annual Percentage Rate", which is basically the annualized interest rate of a loan. Example: if you've been in debt for $1000 at 20% APR for six months, then you owe your bank 6/12 * 20% * $1000 = $100 in interests, on top of the $1000 debt of course. This is the main source of revenue for credit card products. The industry standard, however, is that if the balance is paid in full every month, the interest is waived, so unless you fail to pay your entire balance, you will have an effective APR of 0% on your loan. As for all loans in the US, the FICO score (aka credit score) is both inlfuencing the decision of the bank to issue a credit card AND influenced by the cardholder's usage of said credit card.

The fact that paying with credit means paying with the bank's money has one big implication: at the time of payment, the bank issuing the credit card, and not the cardholder, is liable for the transaction. Therefore, in case of fraudulent activity, say from a stolen card, the cardholder cannot be required to pay the debt incurred ("consumers' limited liability"); it also means that if the cardholder feels like he didn't receive what he thought he was buying (bad seller online, error in the delivery, etc.) he can ask for a "chargeback" that will take the money back from the merchant's account (and sometimes will cost them a processing fee on top of it) and erase the debt for the cardholder (the cargeback will probably be investigated, but the doubt benefits the cardholder). Overall, the regulation tends to favor the credit card holder way more than the merchants. This sounds really consumer-friendly until you realize that credit card companies have used this excuse to set the interchange fee at an incredibly high rate, arguing that because they were bearing such risk on behalf of the customers, they needed this fee to keep their products profitable. Some credit cards sometimes impose a 4% transaction fee on the merchants, and the regulation more or less prevents merchants from displaying different prices based on the mean of payment, so they have to take the loss if they decide to accept credit cards.

Debit cards are nothing like it: they are tied to a checkings account and draw directly from it. Some of them can have differed debit, where the money is drawn only once a month, but most of them cannot carry a negative balance (not without high penalty & fees[0]). Chargebacks can also be requested, but apart from the bank's willingness to do the right thing, the law doesn't require that the debit card holder be reimbursed in full. The flip side is that of course they carry no APR, that the interchange is way lower with debit cards, and that there is no FICO score involved in the decisions of the bank to issue one. 

[0] https://www.bankofamerica.com/deposits/resources/personal-schedule-fees.go

##Why France has such a small credit card market
There are roughly nine times less credit cards per capita in France than in the US [0]. Everybody has a card from the "Réseau Carte Bancaire" but most of them are debit cards and are not associated to any kind of credit. Why such a big discrepancy? Basically, it boils down to the feeble appeal of the French public for consumer credit in general, and revolving credit in particular.

An enlightening quote from Senator Elizabeth Warren:
"Bankruptcy is the great American story rewritten. We're a nation of debtors. Why do you think people left Europe to come to the United States? They left because they were in debt. We like to describe it as, "Oh, it was about religious freedom." No, it was about debt. They were looking for a way to escape their debts." [1]

But some of it also has to do with a peculiar combination of technology and regulations. Credit card companies have always claimed that their business had an inherent risk and therefore should perceive an interchange fee to cover for this risk. French banks, nudged by a regulator that wasn't too keen on imposing a 3%+ fee on transactions to merchants, instead tried to lower the fraud risk, and came up with many innovations: the chip card (Gemalto invented it and it's not becoming a worldwide standard), the PIN code, the 3DSecure online payments, etc. all served to make cards safer.

[0] http://www.indexcreditcards.com/finance/creditcardstatistics/credit-card-use-in-france.html

[1] http://www.pbs.org/wgbh/pages/frontline/shows/credit/interviews/warren.html

#How the networks came to be

There are several networks today that can be considered consequential. The most widely used networks are 4-party networks, but some 3-party networks are still competing and some of them are even growing faster than their counterparts.

##4-party networks
**How they work**

4-party networks involve the *cardholers* on one side, the *merchants* on the other side, the *network organizer* in the middle, and the *banks* managing the relationship between the organizer and their own customers (whether they are chardholders or merchants). In 4-party networks, network organizers only interact with banks: indeed, Visa and MasterCard's only customers are chartered banks (or credit institutions), and every card issued by them is tied to a bank account.

Basically, the banks act as the distribution layer for the network. The cardholder is the customer of an issuing bank. The issuing bank opens an account for the cardholder, and gives her a card so he can transacts with merchants. On the other side, the merchant is the customer of an acquiring bank (often through the intermediary of an "acquirer", a software and/or hardware provider like Stripe, Braintree, Square, etc.). The network organizer makes sure that information about cardholers' accounts is always readily available to acquiring banks, so that cardholders and merchants can transact at all times.

**Special relationship with banks**

Before their IPOs (both in 2006), Visa and MasterCard were owned by the banks that had united over time to create the networks. This explains why in so many ways the relationship between the networks and the bank is strong, symbiotic, and hard to disrupt. Banks are the only customers of Visa and MC: without the banks, credit and debit cards would never be distributed and Visa and MC would have no network. It's my opinion that the interchange fee really acts as a kickback from the networks to the bank to thank them for their efforts in distributing the cards. Even though the banks' customers are the cardholders and the merchants, by the nature of the network effects enjoyed by Visa and MC, and by the nature of the high barriers to entry in the banking indsutry, it is not in the interest of the banks to challenge the networks. In short, when the banks win the networks win, and vice versa. 

**Examples**

Visa and MasterCard are the most successful networks. Both have grown immensely in the last decade, growing more than 5 and 3 times in market cap respectively; both are international networks. 

To provide some perspective, Visa processed $4.9 trillion dollars in 2015, in 71 billion transactions; credit accounts for 63% of volume but only 36% of cards in circulation; [0]. 

UnionPay would be the Chinese equivalent and RuPay the Indian equivalent, although they're almost strictly domestic.

[0] http://s1.q4cdn.com/050606653/files/doc_financials/annual/VISA-2015-Annual-Report.pdf

##3-party networks
**How they work**

As the name suggests, in 3-party networks the network organizer sits directly between the cardholder and the merchant. Balance, authorization, settlement are all taken care of by the network organizer. There is no competition between issuers, as the network organizer has a monopoly on the issuance of cards. Those networks are simpler in nature, but they have to build their own distribution network. I don't think there is a big opportunity to partner with them, both because they have smaller networks and because their networks are less open, but it's still worth mentioning them for the sake of completeness.

**Examples**

*American Express*: the biggest 3-party network, Amex is a pioneer in the credit card industry (started issuing in 1958). American Express interchange is usually highest, neighboring 4%, but they get away with it by bringing to merchants customers of high value: business customers, who tend to both spend more and be more loyal.

*Discover*: in 4-party schemes, the merchants are the ones suffering the most. They cannot display different prices for customers paying in cash and customers paying with cards, so they have to eat the fee, which heavily weighs on their (usually thin) margins. The Discover network is their ripost. Launched by Sears in 1985, it started with no annual fee for the customer and the first possibility of a cashback bonus; it also had lower fees for merchants (I believe it was a fixed fee and not a percentage, but cannot find a source for that). Discover claims to be the 3-rd largest network by merchant acceptance, but both their volume and growth are significantly slower than their competitors.

*PayPal*: even though PayPal doesn't offer payment cards (not as a 3-party network, although they are Program Manager for some debit card programs), they fit the description of a 3-party payment network. They connect consumers directly with merchants, hold money for both of them, and take a fee on transactions. Even though their volumes are tiny when compared to Visa or MasterCard, they are considered the biggest threats to these companies. In May 2016, Visa's CEO said that if PayPal refused to play ball with them, they would go after them "in ways that people have never seen before." [0]

[0] http://www.recode.net/2016/5/25/11768854/visa-ceo-paypal-threat

#Credit card economics

Here we cover the various ways in which the organizations taking part in the network make money.

##Transactions
**The interchange fee: who pays and why? Who gets it?**

The "merchant discount" is the fee that is charged to the merchants on every transaction they accept coming from a network they participate in. They're usually the reason why some merchants don't take credit cards, or not Amex, or force you to go over a certain amount spent to accept your card (as the fee is usually a fixed sum plus a percentage of the transaction).

The merchant discount is actually comprised of 3 different fees: the *acquirer fee*, that is charged for the technical service provided by the merchant's bank to acquire payments; the *scheme fee*, that is paid to the network organizer; and the *interchange fee*, that then goes to the issuing bank.

The merchant discount is used to pay all the intermediaries:
- First comes the merchant's acquirer on the technical side. Depending on their model, they either charge "Interchange+" (cf. Adyen [0]), between 0.40% and 0.60% of the volume transacted *on top of what the network scheme and the issuing bank charge*, or they charge an upfront cost (cf. Stripe, 2.9% + $0.30 [1]) and hope that the scheme and interchange costs will allow them to make money. The biggest acquirers are First Data, WorldPay and Elavon.
- Then comes the acquiring bank. It's unclear whether they take a portion of the fee during the transaction, or whether they recoup their costs solely by charging monthly fees to the merchants, but the portion they get is almost insignificant.
- Then comes the network. They're not very transparent about the share they keep, but it can be inferred from the income they generate divided by the volume of payments they process: for Visa it comes out at roughly 0.12% of all transactions.
- Then comes the issuing bank or financial institution. They get the biggest share of the discount, called the interchange fee, as they provided the customer to begin with. The fees vary from $0.21 + 0.05% for regulated debit, up to 4% in some cases, depending on the conditions of the transaction and the types of goods, etc. It is well detailed in Visa's interchange prices in [2].
- Then (sometimes) comes the cardholder. Credit cards (and in rare cases debit cards) have rewards program that give back either cash, miles, or other forms of retribution to the cardholder. These rewards are financed with the interchange fee, at the discretion of the issuing bank and according to the pertaining Cardholder Agreement.

[0] https://docs.adyen.com/legal/adyen-pricing

[1] https://stripe.com/us/pricing

[2] https://usa.visa.com/dam/VCOM/download/merchants/visa-usa-interchange-reimbursement-fees.pdf

**Difference between credit cards and debit cards transactions**

There are several differences between debit and credit card transactions. First, they don't use the same network (called "rails" in the industry: NYCE, STAR are for debit, while Visa and MasterCard maintain credit rails) to settle transactions. Second, the fees differ greatly in volume. Durbin bill in the US and EU law in Europe regulate the maximum fee that can be applied on a debit card transaction. In the US, credit card transactions are still uncapped, although many bills have been proposed to amend that. For debit, the law states that the fee must be “reasonable and proportional” to the cost incurred. As a result, the interchange is way lower for debit transactions (capped at 0.05% + 21 cents per transaction, so an average of 0.55% or less than 24 cents).

**Regulatory environment, in the US and Europe**

In the US, the most recent & relevant low for this market is the Dodd-Frank & Durbin. The effect for banks was a loss of roughly ~14 billin in revenue, a loss that was mostly passed on to consumers, in the form of additional fees (inactivity fee, overdraft fee) and even monthly maintenance charges on deposit accounts [0].

In Europe, since 2015, caps are enacted on the interchange fee for both credit (0.3%) and debit (0.2%) cards transactions [1].

*As a result, I believe that it is unrealistic to try to fund a debit program solely on interchange fees in the US, or any kind of program in the EU.*

[0] https://www.nerdwallet.com/blog/banking/durbin-amendment-explained/

[1] http://europa.eu/rapid/press-release_IP-15-4585_en.htm

##Fees

Almost every card in the US come with many fees attached to their usage. Some banks claim that recent regulatory changes have forced them to apply new fees to recoup their losses.
- International transactions fees: Visa and MasterCard are usually accepted internationally, but on international payments a fee is often applied *on top of the exchange rate applied*.
- overdraft fees (debit) or over-the-limit fees: are applied when a cardholer spends more than he's allowed to (below zero for debit accounts, above the credit limit for credit cards).
- ATM fees: in the US it is extremely common to charge a fee on ATM withdrawals, as different networks of ATM are operated by different companies that rarely work with one another to lower the fees for the consumers.
- Maintenance fees (debit), annual fees (credit): due to the lowered interchange on debit, maintenance fees are on the rise, while annual fees on credit card vary from card to card. 
- Balance transfer fee (credit): usually between 3% and 4%, it's the cost incurred to move a balance from one card to another.

##Loan interests

This section only applies to credit cards. Financial institutions extending credit to their consumers charge them an interest rate on those loans. Credit card loans are one of the worst types of credit you can get, as not only the APR are extremely high when compared to mortgages, student loans, car loans, etc., they are also variable in time, and can become extremely predatory. 

Basically the idea is that, when a cardholder's risk rises (eg. they're late on the payment of one of their cards), the other institutions that provided them with other cards have the right to *rise* the APR. Some cards offer an "introductory" 0% APR, 

"Normal" APR ranges from 15%-25% for cardholder with good FICO score, and can go up to 500% (meaning you must pay interests of 40% of your debt *every month*).

Credit card companies claim that they need this tool to make sure that everyone can get access to credit, but regulators retort that this can allow for predatory behaviour: it's in the credit institution's best interest to target demographics they know won't be able to meet their monthly payments, so they can extract as much interest from them before they are forced to default and go bankrupt. This ongoing debate hasn't led to a cap on APR yet.

#Launching a new credit card

#Carbon neutral
##How to offset carbon emissions

##Models to estimate the cost to offset 100% of emissions

##Models to estimate the demand & market for this product

##Charities, donations and credit-cards
+ BofA + Susan G. Komen (bad charity, bad card: http://www.chicagotribune.com/business/ct-charity-credit-cards-1108-biz-20151106-story.html)
+ National Breast Cancer Foundation https://www.acecashexpress.com/prepaid-debit-cards/pink
+ UK-based banks: http://www.thegoodshoppingguide.com/ethical-credit-cards/
