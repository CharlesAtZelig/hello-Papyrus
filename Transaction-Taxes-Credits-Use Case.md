#Xalgorithms Use Case - Transaction Taxes/Credits -- One=Pass Tax

##Background

Katla, A musician from Reykjavík, Iceland, travels to perform at the Montreal Jazz Festival. On arrival she finds her almost-new guitar damaged in transit. Full reimbursement assured, her more immediate problem is to keep her concert schedule two days later. She contacts the manufacturer in Nashville to have a new guitar sent by courier to Montreal. The vendor’s e-commerce site, enhanced with Lichen Xalgorithms, recognizes her identity, the product code and jurisdictions, and pulls in the relevant tax and duty rules. The correct amounts are paid directly to the Icelandic revenue agency, and the shipping manifest validates that this courier package is pre-cleared for Canadian customs. She receives her replacement guitar in time for the concert. Furthermore, she is free from the hassle of claiming back Canadian tax at the airport upon departure, or paying Icelandic sales tax upon arrival back in Reykjavík. The required taxes and duties were dealt with all in one pass.

##Preconditions
* User's guitar was damaged in transit

##Use Case

* Katla logs on to guitar manufacturer's e-commerce site
* Katla selects a new guitar and arange for a delivery to Montreal
* The manufacturer's e-commerce site, enhanced with Lichen, recognizes Katla's identity, the product code, and the various jurisdictions involved, and displays the relevant taxes and duties.
  - use "Lichen" use case, TBD
* Katla reviews all this information and buys the guitar.

##PostConditions
* Guitar delivery is accelerated as all fees (e.g. shipping, customs, etc.) are pre-paid and Katla gets the guitar in time to perform at the concert.
* Because the system also knew that Katla is a resident of Iceland, all duties to bring the new guitar into Iceland have been paid, making Katla's return Iceland worry-free.
 