---
title: Application Invitation Code
description: Restrict application sign up with invitation codes
keywords: [application, signup, invitation code]
authors: [leo220yuyaodog]
---

## Introduction

If you want to restrict application sign up, you can use invitation codes. An invitation code is a string that can be
used to sign up for the application. It is generated by the administrator and can be used multiple times. An application
can have multiple invitation codes.

## Configuration

1. First, add the "Invitation code" signup item to the signup item table.
2. Then, add the invitation code on the application configuration page.

![invitation code](/img/application/invitation-code/invitation_code_config.png)

:::tip
Once the application has invitation codes, users can only sign up for the application with a valid invitation code. Regardless of whether the "Invitation code" signup item is visible or not, users must provide the invitation code during sign up. So, if you want to use invitation codes, you need to add the "Invitation code" signup item to the signup item table.
:::

Here is a demo video that shows how to configure and use the invitation code:

![invitation code demo](/img/application/invitation-code/invitation_demo.gif)