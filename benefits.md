---
title: OMH Benefits 
layout: page
description: OMH Benefits
bodyClass: page-about
image1: /images/main/OMH_Research.png
image2: /images/main/OMH_Overview.png
image3: /images/main/OMH_Architecture.png
image4: /images/main/OMH_Benefits.png
image5: /images/main/maps_icon.png
image6: /images/main/storage_icon.jpg
image7: /images/main/login_icon.png
image8: /images/main/OMH_broken_ux.png
---

Our goal is to empower participants in the mobile ecosystem, including app developers, SDK and API service providers, mobile hardware OEMs, and users. We aim to create an open and secure mobile ecosystem by offering a range of software tools and services that ensure high-quality mobile experiences for everyone involved.

<!-- Set the image size to 50% using HTML 
<img src="/images/main/omh_logo.png" alt="About" style="width:70%;">
-->

# Current Experience in the Android Mobile Ecosystems

Google Mobile Services (GMS) are an integral part of most of the Android mobile devices, offering features like Google Maps, Login/Authentication, Google Drive, and many more. These features are core to the seamless user experience across most of the Android Applications.
Mobile devices who don't have GMS core services, experience a limited user experience as these services are not present, resulting in apps failing to run properly.

An Open Mobile Ecosystem seeks to offer a seamless experience where different mobile hardware OEMs, Content Partners and apps developers could have access to non-restricted tools and services, which they do not have today, to deliver high quality mobile experiences, for both GMS and non-GMS devices.
The Open Mobile Hub (OMH) client SDK is an open-source framework designed to address these limitations.

![]({{page.image8 | relative_url}})

<!--# Research Papers from Top Universities support an Open Mobile System in Anticompetitive Practices

![]({{page.image1 | relative_url}})
-->


# OMH Architecture

- The OMH SDKs are open-source and available in GitHub.
- App Developers can add the OMH SDK to their app, as part of a single build to support both GMS and non-GMS devices at run-time, or can chose to have separate builds. This is managed through a standard API.
  - If the device running OMH is a GMS device, OMH will act as a pass-through to allow for all the GMS SDKs to work seamlessly.
  - If the device running OMH is a non-GMS device, OMH will leverage alternative implementations like Google public Web APIs, Third-Party, or custom implementations.
- Providers can write implementations or OMH plugins of the APIs, and surface services to the apps.

![]({{page.image3 | relative_url}})

# OMH Benefits
<!--![]({{page.image4 | relative_url}})-->

- **Open Mobile Ecosystem:** OMH drives adoption of an open-source mobile ecosystem, enables access to non-restricted tools and services, to deliver high-quality mobile experiences to millions of users.

- **Open Source:** As an open-source project, OMH offers several benefits associated with open-source software, including freedom and flexibility in usage, high quality, security, compliance, and access to support and innovation.

- **Minimum Efforts:** Developers can quickly get up to speed with the OMH SDK library, which is designed to be idiomatic with popular products like Google Firebase, identity, location, and in-app purchases SDKs. This seamless integration makes it easy for developers to start using the OMH SDK with minimal effort.

- **No Vendor Lock-In:** Integrating with OMH allows app developers to support all mobile ecosystems with full source code access and no vendor lock-in. The plugin ecosystem also enables providers to build swappable plugins using standard APIs for increased customization.

- **Free-of-Charge:** OMH services are entirely open-sourced and free of charge for use. There is no additional financial burden for app developers to adopt OMH services.



<!--
# ADDITIONAL TEXT FORMATS TO KEEP AS SAMPLES - DELETE AS NEEDED

## Enhancing Qualitative Characteristics

### Verifiability

Verifiability implies consensus between the different knowledgeable and independent users of financial information. Such information must be supported by sufficient evidence to follow the principle of objectivity.

### Comparability

Comparability is the uniform application of accounting methods across entities in the same industry. The principle of consistency is under comparability. Consistency is the uniform application of accounting across points in time within an entity.

### Understandability

Understandability means that accounting reports should be expressed as clearly as possible and should be understood by those to whom the information is relevant.
Timeliness: Timeliness implies that financial information must be presented to the users before a decision is to be made.

---

## Statement of cash flows

The statement of cash flows considers the inputs and outputs in concrete cash within a stated period. The general template of a cash flow statement is as follows: Cash Inflow - Cash Outflow + Opening Balance = Closing Balance

| Cash Inflow | Outflow   | Opening Balance |
| ----------- | --------- | --------------- |
| _Monday_    | `Tuesday` | **Wednesday**   |
| 1           | 2         | 3               |

**Example 1:** in the beginning of September, Ellen started out with $5 in her bank account. During that same month, Ellen borrowed $20 from Tom. At the end of the month, Ellen bought a pair of shoes for $7. Ellen's cash flow statement for the month of September looks like this:

- Cash inflow: $20
- Cash outflow:$7
- Opening balance: $5
- Closing balance: $20 – $7 + $5 = $18

**Example 2:** in the beginning of June, WikiTables, a company that buys and resells tables, sold 2 tables. They'd originally bought the tables for $25 each, and sold them at a price of $50 per table. The first table was paid out in cash however the second one was bought in credit terms. WikiTables' cash flow statement for the month of June looks like this:

> **Important:** the cash flow statement only considers the exchange of actual cash, and ignores what the person in question owes or is owed.

## Statement of financial position (balance sheet)

The balance sheet is the financial statement showing a firm's assets, liabilities and equity (capital) at a set point in time, usually the end of the fiscal year reported on the accompanying income statement.

- **fixed assets**
  - property
  - building
  - equipment (such as factory machinery)
- **intangible assets**
  - copyrights
  - trademarks
  - patents
    - pending
    - international
- goodwill

Owner's equity, sometimes referred to as net assets, is represented differently depending on the type of business ownership. Business ownership can be in the form of a sole proprietorship, partnership, or a corporation. For a corporation, the owner's equity portion usually shows common stock, and retained earnings (earnings kept in the company). Retained earnings come from the retained earnings statement, prepared prior to the balance sheet.
-->
