# F5 Google Deployment Manager Templates 
[![Slack Status](https://f5cloudsolutions.herokuapp.com/badge.svg)](https://f5cloudsolutions.herokuapp.com)
[![Releases](https://img.shields.io/github/release/f5networks/f5-google-gdm-templates.svg)](https://github.com/f5networks/f5-google-gdm-templates/releases)
[![Issues](https://img.shields.io/github/issues/f5networks/f5-google-gdm-templates.svg)](https://github.com/f5networks/f5-google-gdm-templates/issues)




## Introduction
 
Welcome to the GitHub repository for F5's Google Cloud Deployment Manager (GDM) templates for deploying F5 instances in the Google cloud.  All of the templates in this repository have been developed by F5 Networks engineers. Across all branches in this repository, there are two directories: *supported* and *experimental*

  - **supported**<br>
  The *supported* directory contains Google GDM templates that have been created and fully tested by F5 Networks. These templates are fully supported by F5, meaning you can get assistance if necessary from F5 Technical Support.

  - **experimental**<br>
  The *experimental* directory also contains GDM templates that have been created by F5 Networks. However, these templates have not completed full testing and are subject to change. F5 Networks does not offer technical support for templates in the experimental directory, so use these templates with caution.

## Template information
Descriptions for each template, including how the templates are generated and assistance in deploying a template, are contained in the README file on the individual template pages.

### Matrix for tagged releases
F5 has created a matrix that contains all of the tagged releases of the F5 Google GDM templates, and the corresponding BIG-IP versions, license types and throughput levels available for a specific tagged release. See https://github.com/F5Networks/f5-google-gdm-templates/blob/master/google-bigip-version-matrix.md.

## CVE-2017-6168 information  
If you have launched an F5 CFT template from a prior release, see the <a href="#important">important note</a> at the bottom of this page.  

## Current F5 Google Deployment Manager templates
The following is a list of the current *supported* F5 GDM templates. Click the link to view the README file which includes information on how to deploy the template in Google Cloud.
<br>
  - [**Standalone BIG-IP VE - 1 NIC**](https://github.com/F5Networks/f5-google-gdm-templates/tree/master/supported/standalone/1nic)  
  - [**Standalone BIG-IP VE - 2 NIC**](https://github.com/F5Networks/f5-google-gdm-templates/tree/master/supported/standalone/2nic)
  - [**Standalone BIG-IP VE - 3 NIC**](https://github.com/F5Networks/f5-google-gdm-templates/tree/master/supported/standalone/3nic)

<br>
---
<br>
<a name="important"></a>
<table>
 <tr>
  <td align=center>:warning: <strong>IMPORTANT<strong> :warning:  </td>
 </tr>
 <tr>
  <td>BIG-IP virtual servers configured with a Client SSL profile may be vulnerable to an Adaptive Chosen Ciphertext attack (AKA Bleichenbacher attack). For complete information on this vulnerability, see https://support.f5.com/csp/article/K21905460. <br>F5 has released hotfixes for all vulnerable releases. <br>  
   <ul>
    <li><em>If you have an existing BIG-IP VE deployment in Google Cloud</em>  <br>See the <a href="https://support.f5.com/csp/article/K21905460">Security Advisory</a>, which contains information about upgrading your BIG-IP VE to a non-vulnerable version.</li>
    <li><em>For <strong>new</strong> BIG-IP VE deployments in Google Cloud</em><br> F5 has uploaded new, non-vulnerable BIG-IP versions into Google and they are available for immediate use. </li>
    
   </ul></td>
 </tr>
 </table>

### Copyright

Copyright 2014-2018 F5 Networks Inc.


## License



### Apache V2.0

Licensed under the Apache License, Version 2.0 (the "License"); you may not use
this file except in compliance with the License. You may obtain a copy of the
License at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and limitations
under the License.


### Contributor License Agreement

Individuals or business entities who contribute to this project must have
completed and submitted the `F5 Contributor License Agreement`
