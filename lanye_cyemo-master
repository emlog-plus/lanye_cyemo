<?php
/*
Plugin Name: 蓝叶文章看后感想表情
Version: 1.0
Plugin URL: http://lanyes.org
Description: 在文章页添加看后感想表情。
Author: 蓝叶
Author Email: w@lanyes.org
Author URL: http://lanyes.org
*/
!defined('EMLOG_ROOT') && exit('access deined!');
function lanye_ganxiangemo(){
	$active_plugins = Option::get('active_plugins');
	$lanye_ganxiangemo_html = '<div id="cyEmoji" role="cylabs" data-use="emoji" sid="'.$logid.'"></div>
<script type="text/javascript" charset="utf-8" src="http://changyan.itc.cn/js/??lib/jquery.js,changyan.labs.js?appid=cyqOIEzO8"></script>'."\r\n";
	echo $lanye_ganxiangemo_html;
}

addAction('log_related', 'lanye_ganxiangemo');
