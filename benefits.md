---
title: OMH Benefits 
layout: benefits
description: Our goal is to empower participants in the mobile ecosystem, including app developers, SDK and API service providers, mobile hardware OEMs, and users. We aim to create an open and secure mobile ecosystem by offering a range of software tools and services that ensure high-quality mobile experiences for everyone involved.
bodyClass: page-about
image1: /images/main/OMH_Architecture.png
---

# Current Experience in the Android Mobile Ecosystems

Google Mobile Services (GMS) are an integral part of most of the Android mobile devices, offering features like Google Maps, Login/Authentication, Google Drive, and many more. These features are core to the seamless user experience across most of the Android Applications.
Mobile devices who don't have GMS core services, experience a limited user experience as these services are not present, resulting in apps failing to run properly.

An Open Mobile Ecosystem seeks to offer a seamless experience where different mobile hardware OEMs, Content Partners and apps developers could have access to non-restricted tools and services, to deliver high quality mobile experiences, on all popular mobile platforms. The Open Mobile Hub (OMH) client SDK is an open-source framework designed to address these limitations.

<table>
<tr>
<th style="text-align: center; color: white; background: grey; border: 5px solid white; font-size: 90%;">Google Login Authentication</th>
<th style="text-align: center; color: white; background: grey; border: 5px solid white; font-size: 90%;">Missing GMS Play Services</th>
<th style="text-align: center; color: white; background: grey; border: 5px solid white; font-size: 90%">Google Drive Access</th>
<th style="text-align: center; color: white; background: grey; border: 5px solid white; font-size: 90%">Google IAP</th>
</tr>
<tr>
<td width="25%"><img src="/images/main/ux1.gif"/></td>
<td width="25%"><img src="/images/main/ux2.jpg"/></td>
<td width="25%"><img src="/images/main/ux3.gif"/></td>
<td width="25%"><img src="/images/main/ux4.gif"/></td>
</tr>
</table>

# OMH Architecture

- The OMH SDKs are open-source and available in GitHub.
- App Developers can add the OMH SDK to their app, as part of a single build to support all mobile devices at run-time, or can chose to have separate builds. This is managed through a standard SDK.
  - If the device running OMH is a GMS device, OMH will act as a pass-through to allow for all the GMS SDKs to work seamlessly.
  - If the device running OMH is a non-GMS device, OMH will leverage alternative implementations like Google public Web APIs, Third-Party, or custom implementations.
- Providers and other open source developers can write implementations or OMH plugins of the SDKs, and surface services to the apps.

![]({{page.image1 | relative_url}})

# OMH Benefits

> “With OMH, Android app development becomes more flexible, catering to a wide range of devices, our libraries provide a simplified interface to integrate essential mobile services. The goal is to save developers time and effort while enabling a single set of APIs to support any Android device,” says Raul Quino, business partner director at Futurewei Technologies.

- **Open Mobile Ecosystem:** OMH drives adoption of an open-source mobile ecosystem, enables access to non-restricted tools and services, to deliver high-quality mobile experiences to millions of users.

- **Open Source:** As an open-source project, OMH offers several benefits associated with open-source software, including freedom and flexibility in usage, high quality, security, compliance, and access to support and innovation.

- **Minimum Efforts:** Developers can quickly get up to speed with the OMH SDK library, which is designed to be idiomatic with popular SDKs. This seamless integration makes it easy for developers to start using the OMH SDK with minimal effort.

- **No Vendor Lock-In:** Integrating with OMH allows app developers to support all mobile ecosystems with full source code access and no vendor lock-in. The plugin ecosystem also enables providers to build swappable plugins using standard SDKs for increased customization.

- **Free-of-Charge:** OMH services are entirely open-sourced and free of charge for use. There is no additional financial burden for app developers to adopt OMH services.

# Other Open Source Benefits

> “An enlightened open source approach can prioritize human-cen- tered design and social impact while creating value for the customer and the business,” says Rimma Perelmuter, former CEO of the Mobile Ecosystem Forum.

An open source software stack for the mobile ecosystem can provide more transparency, a larger community, enhanced security, faster time to market, and lower costs.

- **More transparency:** Open source code is freely available for anyone to download, examine, and test. This enables developers to verify the quality of the code, identify vulnerabilities, and resolve bugs.  Developers appreciate working with a robust code base that adheres to industry standards. Confident that the lower levels are solid and well-designed, they can build new features at the appli- cation layer to differentiate their offerings and address different use cases.

- **Larger community:** Open source opens the doors to welcome anyone into the commu- nity. Developers can work together to combine their expertise and resources to address challenges, exchange knowledge, and foster innovation in mobile app development.  More ideas can come from more diverse people and places. This community can capture the highest levels of passion and creativity from participants who feel empowered to make a meaningful contribution.

- **Enhanced security:** The Internet runs on robust open source code that withstands constant attacks from hackers. With so many people working on code that is visible to everyone, open source provides many eyes continuously scanning for vulnerabilities and looking for the best ways to fix them.

- **Faster time-to-market:** Using robust open source code is like getting a head start on every project. Working from a pre-built foundation is faster than starting from the ground up. In open source, people work together to exchange, test, and select the best approaches. This avoids dead ends, rework, and wasted effort. All this helps developers and OEMs get products to market faster.

- **Lower costs:** With open source, projects come together faster, as many of
the foundational layers and standards are already in place. Participants gain from the many months or years of effort already completed.  Many organizations also share the costs of coding, testing, main- taining, and updating the code base, which reduces risk and helps development budgets go further.




