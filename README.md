# Stylist

Add and edit live CSS to any page in any modern browser.

Simply copy the link below as a bookmark - click the bookmark on the page you wish to change...

[Run Stylist][1]
[1]:javascript:/*! stylist 2014-10-26 */
!function(a,b,c){function d(a,b){return function d(){if(!d.timer){var e=arguments,f=this;d.timer=setTimeout(function(){a.apply(f,e),d.timer=c},b)}}}function e(a,b){console.log("applying style...."),a.id="stylist:input",b.id="stylist:panel";var c,d,e=[["position","fixed"],["top","0"],["right","0"],["width","300px"],["height","100%"],["zIndex","99999999"],["overflow","auto"],["outline","none"],["padding","10px 20px"],["borderTop","0"],["borderBottom","0"],["borderRight","0"],["borderLeft","1px solid #ccc"],["color","#222"],["background","#fcfcfc"]],f=[["font","13px Inconsolata, Consolas, Menlo, Monaco, Lucida Console, Courier New, Courier, monospace"],["width","100%"],["height","100%"],["direction","ltr"],["textAlign","left"],["background","#fcfcfc"]];for(c=0,d=e.length;d>c;c++)b.style.setProperty(e[c][0],e[c][1],"important");for(c=0,d=f.length;d>c;c++)a.style.setProperty(f[c][0],f[c][1],"important")}function f(){function c(){n.innerHTML=o.value,r()}b.getElementById("stylist:panel")&&alert("Stylist is already running - CTRL+M to open panel");var f=b.getElementsByTagName("head")[0],m=b.body,n=b.createElement("style"),o=b.createElement("textarea"),p=b.createElement("div"),q=b.createElement("h1");p.style.display="none",o.spellcheck=!1,q.innerHTML="",q.style.setProperty("background-color","#fcfcfc","important"),q.style.setProperty("background-image","url(data:image/png;base64,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)","important"),q.style.setProperty("width","150px","important"),q.style.setProperty("height","53px","important"),e(o,p),p.appendChild(q),p.appendChild(o),f.appendChild(n),m.appendChild(p),n.innerHTML=localStorage.siteStyle||"",o.value=n.innerHTML,o.placeholder="/* Enter your styles here. */",m.addEventListener("click",function(a){if(-1===o.style.display.indexOf("none")&&a.target.id!==o.id&&a.altKey){var b,c,d=0,e=a.target,f=e.className.split(" ")||"",g=[],h="",j="";for(j+=e.tagName.toLowerCase(),e.id&&(j+="#"+e.id),d=0;d<f.length;d++)k.test(f[d])||(j+="."+f[d]);if(e.getAttribute("style"))for(g=e.getAttribute("style").split(";"),d=0;d<g.length;d++)b=g[d].split(l).join(" ").trim(),k.test(b)||(h+=i+b.toLowerCase()+";\n");j&&(h=h?"{\n"+h+"}":"{\n\n}",c="\n"+j+" "+h,o.value+=c,o.focus(),o.setSelectionRange(o.value.length-c.length,o.value.length)),a.preventDefault()}});var r=d(function(){localStorage.siteStyle=n.innerHTML},500);o.addEventListener("keyup",c),o.addEventListener("change",c),o.addEventListener("keydown",function(a){var b=o.value,c=o.selectionStart;a.keyCode===g&&(o.value=b.substring(0,c)+i+b.substring(c),o.setSelectionRange(c+j,c+j),a.preventDefault())}),a.addEventListener("keydown",function(a){a.ctrlKey&&a.keyCode===h&&(p.style.display="none"==p.style.display?"block":"none")})}var g=9,h=77,i="    ",j=i.length,k=/^\s*$/,l=/\s+$/g;String.prototype.trim=function(){return this.replace(/(^\s+|\s+$)/g,"")},f()}(this,this.document);

## Rationale

I wasn't aware of any live CSS editors at the time. However upon finding them, they seem to live as extensions for those browsers. You'd need to download and install the extension on each browser. 
		
Styling on Internet Explorer is a pain and quite unfairly it does not have the extension ecosystem enjoyed in the other 'modern' browsers. This editor is to accommodate those developers that need to use IE and make their lives a little easier

## Inspiration		

This work has been inspired by <a href="http://githib.com/karthikv/my-style">githib.com/karthikv/my-style</a>

## Licence

MIT