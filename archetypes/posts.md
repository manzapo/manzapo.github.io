---
date        : {{ .Date }}
title       : {{ replace .Name "-" " " | title }}
description : {{ replace .Name "-" " " | title }}
categories  :
- dokumentasi
- pengumuman
- sosialisasi
slug        : {{ .Name }}
thumbnail   : img/home-thumb.jpg
weight      : 1
layout      : small
---
