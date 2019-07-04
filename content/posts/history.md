---
title: "History"
date: 2019-06-13T21:49:16+09:00
draft: false
---
This page is a crude  histroy that may be summarized as follows

procedure of HUGO






1 $ hugo new site mammal && cd mammal

2 $ git init && git submodule add https://github.com/vaga/hugo-theme-m10c.git themes/m10c;

3 config.toml      add{ theme = “m10c”}

4 hugo server

5 hugo new posts/whale.md

6 whale.md
{
title: "whale."
date: 
draft: true->false

Comment
}
7 hugo #reflectin
/*
/*



8 
	publishDir = "docs"
	canonifyurls = true
	baseURL = "https://beginnercppis.github.io/creature/“
	#baseURL = "https://subtle-life.work"                                                                                                                                                                                                
         
	defaultContentLanguage = "en"
	title = "introduction"
	theme = "m10c"
	
	[params]
	author = "maki"
	description = "simple introduction something like hobby"
	[params.style]
	
	 # darkColor = "#2a3738"                                                                                                                                                                                                                      
	 # darkestColor = "#d35050"                                                                                                                                                                                                                   
	   darkColor = "#212121"
	 # lightColor = "#f5e3e0"                                                                                                                                                                                                                     
	 # lightestColor = "#f5f5f5"                                                                                                                                                                                                                  
	 # primaryColor = "#fff"      
9 github pages make repository
10 
git remote add origin https://github.com/beginnerCPPis/creature.git
https://github.com/beginnerCPPis/creature

11
git add .
git commit -m “updating”
git push origin master
		git fetch
		git merge --allow-unrelated-histories origin/master
