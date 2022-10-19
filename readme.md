<h1 align="center">
  <a href="https://github.com/ankitwasankar/mftool-java">
    <img src="https://raw.githubusercontent.com/ankitwasankar/mftool-java/master/src/main/resources/icons/mf-tool-java-new.jpg" alt="mftool-java">
  </a>
</h1>
<p align="center">
<a href="https://search.maven.org/artifact/com.webencyclop.core/mftool-java"><img src="https://img.shields.io/maven-central/v/com.webencyclop.core/mftool-java.svg?label=Maven%20Central"/></a> 
<a href="https://travis-ci.com/github/ankitwasankar/mftool-java"><img src="https://travis-ci.com/ankitwasankar/mftool-java.svg?branch=master" /></a>
<a href="https://github.com/ankitwasankar/mftool-java/blob/master/license.md"><img src="https://camo.githubusercontent.com/8298ac0a88a52618cd97ba4cba6f34f63dd224a22031f283b0fec41a892c82cf/68747470733a2f2f696d672e736869656c64732e696f2f707970692f6c2f73656c656e69756d2d776972652e737667" /></a>
&nbsp;<a href="https://www.linkedin.com/in/ankitwasankar/"><img height="20" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>
<p align="center">
  This repository contains the <strong>MF TOOL - JAVA</strong> source code.
  MF TOOL - JAVA is a java library developed to ease the process of working with Indian Mutual Funds. It's a powerful, actively maintained and easy to use java library.
</p>
<hr/>

# Introduction
This <b>mf-tool java</b> library provides simple apis/functions/methods to work with Indian Mutual Funds. You can,

- Fetch list of all the mutual fund schemes.
- Fetch list of matching mutual fund schemes based on provided keywords.
- Fetch historic or current NAV for the fund.
- Fetch Fund Details for fund and fund house.
- You can integrate this with any Java projects.

# Installation
##### Maven
```
<dependency>
  <groupId>com.webencyclop.core</groupId>
  <artifactId>mftool-java</artifactId>
  <version>1.0.4</version>
</dependency>
```
##### Graddle
```
implementation 'com.webencyclop.core:mftool-java:1.0.4'
```
For other dependency management tool, please visit
https://search.maven.org/artifact/com.webencyclop.core/mftool-java


# Usage
Sample code on how to use the library. <br/>
There are many methods available apart from below sample code, please scroll down to check the documentation.
```
MFTool tool = new MFTool();
tool.matchingScheme("Axis");   //-- get list of all schemes with Axis in it's name
tool.getCurrentNav("120503");  //-- get current nav
```
# Documentation
Multiple methods provide way to work with mutual funds and related data, here we can see each of the methods in details.
#### 1. How to initialize MFTool object

#### 2. How to fetch list of all Mutual Fund Schemes

#### 3. How to fetch list of all Schemes matching keyword

#### 4. Current NAV for the mutual fund scheme

#### 5. NAV on specific date for the scheme

#### 6. List of historic NAV for the scheme


