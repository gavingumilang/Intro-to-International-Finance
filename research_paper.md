# Geopolitical Arbitrage or Industrial Integration? Chinese Greenfield FDI in Southeast Asia's EV Sector Following US Tariff Shocks

**Shkapich Hanna | Antunez Giachero Maria Pia | Dohyun JU | Gumilang Gavin | Do Khanh Linh | Alicia Arquier**

*Topics in International Macroeconomics — Yonsei University, Spring 2026*

---

## Abstract

This paper investigates whether Chinese greenfield foreign direct investment (FDI) in the electric vehicle (EV) and battery sectors surged into Southeast Asian "connector countries" — specifically Thailand, Indonesia, and Vietnam — in direct response to two US tariff escalation events: the 2018 Section 301 tariffs and the May 2024 Biden administration's 100% EV tariff. Using a Poisson Pseudo-Maximum Likelihood (PPML) gravity model with an event study framework, we test whether these policy shocks triggered statistically significant spikes in Chinese project-level greenfield investment beyond what baseline gravity variables would predict. Drawing on publicly available investment trackers, host-country board of investment data, and the academic literature, we find strong descriptive evidence consistent with the "geopolitical arbitrage" hypothesis: Chinese EV manufacturers significantly accelerated their ASEAN investment activity in windows immediately following both tariff events, with Thailand and Indonesia receiving the largest announced project volumes. Formal regression results are limited by restricted access to project-level fDi Markets data (noted explicitly as a data limitation), but our descriptive and event-window analysis supports the view that US tariff escalation — rather than organic host-country pull factors alone — is a primary driver of China's strategic FDI redirection. These findings challenge the "friend-shoring" hypothesis and have significant implications for US trade enforcement, ASEAN industrial policy, and the global EV supply chain architecture.

**Keywords:** greenfield FDI, geopolitical arbitrage, connector countries, electric vehicles, US-China trade war, friendshoring, PPML gravity model, event study

---

## 1. Introduction

The US-China trade war, which escalated decisively in 2018 with the imposition of Section 301 tariffs on over $360 billion of Chinese goods, triggered a fundamental reorganization of global production and investment networks. While the immediate effect on bilateral US-China trade flows has been extensively documented, a second-order consequence has received comparatively less empirical scrutiny: the strategic redirection of Chinese outbound FDI toward third-party countries capable of serving as conduits to the US market.

This "geopolitical arbitrage" strategy involves Chinese firms establishing or expanding manufacturing operations in Southeast Asian economies — most notably Thailand, Indonesia, and Vietnam — which maintain preferential trade access to the United States and the European Union. From this vantage point, Chinese-origin products can be assembled, processed, or re-exported with altered country-of-origin certification, effectively circumventing the tariff wall. The phenomenon is particularly acute in the EV and battery sector, where China holds dominant first-mover advantages across the entire supply chain, from upstream lithium and nickel processing to cell manufacturing and vehicle assembly.

The stakes intensified dramatically in May 2024 when the Biden administration announced a 100% tariff on Chinese-made electric vehicles — quadrupling the previous rate — alongside elevated duties on Chinese batteries, solar cells, and semiconductors. This second shock provides a rare natural experiment: a sector-specific, high-magnitude policy announcement with a precise date, directed at an industry where Chinese global market power is most visible.

This paper asks: **Does Chinese greenfield FDI into Southeast Asian connector countries in the EV and battery sectors spike immediately following these specific US tariff escalation events?** We answer this question through a PPML gravity model augmented with event-study dummies, treating each tariff announcement as an exogenous shock and measuring the differential FDI response in connector countries relative to non-connector destinations.

Beyond its empirical contribution, this paper addresses a fundamental theoretical tension. The dominant "friend-shoring" hypothesis — advanced by policymakers in Washington and Brussels and formalized by Aiyar et al. (2023) — predicts that geopolitical fragmentation should channel investment flows along alliance lines. Capital should flow to geopolitically proximate partners. Yet the observed pattern appears to be the opposite for Chinese firms: they are aggressively investing in economies that vote with the US in UN resolutions and participate in US-aligned security frameworks, precisely because these countries offer the tariff arbitrage opportunity. Understanding whether this pattern represents durable industrial integration or shallow assembly for circumvention is among the most consequential questions in contemporary international trade economics.

The remainder of this paper proceeds as follows. Section 2 reviews the relevant literature. Section 3 develops the theoretical framework. Section 4 describes the empirical methodology. Section 5 presents our data sources and notes key limitations. Section 6 presents descriptive evidence and event-window analysis. Section 7 discusses the regression framework and expected findings. Section 8 concludes with policy implications.

---

## 2. Literature Review

### 2.1 Geopolitical Fragmentation and FDI Flows

The systematic relationship between geopolitical alignment and capital flows has emerged as a central research agenda in international macroeconomics since 2018. Aiyar, Malacrino, and Presbitero (2023) provide the foundational gravity-model analysis, using bilateral Ideal Point Distance (IPD) — derived from UN General Assembly voting patterns — as a proxy for geopolitical distance. Their IMF Working Paper finds that a one-standard-deviation increase in geopolitical distance reduces bilateral FDI by approximately 15%, with the effect intensifying markedly after 2018. Crucially, they establish that this "geopolitical discount" on FDI operates over and above standard gravity variables such as geographic distance, GDP, and bilateral trade openness.

Aiyar and Ohnsorge (2024) extend this analysis to the concept of "geoeconomic fragmentation" and introduce the role of "connector countries" — economies that maintain strong economic ties with both the US-led and China-led blocs simultaneously. Using a structural gravity framework, they demonstrate that connector countries can partially substitute for direct inter-bloc linkages, thereby mitigating some of the aggregate output losses that would otherwise result from full economic decoupling. Thailand, Indonesia, and Vietnam feature prominently in their empirical identification of connector countries, given their high scores on what Gopinath et al. (2024) term the "geoeconomic connectedness" index.

### 2.2 The Friend-Shoring Hypothesis and Its Discontents

The friend-shoring concept — the explicit policy preference for sourcing from geopolitically aligned partners — gained traction in US policymaking discourse from 2021 onward, championed by Treasury Secretary Janet Yellen among others. Theoretically, it predicts a bifurcation of global supply chains into Western-aligned and China-aligned blocs, with capital following geopolitical alignment.

The empirical evidence on this prediction is mixed in illuminating ways. Grover and Vézina (2025), in a World Bank working paper using project-level greenfield investment data from fDi Markets covering 2003–2023, find that while Western multinational firms do indeed exhibit friend-shoring behavior — significantly increasing their investment in geopolitically proximate economies after 2018 — Chinese firms do precisely the opposite. Chinese companies have systematically *increased* their investment in economies that are geopolitically closer to the US (i.e., higher IPD from China), particularly in manufacturing sectors. This finding directly motivates our research: rather than retreating to geopolitically "safe" partners, Chinese firms are strategically investing in the opposing bloc's preferred partners.

Valdiglesias (2025) offers a complementary perspective through a panel data analysis of export performance and supply chain realignment during the US-China trade conflict. The study shows that geographic proximity and strategic alignment jointly determine where supply chains relocate, but that the effect is asymmetric: for Chinese firms facing tariff walls, the economic incentive to invest in geopolitically distant but tariff-advantaged economies frequently overrides the preference for geopolitical comfort.

### 2.3 The "Great Reallocation" and Connector Countries

Alfaro and Chor (2023) document what they term the "Great Reallocation" of US import sourcing — a substantial shift away from Chinese suppliers toward Vietnam, Mexico, and other third-party countries. Using detailed US import data at the HS-10 product level, they demonstrate that while bilateral US-China trade in manufactured goods fell sharply after 2018, the countries absorbing the reallocation maintained strong upstream input linkages with China. The implication is stark: the US supply chain has de-coupled from China bilaterally but remains coupled with it indirectly through connector countries. Vietnamese and Mexican exports to the US increasingly contain high Chinese-origin content.

This finding has direct relevance for our study. If the Great Reallocation is partly driven by Chinese FDI in connector countries — that is, if Chinese firms established manufacturing capacity in Vietnam and Thailand precisely to serve the US market through a third-country conduit — then the timing of that FDI should correlate with US tariff escalation events. Our empirical strategy is designed to test exactly this timing relationship.

### 2.4 China's EV Sector and Outbound Investment

The EV and battery sector represents an especially important application domain for several reasons. First, China has achieved a dominant global position across the EV value chain through a combination of state industrial policy, massive domestic market scale, and decade-long investment in battery chemistry and manufacturing. As of 2024, China accounted for approximately 60% of global EV production, and Chinese firms — led by BYD, CATL, SAIC, Great Wall Motor, and Chery — hold commanding positions in both vehicle manufacturing and battery cell production (IEA Global EV Outlook, 2025).

Second, this dominance makes the sector a primary target of US and EU trade defense measures. The May 2024 100% US EV tariff was explicitly framed as a response to Chinese industrial subsidization and the perceived threat to nascent US and EU EV industries. The EU followed with its own countervailing duty investigation and provisional tariffs of up to 48% on Chinese-made EVs in 2024.

Third, Southeast Asia has become the primary theater for Chinese EV FDI. Thailand's Board of Investment (BOI) had approved investments from over 10 Chinese EV and battery manufacturers by end-2024, including BYD, Great Wall Motor, SAIC-CP, Hozon (Neta), and battery makers CATL and Sunwoda. Indonesia's nickel reserves — the world's largest — have attracted massive Chinese battery supply chain investment, with firms including CATL (via PT CSIA and battery parks in Java), EVE Energy, and Gotion High-Tech committing multi-billion dollar projects. Vietnam has attracted investment from VinFast (domestic), but also Chinese battery supply chain actors, though the regulatory environment has been more selective.

Huang and Xia (2024) from BBVA Research contextualize this pattern within China's "involution" dynamic: intense domestic price competition in the Chinese EV market, driven by BYD's aggressive pricing strategy, has compressed margins and created strong incentives for Chinese OEMs to seek offshore manufacturing to access new markets and reduce reliance on the increasingly constrained Chinese domestic profit pool. This domestic push factor interacts with the tariff-driven pull factor to create what Dai and Tang (2024) characterize as a "de-risking" investment strategy.

### 2.5 Identifying the Gap

While the existing literature has established robust aggregate relationships between geopolitical alignment and FDI (Aiyar et al., 2023), documented the friend-shoring behavior of Western firms (Grover & Vézina, 2025), and characterized the role of connector countries (Gopinath et al., 2024), a specific gap remains. No existing study has:

1. Isolated the **sector-specific** response to the **2024 100% EV tariff** — the most recent and highest-magnitude shock — on greenfield FDI in the EV/battery industry;
2. Applied a **high-frequency event study** design to test whether FDI spikes are **immediately causally linked** to tariff announcements rather than driven by longer-run structural trends;
3. Distinguished between **greenfield investment** (new production capacity) and M&A activity, which is crucial for identifying whether Chinese firms are building new factories to serve as tariff-circumvention platforms versus acquiring existing assets.

This paper addresses all three gaps.

---

## 3. Theoretical Framework

### 3.1 The Geopolitical Arbitrage Model

We conceptualize Chinese EV FDI in Southeast Asia as a two-stage optimization problem. In the first stage, the firm chooses whether to serve a foreign market (e.g., the US or EU) via direct exports from China or via a third-country production platform. In the second stage, conditional on the third-country platform strategy, the firm chooses the host country *j* that minimizes the combined cost of production, logistics, tariffs, and regulatory risk.

The introduction of a high US tariff *τ* on Chinese-origin EVs creates a discrete shift in the payoff to the third-country platform strategy. Specifically, the expected profit from routing production through connector country *j* becomes:

**π(j) = p_US − c_j − t_j − τ_j(RoO)**

where *p_US* is the US market price for EVs, *c_j* is the production cost in country *j* (including labor, energy, and input costs), *t_j* is logistics and distribution cost, and *τ_j(RoO)* is the effective tariff burden in country *j*, which depends on its rules-of-origin (RoO) compliance relative to US trade agreements.

When the US imposes a tariff on Chinese-made EVs (increasing *τ_China*), the relative advantage of third-country platforms increases discontinuously, creating an incentive for Chinese firms to invest in greenfield production capacity in connector countries. The speed of this investment response — whether it occurs in quarters or years — is the central empirical question.

### 3.2 Why Connector Countries?

Three features make Thailand, Indonesia, and Vietnam optimal connector countries for Chinese EV firms:

**Tariff access:** All three countries benefit from WTO Most Favored Nation (MFN) status with the US and are not subject to the Section 301 or Section 232 tariffs applied to China. None faces the 100% EV-specific tariff.

**RCEP membership:** All three are signatories to the Regional Comprehensive Economic Partnership, facilitating Chinese firms' access to regional supply chains and simplifying input sourcing from China with preferential origin rules within the bloc.

**Host-country industrial policy:** Thailand's "EV 3.5" policy (2021–2025) offers zero import duty on CBU EVs from countries with FTA coverage, tax holidays, and land grants to manufacturers committing to local production. Indonesia's downstream processing requirements for nickel align with Chinese battery manufacturers' need for vertically integrated local supply chains. Vietnam's manufacturing boom makes it attractive for lower-end assembly operations.

**Geopolitical ambiguity:** All three countries score relatively high on "geoeconomic connectedness" — they trade heavily with both the US and China and have avoided formal alignment in the US-China rivalry, making them acceptable platforms from the perspective of US trade enforcement (though this is increasingly under scrutiny).

---

## 4. Methodology

### 4.1 The PPML Gravity Model

We estimate a Poisson Pseudo-Maximum Likelihood (PPML) gravity model, following Santos Silva and Tenreyro (2006), which is the econometric standard for count and value data with many zero bilateral observations — a characteristic feature of project-level FDI data. The baseline specification is:

**FDI_ijt = exp(β₁ · TariffEvent_t × Connector_j + β₂ · IPD_ij,t-1 + γ · X_ij + α_it + δ_jt) · ε_ijt**

where:

- **FDI_ijt** is the count or value of Chinese greenfield FDI projects in the EV and battery sectors (ISIC Rev. 4 codes 2910, 2720) flowing from China (*i*) to country *j* at annual or quarterly time *t*
- **TariffEvent_t** is a set of event dummy variables: *Tariff2018_t* equals 1 for the two quarters following July 2018 (Section 301 implementation); *Tariff2024_t* equals 1 for the two quarters following May 2024 (100% EV tariff announcement)
- **Connector_j** is an indicator variable equal to 1 for Thailand, Indonesia, and Vietnam, and 0 for a comparison group of non-connector developing country destinations
- **TariffEvent_t × Connector_j** is the interaction term of primary interest — it captures the differential FDI response in connector countries relative to other destinations at the time of each tariff shock
- **IPD_ij,t-1** is the lagged bilateral Ideal Point Distance from Bailey, Strezhnev, and Voeten (2017), measuring geopolitical distance between China and host country *j*
- **X_ij** is a vector of standard gravity controls: log bilateral geographic distance (CEPII), common language dummy, RCEP membership indicator, and log host-country GDP per capita
- **α_it** are origin-year fixed effects (absorbing all time-varying China-specific factors, including domestic EV market conditions and capital controls)
- **δ_jt** are destination-year fixed effects (absorbing all time-varying host-country factors, including Thailand's EV 3.5 policy, Indonesia's downstream processing rules, and Vietnam's FDI promotion campaigns)

### 4.2 Event Study Extension

The primary PPML specification is augmented with a dynamic event study framework to trace the temporal pattern of FDI responses. We estimate:

**FDI_ijt = exp(Σ_k β_k · I(t = Event + k) × Connector_j + controls) · ε_ijt**

where *k* ranges from -4 to +8 quarters around each tariff event. The pre-event coefficients (*k < 0*) serve as a falsification test: if connector countries were already on a different FDI trajectory before the tariff shock (perhaps due to secular trends in Chinese outbound investment), the pre-event β_k coefficients would be statistically significant, threatening the causal interpretation. A clean event study would show flat pre-trends and a sharp post-event spike.

### 4.3 Identification Strategy

The key identification assumption is that, conditional on destination-year fixed effects and gravity controls, the timing of US tariff escalation events is exogenous to Chinese FDI decisions in the EV sector. This is plausible for several reasons:

1. The specific dates of tariff announcements reflect US domestic political dynamics (trade remedy investigations, Section 301 statutory timelines, presidential election cycles) rather than being calibrated in response to observable ASEAN FDI trends;
2. The 100% EV tariff of May 2024 was an unusually large discrete shock, reducing the concern that Chinese firms could have gradually anticipated and pre-positioned around it;
3. Destination-year fixed effects absorb the host-country industrial policy confounds (Thailand's EV 3.5, Indonesia's nickel downstream mandates) that could independently attract Chinese EV investment.

The main threat to identification is that Chinese firms may have been planning ASEAN EV investments for reasons unrelated to US tariffs — for example, BYD's global expansion strategy predates 2024. The dynamic event study pre-trend test is our primary tool for addressing this concern.

---

## 5. Data and Limitations

### 5.1 Primary Data Sources

| Variable | Source | Availability |
|---|---|---|
| Chinese Greenfield FDI (EV/Battery) | fDi Markets (Financial Times) | **PAID — not accessed** |
| Chinese Outbound FDI (Large Deals, ≥$100M) | AEI China Global Investment Tracker | FREE — partial proxy |
| ASEAN FDI by Sector and Origin (aggregate) | UNCTAD World Investment Report Annexes | FREE |
| Thailand BOI Approved Investment (by sector, by origin) | Thailand Board of Investment | FREE |
| Indonesia BKPM/BKID FDI Realization Data | Indonesia Investment Coordinating Board | FREE (aggregate) |
| Vietnam MPI FDI Approval Data | Ministry of Planning and Investment | FREE (aggregate) |
| Bilateral Ideal Point Distance | Bailey, Strezhnev & Voeten (2017) — Harvard Dataverse | FREE |
| Tariff event dates and rates | US Federal Register; Global Trade Alert | FREE |
| Host country GDP, LPI | World Bank Open Data API | FREE |
| Geographic distance, language | CEPII GeoDist database | FREE |

### 5.2 Critical Data Limitation: fDi Markets

The central data limitation of this study is the unavailability of the **fDi Markets** database, which is the only comprehensive source of project-level greenfield investment data with sector coding granular enough to isolate EV and battery projects. fDi Markets is a subscription product of the Financial Times Group and is not freely accessible.

Without fDi Markets, we cannot construct the panel dataset required to run the PPML regression specified in Section 4. This prevents us from reporting formal regression coefficients and standard errors for the primary specification.

**Implications for inference:** Our empirical contribution in this paper is therefore limited to: (a) a descriptive analysis of Chinese EV investment events in ASEAN using publicly available data from the AEI tracker, host-country BOI databases, and published research reports (Rhodium Group, IEA, UNCTAD); and (b) a theoretical and qualitative event study that maps announced Chinese EV investments against the tariff timeline.

**Path to resolution:** Access to fDi Markets through an institutional subscription (e.g., Yonsei University Library) or through a data-sharing arrangement with the World Bank (which uses fDi Markets for its own research, including Grover & Vézina 2025) would allow us to complete the formal econometric analysis. The AEI China Global Investment Tracker provides a free partial substitute, though its coverage threshold of USD 100 million excludes smaller greenfield projects that may be economically significant in aggregate.

### 5.3 Secondary Data Limitations

**IPD data coverage:** The Bailey et al. dataset covers UNGA voting through session 78 (2023). For quarters in 2024–2025 that fall within our event window for the May 2024 tariff shock, the most recent available IPD values (2022–2023) are used as proxies, introducing minor measurement error.

**Rules-of-Origin complexity:** Our model does not directly measure the degree to which Chinese-invested ASEAN factories genuinely satisfy US rules-of-origin requirements. Distinguishing "screwdriver assembly" from substantive manufacturing integration requires product-level value-added data that is not systematically collected.

---

## 6. Descriptive Evidence and Event-Window Analysis

Despite the regression data limitation, the publicly available record provides substantial descriptive evidence consistent with our hypothesis.

### 6.1 The 2018 Shock Window (July 2018 – December 2019)

The imposition of Section 301 tariffs beginning in July 2018, covering approximately $34 billion of Chinese goods (List 1) expanding to $200 billion (List 3) by September 2018, triggered an almost immediate acceleration in announced Chinese manufacturing investments in ASEAN:

- **Vietnam** experienced a surge in Chinese manufacturing FDI approvals beginning Q3 2018, with the Vietnam Ministry of Planning and Investment recording a 203% increase in registered Chinese FDI capital in 2019 relative to 2017. Electronics and component manufacturing dominated, but automotive-adjacent supply chain investments (wiring harnesses, EV components) were included.
- **Thailand** saw Chinese automobile and EV-related investment approvals jump sharply. Great Wall Motor signed a deal to acquire GM's Rayong plant in 2020 — a decision traceable to strategic planning initiated in the post-2018 environment.
- **Indonesia** experienced a wave of Chinese investment in nickel processing (the foundational input for EV batteries), with TSINGSHAN Holding Group's dramatic expansion of its Morowali Industrial Park from 2018 onward representing one of the largest single Chinese greenfield investments in the region.

While these investments spanned multiple sectors beyond EVs, they established the supply chain infrastructure that subsequent EV-specific investments would leverage.

### 6.2 The 2024 Shock Window (May 2024 – Present)

The May 14, 2024 announcement of 100% tariffs on Chinese EVs (and 50% on solar cells, 25% on batteries and EV components) produced a more concentrated and visible response in the EV sector specifically:

**BYD:** Announced its first dedicated overseas EV manufacturing plant in Rayong, Thailand, with groundbreaking in July 2024 and a production target of 150,000 vehicles per year. Simultaneously announced feasibility studies for plants in Indonesia and Vietnam. BYD also signed a Memorandum of Understanding with the Indonesian government for a USD 1.3 billion EV factory.

**CATL:** Accelerated its partnership with PTT (Thailand's state oil company) for a battery manufacturing facility in Thailand, with an announced investment of approximately USD 1 billion. This followed earlier commitments to an Indonesian battery plant (via PT CSIA) and discussions with the Malaysian government.

**SAIC:** Expanded production capacity at its existing MG-brand facilities in Thailand and announced new production lines oriented toward ASEAN market export.

**EVE Energy and Gotion High-Tech:** Both announced Southeast Asia battery manufacturing investments in Malaysia and Thailand in H2 2024, citing the need for tariff-insulated production bases.

The AEI China Global Investment Tracker records 7 Chinese EV and battery sector investments in ASEAN above USD 100 million in the 12-month window following the May 2024 tariff announcement, compared to 2 in the equivalent prior-year window — a more than three-fold increase. This pattern is strongly consistent with a tariff-driven investment acceleration.

### 6.3 Comparative Timeline

```
US Policy Event          | Approximate ASEAN EV FDI Response
-------------------------|------------------------------------------
Jul 2018: Section 301    | Vietnam FDI surge (2018-19); Thailand auto
List 1 ($34B)            | plant acquisitions announced (2019-20);
                         | Indonesia nickel processing boom begins.
                         |
Oct 2018: List 3 ($200B) | Supply chain diversification accelerates.
                         | Vietnam emerges as electronics hub.
                         |
May 2019: Huawei ban,    | Broader tech/manufacturing FDI redirection.
escalation               |
                         |
Jan 2020: Phase One deal | Partial pause in new announcements.
                         |
May 2024: 100% EV tariff | SECTOR-SPECIFIC spike: BYD Thailand plant,
                         | CATL Thailand battery facility, EVE Energy
                         | Malaysia, Gotion High-Tech Vietnam — all
                         | announced within 6-month event window.
```

---

## 7. Discussion: Expected Regression Results and Policy Implications

### 7.1 Expected Findings

Based on the descriptive evidence and the existing literature, we expect the following results from the formal PPML regression (pending data access):

**H1 (Main hypothesis):** The coefficient β₁ on *TariffEvent × Connector* will be positive and statistically significant for both the 2018 and 2024 events, indicating that Chinese greenfield EV FDI into connector countries spiked by more than would be predicted by baseline gravity factors following each tariff escalation. We expect the 2024 EV-specific tariff to produce a larger and faster response than the 2018 broad tariff, given its sector-specific targeting.

**H2 (IPD paradox):** The coefficient β₂ on *IPD_ij,t-1* will be positive for China-to-ASEAN EV FDI in the post-2018 period — that is, greater geopolitical distance from China (i.e., closer alignment with the US) will be associated with *more* Chinese FDI, not less. This would directly replicate the Grover and Vézina (2025) finding in a sector-specific context and confirm the theoretical prediction of our geopolitical arbitrage framework.

**H3 (Pre-trend flatness):** The dynamic event study coefficients for pre-event quarters (*k < 0*) will be statistically indistinguishable from zero, supporting the causal interpretation of the tariff shocks as drivers — rather than correlates — of the observed FDI increases.

**H4 (Heterogeneity):** The effect will be strongest for Thailand, given its more established automotive industrial ecosystem, BOI incentive structure, and proximity to Chinese supply chains via ASEAN connectivity. Indonesia may show a strong battery-sector-specific response given its nickel endowment.

### 7.2 Policy Implications

**For US trade enforcement:** If the geopolitical arbitrage hypothesis is confirmed, then the 100% EV tariff targeting Chinese-made vehicles may generate limited long-run protection for US EV producers if Chinese manufacturers successfully establish ASEAN production bases that can export tariff-free to the US. The policy response might require either (a) expanded rules-of-origin scrutiny applied to ASEAN EV exports, (b) bilateral tariff negotiations with ASEAN connector countries, or (c) a broader "China-connected" tariff framework targeting products with high Chinese-origin value content regardless of country of final manufacture.

**For ASEAN industrial policy:** The surge in Chinese EV FDI represents both an opportunity and a structural risk for ASEAN economies. On the opportunity side, countries like Thailand and Indonesia gain technology transfer, employment, and industrial upgrading in high-growth sectors. On the risk side, Lim (2026) notes that "net gains to local workers" remain uncertain — Chinese-invested factories may rely heavily on Chinese managers, engineers, and intermediate inputs, limiting domestic value-added and technology diffusion. The "screwdriver assembly" risk — shallow integration designed primarily for rules-of-origin arbitrage — would represent a missed developmental opportunity.

**For the friend-shoring framework:** Our expected findings, if confirmed, would add to a growing body of evidence that the friend-shoring hypothesis describes the behavior of Western capital but not Chinese capital. The geopolitical arbitrage strategy pursued by Chinese EV firms represents a fundamentally different response to fragmentation — one that exploits the gaps and inconsistencies in Western trade defense architecture rather than retreating from the fray. This "mutual entanglement" of Chinese and Western-aligned supply chains in ASEAN connector countries may ultimately constrain the policy options of both the US and China.

---

## 8. Conclusion

This paper has developed a theoretical framework and empirical strategy for testing the geopolitical arbitrage hypothesis in China's EV and battery sector FDI into Southeast Asia. We find compelling descriptive evidence that Chinese greenfield investment in the EV/battery sector accelerated sharply in Thailand, Indonesia, and Vietnam following both the 2018 Section 301 tariffs and the May 2024 100% EV tariff, consistent with a strategic response to US tariff escalation rather than purely organic host-country pull factors.

The formal econometric analysis using a PPML gravity model with event-study design was constrained by the unavailability of project-level fDi Markets data, which remains the primary data limitation of this study. Subject to obtaining fDi Markets access, the empirical design laid out in Section 4 would allow us to formally test whether the observed FDI spikes are statistically significant after controlling for gravity factors, destination-year fixed effects, and domestic Chinese market conditions.

Our contribution to the literature is threefold. First, we apply the geopolitical arbitrage concept to a specific, high-stakes sector — EVs and batteries — where China's supply chain dominance and the US's tariff response are most sharply in conflict. Second, we propose the first event study design specifically targeted at the May 2024 100% EV tariff shock, which existing academic literature has not yet examined at the investment-flow level. Third, we document the mechanism through which "connector countries" serve as conduits in this geopolitical arbitrage strategy, with implications for both US trade policy effectiveness and ASEAN development trajectories.

The broader insight is that economic decoupling — even when pursued aggressively through high tariff walls — may produce unintended consequences when the target country has sufficient capital and industrial capacity to adapt. China's EV firms are not retreating from the US market; they are rerouting their path to it. Understanding and responding to this adaptive strategy will be among the defining challenges of international trade policy in the decade ahead.

---

## References

Aiyar, S., Malacrino, D., & Presbitero, A. F. (2023, November). *Investing in friends: The role of geopolitical alignment in FDI flows*. IMF Working Paper WP/23/221. International Monetary Fund.

Aiyar, S., & Ohnsorge, F. (2024). *Geoeconomic fragmentation and "connector" countries*. CAMA Working Paper 53/2024. Crawford School of Public Policy, Australian National University.

Alfaro, L., & Chor, D. (2023, September). *Global supply chains: The looming "great reallocation"* (Working Paper No. 31661). National Bureau of Economic Research.

Bailey, M. A., Strezhnev, A., & Voeten, E. (2017). Estimating dynamic state preferences from United Nations voting data. *Journal of Conflict Resolution, 61*(2), 430–456.

CarbonCredits.com. (2024). *China's EV export explosion: How a domestic price war is reshaping the global auto market*. https://carboncredits.com/chinas-ev-export-explosion-how-a-domestic-price-war-is-reshaping-the-global-auto-market/

CARI. (2025, August 19). *Chinese EV manufacturers significantly expand presence in Southeast Asia*. https://cariasean.org/news/cari-captures-issue-717-chinese-ev-manufacturers-significantly-expand-presence-in-southeast-asia/

Counterpoint Research. (2024). *Thailand EV ambitions rise with policy push and Chinese OEM dominance*. https://counterpointresearch.com/en/insights/thailand-ev-ambitions-rise-with-policy-push-and-chinese-oem-dominance-1

Dai, T., & Tang, C. S. (2024). De-risking global supply chains: Looking beyond material flows. *Asia Policy, 19*(4), 153–176.

EBC Financial Group. (2026, April 16). *One country, 60% of global nickel, and a 30% cut: The shockwave hitting defense, EVs & global economy*. https://www.ebc.com/forex/one-country-60-of-global-nickel-and-a-30-cut-the-shockwave-hitting-defense-evs-and-global-economy

Fastmarkets. (2024). *Chinese automakers sign electric vehicles subsidy pact with Thailand*. https://www.fastmarkets.com/insights/chinese-automakers-sign-electric-vehicles-subsidy-pact-with-thailand/

Gopinath, G., et al. (2024). *Changing global linkages: A new cold war?* IMF Working Paper. International Monetary Fund.

Grover, A., & Vézina, P.-L. (2025). *Geopolitical fragmentation and friendshoring: Evidence from project-level foreign investment data*. World Bank Policy Research Working Paper. https://openknowledge.worldbank.org/bitstreams/0083881b-2ca1-4745-b4e3-4637dc66459d/download

Huang, B., & Xia, L. (2024, June 27). *China EV sector: Forging ahead amid intensifying headwinds*. BBVA Research.

IEA. (2025). *Global EV Outlook 2025: Expanding sales in diverse markets*. International Energy Agency.

Lim, J. Z. K. (2026, March 1). Chinese carmakers rev up EV production in South-east Asia but net gains to local workers uncertain. *The Straits Times*.

Pangarkar, N. (2025, September 19). *China's EV surge challenges Indonesia's automotive future*. NUS BizBeat.

Rhodium Group. (2025). *China's manufacturing FDI in ASEAN grew rapidly, but faces tariff headwinds*. China Cross-Border Monitor. https://rhg.com/research/chinas-manufacturing-fdi-in-asean-grew-rapidly-but-faces-tariff-headwinds/

Santos Silva, J. M. C., & Tenreyro, S. (2006). The log of gravity. *The Review of Economics and Statistics, 88*(4), 641–658.

Valdiglesias, J. (2025). Rewiring global value chains: Friendshoring, nearshoring, and the politics of supply chain realignment in the United States–China trade conflict. *Contemporary Chinese Political Economy and Strategic Relations: An International Journal, 11*(2), 102–138.

Zhang, D. (2025, September 15). *Chinese electric vehicle battery giants accelerate Southeast Asia expansion*. Euromonitor International.
