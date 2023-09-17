---
title: Storage SDK
description: The OMH Storage Client Library would allow users to support file management and app backup services in a seamless way, regardless of the types of devices or the OS platforms. The file management feature supports file upload, retrieval, update, and deletion of files and folders. The OMH SDK enables Apps running on all types of devices to backup data with storage and backup providers like Google Drive.
date: 2019-05-18T12:33:46+10:00
weight: 30
github_url: https://www.github.com/openmobilehub/omh-storage
---

<style>
  .container img.standard-image {
    /* Styles for the standard-size image */
    width: 70%; /* Set the desired width here */
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

OMH Storage is a client library that makes it easy to integrate storage on all types of devices, running differnet OS platforms. It eliminates the need for separate codebases for different app builds.

With the OMH Storage Client Library, you can easily add Google Drive and other third-party storage to your applications, regardless of its device types or its OS platforms. The library takes care of the technical details, providing a unified interface and components for a consistent storage experience.

For instance, the following screenshots showcase multiple devices with Android, both with GMS and Non-GMS. The same app works without changing a single line of code, supporting multiple storage provider implementations. 

<div class="container pt-6 pb-6">
  <div class="row">
      <div class="col-12 col-md-6 mb-3">
       <div>
         <div>
           <h2 align="center">Non-GMS Device</h2>
           <video width="80%" autoplay loop src="/images/features/storage/storage-nongms-demo.mp4" controls title="Storage non-GMS"></video>
         </div>
       </div>
      </div>
      <div class="col-12 col-md-6 mb-3">
       <div>
         <div>
           <h2 align="center">GMS Device</h2>
           <video width="90%" autoplay loop src="/images/features/storage/storage-gms-demo.mp4" controls title="Storage GMS"></video>
         </div>
       </div>
      </div>
  </div>
  <div>
    <a href="https://github.com/openmobilehub/omh-storage">
    <img src="/images/main/github-mark/github-mark.png" alt="OMH" class="small-image" align="center">
  </a>
  <p align="center">Fork our samples and try them yourself.</p>
  </div>
</div>

