---
layout: default
title: Home
description: null
author: null
show_tile: false
---

<!-- INTRO -->
<div id="main" class="alt">
    <div class="inner">
        <section class="flexcontainer row uniform">
            <div class="6u 12u$(small)">
                <h1 style="margin-bottom: 0;">Your live stream.<br/>Our specialist production crew.</h1>
                <p style="margin-top:2em;">Crossfade is a UK production company that specialises in simulcasting live music to Facebook and YouTube.</p>
            </div>
            <div class="6u 12u$(small)" style="text-align: right">
                <svg style="height:50vh" xmlns="http://www.w3.org/2000/svg" width="480" height="1040" viewBox="0 0 480 1040">
                  <g id="Group_19" data-name="Group 19" transform="translate(-1201 -268)">
                    <g id="phone_outline" data-name="phone outline" transform="translate(1201 268)" fill="none">
                      <path d="M48,0H432a48,48,0,0,1,48,48V992a48,48,0,0,1-48,48H48A48,48,0,0,1,0,992V48A48,48,0,0,1,48,0Z" stroke="none"/>
                      <path d="M 48 5 C 42.19281005859375 5 36.56201171875 6.13623046875 31.26400756835938 8.3770751953125 C 26.14413452148438 10.542724609375 21.54507446289062 13.6436767578125 17.59439086914062 17.59442138671875 C 13.64373779296875 21.5450439453125 10.54254150390625 26.144287109375 8.3770751953125 31.26397705078125 C 6.136260986328125 36.56201171875 5 42.19281005859375 5 48 L 5 992 C 5 997.8071899414062 6.136260986328125 1003.43798828125 8.3770751953125 1008.736022949219 C 10.54254150390625 1013.855712890625 13.64373779296875 1018.454956054688 17.59439086914062 1022.405578613281 C 21.54507446289062 1026.356323242188 26.14413452148438 1029.457275390625 31.26400756835938 1031.622924804688 C 36.56201171875 1033.86376953125 42.19281005859375 1035 48 1035 L 432 1035 C 437.8071899414062 1035 443.43798828125 1033.86376953125 448.7359924316406 1031.622924804688 C 453.8557434082031 1029.457275390625 458.4549255371094 1026.356323242188 462.4056091308594 1022.405578613281 C 466.3562622070312 1018.454956054688 469.4573364257812 1013.855712890625 471.6229248046875 1008.736022949219 C 473.8637390136719 1003.43798828125 475 997.8071899414062 475 992 L 475 48 C 475 42.19281005859375 473.8637390136719 36.56201171875 471.6229248046875 31.26397705078125 C 469.4573364257812 26.144287109375 466.3562622070312 21.5450439453125 462.4056091308594 17.59442138671875 C 458.4549255371094 13.6436767578125 453.8557434082031 10.542724609375 448.7359924316406 8.3770751953125 C 443.43798828125 6.13623046875 437.8071899414062 5 432 5 L 48 5 M 48 0 L 432 0 C 458.5096130371094 0 480 21.49041748046875 480 48 L 480 992 C 480 1018.509582519531 458.5096130371094 1040 432 1040 L 48 1040 C 21.49026489257812 1040 0 1018.509582519531 0 992 L 0 48 C 0 21.49041748046875 21.49026489257812 0 48 0 Z" stroke="none" fill="#fff"/>
                    </g>
                    <g id="Group_17" data-name="Group 17">
                      <g id="Group_16" data-name="Group 16">
                        <rect id="Rectangle_7" data-name="Rectangle 7" width="82" height="47" rx="4" transform="translate(1231 300)" fill="#f85b54"/>
                        <text id="LIVE" transform="translate(1240 331)" fill="#fff" font-size="27" font-family="Helvetica-Bold, Helvetica" font-weight="700"><tspan x="0" y="0">LIVE</tspan></text>
                      </g>
                      <g id="Group_15" data-name="Group 15">
                        <rect id="Rectangle_7-2" data-name="Rectangle 7" width="101" height="47" rx="4" transform="translate(1324 300)" fill="rgba(0,0,0,0.3)"/>
                        <text id="_203" data-name="203" transform="translate(1371 331)" fill="#fff" font-size="27" font-family="Helvetica-Bold, Helvetica" font-weight="700"><tspan x="0" y="0" id="ticker">203</tspan></text>
                        <g id="Group_9" data-name="Group 9" transform="translate(1333.402 313.946)">
                          <path id="Path_1" data-name="Path 1" d="M175.179,170.668a4.512,4.512,0,1,0,4.512,4.512A4.516,4.516,0,0,0,175.179,170.668Z" transform="translate(-159.738 -164.953)" fill="#fff"/>
                          <path id="Path_2" data-name="Path 2" d="M15.441,74.667A16.6,16.6,0,0,0,0,85.2a16.588,16.588,0,0,0,30.883,0A16.6,16.6,0,0,0,15.441,74.667Zm0,17.547A7.019,7.019,0,1,1,22.46,85.2,7.021,7.021,0,0,1,15.441,92.214Z" transform="translate(0 -74.667)" fill="#fff"/>
                        </g>
                      </g>
                    </g>
                  </g>
                </svg>
            </div>
        </section>
    </div>
</div>

<script>
    function ticker() {
        var tickerCount = 203;
        console.log(tickerCount);

        setInterval(function() {
            if (Math.random() < 0.7) {
                document.getElementById("ticker").value = tickerCount + Math.round(Math.random()*50)
            } 
            else {
                document.getElementById("ticker").innerHTML = tickerCount - Math.round(Math.random()*50)
            }}
        , 1230);
    }
</script>