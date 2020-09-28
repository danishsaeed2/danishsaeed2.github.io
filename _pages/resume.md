---
layout: archive
title: "Resume"
permalink: /resume/
author_profile: true
redirect_from:
  - /resume
---
<script type='text/javascript' src='http://ajax.googleapis.com/ajax/libs/jquery/1.3.2/jquery.min.js?ver=1.3.2'></script>
<script type='text/javascript'>
    $(function(){
        var iFrames = $('iframe');
    	function iResize() {
    		for (var i = 0, j = iFrames.length; i < j; i++) {
    		  iFrames[i].style.height = iFrames[i].contentWindow.document.body.offsetHeight + 'px';}
    	    }  
        	if ($.browser.safari || $.browser.opera) {
        	   iFrames.load(function(){
        	       setTimeout(iResize, 0);
               });  
        	   for (var i = 0, j = iFrames.length; i < j; i++) {
        			var iSource = iFrames[i].src;
        			iFrames[i].src = '';
        			iFrames[i].src = iSource;
               }     
        	} else {
        	   iFrames.load(function() {
        	       this.style.height = this.contentWindow.document.body.offsetHeight + 'px';
        	   });
        	}
        });
</script>


<iframe src="https://danishsaeed2.github.io/files/Resume - Danish Saeed.pdf#toolbar=0" class="iframe" scrolling="no" style="width:100%; border:1px solid #51555d;">
</iframe>

If the embedded pdf is not visible correctly, please [view it externally](https://resume.creddle.io/resume/7igwsegsk9o){:target="_blank"} or download my resume [here](https://danishsaeed2.github.io/files/Resume - Danish Saeed.pdf)
