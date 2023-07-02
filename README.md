# OPEN BANKING: BASIQ
This research is about open banking, featuring one of the pioneering companies called Basiq. There will be no in-depth discussion on this one because this is only used for school assignment and the main purpose is to just be able to learn stuff such as Github, Dillinger.io, and Markdown, and of course, to pass the course. So don't expect anything useful, rather, pray that I pass this one.
## Overview and Origin
**Open Banking**
It is an innovation in financial services sector that is anchored on federal legislation known as the Consumer Data Right (CDR) in Australia. (CDR is an initiative to drive competition and development of new financial products and services by laying out granular, consent-driven set of rules that allows consumers to share their data with accredited third parties.)

The foreseen benefits are:
For Businesses
1. Zero overhead from manual integration with a number of financial institutions;
2. Levels the playing field in creating new products and services due to equal access to consumer data;
For Consumers
1. Simplification of switching banks and sharing information;
2. Use case for signing up for new credit or debit card, manage joint accounts, apply for investment loans, and utilise financial products and budgeting tools.
3. More enjoyable interactive experience;
For Fintechs, Banks and Other Organisations
1. Allows smaller companies and financial institutions equal access to market;
2. easier to initiate consumer data sharing between data holders and data recipients;

Access Models:
1. Unrestricted Accredited Data Receptient (ADR) - provides full unrestricted access to receive raw CDR data.
2. Sponsored Affiliate - allows organisation to gain access to CDR data by using an unrestricted ADR as a sponsor.
3. Principal Representative - there is no official accreditation required as the responsibility of the data is placed squarely on the ADR. 
4. Trusted Advisor - targeted access to specific data with the customer’s consent through an unrestricted ADR.
5. CDR Insights Model - non-accredited parties would receive low-risk insights and data which would benefit their customers in specific ways.
6. Outsourced Service Provider - An outsourcing arrangement must exist between the ADR and OSP.

**Basiq**
Basiq is an account aggregator company. It develops an open banking platform that facilitate the creation and rendering of financial solutions like account verification, credit scoring, credit risk assessment, wealth management, and other related services. It was founded in 2016 by Damir Cuca and is based in Manly, Australia.

Basiq was born out of a frustration with the status quo when its founder, Damir Cuca, couldn't get bank connectivity, secure data access or access to other banking services when he began developing a budgeting app in mid-2015.

In March 2023, Basiq was acquired by Cuscal. The terms of the transaction were not disclosed. Other investors include Nab Ventures, Salesforce Ventures, Westpac’s Reinventure

## Business Activities

* What specific financial problem is the company or project trying to solve?
Many financial applications require aggregating a consumer’s data from banks and financial institutions to deliver their services to market. Financial data such as account balances, transactions, and other information is used for a wide range of use cases across areas such as lending, investment, Buy Now Pay Later (BNPL) and many other fintech services. Open Banking and web connectors are two different data connectivity methods to access financial data, with both methods using application programming interfaces (APIs) to extract the data.



Web connectors (or screen scraping)

Web connectors (often referred to as Digital Data Capture or screen scraping), have been a widely used practice by third party service providers for decades to access and aggregate financial data from banks and financial institutions. It uses an institution’s web based interface (like their online banking platform) to login and acquire a customer’s data, with consent, using their username and password.  

From a consumer perspective, the lack of control and security are often seen as downsides in the use of web connectors. Because a user hands over credentials in the process, it’s unclear who accepts liability if something goes wrong. 

Furthermore, as web connectors rely on the institution’s interface, any updates made can impact a service provider’s ability to access this data, even with consent, making it difficult to deliver their service to market. It is why many countries, including Australia, have moved towards Open Banking as the preferred option.



Open Banking

Open Banking has been implemented as part of the Government’s rollout of the Consumer Data Right (CDR) program. The CDR is an initiative aimed at driving competition and the development of new financial products and services. It gives consumers greater control over their data and the ability to securely share their data for specific purposes, such as using a personal finance management app or applying for a loan. 

Open Banking uses open APIs to enable approved service providers to access and aggregate data from banks and financial institutions. It uses an authentication process that does not require the consumer to disclose their login and password details. 

One of the major advantages of using Open Banking APIs is that the data received is more structured, thus reducing time-to-development (especially when retrieving data from multiple financial institutions). It also provides prescribed guidance on the handling of data and reduces the potential of misinterpretation.
* Who is the company's intended customer?  Is there any information about the market size of this set of customers?
* Basiq has today announced Pearler, Way Forward, The Payment App, Otivo and Fonto as new customers under the CDR Representative model who can now access Open Banking data. Basiq becomes the first Unrestricted Accredited Data Recipient (ADR) to provide access to both CDR and non-CDR data for customers under this arrangement. The adoption of the CDR Representative model shows that fintechs are keen to access and use Open Banking data. As an Open Finance platform that provides access to Open Banking, Basiq supports a number of use cases including lending, wealth & investing, bnpl, personal financial management, charities and payments. The new customers announced demonstrate the breadth with which financial data is used in providing a fintech service across a variety of segments.

* What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilise?)
One of the ways Basiq has simplified access is through its recent announcement on its platform upgrade. The Basiq 3.0 platform helps deliver a more complete picture of end-users, minimising complexity by providing a single API to access multiple data sources. Using a platform such as Basiq that can access CDR and non-CDR data is important while Open Banking is in a transitory stage. Not only does Basiq 3.0 access CDR Open Banking, the platform also provides connectivity to financial institutions that are not yet part of Open Banking such as alternate lenders, card issuers, investments and BNPL services.
* Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing–– you may want to search the company’s engineering blog or use sites like StackShare to find this information.)
* APIs, SAAS, Data Encryption - 256-bit AES, SSL/TLS secure tunnel, MFA, OWASP


## Landscape

* What domain of the financial industry is the company in?
Openbanking
* What have been the major trends and innovations of this domain over the last 5–10 years?
* Open Banking will foster innovation and competition which benefits businesses and consumers. What made the concept feasible in Australia was the Murray (2014) and Harper (2015) reviews, followed by the Federal Government’s 2017 commission’s inquiry into Data Availability, which later triggered the Farrell report the following year which proposed the establishment of the CDR. This sparked the beginning of the CDR rollout which has matured over the years with an increasing number of participants joining the Open Banking ecosystem.
* Open Banking has reshaped the banking sector through extending the reach and convenience of traditional banking services by opening up and leveraging consumer data. This disruption is both challenging and changing the nature of established banks and banking. 
Until recently, web connectors were the most reliable way to access customer banking data. However, big external changes have seriously impacted businesses relying on this data method to connect with banks and service their customers.
Open banking connects non-banking financial companies (NBFCs) and banks to provide customers with custom and more accessible financial services. Banking application programming interfaces (APIs) enable third-party developers to securely access customer financial data without compromising data compliance. Open banking also includes account aggregators that allow customers to manage all their banking accounts through a single platform. Additionally, APIs from banks allow NBFCs to integrate banking functionality into their apps and services. This embedded banking enables NBFCs to verify customer information automatically, reducing the need for manual verification and accelerating customer verification. Moreover, open banking enables banking-as-a-service (BaaS) that allows banks to reach new customers through third parties and increase their revenue.
* What are the other major companies in this domain?
Frollo, Budget Insight, Mogoplus

## Results

* What has been the business impact of this company so far?
Influences the data facilitation 
* What are some of the core metrics that companies in this domain use to measure success? How is your company performing, based on these metrics?
Data holder brands, banks providing access to open Banking Data, business participants, API calls, Average availability
* How is your company performing relative to competitors in the same domain?


## Recommendations

* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)

* Why do you think that offering this product or service would benefit the company?

* What technologies would this additional product or service utilise?

* Why are these technologies appropriate for your solution?

REFERENCES
https://www.basiq.io/blog/banking-data-access-is-changing-and-businesses-need-to-prepare/
https://australianfintech.com.au/basiq-four-new-use-cases-for-open-bankings-future/
https://www.basiq.io/blog/author/shannon-renniebasiq-io/
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3766076
https://www.startus-insights.com/innovators-guide/banking-technology-trends/#open-banking
https://www.basiq.io/blog/basiq-announces-five-new-customers-to-access-open-banking/
https://www.basiq.io/blog/the-definitive-guide-to-open-banking-in-australia/
https://www.basiq.io/blog/comparing-open-banking-and-web-connectors/
https://www.fintechaustralia.org.au/newsroom/basiq-announces-five-new-customers-to-access-open-banking
