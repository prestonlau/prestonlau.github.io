---
title: "Unified Authentication: OMH Auth Android Across GMS and non-GMS Devices"
date: 2023-09-08
github_url: https://www.github.com/openmobilehub/omh-auth
image: /images/libraries/login.png
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

In our ongoing series of OMH libraries, we turn our attention to a critical use case—Authentication across GMS and non-GMS Android devices, which account for 130M+ devices. As developers, we understand the immense advantages of utilizing services like Google Sign-in. They streamline the development process and enhance the user experience by addressing critical aspects such as efficient user onboarding through single sign-on, enhanced security, and access to Google Services and third-party services. 

However, what transpires when the inclusion of such a service in your app is hindered by the absence of Google Mobile Services (GMS) on certain devices? This scenario disrupts the user experience, rendering users unable to utilize the service, thus necessitating the creation of intricate workarounds. Such workarounds often result in a fragmented and suboptimal user experience, ultimately affecting both user satisfaction and the performance of your applications. 

Enter the OMH Auth Library—a powerful open-source solution tailored to resolve these challenges. With this cutting-edge Android SDK, you gain the capability to effortlessly integrate a diverse range of Authentication services, also known as Identity Providers, into your apps. Whether you require Google Sign-in, Facebook Login, Login with X, or other alternatives, this library streamlines the process, eliminating the need for you to delve into intricate technical details. 

<div>
    <img src="/images/blogs/blog2-image1.png" alt="OMH" class="standard-image" align="center">
</div>

## Key Highlights of the OMH Auth Library:

- **Unified Interface:** Attain a uniform and user-centric authentication experience, regardless of whether your application operates on GMS or non-GMS devices. 

- **Enhanced User Convenience:** Seamlessly integrate a variety of authentication services, enhancing user convenience and promoting engagement. 

- **Security:** Uphold the highest standards of security by leveraging trusted authentication providers, safeguarding user data and privacy. 

- **API Access:** Enable access to valuable user data, creating opportunities for personalized experiences and tailored features. 

- **Address Fragmentation:** Reduce the necessity for intricate workarounds that usually demand separate codebases, thus addressing fragmentation and providing a cohesive user experience. 

## Let’s see it in action

These steps provide a streamlined overview of the client library's capabilities, condensed from the Getting Started guide. If you wish to run the complete sample application from start to finish, please consult this guide. 

### Step 1: Declare an OmhAuthProvider with the GMS and non-GMS implementations

<div>
    <img src="/images/blogs/blog2-image2.png" alt="OMH" class="standard-image" align="center">
</div>

<br>
### Step 2: Integrate omhAuthClient for Login Handling in Android App Fragment 

This Kotlin code defines an Android fragment for handling user login. It uses Hilt for dependency injection to inject an authentication client (omhAuthClient). When the “Login” button is clicked, it launches a login activity and handles the result, extracting account information using omhAuthClient, and then navigates the user to the logged-in section of the app using the navigation controller. 

<div>
    <img src="/images/blogs/blog2-image3.png" alt="OMH" class="standard-image" align="center">
</div>

<br>
### Step 3: Test Across GMS and Non-GMS Devices  

Execute the application to confirm its functionality across various Android devices, assessing its compatibility with both GMS devices such as Pixel and Samsung, and non-GMS devices like Amazon FireOS and Huawei. This will verify the seamless integration of the Google Sign-In SDK and Google Sign-In OAuth 2.0, guaranteeing a uniform user experience. 

<div class="container pt-6 pb-6">
  <div class="row">
      <div class="col-12 col-md-6 mb-3">
       <div>
         <div>
           <h2 align="center">Non-GMS Device</h2>
           <p><img src="/images/features/auth/auth-nongms-demo.gif" alt="Auth" class="standard-image"></p>
         </div>
       </div>
      </div>
      <div class="col-12 col-md-6 mb-3">
       <div>
         <div>
           <h2 align="center">GMS Device</h2>
           <p><img src="/images/features/auth/auth-gms-demo.gif" alt="Auth" class="standard-image"></p>
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

For additional information about getting started, documentation, and the code sample, check out the GitHub link here: [https://github.com/openmobilehub/omh-auth](https://github.com/openmobilehub/omh-auth)      

Identity Providers, if you're interested in partnering with us to create plugins for OMH, we welcome your contributions. Get started with our documentation and guides here: [Creating a custom implementation](https://github.com/openmobilehub/omh-auth/wiki/Creating-a-custom-implementation). Let's collaborate! 

Thank you for reading this OMH SDK article! We hope that you are enjoying these series and learning new things.  We are open to any open-source contributors of this project, please contact us at [contact@openmobilehub.com](mailto:contact@openmobilehub.com)  if you are interested in joining the unified authentication revolution now!

