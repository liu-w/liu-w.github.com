---
layout: post
title: "build android project with ant"
date: 2013-02-18 12:39
comments: true
categories: [ant, Andrioid]
---
# Converting to ant project
android update project -p <path_to_project>
or
android update project -s -p <path_to_project>

# solving the "dir.sdk missing" error

sdk.dir is missing. Make sure to generate local.properties using 'android update project' or to inject it through an env var.

android update project --target android-17 ...
