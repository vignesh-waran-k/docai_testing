# Preliminary Processor Management API Documentation* Author: docai-incubator@google.com## Disclaimer
## Introduction and Notes
# Summary
# Part 1: Document AI Client for RPC and Python
## List Processors
<h2><span style="color:#646b67;font-weight:800">Class ListProcessorsPager</span><span>&nbsp;</span></h2>
# Get Processor
# Enable Processor
# 2) Processor Building
# 3) Operation (Async) Management
# 4) Document Service Sample Calls
# Part 2: Document AI Client for Java
<dependencyManagement>
If you are using Maven without BOM, add this to your dependencies:<dependency>
If you are using Gradle 5.x or later, add this to your dependencies:implementation platform('com.google.cloud:libraries-bom:26.30.0')

implementation 'com.google.cloud:google-cloud-document-ai:26.30.0'If you are using SBT, add this to your dependencies:libraryDependencies += "com.google.cloud" % "google-cloud-document-ai" % "26.30.0"Authentication
  <h2 ><span>Getting Started - Procedure</span></h2>
gcloud auth login and gcloud config set project [YOUR PROJECT ID]## Installation and setup
 ## 1. Processor Management
## 2. Processor Building
## 3. Processing Documents
## 4. Example Java Files
package com.google.cloud.documentai.uiv1beta3;

