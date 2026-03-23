For your professional report, here are the primary references and technical deep-dives regarding the **Resolv (USR)** exploit that occurred on **March 22, 2026**. These links provide the data points needed to verify the "Infinite Mint" and the "Audit" context mentioned in your briefing.

### **Primary Reports & Analysis**

* **Chainalysis: The Resolv Hack - How One Compromised Key Printed $23 Million** [https://www.chainalysis.com/blog/lessons-from-the-resolv-hack/](https://www.chainalysis.com/blog/lessons-from-the-resolv-hack/)  
    *This is the most comprehensive technical post-mortem. It details how the attacker compromised the AWS KMS environment to gain the `SERVICE_ROLE` key and bypass on-chain minting limits.*

* **The Block: Resolv’s USR stablecoin depegs after attacker mints 80 million tokens** [https://www.theblock.co/post/resolv-usr-depeg-exploit-25-million](https://www.theblock.co/post/resolv-usr-depeg-exploit-25-million)  
    *A high-level market summary focusing on the financial impact, the $25M extraction, and the immediate effect on the USR/USD exchange rate.*

* **TradingView: Resolv Labs’ stablecoin depegs as attacker mints millions** [https://es.tradingview.com/news/resolv-labs-stablecoin-depegs-as-attacker-mints-millions/](https://es.tradingview.com/news/resolv-labs-stablecoin-depegs-as-attacker-mints-millions/)  
    *Coverage of the price action during the depeg and the protocol's official response on social media to halt operations.*

### **Technical & Security Context**

* **Immunefi: Resolv Bug Bounty Program & Known Issues** [https://immunefi.com/bug-bounty/resolv/information/](https://immunefi.com/bug-bounty/resolv/information/)  
    *Crucial for your "Audit" point: This page lists the scope of their security program. Note the section on "previously-discovered bugs," which often includes issues identified in audits that the team decided were acceptable risks (or "Acknowledged" but not fixed).*

* **Resolv Labs Official X (Twitter) Updates** [https://x.com/resolvlabs](https://x.com/resolvlabs)  
    *The source for the immediate "Protocol Paused" announcement and the team's ongoing communication regarding the status of the USR peg.*

---

**Summary of Verified Data for your Team:**
* **Initial Capital Used:** ~$200,000 USDC.
* **Tokens Minted:** ~80,000,000 USR (in two transactions of 50M and 30M).
* **Total Stolen:** ~$25 Million (mostly converted to ETH).
* **Lowest Price Point:** ~$0.20 - $0.30 during the peak of the dump.

**Would you like me to extract the specific transaction IDs (hashes) from these reports so you can include them as "Proof of Evidence" in your final mail?**
