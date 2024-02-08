# CSS Cheat Sheet
**CSS** stands for Cascading Style Sheets.

**CSS contains** – selector and declaration block. A declaration block consists of property-value pairs.  Example, 

#box

Here, 'box' is the selector and the declaration block is the entire thing inside the curly braces. Saved as - .css file


# 1. Font

| Property | Values | Example |
| --- | --- | --- |
| font-style | normal/italic/inherit/oblique | font-style: normal |
| font-variant | normal/inherit/small-caps | font-variant: small-caps |
| font-weight |	normal/bold/bolder/lighter/100-900/inherit | font-weight:bold |
| font-size	 | ?px/?%/small/medium/large | font-size: large font-size :5 |
| font-family |	verdana/calibri.. etc…	| font-family: verdana |


# 2. Text

| Property | Values | Example |
| --- | --- | --- |
| text-align | left/right/center/justify |	text-align: justify; |
| letter spacing |	normal/length/?%	| letter spacing : 3%; |
| Text-outline |	None/length/color	| Text-outline: red |
| word-wrap |	normal/length	| word-wrap: normal; |
| direction	| ltr/rtl/inherit |	Direction: ltr; |
| text-wrap |	normal/unrestricted/none | text-wrap: normal |
| text-indent |	?%/?px | text-indent: 2% |
| word-spacing | normal/?%/?px | word-spacing: normal |
| text-transform	| none/uppercase/lowercase/capitalize |	text-transform: lowercase |
| text-emphasis	| none/dot/open/filled/circle/triangle | text-emphasis: filled |
| text-justify | auto/distribute/inter-word |	text-justify:distribute |


# 3. User Interface

| Property | Values | Example |
| --- | --- | --- |
| appearance – apply platform specific styling |	normal / inherit / [icon / window / desktop / work-space / document / tooltip / dialog / button / push-button / hyperlink / radio-button / checkbox / menu-item / tab / menu / menubar / pull-down-menu / pop-up-menu / list-menu / radio-group / checkbox-group / outline-tree / range / field / combo-box / signature / password]	| appearance: password; |
| cursor | auto / crosshair / default / pointer / move / e-resize / neresize / nw-resize / n-resize / se-resize / sw-resize / swresize / s-resize / w-resize / text / wait / help |	.help { cursor: help; } |
| nav-index - specifies the sequential navigation order of current element. Similar to tab index in html. Values can be auto or a positive number representing the navigation order. First value is 1. |	auto / inherit  number | nav-index: 1; |
| nav-up | auto / inherit <id> [current / root / <target-name> auto (browser decides where to navigate to)/ id (specific ID to be navigated to)/ target_name (target frame to navigate to)/inherit (value computed based on element’s parent; root or current)| nav-up: auto; |
| nav-down | auto / inherit <id> [current / root / <target-name> | nav-down: #b2; |
| nav-left | auto / inherit <id> [current / root / <target-name> | nav-left: #b1; |
| nav-right |	auto / inherit <id> [current / root / <target-name>	| nav-right: #b2; |
| resize | none / both / horizontal / vertical / inherit | resize: horizontal; |
| icon | auto / inherit | url	icon: url(“like.png”); |


# 4. Backgrounds

| Property | Values | Example |
| --- | --- | --- |
| background-size |	auto/cover/?px/?%	| background-size: cover |
| background-image |	url/none |	background-image: none |
| background-repeat |	no-repeat/repeat-x/repeat-y/repeat |	background-repeat: repeat |
| background-attachment |	fixed/scroll | background-attachment: fixed |
| background-color | color/transparent | background-color: white |
| background-position | can be any position from different combinations like top left, top right, top center. Same with bottom. can be mentioned in terms of position x-% and y-%	| background-position: top-left; |
| background-origin |	the starting point of the background | background-origin: 0; |
| background-clip - lets you control how much of the background image should extend beyond the element’s content or padding | content-box/padding-box/border-box/no-clip/?%/?px | background-clip: no-clip |


# 5. Borders

| Property | Values | Example |
| --- | --- | --- |
| border-width | thin/thick/medium/?px | border-width: medium border-width: 20px |
| border-style | none/dashed/dotted/inset/double/solid | border-style : dotted |
| border-color | name of the color | border-color: black |
| border-left: border-left-color border-left-width |	| border-left-color: black border-left-width : 10px |
| border-right: border-right-color border-right-width	| |	border-right-color : black border-right-width : 15px |
| border-top: border-top-width border-top-color	| |	border-top-width : 10px border-top-color : blue |
| border-bottom: border-bottom-color border-bottom-width | |	border-bottom-color : black border-bottom-width : 15px |
| border-decoration-break | maintain consistent design amongst fragments of broken element slice/clone | border-decoration-break: slice; |
| border-radius border-top-right-radius  border-bottom-right-radius  border-bottom-left-radius  border-top-left-radius | ?px | border-top-left-radius : 20px |
| border-image| ?%/stretch/repeat/round/none | border-image : repeat border-image : 12px |

# 6. Box Model  

| Property | Values | Example |
| --- | --- | --- |
| float |	left / right / none |	float : right |
| height | auto length % | height : 10px |
| max-height | none length % | max-height : 10px |
| max-width |	none length %	| max-width : 120% | 
| min-height |	none length %	| min-height : 50% |
| min-width |	auto % length |	min-width : 30px |


## 6.1. Margin 

| Property | Values | Example |
| --- | --- | --- |
| margin-bottom |	auto/length %	| margin-bottom : 20px |
| margin-left	| auto/height % |	margin-left : auto |
| margin-right | auto/height % | margin-right : 30% |
| margin-top | auto/length %	| margin-top : 40mm |

## 6.1. Padding 

| Property | Values | Example |
| --- | --- | --- |
padding-bottom | length %	| padding-bottom : 20px
padding-top	| length %	| padding-top : 20px
padding-right	| length %	| padding-right : 20px
padding-left | length %	| padding-left : 20px
display | none/inline/block/inline-block/list-item/run-in/compact/table/inline-table/table-row-group/table-headergroup/table-footer-group/table-row/table-column-group/table-column/table-cell/table-caption/ruby/ruby-base/ruby-text/ruby-base-group/ruby-text-group |	display : inline |
marquee-direction | forward/reverse |	marquee-direction : forward |
marquee-loop | infinite/integer | marquee-loop : 10 |
marquee-play-count | infinite/integer | marquee-play-count : 50 |
marquee-speed |	slow/normal/fast | marquee-speed : slow |
marquee-style	| scroll/slide/alternate | marquee-style : scroll |
overflow | visible/hidden/scroll/auto/no-display/no-content/overflow-x/overflow-y | overflow : visible |
overflow-style | auto/marquee-line/marquee-block | overflow-style : auto |
overflow-x | visible/hidden/scroll/auto/no-display/no-content |	overflow-x : scroll |
rotation | angle | rotation : 20deg |
rotation-point | position (paired value off-set) | rotation-point : 50% 50% |
visibility | visible/hidden/collapse | visibility: hidden |
clear |	left/right/both/none |	clear: left |
