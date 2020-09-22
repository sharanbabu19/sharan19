---
title: "Serverless Functions"
description: "Info about what Serverless functions are..."
layout: post
toc: false
comments: true
categories: [deployment, serverless functions]
metadata_key1: metadata_value1
metadata_key2: metadata_value2
---
# Deploying Code as Serverless functions
<ul>
<li> App code and dependencies are packaged into .zip files, with a a single entry point function.</li>
<li> Example of  cloud services that provide this: AWS Lambda, Google Cloud Functions.</li>
<li> These services provide instant scaling upto 10,000+ requests per second, load balancing, etc.</li>
<li> No worry of servers going down</li>
<li> Only pay for compute time.</li>
<br>
<i>Cons<i>
<li> Entire deployment package has to fit within 500 MB, <5 minutes execution time and < 3 GB memory (on AWS Lambda)</li>
<li> Only CPU execution. No GPU!!</li>
<br>
<i> Other Pros</i>
<li>Canarying: Easy to have 2 versions of Lambda functions in production.</li>
<li> Easy to switch back to the previous version of the function.</li>
