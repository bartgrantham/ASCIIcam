# ASCIICam

## What is it?

Lean back....

```
'''''''''''!:,==|"^:^"^=?y4'''''~,^=*:=!^;:;".~~,''''''/3f=,,~::=::(!*]?**=?l*jc
''''''''''..!:v}**!;>-t3a''''''.;::!!=!!=!::::::^.'''''''*43y"^.-"^::;!!!=**1j1?
''''''''''!:=",'':=;!?4''''''''.|";!};!:;!;=:",~'''''.'''''nk&*,',.~"":=:![*?*?t
'''''''''':.==.,."!??*''''''^'''''',~""-~"'~~,''''''''~''''':gs1:'.^~:^=![**>>j?
''''''''':=^^:,,.=!=t-'''''',~~!!;=*|":::::::"~-!===~='''''''[tl*.,--::=*[1jl??v
''''''''';:!:=|""!=j}.'.>l*!*yv??>===::=:::":::![=!>?>j!!>}~'=1ft^,,~^::!]!/]t}1
''''''''!:".:~~,,(]!",:=:=:!===((====:^;"^::"^^;;:;!=:==::;!|!tf?'''''''(/([>>*>
''''''''!::'''''':!:=.:^:*1t3fq2kf1}[;::^::^|:!(}*yyy?>?*==:::ln?''''''''''>?*>1
'''''''?}|~::]="::}^('=}?nv=|88d2*???>:,'''';}}?ytlSSn!y&y1=:.y>1'''''''''''1vy?
'''''',":~~''''''''=.':t?::=t3oqs4gyv="''''''=>ooyDSSZj?yt>*;,tn''''''''''''"?y3
''''''-;==},~:;!*!','''~:!=!;=[*?*!|",'''''''.;=*?t>>!*!(::,|'?>'''''''''',=c?:o
''''':1]:!=!*[!;::~,'''',~"::==:;=:~.''''''''''~:;:::;^~''''''.!=11=;.=:;|l'''".
''''':(':[:*^:/*>l;''''',:"""|:":::,''''''''''''":",,,''''''''']?!?1?1]*|:^;^:~!
'''':=/./4y*?=!*}!,'''',-~~~,;!**''''.'''''.~,''''===^|~'''''''.',|=*=":;>}*tyf3
''''=!!=!'''''''''','.~"^:::!=]*/*j1*=:"~","*>j}!!;=!]="|~~~.,.~=1*?tttgco??v?>1
'''=,*:=l1*?>j3}=~.~.,"^::/l?>t??>?yl>j!::;*ty??*=}>**>*:"""~".='::=1to?1*l??1=:
'''j!^=1:===!>=||~":"""::1?>?>cy1?]vntll>?yt???1l?1}y?>t}^^"""~::1j1}>?l/:;:;|;=
''j*=[?Z4t?y?y>*==^--^:"=3[!>*(**=/*===|:|^:"^:(=}11111/c;"~^|"'.,,::==:=~^:====
''=!:}f&44gsgVt??*c-":(::>!1!}0S~j'..^'''"'''~~,-,"q]j;[?:"^=:::;=!]}*/!!]!=!?![
'!![(}Fgy3s3tn?t1?f>"!!:^=>!:?Tbd@23fy333c3oo42@@@Pjt==*!^":!=!}?[=!***?*j*1]?t?
'*}!tcVZVF$a0??>1oek!!;=!=?!j=*@D@ty??3ncgoc?t3VSDs>=]=1:";=*.'?333334gctc??>tv?
[1>1[DSZbZPZ$!'^:!:*>?[*[:c1!=!>ajfo*}?j???}=>na&y}=!=>j"*1?:'~=',='''''!''''!yc
>};?cZt'''.,,:=!3lyt>fv}*;1}*==!}?3*}:=~=^:"^=4y?]==:?=->]?!""::/",,,....,::"~.,
''''''"=3t[j1y3clntt>?>y?t==l==/(!=!==!*!*!!==/!;!:=?;"}=4>~"::;=:,,.~,"..,.~~""
```

See it live at [http://bartgrantham.github.io/ASCIIcam/](http://bartgrantham.github.io/ASCIIcam/)

**This was a quick hack.**  The code will not be winning any awards for clarity.

To use it yourself you'll have to serve it from a webpage.  Poor man's webserver:
```
python -m SimpleHTTPServer
```

## TODO

* Mirror image
* Inverse text
* FPS
* Grid square intensity should be the average of the square, not the upper-left pixel
* Color
* Export to ANSI-256 color codes, or HTML
* Create grid of glyphs and clone/xor webcam squares against to determine best match
* Edge detect and weight edge-detected glyphs
* User-provided charset/fontface
* User-controller brighness/contrast
* Automatic gain control
* Gamma curves to expand dynamic range to maximize character usage

