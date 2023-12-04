<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Резюме</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	padding-inline-start: 0;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.page-description {
    margin-bottom: 2em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-uiBlue { background-color: rgba(35, 131, 226, .07); }
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-translucentGray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }
.select-value-color-pageGlass { background-color: undefined; }
.select-value-color-washGlass { background-color: undefined; }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="59371923-d17c-4478-8c7e-328798a25376" class="page sans"><header><h1 class="page-title">Резюме</h1><p class="page-description"></p></header><div class="page-body"><div id="50a150a0-6b5e-4974-a077-63ebaf3b430c" class="column-list"><div id="e05b7422-cb98-4821-9990-41558e72cdc3" style="width:25%" class="column"><figure id="33ff20cf-06c4-43ae-a995-5285ed0c9a3f" class="image"><a href="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/%25D0%25A4%25D0%25BE%25D1%2582%25D0%25BE_%25D0%25BF%25D0%25B0%25D1%2581%25D0%25BF%25D0%25BE%25D1%2580%25D1%2582.jpg"><img style="width:687px" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/%25D0%25A4%25D0%25BE%25D1%2582%25D0%25BE_%25D0%25BF%25D0%25B0%25D1%2581%25D0%25BF%25D0%25BE%25D1%2580%25D1%2582.jpg"/></a></figure></div><div id="2d8538f3-a649-4a1d-915c-a86250884a85" style="width:93.74999999999999%" class="column"><h1 id="174c2e3e-c23b-46af-bdcf-1c6607da54a9" class=""><strong>Ноянов Роман Станиславович</strong></h1><p id="fd3806b7-4b7d-41e2-accc-3e7f7dc2e1f3" class="">Контактная информация:</p><div id="21c06c42-42ec-433f-ba50-22d674ed69e7" class="column-list"><div id="d9340f7d-c680-42bd-b728-819bb11ec049" style="width:100%" class="column"><p id="8f010476-ac07-4dba-a55f-add468b58e46" class=""><strong>@  </strong>roman.noyanov@yandex.ru</p><p id="b1da6236-4618-4e0e-ab07-177505e456af" class="">📍 <mark class="highlight-gray">Санкт-Петербург, Россия</mark></p></div><div id="c21b82f4-b17e-4800-ba67-44d815aebf30" style="width:100%" class="column"><p id="15606df7-ff42-49a8-aa27-6db9ea6ec695" class=""> <strong>#   </strong><mark class="highlight-gray">+7(931) 223-84-41</mark></p></div></div></div></div><div id="af449d4e-6a23-4913-98c5-26c9e8838880" class="column-list"><div id="a8b1c997-5c3d-4b69-99e8-51dd9f65f8ed" style="width:33.33333333333333%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="dcdf672a-674b-4698-b6b0-2524a27b43ae"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/github-mark.png"/></div><div style="width:100%"><a href="https://github.com/RomanNoyanov">GitHub</a></div></figure></div><div id="1bceb883-ad90-456d-9f07-a9ce62686831" style="width:33.33333333333333%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="5e060742-6867-4ff0-9898-5446ec5d4d5a"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/Logo.png"/></div><div style="width:100%"><a href="https://t.me/qazvpol">Telegram</a></div></figure></div><div id="3b485911-9707-4647-970c-428363ca019d" style="width:33.33333333333333%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="f91d5fa7-ea6c-4d0a-bdc7-52ad00df5daa"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/VK_Logo.png"/></div><div style="width:100%"><a href="https://vk.com/roman_rozanov">Вконтакте</a></div></figure></div></div><h2 id="3a6cec91-9df1-4143-baf3-b096dc928b06" class="">Обо мне</h2><hr id="b78ff8f8-aa91-408c-8d1d-9f50eed8a22e"/><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="ddf309b6-4776-4180-bed8-77fa0ef24712"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/info.png"/></div><div style="width:100%">Мне 22 года, живу в Санкт-Петербурге. Многие годы увлекаюсь компьютерами, в данный момент получаю высшее образование по направлению информационная безопасность  на третьем курсе очной формы (бюджет). Обладаю высокой коммуникабельностью, легко вливаюсь в коллектив и быстро осваиваю новые навыки в компьютерной сфере, являюсь отзывчивым и ответственным человеком.
Собрал команду в университете, состоящую из преподавателей и студентов, чтобы создать telegrm - бота для облегчения процесса обучения и упрощения работы преподавателей в тестирования знаний студентов, и написал на эту тему научную статью.  
Изучаю Linux ,также интересуюсь программированием на Python, участвую в CTF и различных студенческих олимпиадах.
Также увлекаюсь кинематографом, спортом, имею звание кандидата в мастера спорта по водному поло, поддерживаю здоровый образ жизни. </div></figure><h2 id="42bfe435-5214-4fd8-abce-930745c0d830" class="">Образование</h2><hr id="3667a604-58f4-4aaf-b067-4b84c0236555"/><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="231fc259-f2a2-46f3-8527-58cf2b877760"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/classroom.png"/></div><div style="width:100%"><strong>Колледж Телекоммуникаций СПбГУТ им. профессора М. А. Бонч-Бруевича</strong><p id="cf4f2c83-45ab-4f18-b5fb-8c86c35b1229" class=""> Программирование в компьютерных системах</p><p id="ea7632f0-070d-4f90-b421-27fa6a037264" class="">Диплом с «отличием»</p><p id="e9aae8a4-2a22-4ae3-8dfd-77e03fa918e3" class=""><mark class="highlight-gray"><em>2017-2021</em></mark></p></div></figure><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="7aef89bb-1f28-4454-9701-fd3b7e1d0a57"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/classroom%201.png"/></div><div style="width:100%"><strong>Санкт-Петербургский государственный университет телекоммуникаций имени профессора М. А. Бонч-Бруевича</strong> <p id="b524d06a-4449-4917-8839-eaf96a391cb4" class="">Информационная безопасность</p><p id="050a5efa-0925-4917-a9a8-adc12b489f54" class=""><mark class="highlight-gray"><em>2021-2025</em></mark></p></div></figure><h2 id="d5a3cbc2-140b-4ac8-90e1-540597ebc977" class="">Дополнительное образование</h2><hr id="f124daa6-46cb-4b12-a00a-fd062494907d"/><div id="d1a70c7e-a5dc-4511-8a56-2008a25dcdca" class="column-list"><div id="cf8e406e-a08e-4a28-8fba-f6aed51eb388" style="width:50%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="b397e422-07ae-4244-8539-4f76f3d6ef04"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/sertificat.png"/></div><div style="width:100%"><strong>Программирование на Python</strong><hr id="c4a1075e-99c9-4ef4-b93b-8fb856192684"/><p id="9b0b3185-4785-4871-bf44-6be9d4735a16" class="">Bioinformatics Institute</p><p id="db79fc63-6b33-41c6-808e-680efcf5d259" class=""><mark class="highlight-gray"><em> 2020</em></mark></p><figure id="ad71d3f0-e0e0-4dc9-9255-06cb4616dd26"><div class="source"><a href="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/stepik-certificate-python.pdf">Сертификат</a></div></figure></div></figure></div><div id="c423f754-d939-438a-910d-fdc81e13cd15" style="width:50%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="a2fffe38-7efe-43db-a5a2-8992557c0c3e"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/sertificat%201.png"/></div><div style="width:100%"><strong>IT Essentials</strong><hr id="62329f67-41ce-405f-a9f7-8e6957984543"/><p id="41073567-42f6-4546-ac14-95e6ad445296" class=""><strong> </strong>CISCO</p><p id="71ba32a5-4fdc-4c1c-8e20-f1e2d658113a" class=""><mark class="highlight-gray"><em> 2019</em></mark></p><figure id="0efeea3c-c71a-4f9b-93ad-5ccfbca46d0d"><div class="source"><a href="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/-ITE-581-1819-certificate.pdf">Сертификат</a></div></figure></div></figure></div></div><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="c0badb4e-684c-4117-849b-deda552b2eb5"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/sertificat%202.png"/></div><div style="width:100%"><strong>Веб-разработка: HTML и CSS</strong><hr id="de6f8571-af26-4755-982c-ce066dafd650"/><p id="5e1099b1-ca1d-46e6-a920-cb44a747a8a7" class=""> ITC</p><p id="0dca526f-90ae-4216-93d3-d13a30905d6d" class=""><mark class="highlight-gray"><em> 2020</em></mark></p><figure id="a4178119-3c74-4a92-b8d3-69b84c71e408"><div class="source"><a href="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/stepik-certificate-38218-c8fb516.pdf">Сертификат</a></div></figure></div></figure><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="40e9a341-7909-40da-8a55-386c77014c26"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/sertificat%203.png"/></div><div style="width:100%"><strong>1С: программировать легко</strong><hr id="953356db-acf9-41dd-b1aa-b0d618e5f550"/><p id="a7e5bfa3-67ab-48e0-8f04-cf71e309d2c7" class=""><strong> </strong>BIA Technologies</p><p id="e04f0547-d1fc-43f8-8498-1a64b8cc83d9" class=""><mark class="highlight-gray"><em> 2023</em></mark></p></div></figure><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="bd7d41fb-3586-4c81-92d0-c21b78d624ff"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/sertificat%204.png"/></div><div style="width:100%"><strong>Разработка, администрирование и защита баз данных</strong><hr id="0af4cdda-f8ed-48bb-bed6-0223530775df"/><p id="49c5be10-e2b7-4d7b-87db-fb3d34e9e81f" class="">Academia-moscow</p><p id="9ec12f16-e9e8-4069-a379-576ad84152b5" class=""><mark class="highlight-gray"><em> 2019</em></mark></p></div></figure><h2 id="236f7cda-6962-49a9-8fb3-d38cb6ddd72d" class="">Опыт работы</h2><hr id="f541871a-21a3-4045-9edc-bb0d3ced6ca8"/><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="dfbc4235-d723-404b-bcb4-b61e903aec88"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/business.png"/></div><div style="width:100%"><strong>Центральной городской детской библиотеке им. А.С. Пушкина </strong><p id="630a67b3-6f47-4e55-a652-b1f2707c522f" class="">Практика в компании</p><p id="32be5440-ca28-45ee-a2a9-9722c0d818b7" class=""> <mark class="highlight-gray">Июнь 2020 - Июль 2020</mark></p><hr id="41000f1d-485e-49c9-b134-1081a9279354"/><ul id="300673b4-a1bc-43d3-8f0a-8caadb3ffa73" class="bulleted-list"><li style="list-style-type:disc">Стояла задача разработать интерактивную карту истории библиотеки на веб-страницы, используя API 2GIS.</li></ul><ul id="6ff098ab-1d1a-4de9-a80b-a92c5ac2a0d5" class="bulleted-list"><li style="list-style-type:disc">В ходе работы были получены навыки взаимодействия с заказчиком, коррекция начального ТЗ, а также внедрение предложенных идей по улучшению продукта.</li></ul><ul id="4fccd88c-c8b0-4331-8f30-3d4e2cafcae1" class="bulleted-list"><li style="list-style-type:disc">Был нарисован дизайн интерфейса, согласно составленной документации и разработано web-приложение на языке JavaScript.</li></ul></div></figure><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="b19b031d-11c5-459f-9506-97918f9ba27a"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/business%201.png"/></div><div style="width:100%"><strong>АО «ЦНИИМ»</strong><p id="9959d9d6-f045-45cc-8365-8d1ae55078ed" class=""><strong> </strong>Практика в компании</p><p id="c25ee0a3-96c1-4052-9e2d-a0192e82b933" class=""><mark class="highlight-gray"><em> Июль 2023</em></mark></p><hr id="7e306132-cd67-4d48-8d1b-1303db672e3c"/><ul id="c769fc01-6b74-420f-bf60-dc993a947322" class="bulleted-list"><li style="list-style-type:disc">Стояла задача по модернизации компьютерной сети предприятия</li></ul><ul id="1d63ce0b-ce7f-45a5-84b4-e0519dd190f4" class="bulleted-list"><li style="list-style-type:disc">Была проведена настройка новых коммутаторов и проведен оптоволоконный кабель.</li></ul></div></figure><h2 id="02bd2d81-aa59-4918-86ab-1846d979796b" class="">Изучаю</h2><hr id="4e819166-4cba-4cca-897b-6e05753d5c17"/><div id="df4b3afc-8a7e-49b3-8ff2-f4cdb9178ca4" class="column-list"><div id="a890ea80-feed-4d34-ad79-663e3df6b1c6" style="width:83.33333333333333%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="81a843b4-dce4-40b5-9521-04beaf3cfa6e"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/star.png"/></div><div style="width:100%">Java</div></figure><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="37d216de-25ca-4975-92be-89a1ad3fb744"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/star%201.png"/></div><div style="width:100%">JavaScript</div></figure><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="d0275b61-042e-4074-8735-3f6f0fa4f028"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/star%202.png"/></div><div style="width:100%">Pentest</div></figure></div><div id="70fb2e0c-3717-4c9f-8f0d-5068207ad515" style="width:79.16666666666666%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="065a03ca-8366-400f-bc33-7b6ba6ed47a7"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/star%203.png"/></div><div style="width:100%">Python</div></figure><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="36b8c418-afa4-4f00-bf4e-a237e2f81801"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/star%204.png"/></div><div style="width:100%">SQL</div></figure><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="9e9a8341-a5b1-4eb7-b942-6e50be84246f"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/star%205.png"/></div><div style="width:100%">CTF</div></figure></div><div id="08d56333-58ea-4cc0-9c11-edecd6903c61" style="width:120.83333333333334%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="1a37f7d4-b635-4819-a99d-b8860744fcb6"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/star%206.png"/></div><div style="width:100%">HTML, CSS</div></figure><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="5a29b1c0-767e-48c3-973c-4eae35332c08"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/star%207.png"/></div><div style="width:100%">Git</div></figure><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="4721dc67-dd91-4f66-b0db-6792dae6bec2"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/star%208.png"/></div><div style="width:100%">Windows/Linux</div></figure></div></div><h2 id="ec24736b-c084-4b1e-9bb3-9c75264d8de5" class="">Программное обеспечение</h2><hr id="b3afa3c9-85d2-4f39-9aa2-ceb4e278e834"/><div id="e71a6975-2244-4c69-89d4-f7c3c6f242a2" class="column-list"><div id="a3c407c9-bc31-48c1-b7be-e182ab2ddf4e" style="width:33.33333333333333%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="be8a5f27-c8b4-428a-81a0-427b9b05eb64"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/intellij-idea-seeklogo.com.svg"/></div><div style="width:100%"><strong>IntelliJ IDEA</strong></div></figure><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="093945e4-c0db-48e3-9630-3c216e900e0f"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/%25D0%25A1%25D0%25BD%25D0%25B8%25D0%25BC%25D0%25BE%25D0%25BA_%25D1%258D%25D0%25BA%25D1%2580%25D0%25B0%25D0%25BD%25D0%25B0_2023-07-11_%25D0%25B2_2.19.50_AM.png"/></div><div style="width:100%"><strong>MS Office </strong></div></figure></div><div id="aff57075-4e72-4e2b-90bc-a0ebc7f4fd91" style="width:33.33333333333334%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="7cbf804c-ed2f-49f1-9f48-d7e99eebf1a0"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/pngegg.png"/></div><div style="width:100%">VS Code</div></figure><p id="4b21e8e2-0355-4bab-a67f-02fb339044c4" class="">
</p></div><div id="6b92d89a-4741-4237-baf1-f8d3332d1a11" style="width:33.33333333333334%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="3f951666-f53f-43e6-b736-1a69e7f98e36"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/pycharm-seeklogo.com.svg"/></div><div style="width:100%"><strong>PyCharm</strong></div></figure><p id="894d9cd3-82a8-4278-b6d5-b37f0d66e22a" class="">
</p></div></div><h2 id="9b41f005-4e20-493d-897f-90a15087b45a" class=""><strong>Личностные</strong> <strong>качества</strong></h2><hr id="919c4aa3-5f6a-4354-8380-6dca670ad856"/><div id="01394a69-e85f-4491-8292-9f5409a6a9f8" class="column-list"><div id="9a0b991e-39f8-48b7-a184-2c0e6e3d6b0f" style="width:50%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="1363a28d-a9d4-4afd-bf4b-c20c25254c35"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/user.png"/></div><div style="width:100%">Открытость</div></figure></div><div id="6346b46d-b74a-4a1d-901a-a0b12f731940" style="width:50%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="cc66cfec-19e7-4e16-b308-ba9e4e13da85"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/user%201.png"/></div><div style="width:100%">Дисциплинированность</div></figure></div></div><div id="f0bcf4bc-2654-46f5-8a65-dda99b0721b9" class="column-list"><div id="cb6c06a5-bb8f-4448-ac09-e27cf90914bc" style="width:50%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="b63ea1a8-fc18-4c97-b2de-0f0e64eec796"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/user%202.png"/></div><div style="width:100%">Трудолюбие</div></figure></div><div id="5571e995-0b1d-41f5-9065-f9e8a2e2290f" style="width:50%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="28b7ba52-b0e8-4b56-b8d7-40e2a767cb1d"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/user%203.png"/></div><div style="width:100%">Направленность на результат</div></figure></div></div><div id="7228724f-b06a-45b5-8d83-c1833c511ee3" class="column-list"><div id="24432108-adb0-449e-a7c0-a8f2f44e6b3c" style="width:50%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="6ea2f41e-a79c-4cf9-8cc4-0695be043310"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/user%204.png"/></div><div style="width:100%">Умение работать в команде</div></figure></div><div id="77bb548b-5b50-46b4-ad61-170c1f58e61c" style="width:50%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="fd543ef9-dabe-401a-bcf9-442c86ca320b"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/user%205.png"/></div><div style="width:100%">Обучаемость</div></figure></div></div><h2 id="dec4ab1e-2718-4479-ac72-0de5855f332b" class="">Языки</h2><hr id="725834ac-ce7b-44a8-9dd6-77f69319f92e"/><div id="59f823e9-f76e-467d-9c2a-b5fbc080c6a7" class="column-list"><div id="d7c92d66-b59a-4357-a0a8-a223cc585264" style="width:50%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="1a3f01dc-fd8e-421c-a4b4-39702dda44f9"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/speech-bubble.png"/></div><div style="width:100%">Русский<hr id="9175ca09-82e7-473d-972c-ef54b464e6ea"/><p id="95a7a83e-f7ab-4d0b-8b42-53800c970376" class=""><em><mark class="highlight-gray"><em><mark class="highlight-gray"><em><mark class="highlight-gray"><em><mark class="highlight-gray"><em><mark class="highlight-gray"><em><mark class="highlight-gray">Родной </mark></em></mark></em></mark></em></mark></em></mark></em></mark></em></p></div></figure></div><div id="3d84a507-2cfc-4d2f-b665-b6a1ce5fc963" style="width:50%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="130e1c10-a9fc-440c-988a-80e4c0deb669"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/speech-bubble%201.png"/></div><div style="width:100%">Английский<hr id="eeab7bdf-36b6-4052-932e-4e233c75d4e4"/><p id="e322f6d7-9b64-462a-9648-25668c8472e8" class=""><em><mark class="highlight-gray"><em><mark class="highlight-gray"><em><mark class="highlight-gray"><em><mark class="highlight-gray"><em><mark class="highlight-gray"><em><mark class="highlight-gray">A2-Elementary</mark></em></mark></em></mark></em></mark></em></mark></em></mark></em></p></div></figure></div></div><h2 id="8396d9f4-a0ac-4808-9406-33c3e38a94e9" class="">Дополнительные сведения</h2><hr id="18b9bf00-56b5-4cdd-bc46-b40f0c2d6ccc"/><div id="0abf1b49-f7e4-46c8-85a2-2ad0229ff2fe" class="column-list"><div id="1afdc90c-4da8-4892-b9ed-3813891acd93" style="width:50%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="c5a5b6bb-4a6a-421f-b98c-b0fa8046681d"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/resume.png"/></div><div style="width:100%">Семейное положение: не женат</div></figure></div><div id="4d495480-7fea-424e-aefa-5dd4b2378930" style="width:50%" class="column"><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="a7ec9136-6341-4261-8d3e-eb98a40fbfb4"><div style="font-size:1.5em"><img class="icon" src="%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5%2059371923d17c44788c7e328798a25376/resume%201.png"/></div><div style="width:100%">Водительское удостоверение</div></figure></div></div><p id="5db846aa-c7f5-467c-aea5-a230a80c7b44" class="">
</p></div></article><span class="sans" style="font-size:14px;padding-top:2em"></span></body></html>
