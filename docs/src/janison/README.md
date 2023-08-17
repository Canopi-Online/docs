# Introduction

Janison CLS has a rich adhoc reporting framework called “customisable reports”. It allows users to create their own reports based on a certain model (entity) and then picking the desired output columns and filter criteria. 

This document will describe how you can use a customisable report as a web service end point for extracting data from the Janison CLS in either JSON or XML formats.

There are several pieces required to work in conjunction with each other to expose and consume CLS Report API. 

**Here’s an overview of what required:**
1. A customisable report needs to be created in CLS,
2. The customisable report needs to be exposed via creating a Report API Endpoint,
3. Reporting API keys will need to be generated,
4. A programmer will need to write a client app to consume the Report API (A sample in Node can be found within our documentation).

So let’s get started.