---
layout: post
title: "google hack寻找练习目标"
description: ""
category: 渗透测试
tags: [google hack]
---
{% include JB/setup %}

搜索ftp泄漏的web.config文件

	filetype:config inurl:web.config inurl:ftp

空密码的phpadmin

	inurl:phpmyadmin inurl:phpmyadmin/index.php

	inurl:phpmyadmin inurl:phpmyadmin/sql.php
