Download Link: https://assignmentchef.com/product/solved-cind110-assignment1-on-modeling-a-relational-database
<br>
<ol>

 <li>Clients are individual investors who buy Financial Securities (FS) as investments. They do this through financial advisers.</li>

 <li>Clients are identified by a SIN, and their names, addresses, and ages must be recorded.</li>

 <li>Financial advisers are professional investment agents who contact clients and recommend FS for them to buy.</li>

 <li>Financial advisers are identified by a SIN. For each adviser, the name, specialty, and years of experience must be recorded.</li>

 <li>Every client has a primary financial adviser. Every adviser has at least one client.</li>

 <li>Financial Security Issuers (FSI) are companies that are listed in the exchange and offer FS for investors to buy. Examples of FSI are IBM, Microsoft, TELUS, etc.</li>

 <li>Each financial security issuer is identified by name and has a phone number.</li>

 <li>For each financial security, the trade name and symbol must be recorded.</li>

 <li>Each security is sold by a given issuer, and the trade name identifies a security uniquely from among the products of that issuer. If an issuer is deleted, you need not keep track of its products any longer.</li>

 <li>An exchange is a marketplace in which securities, commodities, derivatives and other financial instruments are traded.</li>

</ol>

1

<ol start="11">

 <li>Each exchange has a name, address, and phone number.</li>

 <li>Each exchange lists several securities and has a price and currency for each. A security could be listed at several exchanges, and the price could vary from one exchange to another.</li>

 <li>Financial advisers recommend securities for clients. An adviser could recommend one or more securities for several clients, and a client could obtain recommendations from several advisers.</li>

 <li>Each recommendation has a date and a quantity associated with it. You can assume that, if an adviser recommends the same security for the same client more than once, only the last such recommendation needs to be stored.</li>

 <li>Issuers have long-term contracts with exchanges. An issuer can contract with several exchanges, and an exchange can contract with several issuers. For each contract, you have to store a start date, an end date, and the text of the contract.</li>

</ol>

Definitions: Here are links for more details about the terminology used for this assignment:

<ol>

 <li>Financial Securities: <a href="http://www.investopedia.com/terms/s/security.asp">http://www.investopedia.com/terms/s/security.asp</a></li>

 <li>Listed Security: <a href="http://www.investopedia.com/terms/l/listedsecurity.asp">http://www.investopedia.com/terms/l/listedsecurity.asp</a></li>

 <li>Financial Security Issuer: <a href="http://www.investopedia.com/terms/i/issuer.asp">http://www.investopedia.com/terms/i/issuer.asp</a></li>

 <li>Trade Name: <a href="https://en.wikipedia.org/wiki/Trade_name">https://en.wikipedia.org/wiki/Trade_name</a></li>

 <li>Financial Advisor: <a href="http://www.investopedia.com/terms/f/financial-adviser.asp">http://www.investopedia.com/terms/f/financial-adviser. </a><a href="http://www.investopedia.com/terms/f/financial-adviser.asp">asp</a></li>

 <li>Exchange: <a href="http://www.investopedia.com/terms/e/exchange.asp">http://www.investopedia.com/terms/e/exchange.asp</a></li>

 <li>Ticker Symbol: <a href="http://www.investopedia.com/terms/t/tickersymbol.asp">http://www.investopedia.com/terms/t/tickersymbol.asp</a></li>

</ol>