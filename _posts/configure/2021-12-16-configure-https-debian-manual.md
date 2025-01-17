---
title: Manual HTTPS configuration on Debian and Ubuntu with user provided certificates
date: 2021-12-16 00:00:00 Z
card_teaser: Configure HTTPS with user provided certificates
card_title: Debian/Ubuntu manual HTTPS configuration
description: Configure HTTPS with user provided certificates on debian and ubuntu systems
icon: fa-debian
card_position: 2
categories: [configure,https,ce,debian]
sidebar: configure
layout: default
slug: manual
permalink: /:categories/:slug.html
---

{% assign product = 'ce' %}
{% include layout/row_start.html %}
{% include layout/col_start.html column="7" %}

{% include configure/configure-debian-package-nginx-https-manual.md %}

{% include date/updated.html %}

{% include layout/col_end.html %}
{% include layout/col_start.html column="4 last push1" %}

{% include aside/message.html
    class="tldr notice"
    content="Are you experiencing issues when installing passbolt?"
    link="https://community.passbolt.com/c/installation-issues"
    ask="Ask the community!"
    button="primary"
%}

{% include layout/row_end.html %}
