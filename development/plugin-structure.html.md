---
title: Plugin Structure
layout: guide
tags: ['guide', page']
guideOrder: 2020
---

<<<<<<< HEAD
Fork the plugin template on github and clone your forked version into your `node_modules` folder 
=======
For the plugin template on github and clone your forked version into your `node_modules` folder 
>>>>>>> refs/remotes/pimatic/master
in your `pimatic-dev` directory.

	cd node_modules
	git clone https://github.com/your-name/pimatic-plugin-template.git pimatic-my-plugin

Your `pimatic-dev` directory should now look like this:

<table class="table file-listing">
<tr><td>`config.json`</td>				       <td>the config file</td></tr>
<tr><td>`node_modules`</td>				       <td>directory for the framework and plugins</td></tr>
<tr><td>`node_modules/pimatic`</td>			   <td>the pimatic framework files</td></tr>
<tr><td>`node_modules/pimatic-my-plugin`</td>  <td>your plugin development</td></tr>
</table>

In your `pimatic-my-plugin` directory you will find these files:

<table class="table file-listing">
<tr><td>`my-plugin.coffee`</td>	                   <td>This should become the main source file of your plugin</td></tr>
<tr><td>`my-plugin-config-schema.coffee`</td>	   <td>Template for config definitions of your plugin</td></tr>
<tr><td>`package.json`</td>	                       <td>[npm package specification](https://npmjs.org/doc/json.html)</td></tr>
</table>
