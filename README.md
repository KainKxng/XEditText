<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/1999/REC-html401-19991224/strict.dtd">
<html>
<head>
<META http-equiv=Content-Type content="text/html; charset=windows-1252">
<title>Exported from Notepad++</title>
<style type="text/css">
span {
	font-family: 'Courier New';
	font-size: 10pt;
	color: #000000;
}
.sc0 {
}
.sc2 {
	color: #008000;
}
.sc5 {
	font-weight: bold;
	color: #0000FF;
}
.sc10 {
	font-weight: bold;
	color: #000080;
}
.sc11 {
}
.sc16 {
	color: #8000FF;
}
</style>
</head>
<body>

加强版的EditText,可以为DrawableLeft和DrawableRight设置点击事件

<p><b>Demo</b></p>
<hr>
<div style="float: left; white-space: pre; line-height: 1; background: #FFFFFF; "><span class="sc16">public</span><span class="sc0"> </span><span class="sc16">class</span><span class="sc0"> </span><span class="sc11">MainActivity</span><span class="sc0"> </span><span class="sc5">extends</span><span class="sc0"> </span><span class="sc11">Activity</span><span class="sc0"> </span><span class="sc10">{</span><span class="sc0">
    </span><span class="sc16">private</span><span class="sc0"> </span><span class="sc11">XEditText</span><span class="sc0"> </span><span class="sc11">mPassword</span><span class="sc0"> </span><span class="sc10">;</span><span class="sc0">

    </span><span class="sc11">@Override</span><span class="sc0">
    </span><span class="sc16">protected</span><span class="sc0"> </span><span class="sc16">void</span><span class="sc0"> </span><span class="sc11">onCreate</span><span class="sc10">(</span><span class="sc11">Bundle</span><span class="sc0"> </span><span class="sc11">saveInstance</span><span class="sc10">)</span><span class="sc0"> </span><span class="sc10">{</span><span class="sc0">
        </span><span class="sc5">super</span><span class="sc10">.</span><span class="sc11">onCreate</span><span class="sc10">()</span><span class="sc0"> </span><span class="sc10">;</span><span class="sc0">
        </span><span class="sc11">setContentView</span><span class="sc10">(</span><span class="sc11">R</span><span class="sc10">.</span><span class="sc11">layout</span><span class="sc10">.</span><span class="sc11">main</span><span class="sc10">)</span><span class="sc0"> </span><span class="sc10">;</span><span class="sc0">
        
        </span><span class="sc11">mPassword</span><span class="sc10">.</span><span class="sc11">setDrawableRightListener</span><span class="sc10">(</span><span class="sc5">new</span><span class="sc0"> </span><span class="sc11">DrawableRightListener</span><span class="sc10">()</span><span class="sc0"> </span><span class="sc10">{</span><span class="sc0">            
            </span><span class="sc11">@Override</span><span class="sc0">
            </span><span class="sc16">public</span><span class="sc0"> </span><span class="sc16">void</span><span class="sc0"> </span><span class="sc11">onDrawableRightClick</span><span class="sc10">(</span><span class="sc11">View</span><span class="sc0"> </span><span class="sc11">view</span><span class="sc10">)</span><span class="sc0"> </span><span class="sc10">{</span><span class="sc0">
                </span><span class="sc2">// 设置你具体的逻辑
</span><span class="sc0">            </span><span class="sc10">}</span><span class="sc0">
        </span><span class="sc10">})</span><span class="sc0"> </span><span class="sc10">;</span><span class="sc0">
    </span><span class="sc10">}</span><span class="sc0">
</span><span class="sc10">}</span></div></body>
</html>
