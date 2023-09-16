---
title: "Introducing the OMH Maps Client Library: Simplifying Unified Mapping for Android Developers"
date: 2023-08-29T12:33:46+10:00
weight: 100
github_url: https://www.github.com/openmobilehub/omh-maps
---

<style>
  .container img.standard-image {
    /* Styles for the standard-size image */
    width: 80%; /* Set the desired width here */
    display: block;
    margin: 0 auto;
  }

  .container img.small-image {
    width: 15%;
    display: block;
    margin: 0 auto;
  }
</style>

If you have a history as an Android developer, chances are that you've come across the challenges posed by compatibility when crafting applications intended to function across various Android platforms. This becomes particularly intricate when dealing with devices embedded with Google Mobile Services (GMS). I am thrilled to introduce a promising solution: the latest Map Client Library, which comes as an integral facet of the Open Mobile Hub (OMH) open-source initiative. This innovation holds the potential to effectively address and surmount these longstanding issues. 

This OMH Maps Client Library is an Android SDK that simplifies map integration, catering to both Google Mobile Services (GMS) and non-GMS devices. It conforms to our set of guidelines which ensure it will remain idiomatic, consistent, approachable, and dependable across all Android platforms. You can easily add Google Maps, OpenStreetMap, and other third-party maps via the Plugins architecture to your apps. No more juggling separate codebases! This library provides a unified interface for a consistent map experience, making your development process smoother and more efficient.

## OMH Main Benefits

🌍 **Unified Experience:** Say goodbye to maintaining separate code for different Android builds. OMH Maps allows your app to work seamlessly on various devices.

🔧 **Multiple Providers/Open Interfaces:** With support for Google Maps and OpenStreetMap, you can easily switch between map providers without hassle. 

🚀 **Effortless Integration:** Implementing maps becomes a breeze with the comprehensive Getting Started guide in our GitHub repository:  

🆓 **Open Source:** As an open-source project, OMH offers several benefits associated with open-source software, including freedom and flexibility in usage, high quality, security, compliance, and access to support and innovation.

[Learn More](https://github.com/openmobilehub/omh-maps)

## How OMH Maps Resolves the Issue

OMH Maps presents a transformative solution to the problem of integrating diverse mapping service providers. The crux of this solution is the OMH Maps unified API, which offers a single interface accessed via client libraries for multiple API Service Providers. This approach allows providers like Google Maps and OpenStreetMap to seamlessly integrate their services within the OMH Maps framework. You can find their implementations at [OMH Google Maps](https://github.com/openmobilehub/omh-maps/tree/main/maps-api-googlemaps) and [OMH OpenStreetMap](https://github.com/openmobilehub/omh-maps/tree/main/maps-api-openstreetmap).

The ultimate aim is to broaden this approach to include more providers like MapBox and Microsoft Bing Maps, all conforming to the OMH Maps API. This collective effort empowers developers to build applications once, eliminating the need for code modifications when switching between mapping providers.

<div>
    <img src="/images/blogs/blog1-image1.png" alt="OMH" class="standard-image" align="center">
</div>

OMH Maps' success lies in its ability to provide a uniform developer experience across different services, simplifying the development process and enhancing flexibility for developers.

## Let’s see it in Action 

To introduce the new client, we’ll explore some sample apps with examples that walk through some of the key functionality of the SDK, including support of both GMS and non-GMS platforms, as shown below:  

### Step 1: Initializing OmhMapProvider with Google Maps and OpenStreetMap 

 In this step, we will initialize the OmhMapProvider to support both Google Maps Services (GMS) and non-GMS devices. This involves configuring the provider to seamlessly switch between Google Maps and OpenStreetMap based on device capabilities and user preferences. This step sets the foundation for a versatile map experience across various devices. 

<div>
    <img src="/images/blogs/blog1-image2.png" alt="OMH" class="standard-image" align="center">
</div>

<br>
### Step 2: Integrate OmhMapFragment into your map fragment 

This section demonstrates how to seamlessly integrate OmhMapFragment to create interactive maps within your Android application. 

<div>
    <img src="/images/blogs/blog1-image3.png" alt="OMH" class="standard-image" align="center">
</div>
<br>
### Step 3: Test Across GMS and Non-GMS Devices 

Unified codebase on different devices. Run the app to verify its implementation. Witness its adaptability across GMS devices like Pixel and Samsung, as well as non-GMS devices like Amazon FireOS and Huawei. This validates the successful integration of Google Maps and OpenStreetMap, ensuring a consistent user experience. 

<div class="container pt-6 pb-6">
  <div class="row">
      <div class="col-12 col-md-6 mb-3">
       <div>
         <div>
           <h2 align="center">Non-GMS Device</h2>
           <p><img src="/images/features/maps/maps-kindle-table-demo.gif" alt="Maps non-GMS" class="standard-image"></p>
         </div>
       </div>
      </div>
      <div class="col-12 col-md-6 mb-3">
       <div>
         <div>
           <h2 align="center">GMS Device</h2>
           <p><img src="/images/features/maps/maps-gms-demo.gif" alt="Maps GMS" class="standard-image"></p>
         </div>
       </div>
      </div>
  </div>
  <div>
    <a href="https://github.com/openmobilehub/omh-auth">
    <img src="/images/main/github-mark/github-mark.png" alt="OMH" class="small-image" align="center">
  </a>
  <p align="center">Fork our samples and try them yourself.</p>
  </div>
</div>

## Learn more

For additional information about getting started, documentation, and the code sample, check out the GitHub link here: [https://github.com/openmobilehub/omh-maps/](https://github.com/openmobilehub/omh-maps/)

Thank you for reading this OMH SDK article! We hope that you learned something new and welcome you to share this post. We are open to any open-source contributors of this project, please contact us at [contact@openmobilehub.com](mailto:contact@openmobilehub.com) if you are interested in joining the unified mapping revolution now!

[#openmobilehub](https://twitter.com/hashtag/openmobilehub) #OMHMaps #AndroidDevelopment #MappingSimplified #UnifiedExperience
