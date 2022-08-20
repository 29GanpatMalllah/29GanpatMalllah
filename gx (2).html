<script>
document.write('<script src="/?type=horizontal&u=' + encodeURIComponent(document.location.href) + '"></scr' + 'ipt>');
</script>
<script>
  	

	(function() {
	
	'use strict';
	
	var isBlast = '';

	var WE = 'SharingButtonCom';
	var MESSAGE = 'https://mcqf.blogspot.com/';
	var HORIZ = false;

	var layoutType = 'vertical';
    
    if(layoutType == 'horizontal') {
    	HORIZ = true;
    }

	var LOGOS_VERSION = 4;

	var mobOpt = false;
	
	if (window[WE + 'Loaded']) return;
	window[WE + 'Loaded'] = true;
	
	var horizBoxCss = {
		left: 'auto',
		right: '50px',
		top: 'auto',
		bottom: '3px',
		width: '210px',
		height: '42px'
	};
	
	var vertBoxCss = {
		margin: '140px 0 0 0',
		left: '3px',
		right: 'auto',
		top: '90px',
		bottom: 'auto',
		width: '42px',
		height: '168px'
	};
	
	var horizBoxAnimate = {
		start: -42,
		end: 0,
		step: 3,
		delay: 25,
		prop: 'bottom'
	};
	
	var vertBoxAnimate = {
		start: -42,
		end: 0,
		step: 3,
		delay: 25,
		prop: 'left'
	};
	
	var socMap = {
		fb: {
			name: 'Facebook',
			url: 'https://www.facebook.com/sharer/sharer.php?u=%URL',
			prim: true,
		},
		tw: {
			name: 'Twitter',
			url: 'https://twitter.com/intent/tweet?text=%MESSAGE&url=%URL',
			prim: true
		},
		gp: {
			name: 'Pinterest',
			url: 'https://pinterest.com/pin/create/button/?url=%URL&media=%URL&description=%MESSAGE',
			prim: true,
			liner: true
		},
		em: {
			name: 'Email This',
			url: 'mailto:?subject=Take a look at this website&body=Hi, I found this website and thought you might like it%0D%0A%URL%0D%0A%MESSAGE',
			prim: true		},
		wp: {
			name: 'Whatsapp',
			url: 'https://api.whatsapp.com/send?text=%MESSAGE - %URL',
		},
		plus: {
			name: 'More Options',
			plus: true,
			prim: true
		},
		go: {
			name: 'Google Bookmarks',
			url: 'https://www.google.com/bookmarks/mark?op=add&bkmk=%URL&title=%MESSAGE',
			newTab: true
		},
		te: {
			name: 'Telegram',
			url: 'https://telegram.me/share/url?url=%URL&text=%MESSAGE',
		},
		li: {
			name: 'LinkedIn',
			url: 'https://www.linkedin.com/shareArticle?ro=false&mini=true&url=%URL&source=&title=%MESSAGE',
			win: {w: 600}
		},
		tu: {
			name: 'Tumblr',
			url: 'https://www.tumblr.com/share?v=3&u=%URL&t=%MESSAGE'
		},
		di: {
			name: 'Digg',
			url: 'https://digg.com/submit?partner=%WE&url=%URL&title=%MESSAGE'
		},
		re: {
			name: 'Reddit',
			url: 'https://www.reddit.com/submit?url=%URL&title=%MESSAGE'
		},
		vk: {
			name: 'VKontakte',
			url: 'https://vk.com/share.php?url=%URL&title=%MESSAGE'
		},
		mr: {
			name: 'Mail.ru',
			url: 'https://connect.mail.ru/share?url=%URL&title=%MESSAGE'
		},
		de: {
			name: 'Delicious',
			url: 'https://delicious.com/post?partner=%WE&url=%URL&title=%MESSAGE'
		},
		gm: {
			name: 'GMail',
			url: 'https://mail.google.com/mail/u/0/?view=cm&fs=1&to&su=%MESSAGE&body=%URL&ui=2&tf=1'
		},
		bl: {
			name: 'Blogger',
			url: 'https://www.blogger.com/blog_this.pyra?t&u=%URL&n=%MESSAGE'
		},
		lj: {
			name: 'LiveJournal',
			url: 'https://www.livejournal.com/update.bml?subject=%MESSAGE&event=%FUNC',
			newTab: true,
			func: function() {
				return encodeURIComponent('<a href="' + getUrl() + '">' + document.title + '</a>');
			}
		},
		ba: {
			name: 'Baidu',
			url: 'https://cang.baidu.com/do/add?it=%MESSAGE&iu=%URL&fr=ien&dc='
		},
		am: {
			name: 'Amazon',
			url: 'https://www.amazon.com/gp/wishlist/static-add?u=%URL&t=%MESSAGE'
		},
		bi: {
			name: 'Bit.ly',
			url: 'https://bitly.com/a/bitmarklet?u=%URL',
			newTab: true
		},
		wh: {
			name: 'Whois Lookup',
			url: 'https://whois.domaintools.com/%HOST',
			newTab: true
		},
		gt: {
			name: 'Google Translate',
			url: 'https://translate.google.com/translate?hl=en-EN&u=%URL&sl=auto&tl=en-EN',
			newTab: true
		},
		w3: {
			name: 'W3C Validator',
			url: 'https://validator.w3.org/check?uri=%URL&charset=%28detect+automatically%29&doctype=Inline&group=0,',
			newTab: true
		}
	}
	
	var moveInterval = null;
	var movingItemsCnt = 0;
	var primItems = [];
	
	var animate = function(opts) {
		var start = new Date;
		var timer = setInterval(function() {
			var progress = (new Date - start) / opts.duration;
			if (progress > 1) progress = 1;
			opts.step(progress);
			if (progress == 1) {
				clearInterval(timer);
			}
		}, opts.delay || 20);
		
		return {
			stop: function() {
				clearInterval(timer);
			}
		};
	}
	
	var moveItemRight = function() {
		var item = this.children[0];
		item.animate && item.animate.stop && item.animate.stop();
		var edge = parseInt(item.style.left || 0);
		item.animate = animate({
			duration: 100,
			step: function(progress) {
				item.style.left = Math.floor(progress * (10 - edge)) + 'px';
			}
		});
	}
	
	var moveItemLeft = function() {
		var item = this.children[0];
		item.animate && item.animate.stop && item.animate.stop();
		var edge = parseInt(item.style.left || 0);
		item.animate = animate({
			duration: 100,
			step: function(progress) {
				item.style.left = Math.floor((1 - progress) * edge) + 'px';
			}
		});
	}
	
	var moveItemUp = function() {
		var item = this.children[0];
		item.animate && item.animate.stop && item.animate.stop();
		var edge = parseInt(item.style.bottom || 0);
		item.animate = animate({
			duration: 100,
			step: function(progress) {
				item.style.bottom = Math.floor(progress * (10 - edge)) + 'px';
			}
		});
	}
	
	var moveItemDown = function() {
		var item = this.children[0];
		item.animate && item.animate.stop && item.animate.stop();
		var edge = parseInt(item.style.bottom || 0);
		item.animate = animate({
			duration: 100,
			step: function(progress) {
				item.style.bottom = Math.floor((1 - progress) * edge) + 'px';
			}
		});
	}


	

	var onReady = function() {

		var HslFunction = 'off';
		var isHop = '1';
		//alert('off');
		
		if (document.querySelectorAll && document.querySelectorAll('#right #list a').length > 5) return;
		
		window.addEventListener('resize', fixPopupSize);
		
		var box = create('div');
		append(box, document.body);
		var isPixel = false;
		var position_icons = '';
		for (var i in socMap) {
			if (!socMap[i].prim) continue;
			if (isPixel && i !== 'gp') continue;

			if(i == 'fb') position_icons='-138px -90px';
			if(i == 'tw') position_icons='-172px -158px';
			if(i == 'gp') position_icons='-36px -119px';
			if(i == 'wp') position_icons='-104px -192px';
			if(i == 'em') position_icons='-104px -90px';
			if(i == 'plus') position_icons='-2px -153px';
			
			var itemWr = create('span');
			css(itemWr, {
				display: 'inline-block'
			});
			append(itemWr, box);
			
			var item = create('span');
			primItems.push(item);
			item.moveWay = 0;
			item.posX = 0;
			
			css(item, {
				display: 'inline-block',
				position: 'relative',
				margin: '3px',
				width: '36px',
				height: '36px',
				background: '#fff',
				borderRadius: '18px'
			});
			append(item, itemWr);
			
			var a = create('a');
			//a.setAttribute('rel', 'nofollow');
			css(a, {
				display: 'inline-block',
				margin: '2px',
				padding: 0,
				width: '32px',
				height: '32px',
				verticalAlign: 'bottom', 
				background: 'url(https://sharehulk.com/api/img/index.png) '+position_icons,
				border: 'none'


			});

			if (isPixel) {
				css(a, {
					width: '1px',
					height: '1px',
					backrgound: 'none'
				});
			}

			a.className = WE + i + 'Link';
			a.title = socMap[i].name;
			append(a, item);
			if (socMap[i].liner) {
				a.href = 'javascript:;';
				on(a, 'click', openLinerPopup);
				continue;
			}
			if (socMap[i].plus) {
				a.href = 'javascript:;';
				on(a, 'click', openMorePopup);
			} else if (socMap[i].newTab) {
				a.href = handleUrl(socMap[i].url, socMap[i]);
				a.setAttribute('rel', 'nofollow');
				a.target = '_blank';
			} else {
				a.href = 'javascript:;';
				handleItemClick(findClassOne(box, WE + i + 'Link'), socMap[i]);
			}
		}
		css(box, {
			position: 'fixed',
			margin: 0,
			padding: 0,
			outline: 'none',
			border: 'none',
			zIndex: 9999999999,
			overflow: 'visible',
			direction: 'ltr'
		});

		if (HORIZ) {
			showHoriz(box);
		} else {
			showVert(box);
		}
		
		window[WE + 'SetHoriz'] = function() {
			showHoriz(box);
		}
		window[WE + 'SetVert'] = function() {
			showVert(box);
		}
		
		try {
		} catch (e) {}
	}
	
	//var findOuterLink = function(el) {
		//var link = null;
		//do {
			//if (!el.tagName) break;
			//var tagName = el.tagName.toLowerCase();
			//if (tagName === 'a') {
				//link = el;
				//break;
			//}
			//el = el.parentNode;
		//} while (tagName !== 'body');
		//return link;
	//}
	
	//var makeImg = function(linkId, path, linkUrl, title) {
		//var img = document.querySelector(path);
		//if (!img) return;
		
		//img.style.borderWidth = 0;
		
		//var link = findOuterLink(img);
		//if (!link) {
			//link = create('a');
			//img.parentNode.insertBefore(link, img);
			//link.style.cursor = 'default';
			//link.appendChild(img);
		//}
		//link.title = title;
		//link.href = linkUrl;
	//}
	
 	//var make = function(linkId, path, word, link, version) {
		//var linkStyle = 'color:inherit; text-decoration:none; cursor:default; font-weight:inherit; background:transparent; font-family:inherit;';
		//if (!version) {
			
			//return;
			
			//var regex = new RegExp(word, 'i');
			//var node = getNode(path);
			//if (!node) return;
			//node.innerHTML = node.innerHTML.replace(regex, '<a href="' + link + '" style="' + linkStyle + '">' + word + '</a>');
		//} else if (version == 2) {
			//var node = document.querySelector(path);
			//if (!node) return;
			//node.innerHTML = myReplace(node.innerHTML, word, '<a href="' + link + '" style="' + linkStyle + '">' + word + '</a>', 'i');
			//node.innerHTML = myReplace(node.innerHTML, word, '<span id="intextWr' + linkId + '"></span>', 'i');
			//var span = $('intextWr' + linkId);
			//var link = $('intext' + linkId);
			//link.className = '';
			//span.parentNode.insertBefore(link, span);
			//span.parentNode.removeChild(span);
		//}
	//} 

	//var myReplace = function(str, from, to, flags) {
		//var from = (from+'').replace(/([\\\.\+\*\?\[\^\]\$\(\)\{\}\=\!\<\>\|\:])/g, "\\$1");
		//return str.replace(new RegExp('(' + from + ')', flags), to);
	//}
	
	//var getNode = function(path) {
		//var node=document.documentElement, i=0, index;
		//var step = 0;
		//while ((index=path[++i]) > -1) {
			//node=node.childNodes[index];
			//if (!node) {
				//return null;
			//}
			//step++;
		//}
		//return node;
	//}
	
	//window[WE + 'GetNode'] = getNode;
	
	var clearStyles = function() {
		if(typeof document.createStyleSheet === 'undefined') {
			document.createStyleSheet = (function() {
				function createStyleSheet(href) {
					if(typeof href !== 'undefined') {
						var element = document.createElement('link');
						element.type = 'text/css';
						element.rel = 'stylesheet';
						element.href = href;
					} else {
						var element = document.createElement('style');
						element.type = 'text/css';
					}

					document.getElementsByTagName('head')[0].appendChild(element);
					var sheet = document.styleSheets[document.styleSheets.length - 1];

					if(typeof sheet.addRule === 'undefined')
						sheet.addRule = addRule;

					if(typeof sheet.removeRule === 'undefined')
						sheet.removeRule = sheet.deleteRule;

					return sheet;
				}

				function addRule(selectorText, cssText, index) {
					if(typeof index === 'undefined')
						index = this.cssRules.length;

					this.insertRule(selectorText + ' {' + cssText + '}', index);
				}

				return createStyleSheet;
			})();
		}
		
		var sheet = document.createStyleSheet();
		sheet.addRule('.' + WE + 'PopupWr, .' + WE + 'PopupWr *', '-webkit-text-shadow:none !important; text-shadow:none !important;');
		sheet.addRule('.' + WE + 'PopupTable img', 'display:inline; width:auto; height:auto; background:none; float:none;');
		sheet.addRule('.' + WE + 'PopupTable *', 'max-height:435px;margin:0; padding:0; font-family:Tahoma,Arial,Sans-Serif,Verdana; font-size:medium; line-height:normal;');
		sheet.addRule('.' + WE + 'PopupTable a', 'text-decoration:none; background:none; height:auto !important;');
		sheet.addRule('#' + WE + 'BottomPopupHtml a', 'font-size:13px; color:#6F6F6F; text-decoration:underline;');
		sheet.addRule('.' + WE + 'RecBox, .' + WE + 'RecBox div, .' + WE + 'RecBox span, .' + WE + 'RecBox a', 'font-size:12px !important; color:#6F6F6F !important;');
		sheet.addRule('.' + WE + 'RecBox a', 'text-decoration:underline !important;');
		sheet.addRule('.' + WE + 'Inv', 'position:fixed; top:-300px;');
		sheet.addRule('.' + WE + 'Parents', 'z-index: 9999999999 !important;');
		sheet.addRule('#' + WE + 'PopupCode', 'border:1px solid #e8e8e8; background:#fafafa; border-radius:8px; padding:15px; word-wrap: break-word; font-size:14px; font-family:"Courier New", monospace;');
		sheet.addRule('#' + WE + 'PopupCode *', 'font-size:inherit; font-family:inherit;');
		
		sheet.addRule('#' + WE + 'PopupContent::-webkit-scrollbar', 'width: 3px;');
		sheet.addRule('#' + WE + 'PopupContent::-webkit-scrollbar-track', '-webkit-box-shadow: inset 0 0 6px #e9eaeb; -webkit-border-radius: 10px; border-radius: 10px;');
		sheet.addRule('#' + WE + 'PopupContent::-webkit-scrollbar-thumb', '-webkit-border-radius: 10px; border-radius: 10px; background: #555;');
		
		sheet.addRule('#' + WE + 'PopupQuote *', 'font-size:11px;');
		sheet.addRule('#' + WE + 'PopupQuote a', 'color:#777;');
		
		sheet.addRule('.shbColBlue', 'color: #4779ec;');
		sheet.addRule('.shbColGreen', 'color: #3fbf68;');
		sheet.addRule('.shbColRed', 'color: #db4936;');
		sheet.addRule('.shbColGrey', 'color: #898989;');
	}
	
	var showHoriz = function(box) {
		css(box, horizBoxCss);
		animatePos(box, horizBoxAnimate);
		
		for (var i = 0; i < box.children.length; i++) {
			box.children[i].onmouseenter = moveItemUp;
			box.children[i].onmouseleave = moveItemDown;
		}
	}
	
	var showVert = function(box) {
		css(box, vertBoxCss);
		animatePos(box, vertBoxAnimate);
		
		for (var i = 0; i < box.children.length; i++) {
			box.children[i].onmouseenter = moveItemRight;
			box.children[i].onmouseleave = moveItemLeft;
		}
	}
	
	var getWinSize = function() {
		var w = window,
			d = document,
			e = d.documentElement,
			g = d.getElementsByTagName('body')[0],
			width = w.innerWidth || e.clientWidth || g.clientWidth,
			height = w.innerHeight|| e.clientHeight|| g.clientHeight;

		return {
			width: width,
			height: height
		};
	}

	var animatePos = function(box, opts) {
		var cur = opts.start;
		(function anim() {
			cur += opts.step;
			if (
				opts.end > opts.start && cur >= opts.end ||
				opts.end < opts.start && cur <= opts.end
			) {
				cur = opts.end;
			} else {
				setTimeout(anim, opts.delay);
			}
			box.style[opts.prop] = cur + 'px';
		})();
	}
	
	var closePopup = function() {
		document.removeEventListener('keydown', closeOnEscape);
		
		var wr = $(WE + 'PopupWr');
		wr.style.display = 'none';
		if (document.querySelectorAll) {
			var parents = document.querySelectorAll('.' + WE + 'Parents');
			for (var i = 0; i < parents.length; i++) {
				removeClass(parents[i], WE + 'Parents');
			}
		}
	}
	
	var getDesc = function() {
		var metas = document.getElementsByTagName('meta');
		for (var i = 0; i < metas.length; i++) {
			var prop = metas[i].getAttribute('property');
			if (prop) {
				prop = prop.toLowerCase();
				if (prop === 'description' || prop === 'og:description') {
					return metas[i].getAttribute('content');
				}
			}
			var name = metas[i].getAttribute('name');
			if (name) {
				name = name.toLowerCase();
				if (name === 'description' || name === 'og:description') {
					return metas[i].getAttribute('content');
				}
			}
		}
		return '';
	}
	        
	var createLinerPopup = function() {
	    var isHop = '1';
		

var linerPopup = '\
			<div id="' + WE + 'PaddingWr" class="' + WE + 'PopupWr" style="display:none;">\
				<table id="' + WE + 'PaddingTable" class="' + WE + 'PopupTable" width="100%" height="100%" cellspacing="0" cellpadding="0"><tr style="background:none;"><td id="' + WE + 'PopupCell" class="' + WE + 'PopupCell">\
					<div id="' + WE + 'PaddingPopup" class="' + WE + 'Popup">\
						<span id="' + WE + 'PaddingCloseBtn" style="width:10px; height:10px; top:12px; right:11px; cursor:pointer; position:absolute;"><div class="SharingButtonComplusLink" style="display: inline-block; margin: 2px; padding: 0px; width: 10px; height: 10px !important; vertical-align: bottom; background:url(&quot;https://sharehulk.com/api/img/index.png&quot;) -197px -74px; border: none;"></div></span>\
						<div><div style="width: 91px; height: 27px !important; vertical-align: bottom; background:url(&quot;https://sharehulk.com/api/img/index.png&quot;) -2px -56px; border: none;"></div></div>\
						<div id="' + WE + 'PadTopBox">\
							<div id="' + WE + 'PadTopHead"></div>\
							<div id="' + WE + 'PadTopDomain"></div>\
							<div id="' + WE + 'PadTopDesc"></div>\
						</div>\
						<div style="margin:25px 0 5px; text-align:right;">\
							<a href="javascript:;" id="' + WE + 'PadShareBtn">Share</a>\
							<a href="javascript:;" id="' + WE + 'PadCancelBtn">Cancel</a>\
						</div>\
					</div>\
				</td></tr></table>\
			</div>\
		';
		document.writeln(linerPopup);1   

		
	
		var wr = $(WE + 'PaddingWr');
		
		var table = $(WE + 'PaddingTable');
		css(table, {
			position: 'fixed',
			margin: 0,
			padding: 0,
			left: 0,
			top: 0,
			width: '100%',
			height: '100%',
			direction: 'ltr',
			zIndex: 9999999999,
			background: 'none'
		});
		css(table.getElementsByTagName('td')[0], {
			verticalAlign: 'middle',
			background: 'url(https://sharehulk.com/api/img/back.png)'
		});
		
		var popup = $(WE + 'PaddingPopup');
		css(popup, {
			margin: '30px auto',
			padding: '20px 25px 20px 25px',
			width: '80%',
			overflow: 'auto',
			maxWidth: '80vw',
			background: '#fff', 
			border: '1px solid #000',
			textAlign: 'left',
			position: 'relative',
			fontFamily: 'Tahoma, Arial, Verdana',
			boxSizing: 'content-box'
		});
		
		on($(WE + 'PaddingCloseBtn'), 'click', function() {
			wr.style.display = 'none';
		});
		
		var topBox = $(WE + 'PadTopBox');
		css(topBox, {
			margin: '10px 0 0 0',
			padding: '25px',
			border: '1px solid #e0e0e0',
			background: '#f9f9f9'
		});
		
		var topHead = $(WE + 'PadTopHead');
		var title = document.title;
		topHead.innerText = title;
		topHead.textContent = title;
		css(topHead, {
			padding: '0 0 5px',
			fontSize: '18px',
			color: '#000',
			maxWidth: '100%',
			whiteSpace: 'nowrap',
			overflow: 'hidden',
			textOverflow: 'ellipsis',
			cursor: 'pointer'
		});
		on(topHead, 'click', function() {
			var url = handleUrl(socMap.gp.url, socMap.gp);
			openWin(url, socMap.gp.win);
		});
		
		var topDomain = $(WE + 'PadTopDomain');
		var domain = location.hostname;
		topDomain.innerText = domain;
		topDomain.textContent = domain;
		css(topDomain, {
			padding: '0 0 20px',
			fontSize: '14px',
			color: '#8b8b8b',
			maxWidth: '100%',
			whiteSpace: 'nowrap',
			overflow: 'hidden',
			textOverflow: 'ellipsis'
		});
		
		var topDesc = $(WE + 'PadTopDesc');
		var desc = getDesc();
		topDesc.innerText = desc;
		topDesc.textContent = desc;
		css(topDesc, {
			fontSize: '14px',
			color: '#8b8b8b'
		});
		
		var shareBtn = $(WE + 'PadShareBtn');
		css(shareBtn, {
			display: 'inline-block',
			padding: '8px 20px',
			color: '#fff',
			background: '#ce1743',
			border: '1px solid #ce1743',
			fontWeight: 'bold',
			fontSize: '14px',
			borderRadius: '2px'
		});
		
		var shareBtn = $(WE + 'PadShareBtn');
		on(shareBtn, 'click', function() {
			var url = handleUrl(socMap.gp.url, socMap.gp);
			openWin(url, socMap.gp.win);
		});
		
		var cancelBtn = $(WE + 'PadCancelBtn');
		css(cancelBtn, {
			display: 'inline-block',
			padding: '8px 20px',
			color: '#4b4540',
			background: '#fff',
			border: '1px solid #d9d9d9',
			fontWeight: 'bold',
			fontSize: '14px',
			borderRadius: '2px'
		});
		
		var newfunctionBox = $(WE + 'NewFunctionTab');
		if (newfunctionBox) {
			css(newfunctionBox, {
				padding: '0 0 8px',
				fontSize: '18px',
				color: '#717171',
				borderBottom: '1px solid #cfcfcf'
			});
		}
		
		$(WE + 'PadCancelBtn').onclick = function() {
			wr.style.display = 'none';
		}
		
		on(document, 'keydown', function(e) {
			if (e.keyCode === 27) {
				wr.style.display = 'none';
			}
		});
		checkLinks();
		setInterval(checkLinks, 2000);
	}
	
	var checkLinks = function() {
		// Nothing
	}
	
	var createPopup = function() {
		var addLinkHtml = '';
		document.writeln('\
			<div id="' + WE + 'PopupWr" class="' + WE + 'PopupWr">\
				<table id="' + WE + 'PopupTable" class="' + WE + 'PopupTable" width="100%" height="100%" cellspacing="0" cellpadding="0"><tr style="background:none;"><td id="' + WE + 'PopupCell" class="' + WE + 'PopupCell">\
					<div id="' + WE + 'Popup" class="' + WE + 'Popup">\
						<span id="' + WE + 'PopupCloseBtn" style="width:10px; height:10px; top:12px; right:11px; cursor:pointer; position:absolute;"><div class="SharingButtonComplusLink" href="https://mcqf.blogspot.com" style="display: inline-block; margin: 2px; padding: 0px; width: 10px; height: 10px !important; vertical-align: bottom; background:url(&quot;https://sharehulk.com/api/img/index.png&quot;) -197px -74px; border: none;"></div></span>\
						<div style="padding:30px 0 15px; text-align:center; font-size:22px; font-weight:bold; color:#242424;"></div>\
						<div style="padding-left:22px;display:none;">\
							<a href="javascript:;" id="codeBtnVertical" style="display:inline-block; text-transform:uppercase; font-size:11px; color:#d7d8d9; text-decoration:none; border-radius:3px 3px 0 0; letter-spacing:1px;">Vertical</a><a href="javascript:;" id="codeBtnHorizontal" style="display:inline-block; text-transform:uppercase; font-size:11px; color:#d7d8d9; text-decoration:none; border-radius:3px 3px 0 0; letter-spacing:1px; padding:10px 25px 7px; background:#fe8900;">Horizontal</a>\
						</div>\
						<div style="display:none;" id="' + WE + 'PopupCode">\
							<span class="shbColGrey">&lt;script async defer&gt;</span><br><span class="shbColBlue">document.write(\'</span><span class="shbColGreen">&lt;script src="https://sharehulk.com/api/sharingbutton.php</span><span class="shbColBlue">?type=<span id="codeTextVertical" style="display: inline;">vertical</span><span id="codeTextHorizontal" style="display: none;">horizontal</span>&amp;u=\'</span><span class="shbColRed">+ encodeURIComponent</span><span class="shbColBlue">(document.location.href)</span> + </span><span class="shbColGreen">\'"&gt;&lt;/scr\'</span><span class="shbColBlue"> + </span><span class="shbColGreen">\'ipt&gt;\'</span><span class="shbColBlue">);</span><br><span class="shbColGrey">&lt;/script&gt;</span>\
						</div>\
						<div style="padding:10px 0; text-align:center;">\
							<span style="display:inline-block; color:#242424; font-size:16px; padding:14px 15px 8px 0; text-align:left;">Find a service to share:</span>\
							<input type="text" id="' + WE + 'PopupSearch" style="display: inline-block; border:none; border-bottom:1px solid #262626; outline:none; width:260px;">\
							<span style="display: inline-block; position: relative; margin: 3px; width: 36px; height: 36px; background: rgb(255, 255, 255); border-radius: 18px; left: 10px;"><a class="SharingButtonComplusLink" href="javascript:;" style="display: inline-block; margin: 2px; padding: 0px; width: 16px; height: 15px !important; vertical-align: bottom; background: url(&quot;https://sharehulk.com/api/img/index.png&quot;) -197px -56px; border: none;"></a></span>\
						</div>\
						<div id="' + WE + 'PopupContent">\
							<div id="' + WE + 'PopupContentInner">\
								<div id="' + WE + 'PopupContentSocBtns"></div>\
							</div>\
						</div>\
						<div style="text-align: center;margin-top: 15px;">\<a class="SharingButtonComplusLink" href="https://mcqf.blogspot.com" target="_blank" style="display: inline-block; width: 141px; height: 56px !important; vertical-align: bottom; background:url(&quot;https://drive.google.com/u/0/uc?id=1VMvqqeFNMGcFFH85YKiBjRJh4zAkLOOm&quot;) -10px -0px; border: none;"></a>\</div>\
					</div>\
				</table>\
			</div>\
		');
		
		var horizText = $('codeTextHorizontal');
		var vertText = $('codeTextVertical');
		
		var horizBtn = $('codeBtnHorizontal');
		var vertBtn = $('codeBtnVertical');
		
		var isHorizontal;
		
		var btnEnabledCss = {
			padding: '12px 25px 7px',
			background: '#fe8900'
		};
		
		var btnDisabledCss = {
			padding: '7px 25px',
			background: '#242d38'
		};
		
		on(horizBtn, 'click', function() {
			setCodePosition(true);
		});
		
		on(vertBtn, 'click', function() {
			setCodePosition(false);
		});
		
		function setCodePosition(isHoriz) {
			isHorizontal = isHoriz;
			
			if (isHoriz) {
				horizText.style.display = 'inline';
				vertText.style.display = 'none';
				
				css(horizBtn, btnEnabledCss);
				css(vertBtn, btnDisabledCss);
			} else {
				vertText.style.display = 'inline';
				horizText.style.display = 'none';
				
				css(vertBtn, btnEnabledCss);
				css(horizBtn, btnDisabledCss);
			}
		}
		
		setCodePosition(false);
		
		var codeNode = $(WE + 'PopupCode');
		on(codeNode, 'mouseup', function() {
			var codeType = (isHorizontal ? 'horiz' : 'vert');
			try {
				
				
				var range = document.createRange();
				range.selectNodeContents(codeNode);
				var sel = window.getSelection();
				sel.removeAllRanges();
				sel.addRange(range);
			} catch (err) {
				return;
			}
			
			on(document.body, 'mousedown', function mDown() {
				off(document.body, 'mousedown', mDown);
				
				if (window.getSelection) {
					var sel = window.getSelection();
					if (sel.empty) {  // Chrome
						sel.empty();
					} else if (sel.removeAllRanges) {  // Firefox
						sel.removeAllRanges();
					}
				} else if (document.selection) {  // IE?
					document.selection.empty();
				}
			});
		});
		var wr = $(WE + 'PopupWr');
		
		wr.appendChild($(WE + 'PopupTable'));
		wr.style.display = 'none';
		
		var crLink = $(WE + 'CopyrightLink');
		if (crLink) {
			css(crLink, {
				fontSize: '12px',
				color: '#414438',
				textDecoration: 'none'
			});
			crLink.onmouseover = function() {
				this.style.textDecoration = 'underline';
			}
			crLink.onmouseout = function() {
				this.style.textDecoration = 'none';
			}
		}
		
		on($(WE + 'PopupCloseBtn'), 'click', closePopup);
		
		var table = $(WE + 'PopupTable');
		css(table, {
			position: 'fixed',
			margin: 0,
			padding: 0,
			left: 0,
			top: 0,
			width: '100%',
			height: '100%',
			direction: 'ltr',
			zIndex: 9999999999,
			background: 'none'
		});
		css(table.getElementsByTagName('td')[0], {
			verticalAlign: 'middle',
			background: 'url(https://sharehulk.com/api/img/back.png)'
		});
		
		var popup = $(WE + 'Popup');
		css(popup, {
			margin: '30px auto',
			padding: '0px 20px 0px 20px',
			width: '80%',
			height: '70%',
            overflow: 'auto',
			maxWidth: '80vw',
			background: '#fff', 
			border: '1px solid #000',
			textAlign: 'left',
			position: 'relative',
			fontFamily: 'Tahoma, Arial, Verdana',
			boxSizing: 'content-box'
		});
		
		var content = $(WE + 'PopupContent');
		css(content, {
			position: 'relative',
			//width: '450px',
			height: '240px',
			maxHeight: '240px',
			overflowY: 'scroll'
		});
		content.onmousewheel = function(e) {
			if (
				e.wheelDelta < 0 && content.scrollTop + content.clientHeight ===  content.scrollHeight ||
				e.wheelDelta > 0 && content.scrollTop === 0
			) {
				e.preventDefault && e.preventDefault();
			}
		}
		
		var itemStyle = {
			display: 'inline-block',
			margin: 0,
			padding: '7px 0 5px 14px',
			width: '190px',
			verticalAlign: 'bottom',
			textAlign: 'left',
			textDecoration: 'none',
			boxSizing: 'content-box',
			border: 'none'
		};
		var onLinkMouseOver = function() {
			this.style.background = '#eee';
		}
		var onLinkMouseOut = function() {
			this.style.background = 'none';
		}
		var contentSocBtns = $(WE + 'PopupContentSocBtns');
		var position_icons = '';
		for (var i in socMap) {
			var soc = socMap[i];
			if (soc.plus) continue;

			<!-- new code for icon -->
			if(i == 'fb') position_icons='-138px -90px';
			if(i == 'tw') position_icons='-172px -158px';
			if(i == 'gp') position_icons='-36px -119px';

			if(i == 'em') position_icons='-104px -90px;';
			
			if(i == 'wp') position_icons='-104px -192px';

			if(i == 'go') position_icons='-2px -119px';

			if(i == 'te') position_icons='-104px -158px';

			if(i == 'li') position_icons='-104px -124px';

			if(i == 'tu') position_icons='-138px -158px';

			if(i == 'di') position_icons='-70px -90px';

			if(i == 're') position_icons='-36px -153px';

			if(i == 'vk') position_icons='-2px -187px';
			
			if(i == 'mr') position_icons='-172px -124px';

			if(i == 'de') position_icons='-36px -85px';

			if(i == 'gm') position_icons='-172px -90px';

			if(i == 'bl') position_icons='-2px -85px';

			if(i == 'lj') position_icons='-138px -124px';

			if(i == 'ba') position_icons='-129px -56px';

			if(i == 'am') position_icons='-95px -56px';

			if(i == 'bi') position_icons='-163px -56px';

			if(i == 'wh') position_icons='-70px -192px';

			if(i == 'gt') position_icons='-70px -124px';

			if(i == 'w3') position_icons='-36px -187px';

			if(i == 'sm') position_icons='-70px -158px';

			






			<!--End new code for icon -->	


			var a = create('a');
			//a.setAttribute('rel', 'nofollow');
			a.id = WE + i + 'PopupItem';
			a.innerHTML = '\
				<div style="border:none; vertical-align:baseline; margin:0; display:inherit; width:32px; height:32px;background: url(https://sharehulk.com/api/img/index.png) '+position_icons+'"></div>\
				<span style="vertical-align:baseline; font-size:14px; color:#6f6f6f; position:relative; top:-10px; padding-left:5px; font-weight:normal; text-decoration:none;">' + soc.name + '</span>\
			'; 
			css(a, itemStyle);
			if (mobOpt) {
				var img = a.getElementsByTagName('img')[0];
				css(img, {
					width: '16px',
					height: '16px'
				});
				var span = a.getElementsByTagName('span')[0];
				css(span, {
					display: 'inline-block',
					width: '82px',
					maxWidth: '82px',
					top: '2px',
					fontSize: '12px',
					whiteSpace: 'nowrap',
					overflow: 'hidden',
					textOverflow: 'ellipsis',
					verticalAlign: 'top'
				});
				css(a, {
					width: '113px',
					maxWidth: '113px',
					padding: '5px 0 3px 2px'
				});
			}
			append(a, contentSocBtns);
			a.onmouseover = onLinkMouseOver;
			a.onmouseout = onLinkMouseOut;
			
			if (soc.newTab) {
				a.href = handleUrl(soc.url, soc)
				a.setAttribute('rel', 'nofollow');
				a.target = '_blank';
			} else {
				a.href = 'javascript:;';
				handleItemClick(a, soc);
			}
		}
		
		on($(WE + 'PopupSearch'), 'input', function() {
			var input = this.value.toLowerCase();
			
			for (var i in socMap) {
				var soc = socMap[i];
				if (soc.plus) continue;
				var socName = soc.name.toLowerCase();
				var a = document.getElementById(WE + i + 'PopupItem');
				if (socName.indexOf(input) === 0) {
					a.style.display = 'inline-block';
				} else {
					a.style.display = 'none';
				}
			}
		});
		
		if (mobOpt) {
			$(WE + 'PopupLogo').style.width = 'auto';
			$(WE + 'PopupLogoWr').style.marginBottom = '5px';
			$(WE + 'PopupContentInner').style.width = '230px';
			css($(WE + 'PopupContent'), {
				width: '245px',
				height: '190px',
				maxHeight: '190px'
			});
			css($(WE + 'Popup'), {
				width: '245px',
				top: '-30px'
			});
			css($(WE + 'PopupSearch'), {
				width: '230px',
				maxWidth: '230px'
			});
		}
	}
	
	var handleItemClick = function(elem, socObj) {
		on(elem, 'click', function() {
			var url = handleUrl(socObj.url, socObj);
			openWin(url, socObj.win);
		});
	}
	
	var handleUrl = function(url, socObj) {
		var redirectUri = url
			.replace(/%URL/, getEncodedUrl())
			.replace(/%HOST/, location.host)
			.replace(/%MESSAGE/, encodeURIComponent(document.title))
			.replace(/%WE/, WE)
			.replace(/%FUNC/, socObj.func || '');
		
		return 'https://mcqf.blogspot.com?soc=' + encodeURIComponent(socObj.name) + '&redirect_uri=' + encodeURIComponent(redirectUri);
	}
	
	var findClassOne = function(parent, className) {
		return parent.getElementsByClassName(className)[0];
	}
	
	var getUrl = function() {
		return location.href;
	}
	
	var getEncodedUrl = function() {
		return encodeURIComponent(getUrl());
	}
	
	var openWin = function(path, popupSize) {
		if (!popupSize) {
			popupSize = {};
		}
		var w = popupSize.w || 650;
		var h = popupSize.h || 500;
		
		var l = window.screenX + (window.outerWidth - w) / 2;
		var t = window.screenY + (window.outerHeight - h) / 2;
		var winProps = 'width=' + w + ',height=' + h + ',left=' + l + ',top=' + t + ',status=no,resizable=yes,toolbar=no,menubar=no,scrollbars=yes';
		var win = window.open(path, 'sharePopup' + Math.random(), winProps);
		return win;
	}
	
	var closeOnEscape = function(e) {
		if (e.keyCode === 27) {
			closePopup();
		}
	}
	
	var addClass = function(node, className) {
		if (!node) return;
		if (!node.className) {
			node.className = className;
			return;
		}
		if ((' ' + node.className + ' ').indexOf(' ' + className + ' ') === -1) {
			node.className += ' ' + className;
		}
	}
	
	var removeClass = function(node, className) {
		if (node && node.className) {
			node.className = node.className.replace(new RegExp('\\b' + className + '\\b', 'g'), '');
		}
	}
	
	var openLinerPopup = function() {
		var pad = $(WE + 'PaddingWr');
		if (!pad) return;
		
		pad.style.display = 'block';
		
		var mainPopup = $(WE + 'PopupWr');
		if (!mainPopup) return;
		
		mainPopup.style.display = 'none';
	}
	
	var openMorePopup = function() {
		var liner = $(WE + 'PaddingWr');
		if (liner) {
			liner.style.display = 'none';
		}
		
		document.addEventListener('keydown', closeOnEscape);
		
		var wr = $(WE + 'PopupWr');
		wr.style.display = 'block';
		var parent = wr;
		while (parent = parent.parentNode) {
			if (!parent.style) break;
			parent.style.display = '';
			addClass(parent, WE + 'Parents');
		}
		$(WE + 'PopupSearch').focus();
	
		fixPopupSize();
	}

	var fixPopupSize = function() {
		$(WE + 'PopupCell').style.height = getWinSize().height + 'px';
	}
	
	var $ = function(id) {
		return document.getElementById(id);
	}
	
	var on = function(elem, event, handler) {
		elem.addEventListener(event, handler, false);
	}
	
	var off = function(elem, event, handler) {
		elem.removeEventListener(event, handler, false);
	}
	
	var css = function(elem, style) {
		for (var prop in style) {
			if(typeof elem != 'undefined' && elem != null)
				elem.style[prop] = style[prop]; 
		}
	}
	 
	var create = function(tag) {
		return document.createElement(tag);
	}
	
	var append = function(elem, parent) {
		parent.appendChild(elem);
	}
	
	var prepend = function(elem, parent) {
		if (parent.children && parent.children.length) {
			parent.insertBefore(elem, parent.children[0]);
		} else {
			parent.appendChild(elem);
		}
	}
	
	setTimeout(function() {
		
	}, 10);
	if (document.readyState === 'complete') {
		onReady();
	} else {
		on(document, 'DOMContentLoaded', onReady);
	}
	
	createPopup();
	createLinerPopup();
	
	try {
		clearStyles();
	} catch (ex) {}
	
})();

</script>
