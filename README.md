# fundpadi-enterprise-risk-assessment
Enterprise risk assessment for FundPadi, a fictional Nigerian fintech. Covers asset classification, threats and vulnerabilities, 5x5 risk ratings, treatment plan, SLE/ALE exposure (₦43M combined), KRIs and a management report. 10Alytics ERM case study.
# FundPadi Enterprise Risk Assessment

An enterprise risk assessment for **FundPadi Digital Financial Services Ltd.**, a fictional Lagos-based fintech with about 180 employees, 350,000 registered users and 6,500 merchants. The project covers asset classification, threat and vulnerability analysis, 5x5 risk ratings, risk appetite assessment, treatment planning, financial exposure (SLE/ALE) and Key Risk Indicators (KRIs).

> **Note:** FundPadi is a fictional company. This is a training case study prepared for the 10Alytics Enterprise Risk Management programme. All scenario facts and financial estimates come from the case brief.

## Scenarios assessed

1. **Privileged access and customer database security:** administrator accounts without MFA, shared passwords, no access reviews and no alerting on unusual logins.
2. **Mobile application and unauthorised transactions:** no MFA or documented rate limiting at customer login, with unauthorised-transfer complaints rising for three months.
3. **Third-party vendor and service disruption:** dependence on Cloudy Solutions Ltd. with no security assessment, unclear data-sharing terms and a three-hour outage.

## Headline results

| Risk | Scenario | Current score | Level | ALE | Residual |
|---|---|---|---|---|---|
| R1 | Privileged access and customer database | 20 | Critical | ₦15,000,000 | Medium |
| R2 | Mobile app and unauthorised transactions | 20 | Critical | ₦18,000,000 | Medium |
| R3 | Third-party vendor and service disruption | 12 | High | ₦10,000,000 | Medium |

- All three risks are **outside FundPadi's risk appetite**, which only allows Low risks to be accepted without further treatment.
- Estimated **combined annual loss exposure is ₦43 million**.
- **Mobile app fraud is the most urgent risk.** It is already materialising and has the highest ALE.
- **MFA is the common thread.** It is missing for both administrators and customers, which makes it the highest-value quick win.
- No risk reaches Low after treatment, so management must decide whether to fund further treatment or formally accept the Medium residual risk.

## Method

- **Asset classification** using four levels: Public, Internal, Confidential, Restricted.
- **Threat and vulnerability analysis** with nine threat and vulnerability pairs across the three scenarios.
- **Risk rating** on a 5x5 matrix, where Risk Score = Likelihood x Impact. Bands: Low (1-4), Medium (5-9), High (10-16), Critical (17-25). Each risk is rated as inherent, current and residual.
- **Financial exposure** using SLE = Asset Value x Exposure Factor and ALE = SLE x ARO.
- **Treatment roadmap** of 15 controls split into 30-day quick wins and 90-day structural controls.
- **12 KRIs** with warning and escalation thresholds and monitoring frequencies.
- **Control mapping** to NIST CSF 2.0, ISO/IEC 27001:2022 and COBIT 2019 (indicative).

## Financial exposure

| Scenario | Asset value | EF | SLE | ARO | ALE |
|---|---|---|---|---|---|
| S1 Customer database breach | ₦50,000,000 | 60% | ₦30,000,000 | 0.5 | ₦15,000,000 |
| S2 Unauthorised mobile app transactions | ₦30,000,000 | 40% | ₦12,000,000 | 1.5 | ₦18,000,000 |
| S3 Third-party service disruption | ₦20,000,000 | 25% | ₦5,000,000 | 2 | ₦10,000,000 |
| **Total** | | | | | **₦43,000,000** |

## Repository contents

| File | Description |
|---|---|
| `FundPadi_Risk_Assessment_Workbook.xlsx` | Asset register, risk register, SLE/ALE calculations and KRIs |
| `FundPadi_Management_Risk_Assessment_Report.pdf` | Full management report with findings, appetite assessment, treatment plan, evidence gaps and prioritised recommendations |
| `FundPadi Enterprise Risk Assessment.pptx` | Management presentation slides |

## Limitations

- No technical testing was performed. Findings rest on the case brief and a preliminary IT review.
- Likelihood and impact ratings are analyst judgements.
- Asset values, exposure factors and AROs were supplied for the exercise and have not been validated against loss history.
- Post-treatment ALE figures in the report are illustrative assumptions, not values from the case brief.
- Framework references are indicative and should be verified before formal use.

## Author

**Steven Dairo**, Junior Enterprise Risk Analyst (GRC)

## Acknowledgements

Case study provided by [10Alytics](https://www.10alytics.com).

#GRC #RiskAssessmentWith10Alytics #ERMWith10Alytics
