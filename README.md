<!DOCTYPE html>

<html lang="en">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black">
    <meta name="mobile-web-app-capable" content="yes">
    <title>
        計程出題練習 report - HackMD
    </title>
    <link rel="icon" type="image/png" href="https://hackmd.io/favicon.png">
    <link rel="apple-touch-icon" href="https://hackmd.io/apple-touch-icon.png">

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha256-916EbMg70RQy9LHiGkXzG8hSg9EdNy97GazNG/aiY1w=" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" integrity="sha256-eZrrJcwDc/3uDhsdt61sL2oOBY362qM3lon1gyExkL0=" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/ionicons/2.0.1/css/ionicons.min.css" integrity="sha256-3iu9jgsy9TpTwXKb7bNQzqWekRX7pPK+2OLj3R922fo=" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/octicons/3.5.0/octicons.min.css" integrity="sha256-QiWfLIsCT02Sdwkogf6YMiQlj4NE84MKkzEMkZnMGdg=" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.5.1/themes/prism.min.css" integrity="sha256-vtR0hSWRc3Tb26iuN2oZHt3KRUomwTufNIf5/4oeCyg=" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@hackmd/emojify.js@2.1.0/dist/css/basic/emojify.min.css" integrity="sha256-UOrvMOsSDSrW6szVLe8ZDZezBxh5IoIfgTwdNDgTjiU=" crossorigin="anonymous" />
    <style>
        @import url(https://fonts.googleapis.com/css?family=Roboto:300,300i,400,400i,500,500i|Source+Code+Pro:300,400,500|Source+Sans+Pro:300,300i,400,400i,600,600i|Source+Serif+Pro&subset=latin-ext);.hljs{background:#fff;color:#333;display:block;overflow-x:auto;padding:.5em}.hljs-comment,.hljs-meta{color:#969896}.hljs-emphasis,.hljs-quote,.hljs-string,.hljs-strong,.hljs-template-variable,.hljs-variable{color:#df5000}.hljs-keyword,.hljs-selector-tag,.hljs-type{color:#a71d5d}.hljs-attribute,.hljs-bullet,.hljs-literal,.hljs-number,.hljs-symbol{color:#0086b3}.hljs-built_in,.hljs-builtin-name{color:#005cc5}.hljs-name,.hljs-section{color:#63a35c}.hljs-tag{color:#333}.hljs-attr,.hljs-selector-attr,.hljs-selector-class,.hljs-selector-id,.hljs-selector-pseudo,.hljs-title{color:#795da3}.hljs-addition{background-color:#eaffea;color:#55a532}.hljs-deletion{background-color:#ffecec;color:#bd2c00}.hljs-link{text-decoration:underline}.markdown-body{word-wrap:break-word;font-size:16px;line-height:1.5}.markdown-body:after,.markdown-body:before{content:"";display:table}.markdown-body:after{clear:both}.markdown-body>:first-child{margin-top:0!important}.markdown-body>:last-child{margin-bottom:0!important}.markdown-body a:not([href]){color:inherit;text-decoration:none}.markdown-body .absent{color:#c00}.markdown-body .anchor{float:left;line-height:1;margin-left:-20px;padding-right:4px}.markdown-body .anchor:focus{outline:none}.markdown-body blockquote,.markdown-body dl,.markdown-body ol,.markdown-body p,.markdown-body pre,.markdown-body table,.markdown-body ul{margin-bottom:16px;margin-top:0}.markdown-body hr{background-color:#e7e7e7;border:0;height:.25em;margin:24px 0;padding:0}.markdown-body blockquote{border-left:.25em solid #ddd;color:#777;font-size:16px;padding:0 1em}.markdown-body blockquote>:first-child{margin-top:0}.markdown-body blockquote>:last-child{margin-bottom:0}.markdown-body kbd,.popover kbd{background-color:#fcfcfc;border:1px solid;border-color:#ccc #ccc #bbb;border-radius:3px;box-shadow:inset 0 -1px 0 #bbb;color:#555;display:inline-block;font-size:11px;line-height:10px;padding:3px 5px;vertical-align:middle}.markdown-body .loweralpha{list-style-type:lower-alpha}.markdown-body h1,.markdown-body h2,.markdown-body h3,.markdown-body h4,.markdown-body h5,.markdown-body h6{font-weight:600;line-height:1.25;margin-bottom:16px;margin-top:24px}.markdown-body h1 .octicon-link,.markdown-body h2 .octicon-link,.markdown-body h3 .octicon-link,.markdown-body h4 .octicon-link,.markdown-body h5 .octicon-link,.markdown-body h6 .octicon-link{color:#000;vertical-align:middle;visibility:hidden}.markdown-body h1:hover .anchor,.markdown-body h2:hover .anchor,.markdown-body h3:hover .anchor,.markdown-body h4:hover .anchor,.markdown-body h5:hover .anchor,.markdown-body h6:hover .anchor{text-decoration:none}.markdown-body h1:hover .anchor .octicon-link,.markdown-body h2:hover .anchor .octicon-link,.markdown-body h3:hover .anchor .octicon-link,.markdown-body h4:hover .anchor .octicon-link,.markdown-body h5:hover .anchor .octicon-link,.markdown-body h6:hover .anchor .octicon-link{visibility:visible}.markdown-body h1 code,.markdown-body h1 tt,.markdown-body h2 code,.markdown-body h2 tt,.markdown-body h3 code,.markdown-body h3 tt,.markdown-body h4 code,.markdown-body h4 tt,.markdown-body h5 code,.markdown-body h5 tt,.markdown-body h6 code,.markdown-body h6 tt{font-size:inherit}.markdown-body h1{font-size:2em}.markdown-body h1,.markdown-body h2{border-bottom:1px solid #eee;padding-bottom:.3em}.markdown-body h2{font-size:1.5em}.markdown-body h3{font-size:1.25em}.markdown-body h4{font-size:1em}.markdown-body h5{font-size:.875em}.markdown-body h6{color:#777;font-size:.85em}.markdown-body ol,.markdown-body ul{padding-left:2em}.markdown-body ol.no-list,.markdown-body ul.no-list{list-style-type:none;padding:0}.markdown-body ol ol,.markdown-body ol ul,.markdown-body ul ol,.markdown-body ul ul{margin-bottom:0;margin-top:0}.markdown-body li>p{margin-top:16px}.markdown-body li+li{padding-top:.25em}.markdown-body dl{padding:0}.markdown-body dl dt{font-size:1em;font-style:italic;font-weight:700;margin-top:16px;padding:0}.markdown-body dl dd{margin-bottom:16px;padding:0 16px}.markdown-body table{display:block;overflow:auto;width:100%;word-break:normal;word-break:keep-all}.markdown-body table th{font-weight:700}.markdown-body table td,.markdown-body table th{border:1px solid #ddd;padding:6px 13px}.markdown-body table tr{background-color:#fff;border-top:1px solid #ccc}.markdown-body table tr:nth-child(2n){background-color:#f8f8f8}.markdown-body img{background-color:#fff;box-sizing:initial;max-width:100%}.markdown-body img[align=right]{padding-left:20px}.markdown-body img[align=left]{padding-right:20px}.markdown-body .emoji{background-color:initial;max-width:none;vertical-align:text-top}.markdown-body span.frame{display:block;overflow:hidden}.markdown-body span.frame>span{border:1px solid #ddd;display:block;float:left;margin:13px 0 0;overflow:hidden;padding:7px;width:auto}.markdown-body span.frame span img{display:block;float:left}.markdown-body span.frame span span{clear:both;color:#333;display:block;padding:5px 0 0}.markdown-body span.align-center{clear:both;display:block;overflow:hidden}.markdown-body span.align-center>span{display:block;margin:13px auto 0;overflow:hidden;text-align:center}.markdown-body span.align-center span img{margin:0 auto;text-align:center}.markdown-body span.align-right{clear:both;display:block;overflow:hidden}.markdown-body span.align-right>span{display:block;margin:13px 0 0;overflow:hidden;text-align:right}.markdown-body span.align-right span img{margin:0;text-align:right}.markdown-body span.float-left{display:block;float:left;margin-right:13px;overflow:hidden}.markdown-body span.float-left span{margin:13px 0 0}.markdown-body span.float-right{display:block;float:right;margin-left:13px;overflow:hidden}.markdown-body span.float-right>span{display:block;margin:13px auto 0;overflow:hidden;text-align:right}.markdown-body code,.markdown-body tt{background-color:#0000000a;border-radius:3px;font-size:85%;margin:0;padding:.2em 0}.markdown-body code:after,.markdown-body code:before,.markdown-body tt:after,.markdown-body tt:before{content:"\00a0";letter-spacing:-.2em}.markdown-body code br,.markdown-body tt br{display:none}.markdown-body del code{text-decoration:inherit}.markdown-body pre{word-wrap:normal}.markdown-body pre>code{background:#0000;border:0;font-size:100%;margin:0;padding:0;white-space:pre;word-break:normal}.markdown-body .highlight{margin-bottom:16px}.markdown-body .highlight pre{margin-bottom:0;word-break:normal}.markdown-body .highlight pre,.markdown-body pre{border-radius:3px;font-size:85%;line-height:1.45;overflow:auto}.markdown-body:not(.next-editor) pre{background-color:#f7f7f7;padding:16px}.markdown-body pre code,.markdown-body pre tt{word-wrap:normal;background-color:initial;border:0;display:inline;line-height:inherit;margin:0;max-width:auto;overflow:visible;padding:0}.markdown-body pre code:after,.markdown-body pre code:before,.markdown-body pre tt:after,.markdown-body pre tt:before{content:normal}.markdown-body .csv-data td,.markdown-body .csv-data th{font-size:12px;line-height:1;overflow:hidden;padding:5px;text-align:left;white-space:nowrap}.markdown-body .csv-data .blob-line-num{background:#fff;border:0;padding:10px 8px 9px;text-align:right}.markdown-body .csv-data tr{border-top:0}.markdown-body .csv-data th{background:#f8f8f8;border-top:0;font-weight:700}.news .alert .markdown-body blockquote{border:0;padding:0 0 0 40px}.activity-tab .news .alert .commits,.activity-tab .news .markdown-body blockquote{padding-left:0}.task-list-item{list-style-type:none}.task-list-item label{font-weight:400}.task-list-item.enabled label{cursor:pointer}.task-list-item+.task-list-item{margin-top:3px}.task-list-item-checkbox{cursor:default!important;float:left;margin:.31em 0 .2em -1.3em!important;vertical-align:middle}.markdown-body{max-width:758px;overflow:visible!important;padding-bottom:40px;padding-top:40px;position:relative}.markdown-body.next-editor{overflow-x:hidden!important}.markdown-body .emoji{vertical-align:top}.markdown-body pre{border:inherit!important}.markdown-body code{color:inherit!important}.markdown-body pre code .wrapper{display:-moz-inline-flex;display:-ms-inline-flex;display:-o-inline-flex;display:inline-flex}.markdown-body pre code .gutter{float:left;overflow:hidden;-webkit-user-select:none;user-select:none}.markdown-body pre code .gutter.linenumber{border-right:3px solid #6ce26c!important;box-sizing:initial;color:#afafaf!important;cursor:default;display:inline-block;min-width:20px;padding:0 8px 0 0;position:relative;text-align:right;z-index:4}.markdown-body pre code .gutter.linenumber>span:before{content:attr(data-linenumber)}.markdown-body pre code .code{float:left;margin:0 0 0 16px}.markdown-body .gist .line-numbers{border-bottom:none;border-left:none;border-top:none}.markdown-body .gist .line-data{border:none}.markdown-body .gist table{border-collapse:inherit!important;border-spacing:0}.markdown-body code[data-gist-id]{background:none;padding:0}.markdown-body code[data-gist-id]:after,.markdown-body code[data-gist-id]:before{content:""}.markdown-body code[data-gist-id] .blob-num{border:unset}.markdown-body code[data-gist-id] table{margin-bottom:unset;overflow:unset}.markdown-body code[data-gist-id] table tr{background:unset}.markdown-body[dir=rtl] pre{direction:ltr}.markdown-body[dir=rtl] code{direction:ltr;unicode-bidi:embed}.markdown-body .alert>p:last-child{margin-bottom:0}.markdown-body pre.abc,.markdown-body pre.flow-chart,.markdown-body pre.graphviz,.markdown-body pre.mermaid,.markdown-body pre.sequence-diagram,.markdown-body pre.vega{background-color:inherit;border-radius:0;overflow:visible;text-align:center;white-space:inherit}.markdown-body pre.abc>code,.markdown-body pre.flow-chart>code,.markdown-body pre.graphviz>code,.markdown-body pre.mermaid>code,.markdown-body pre.sequence-diagram>code,.markdown-body pre.vega>code{text-align:left}.markdown-body pre.abc>svg,.markdown-body pre.flow-chart>svg,.markdown-body pre.graphviz>svg,.markdown-body pre.mermaid>svg,.markdown-body pre.sequence-diagram>svg,.markdown-body pre.vega>svg{height:100%;max-width:100%}.markdown-body pre>code.wrap{word-wrap:break-word;white-space:pre-wrap;white-space:-moz-pre-wrap;white-space:-pre-wrap;white-space:-o-pre-wrap}.markdown-body .alert>p:last-child,.markdown-body .alert>ul:last-child{margin-bottom:0}.markdown-body summary{display:list-item}.markdown-body summary:focus{outline:none}.markdown-body details summary{cursor:pointer}.markdown-body details:not([open])>:not(summary){display:none}.markdown-body figure{margin:1em 40px}.markdown-body .mark,.markdown-body mark{background-color:#fff1a7}.vimeo,.youtube{background-color:#000;background-position:50%;background-repeat:no-repeat;background-size:contain;cursor:pointer;display:table;overflow:hidden;text-align:center}.vimeo,.youtube{position:relative;width:100%}.youtube{padding-bottom:56.25%}.vimeo img{object-fit:contain;width:100%;z-index:0}.youtube img{object-fit:cover;z-index:0}.vimeo iframe,.youtube iframe,.youtube img{height:100%;left:0;position:absolute;top:0;width:100%}.vimeo iframe,.youtube iframe{vertical-align:middle;z-index:1}.vimeo .icon,.youtube .icon{color:#fff;height:auto;left:50%;opacity:.3;position:absolute;top:50%;transform:translate(-50%,-50%);transition:opacity .2s;width:auto;z-index:0}.vimeo:hover .icon,.youtube:hover .icon{opacity:.6;transition:opacity .2s}.slideshare .inner,.speakerdeck .inner{position:relative;width:100%}.slideshare .inner iframe,.speakerdeck .inner iframe{bottom:0;height:100%;left:0;position:absolute;right:0;top:0;width:100%}.figma{display:table;padding-bottom:56.25%;position:relative;width:100%}.figma iframe{border:1px solid #eee;bottom:0;height:100%;left:0;position:absolute;right:0;top:0;width:100%}.markmap-container{height:300px}.markmap-container>svg{height:100%;width:100%}.MJX_Assistive_MathML{display:none}#MathJax_Message{z-index:1000!important}.ui-infobar{color:#777;margin:25px auto -25px;max-width:760px;position:relative;z-index:2}.toc .invisable-node{list-style-type:none}.ui-toc{bottom:20px;position:fixed;z-index:998}.ui-toc.both-mode{margin-left:8px}.ui-toc.both-mode .ui-toc-label{border-bottom-left-radius:0;border-top-left-radius:0;height:40px;padding:10px 4px}.ui-toc-label{background-color:#e6e6e6;border:none;color:#868686;transition:opacity .2s}.ui-toc .open .ui-toc-label{color:#fff;opacity:1;transition:opacity .2s}.ui-toc-label:focus{background-color:#ccc;color:#000;opacity:.3}.ui-toc-label:hover{background-color:#ccc;opacity:1;transition:opacity .2s}.ui-toc-dropdown{margin-bottom:20px;margin-top:20px;max-height:70vh;max-width:45vw;overflow:auto;padding-left:10px;padding-right:10px;text-align:inherit;width:25vw}.ui-toc-dropdown>.toc{max-height:calc(70vh - 100px);overflow:auto}.ui-toc-dropdown[dir=rtl] .nav{letter-spacing:.0029em;padding-right:0}.ui-toc-dropdown a{overflow:hidden;text-overflow:ellipsis;white-space:pre}.ui-toc-dropdown .nav>li>a{color:#767676;display:block;font-size:13px;font-weight:500;padding:4px 20px}.ui-toc-dropdown .nav>li:first-child:last-child>ul,.ui-toc-dropdown .toc.expand ul{display:block}.ui-toc-dropdown .nav>li>a:focus,.ui-toc-dropdown .nav>li>a:hover{background-color:initial;border-left:1px solid #000;color:#000;padding-left:19px;text-decoration:none}.ui-toc-dropdown[dir=rtl] .nav>li>a:focus,.ui-toc-dropdown[dir=rtl] .nav>li>a:hover{border-left:none;border-right:1px solid #000;padding-right:19px}.ui-toc-dropdown .nav>.active:focus>a,.ui-toc-dropdown .nav>.active:hover>a,.ui-toc-dropdown .nav>.active>a{background-color:initial;border-left:2px solid #000;color:#000;font-weight:700;padding-left:18px}.ui-toc-dropdown[dir=rtl] .nav>.active:focus>a,.ui-toc-dropdown[dir=rtl] .nav>.active:hover>a,.ui-toc-dropdown[dir=rtl] .nav>.active>a{border-left:none;border-right:2px solid #000;padding-right:18px}.ui-toc-dropdown .nav .nav{display:none;padding-bottom:10px}.ui-toc-dropdown .nav>.active>ul{display:block}.ui-toc-dropdown .nav .nav>li>a{font-size:12px;font-weight:400;padding-bottom:1px;padding-left:30px;padding-top:1px}.ui-toc-dropdown[dir=rtl] .nav .nav>li>a{padding-right:30px}.ui-toc-dropdown .nav .nav>li>ul>li>a{font-size:12px;font-weight:400;padding-bottom:1px;padding-left:40px;padding-top:1px}.ui-toc-dropdown[dir=rtl] .nav .nav>li>ul>li>a{padding-right:40px}.ui-toc-dropdown .nav .nav>li>a:focus,.ui-toc-dropdown .nav .nav>li>a:hover{padding-left:29px}.ui-toc-dropdown[dir=rtl] .nav .nav>li>a:focus,.ui-toc-dropdown[dir=rtl] .nav .nav>li>a:hover{padding-right:29px}.ui-toc-dropdown .nav .nav>li>ul>li>a:focus,.ui-toc-dropdown .nav .nav>li>ul>li>a:hover{padding-left:39px}.ui-toc-dropdown[dir=rtl] .nav .nav>li>ul>li>a:focus,.ui-toc-dropdown[dir=rtl] .nav .nav>li>ul>li>a:hover{padding-right:39px}.ui-toc-dropdown .nav .nav>.active:focus>a,.ui-toc-dropdown .nav .nav>.active:hover>a,.ui-toc-dropdown .nav .nav>.active>a{font-weight:500;padding-left:28px}.ui-toc-dropdown[dir=rtl] .nav .nav>.active:focus>a,.ui-toc-dropdown[dir=rtl] .nav .nav>.active:hover>a,.ui-toc-dropdown[dir=rtl] .nav .nav>.active>a{padding-right:28px}.ui-toc-dropdown .nav .nav>.active>.nav>.active:focus>a,.ui-toc-dropdown .nav .nav>.active>.nav>.active:hover>a,.ui-toc-dropdown .nav .nav>.active>.nav>.active>a{font-weight:500;padding-left:38px}.ui-toc-dropdown[dir=rtl] .nav .nav>.active>.nav>.active:focus>a,.ui-toc-dropdown[dir=rtl] .nav .nav>.active>.nav>.active:hover>a,.ui-toc-dropdown[dir=rtl] .nav .nav>.active>.nav>.active>a{padding-right:38px}.markdown-body{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol}html[lang^=ja] .markdown-body{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,Hiragino Kaku Gothic Pro,ヒラギノ角ゴ Pro W3,Osaka,Meiryo,メイリオ,MS Gothic,ＭＳ ゴシック,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol}html[lang=zh-tw] .markdown-body{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,PingFang TC,Microsoft JhengHei,微軟正黑,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol}html[lang=zh-cn] .markdown-body{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,PingFang SC,Microsoft YaHei,微软雅黑,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol}html .markdown-body[lang^=ja]{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,Hiragino Kaku Gothic Pro,ヒラギノ角ゴ Pro W3,Osaka,Meiryo,メイリオ,MS Gothic,ＭＳ ゴシック,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol}html .markdown-body[lang=zh-tw]{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,PingFang TC,Microsoft JhengHei,微軟正黑,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol}html .markdown-body[lang=zh-cn]{font-family:-apple-system,BlinkMacSystemFont,Segoe UI,Helvetica Neue,Helvetica,Roboto,Arial,PingFang SC,Microsoft YaHei,微软雅黑,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol}html[lang^=ja] .ui-toc-dropdown{font-family:Source Sans Pro,Helvetica,Arial,Meiryo UI,MS PGothic,ＭＳ Ｐゴシック,sans-serif}html[lang=zh-tw] .ui-toc-dropdown{font-family:Source Sans Pro,Helvetica,Arial,Microsoft JhengHei UI,微軟正黑UI,sans-serif}html[lang=zh-cn] .ui-toc-dropdown{font-family:Source Sans Pro,Helvetica,Arial,Microsoft YaHei UI,微软雅黑UI,sans-serif}html .ui-toc-dropdown[lang^=ja]{font-family:Source Sans Pro,Helvetica,Arial,Meiryo UI,MS PGothic,ＭＳ Ｐゴシック,sans-serif}html .ui-toc-dropdown[lang=zh-tw]{font-family:Source Sans Pro,Helvetica,Arial,Microsoft JhengHei UI,微軟正黑UI,sans-serif}html .ui-toc-dropdown[lang=zh-cn]{font-family:Source Sans Pro,Helvetica,Arial,Microsoft YaHei UI,微软雅黑UI,sans-serif}.ui-affix-toc{max-height:70vh;max-width:15vw;overflow:auto;position:fixed;top:0}.back-to-top,.expand-toggle,.go-to-bottom{color:#999;display:block;font-size:12px;font-weight:500;margin-left:10px;margin-top:10px;padding:4px 10px}.back-to-top:focus,.back-to-top:hover,.expand-toggle:focus,.expand-toggle:hover,.go-to-bottom:focus,.go-to-bottom:hover{color:#563d7c;text-decoration:none}.back-to-top,.go-to-bottom{margin-top:0}.ui-user-icon{background-position:50%;background-repeat:no-repeat;background-size:cover;border-radius:50%;display:block;height:20px;margin-bottom:2px;margin-right:5px;margin-top:2px;width:20px}.ui-user-icon.small{display:inline-block;height:18px;margin:0 0 .2em;vertical-align:middle;width:18px}.ui-infobar>small>span{line-height:22px}.ui-infobar>small .dropdown{display:inline-block}.ui-infobar>small .dropdown a:focus,.ui-infobar>small .dropdown a:hover{text-decoration:none}.ui-more-info{color:#888;cursor:pointer;vertical-align:middle}.ui-more-info .fa{font-size:16px}.ui-connectedGithub,.ui-published-note{color:#888}.ui-connectedGithub{line-height:23px;white-space:nowrap}.ui-connectedGithub a.file-path{color:#888;padding-left:22px;text-decoration:none}.ui-connectedGithub a.file-path:active,.ui-connectedGithub a.file-path:hover{color:#888;text-decoration:underline}.ui-connectedGithub .fa{font-size:20px}.ui-published-note .fa{font-size:20px;vertical-align:top}.unselectable{-webkit-user-select:none;-o-user-select:none;user-select:none}.selectable{-webkit-user-select:text;-o-user-select:text;user-select:text}.inline-spoiler-section{cursor:pointer}.inline-spoiler-section .spoiler-text{background-color:#333;border-radius:2px}.inline-spoiler-section .spoiler-text>*{opacity:0}.inline-spoiler-section .spoiler-img{filter:blur(10px)}.inline-spoiler-section.raw{background-color:#333;border-radius:2px}.inline-spoiler-section.raw>*{opacity:0}.inline-spoiler-section.unveil{cursor:auto}.inline-spoiler-section.unveil .spoiler-text{background-color:#3333331a}.inline-spoiler-section.unveil .spoiler-text>*{opacity:1}.inline-spoiler-section.unveil .spoiler-img{filter:none}@media print{blockquote,div,img,pre,table{page-break-inside:avoid!important}a[href]:after{font-size:12px!important}}.markdown-body.slides{color:#222;position:relative;z-index:1}.markdown-body.slides:before{background-color:currentColor;bottom:0;box-shadow:0 0 0 50vw;content:"";display:block;left:0;position:absolute;right:0;top:0;z-index:-1}.markdown-body.slides section[data-markdown]{background-color:#fff;margin-bottom:1.5em;position:relative;text-align:center}.markdown-body.slides section[data-markdown] code{text-align:left}.markdown-body.slides section[data-markdown]:before{content:"";display:block;padding-bottom:56.23%}.markdown-body.slides section[data-markdown]>div:first-child{left:1em;max-height:100%;overflow:hidden;position:absolute;right:1em;top:50%;transform:translateY(-50%)}.markdown-body.slides section[data-markdown]>ul{display:inline-block}.markdown-body.slides>section>section+section:after{border:3px solid #777;content:"";height:1.5em;position:absolute;right:1em;top:-1.5em}.site-ui-font{font-family:Source Sans Pro,Helvetica,Arial,sans-serif}html[lang^=ja] .site-ui-font{font-family:Source Sans Pro,Helvetica,Arial,Hiragino Kaku Gothic Pro,ヒラギノ角ゴ Pro W3,Osaka,Meiryo,メイリオ,MS Gothic,ＭＳ ゴシック,sans-serif}html[lang=zh-tw] .site-ui-font{font-family:Source Sans Pro,Helvetica,Arial,PingFang TC,Microsoft JhengHei,微軟正黑,sans-serif}html[lang=zh-cn] .site-ui-font{font-family:Source Sans Pro,Helvetica,Arial,PingFang SC,Microsoft YaHei,微软雅黑,sans-serif}body{font-smoothing:subpixel-antialiased!important;-webkit-font-smoothing:subpixel-antialiased!important;-moz-osx-font-smoothing:auto!important;-webkit-overflow-scrolling:touch;font-family:Source Sans Pro,Helvetica,Arial,sans-serif;letter-spacing:.025em}html[lang^=ja] body{font-family:Source Sans Pro,Helvetica,Arial,Hiragino Kaku Gothic Pro,ヒラギノ角ゴ Pro W3,Osaka,Meiryo,メイリオ,MS Gothic,ＭＳ ゴシック,sans-serif}html[lang=zh-tw] body{font-family:Source Sans Pro,Helvetica,Arial,PingFang TC,Microsoft JhengHei,微軟正黑,sans-serif}html[lang=zh-cn] body{font-family:Source Sans Pro,Helvetica,Arial,PingFang SC,Microsoft YaHei,微软雅黑,sans-serif}abbr[title]{border-bottom:none;text-decoration:underline;-webkit-text-decoration:underline dotted;text-decoration:underline dotted}abbr[data-original-title],abbr[title]{cursor:help}body.modal-open{overflow-y:auto;padding-right:0!important}svg{text-shadow:none}
    </style>
    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
    	<script src="https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv.min.js" integrity="sha256-3Jy/GbSLrg0o9y5Z5n1uw0qxZECH7C6OQpVBgNFYa0g=" crossorigin="anonymous"></script>
    	<script src="https://cdnjs.cloudflare.com/ajax/libs/respond.js/1.4.2/respond.min.js" integrity="sha256-g6iAfvZp+nDQ2TdTR/VVKJf3bGro4ub5fvWSWVRi2NE=" crossorigin="anonymous"></script>
		<script src="https://cdnjs.cloudflare.com/ajax/libs/es5-shim/4.5.9/es5-shim.min.js" integrity="sha256-8E4Is26QH0bD52WoQpcB+R/tcWQtpzlCojrybUd7Mxo=" crossorigin="anonymous"></script>
    <![endif]-->
</head>

<body>
    <div id="doc" class="markdown-body container-fluid comment-enabled" data-hard-breaks="true"><h1 id="Problem" data-id="Problem"><a class="anchor hidden-xs" href="#Problem" title="Problem"><span class="octicon octicon-link"></span></a><span>Problem</span></h1><p><span>給定一個包含</span><span class="mathjax"><span class="MathJax_Preview" style="color: inherit;"></span><span id="MathJax-Element-1-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" style="font-size: 113%; position: relative;" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mi>n</mi></math>" role="presentation"><span id="MJXc-Node-1" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-2" class="mjx-mrow"><span id="MJXc-Node-3" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.224em; padding-bottom: 0.279em;">n</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>n</mi></math></span></span><script type="math/tex" id="MathJax-Element-1">n</script></span><span>個整數的陣列，找出一段</span><strong><span>連續</span></strong><span>的區間，使得該區間中的數字總和達到最大，並輸出該最大的總和。</span></p><h1 id="Solutions" data-id="Solutions"><a class="anchor hidden-xs" href="#Solutions" title="Solutions"><span class="octicon octicon-link"></span></a><span>Solutions</span></h1><h2 id="穩扎穩打-The-naïve-method" data-id="穩扎穩打-The-naïve-method"><a class="anchor hidden-xs" href="#穩扎穩打-The-naïve-method" title="穩扎穩打-The-naïve-method"><span class="octicon octicon-link"></span></a><span>穩扎穩打 The naïve method</span></h2><p><span>最直接的暴力法。我們可以對陣列中的每一個數字分別找到「以它為起點，最大的區間總和」。</span></p><p><span>總共 </span><span class="mathjax"><span class="MathJax_Preview" style="color: inherit;"></span><span id="MathJax-Element-2-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" style="font-size: 113%; position: relative;" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mi>n</mi></math>" role="presentation"><span id="MJXc-Node-4" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-5" class="mjx-mrow"><span id="MJXc-Node-6" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.224em; padding-bottom: 0.279em;">n</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>n</mi></math></span></span><script type="math/tex" id="MathJax-Element-2">n</script></span><span> 個數字，對於第 </span><span class="mathjax"><span class="MathJax_Preview" style="color: inherit;"></span><span id="MathJax-Element-3-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" style="font-size: 113%; position: relative;" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mi>k</mi></math>" role="presentation"><span id="MJXc-Node-7" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-8" class="mjx-mrow"><span id="MJXc-Node-9" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.445em; padding-bottom: 0.279em;">k</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>k</mi></math></span></span><script type="math/tex" id="MathJax-Element-3">k</script></span><span> 個數字，需計算 </span><span class="mathjax"><span class="MathJax_Preview" style="color: inherit;"></span><span id="MathJax-Element-4-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" style="font-size: 113%; position: relative;" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mi>n</mi><mo>&amp;#x2212;</mo><mi>k</mi><mo>+</mo><mn>1</mn></math>" role="presentation"><span id="MJXc-Node-10" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-11" class="mjx-mrow"><span id="MJXc-Node-12" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.224em; padding-bottom: 0.279em;">n</span></span><span id="MJXc-Node-13" class="mjx-mo MJXc-space2"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.279em; padding-bottom: 0.445em;">−</span></span><span id="MJXc-Node-14" class="mjx-mi MJXc-space2"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.445em; padding-bottom: 0.279em;">k</span></span><span id="MJXc-Node-15" class="mjx-mo MJXc-space2"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.279em; padding-bottom: 0.445em;">+</span></span><span id="MJXc-Node-16" class="mjx-mn MJXc-space2"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.39em; padding-bottom: 0.335em;">1</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>n</mi><mo>−</mo><mi>k</mi><mo>+</mo><mn>1</mn></math></span></span><script type="math/tex" id="MathJax-Element-4">n-k+1</script></span><span> 個區間。總時間複雜度為 </span><span class="mathjax"><span class="MathJax_Preview" style="color: inherit;"></span><span id="MathJax-Element-5-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" style="font-size: 113%; position: relative;" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mi>O</mi><mo stretchy=&quot;false&quot;>(</mo><msup><mi>n</mi><mn>2</mn></msup><mo stretchy=&quot;false&quot;>)</mo></math>" role="presentation"><span id="MJXc-Node-17" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-18" class="mjx-mrow"><span id="MJXc-Node-19" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.501em; padding-bottom: 0.279em;">O</span></span><span id="MJXc-Node-20" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.445em; padding-bottom: 0.611em;">(</span></span><span id="MJXc-Node-21" class="mjx-msubsup"><span class="mjx-base"><span id="MJXc-Node-22" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.224em; padding-bottom: 0.279em;">n</span></span></span><span class="mjx-sup" style="font-size: 70.7%; vertical-align: 0.513em; padding-left: 0px; padding-right: 0.071em;"><span id="MJXc-Node-23" class="mjx-mn" style=""><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.39em; padding-bottom: 0.335em;">2</span></span></span></span><span id="MJXc-Node-24" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.445em; padding-bottom: 0.611em;">)</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>O</mi><mo stretchy="false">(</mo><msup><mi>n</mi><mn>2</mn></msup><mo stretchy="false">)</mo></math></span></span><script type="math/tex" id="MathJax-Element-5">O(n^2)</script></span><span> 。</span><br>
<span class="mathjax"><span class="MathJax_Preview" style="color: inherit;"></span><span class="mjx-chtml MJXc-display" style="text-align: center;"><span id="MathJax-Element-6-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" style="font-size: 113%; text-align: center; position: relative;" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot; display=&quot;block&quot;><munderover><mo>&amp;#x2211;</mo><mrow class=&quot;MJX-TeXAtom-ORD&quot;><mi>k</mi><mo>=</mo><mn>1</mn></mrow><mi>n</mi></munderover><mi>k</mi><mo>=</mo><mfrac><mrow><mi>n</mi><mo stretchy=&quot;false&quot;>(</mo><mi>n</mi><mo>+</mo><mn>1</mn><mo stretchy=&quot;false&quot;>)</mo></mrow><mn>2</mn></mfrac><mo>=</mo><mi>O</mi><mo stretchy=&quot;false&quot;>(</mo><msup><mi>n</mi><mn>2</mn></msup><mo stretchy=&quot;false&quot;>)</mo></math>" role="presentation"><span id="MJXc-Node-25" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-26" class="mjx-mrow"><span id="MJXc-Node-27" class="mjx-munderover"><span class="mjx-itable"><span class="mjx-row"><span class="mjx-cell"><span class="mjx-stack"><span class="mjx-over" style="font-size: 70.7%; padding-bottom: 0.247em; padding-top: 0.141em; padding-left: 0.721em;"><span id="MJXc-Node-34" class="mjx-mi" style=""><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.224em; padding-bottom: 0.279em;">n</span></span></span><span class="mjx-op"><span id="MJXc-Node-28" class="mjx-mo"><span class="mjx-char MJXc-TeX-size2-R" style="padding-top: 0.722em; padding-bottom: 0.722em;">∑</span></span></span></span></span></span><span class="mjx-row"><span class="mjx-under" style="font-size: 70.7%; padding-top: 0.236em; padding-bottom: 0.141em; padding-left: 0.122em;"><span id="MJXc-Node-29" class="mjx-texatom" style=""><span id="MJXc-Node-30" class="mjx-mrow"><span id="MJXc-Node-31" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.445em; padding-bottom: 0.279em;">k</span></span><span id="MJXc-Node-32" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.058em; padding-bottom: 0.335em;">=</span></span><span id="MJXc-Node-33" class="mjx-mn"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.39em; padding-bottom: 0.335em;">1</span></span></span></span></span></span></span></span><span id="MJXc-Node-35" class="mjx-mi MJXc-space1"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.445em; padding-bottom: 0.279em;">k</span></span><span id="MJXc-Node-36" class="mjx-mo MJXc-space3"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.058em; padding-bottom: 0.335em;">=</span></span><span id="MJXc-Node-37" class="mjx-mfrac MJXc-space3"><span class="mjx-box MJXc-stacked" style="width: 3.9em; padding: 0px 0.12em;"><span class="mjx-numerator" style="width: 3.9em; top: -1.533em;"><span id="MJXc-Node-38" class="mjx-mrow"><span id="MJXc-Node-39" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.224em; padding-bottom: 0.279em;">n</span></span><span id="MJXc-Node-40" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.445em; padding-bottom: 0.611em;">(</span></span><span id="MJXc-Node-41" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.224em; padding-bottom: 0.279em;">n</span></span><span id="MJXc-Node-42" class="mjx-mo MJXc-space2"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.279em; padding-bottom: 0.445em;">+</span></span><span id="MJXc-Node-43" class="mjx-mn MJXc-space2"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.39em; padding-bottom: 0.335em;">1</span></span><span id="MJXc-Node-44" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.445em; padding-bottom: 0.611em;">)</span></span></span></span><span class="mjx-denominator" style="width: 3.9em; bottom: -0.711em;"><span id="MJXc-Node-45" class="mjx-mn"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.39em; padding-bottom: 0.335em;">2</span></span></span><span class="mjx-line" style="border-bottom: 1.3px solid; top: -0.285em; width: 3.9em;"></span></span><span class="mjx-vsize" style="height: 2.244em; vertical-align: -0.711em;"></span></span><span id="MJXc-Node-46" class="mjx-mo MJXc-space3"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.058em; padding-bottom: 0.335em;">=</span></span><span id="MJXc-Node-47" class="mjx-mi MJXc-space3"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.501em; padding-bottom: 0.279em;">O</span></span><span id="MJXc-Node-48" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.445em; padding-bottom: 0.611em;">(</span></span><span id="MJXc-Node-49" class="mjx-msubsup"><span class="mjx-base"><span id="MJXc-Node-50" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.224em; padding-bottom: 0.279em;">n</span></span></span><span class="mjx-sup" style="font-size: 70.7%; vertical-align: 0.584em; padding-left: 0px; padding-right: 0.071em;"><span id="MJXc-Node-51" class="mjx-mn" style=""><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.39em; padding-bottom: 0.335em;">2</span></span></span></span><span id="MJXc-Node-52" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.445em; padding-bottom: 0.611em;">)</span></span></span></span><span class="MJX_Assistive_MathML MJX_Assistive_MathML_Block" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><munderover><mo>∑</mo><mrow class="MJX-TeXAtom-ORD"><mi>k</mi><mo>=</mo><mn>1</mn></mrow><mi>n</mi></munderover><mi>k</mi><mo>=</mo><mfrac><mrow><mi>n</mi><mo stretchy="false">(</mo><mi>n</mi><mo>+</mo><mn>1</mn><mo stretchy="false">)</mo></mrow><mn>2</mn></mfrac><mo>=</mo><mi>O</mi><mo stretchy="false">(</mo><msup><mi>n</mi><mn>2</mn></msup><mo stretchy="false">)</mo></math></span></span></span><script type="math/tex; mode=display" id="MathJax-Element-6">
\sum_{k=1}^n k = \frac{n(n+1)}{2}=O(n^2)
</script></span></p><h3 id="優化方向" data-id="優化方向"><a class="anchor hidden-xs" href="#優化方向" title="優化方向"><span class="octicon octicon-link"></span></a><span>優化方向</span></h3><p><span>如果目前的起點是負數，而上一個起點是正數，就可以跳過了。</span></p><div class="alert alert-danger">
<p><span>對於</span><span class="mathjax"><span class="MathJax_Preview" style="color: inherit;"></span><span id="MathJax-Element-7-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" style="font-size: 113%; position: relative;" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mi>n</mi></math>" role="presentation"><span id="MJXc-Node-53" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-54" class="mjx-mrow"><span id="MJXc-Node-55" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.224em; padding-bottom: 0.279em;">n</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>n</mi></math></span></span><script type="math/tex" id="MathJax-Element-7">n</script></span><span>較大的測資，</span><span class="mathjax"><span class="MathJax_Preview" style="color: inherit;"></span><span id="MathJax-Element-8-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" style="font-size: 113%; position: relative;" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mi>O</mi><mo stretchy=&quot;false&quot;>(</mo><msup><mi>n</mi><mn>2</mn></msup><mo stretchy=&quot;false&quot;>)</mo></math>" role="presentation"><span id="MJXc-Node-56" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-57" class="mjx-mrow"><span id="MJXc-Node-58" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.501em; padding-bottom: 0.279em;">O</span></span><span id="MJXc-Node-59" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.445em; padding-bottom: 0.611em;">(</span></span><span id="MJXc-Node-60" class="mjx-msubsup"><span class="mjx-base"><span id="MJXc-Node-61" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.224em; padding-bottom: 0.279em;">n</span></span></span><span class="mjx-sup" style="font-size: 70.7%; vertical-align: 0.513em; padding-left: 0px; padding-right: 0.071em;"><span id="MJXc-Node-62" class="mjx-mn" style=""><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.39em; padding-bottom: 0.335em;">2</span></span></span></span><span id="MJXc-Node-63" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.445em; padding-bottom: 0.611em;">)</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>O</mi><mo stretchy="false">(</mo><msup><mi>n</mi><mn>2</mn></msup><mo stretchy="false">)</mo></math></span></span><script type="math/tex" id="MathJax-Element-8">O(n^2)</script></span><span>的演算法可能會超過時間限制</span></p>
</div><h2 id="前綴和-Prefix-Sum" data-id="前綴和-Prefix-Sum"><a class="anchor hidden-xs" href="#前綴和-Prefix-Sum" title="前綴和-Prefix-Sum"><span class="octicon octicon-link"></span></a><span>前綴和 Prefix Sum</span></h2><p><span>因為我們想要知道區間的總和，直觀上，我們可以先計算整個陣列的前綴和。如果把前綴和畫成一個折線圖，橫軸代表從第一個數字開始計算的前綴和，這條線看起來會上上下下波動（出現正數則前綴和增加、反之亦然）。</span><br><br>
<img src="https://hackmd.io/_uploads/HkNVVGwka.png" alt="" loading="lazy"><br>
<span>示意圖</span><br><br>
<span>在這張圖中，從線上取兩點，兩點之間前綴和的差距就是該區間的總和。所以，從這條線的最低點拉到最高點之間，就是我們想要找的總和最大的區間！</span><br><br>
<span>計算前綴和以及尋找其中的最小、最大值都是</span><span class="mathjax"><span class="MathJax_Preview" style="color: inherit;"></span><span id="MathJax-Element-19-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" style="font-size: 113%; position: relative;" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mi>O</mi><mo stretchy=&quot;false&quot;>(</mo><mi>n</mi><mo stretchy=&quot;false&quot;>)</mo></math>" role="presentation"><span id="MJXc-Node-106" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-107" class="mjx-mrow"><span id="MJXc-Node-108" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.501em; padding-bottom: 0.279em;">O</span></span><span id="MJXc-Node-109" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.445em; padding-bottom: 0.611em;">(</span></span><span id="MJXc-Node-110" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.224em; padding-bottom: 0.279em;">n</span></span><span id="MJXc-Node-111" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.445em; padding-bottom: 0.611em;">)</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>O</mi><mo stretchy="false">(</mo><mi>n</mi><mo stretchy="false">)</mo></math></span></span><script type="math/tex" id="MathJax-Element-19">O(n)</script></span><span>的操作，看來我們成功找到了有效率的解法···</span><br></p><p><span>or… did we?</span><br></p><div class="alert alert-danger">
<p><span>若最高點出現在最低點之前，該區間就不會是正確答案（總和是負的）。</span></p>
</div><h2 id="正確解法-The-correct-method" data-id="正確解法-The-correct-method"><a class="anchor hidden-xs" href="#正確解法-The-correct-method" title="正確解法-The-correct-method"><span class="octicon octicon-link"></span></a><span>正確解法 The correct method</span></h2><p><span>我們可以先想想：「如果知道陣列中</span><strong><span>第 </span><span class="mathjax"><span class="MathJax_Preview" style="color: inherit;"></span><span id="MathJax-Element-10-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" style="font-size: 113%; position: relative;" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mn>1</mn></math>" role="presentation"><span id="MJXc-Node-70" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-71" class="mjx-mrow"><span id="MJXc-Node-72" class="mjx-mn"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.39em; padding-bottom: 0.335em;">1</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>1</mn></math></span></span><script type="math/tex" id="MathJax-Element-10">1</script></span><span> 到 </span><span class="mathjax"><span class="MathJax_Preview" style="color: inherit;"></span><span id="MathJax-Element-11-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" style="font-size: 113%; position: relative;" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mi>k</mi><mo>&amp;#x2212;</mo><mn>1</mn></math>" role="presentation"><span id="MJXc-Node-73" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-74" class="mjx-mrow"><span id="MJXc-Node-75" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.445em; padding-bottom: 0.279em;">k</span></span><span id="MJXc-Node-76" class="mjx-mo MJXc-space2"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.279em; padding-bottom: 0.445em;">−</span></span><span id="MJXc-Node-77" class="mjx-mn MJXc-space2"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.39em; padding-bottom: 0.335em;">1</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>k</mi><mo>−</mo><mn>1</mn></math></span></span><script type="math/tex" id="MathJax-Element-11">k - 1</script></span><span> 個元素的最大連續區間和</span></strong><span>，是否可以知道第 </span><span class="mathjax"><span class="MathJax_Preview" style="color: inherit;"></span><span id="MathJax-Element-12-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" style="font-size: 113%; position: relative;" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mn>1</mn></math>" role="presentation"><span id="MJXc-Node-78" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-79" class="mjx-mrow"><span id="MJXc-Node-80" class="mjx-mn"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.39em; padding-bottom: 0.335em;">1</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mn>1</mn></math></span></span><script type="math/tex" id="MathJax-Element-12">1</script></span><span> 到 </span><span class="mathjax"><span class="MathJax_Preview" style="color: inherit;"></span><span id="MathJax-Element-13-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" style="font-size: 113%; position: relative;" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mi>k</mi></math>" role="presentation"><span id="MJXc-Node-81" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-82" class="mjx-mrow"><span id="MJXc-Node-83" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.445em; padding-bottom: 0.279em;">k</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>k</mi></math></span></span><script type="math/tex" id="MathJax-Element-13">k</script></span><span> 的最大連續區間和？」</span><br><br>
<span>答案是幾乎可以，但差一步。</span><br><br>
<span>我們將答案的區分為以下兩種狀況：</span></p><ol>
<li><span>此最大和不包含第 </span><span class="mathjax"><span class="MathJax_Preview" style="color: inherit;"></span><span id="MathJax-Element-14-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" style="font-size: 113%; position: relative;" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mi>k</mi></math>" role="presentation"><span id="MJXc-Node-84" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-85" class="mjx-mrow"><span id="MJXc-Node-86" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.445em; padding-bottom: 0.279em;">k</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>k</mi></math></span></span><script type="math/tex" id="MathJax-Element-14">k</script></span><span> 元素 </span><span class="mathjax"><span class="MathJax_Preview" style="color: inherit;"></span><span id="MathJax-Element-15-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" style="font-size: 113%; position: relative;" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><msub><mi>a</mi><mi>k</mi></msub></math>" role="presentation"><span id="MJXc-Node-87" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-88" class="mjx-mrow"><span id="MJXc-Node-89" class="mjx-msubsup"><span class="mjx-base"><span id="MJXc-Node-90" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.224em; padding-bottom: 0.279em;">a</span></span></span><span class="mjx-sub" style="font-size: 70.7%; vertical-align: -0.219em; padding-right: 0.071em;"><span id="MJXc-Node-91" class="mjx-mi" style=""><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.445em; padding-bottom: 0.279em;">k</span></span></span></span></span></span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>a</mi><mi>k</mi></msub></math></span></span><script type="math/tex" id="MathJax-Element-15">a_k</script></span></li>
<li><span>此最大和包含第 </span><span class="mathjax"><span class="MathJax_Preview" style="color: inherit;"></span><span id="MathJax-Element-16-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" style="font-size: 113%; position: relative;" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mi>k</mi></math>" role="presentation"><span id="MJXc-Node-92" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-93" class="mjx-mrow"><span id="MJXc-Node-94" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.445em; padding-bottom: 0.279em;">k</span></span></span></span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>k</mi></math></span></span><script type="math/tex" id="MathJax-Element-16">k</script></span><span> 元素 </span><span class="mathjax"><span class="MathJax_Preview" style="color: inherit;"></span><span id="MathJax-Element-17-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" style="font-size: 113%; position: relative;" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><msub><mi>a</mi><mi>k</mi></msub></math>" role="presentation"><span id="MJXc-Node-95" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-96" class="mjx-mrow"><span id="MJXc-Node-97" class="mjx-msubsup"><span class="mjx-base"><span id="MJXc-Node-98" class="mjx-mi"><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.224em; padding-bottom: 0.279em;">a</span></span></span><span class="mjx-sub" style="font-size: 70.7%; vertical-align: -0.219em; padding-right: 0.071em;"><span id="MJXc-Node-99" class="mjx-mi" style=""><span class="mjx-char MJXc-TeX-math-I" style="padding-top: 0.445em; padding-bottom: 0.279em;">k</span></span></span></span></span></span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><msub><mi>a</mi><mi>k</mi></msub></math></span></span><script type="math/tex" id="MathJax-Element-17">a_k</script></span></li>
</ol><p><span>那麼很顯然的，第一種可能性的答案就是原先第 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-91"><span class="MJXp-mn" id="MJXp-Span-92">1</span></span></span><script type="math/tex" id="MathJax-Element-20">1</script></span><span> 到 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-93"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-94">k</span><span class="MJXp-mo" id="MJXp-Span-95" style="margin-left: 0.267em; margin-right: 0.267em;">−</span><span class="MJXp-mn" id="MJXp-Span-96">1</span></span></span><script type="math/tex" id="MathJax-Element-21">k-1</script></span><span> 個元素中的最大連續區間和。但問題是第二種可能性呢？如果答案包含第 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-97"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-98">k</span></span></span><script type="math/tex" id="MathJax-Element-22">k</script></span><span> 元素，代表我們需要知道包含第 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-99"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-100">k</span><span class="MJXp-mo" id="MJXp-Span-101" style="margin-left: 0.267em; margin-right: 0.267em;">−</span><span class="MJXp-mn" id="MJXp-Span-102">1</span></span></span><script type="math/tex" id="MathJax-Element-23">k - 1</script></span><span> 個元素時，所能求得的最大連續區間和(當然，如果答案就是第 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-103"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-104">k</span></span></span><script type="math/tex" id="MathJax-Element-24">k</script></span><span> 個元素本身，那便不需要了)，然後加上第 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-105"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-106">k</span></span></span><script type="math/tex" id="MathJax-Element-25">k</script></span><span> 個元素便是答案。</span><br><br>
<span>所以現在我們重新整理一下所需的條件：</span></p><ul>
<li><span>陣列中第 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-107"><span class="MJXp-mn" id="MJXp-Span-108">1</span></span></span><script type="math/tex" id="MathJax-Element-26">1</script></span><span> 到 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-109"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-110">k</span><span class="MJXp-mo" id="MJXp-Span-111" style="margin-left: 0.267em; margin-right: 0.267em;">−</span><span class="MJXp-mn" id="MJXp-Span-112">1</span></span></span><script type="math/tex" id="MathJax-Element-27">k - 1</script></span><span> 個元素的最大連續區間和</span></li>
<li><span>包含第 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-113"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-114">k</span></span></span><script type="math/tex" id="MathJax-Element-28">k</script></span><span> 個元素時所能求得的最大連續需間和</span></li>
</ul><p><span>有了以上的條件，我們就能求得</span><strong><span>陣列中第 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-115"><span class="MJXp-mn" id="MJXp-Span-116">1</span></span></span><script type="math/tex" id="MathJax-Element-29">1</script></span><span> 到 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-117"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-118">k</span></span></span><script type="math/tex" id="MathJax-Element-30">k</script></span><span> 個元素的最大連續區間和。</span></strong><br><br>
<span>在 </span><code>AC_Code.c</code><span> 中，我們設兩個變數 </span><code>max</code><span> 以及 </span><code>sum</code><span>，分別代表現在的最大值以及包含第 </span><code>k</code><span> 個元素時所能求得的最大連續區間和。在迴圈跑第一次時(即 </span><code>i</code><span> 為 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-119"><span class="MJXp-mn" id="MJXp-Span-120">0</span></span></span><script type="math/tex" id="MathJax-Element-31">0</script></span><span> )，我們將 </span><code>max</code><span> 及 </span><code>sum</code><span> 初始化成第 </span><code>0</code><span> 個元素。迴圈從 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-121"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-122">k</span><span class="MJXp-mo" id="MJXp-Span-123" style="margin-left: 0.267em; margin-right: 0.267em;">−</span><span class="MJXp-mn" id="MJXp-Span-124">1</span></span></span><script type="math/tex" id="MathJax-Element-32">k - 1</script></span><span> 跑到 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-125"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-126">k</span></span></span><script type="math/tex" id="MathJax-Element-33">k</script></span><span> 時，我們對 </span><code>sum</code><span> 更新，更新方法如下：</span></p><ul>
<li><span>如果原先的 </span><code>sum</code><span> </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-127"><span class="MJXp-mo" id="MJXp-Span-128" style="margin-left: 0.333em; margin-right: 0.333em;">≥</span><span class="MJXp-mn" id="MJXp-Span-129">0</span></span></span><script type="math/tex" id="MathJax-Element-34">\ge 0</script></span><span>，則代表進入下一個迴圈時，</span><code>sum</code><span> 應該更新為 </span><code>sum + a[k]</code><span> ，因為 </span><code>sum + a[k]</code><span> </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-130"><span class="MJXp-mo" id="MJXp-Span-131" style="margin-left: 0.333em; margin-right: 0.333em;">≥</span></span></span><script type="math/tex" id="MathJax-Element-35">\ge</script></span><span> </span><code>a[k]</code><span>。</span></li>
<li><span>反之，原先的 </span><code>sum</code><span> </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-132"><span class="MJXp-mo" id="MJXp-Span-133" style="margin-left: 0.333em; margin-right: 0.333em;">&lt;</span><span class="MJXp-mn" id="MJXp-Span-134">0</span></span></span><script type="math/tex" id="MathJax-Element-36">< 0</script></span><span> ，則進入下一個迴圈時，</span><code>sum</code><span> 應該更新為 </span><code>a[k]</code><span>，因為 </span><code>sum + a[k]</code><span> </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-135"><span class="MJXp-mo" id="MJXp-Span-136" style="margin-left: 0.333em; margin-right: 0.333em;">&lt;</span></span></span><script type="math/tex" id="MathJax-Element-37"><</script></span><span> </span><code>a[k]</code><span>。</span></li>
</ul><p><span>最後比較 </span><code>sum</code><span> 與 </span><code>max</code><span> 的大小，把大的存入 </span><code>max</code><span>，故迴圈跑完 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-137"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-138">n</span></span></span><script type="math/tex" id="MathJax-Element-38">n</script></span><span> 次後的 </span><code>max</code><span> 即為所求之最大值。</span></p><h3 id="同樣解法，換一種更易懂的思路" data-id="同樣解法，換一種更易懂的思路"><a class="anchor hidden-xs" href="#同樣解法，換一種更易懂的思路" title="同樣解法，換一種更易懂的思路"><span class="octicon octicon-link"></span></a><span>同樣解法，換一種更易懂的思路</span></h3><p><span>遍歷每一個元素，對於每一個元素，考慮如何才能使連續區間和最大化。那麼，要如何考慮？</span><br>
<span>舉這個測資當例子</span></p><pre><code>9
-2 1 -3 4 -1 2 1 -5 4
</code></pre><table>
<thead>
<tr>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-139"><span class="MJXp-msubsup" id="MJXp-Span-140"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-141" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-142" style="vertical-align: -0.4em;">0</span></span></span></span><script type="math/tex" id="MathJax-Element-39">a_0</script></span></th>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-143"><span class="MJXp-msubsup" id="MJXp-Span-144"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-145" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-146" style="vertical-align: -0.4em;">1</span></span></span></span><script type="math/tex" id="MathJax-Element-40">a_1</script></span></th>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-147"><span class="MJXp-msubsup" id="MJXp-Span-148"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-149" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-150" style="vertical-align: -0.4em;">2</span></span></span></span><script type="math/tex" id="MathJax-Element-41">a_2</script></span></th>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-151"><span class="MJXp-msubsup" id="MJXp-Span-152"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-153" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-154" style="vertical-align: -0.4em;">3</span></span></span></span><script type="math/tex" id="MathJax-Element-42">a_3</script></span></th>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-155"><span class="MJXp-msubsup" id="MJXp-Span-156"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-157" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-158" style="vertical-align: -0.4em;">4</span></span></span></span><script type="math/tex" id="MathJax-Element-43">a_4</script></span></th>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-159"><span class="MJXp-msubsup" id="MJXp-Span-160"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-161" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-162" style="vertical-align: -0.4em;">5</span></span></span></span><script type="math/tex" id="MathJax-Element-44">a_5</script></span></th>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-163"><span class="MJXp-msubsup" id="MJXp-Span-164"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-165" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-166" style="vertical-align: -0.4em;">6</span></span></span></span><script type="math/tex" id="MathJax-Element-45">a_6</script></span></th>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-167"><span class="MJXp-msubsup" id="MJXp-Span-168"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-169" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-170" style="vertical-align: -0.4em;">7</span></span></span></span><script type="math/tex" id="MathJax-Element-46">a_7</script></span></th>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-171"><span class="MJXp-msubsup" id="MJXp-Span-172"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-173" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-174" style="vertical-align: -0.4em;">8</span></span></span></span><script type="math/tex" id="MathJax-Element-47">a_8</script></span></th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center"><span>-2</span></td>
<td style="text-align:center"><span>1</span></td>
<td style="text-align:center"><span>-3</span></td>
<td style="text-align:center"><span>4</span></td>
<td style="text-align:center"><span>-1</span></td>
<td style="text-align:center"><span>2</span></td>
<td style="text-align:center"><span>1</span></td>
<td style="text-align:center"><span>-5</span></td>
<td style="text-align:center"><span>4</span></td>
</tr>
</tbody>
</table><p><span>第 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-175"><span class="MJXp-mn" id="MJXp-Span-176">0</span></span></span><script type="math/tex" id="MathJax-Element-48">0</script></span><span> 個元素 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-177"><span class="MJXp-msubsup" id="MJXp-Span-178"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-179" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-180" style="vertical-align: -0.4em;">0</span></span></span></span><script type="math/tex" id="MathJax-Element-49">a_0</script></span><span> 先放入 </span><code>sum</code><span> 以及 </span><code>max</code><span> 。往後看下一個數 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-181"><span class="MJXp-msubsup" id="MJXp-Span-182"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-183" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-184" style="vertical-align: -0.4em;">1</span></span></span></span><script type="math/tex" id="MathJax-Element-50">a_1</script></span><span>，此時分成兩種情況：</span></p><ol>
<li><code>sum</code><span> 為正，則代表以 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-185"><span class="MJXp-msubsup" id="MJXp-Span-186"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-187" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-188" style="vertical-align: -0.4em;">0</span></span></span></span><script type="math/tex" id="MathJax-Element-51">a_0</script></span><span> 作為連續區間和的第一個元素，</span><strong><span>有機會是最大連續區間和</span></strong><span>。</span></li>
<li><code>sum</code><span> 為負，則代表以 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-189"><span class="MJXp-msubsup" id="MJXp-Span-190"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-191" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-192" style="vertical-align: -0.4em;">0</span></span></span></span><script type="math/tex" id="MathJax-Element-52">a_0</script></span><span> 作為連續區間和的第一個元素，</span><strong><span>只會讓值變小</span></strong><span>，不如直接捨棄， </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-193"><span class="MJXp-msubsup" id="MJXp-Span-194"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-195" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-196" style="vertical-align: -0.4em;">0</span></span></span></span><script type="math/tex" id="MathJax-Element-53">a_0</script></span><span>，改以 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-197"><span class="MJXp-msubsup" id="MJXp-Span-198"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-199" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-200" style="vertical-align: -0.4em;">1</span></span></span></span><script type="math/tex" id="MathJax-Element-54">a_1</script></span><span> 作為連續區間和的第一個元素。</span></li>
</ol><p><span>前面的 </span><code>sum</code><span> 值為 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-201"><span class="MJXp-mo" id="MJXp-Span-202" style="margin-left: 0em; margin-right: 0.111em;">−</span><span class="MJXp-mn" id="MJXp-Span-203">2</span></span></span><script type="math/tex" id="MathJax-Element-55">-2</script></span><span>，小於 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-204"><span class="MJXp-mn" id="MJXp-Span-205">0</span></span></span><script type="math/tex" id="MathJax-Element-56">0</script></span><span>，因此更新到下一次迴圈時，捨棄原先的負值，令 </span><code>sum = a_1</code><span>。然後在迴圈結尾，比較 </span><code>sum</code><span> 與 </span><code>max</code><span> 的大小，大的存入 </span><code>max</code><span>。</span></p><p><span>用相同的想法，再看下一個元素 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-206"><span class="MJXp-msubsup" id="MJXp-Span-207"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-208" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-209" style="vertical-align: -0.4em;">2</span></span></span></span><script type="math/tex" id="MathJax-Element-57">a_2</script></span><span>。之前的 </span><code>sum</code><span> 值為 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-210"><span class="MJXp-mn" id="MJXp-Span-211">1</span></span></span><script type="math/tex" id="MathJax-Element-58">1</script></span><span> 是正的，姑且不論 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-212"><span class="MJXp-msubsup" id="MJXp-Span-213"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-214" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-215" style="vertical-align: -0.4em;">2</span></span></span></span><script type="math/tex" id="MathJax-Element-59">a_2</script></span><span> 本身的正負，連續區間和若從 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-216"><span class="MJXp-msubsup" id="MJXp-Span-217"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-218" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-219" style="vertical-align: -0.4em;">1</span></span></span></span><script type="math/tex" id="MathJax-Element-60">a_1</script></span><span> 開始，確實有機會變大。於是讓 </span><code>sum = sum + a[3]</code><span> ，得到 </span><code>sum</code><span> 值為 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-220"><span class="MJXp-mo" id="MJXp-Span-221" style="margin-left: 0em; margin-right: 0.111em;">−</span><span class="MJXp-mn" id="MJXp-Span-222">2</span></span></span><script type="math/tex" id="MathJax-Element-61">-2</script></span><span>。</span></p><p><span>進到下一個數字 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-223"><span class="MJXp-msubsup" id="MJXp-Span-224"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-225" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-226" style="vertical-align: -0.4em;">3</span></span></span></span><script type="math/tex" id="MathJax-Element-62">a_3</script></span><span>，因為之前的 </span><code>sum</code><span> 是負的，所以直接捨棄，讓 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-227"><span class="MJXp-msubsup" id="MJXp-Span-228"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-229" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-230" style="vertical-align: -0.4em;">3</span></span></span></span><script type="math/tex" id="MathJax-Element-63">a_3</script></span><span> 做為新的開頭，以此類推。</span></p><p><span>再舉一個簡單的例子</span></p><pre><code>8
1 1 -10 1 1 1 1 1
</code></pre><table>
<thead>
<tr>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-231"><span class="MJXp-msubsup" id="MJXp-Span-232"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-233" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-234" style="vertical-align: -0.4em;">0</span></span></span></span><script type="math/tex" id="MathJax-Element-64">a_0</script></span></th>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-235"><span class="MJXp-msubsup" id="MJXp-Span-236"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-237" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-238" style="vertical-align: -0.4em;">1</span></span></span></span><script type="math/tex" id="MathJax-Element-65">a_1</script></span></th>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-239"><span class="MJXp-msubsup" id="MJXp-Span-240"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-241" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-242" style="vertical-align: -0.4em;">2</span></span></span></span><script type="math/tex" id="MathJax-Element-66">a_2</script></span></th>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-243"><span class="MJXp-msubsup" id="MJXp-Span-244"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-245" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-246" style="vertical-align: -0.4em;">3</span></span></span></span><script type="math/tex" id="MathJax-Element-67">a_3</script></span></th>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-247"><span class="MJXp-msubsup" id="MJXp-Span-248"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-249" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-250" style="vertical-align: -0.4em;">4</span></span></span></span><script type="math/tex" id="MathJax-Element-68">a_4</script></span></th>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-251"><span class="MJXp-msubsup" id="MJXp-Span-252"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-253" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-254" style="vertical-align: -0.4em;">5</span></span></span></span><script type="math/tex" id="MathJax-Element-69">a_5</script></span></th>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-255"><span class="MJXp-msubsup" id="MJXp-Span-256"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-257" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-258" style="vertical-align: -0.4em;">6</span></span></span></span><script type="math/tex" id="MathJax-Element-70">a_6</script></span></th>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-259"><span class="MJXp-msubsup" id="MJXp-Span-260"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-261" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-262" style="vertical-align: -0.4em;">7</span></span></span></span><script type="math/tex" id="MathJax-Element-71">a_7</script></span></th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center"><span>1</span></td>
<td style="text-align:center"><span>1</span></td>
<td style="text-align:center"><span>-10</span></td>
<td style="text-align:center"><span>1</span></td>
<td style="text-align:center"><span>1</span></td>
<td style="text-align:center"><span>1</span></td>
<td style="text-align:center"><span>1</span></td>
<td style="text-align:center"><span>1</span></td>
</tr>
</tbody>
</table><p><span>從第 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-263"><span class="MJXp-mn" id="MJXp-Span-264">0</span></span></span><script type="math/tex" id="MathJax-Element-72">0</script></span><span> 個元素開始加總，加到 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-265"><span class="MJXp-msubsup" id="MJXp-Span-266"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-267" style="margin-right: 0.05em;">a</span><span class="MJXp-mn MJXp-script" id="MJXp-Span-268" style="vertical-align: -0.4em;">2</span></span></span></span><script type="math/tex" id="MathJax-Element-73">a_2</script></span><span> 時，前面的 </span><code>sum</code><span> 值為 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-269"><span class="MJXp-mn" id="MJXp-Span-270">2</span></span></span><script type="math/tex" id="MathJax-Element-74">2</script></span><span> 是正的，所以讓 </span><code>sum = sum + a[2]</code><span>。</span></p><p><span>然而進到下一次迴圈，前面 </span><code>sum</code><span> 是負的，</span><strong><span>從前面開始當作連續區間和一定不會是最大</span></strong><span>，所以讓 </span><code>sum = a[3]</code><span>。之後就以此類推。</span></p><p><span>在這個思路中，我們注重</span><strong><span>以誰作為連續區間和的開頭</span></strong><span>，而每次迴圈結尾會自動幫我們把找出的最大值存到 </span><code>max</code><span>，所以不用關心結尾是誰。</span></p><h1 id="AC-Code" data-id="AC-Code"><a class="anchor hidden-xs" href="#AC-Code" title="AC-Code"><span class="octicon octicon-link"></span></a><span>AC Code</span></h1><pre><code class="c hljs"><div class="wrapper"><div class="gutter linenumber"><span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span>
<span></span></div><div class="code"><span class="token macro property"><span class="token directive-hash">#</span><span class="token directive keyword">include</span> <span class="token string">&lt;stdio.h&gt;</span></span>

<span class="token keyword">int</span> <span class="token function">main</span><span class="token punctuation">(</span><span class="token punctuation">)</span>
<span class="token punctuation">{</span>
    <span class="token keyword">int</span> n<span class="token punctuation">;</span>
    <span class="token function">scanf</span><span class="token punctuation">(</span><span class="token string">"%d"</span><span class="token punctuation">,</span> <span class="token operator">&amp;</span>n<span class="token punctuation">)</span><span class="token punctuation">;</span>

    <span class="token keyword">long</span> <span class="token keyword">long</span> max<span class="token punctuation">,</span> sum<span class="token punctuation">;</span>
    <span class="token keyword">for</span> <span class="token punctuation">(</span><span class="token keyword">int</span> i <span class="token operator">=</span> <span class="token number">0</span><span class="token punctuation">;</span> i <span class="token operator">&lt;</span> n<span class="token punctuation">;</span> i<span class="token operator">++</span><span class="token punctuation">)</span>
    <span class="token punctuation">{</span>
        <span class="token keyword">long</span> <span class="token keyword">long</span> num<span class="token punctuation">;</span>
        <span class="token function">scanf</span><span class="token punctuation">(</span><span class="token string">"%lld"</span><span class="token punctuation">,</span> <span class="token operator">&amp;</span>num<span class="token punctuation">)</span><span class="token punctuation">;</span>

        <span class="token keyword">if</span> <span class="token punctuation">(</span>i <span class="token operator">==</span> <span class="token number">0</span><span class="token punctuation">)</span>
        <span class="token punctuation">{</span>
            sum <span class="token operator">=</span> num<span class="token punctuation">;</span>
            max <span class="token operator">=</span> sum<span class="token punctuation">;</span>
            <span class="token keyword">continue</span><span class="token punctuation">;</span>
        <span class="token punctuation">}</span>

        <span class="token keyword">if</span> <span class="token punctuation">(</span>sum <span class="token operator">&lt;</span> <span class="token number">0</span><span class="token punctuation">)</span>
            sum <span class="token operator">=</span> num<span class="token punctuation">;</span>
        <span class="token keyword">else</span>
            sum <span class="token operator">+=</span> num<span class="token punctuation">;</span>
        
        <span class="token keyword">if</span> <span class="token punctuation">(</span>sum <span class="token operator">&gt;</span> max<span class="token punctuation">)</span>
            max <span class="token operator">=</span> sum<span class="token punctuation">;</span>
    <span class="token punctuation">}</span>
    <span class="token function">printf</span><span class="token punctuation">(</span><span class="token string">"%lld\n"</span><span class="token punctuation">,</span> max<span class="token punctuation">)</span><span class="token punctuation">;</span>
<span class="token punctuation">}</span>
</div></div></code></pre><h1 id="TestData" data-id="TestData"><a class="anchor hidden-xs" href="#TestData" title="TestData"><span class="octicon octicon-link"></span></a><span>TestData</span></h1><ul>
<li><span>每筆測資占 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-271"><span class="MJXp-mn" id="MJXp-Span-272">10</span></span></span><script type="math/tex" id="MathJax-Element-75">10</script></span><span> 分，時間限制皆為 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-273"><span class="MJXp-mn" id="MJXp-Span-274">1</span></span></span><script type="math/tex" id="MathJax-Element-76">1</script></span><span> 秒</span></li>
<li><span>測資 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-275"><span class="MJXp-mn" id="MJXp-Span-276">0</span></span></span><script type="math/tex" id="MathJax-Element-77">0</script></span><span> 手動生成，測試 </span><code>input</code><span> 正負相間但絕對值遞增的情況</span></li>
<li><span>只考慮 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-277"><span class="MJXp-msubsup" id="MJXp-Span-278"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-279" style="margin-right: 0.05em;">a</span><span class="MJXp-mi MJXp-italic MJXp-script" id="MJXp-Span-280" style="vertical-align: -0.4em;">k</span></span></span></span><script type="math/tex" id="MathJax-Element-78">a_k</script></span><span> 為正數的情況，只能在測資 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-281"><span class="MJXp-mn" id="MJXp-Span-282">3</span></span></span><script type="math/tex" id="MathJax-Element-79">3</script></span><span> 和 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-283"><span class="MJXp-mn" id="MJXp-Span-284">10</span></span></span><script type="math/tex" id="MathJax-Element-80">10</script></span><span> 中拿到分數</span></li>
<li><span>測資 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-285"><span class="MJXp-mn" id="MJXp-Span-286">1</span></span></span><script type="math/tex" id="MathJax-Element-81">1</script></span><span> 手動生成，測試 </span><code>input</code><span> 遞增的情況</span></li>
<li><span>測資 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-287"><span class="MJXp-mn" id="MJXp-Span-288">2</span></span></span><script type="math/tex" id="MathJax-Element-82">2</script></span><span> 手動生成，測試 </span><code>input</code><span> 遞減的情況</span></li>
<li><span>測資 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-289"><span class="MJXp-mn" id="MJXp-Span-290">4</span></span></span><script type="math/tex" id="MathJax-Element-83">4</script></span><span> 測試 </span><code>input</code><span> 皆為負數的 </span><code>edge case</code></li>
<li><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-291"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-292">n</span></span></span><script type="math/tex" id="MathJax-Element-84">n</script></span><span> 越來越大，使用陣列儲存可能導致 </span><code>MLE</code></li>
<li><span>測資 </span><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-293"><span class="MJXp-mn" id="MJXp-Span-294">9</span></span></span><script type="math/tex" id="MathJax-Element-85">9</script></span><span> 測試使用</span><code>int</code><span>造成 </span><code>overflow</code><span> 的情形 </span><br></li>
</ul><table>
<thead>
<tr>
<th style="text-align:center"><span>testdata</span></th>
<th style="text-align:center"><span>n</span></th>
<th style="text-align:center"><span class="mathjax raw"><span class="MathJax_Preview" style="color: inherit;"><span class="MJXp-math" id="MJXp-Span-295"><span class="MJXp-msubsup" id="MJXp-Span-296"><span class="MJXp-mi MJXp-italic" id="MJXp-Span-297" style="margin-right: 0.05em;">a</span><span class="MJXp-mi MJXp-italic MJXp-script" id="MJXp-Span-298" style="vertical-align: -0.4em;">k</span></span></span></span><script type="math/tex" id="MathJax-Element-86">a_k</script></span><span> range</span></th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center"><span>0</span></td>
<td style="text-align:center"><span>10</span></td>
<td style="text-align:center"><span>[-50, 50]</span></td>
</tr>
<tr>
<td style="text-align:center"><span>1</span></td>
<td style="text-align:center"><span>20</span></td>
<td style="text-align:center"><span>[-20, 20]</span></td>
</tr>
<tr>
<td style="text-align:center"><span>2</span></td>
<td style="text-align:center"><span>20</span></td>
<td style="text-align:center"><span>[-100, 100]</span></td>
</tr>
<tr>
<td style="text-align:center"><span>3</span></td>
<td style="text-align:center"><span>100</span></td>
<td style="text-align:center"><span>[0, 10000]</span></td>
</tr>
<tr>
<td style="text-align:center"><span>4</span></td>
<td style="text-align:center"><span>1000</span></td>
<td style="text-align:center"><span>[-1000, -1]</span></td>
</tr>
<tr>
<td style="text-align:center"><span>5</span></td>
<td style="text-align:center"><span>10000</span></td>
<td style="text-align:center"><span>[-10000, 10000]</span></td>
</tr>
<tr>
<td style="text-align:center"><span>6</span></td>
<td style="text-align:center"><span>10000</span></td>
<td style="text-align:center"><span>[-100000, 100000]</span></td>
</tr>
<tr>
<td style="text-align:center"><span>7</span></td>
<td style="text-align:center"><span>300000</span></td>
<td style="text-align:center"><span>[-100000, 100000]</span></td>
</tr>
<tr>
<td style="text-align:center"><span>8</span></td>
<td style="text-align:center"><span>300000</span></td>
<td style="text-align:center"><span>[-1000000, 1000000]</span></td>
</tr>
<tr>
<td style="text-align:center"><span>9</span></td>
<td style="text-align:center"><span>300000</span></td>
<td style="text-align:center"><span>[0, 1000000]</span></td>
</tr>
</tbody>
</table><h1 id="Teamwork" data-id="Teamwork"><a class="anchor hidden-xs" href="#Teamwork" title="Teamwork"><span class="octicon octicon-link"></span></a><span>Teamwork</span></h1><table>
<thead>
<tr>
<th style="text-align:center"><span>工作項目</span></th>
<th style="text-align:left"><span>張子恩</span></th>
<th style="text-align:left"><span>陳泓瑋</span></th>
<th style="text-align:left"><span>左峻豪</span></th>
<th style="text-align:left"><span>郭至恩</span></th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center"><span>題目設計</span></td>
<td style="text-align:left"></td>
<td style="text-align:left"><span>編修題目</span></td>
<td style="text-align:left"></td>
<td style="text-align:left"><span>撰寫完整題目(README檔)</span></td>
</tr>
<tr>
<td style="text-align:center"><span>解題思路</span></td>
<td style="text-align:left"></td>
<td style="text-align:left"><span>解釋穩扎穩打、假解</span></td>
<td style="text-align:left"></td>
<td style="text-align:left"><span>解釋AC_Code思路</span></td>
</tr>
<tr>
<td style="text-align:center"><span>撰寫程式碼</span></td>
<td style="text-align:left"><span>檢測AC_Code</span></td>
<td style="text-align:left"></td>
<td style="text-align:left"></td>
<td style="text-align:left"><span>撰寫AC_Code</span></td>
</tr>
<tr>
<td style="text-align:center"><span>測資設計</span></td>
<td style="text-align:left"><span>強化測資、撰寫測資說明</span></td>
<td style="text-align:left"></td>
<td style="text-align:left"></td>
<td style="text-align:left"><span>設計TLE、MLE情境，以限制演算法</span></td>
</tr>
</tbody>
</table><div class="alert alert-warning">
<p><strong><span>TODO</span></strong><span> 填上工作內容(沒德田 就空白) 以下參考</span></p>
<table>
<thead>
<tr>
<th><span>工作項目</span></th>
<th><span>可以填的東西</span></th>
<th></th>
</tr>
</thead>
<tbody>
<tr>
<td><span>題目設計</span></td>
<td></td>
<td></td>
</tr>
<tr>
<td><span>解題思路</span></td>
<td><span>1.提供某解法的思路</span></td>
<td><span>2.撰寫/編修思路</span></td>
</tr>
<tr>
<td><span>撰寫程式碼</span></td>
<td><span>驗題</span></td>
<td></td>
</tr>
<tr>
<td><span>測資設計</span></td>
<td><span>1.某人設計某個測資 例如:遞增遞減</span></td>
<td><span>2.report的測資設計說明</span></td>
</tr>
</tbody>
</table>
</div><h1 id="Reference" data-id="Reference"><a class="anchor hidden-xs" href="#Reference" title="Reference"><span class="octicon octicon-link"></span></a><span>Reference</span></h1><p><span>ADA mini HW </span><a href="https://ada-judge.csie.ntu.edu.tw/#!/problem/1" target="_blank" rel="noopener"><span>Maximum Subarray</span></a><br><br>
<span>Zerojudge </span><a href="https://zerojudge.tw/ShowProblem?problemid=a164" target="_blank" rel="noopener"><span>a164. 區間最大連續和</span></a><br><br>
<span>iT 邦幫忙 </span><a href="https://ithelp.ithome.com.tw/articles/10213270" target="_blank" rel="noopener"><span>從LeetCode學演算法 - 0053. Maximum Subarray</span></a><span> </span><br><br>
<span>LeetCode </span><a href="https://leetcode.com/problems/maximum-subarray/description/" target="_blank" rel="noopener"><span>Maximum Subarray</span></a><br><br>
<span>示意圖：The logarithm of the Dow Jones Industrial Average, 1896-2014;</span><br><span>Gary Smith,</span><br><span>2 - Displaying Data,</span><br><span>Essential Statistics, Regression, and Econometrics (Second Edition),</span><br><span>Academic Press, 2015</span></p></div>
    <div class="ui-toc dropup unselectable hidden-print" style="display:none;">
        <div class="pull-right dropdown">
            <a id="tocLabel" class="ui-toc-label btn btn-default" data-toggle="dropdown" href="#" role="button" aria-haspopup="true" aria-expanded="false" title="Table of content">
                <i class="fa fa-bars"></i>
            </a>
            <ul id="ui-toc" class="ui-toc-dropdown dropdown-menu" aria-labelledby="tocLabel">
                <div class="toc"><ul class="nav">
<li><a href="#Problem" title="Problem">Problem</a></li>
<li><a href="#Solutions" title="Solutions">Solutions</a><ul class="nav">
<li><a href="#穩扎穩打-The-naïve-method" title="穩扎穩打 The naïve method">穩扎穩打 The naïve method</a><ul class="nav">
<li><a href="#優化方向" title="優化方向">優化方向</a></li>
</ul>
</li>
<li><a href="#前綴和-Prefix-Sum" title="前綴和 Prefix Sum">前綴和 Prefix Sum</a></li>
<li><a href="#正確解法-The-correct-method" title="正確解法 The correct method">正確解法 The correct method</a><ul class="nav">
<li><a href="#同樣解法，換一種更易懂的思路" title="同樣解法，換一種更易懂的思路">同樣解法，換一種更易懂的思路</a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#AC-Code" title="AC Code">AC Code</a></li>
<li><a href="#TestData" title="TestData">TestData</a></li>
<li><a href="#Teamwork" title="Teamwork">Teamwork</a></li>
<li><a href="#Reference" title="Reference">Reference</a></li>
</ul>
</div><div class="toc-menu"><a class="expand-toggle" href="#">全部展開</a><a class="back-to-top" href="#">回到頂部</a><a class="go-to-bottom" href="#">移至底部</a></div>
            </ul>
        </div>
    </div>
    <div id="ui-toc-affix" class="ui-affix-toc ui-toc-dropdown unselectable hidden-print" data-spy="affix" style="top:17px;display:none;" null null>
        <div class="toc"><ul class="nav">
<li><a href="#Problem" title="Problem">Problem</a></li>
<li><a href="#Solutions" title="Solutions">Solutions</a><ul class="nav">
<li><a href="#穩扎穩打-The-naïve-method" title="穩扎穩打 The naïve method">穩扎穩打 The naïve method</a><ul class="nav">
<li><a href="#優化方向" title="優化方向">優化方向</a></li>
</ul>
</li>
<li><a href="#前綴和-Prefix-Sum" title="前綴和 Prefix Sum">前綴和 Prefix Sum</a></li>
<li><a href="#正確解法-The-correct-method" title="正確解法 The correct method">正確解法 The correct method</a><ul class="nav">
<li><a href="#同樣解法，換一種更易懂的思路" title="同樣解法，換一種更易懂的思路">同樣解法，換一種更易懂的思路</a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#AC-Code" title="AC Code">AC Code</a></li>
<li><a href="#TestData" title="TestData">TestData</a></li>
<li><a href="#Teamwork" title="Teamwork">Teamwork</a></li>
<li><a href="#Reference" title="Reference">Reference</a></li>
</ul>
</div><div class="toc-menu"><a class="expand-toggle" href="#">全部展開</a><a class="back-to-top" href="#">回到頂部</a><a class="go-to-bottom" href="#">移至底部</a></div>
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js" integrity="sha256-hVVnYaiADRTO2PzUGmuLJr8BLUSjGIZsDYGmIJLv2b8=" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha256-U5ZEeKfGNOja007MMD3YBI0A3OSZOQbeG6z2f2Y0hu8=" crossorigin="anonymous" defer></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gist-embed/2.6.0/gist-embed.min.js" integrity="sha256-KyF2D6xPIJUW5sUDSs93vWyZm+1RzIpKCexxElmxl8g=" crossorigin="anonymous" defer></script>
    <script>
        var markdown = $(".markdown-body");
        //smooth all hash trigger scrolling
        function smoothHashScroll() {
            var hashElements = $("a[href^='#']").toArray();
            for (var i = 0; i < hashElements.length; i++) {
                var element = hashElements[i];
                var $element = $(element);
                var hash = element.hash;
                if (hash) {
                    $element.on('click', function (e) {
                        // store hash
                        var hash = this.hash;
                        if ($(hash).length <= 0) return;
                        // prevent default anchor click behavior
                        e.preventDefault();
                        // animate
                        $('body, html').stop(true, true).animate({
                            scrollTop: $(hash).offset().top
                        }, 100, "linear", function () {
                            // when done, add hash to url
                            // (default click behaviour)
                            window.location.hash = hash;
                        });
                    });
                }
            }
        }

        smoothHashScroll();
        var toc = $('.ui-toc');
        var tocAffix = $('.ui-affix-toc');
        var tocDropdown = $('.ui-toc-dropdown');
        //toc
        tocDropdown.click(function (e) {
            e.stopPropagation();
        });

        var enoughForAffixToc = true;

        function generateScrollspy() {
            $(document.body).scrollspy({
                target: ''
            });
            $(document.body).scrollspy('refresh');
            if (enoughForAffixToc) {
                toc.hide();
                tocAffix.show();
            } else {
                tocAffix.hide();
                toc.show();
            }
            $(document.body).scroll();
        }

        function windowResize() {
            //toc right
            var paddingRight = parseFloat(markdown.css('padding-right'));
            var right = ($(window).width() - (markdown.offset().left + markdown.outerWidth() - paddingRight));
            toc.css('right', right + 'px');
            //affix toc left
            var newbool;
            var rightMargin = (markdown.parent().outerWidth() - markdown.outerWidth()) / 2;
            //for ipad or wider device
            if (rightMargin >= 133) {
                newbool = true;
                var affixLeftMargin = (tocAffix.outerWidth() - tocAffix.width()) / 2;
                var left = markdown.offset().left + markdown.outerWidth() - affixLeftMargin;
                tocAffix.css('left', left + 'px');
            } else {
                newbool = false;
            }
            if (newbool != enoughForAffixToc) {
                enoughForAffixToc = newbool;
                generateScrollspy();
            }
        }
        $(window).resize(function () {
            windowResize();
        });
        $(document).ready(function () {
            windowResize();
            generateScrollspy();
        });

        //remove hash
        function removeHash() {
            window.location.hash = '';
        }

        var backtotop = $('.back-to-top');
        var gotobottom = $('.go-to-bottom');

        backtotop.click(function (e) {
            e.preventDefault();
            e.stopPropagation();
            if (scrollToTop)
                scrollToTop();
            removeHash();
        });
        gotobottom.click(function (e) {
            e.preventDefault();
            e.stopPropagation();
            if (scrollToBottom)
                scrollToBottom();
            removeHash();
        });

        var toggle = $('.expand-toggle');
        var tocExpand = false;

        checkExpandToggle();
        toggle.click(function (e) {
            e.preventDefault();
            e.stopPropagation();
            tocExpand = !tocExpand;
            checkExpandToggle();
        })

        function checkExpandToggle () {
            var toc = $('.ui-toc-dropdown .toc');
            var toggle = $('.expand-toggle');
            if (!tocExpand) {
                toc.removeClass('expand');
                toggle.text('Expand all');
            } else {
                toc.addClass('expand');
                toggle.text('Collapse all');
            }
        }

        function scrollToTop() {
            $('body, html').stop(true, true).animate({
                scrollTop: 0
            }, 100, "linear");
        }

        function scrollToBottom() {
            $('body, html').stop(true, true).animate({
                scrollTop: $(document.body)[0].scrollHeight
            }, 100, "linear");
        }
    </script>
</body>

</html>
