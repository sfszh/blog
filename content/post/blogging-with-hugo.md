+++
date = "2016-07-26T22:46:37+12:00"
draft = false
title = "blogging with hugo"
comments = true

+++

I recent changed my blogging system to hugo. The reason I choose hugo is its simplicity. Hugo has no extra dependencies, every thing is included into a single executable. Like other static site generators, I can edit my blog like coding, and versioning them as regular code. With that, each blog does not have to be outdated.


I am using codeship to continuous deploy it to azure. At current stage, I don't have any testing code, the deployment code is changed from [chris' blog](https://cwhite.me/continuous-delivery-for-your-static-site-with-codeship/). I prefer his idea of "wget the steady version of hugo instead git clone the latest version". And since I am deploy it into an azure virtual machine, I have to use ssh instead.
