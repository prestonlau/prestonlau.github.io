---
title: OMH Benefits 
layout: benefits
description: Our goal is to empower participants in the mobile ecosystem, including app developers, SDK and API service providers, mobile hardware OEMs, and users. We aim to create an open and secure mobile ecosystem by offering a range of software tools and services that ensure high-quality mobile experiences for everyone involved.
bodyClass: page-about
image2: /images/main/OMH_Overview.png
image3: /images/main/OMH_Architecture.png
image4: /images/main/OMH_Benefits.png
image8: /images/main/OMH_broken_ux.png
---

# Current Experience in the Android Mobile Ecosystems

Google Mobile Services (GMS) are an integral part of most of the Android mobile devices, offering features like Google Maps, Login/Authentication, Google Drive, and many more. These features are core to the seamless user experience across most of the Android Applications.
Mobile devices who don't have GMS core services, experience a limited user experience as these services are not present, resulting in apps failing to run properly.

An Open Mobile Ecosystem seeks to offer a seamless experience where different mobile hardware OEMs, Content Partners and apps developers could have access to non-restricted tools and services, to deliver high quality mobile experiences, on all popular mobile platforms. The Open Mobile Hub (OMH) client SDK is an open-source framework designed to address these limitations.

![]({{page.image8 | relative_url}})

# OMH Architecture

- The OMH SDKs are open-source and available in GitHub.
- App Developers can add the OMH SDK to their app, as part of a single build to support all mobile devices at run-time, or can chose to have separate builds. This is managed through a standard SDK.
  - If the device running OMH is a GMS device, OMH will act as a pass-through to allow for all the GMS SDKs to work seamlessly.
  - If the device running OMH is a non-GMS device, OMH will leverage alternative implementations like Google public Web APIs, Third-Party, or custom implementations.
- Providers and other open source developers can write implementations or OMH plugins of the SDKs, and surface services to the apps.

![]({{page.image3 | relative_url}})

# OMH Benefits
<!--![]({{page.image4 | relative_url}})-->

- **Open Mobile Ecosystem:** OMH drives adoption of an open-source mobile ecosystem, enables access to non-restricted tools and services, to deliver high-quality mobile experiences to millions of users.

- **Open Source:** As an open-source project, OMH offers several benefits associated with open-source software, including freedom and flexibility in usage, high quality, security, compliance, and access to support and innovation.

- **Minimum Efforts:** Developers can quickly get up to speed with the OMH SDK library, which is designed to be idiomatic with popular SDKs. This seamless integration makes it easy for developers to start using the OMH SDK with minimal effort.

- **No Vendor Lock-In:** Integrating with OMH allows app developers to support all mobile ecosystems with full source code access and no vendor lock-in. The plugin ecosystem also enables providers to build swappable plugins using standard SDKs for increased customization.

- **Free-of-Charge:** OMH services are entirely open-sourced and free of charge for use. There is no additional financial burden for app developers to adopt OMH services.
