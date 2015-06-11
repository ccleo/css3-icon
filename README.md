<style>
body {
    padding: 0;
    margin: 0;
}

h1 {
    font: 700 40px / 25px "Calibri";
    text-align: center;
    color: #333;
    text-shadow: 1px 1px 3px rgba(255, 255, 255, 1);
    margin: 50px 0 100px;
}

div.container {
    position: relative;
    width: 590px;
    margin: 0 auto;
}

div.container_d {
    position: relative;
    width: 592px;
    margin: 0 auto;
}

p {
    font-size: 13px;
    line-height: 18px;
    font-family: Arial, Helvetica, sans-serif;
}

hr {
    width: 592px;
    height: 1px;
    background: #888;
    border: none;
    border-bottom: 1px solid #eee;
    outline: none;
}

h3 {
    font-size: 16px;
    line-height: 20px;
    font-family: Arial, Helvetica, sans-serif;
    border-bottom: 1px solid #aaa;
    padding: 8px 0;
    margin: 25px 0 10px;
}

code {
    margin: 0;
    padding: 20px;
    background: #ddd;
    border: 1px solid #fff;
    display: block;
    -webkit-box-shadow: 0px 0px 3px 1px rgba(0, 0, 0, 0.3);
    -moz-box-shadow: 0px 0px 3px 1px rgba(0, 0, 0, 0.3);
    box-shadow: 0px 0px 3px 1px rgba(0, 0, 0, 0.3);
}

/*##### ICONS #####*/
div.icon {
    height: 32px;
    width: 32px;
    position: relative;
    margin: 15px;
    overflow: hidden;
    display: inline-block;
}

/* Down Arrow */
div.icon div.downArrow {
    height: 0px;
    width: 0px;
    border-width: 16px;
    border-style: solid;
    border-color: #333 transparent transparent transparent;
    position: absolute;
    top: 16px;
    left: 0;
}

div.icon div.downArrow:after {
    content: '';
    width: 12px;
    height: 16px;
    background-color: #333;
    position: absolute;
    bottom: 16px;
    right: -6px;
}

/* Up Arrow */
div.icon div.upArrow {
    height: 0px;
    width: 0px;
    border-width: 16px;
    border-style: solid;
    border-color: transparent transparent #333 transparent;
    position: absolute;
    bottom: 16px;
    left: 0;
}

div.icon div.upArrow:after {
    content: '';
    width: 12px;
    height: 16px;
    background-color: #333;
    position: absolute;
    top: 16px;
    right: -6px;
}

/* Left Arrow */
div.icon div.leftArrow {
    height: 0px;
    width: 0px;
    border-width: 16px;
    border-style: solid;
    border-color: transparent #333 transparent transparent;
    position: absolute;
    right: 16px;
    top: 0;
}

div.icon div.leftArrow:after {
    content: '';
    width: 16px;
    height: 12px;
    background-color: #333;
    position: absolute;
    top: -6px;
    left: 16px;
}

/* Right Arrow */
div.icon div.rightArrow {
    height: 0px;
    width: 0px;
    border-width: 16px;
    border-style: solid;
    border-color: transparent transparent transparent #333;
    position: absolute;
    left: 16px;
    top: 0;
}

div.icon div.rightArrow:after {
    content: '';
    width: 16px;
    height: 12px;
    background-color: #333;
    position: absolute;
    top: -6px;
    right: 16px;
}

/* Home */
div.icon div.home {
    height: 0px;
    width: 0px;
    border-width: 16px;
    border-style: solid;
    border-color: transparent transparent #333 transparent;
    position: absolute;
    bottom: 16px;
    left: 0;
}

div.icon div.home:after {
    content: '';
    width: 5px;
    height: 16px;
    background-color: transparent;
    position: absolute;
    top: 16px;
    right: -11px;
    border-left: 8px solid #333;
    border-right: 8px solid #333;
}

div.icon div.home:before {
    content: '';
    width: 9px;
    height: 6px;
    background-color: #333;
    position: absolute;
    top: 16px;
    right: -5px;
}

div.icon div.chimney {
    width: 4px;
    height: 10px;
    background: #333;
    position: absolute;
    right: 6px;
    top: 3px;
}

/* Disc */
div.icon div.disc:after {
    content: '';
    width: 6px;
    height: 6px;
    background: transparent;
    border-radius: 50px;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border: 3px solid #333;
    position: absolute;
    left: -3px;
    top: -3px;
}

div.icon div.disc:before {
    content: '';
    width: 6px;
    height: 6px;
    background: transparent;
    border-radius: 50px;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border: 13px solid #333;
    position: absolute;
    left: -13px;
    top: -13px;
    z-index: -1
}

div.icon div.disc {
    width: 6px;
    height: 6px;
    background: transparent;
    border-radius: 50px;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border: 10px solid #eee;
    position: absolute;
    left: 3px;
    top: 3px;
}

/* Heart */
div.icon div.heart {
    height: 26px;
    width: 16px;
    background: #333;
    -webkit-border-radius: 100px 100px 0 0;
    -moz-border-radius: 100px 100px 0 0;
    border-radius: 100px 100px 0 0;
    -webkit-transform: rotate(-45deg);
    -moz-transform: rotate(-45deg);
    -ms-transform: rotate(-45deg);
    -o-transform: rotate(-45deg);
    transform: rotate(-45deg);
    position: absolute;
    left: 5px;
    top: 2px;
}

div.icon div.heart:after {
    content: '';
    height: 26px;
    width: 16px;
    background: #333;
    -webkit-border-radius: 100px 100px 0 0;
    -moz-border-radius: 100px 100px 0 0;
    border-radius: 100px 100px 0 0;
    -webkit-transform: rotate(90deg);
    -moz-transform: rotate(90deg);
    -ms-transform: rotate(90deg);
    -o-transform: rotate(90deg);
    transform: rotate(90deg);
    position: absolute;
    right: -5px;
    bottom: -5px;
}

/* Pencil */
div.icon div.pencil {
    height: 23px;
    width: 6px;
    background: #333;
    -webkit-transform: rotate(45deg);
    -moz-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    -o-transform: rotate(45deg);
    transform: rotate(45deg);
    position: absolute;
    left: 12px;
    top: 6px;
}

div.icon div.pencil:after {
    content: '';
    height: 4px;
    width: 6px;
    background: #333;
    -webkit-border-radius: 2px 2px 0 0;
    -moz-border-radius: 2px 2px 0 0;
    border-radius: 2px 2px 0 0;
    position: absolute;
    top: -5px;
    left: 0px;
}

div.icon div.pencil:before {
    content: '';
    width: 0px;
    height: 0px;
    border-width: 5px 3px 0 3px;
    border-style: solid;
    border-color: #333 transparent transparent transparent;
    position: absolute;
    bottom: -6px;
}

/* Chat Box */
div.icon div.chat {
    width: 32px;
    height: 22px;
    background: #333;
    border-radius: 4px;
    -webkit-border-radius: 4px;
    -moz-border-radius: 4px;
}

div.icon div.chat:after {
    content: '';
    width: 0px;
    height: 0px;
    border-style: solid;
    border-color: #333 transparent transparent transparent;
    border-width: 5px;
    position: absolute;
    top: 16px;
    left: 2px;
    -webkit-transform: rotate(135deg);
    -moz-transform: rotate(135deg);
    -ms-transform: rotate(135deg);
    -o-transform: rotate(135deg);
    transform: rotate(135deg);
}

div.icon div.lines {
    background-color: #eee;
    height: 2px;
    width: 17px;
    left: 5px;
    position: absolute;
    top: 5px;
}

div.icon div.lines:after {
    content: '';
    background-color: #eee;
    height: 2px;
    width: 10px;
    position: absolute;
    top: 5px;
}

div.icon div.lines:before {
    content: '';
    background-color: #eee;
    height: 2px;
    width: 22px;
    position: absolute;
    top: 10px;
}

/* Tick */
div.icon div.tick {
    width: 25px;
    height: 4px;
    background: #333;
    margin: 13px 0 0 6px;
    -webkit-transform: rotate(-45deg);
    -moz-transform: rotate(-45deg);
    -ms-transform: rotate(-45deg);
    -o-transform: rotate(-45deg);
    transform: rotate(-45deg);
}

div.icon div.tick:after {
    content: '';
    width: 12px;
    height: 4px;
    background: #333;
    position: absolute;
    top: -4px;
    left: -4px;
    -webkit-transform: rotate(90deg);
    -moz-transform: rotate(90deg);
    -ms-transform: rotate(90deg);
    -o-transform: rotate(90deg);
    transform: rotate(90deg);
}

/* Cross */
div.icon div.cross {
    width: 25px;
    height: 4px;
    background: #333;
    margin: 15px 0 0 4px;
    -webkit-transform: rotate(-45deg);
    -moz-transform: rotate(-45deg);
    -ms-transform: rotate(-45deg);
    -o-transform: rotate(-45deg);
    transform: rotate(-45deg);
}

div.icon div.cross:after {
    content: '';
    width: 25px;
    height: 4px;
    background: #333;
    position: absolute;
    top: 0px;
    left: 0px;
    -webkit-transform: rotate(90deg);
    -moz-transform: rotate(90deg);
    -ms-transform: rotate(90deg);
    -o-transform: rotate(90deg);
    transform: rotate(90deg);
}

/* User */
div.icon div.user {
    width: 12px;
    height: 13px;
    background: #333;
    border-radius: 5px 5px 0 0;
    margin-left: 10px;
    margin-top: 2px;
}

div.icon div.user:after {
    content: '';
    width: 8px;
    height: 5px;
    background: #333;
    position: absolute;
    margin-top: 13px;
    margin-left: 2px;
}

div.icon div.user:before {
    content: '';
    width: 0px;
    height: 0px;
    position: absolute;
    top: 17px;
    left: 0px;
    border-style: solid;
    border-color: transparent transparent #333 transparent;
    border-width: 0 16px 6px 16px;
}

div.icon div.shoulder {
    width: 32px;
    height: 5px;
    background: #333;
    position: absolute;
    bottom: 4px;
}

/* Search */
div.icon div.search {
    height: 13px;
    width: 13px;
    background: transparent;
    border-radius: 50px;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border: 4px solid #333;
}

div.icon div.search:after {
    content: '';
    width: 4px;
    height: 15px;
    background: #333;
    position: absolute;
    bottom: 2px;
    -webkit-transform: rotate(-45deg);
    -moz-transform: rotate(-45deg);
    -ms-transform: rotate(-45deg);
    -o-transform: rotate(-45deg);
    transform: rotate(-45deg);
    right: 8px;
}

/* Search */
div.icon div.searchB {
    width: 32px;
    height: 32px;
    background-color: #333;
    border-radius: 8px;
    -moz-border-radius: 8px;
    -webkit-border-radius: 8px;
}

div.icon div.searchB:before {
    position: absolute;
    content: '';
    height: 6px;
    width: 6px;
    background: transparent;
    border-radius: 50px;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    border: 3px solid #eee;
    margin: 7px
}

div.icon div.searchB:after {
    content: '';
    width: 3px;
    height: 11px;
    background: #eee;
    position: absolute;
    bottom: 6px;
    -webkit-transform: rotate(-45deg);
    -moz-transform: rotate(-45deg);
    -ms-transform: rotate(-45deg);
    -o-transform: rotate(-45deg);
    transform: rotate(-45deg);
    right: 10px;
}

/* Phone */
div.icon div.phone {
    position: absolute;
    width: 20px;
    height: 32px;
    background-color: #333;
    -webkit-border-radius: 2px;
    -moz-border-radius: 2px;
    border-radius: 2px;
    margin-left: 6px;
}

div.icon div.phone:before {
    position: absolute;
    content: '';
    width: 16px;
    height: 20px;
    background: #eee;
    left: 2px;
    top: 5px;
}

div.icon div.phone:after {
    position: absolute;
    content: '';
    background: #eee;
    width: 3px;
    height: 3px;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    bottom: 2px;
    left: 8px;
}

/* iPod */
div.icon div.ipod {
    width: 18px;
    height: 32px;
    background: #333;
    -webkit-border-radius: 2px;
    -moz-border-radius: 2px;
    border-radius: 2px;
    position: absolute;
    left: 7px;
}

div.icon div.ipod:after {
    content: '';
    position: absolute;
    width: 14px;
    height: 12px;
    background: #ddd;
    left: 2px;
    top: 2px;
    -webkit-border-radius: 1px;
    -moz-border-radius: 1px;
    border-radius: 1px;
}

div.icon div.ipod:before {
    content: '';
    position: absolute;
    width: 6px;
    height: 6px;
    border: 3px solid #ddd;
    left: 3px;
    bottom: 3px;
    -webkit-border-radius: 100px;
    -moz-border-radius: 100px;
    border-radius: 100px;
}

/* Tab */
div.icon div.tab {
    position: absolute;
    width: 28px;
    height: 32px;
    background-color: #333;
    -webkit-border-radius: 2px;
    -moz-border-radius: 2px;
    border-radius: 2px;
    left: 2px;
}

div.icon div.tab:before {
    position: absolute;
    content: '';
    width: 24px;
    height: 23px;
    background: #eee;
    left: 2px;
    top: 2px;
}

div.icon div.tab:after {
    position: absolute;
    content: '';
    background: #eee;
    width: 3px;
    height: 3px;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    bottom: 2px;
    left: 12px;
}

/* Graph 1 */
div.icon div.graph1 {
    width: 28px;
    height: 28px;
    border-radius: 0 0 0 5px;
    -moz-border-radius: 0 0 0 5px;
    -webkit-border-radius: 0 0 0 5px;
    border: solid #333;
    border-width: 0 0 3px 3px;
}

div.icon div.bars {
    width: 5px;
    height: 10px;
    background: #333;
    position: absolute;
    bottom: 5px;
    right: 3px;
}

div.icon div.bars:before {
    position: absolute;
    content: '';
    width: 5px;
    height: 25px;
    background: #333;
    position: absolute;
    right: 6px;
    bottom: 0px;
}

div.icon div.bars:after {
    position: absolute;
    content: '';
    width: 5px;
    height: 18px;
    background: #333;
    position: absolute;
    bottom: 0px;
    right: 12px;
}

/* Screen */
div.icon div.screen {
    width: 28px;
    height: 24px;
    border: 2px solid #333;
    background: #eee;
}

div.icon div.screen:before {
    position: absolute;
    content: '';
    width: 10px;
    height: 3px;
    background: #333;
    bottom: 2px;
    left: 11px
}

div.icon div.screen:after {
    position: absolute;
    content: '';
    width: 22px;
    height: 2px;
    background: #333;
    bottom: 0;
    left: 5px;
}

/* Cloud */
div.icon div.cloud {
    width: 32px;
    height: 12px;
    -webkit-border-radius: 10px;
    -moz-border-radius: 10px;
    border-radius: 10px;
    background: #333;
    margin-top: 14px;
}

div.icon div.cloud:before {
    position: absolute;
    content: '';
    width: 15px;
    height: 15px;
    -webkit-border-radius: 20px;
    -moz-border-radius: 20px;
    border-radius: 20px;
    background: #333;
    top: 7px;
    right: 5px;
}

div.icon div.cloud:after {
    position: absolute;
    content: '';
    width: 10px;
    height: 10px;
    -webkit-border-radius: 20px;
    -moz-border-radius: 20px;
    border-radius: 20px;
    background: #333;
    top: 9px;
    left: 4px;
}

/* Cloud-Up */
div.icon div.cloudUp {
    width: 32px;
    height: 12px;
    -webkit-border-radius: 10px;
    -moz-border-radius: 10px;
    border-radius: 10px;
    background: #333;
    margin-top: 14px;
}

div.icon div.cloudUp:before {
    position: absolute;
    content: '';
    width: 15px;
    height: 15px;
    -webkit-border-radius: 20px;
    -moz-border-radius: 20px;
    border-radius: 20px;
    background: #333;
    top: 7px;
    right: 5px;
}

div.icon div.cloudUp:after {
    position: absolute;
    content: '';
    width: 10px;
    height: 10px;
    -webkit-border-radius: 20px;
    -moz-border-radius: 20px;
    border-radius: 20px;
    background: #333;
    top: 9px;
    left: 4px;
}

div.icon div.cloudUpArrow {
    height: 0px;
    width: 0px;
    border-width: 5px;
    border-style: solid;
    border-color: transparent transparent #ddd transparent;
    position: absolute;
    bottom: 12px;
    left: 11px;
}

div.icon div.cloudUpArrow:after {
    content: '';
    width: 3px;
    height: 5px;
    background-color: #ddd;
    position: absolute;
    top: 4px;
    right: -2px;
}

/* Cloud-Down */
div.icon div.cloudDown {
    width: 32px;
    height: 12px;
    -webkit-border-radius: 10px;
    -moz-border-radius: 10px;
    border-radius: 10px;
    background: #333;
    margin-top: 14px;
}

div.icon div.cloudDown:before {
    position: absolute;
    content: '';
    width: 15px;
    height: 15px;
    -webkit-border-radius: 20px;
    -moz-border-radius: 20px;
    border-radius: 20px;
    background: #333;
    top: 7px;
    right: 5px;
}

div.icon div.cloudDown:after {
    position: absolute;
    content: '';
    width: 10px;
    height: 10px;
    -webkit-border-radius: 20px;
    -moz-border-radius: 20px;
    border-radius: 20px;
    background: #333;
    top: 9px;
    left: 4px;
}

div.icon div.cloudDownArrow {
    height: 0px;
    width: 0px;
    border-width: 5px;
    border-style: solid;
    border-color: #ddd transparent transparent transparent;
    position: absolute;
    bottom: 3px;
    left: 11px;
}

div.icon div.cloudDownArrow:after {
    content: '';
    width: 3px;
    height: 5px;
    background-color: #ddd;
    position: absolute;
    bottom: 4px;
    right: -2px;
}

/* Page */
div.icon div.page {
    width: 20px;
    height: 28px;
    background: #eee;
    margin-left: 4px;
    border: 2px solid #333;
}

div.icon div.page:before {
    position: absolute;
    content: '';
    height: 2px;
    width: 16px;
    background: #333;
    margin: 5px 2px 0 2px;
}

div.icon div.page:after {
    position: absolute;
    content: '';
    height: 2px;
    width: 16px;
    background: #333;
    margin: 9px 2px 0 2px;
}

div.icon div.pageLines {
    height: 2px;
    width: 16px;
    position: absolute;
    left: 8px;
    top: 15px;
    background: #333;
}

div.icon div.pageLines:after {
    position: absolute;
    content: '';
    height: 2px;
    width: 16px;
    background: #333;
    margin: 4px 0 0 0;
}

div.icon div.pageLines:before {
    position: absolute;
    content: '';
    height: 2px;
    width: 16px;
    background: #333;
    margin: 8px 0 0 0;
}

/* RSS */
div.icon div.rss {
    width: 6px;
    height: 6px;
    border-radius: 8px;
    -moz-border-radius: 8px;
    -webkit-border-radius: 8px;
    background: #333;
    position: absolute;
    bottom: 2px;
    left: 2px;
}

div.icon div.rss:after {
    content: '';
    position: absolute;
    width: 13px;
    height: 13px;
    border-radius: 0 60px 0 0;
    -moz-border-radius: 0 60px 0 0;
    -webkit-border-radius: 0 60px 0 0;
    border-style: double;
    border-width: 15px 15px 0 0;
    border-color: #333;
    top: -22px;
    left: 0;
}

/* Battery Full */
div.icon div.batFull {
    width: 23px;
    height: 11px;
    margin-top: 7px;
    border: 3px solid #333;
}

div.icon div.batFull:after {
    content: '';
    position: absolute;
    height: 7px;
    width: 2px;
    background: #333;
    right: 1px;
    top: 5px;
    margin-top: 7px;
}

div.icon div.batFull:before {
    content: '';
    position: absolute;
    height: 9px;
    width: 21px;
    background: #333;
    left: 4px;
    top: 4px;
    margin-top: 7px;
}

/* Battery Medium */
div.icon div.batMed {
    width: 23px;
    height: 11px;
    margin-top: 7px;
    border: 3px solid #333;
}

div.icon div.batMed:after {
    content: '';
    position: absolute;
    height: 7px;
    width: 2px;
    background: #333;
    right: 1px;
    top: 5px;
    margin-top: 7px;
}

div.icon div.batMed:before {
    content: '';
    position: absolute;
    height: 9px;
    width: 10px;
    background: #333;
    left: 4px;
    top: 4px;
    margin-top: 7px;
}

/* Battery Low */
div.icon div.batLow {
    width: 23px;
    height: 11px;
    margin-top: 7px;
    border: 3px solid #333;
}

div.icon div.batLow:after {
    content: '';
    position: absolute;
    height: 7px;
    width: 2px;
    background: #333;
    right: 1px;
    top: 5px;
    margin-top: 7px;
}

div.icon div.batLow:before {
    content: '';
    position: absolute;
    height: 9px;
    width: 3px;
    background: #333;
    left: 4px;
    top: 4px;
    margin-top: 7px;
}

/* Battery Empty */
div.icon div.batEmpty {
    width: 23px;
    height: 11px;
    margin-top: 7px;
    border: 3px solid #333;
}

div.icon div.batEmpty:after {
    content: '';
    position: absolute;
    height: 7px;
    width: 2px;
    background: #333;
    right: 1px;
    top: 5px;
    margin-top: 7px;
}

/* Speaker Volume Full */
div.icon div.speakerVolF {
    width: 10px;
    height: 10px;
    background: #333;
    margin: 12px 0 0 2px;
}

div.icon div.speakerVolF:after {
    content: '';
    position: absolute;
    width: 0;
    height: 0;
    border-style: solid;
    border-color: transparent #333 transparent transparent;
    border-width: 12px 16px 12px 15px;
    left: -13px;
    top: 5px;
}

div.icon div.speakerVolF:before {
    content: '';
    position: absolute;
    width: 5px;
    height: 5px;
    border-style: double;
    border-color: #333;
    border-width: 8px 8px 0 0;
    -webkit-border-radius: 0 50px 0 0;
    -moz-border-radius: 0 50px 0 0;
    border-radius: 0 50px 0 0;
    -webkit-transform: rotate(45deg);
    -moz-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    -o-transform: rotate(45deg);
    transform: rotate(45deg);
    left: 19px;
    top: 11px;
}

/* Speaker Volume Half */
div.icon div.speakerVolH {
    width: 10px;
    height: 10px;
    background: #333;
    margin: 12px 0 0 4px;
}

div.icon div.speakerVolH:after {
    content: '';
    position: absolute;
    width: 0;
    height: 0;
    border-style: solid;
    border-color: transparent #333 transparent transparent;
    border-width: 12px 16px 12px 15px;
    left: -11px;
    top: 5px;
}

div.icon div.speakerVolH:before {
    content: '';
    position: absolute;
    width: 5px;
    height: 5px;
    border-style: solid;
    border-color: #333;
    border-width: 3px 3px 0 0;
    -webkit-border-radius: 0 50px 0 0;
    -moz-border-radius: 0 50px 0 0;
    border-radius: 0 50px 0 0;
    -webkit-transform: rotate(45deg);
    -moz-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    -o-transform: rotate(45deg);
    transform: rotate(45deg);
    left: 21px;
    top: 13px;
}

/* Speaker Volume Mute */
div.icon div.speakerVolM {
    width: 10px;
    height: 10px;
    background: #333;
    margin: 12px 0 0 7px;
}

div.icon div.speakerVolM:after {
    content: '';
    position: absolute;
    width: 0;
    height: 0;
    border-style: solid;
    border-color: transparent #333 transparent transparent;
    border-width: 12px 16px 12px 15px;
    left: -8px;
    top: 5px;
}

/* Play */
div.icon div.play {
    width: 0;
    height: 0;
    border-style: solid;
    border-color: transparent transparent transparent #333;
    border-width: 8px 8px 8px 12px;
    margin: 8px 0 0 11px;
}

/* Pause */
div.icon div.pause {
    width: 2px;
    height: 16px;
    border: 4px solid #333;
    border-top: none;
    border-bottom: none;
    margin: 8px 0 0 11px;
}

/* Forward */
div.icon div.forward {
    width: 0;
    height: 0;
    border-style: solid;
    border-color: transparent transparent transparent #333;
    border-width: 8px 8px 8px 12px;
    margin: 8px 0 0 5px;
}

div.icon div.forward:after {
    content: '';
    position: absolute;
    width: 0;
    height: 0;
    border-style: solid;
    border-color: transparent transparent transparent #333;
    border-width: 8px 8px 8px 12px;
    margin: 8px 0 0 17px;
    left: 0;
    top: 0
}

/* Next */
div.icon div.next {
    width: 0;
    height: 0;
    border-style: solid;
    border-color: transparent transparent transparent #333;
    border-width: 8px 8px 8px 12px;
    margin: 8px 0 0 2px;
}

div.icon div.next:after {
    content: '';
    position: absolute;
    width: 0px;
    height: 0;
    border-style: solid;
    border-color: transparent transparent transparent #333;
    border-width: 8px 8px 8px 12px;
    margin: 8px 0 0 14px;
    left: 0;
    top: 0
}

div.icon div.next:before {
    content: '';
    position: absolute;
    background: #333;
    width: 4px;
    height: 16px;
    left: 0;
    top: 0;
    margin: 8px 0 0 26px;
}

/* Rewind */
div.icon div.rewind {
    width: 0;
    height: 0;
    border-style: solid;
    border-color: transparent #333 transparent transparent;
    border-width: 8px 12px 8px 8px;
    margin: 8px 0 0 -5px;
}

div.icon div.rewind:after {
    content: '';
    position: absolute;
    width: 0px;
    height: 0;
    border-style: solid;
    border-color: transparent #333 transparent transparent;
    border-width: 8px 12px 8px 8px;
    margin: 8px 0 0 7px;
    left: 0;
    top: 0
}

/* Previous */
div.icon div.previous {
    width: 0;
    height: 0;
    border-style: solid;
    border-color: transparent #333 transparent transparent;
    border-width: 8px 12px 8px 8px;
    margin: 8px 0 0 -2px;
}

div.icon div.previous:after {
    content: '';
    position: absolute;
    width: 0px;
    height: 0;
    border-style: solid;
    border-color: transparent #333 transparent transparent;
    border-width: 8px 12px 8px 8px;
    margin: 8px 0 0 10px;
    left: 0;
    top: 0
}

div.icon div.previous:before {
    content: '';
    position: absolute;
    background: #333;
    width: 4px;
    height: 16px;
    left: 0;
    top: 0;
    margin: 8px 0 0 2px;
}

/* Stop */
div.icon div.stop {
    width: 16px;
    height: 16px;
    margin: 8px 0 0 8px;
    background: #333;
}

/* Location */
div.icon div.location {
    width: 0px;
    height: 0px;
    border-style: solid;
    border-color: #333 transparent transparent transparent;
    border-width: 16px 8px 8px 8px;
    margin: 15px 0 0 8px;
}

div.icon div.location:after {
    content: '';
    position: absolute;
    width: 18px;
    height: 18px;
    border-radius: 50px;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    background: #333;
    left: 7px;
    top: 2px;
}

div.icon div.location:before {
    content: '';
    position: absolute;
    width: 8px;
    height: 8px;
    border-radius: 50px;
    -moz-border-radius: 50px;
    -webkit-border-radius: 50px;
    background: #ddd;
    left: 12px;
    top: 7px;
    z-index: 2;
}

/* Clock */
div.icon div.clock {
    width: 4px;
    height: 6px;
    border: solid #333;
    border-width: 0 0 3px 3px;
    margin: 9px 0 0 14px
}

div.icon div.clock:after {
    content: '';
    position: absolute;
    width: 18px;
    height: 18px;
    border: 4px solid #333;
    border-radius: 50px;
    top: 3px;
    left: 3px;
}

/* Clock Alt */
div.icon div.clockAlt {
    width: 18px;
    height: 18px;
    border: 4px solid #333;
    border-radius: 50px;
    margin-top: 3px;
    margin-left: 3px;
}

div.icon div.clockAlt:after {
    content: '';
    position: absolute;
    width: 4px;
    height: 5px;
    border: solid #ddd;
    border-width: 0 0 2px 2px;
    top: 11px;
    left: 15px;
}

div.icon div.clockAlt:before {
    content: '';
    position: absolute;
    width: 16px;
    height: 16px;
    background: #333;
    border-radius: 50px;
    left: 8px;
    top: 8px;
}

/* Pointer Right */
div.icon div.pointerRight {
    width: 10px;
    height: 10px;
    border: solid #333;
    border-width: 6px 6px 0 0;
    -webkit-transform: rotate(45deg);
    -moz-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    -o-transform: rotate(45deg);
    transform: rotate(45deg);
    margin: 8px 0 0 5px;
}

/* Pointer Top */
div.icon div.pointerTop {
    width: 10px;
    height: 10px;
    border: solid #333;
    border-width: 6px 6px 0 0;
    -webkit-transform: rotate(-45deg);
    -moz-transform: rotate(-45deg);
    -ms-transform: rotate(-45deg);
    -o-transform: rotate(-45deg);
    transform: rotate(-45deg);
    margin: 10px 0 0 8px;
}

/* Pointer Left */
div.icon div.pointerLeft {
    width: 10px;
    height: 10px;
    border: solid #333;
    border-width: 6px 6px 0 0;
    -webkit-transform: rotate(-135deg);
    -moz-transform: rotate(-135deg);
    -ms-transform: rotate(-135deg);
    -o-transform: rotate(-135deg);
    transform: rotate(-135deg);
    margin: 8px 0 0 5px;
}

/* Pointer Down */
div.icon div.pointerDown {
    width: 10px;
    height: 10px;
    border: solid #333;
    border-width: 6px 6px 0 0;
    -webkit-transform: rotate(135deg);
    -moz-transform: rotate(135deg);
    -ms-transform: rotate(135deg);
    -o-transform: rotate(135deg);
    transform: rotate(135deg);
    margin: 5px 0 0 8px;
}

/* Signals */
div.icon div.signal1 {
    width: 5px;
    height: 5px;
    background: #333;
    position: absolute;
    bottom: 0;
    left: 1px
}

div.icon div.signal1:after {
    content: '';
    position: absolute;
    width: 5px;
    height: 9px;
    background: #333;
    left: 6px;
    bottom: 0;
}

div.icon div.signal1:before {
    content: '';
    position: absolute;
    width: 5px;
    height: 14px;
    background: #333;
    left: 12px;
    bottom: 0;
}

div.icon div.signal2 {
    width: 5px;
    height: 22px;
    background: #333;
    position: absolute;
    bottom: 0;
    left: 19px
}

div.icon div.signal2:after {
    content: '';
    position: absolute;
    width: 5px;
    height: 32px;
    background: #333;
    left: 6px;
    bottom: 0;
}

/* Graph 2 */
div.icon div.base {
    width: 5px;
    height: 8px;
    background: #333;
    position: absolute;
    bottom: 3px;
    left: 4px
}

div.icon div.base:after {
    content: '';
    position: absolute;
    width: 5px;
    height: 13px;
    background: #333;
    left: 6px;
    bottom: 0;
}

div.icon div.base:before {
    content: '';
    position: absolute;
    width: 5px;
    height: 25px;
    background: #333;
    left: 12px;
    bottom: 0;
}

div.icon div.bars2 {
    width: 5px;
    height: 18px;
    background: #333;
    position: absolute;
    bottom: 3px;
    left: 22px
}

div.icon div.bars2:after {
    content: '';
    position: absolute;
    width: 32px;
    height: 2px;
    background: #333;
    left: -22px;
    bottom: 0px;
}

/* Ribbon */
div.icon div.ribbon {
    width: 12px;
    height: 20px;
    background: #333;
    margin: 2px 0 0 10px
}

div.icon div.ribbon:after {
    content: '';
    position: absolute;
    left: 10px;
    top: 16px;
    width: 0;
    height: 0;
    border: solid #333;
    border-color: transparent #333 transparent #333;
    border-width: 6px 6px 8px 6px;
}

/* Video Cam */
div.icon div.videoCam {
    width: 18px;
    height: 16px;
    background: #333;
    margin: 8px 0 0 3px
}

div.icon div.videoCam:after {
    content: '';
    position: absolute;
    left: 14px;
    top: 10px;
    width: 0;
    height: 0;
    border: solid #333;
    border-color: transparent #333 transparent transparent;
    border-width: 6px 8px 6px 6px;
}

/* Star */
div.icon div.star {
    margin: 13px 0;
    position: relative;
    display: block;
    width: 0px;
    height: 0px;
    border-right: 17px solid transparent;
    border-bottom: 10px solid #333;
    border-left: 16px solid transparent;
    -moz-transform: rotate(35deg);
    -webkit-transform: rotate(35deg);
    -ms-transform: rotate(35deg);
    -o-transform: rotate(35deg);
}

div.icon div.star:before {
    border-bottom: 12px solid #333;
    border-left: 4px solid transparent;
    border-right: 4px solid transparent;
    position: absolute;
    height: 0;
    width: 0;
    top: -9px;
    left: -10px;
    display: block;
    content: '';
    -webkit-transform: rotate(-35deg);
    -moz-transform: rotate(-35deg);
    -ms-transform: rotate(-35deg);
    -o-transform: rotate(-35deg);
}

div.icon div.star:after {
    position: absolute;
    display: block;
    top: 0px;
    left: -17px;
    width: 0px;
    height: 0px;
    border-right: 17px solid transparent;
    border-bottom: 10px solid #333;
    border-left: 16px solid transparent;
    -webkit-transform: rotate(-70deg);
    -moz-transform: rotate(-70deg);
    -ms-transform: rotate(-70deg);
    -o-transform: rotate(-70deg);
    content: '';
}

/* Headphones */
div.icon div.headphones {
    width: 26px;
    border: 3px solid #333;
    height: 23px;
    border-radius: 50px 50px 0 0;
    border-bottom: none;
    margin: 1px 0 0 0;
}

div.icon div.headphones:before {
    position: absolute;
    content: '';
    top: 21px;
    left: 4px;
    width: 5px;
    height: 10px;
    background: #333;
    border-radius: 0 2px 2px 0;
}

div.icon div.headphones:after {
    position: absolute;
    content: '';
    top: 21px;
    left: 23px;
    width: 5px;
    height: 10px;
    background: #333;
    border-radius: 2px 0 0 2px;
}

/* Capsule */
div.icon div.capsule {
    width: 13px;
    background: #333;
    height: 15px;
    border-radius: 50px 50px 0 0;
    position: absolute;
    top: 5px;
    left: 13px;
    -webkit-transform: rotate(45deg);
    -moz-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    -o-transform: rotate(45deg);
}

div.icon div.capsule:before {
    position: absolute;
    content: '';
    width: 13px;
    background: #333;
    height: 10px;
    border-radius: 0 0 50px 50px;
    -webkit-border-radius: 0 0 50px 50px;
    -moz-border-radius: 0 0 50px 50px;
    top: 16px;
    left: 0
}

/* Microphone */
div.icon div.mic {
    width: 10px;
    background: #333;
    height: 10px;
    border-radius: 50px 50px 0 0;
    -moz-border-radius: 50px 50px 0 0;
    -webkit-border-radius: 50px 50px 0 0;
    position: absolute;
    top: 2px;
    left: 11px;
}

div.icon div.mic:after {
    position: absolute;
    content: '';
    width: 10px;
    background: #333;
    height: 10px;
    border-radius: 0 0 50px 50px;
    -webkit-border-radius: 0 0 50px 50px;
    -moz-border-radius: 0 0 50px 50px;
    top: 11px;
    left: 0
}

div.icon div.holder {
    position: absolute;
    height: 11px;
    width: 12px;
    left: 8px;
    top: 13px;
    border: 2px solid #333;
    border-radius: 0 0 50px 50px;
    -webkit-border-radius: 0 0 50px 50px;
    -moz-border-radius: 0 0 50px 50px;
    border-top: none;
}

div.icon div.holder:after {
    content: '';
    position: absolute;
    width: 4px;
    height: 3px;
    background: #333;
    top: 13px;
    left: 4px;
}

div.icon div.holder:before {
    content: '';
    position: absolute;
    width: 8px;
    height: 2px;
    background: #333;
    bottom: -6px;
    left: 2px;
}

/* Tower */
div.icon div.tower {
    width: 0px;
    height: 0px;
    position: absolute;
    bottom: 1px;
    left: 13px;
    border: solid #333;
    border-color: transparent transparent #333 transparent;
    border-width: 0px 3px 22px 3px;
}

div.icon div.tower:after {
    position: absolute;
    content: '';
    width: 4px;
    height: 4px;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    background: #333;
    left: -2px;
    top: 0;
}

div.icon div.waves {
    position: absolute;
    content: '';
    width: 8px;
    height: 8px;
    border-color: #333;
    border-style: double;
    border-width: 6px 6px 0 0;
    -webkit-border-radius: 0 50px 0 0;
    -moz-border-radius: 0 50px 0 0;
    border-radius: 0 50px 0 0;
    left: 17px;
    top: 4px;
    -webkit-transform: rotate(45deg);
    -moz-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    -o-transform: rotate(45deg);
}

div.icon div.waves:after {
    position: absolute;
    content: '';
    width: 8px;
    height: 8px;
    border-color: #333;
    border-style: double;
    border-width: 6px 6px 0 0;
    -webkit-border-radius: 0 50px 0 0;
    -moz-border-radius: 0 50px 0 0;
    border-radius: 0 50px 0 0;
    left: -11px;
    top: 5px;
    -webkit-transform: rotate(180deg);
    -moz-transform: rotate(180deg);
    -ms-transform: rotate(180deg);
    -o-transform: rotate(180deg);
}

/* IceCream */
div.icon div.icecream {
    width: 20px;
    height: 25px;
    background: #333;
    -webkit-border-radius: 50px 50px 10px 10px;
    -moz-border-radius: 50px 50px 10px 10px;
    border-radius: 50px 50px 10px 10px;
    position: absolute;
    top: 0;
    left: 6px;
}

div.icon div.icecream:after {
    content: '';
    position: absolute;
    bottom: -7px;
    left: 8px;
    width: 4px;
    height: 7px;
    background: #333;
}

/* Golf */
div.icon div.golf_stick {
    width: 2px;
    height: 25px;
    background: #333;
    -webkit-border-radius: 50px 50px 10px 10px;
    -moz-border-radius: 50px 50px 10px 10px;
    border-radius: 50px 50px 10px 10px;
    position: absolute;
    bottom: 2px;
    left: 15px;
}

div.icon div.golf_stick:after {
    content: '';
    position: absolute;
    bottom: 0px;
    left: -3px;
    width: 8px;
    height: 2px;
    background: #333;
}

div.icon div.golf_ball {
    position: absolute;
    left: 9px;
    top: 2px;
    width: 14px;
    height: 14px;
    background: #333;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
}

div.icon div.golf_ball:after {
    content: '';
    position: absolute;
    top: 3px;
    left: 3px;
    background: #ddd;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    width: 3px;
    height: 3px;
}

/* PolyBag */
div.icon div.polybag {
    width: 32px;
    height: 16px;
    background: #333;
    position: absolute;
    top: 8px;
    left: 0;
}

div.icon div.polybag:after {
    content: '';
    position: absolute;
    left: 0;
    bottom: -7px;
    height: 6px;
    width: 32px;
    background: #333;
    -webkit-border-radius: 0 0 4px 4px;
    -moz-border-radius: 0 0 4px 4px;
    border-radius: 0 0 4px 4px;
}

div.icon div.polybag:before {
    content: '';
    position: absolute;
    top: -7px;
    left: 9px;
    width: 10px;
    height: 10px;
    border: 2px solid #333;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
}

/* BriefCase */
div.icon div.briefcase {
    width: 18px;
    height: 23px;
    background: #333;
    position: absolute;
    top: 7px;
    left: 7px;
}

div.icon div.briefcase:after {
    content: '';
    position: absolute;
    left: -7px;
    bottom: 0px;
    height: 23px;
    width: 6px;
    background: #333;
    -webkit-border-radius: 3px 0 0 3px;
    -moz-border-radius: 3px 0 0 3px;
    border-radius: 3px 0 0 3px;
}

div.icon div.briefcase:before {
    content: '';
    position: absolute;
    right: -7px;
    bottom: 0px;
    height: 23px;
    width: 6px;
    background: #333;
    -webkit-border-radius: 0 3px 3px 0;
    -moz-border-radius: 0 3px 3px 0;
    border-radius: 0 3px 3px 0;
}

div.icon div.briefcase_handle {
    position: absolute;
    left: 9px;
    top: 2px;
    width: 10px;
    height: 3px;
    border: 2px solid #333;
    -webkit-border-radius: 3px 3px 0 0;
    -moz-border-radius: 3px 3px 0 0;
    border-radius: 3px 3px 0 0;
}

/* Roller */
div.icon div.roller_brush {
    position: absolute;
    top: 0;
    left: 0;
    width: 29px;
    height: 10px;
    background: #333;
    -webkit-border-radius: 3px;
    -moz-border-radius: 3px;
    border-radius: 3px;
}

div.icon div.roller_brush:after {
    content: '';
    position: absolute;
    right: -3px;
    top: 3px;
    height: 6px;
    width: 15px;
    border: 2px solid #333;
    border-left: none;
}

div.icon div.roller_handle {
    position: absolute;
    width: 4px;
    position: absolute;
    left: 14px;
    bottom: 0;
    height: 17px;
    -webkit-border-radius: 2px;
    -moz-border-radius: 2px;
    border-radius: 2px;
    background: #333;
}

div.icon div.roller_handle:before {
    content: '';
    position: absolute;
    width: 2px;
    top: -2px;
    height: 4px;
    left: 1px;
    background: #333;
}

/* Magnet */
div.icon div.magnet {
    position: absolute;
    bottom: 2px;
    left: 2px;
    width: 16px;
    height: 15px;
    border: 6px solid #333;
    border-top: none;
    -webkit-border-radius: 0 0 30px 30px;
    -moz-border-radius: 0 0 30px 30px;
    border-radius: 0 0 30px 30px;
}

div.icon div.magnet:after {
    content: '';
    position: absolute;
    right: -6px;
    top: -7px;
    width: 6px;
    height: 6px;
    background: #333;
}

div.icon div.magnet:before {
    content: '';
    position: absolute;
    left: -6px;
    top: -7px;
    width: 6px;
    height: 6px;
    background: #333;
}

/* Bomb */
div.icon div.bomb {
    position: absolute;
    bottom: 0;
    left: 4px;
    width: 24px;
    height: 24px;
    background: #333;
    -webkit-border-radius: 30px;
    -moz-border-radius: 30px;
    border-radius: 30px;
}

div.icon div.bomb:after {
    content: '';
    position: absolute;
    top: -1px;
    left: 8px;
    width: 8px;
    background: #333;
    height: 3px;
}

div.icon div.bomb:before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 8px;
    height: 15px;
    border: 2px solid #333;
    border-right: none;
    -webkit-border-radius: 50px 0 0 50px;
    -moz-border-radius: 50px 0 0 50px;
    border-radius: 50px 0 0 50px;
    left: 11px;
    top: -8px;
}

/* BirdHouse */
div.icon div.birdhouse {
    width: 0;
    height: 0;
    position: absolute;
    top: 0;
    left: 0;
    border-style: solid;
    border-color: transparent transparent #333 transparent;
    border-width: 0 16px 14px;
}

div.icon div.birdhouse:after {
    content: '';
    position: absolute;
    top: 14px;
    left: -12px;
    border-style: solid;
    border-color: #333 transparent transparent transparent;
    border-width: 100px 12px;
}

div.icon div.birdhouse_holes {
    width: 12px;
    height: 12px;
    background: #ddd;
    position: absolute;
    -webkit-border-radius: 60px;
    -moz-border-radius: 60px;
    border-radius: 60px;
    left: 10px;
    top: 8px;
}

div.icon div.birdhouse_holes:after {
    content: '';
    position: absolute;
    width: 4px;
    height: 4px;
    background: #ccc;
    bottom: -8px;
    left: 4px;
    -webkit-border-radius: 60px;
    -moz-border-radius: 60px;
    border-radius: 60px;
}

/* Woofer */
div.icon div.woofer {
    width: 22px;
    height: 32px;
    position: absolute;
    top: 0;
    left: 5px;
    background: #333;
    border-radius: 2px;
    -webkit-border-radius: 2px;
    -moz-border-radius: 2px;
}

div.icon div.woofer:after {
    content: '';
    position: absolute;
    width: 2px;
    height: 2px;
    background: #333;
    border-radius: 60px;
    -moz-border-radius: 60px;
    -webkit-border-radius: 60px;
    border: 2px solid #ddd;
    left: 8px;
    top: 5px;
}

div.icon div.woofer:before {
    content: '';
    position: absolute;
    width: 4px;
    height: 4px;
    background: #333;
    border-radius: 60px;
    -moz-border-radius: 60px;
    -webkit-border-radius: 60px;
    border: 5px solid #ddd;
    left: 4px;
    top: 14px;
}

/* HandBag */
div.icon div.handbag {
    position: absolute;
    top: 13px;
    left: 1px;
    height: 0;
    width: 24px;
    border-style: solid;
    border-color: transparent transparent #333 transparent;
    border-width: 0 3px 16px;
}

div.icon div.handbag:after {
    content: '';
    position: absolute;
    left: 0;
    top: -3px;
    height: 3px;
    width: 24px;
    background: #333;
}

div.icon div.handbag:before {
    content: '';
    position: absolute;
    width: 16px;
    height: 16px;
    border: 2px solid #333;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    top: -10px;
    left: 2px;
}

/* Bell */
div.icon div.belltop {
    position: absolute;
    width: 6px;
    height: 6px;
    border: 2px solid #333;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    left: 11px;
}

div.icon div.belltop:after {
    content: '';
    position: absolute;
    top: 1px;
    width: 20px;
    height: 20px;
    background: #333;
    left: -7px;
    -webkit-border-radius: 50px 50px 0 0;
    -moz-border-radius: 50px 50px 0 0;
    border-radius: 50px 50px 0 0;
}

div.icon div.belltop:before {
    content: '';
    position: absolute;
    left: -11px;
    top: 14px;
    width: 20px;
    height: 0;
    border-style: solid;
    border-color: transparent transparent #333 transparent;
    border-width: 0 4px 9px;
}

div.icon div.bellbottom {
    position: absolute;
    bottom: 5px;
    left: 2px;
    width: 28px;
    height: 2px;
    background: #333;
}

div.icon div.bellbottom:after {
    content: '';
    position: absolute;
    width: 6px;
    height: 3px;
    background: #333;
    -webkit-border-radius: 0 0 50px 50px;
    -moz-border-radius: 0 0 50px 50px;
    border-radius: 0 0 50px 50px;
    top: 3px;
    left: 5px;
}

/* SignBoard */
div.icon div.signboard {
    position: absolute;
    top: 3px;
    left: 2px;
    width: 28px;
    height: 18px;
    background: #333;
}

div.icon div.signboard:after {
    content: '';
    position: absolute;
    height: 8px;
    width: 4px;
    background: #333;
    bottom: -8px;
    left: 12px;
}

div.icon div.signboard_arrow {
    width: 6px;
    height: 4px;
    background: #ddd;
    position: absolute;
    top: 10px;
    left: 10px;
}

div.icon div.signboard_arrow:after {
    content: '';
    position: absolute;
    width: 0;
    height: 0;
    border-style: solid;
    border-color: transparent transparent transparent #ddd;
    border-width: 6px;
    right: -12px;
    top: -4px;
}

/* Music Note */
div.icon div.musicnote_base {
    width: 14px;
    height: 4px;
    background: #333;
    position: absolute;
    top: 5px;
    left: 12px;
    -webkit-transform: skew(0, -10deg);
    -moz-transform: skew(0, -10deg);
    -ms-transform: skew(0, -10deg);
    -o-transform: skew(0, -10deg);
    transform: skew(0, -10deg);
}

div.icon div.musicnote_left {
    position: absolute;
    top: 8px;
    left: 12px;
    width: 2px;
    height: 16px;
    background: #333;
}

div.icon div.musicnote_right {
    position: absolute;
    top: 5px;
    right: 6px;
    width: 2px;
    height: 17px;
    background: #333;
}

div.icon div.musicnote_ovals {
    position: absolute;
    width: 8px;
    height: 6px;
    background: #333;
    -webkit-border-radius: 12px / 8px;
    -moz-border-radius: 12px / 8px;
    border-radius: 12px / 8px;
    bottom: 4px;
    left: 6px;
}

div.icon div.musicnote_ovals:after {
    content: '';
    position: absolute;
    width: 8px;
    height: 6px;
    background: #333;
    -webkit-border-radius: 12px / 8px;
    -moz-border-radius: 12px / 8px;
    border-radius: 12px / 8px;
    bottom: 3px;
    left: 12px;
}

/* Key */
div.icon div.key_base {
    width: 22px;
    height: 22px;
    background: #333;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    position: absolute;
    top: 0;
    left: 0;
}

div.icon div.key_base:after {
    content: '';
    position: absolute;
    top: 5px;
    left: 5px;
    width: 6px;
    height: 6px;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    background: #ddd;
}

div.icon div.key_base:before {
    content: '';
    position: absolute;
    height: 12px;
    width: 5px;
    border-top: 6px solid #333;
    border-right: 3px solid #333;
    -webkit-transform: rotate(315deg);
    -moz-transform: rotate(315deg);
    -ms-transform: rotate(315deg);
    -o-transform: rotate(315deg);
    transform: rotate(315deg);
    left: 18px;
    top: 14px;
}

div.icon div.key_squares {
    width: 6px;
    height: 6px;
    background: #333;
    position: absolute;
    top: 18px;
    left: 17px;
}

div.icon div.key_squares:after {
    content: '';
    width: 6px;
    height: 6px;
    background: #333;
    position: absolute;
    top: 4px;
    left: 4px;
}

div.icon div.key_squares:before {
    content: '';
    width: 6px;
    height: 6px;
    background: #333;
    position: absolute;
    top: 8px;
    left: 8px;
}

/* Download */
div.icon div.download {
    width: 24px;
    height: 8px;
    border: 4px solid #333;
    border-top: none;
    position: absolute;
    bottom: 3px;
}

div.icon div.download:after {
    width: 0px;
    height: 0px;
    content: '';
    position: absolute;
    border-style: solid;
    border-color: #333 transparent transparent transparent;
    border-width: 8px;
    left: 4px;
    top: -4px;
}

div.icon div.download:before {
    content: '';
    position: absolute;
    width: 7px;
    height: 10px;
    background: #333;
    top: -14px;
    left: 9px;
}

/* Upload */
div.icon div.upload {
    width: 24px;
    height: 8px;
    border: 4px solid #333;
    border-top: none;
    position: absolute;
    bottom: 3px;
}

div.icon div.upload:after {
    width: 0px;
    height: 0px;
    content: '';
    position: absolute;
    border-style: solid;
    border-color: transparent transparent #333 transparent;
    border-width: 8px;
    left: 4px;
    top: -22px;
}

div.icon div.upload:before {
    content: '';
    position: absolute;
    width: 7px;
    height: 10px;
    background: #333;
    top: -6px;
    left: 9px;
}

/* Reload */
div.icon div.reload {
    width: 18px;
    height: 9px;
    border-style: solid;
    border-width: 0px 4px 4px 4px;
    border-color: #333;
    -webkit-border-radius: 0 0 50px 50px;
    -moz-border-radius: 0 0 50px 50px;
    border-radius: 0 0 50px 50px;
    position: absolute;
    top: 18px;
    left: 2px;
}

div.icon div.reload:after {
    content: '';
    width: 9px;
    height: 9px;
    border-style: solid;
    border-width: 4px 0 0 4px;
    border-color: #333;
    -webkit-border-radius: 50px 0 0 0;
    -moz-border-radius: 50px 0 0 0;
    border-radius: 50px 0 0 0;
    position: absolute;
    left: -4px;
    bottom: 9px;
}

div.icon div.reload:before {
    content: '';
    position: absolute;
    width: 0;
    height: 0;
    border-style: solid;
    border-width: 6px;
    border-color: transparent transparent transparent #333;
    bottom: 14px;
    left: 9px;
}

/* LoopBack */
div.icon div.loopback_l {
    width: 10px;
    height: 5px;
    border-style: solid;
    border-width: 0px 3px 3px 3px;
    border-color: #333;
    border-radius: 0 0 50px 50px;
    position: absolute;
    top: 16px;
    left: 1px;
}

div.icon div.loopback_l:after {
    content: '';
    width: 5px;
    height: 5px;
    border-style: solid;
    border-width: 3px 0 0 3px;
    border-color: #333;
    border-radius: 50px 0 0 0;
    position: absolute;
    left: -3px;
    bottom: 5px;
}

div.icon div.loopback_l:before {
    content: '';
    position: absolute;
    width: 0;
    height: 0;
    border-style: solid;
    border-width: 4px;
    border-color: transparent transparent transparent #333;
    bottom: 7px;
    left: 5px;
}

div.icon div.loopback_r {
    width: 10px;
    height: 5px;
    border-style: solid;
    border-width: 3px 3px 0 3px;
    border-color: #333;
    border-radius: 50px 50px 0 0;
    position: absolute;
    top: 8px;
    right: 2px;
}

div.icon div.loopback_r:after {
    content: '';
    width: 5px;
    height: 5px;
    border-style: solid;
    border-width: 0 3px 3px 0;
    border-color: #333;
    border-radius: 0 0 50px 0;
    position: absolute;
    left: 5px;
    top: 5px;
}

div.icon div.loopback_r:before {
    content: '';
    position: absolute;
    width: 0;
    height: 0;
    border-style: solid;
    border-width: 4px;
    border-color: transparent #333 transparent transparent;
    top: 7px;
    right: 5px;
}

/* Redo */
div.icon div.redo_l {
    width: 8px;
    height: 8px;
    border-style: solid;
    border-width: 0px 0px 4px 4px;
    border-color: #333;
    -webkit-border-radius: 0 0 0 50px;
    -moz-border-radius: 0 0 0 50px;
    border-radius: 0 0 0 50px;
    position: absolute;
    bottom: 4px;
    left: 4px;
}

div.icon div.redo_l:before {
    content: '';
    position: absolute;
    width: 0;
    height: 0;
    border-style: solid;
    border-width: 6px;
    border-color: transparent transparent #333 transparent;
    bottom: 8px;
    left: -8px;
}

div.icon div.redo_r {
    width: 8px;
    height: 8px;
    border-style: solid;
    border-width: 4px 4px 0 0;
    border-color: #333;
    -webkit-border-radius: 0 50px 0 0;
    -moz-border-radius: 0 50px 0 0;
    border-radius: 0 50px 0 0;
    position: absolute;
    top: 4px;
    right: 4px;
}

div.icon div.redo_r:before {
    content: '';
    position: absolute;
    width: 0;
    height: 0;
    border-style: solid;
    border-width: 6px;
    border-color: #333 transparent transparent transparent;
    top: 8px;
    right: -8px;
}

/* Target */
div.icon div.target {
    width: 15px;
    height: 15px;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    border: 8px double #333;
    position: absolute;
    top: 0px;
    left: 0px;
}

div.icon div.target:after {
    content: '';
    position: absolute;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    width: 11px;
    height: 11px;
    background: #333;
    left: 2px;
    top: 2px;
}

/* Lock Open */
div.icon div.lockClosed_base {
    width: 20px;
    height: 16px;
    background: #333;
    position: absolute;
    left: 6px;
    top: 12px;
}

div.icon div.lockClosed_base:after {
    content: '';
    position: absolute;
    background: #ddd;
    width: 4px;
    height: 4px;
    left: 8px;
    top: 5px;
    -webkit-border-radius: 40px;
    -moz-border-radius: 40px;
    border-radius: 40px;
}

div.icon div.lockClosed_base:before {
    content: '';
    position: absolute;
    background: #ddd;
    width: 2px;
    height: 4px;
    left: 9px;
    top: 8px;
}

div.icon div.lockClosed_handle {
    width: 10px;
    height: 7px;
    border: 2px solid #333;
    border-bottom: none;
    -webkit-border-radius: 40px 40px 0 0;
    -moz-border-radius: 40px 40px 0 0;
    border-radius: 40px 40px 0 0;
    position: absolute;
    left: 9px;
    top: 3px;
}

/* Lock Open */
div.icon div.lockOpen_base {
    width: 20px;
    height: 16px;
    background: #333;
    position: absolute;
    left: 2px;
    top: 12px;
}

div.icon div.lockOpen_base:after {
    content: '';
    position: absolute;
    background: #ddd;
    width: 4px;
    height: 4px;
    left: 8px;
    top: 5px;
    -webkit-border-radius: 40px;
    -moz-border-radius: 40px;
    border-radius: 40px;
}

div.icon div.lockOpen_base:before {
    content: '';
    position: absolute;
    background: #ddd;
    width: 2px;
    height: 4px;
    left: 9px;
    top: 8px;
}

div.icon div.lockOpen_handle {
    width: 10px;
    height: 7px;
    border: 2px solid #333;
    border-bottom: none;
    -webkit-border-radius: 40px 40px 0 0;
    -moz-border-radius: 40px 40px 0 0;
    border-radius: 40px 40px 0 0;
    position: absolute;
    left: 17px;
    top: 3px;
}

/* Weight */
div.icon div.weight {
    width: 22px;
    height: 0;
    position: absolute;
    border-style: solid;
    border-width: 0px 5px 15px 5px;
    border-color: transparent transparent #333 transparent;
    top: 14px;
    left: 0;
}

div.icon div.weight:after {
    content: '';
    position: absolute;
    top: -12px;
    left: 4px;
    width: 6px;
    height: 6px;
    border: 4px solid #333;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
}

/* Light Bulb */
div.icon div.bulb_glass {
    width: 22px;
    height: 22px;
    background: #333;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    position: absolute;
    left: 5px;
    top: 1px
}

div.icon div.bulb_glass:after {
    content: '';
    position: absolute;
    width: 8px;
    height: 8px;
    background: #333;
    bottom: -2px;
    left: 7px;
}

div.icon div.bulb_holder {
    width: 8px;
    height: 1px;
    background: #333;
    position: absolute;
    left: 12px;
    bottom: 5px;
}

div.icon div.bulb_holder:after {
    content: '';
    width: 8px;
    height: 1px;
    background: #333;
    position: absolute;
    top: 2px;
    left: 0px;
}

div.icon div.bulb_holder:before {
    content: '';
    width: 4px;
    height: 1px;
    background: #333;
    position: absolute;
    left: 2px;
    top: 4px;
}

/* Camera */
div.icon div.camera_body {
    width: 32px;
    height: 20px;
    background: #333;
    position: absolute;
    top: 7px;
    -webkit-border-radius: 2px;
    -moz-border-radius: 2px;
    border-radius: 2px;
}

div.icon div.camera_body:after {
    width: 4px;
    height: 2px;
    position: absolute;
    content: '';
    background: #333;
    top: -2px;
    left: 5px;
}

div.icon div.camera_body:before {
    content: '';
    position: absolute;
    width: 3px;
    height: 2px;
    background: #ddd;
    right: 3px;
    top: 3px;
}

div.icon div.camera_lens {
    width: 8px;
    height: 8px;
    border: 3px solid #ddd;
    position: absolute;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    top: 10px;
    left: 9px;
}

/* EarBuds */
div.icon div.earbud_left {
    position: absolute;
    width: 7px;
    height: 7px;
    border: 1px solid #333;
    background: #ddd;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    left: 5px;
    top: 3px;
}

div.icon div.earbud_left:after {
    content: '';
    position: absolute;
    width: 3px;
    height: 5px;
    background: #333;
    bottom: -5px;
    left: 2px;
}

div.icon div.earbud_left:before {
    content: '';
    position: absolute;
    width: 1px;
    height: 6px;
    background: #333;
    bottom: -11px;
    left: 3px;
}

div.icon div.earbud_right {
    position: absolute;
    width: 7px;
    height: 7px;
    border: 1px solid #333;
    background: #333;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    right: 5px;
    top: 10px;
}

div.icon div.earbud_right:after {
    content: '';
    position: absolute;
    width: 3px;
    height: 5px;
    background: #333;
    bottom: -5px;
    left: 2px;
}

div.icon div.earbud_right:before {
    content: '';
    position: absolute;
    width: 1px;
    height: 6px;
    background: #333;
    bottom: -11px;
    left: 3px;
}

/* Restricted */
div.icon div.restricted {
    width: 22px;
    height: 22px;
    border: 4px solid #333;
    position: absolute;
    top: 1px;
    left: 1px;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
}

div.icon div.restricted:after {
    content: '';
    position: absolute;
    width: 4px;
    height: 26px;
    background: #333;
    -webkit-transform: rotate(45deg);
    -moz-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    -o-transform: rotate(45deg);
    transform: rotate(45deg);
    left: 10px;
    top: -3px;
}

/* Pin */
div.icon div.pin_middle {
    width: 12px;
    height: 10px;
    background: #333;
    position: absolute;
    top: 8px;
    left: 12px;
    -webkit-transform: rotate(45deg);
    -moz-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    -o-transform: rotate(45deg);
    transform: rotate(45deg);
}

div.icon div.pin_middle:after {
    content: '';
    position: absolute;
    width: 0;
    height: 0;
    border-style: solid;
    border-color: transparent transparent #ddd transparent;
    border-width: 0 2px 8px 0;
    left: 2px;
    top: 0px;
}

div.icon div.pin_middle:before {
    content: '';
    position: absolute;
    width: 12px;
    height: 0;
    bottom: -5px;
    left: -2px;
    border-style: solid;
    border-color: transparent transparent #333 transparent;
    border-width: 0 2px 6px 2px;
}

div.icon div.pin_bottom {
    width: 14px;
    height: 2px;
    background: #333;
    -webkit-transform: rotate(45deg);
    -moz-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    -o-transform: rotate(45deg);
    transform: rotate(45deg);
    position: absolute;
    top: 7px;
    left: 16px;
}

div.icon div.pin_bottom:after {
    content: '';
    position: absolute;
    width: 0;
    height: 0;
    border-style: solid;
    border-color: #333 transparent transparent transparent;
    border-width: 12px 2px 0 2px;
    top: 19px;
    left: 5px;
}

/* Plus */
div.icon div.plus {
    width: 24px;
    height: 4px;
    background: #333;
    position: absolute;
    left: 4px;
    top: 14px;
}

div.icon div.plus:after {
    content: '';
    position: absolute;
    width: 4px;
    height: 24px;
    background: #333;
    left: 10px;
    top: -10px;
}

/* Minus */
div.icon div.minus {
    width: 24px;
    height: 4px;
    background: #333;
    position: absolute;
    left: 4px;
    top: 14px;
}

/* Flask */
div.icon div.flask_body {
    width: 10px;
    height: 2px;
    background: #333;
    position: absolute;
    left: 11px;
    top: 2px;
}

div.icon div.flask_body:after {
    content: '';
    position: absolute;
    width: 6px;
    height: 8px;
    background: #333;
    left: 2px;
    top: 2px;
}

div.icon div.flask_body:before {
    content: '';
    position: absolute;
    width: 6px;
    height: 0;
    border-style: solid;
    border-color: transparent transparent #333 transparent;
    border-width: 0 12px 18px 12px;
    top: 10px;
    left: -10px;
}

div.icon div.flask_liquid {
    width: 10px;
    height: 0;
    border-style: solid;
    border-color: transparent transparent #ddd transparent;
    border-width: 0 7px 10px 7px;
    position: absolute;
    top: 18px;
    left: 4px;
}

div.icon div.flask_liquid:after {
    width: 4px;
    height: 4px;
    background: #333;
    content: '';
    position: absolute;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    top: 4px;
}

div.icon div.flask_liquid:before {
    width: 2px;
    height: 2px;
    background: #333;
    content: '';
    position: absolute;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    top: 2px;
    left: 6px;
}

/* Test Tube */
div.icon div.testtube_body {
    width: 14px;
    height: 2px;
    background: #333;
    position: absolute;
    left: 9px;
    top: 2px;
}

div.icon div.testtube_body:after {
    content: '';
    position: absolute;
    width: 10px;
    height: 26px;
    background: #333;
    left: 2px;
    top: 2px;
    -webkit-border-radius: 0 0 50px 50px;
    -moz-border-radius: 0 0 50px 50px;
    border-radius: 0 0 50px 50px;
}

div.icon div.testtube_body:before {
    content: '';
    position: absolute;
    width: 8px;
    height: 17px;
    background: #ddd;
    left: 3px;
    top: 10px;
    -webkit-border-radius: 0 0 50px 50px;
    -moz-border-radius: 0 0 50px 50px;
    border-radius: 0 0 50px 50px;
    z-index: 2;
}

div.icon div.testtube_bubbles {
    position: absolute;
    width: 5px;
    height: 5px;
    background: #333;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    top: 22px;
    left: 13px;
    z-index: 3;
}

div.icon div.testtube_bubbles:after {
    content: '';
    position: absolute;
    width: 3px;
    height: 3px;
    background: #333;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    bottom: 6px;
    left: 3px;
    z-index: 3;
}

div.icon div.testtube_bubbles:before {
    content: '';
    position: absolute;
    width: 2px;
    height: 2px;
    background: #333;
    -webkit-border-radius: 50px;
    -moz-border-radius: 50px;
    border-radius: 50px;
    bottom: 10px;
    left: 0px;
    z-index: 3;
}

/* DustBin */
div.icon div.dustbin {
    width: 16px;
    height: 20px;
    background: #333;
    position: absolute;
    left: 8px;
    bottom: 3px;
}

div.icon div.dustbin:after {
    content: '';
    position: absolute;
    width: 20px;
    height: 3px;
    background: #333;
    left: -2px;
    top: -4px;
}

div.icon div.dustbin:before {
    height: 3px;
    width: 6px;
    position: absolute;
    top: -6px;
    content: '';
    background: #333;
    left: 5px;
}
</style>
<h1>CSS3 Monochrome Icon Set</h1>
<div class="container">
	
	<!-- ### Down Arrow ### -->
	<div class="icon">
		<div class="downArrow"></div>
	</div>
	
	<!-- ### Up Arrow ### -->
	<div class="icon">
		<div class="upArrow"></div>
	</div>
	
	<!-- ### Left Arrow ### -->
	<div class="icon">
		<div class="leftArrow"></div>
	</div>
	
	<!-- ### Right Arrow ### -->
	<div class="icon">
		<div class="rightArrow"></div>
	</div>
	
	<!-- ### Home ### -->
	<div class="icon">
		<div class="home"></div>
		<div class="chimney"></div>
	</div>
	
	<!-- ### Disc ### -->
	<div class="icon">
		<div class="disc"></div>
	</div>
	
	<!-- ### Heart ### -->
	<div class="icon">
		<div class="heart"></div>
	</div>
	
	<!-- ### Pencil ### -->
	<div class="icon">
		<div class="pencil"></div>
	</div>
	
	<!-- ### Chat Box ### -->
	<div class="icon">
		<div class="chat"></div>
		<div class="lines"></div>
	</div>
	
	<!-- ### Tick ### -->
	<div class="icon">
		<div class="tick"></div>
	</div>
	
	<!-- ### Cross ### -->
	<div class="icon">
		<div class="cross"></div>
	</div>
	
	<!-- ### User ### -->
	<div class="icon">
		<div class="user"></div>
		<div class="shoulder"></div>
	</div>
	
	<!-- ### Search ### -->
	<div class="icon">
		<div class="search"></div>
	</div>
	
	<!-- ### Search with base ### -->
	<div class="icon">
		<div class="searchB"></div>
	</div>
	
	<!-- ### Phone ### -->
	<div class="icon">
		<div class="phone"></div>
	</div>
	
	<!-- ### iPod ### -->
	<div class="icon">
		<div class="ipod"></div>
	</div>
	
	<!-- ### Tab ### -->
	<div class="icon">
		<div class="tab"></div>
	</div>
	
	<!-- ### Graph1 ### -->
	<div class="icon">
		<div class="graph1"></div>
		<div class="bars"></div>
	</div>
	
	<!-- ### Screen ### -->
	<div class="icon">
		<div class="screen"></div>
	</div>
	
	<!-- ### Cloud ### -->
	<div class="icon">
		<div class="cloud"></div>
	</div>
	
	<!-- ### Cloud-Up ### -->
	<div class="icon">
		<div class="cloudUp"></div>
		<div class="cloudUpArrow"></div>
	</div>
	
	<!-- ### Cloud-Down ### -->
	<div class="icon">
		<div class="cloudDown"></div>
		<div class="cloudDownArrow"></div>
	</div>
	
	<!-- ### Page ### -->
	<div class="icon">
		<div class="page"></div>
		<div class="pageLines"></div>
	</div>
	
	<!-- ### RSS ### -->
	<div class="icon">
		<div class="rss"></div>
	</div>
	
	<!-- ### Battery Full ### -->
	<div class="icon">
		<div class="batFull"></div>
	</div>
	
	<!-- ### Battery Medium ### -->
	<div class="icon">
		<div class="batMed"></div>
	</div>
	
	<!-- ### Battery Low ### -->
	<div class="icon">
		<div class="batLow"></div>
	</div>
	
	<!-- ### Battery Empty ### -->
	<div class="icon">
		<div class="batEmpty"></div>
	</div>
	
	<!-- ### Speaker Volume Full ### -->
	<div class="icon">
		<div class="speakerVolF"></div>
	</div>
	
	<!-- ### Speaker Volume Half ### -->
	<div class="icon">
		<div class="speakerVolH"></div>
	</div>
	
	<!-- ### Speaker Volume Mute ### -->
	<div class="icon">
		<div class="speakerVolM"></div>
	</div>
	
	<!-- ### Play ### -->
	<div class="icon">
		<div class="play"></div>
	</div>
	
	<!-- ### Pause ### -->
	<div class="icon">
		<div class="pause"></div>
	</div>
	
	<!-- ### Forward ### -->
	<div class="icon">
		<div class="forward"></div>
	</div>
	
	<!-- ### Next ### -->
	<div class="icon">
		<div class="next"></div>
	</div>
	
	<!-- ### Rewind ### -->
	<div class="icon">
		<div class="rewind"></div>
	</div>
	
	<!-- ### Previous ### -->
	<div class="icon">
		<div class="previous"></div>
	</div>
	
	<!-- ### Stop ### -->
	<div class="icon">
		<div class="stop"></div>
	</div>
	
	<!-- ### Location ### -->
	<div class="icon">
		<div class="location"></div>
	</div>
	
	<!-- ### Clock ### -->
	<div class="icon">
		<div class="clock"></div>
	</div>
	
	<!-- ### Clock Alt ### -->
	<div class="icon">
		<div class="clockAlt"></div>
	</div>
	
	<!-- ### Pointer Right ### -->
	<div class="icon">
		<div class="pointerRight"></div>
	</div>
	
	<!-- ### Pointer Top ### -->
	<div class="icon">
		<div class="pointerTop"></div>
	</div>
	
	<!-- ### Pointer Left ### -->
	<div class="icon">
		<div class="pointerLeft"></div>
	</div>
	
	<!-- ### Pointer Down ### -->
	<div class="icon">
		<div class="pointerDown"></div>
	</div>
	
	<!-- ### Signals ### -->
	<div class="icon">
		<div class="signal1"></div>
		<div class="signal2"></div>
	</div>
	
	<!-- ### Graph2 ### -->
	<div class="icon">
		<div class="base"></div>
		<div class="bars2"></div>
	</div>
	
	<!-- ### Ribbon ### -->
	<div class="icon">
		<div class="ribbon"></div>
	</div>
	
	<!-- ### Video Cam ### -->
	<div class="icon">
		<div class="videoCam"></div>
	</div>
	
	<!-- ### Star ### -->
	<div class="icon">
		<div class="star"></div>
	</div>
	
	<!-- ### HeadPhones ### -->
	<div class="icon">
		<div class="headphones"></div>
	</div>
	
	<!-- ### Capsule ### -->
	<div class="icon">
		<div class="capsule"></div>
	</div>
	
	<!-- ### Microphone ### -->
	<div class="icon">
		<div class="mic"></div>
		<div class="holder"></div>
	</div>
	
	<!-- ### Tower ### -->
	<div class="icon">
		<div class="tower"></div>
		<div class="waves"></div>
	</div>
	
	<!-- ### IceCream ### -->
	<div class="icon">
		<div class="icecream"></div>
	</div>
	
	<!-- ### Golf ### -->
	<div class="icon">
		<div class="golf_stick"></div>
		<div class="golf_ball"></div>
	</div>
	
	<!-- ### PolyBag ### -->
	<div class="icon">
		<div class="polybag"></div>
	</div>
	
	<!-- ### BriefCase ### -->
	<div class="icon">
		<div class="briefcase_handle"></div>
		<div class="briefcase"></div>
	</div>
	
	<!-- ### Roller ### -->
	<div class="icon">
		<div class="roller_brush"></div>
		<div class="roller_handle"></div>
	</div>
	
	<!-- ### Magnet ### -->
	<div class="icon">
		<div class="magnet"></div>
	</div>
	
	<!-- ### Bomb ### -->
	<div class="icon">
		<div class="bomb"></div>
	</div>
	
	<!-- ### BirdHouse ### -->
	<div class="icon">
		<div class="birdhouse"></div>
		<div class="birdhouse_holes"></div>
	</div>
	
	<!-- ### Woofer ### -->
	<div class="icon">
		<div class="woofer"></div>
	</div>	
	
	<!-- ### HandBag ### -->
	<div class="icon">
		<div class="handbag"></div>
	</div>
	
	<!-- ### Bell ### -->
	<div class="icon">
		<div class="belltop"></div>
		<div class="bellbottom"></div>
	</div>
	
	<!-- ### SignBoard ### -->
	<div class="icon">
		<div class="signboard"></div>
		<div class="signboard_arrow"></div>
	</div>
	
	<!-- ### Music Note ### -->
	<div class="icon">
		<div class="musicnote_base"></div>
		<div class="musicnote_left"></div>
		<div class="musicnote_right"></div>
		<div class="musicnote_ovals"></div>
	</div>
	
	<!-- ### Key ### -->
	<div class="icon">
		<div class="key_base"></div>
		<div class="key_squares"></div>
	</div>
	
	<!-- ### Download ### -->
	<div class="icon">
		<div class="download"></div>
	</div>
	
	<!-- ### Upload ### -->
	<div class="icon">
		<div class="upload"></div>
	</div>
	
	<!-- ### Reload ### -->
	<div class="icon">
		<div class="reload"></div>
	</div>
	
	<!-- ### Redo ### -->
	<div class="icon">
		<div class="redo_l"></div>
		<div class="redo_r"></div>
	</div>
	
	
	<!-- ### LoopBack ### -->
	<div class="icon">
		<div class="loopback_l"></div>
		<div class="loopback_r"></div>
	</div>
	
	<!-- ### Target ### -->
	<div class="icon">
		<div class="target"></div>
	</div>
	
	<!-- ### Lock Closed ### -->
	<div class="icon">
		<div class="lockClosed_base"></div>
		<div class="lockClosed_handle"></div>
	</div>
	
	<!-- ### Lock Open ### -->
	<div class="icon">
		<div class="lockOpen_base"></div>
		<div class="lockOpen_handle"></div>
	</div>
	
	<hr />
	<h3 style="border: none; color: #333; margin: 0;">New!</h3>
	<hr />
	
	<!-- ### Weight ### -->
	<div class="icon">
		<div class="weight"></div>
	</div>
	
	<!-- ### Light Bulb ### -->
	<div class="icon">
		<div class="bulb_glass"></div>
		<div class="bulb_holder"></div>
	</div>
	
	<!-- ### Camera ### -->
	<div class="icon">
		<div class="camera_body"></div>
		<div class="camera_lens"></div>
	</div>
	
	<!-- ### EarBuds ### -->
	<div class="icon">
		<div class="earbud_left"></div>
		<div class="earbud_right"></div>
	</div>
	
	<!-- ### Restricted ### -->
	<div class="icon">
		<div class="restricted"></div>
	</div>
	
	<!-- ### Pin ### -->
	<div class="icon">
		<div class="pin_middle"></div>
		<div class="pin_bottom"></div>
	</div>
	
	<!-- ### Plus ### -->
	<div class="icon">
		<div class="plus"></div>
	</div>
	
	<!-- ### Minus ### -->
	<div class="icon">
		<div class="minus"></div>
	</div>
	
	<!-- ### Flask ### -->
	<div class="icon">
		<div class="flask_body"></div>
		<div class="flask_liquid"></div>
	</div>
	
	<!-- ### Test Tube ### -->
	<div class="icon">
		<div class="testtube_body"></div>
		<div class="testtube_bubbles"></div>
	</div>
	
	<!-- ### DustBin ### -->
	<div class="icon">
		<div class="dustbin"></div>
	</div>
	
	<!-- END -->
</div>
