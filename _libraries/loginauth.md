---
title: Login & Authentication SDK
description: OMH Auth is an Android client library that makes it easy to integrate auth providers on all types of devices running different OS platforms. It eliminates the need for separate codebases for different app builds.
date: 2019-01-28T15:15:26+10:00
weight: 10
github_url: https://www.github.com/openmobilehub/omh-auth
---

<style>
  .container img.standard-image {
    /* Styles for the standard-size image */
    width: 60%; /* Set the desired width here */
    display: block;
    margin: 0 auto;
  }

  .container img.small-image {
    width: 12%;
    display: block;
    margin: 0 auto;
  }
</style>

<h1>A single codebase, running seamlessly on any device</h1>

The OMH Auth Client Library simplifies authentication integration for app developers across devices, supporting differnet OS platforms. With a unified interface, it enables easy incorporation of Google Sign-in and other third-party authentication providers without maintaining separate codebases.

With the OMH Auth Client Library, you can easily add Google Sign in and other third-party authentication providers to your applications, regardless of the devices types or the OS platforms. The library takes care of the technical details, providing a unified interface and components for a consistent auth experience.

For instance, the following screenshots showcase multiple devices with Android, both with GMS and Non-GMS. The same app works without changing a single line of code, supporting multiple auth provider implementations.

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

# Sample App

This repository includes a [auth-sample](/auth-sample) that demonstrates the functionality of the
OMH Auth Client Library. By cloning the repo and executing the app, you can explore the various
features offered by the library. However, if you prefer a step-by-step approach to learn the SDK
from scratch, we recommend following the detailed Getting Started guide provided in this repository.
The guide will walk you through the implementation process and help you integrate the OMH Auth
Client Library into your projects effectively.

**Note: Before running the sample application, make sure to follow the steps in Setup your Google
Cloud project for application with Google Services to configure your Google Cloud project.**

# Documentation

See example and check the full documentation and add custom implementation at
our [Wiki](https://github.com/openmobilehub/omh-auth/wiki).

Additionally for more information about the OMH Auth
functions, [Docs](https://openmobilehub.github.io/omh-auth).

# Provider Implementations / Plugins

OMH Auth SDK is open-source, promoting community collaboration and plugin support from other auth providers to enhance capabilities and expand supported auth services. More details can be found at [the wiki](https://github.com/openmobilehub/omh-auth/wiki/Creating-a-custom-implementation).

# Contributing

Please contribute! We will gladly review any pull requests. Make sure to read
the [CONTRIBUTING](https://github.com/openmobilehub/omh-auth/blob/main/CONTRIBUTING.md) page first
though.

