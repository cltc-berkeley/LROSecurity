_Please Note: Cybersecurity is a rapidly evolving field. This document was last updated on February 2, 2019. Some of the technical guidance within this document may change, and some of the risks defined may increase or decrease in their potential likelihood or impact._

# Introduction

This guide is intended as an introductory document for low-risk organizations interested in improving their cybersecurity practices, **_specifically nonprofits and public interest organizations at low risk of targeted cyberattacks._** By "targeted cyberattacks," this guide refers to attacks on systems that seek to disrupt or surveil a specific organization or individual (as opposed to attacks meant to compromise as many devices or accounts as possible). This document provides guidance to improve the resilience of low-risk organizations (LROs) to common cyberattacks, and a framework for LROs to develop a basic cybersecurity policy. It is worth noting that all organizations are at some risk of cybersecurity incidents. Though not all organizations are equally likely to be victimized by online attacks, there are basic steps that LROs can take to improve their resiliency and keep themselves at lower risk—even while recognizing the limits to their potential investments of time, people, and money.

This is not intended to be a comprehensive guide to cybersecurity, nor an exhaustive set of recommendations. This guide is intended to help individuals in leadership positions and technical staff with little or no cybersecurity background understand some of the fundamentals of their own security context and guide them toward initial steps for improving their cybersecurity. The audience for this guide could include executive staff, system administrators, financial officers, general counsels, non-profit board members, or anyone interested in elevating their organizations' appreciation of cybersecurity issues.

This guide has three primary sections: the first introduces basic cybersecurity concepts, including the fundamentals of cybersecurity risk management; the second describes a series of basic cybersecurity "controls" – or measures organizations can take to improve their resilience to cybersecurity threats; the third describes additional cybersecurity best practices and policies LROs should adopt. Appendix A is designed to help organizations draft a basic cybersecurity policy using the controls and best practices described in this guide. Appendix B provides guidance on how to implement selected cybersecurity controls. Appendix C describes a series of additional resources for organizations interested in moving toward a more sophisticated cybersecurity posture.

# Table of Contents

**Section 1**
* [Why do Low-Risk Organizations Need Cybersecurity?](1-Why%20do%20Low-Risk%20Organizations%20Need%20Cybersecurity.md#section-1-why-do-low-risk-organizations-need-cybersecurity)
   * [Introduction to Cybersecurity](1-Why%20do%20Low-Risk%20Organizations%20Need%20Cybersecurity.md#introduction-to-cybersecurity)
     * [Confidentiality](1-Why%20do%20Low-Risk%20Organizations%20Need%20Cybersecurity.md#confidentiality)
     * [Integrity](1-Why%20do%20Low-Risk%20Organizations%20Need%20Cybersecurity.md#integrity)
     * [Availability](1-Why%20do%20Low-Risk%20Organizations%20Need%20Cybersecurity.md#availability)
   * [Understanding Cybersecurity Risk](1-Why%20do%20Low-Risk%20Organizations%20Need%20Cybersecurity.md#understanding-cybersecurity-risk)
     * [Common Threat Areas](1-Why%20do%20Low-Risk%20Organizations%20Need%20Cybersecurity.md#common-threat-areas)
 
**Section 2**
* [Common Cybersecurity Controls](2-Common%20Cybersecurity%20Controls.md#section-2-common-cybersecurity-controls)
   * [How to Use This Guide](2-Common%20Cybersecurity%20Controls.md#how-to-use-this-guide)
   * [Strong Authentication](2-Common%20Cybersecurity%20Controls.md#strong-authentication)
     * [Multi-Factor Authentication](2-Common%20Cybersecurity%20Controls.md#multi-factor-authentication)
     * [Password Managers](2-Common%20Cybersecurity%20Controls.md#password-managers)
     * [Account Monitoring](h2-Common%20Cybersecurity%20Controls.md#account-monitoring)
   * [Automatic Updates and Software Licenses](2-Common%20Cybersecurity%20Controls.md#automatic-updates-and-software-licenses)
   * [The Cloud](2-Common%20Cybersecurity%20Controls.md#the-cloud)
   * [HTTPS](2-Common%20Cybersecurity%20Controls.md#https)
   * [Data Security](2-Common%20Cybersecurity%20Controls.md#data-security)
     * [Encryption](2-Common%20Cybersecurity%20Controls.md#encryption)
     * [Access Management](2-Common%20Cybersecurity%20Controls.md#access-management)
     
**Section 3**
* [Additional Cybersecurity Best Practices](3-Additional%20Cybersecurity%20Best%20Practices.md#section-3-additional-cybersecurity-best-practices)
   * [“Fleet” Management](3-Additional%20Cybersecurity%20Best%20Practices.md#fleet-management)
   * [Travel Policy](3-Additional%20Cybersecurity%20Best%20Practices.md#travel-policy)
   * [Incident Response](3-Additional%20Cybersecurity%20Best%20Practices.md#incident-response)
   * [Social Media Use](3-Additional%20Cybersecurity%20Best%20Practices.md#social-media-use)
   * [Payment Card Security](3-Additional%20Cybersecurity%20Best%20Practices.md#payment-card-security)
   
**Appendix A** 
* [Building a Security Policy for Your Organization](4-Appendix%20A%20Building%20a%20Security%20Policy.md#appendix-a-building-a-security-policy-for-your-organization)
   * [Authentication](4-Appendix%20A%20Building%20a%20Security%20Policy.md#strong-authentication)
   * [Automatic Updates and Software Licenses](4-Appendix%20A%20Building%20a%20Security%20Policy.md#automatic-updates-and-software-licenses)
   * [The Cloud](4-Appendix%20A%20Building%20a%20Security%20Policy.md#the-cloud)
   * [HTTPS](4-Appendix%20A%20Building%20a%20Security%20Policy.md#https)
   * [Data Security](4-Appendix%20A%20Building%20a%20Security%20Policy.md#data-security)

**Appendix B**
* [Implementation Guidance](5-Appendix%20B%20Implementation%20Guidance.md#appendix-b-implementation-guidance)
   * [Authentication](5-Appendix%20B%20Implementation%20Guidance.md#strong-authentication)
   * [Automatic Updates and Software Licenses](5-Appendix%20B%20Implementation%20Guidance.md#automatic-updates-and-software-licenses)
     * [Turning on Automatic Updates](5-Appendix%20B%20Implementation%20Guidance.md#turning-on-automatic-updates)
     * [Finding Affordable Software Licenses](5-Appendix%20B%20Implementation%20Guidance.md#finding-affordable-software-licenses)
   * [The Cloud](5-Appendix%20B%20Implementation%20Guidance.md#the-cloud)
     * [Migrating Files to Cloud-Based Storage](5-Appendix%20B%20Implementation%20Guidance.md#migrating-files-to-cloud-based-storage)
   * [HTTPS](5-Appendix%20B%20Implementation%20Guidance.md#https)
   * [Data Security](5-Appendix%20B%20Implementation%20Guidance.md#data-security)
     * [Data Inventory](/5-Appendix%20B%20Implementation%20Guidance.md#data-inventory)
     * [Access Management in the Cloud](5-Appendix%20B%20Implementation%20Guidance.md#access-management-in-the-cloud)
     * [Enabling Device Encryption](5-Appendix%20B%20Implementation%20Guidance.md#enabling-device-encryption)

**Appendix C** 
* [Moving Beyond the Baseline](6-Appendix%20C%20Moving%20Beyond%20the%20Baseline.md#appendix-c-moving-beyond-the-baseline)
