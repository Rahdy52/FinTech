# OPEN BANKING: BASIQ
* This research is about open banking, featuring one of the pioneering companies called Basiq. There will be no in-depth discussion on this one because this is only used for school assignment and the main purpose is to just be able to learn stuff such as Github, Dillinger.io, and Markdown, and of course, to pass the course. So don't expect anything useful, rather, pray that I pass this one.
## Overview and Origin

* Basiq is an account aggregator company. It develops an open banking platform that facilitate the creation and rendering of financial solutions like account verification, credit scoring, credit risk assessment, wealth management, and other related services. It was founded in 2016 by Damir Cuca and is based in Manly, Australia.

* Basiq was born out of a frustration with the status quo when its founder, Damir Cuca, couldn't get bank connectivity, secure data access or access to other banking services when he began developing a budgeting app in mid-2015.

* In March 2023, Basiq was acquired by Cuscal. The terms of the transaction were not disclosed. Other investors include Nab Ventures, Salesforce Ventures, Westpac’s Reinventure

## Business Activities

* Many financial applications require aggregating a consumer’s data from banks and financial institutions to deliver their services to market. Financial data such as account balances, transactions, and other information is used for a wide range of use cases across areas such as lending, investment, Buy Now Pay Later (BNPL) and many other fintech services. Open Banking and web connectors are two different data connectivity methods to access financial data, with both methods using application programming interfaces (APIs) to extract the data. Basiq aims to solve the issues encountered by consumers in web connectors. Below lists the benefits of Open Banking v Web Connectors:

* Web Connectors
* Web connectors (often referred to as Digital Data Capture or screen scraping), have been a widely used practice by third party service providers for decades to access and aggregate financial data from banks and financial institutions. It uses an institution’s web based interface (like their online banking platform) to login and acquire a customer’s data, with consent, using their username and password.  

* From a consumer perspective, the lack of control and security are often seen as downsides in the use of web connectors. Because a user hands over credentials in the process, it’s unclear who accepts liability if something goes wrong. 

* Furthermore, as web connectors rely on the institution’s interface, any updates made can impact a service provider’s ability to access this data, even with consent, making it difficult to deliver their service to market. It is why many countries, including Australia, have moved towards Open Banking as the preferred option.

* Open Banking

* Open Banking has been implemented as part of the Government’s rollout of the Consumer Data Right (CDR) program. The CDR is an initiative aimed at driving competition and the development of new financial products and services. It gives consumers greater control over their data and the ability to securely share their data for specific purposes, such as using a personal finance management app or applying for a loan. 

* Open Banking uses open APIs to enable approved service providers to access and aggregate data from banks and financial institutions. It uses an authentication process that does not require the consumer to disclose their login and password details. 

* One of the major advantages of using Open Banking APIs is that the data received is more structured, thus reducing time-to-development (especially when retrieving data from multiple financial institutions). It also provides prescribed guidance on the handling of data and reduces the potential of misinterpretation.

* Basiq has recently announced Pearler, Way Forward, The Payment App, Otivo and Fonto as new customers under the CDR Representative model who can now access Open Banking data. Basiq becomes the first Unrestricted Accredited Data Recipient (ADR) to provide access to both CDR and non-CDR data for customers under this arrangement. The adoption of the CDR Representative model shows that fintechs are keen to access and use Open Banking data. As an Open Finance platform that provides access to Open Banking, Basiq supports a number of use cases including lending, wealth & investing, bnpl, personal financial management, charities and payments. The new customers announced demonstrate the breadth with which financial data is used in providing a fintech service across a variety of segments.

* One of the ways Basiq has simplified access is through its recent announcement on its platform upgrade. The Basiq 3.0 platform helps deliver a more complete picture of end-users, minimising complexity by providing a single API to access multiple data sources. Using a platform such as Basiq that can access CDR and non-CDR data is important while Open Banking is in a transitory stage. Not only does Basiq 3.0 access CDR Open Banking, the platform also provides connectivity to financial institutions that are not yet part of Open Banking such as alternate lenders, card issuers, investments and BNPL services. To implement this platform Basiq uses APIs, SAAS, and Data Encryption - 256-bit AES, SSL/TLS secure tunnel, MFA, OWASP, among other tools and technologies.


## Landscape

* Basiq belongs to the open banking domain of the financial industry.It is an innovation in financial services sector that is anchored on federal legislation known as the Consumer Data Right (CDR) in Australia. (CDR is an initiative to drive competition and development of new financial products and services by laying out granular, consent-driven set of rules that allows consumers to share their data with accredited third parties.)

* The foreseen benefits are:
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

* Access Models:
1. Unrestricted Accredited Data Receptient (ADR) - provides full unrestricted access to receive raw CDR data.
2. Sponsored Affiliate - allows organisation to gain access to CDR data by using an unrestricted ADR as a sponsor.
3. Principal Representative - there is no official accreditation required as the responsibility of the data is placed squarely on the ADR. 
4. Trusted Advisor - targeted access to specific data with the customer’s consent through an unrestricted ADR.
5. CDR Insights Model - non-accredited parties would receive low-risk insights and data which would benefit their customers in specific ways.
6. Outsourced Service Provider - An outsourcing arrangement must exist between the ADR and OSP.

* Open Banking will foster innovation and competition which benefits businesses and consumers. What made the concept feasible in Australia was the Murray (2014) and Harper (2015) reviews, followed by the Federal Government’s 2017 commission’s inquiry into Data Availability, which later triggered the Farrell report the following year which proposed the establishment of the CDR. This sparked the beginning of the CDR rollout which has matured over the years with an increasing number of participants joining the Open Banking ecosystem. Since then Open Banking has reshaped the banking sector through extending the reach and convenience of traditional banking services by opening up and leveraging consumer data. This disruption is both challenging and changing the nature of established banks and banking as until recently, web connectors were the most reliable way to access customer banking data. Now Open banking connects non-banking financial companies (NBFCs) and banks to provide customers with custom and more accessible financial services. Banking application programming interfaces (APIs) enable third-party developers to securely access customer financial data without compromising data compliance.  Additionally, APIs from banks allow NBFCs to integrate banking functionality into their apps and services. This embedded banking enables NBFCs to verify customer information automatically, reducing the need for manual verification and accelerating customer verification. Moreover, open banking enables banking-as-a-service (BaaS) that allows banks to reach new customers through third parties and increase their revenue.

* The other major players in this domain include Frollo, Budget Insight, and Mogoplus.

## Results

* Basiq' business impact as an account aggregator is coming up with a platform that allows customers to manage all their banking accounts through a single platform. As regards performance, the core metrics that companies in this domain use to measure success are business participants, API calls, and Average availability and Basiq boasts 110 businesses enabled to use Open Banking data including ADRs and alternate access models, 57 million monthly calls made to access banking data, and 98.60% rate of success when consumers try to share their CDR data with accredited data recipients. That said, it is one of the leading companies in this domain.

## Recommendations

* Basiq should develop an API for users to offer their clients a personalized management tool for their real-time, tailor-made finance. Users choose the bank, assets, invoices, and budget management options to customize it to their needs. Offering this product or service would benefit the company as this expands their scope to data management. The technologies that this concept will utilise will be the same ones that the company is already using.


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
https://www.cbinsights.com/compare/basiq-vs-budget-insight
