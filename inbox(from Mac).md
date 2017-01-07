
w to jump to a screen location using a mouse click with iTerm2? | alvinalexander.com](http://alvinalexander.com/macos/iterm2-how-to-jump-to-location-mouse-click)


["검사님, 그걸 왜 저한테 물어보세요" 상상 뛰어넘는 최순실 모르쇠](http://v.media.daum.net/v/20170107044215962?d=y)
[머리 숙인 김정은 쇼일까? 진심일까?](http://v.media.daum.net/v/20170107030152433?d=y)
[[단독] 최순실 "덴마크에 연락해 정유라 상황 알아봐달라"](http://v.media.daum.net/v/20170107093102877?d=y)
[[Why] 폭행·욕설·성추행까지.. 하늘이 '지옥' 된 여자 승무원들](http://v.media.daum.net/v/20170107030606528?d=y)
[靑 "윤전추는 트레이너가 아니라 비서"..'요가설' 일축](http://v.media.daum.net/v/20170107110355858?d=y)
[정유라 체포한 덴마크 경찰, 일베에 당하다](http://v.media.daum.net/v/20170106164108900?d=y)
[[단독]"송수근 아는게 많아 등돌릴 우려.. 차관으로 승진시켜야"](http://v.media.daum.net/v/20170107030106404?d=y)
[김종인에 "노인 죽을 날.." 문자 테러](http://v.media.daum.net/v/20170107031107630?d=y)
[[단독]CCTV·휴대폰 기록 삭제..김기춘, 역시 '법꾸라지'](http://v.media.daum.net/v/20170107060103318?d=y)
[정유라 체포한 덴마크 경찰, 일베에 당하다 | Daum 뉴스](http://v.media.daum.net/v/20170106164108900?d=y)
[대통령이 추천한 재판관들, 윤전추에 질문 안 해](http://v.media.daum.net/v/20170107044213960?d=y)
[[Why] 허름한 행색의 자칭 투자 천재는 왜 '가난한 여대생'만 노렸나](http://v.media.daum.net/v/20170107030503517?d=y)

‘100억 부당수임’ 최유정 변호사 징역6년
앱열기 시험함
앱열기 시험함
앱열기 시험함
[Title](https://m.youtube.com/watch?list=PL-osiE80TeTvGhHkpvfmKWOiIPF8UVy6c&params=EAEYATgBSAFYCmILMGxpWGVvQURVNkFoCA%253D%253D&v=HVMOBKRNEbc&mode=NORMAL)

---
[Subnetting Explained Step by Step & Subnetting Chart]
(https://www.youtube.com/watch?v=Gt0RQX3QCO8)
Clicking [here][section-preview] will lead you to the **Preview** section.

---

Sqlite3로 입력하여 변경하기

[How to remove an icon from launchpad that does not appear in the Finder? - Ask Different](http://apple.stackexchange.com/questions/144756/how-to-remove-an-icon-from-launchpad-that-does-not-appear-in-the-finder)
# 
sqlite3 $(sudo find /private/var/folders -name com.apple.dock.launchpad)/db/db "DELETE FROM apps WHERE title='APP_NAME_CASE_SENSITIVE';" && killall Dock
shareimprove this answer
edited Dec 13 '15 at 12:27
 #  	 	
Gives error Error: unable to open database "/private/var/folders/bd/q50jcx3s0q9dhskwrwb308hh0000gp/0/co‌​m.apple.dock.launchp‌​ad": unable to open database file – Boggartfly Nov 23 '16 at 5:12
add a comment
# 
또 다른 ㅇSQL의 방식
[How to Remove Stubborn Apps from Launchpad - YouTube](https://www.youtube.com/watch?v=j6klO3TFwDw)
sqlite3 ~/Library/Application\ Support/Dock/*.db "DELETE from apps WHERE title='APPNAME';" && killall Dock
#
---
론치패드를 원상복귀하는 법, 연구 이것을 다시 편집한 것은?? 터미널의 일반명령어 연구
defaults write com.apple.dock ResetLaunchPad -bool true; killall Dock 
[How To Reset Your LaunchPad In OS X Yosemite - YouTube](https://www.youtube.com/watch?v=QGOIrA7FbEM)
#
론치패드를 화면에 보이는 가로세로 수량 조절법 터미널에서 실행하는 3번의 리턴입력
#
[How To Change Launchpad Icon Size in OS X - YouTube](https://www.youtube.com/watch?v=_5AZs6_Bb5k)
defaults write com.apple.dock springboard-columns -int 4
defaults write com.apple.dock springboard-rows -int 3
killall Dock
#
defaults write com.apple.dock ResetLaunchPad -bool TRUE
killall Dock

**// 한화면에 자동정렬하는 기능임**
#
defaults delete com.apple.dock springboard-columns 
defaults delete com.apple.dock springboard-rows
killall Dock
// 원상복귀 명령임
#

#
대안의 먼저본것
defaults write com.apple.doc springboard-rows -int 10
defaults write com.apple.doc springboard-columns -int 10
killall Dock
[Resize and Get More Icons in Launchpad | Mac OS X El Capitan - YouTube](https://youtu.be/cg3gEEogu74?t=1m28s)
#






