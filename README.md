if os.date('%Y%m%d') > '20200627' then
gg.alert('⚠️ Please Update Script!\n__________________________________________\n\n', '⛔ EXIT 🔴')
print('⚠️ Please Update Script!\n__________________________________________\n\n')
os.exit()
end
if gg.isPackageInstalled("sstool.only.com.sstool") then
gg.toast("️⚠️ Dangerous software installed! Remove it! ⚠️")
print("⚠️ Dangerous software installed! Remove it! ⚠️")
os.exit()
end
if gg.isPackageInstalled("io.neoterm") then
gg.toast("️⚠️ Dangerous software installed! Remove it! ⚠️")
print("⚠️ Dangerous software installed! Remove it! ⚠️")
os.exit()
end
if gg.isPackageInstalled("com.sstool.only.sstool") then
gg.toast("️⚠️ Dangerous software installed! Remove it! ⚠️")
print("⚠️ Dangerous software installed! Remove it! ⚠️")
os.exit()
end
function startscript()
gg.setVisible(false)
BP = gg.alert(' 🔹   🇰🇼  سـكـربـت هـــدام  🇰🇼   🔹\n  🔹       Secrept: HDAM       🔹\n  🔹     Phone: 90029245     🔹\n 🔹    Telegram: bu_athbi      🔹',
'🔹بـــدء🔹') 
if BP == 1 then HOME() end
end
HOME=1
function HOME()
FF = gg.choice({  
   '✅ حمايه اللوبي سيرفر (1)✅\n',--AntibanLobby
   '✅ حمايه اللوبي سيرفر (2)✅\n',--AntibanLobby
   '🔶 قائمة نقرة واحدة ♦️\n',--One Click Menu
   '👁️ قائمه الولهاك و الالوان 📚\n️',--Wallhack/Colors Menu
   '🎯 قائمة الأسلحة ➿🔰\n',--Weapon Menu
   '🏃 قائمة السرعة 🌀\n',--Speed Menu
   '➿🔰 قائمة النباتات 🌿\n🗃 قائمة الوظائف الأخرى 🗂\n️️',--Vegetation Menu Other Function Menu
   '🔅 ترسيت سـريع 🔅\n',--Fix 10 min DataOff
   '⛔ خروج 🔴'--exit
},nil, ' 🔹   🇰🇼  سـكـربـت هـــدام  🇰🇼   🔹\n  🔹       Secrept: HDAM       🔹\n  🔹     Phone: 90029245     🔹\n 🔹    Telegram: bu_athbi      🔹')
if FF == 1 then AntibanLobbyP1() end
if FF == 2 then AntibanLobbyP2() end
if FF == 3 then OneClickMenu() end
if FF == 4 then WallhackColors() end
if FF == 5 then WeaponMenu() end
if FF == 6 then SpeedMenu() end
if FF == 7 then VegetationOtherMenu() end
if FF == 8 then minDataOff() end
if FF == 9 then exit() end
HOMEDM=-1
end
function AntibanLobbyP1()
gg.clearResults()
gg.setRanges(4)
gg.searchNumber("67109377", 4, false, 536870912, 0, -1)
gg.refineNumber("67109377", 4, false, 536870912, 0, -1)
if gg.getResultCount() == 0 then
gg.alert("The first step failed, please try again!")
else
local searchCount = gg.getResultCount()
local searchResults = gg.getResults(searchCount)
for i, v in ipairs(searchResults) do
  v.freeze = true
  v.flags = 4
  v.value = 0
end
gg.addListItems(searchResults)
gg.clearResults()
gg.setRanges(4)
gg.searchNumber("67109633", 4, false, 536870912, 0, -1)
gg.refineNumber("67109633", 4, false, 536870912, 0, -1)
if gg.getResultCount() == 0 then
gg.alert("The second step failed, please try again!")
else
local searchCount = gg.getResultCount()
local searchResults = gg.getResults(searchCount)
for i, v in ipairs(searchResults) do
  v.freeze = true
  v.flags = 4
  v.value = 0
end
gg.addListItems(searchResults)
gg.clearResults()
gg.alert("https://t.me/HDAM_Channel")
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.setVisible(false)
gg.searchNumber("67109633", gg.TYPE_DWORD)
gg.setVisible(false)
gg.setVisible(false)
gg.getResults(100000)
gg.setVisible(false)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.setVisible(false)
gg.searchNumber("67109633", gg.TYPE_DWORD)
gg.isVisible(false)
gg.getResults(50000)
gg.setVisible(false)
gg.editAll("0", gg.TYPE_DWORD)
gg.setVisible(false)
gg.clearResults() 
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("67109377", gg.TYPE_DWORD)
gg.setVisible(false)
gg.getResults(100000)
gg.setVisible(false)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.alert("Waiting...")
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.setVisible(false)
gg.searchNumber("1,130,852,172;1,852,139,884", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.setVisible(false)
gg.getResults(100000)
gg.setVisible(false)
gg.editAll("0", gg.TYPE_DWORD)
gg.setVisible(false)
gg.getResults(100000)
gg.setVisible(false)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
    gg.setRanges(4)
    gg.setVisible(false)
    gg.searchNumber("16,224;16,384", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.setVisible(false)
    gg.searchNumber("16224", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.isVisible(false)
gg.getResults(50000)
gg.setVisible(false)
gg.editAll("0", gg.TYPE_DWORD)
gg.setVisible(false)
gg.clearResults() 
    gg.clearResults()
    gg.setRanges(4)
    gg.setVisible(false)
    gg.searchNumber("16384;67,177,356", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.setVisible(false)
    gg.searchNumber("67,177,356", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.isVisible(false)
gg.getResults(50000)
gg.setVisible(false)
gg.editAll("0", gg.TYPE_DWORD)
gg.setVisible(false)
gg.clearResults() 
    gg.clearResults()
    gg.setRanges(4)
    gg.setVisible(false)
    gg.searchNumber("37,497;32,768:61", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.setVisible(false)
    gg.searchNumber("37,497", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
   gg.isVisible(false)
gg.getResults(50000)
gg.setVisible(false)
gg.editAll("0", gg.TYPE_DWORD)
gg.setVisible(false)
gg.clearResults() 
    gg.clearResults()
    gg.setRanges(4)
    gg.setVisible(false)
    gg.searchNumber("37,497;16384:61", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("37497", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.isVisible(false)
gg.getResults(50000)
gg.setVisible(false)
gg.editAll("0", gg.TYPE_DWORD)
gg.setVisible(false)
gg.clearResults() 
    gg.clearResults()
    gg.setRanges(4)
    gg.searchNumber("15,968;262,144:17", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("15,968", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.isVisible(false)
gg.getResults(50000)
gg.setVisible(false)
gg.editAll("0", gg.TYPE_DWORD)
gg.setVisible(false)
gg.clearResults() 
    gg.clearResults()
    gg.setRanges(4)
    gg.searchNumber("65,536;458,752;393,216:25", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("458,752;393,216", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.isVisible(false)
gg.getResults(50000)
gg.setVisible(false)
gg.editAll("0", gg.TYPE_DWORD)
gg.setVisible(false)
gg.clearResults() 
    gg.clearResults()
    gg.setRanges(4)
    gg.searchNumber("0;0;132098:9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("132098", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.isVisible(false)
gg.getResults(50000)
gg.setVisible(false)
gg.editAll("0", gg.TYPE_DWORD)
gg.setVisible(false)
gg.clearResults() 
    gg.clearResults()
    gg.setRanges(4)
    gg.searchNumber("12547", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("12547", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
   gg.isVisible(false)
gg.getResults(50000)
gg.setVisible(false)
gg.editAll("0", gg.TYPE_DWORD)
gg.setVisible(false)
gg.clearResults() 
    gg.clearResults()
    gg.setRanges(4)
    gg.searchNumber("16777216;67108864;65536:100", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("16777216;67108864", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.isVisible(false)
gg.getResults(50000)
gg.setVisible(false)
gg.editAll("0", gg.TYPE_DWORD)
gg.setVisible(false)
gg.clearResults() 
    gg.clearResults()
    gg.setRanges(16384)
    gg.searchNumber("1,179,403,647;65,793;2,621,443;2,097,204:41", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("1,179,403,647;65,793;2,621,443;2,097,204", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.isVisible(false)
gg.getResults(50000)
gg.setVisible(false)
gg.editAll("-1", gg.TYPE_DWORD)
gg.setVisible(false)
gg.clearResults() 
    gg.clearResults()
    gg.setRanges(16384)
    gg.searchNumber("16384;32768", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("16384;32768", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.isVisible(false)
gg.getResults(50000)
gg.setVisible(false)
gg.editAll("-1", gg.TYPE_DWORD)
gg.setVisible(false)
gg.clearResults() 
gg.clearResults()
gg.toast("Bypass Activated")
end
end
end
function AntibanLobbyP2()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("67109633", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("67109633", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("67109377;12547::100", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("12547", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
jg = gg.getResults(100)
sl = gg.getResultCount()
if 100 < sl then
sl = 100
end
do
do
for _FORV_3_ = 1, sl do
dzy = jg[_FORV_3_].address
gg.addListItems({
 [1] = {
 address = dzy,
 flags = gg.TYPE_DWORD,
 freeze = true,
 value = 0
 }
})
end
end
end
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("0;0~20;131586::9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("131586", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
jg = gg.getResults(100)
sl = gg.getResultCount()
if 100 < sl then
sl = 100
end
do
do
for _FORV_3_ = 1, sl do
dzy = jg[_FORV_3_].address
gg.addListItems({
 [1] = {
 address = dzy,
 flags = gg.TYPE_DWORD,
 freeze = true,
 value = 0
 }
})
end
end
end
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("67109377;12547::100", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("12547", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
jg = gg.getResults(100)
sl = gg.getResultCount()
if 100 < sl then
sl = 100
end
do
do
for _FORV_3_ = 1, sl do
dzy = jg[_FORV_3_].address
gg.addListItems({
 [1] = {
 address = dzy,
 flags = gg.TYPE_DWORD,
 freeze = true,
 value = 0
 }
})
end
end
end
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("0;0~20;131586::9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("131586", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
jg = gg.getResults(100)
sl = gg.getResultCount()
if 100 < sl then
sl = 100
end
do
do
for _FORV_3_ = 1, sl do
dzy = jg[_FORV_3_].address
gg.addListItems({
 [1] = {
 address = dzy,
 flags = gg.TYPE_DWORD,
 freeze = true,
 value = 0
 }
})
end
end
end
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("67109377;12547::100", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("12547", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
jg = gg.getResults(100)
sl = gg.getResultCount()
if 100 < sl then
sl = 100
end
do
do
for _FORV_3_ = 1, sl do
dzy = jg[_FORV_3_].address
gg.addListItems({
 [1] = {
 address = dzy,
 flags = gg.TYPE_DWORD,
 freeze = true,
 value = 0
 }
})
end
end
end
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("0;0~20;131586::9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("131586", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
jg = gg.getResults(100)
sl = gg.getResultCount()
if 100 < sl then
sl = 100
end
do
do
for _FORV_3_ = 1, sl do
dzy = jg[_FORV_3_].address
gg.addListItems({
 [1] = {
 address = dzy,
 flags = gg.TYPE_DWORD,
 freeze = true,
 value = 0
 }
})
end
end
end
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("67109377;12547::100", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("12547", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
jg = gg.getResults(100)
sl = gg.getResultCount()
if 100 < sl then
sl = 100
end
do
do
for _FORV_3_ = 1, sl do
dzy = jg[_FORV_3_].address
gg.addListItems({
 [1] = {
 address = dzy,
 flags = gg.TYPE_DWORD,
 freeze = true,
 value = 0
 }
})
end
end
end
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("0;0~20;131586::9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("131586", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
jg = gg.getResults(100)
sl = gg.getResultCount()
if 100 < sl then
sl = 100
end
do
do
for _FORV_3_ = 1, sl do
dzy = jg[_FORV_3_].address
gg.addListItems({
 [1] = {
 address = dzy,
 flags = gg.TYPE_DWORD,
 freeze = true,
 value = 0
 }
})
end
end
gg.alert("Antiban Activated")
end
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("67109377", gg.TYPE_DWORD)
gg.getResults(50000)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
end
function minDataOff()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("1.1754945e-37", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("9CC", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100000)
gg.editAll("0", gg.TYPE_FLOAT)
gg.sleep(5000)
gg.getResults(100000)
gg.editAll("1.1754945e-37", gg.TYPE_FLOAT)
gg.clearResults()
end
function OneClickMenu() 
FF = gg.choice({
   '➿🔰 آمنة بنقرة واحدة\n             (قـيــم)\n',--OneClickSafe
   '➿🔰 نقرة واحدة وحشية\n             (قـيــم)\n',--OneClickBrutal
   '🔙 عودة'--BACK
},nil, '')
if FF == 1 then OneClickSafe() end
if FF == 2 then OneClickBrutal() end
if FF == 3 then HOME() end
HOMEDM=-1
end
function LobbyDFone()
WideViewV2()
MicroAimbot()
LessRecoilV2()
NoGrassLobby()
NoFogLobby()
ColorMenu()
end
function DF1gameoneclick()
WallhackColors()
HardHeadshot()
AntiShake()
SmailCrosshair()
Zoom15X()
SpeedFallParachute()
end
function DF2gameoneclick()
skycolormenupro()
MircoSpeedON()
end
function OneClickSafe()
skycolormenupro()
MicroAimbot()
LessRecoilV2()
NoFogGame()
NoGrassGame()
MircoHeadshot()
Zoom8X()
IpadView()
end
function OneClickBrutal()
UltraAimbot()
skycolormenupro()
NoRecoilV2()
NoFogGame()
NoGrassGame()
HardHeadshot()
SpeedFallParachute()
MircoSpeedON()
AntiShake()
Zoom15X()
SmailCrosshair()
WideView()
end

function WeaponMenu()
SSQ = gg.multiChoice({
   '➿🔰 قـائـمـه الاسـلـحـه\n             (لـوبي/قـيــم)',--RecoilMenu
   '➿🔰🔸 عدم اهتزاز السلاح\n             (قـيــم)',--AntiShake
   '➿🔰🔸 تكبـير النـيشـان\n             (قـيــم)',--SmailCrosshair
   '➿🔰🔸 ايمبوت خفيف\n             (لـوبي/قـيــم)',--MicroAimbot
   '➿🔰🔹 ايم بوت قوي\n             (قـيــم)',--UltraAimbot   
   '➿🔰 قائمه الـزوم\n             (قـيــم)',--ZoomMenu   
   '➿🔰 قائمه الهيدشوت\n             (قـيــم)',--HeadshotMenu
   '➿🔰 قـائـمـه الـمـجــك\n             (لـوبي/قـيــم)',--MagicBulletMenu  
   '➿🔰 قائمه الست سكوب\n             (قـيــم)',--ScopeMenu   
   '➿🔰🔸 زحـف سـريع\n             (قـيــم)',--SpeedKnock     
   '➿🔰 دمـــج بلس\n             (قـيــم)',--MoreDamage
   '🔙 عودة'--BACK
},nil,'')
if SSQ == nil then else
if SSQ[1] == true then RecoilMenu() end
if SSQ[2] == true then AntiShake() end
if SSQ[3] == true then SmailCrosshair() end
if SSQ[4] == true then MicroAimbot() end
if SSQ[5] == true then UltraAimbot() end
if SSQ[6] == true then ZoomMenu() end
if SSQ[7] == true then HeadshotMenu() end
if SSQ[8] == true then MagicBulletMenu() end
if SSQ[9] == true then ScopeMenu() end
if SSQ[10] == true then SpeedKnock() end 
if SSQ[11] == true then MoreDamage() end 
if SSQ[12] == true then HOME() end
end
end
function MicroAimbot()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("6.1630853e-33;-1.0767317e28::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1.0767317e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
end
function UltraAimbot()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("2046820354;-336587221:9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2046820354", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("2046820353", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("2015175168", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(6)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
end
function RecoilMenu()
SSTP = gg.multiChoice({
   '➿🔰🔸 ثبات سلاحv1\n             (لـوبي/قـيــم)',--LessRecoilv1
   '➿🔰🔸 ثبات سلاحv2\n             (لـوبي/قـيــم)',--LessRecoilv2
   '➿🔰🔹 الغاء ثبات سلاحv1\n             (لـوبي/قـيــم)',--NoRecoilv1
   '➿🔰🔹 الغاء ثبات سلاحv2\n             (لـوبي/قـيــم)',--NoRecoilv2
   '🔙 عودة'--BACK
},nil,'')
if SSTP == nil then else
if SSTP[1] == true then LessRecoilV1() end
if SSTP[2] == true then LessRecoilV2() end
if SSTP[3] == true then NoRecoilV1() end
if SSTP[4] == true then NoRecoilV2() end
if SSTP[5] == true then WeaponMenu() end
end
end
function LessRecoilV1()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-2.2673448e24;-1.36203639e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-1.36203639e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
end
function LessRecoilV2()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1.3039565e21;-3.6907917e20;-1.3620364e28;-3.6893509e20:13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1.3620364e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-5.8454592e27;-5.7318526e27;-1.3620364e28:9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1.3620364e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
end
function NoRecoilV2()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-2.2673448e24;-1.36203639e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-1.36203639e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-6.1549454e27;1.8638966e-20;-1.1144502e28;0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-2.8111605e28;-3.7444097e28;-1.1144502e28;128.0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
end
function SitScope()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("h0AF872B922214CB9EC343A38", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("h22214CB9", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("h00009643", gg.TYPE_BYTE)
gg.clearResults()
end
function AntiShake()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-6.1549454e27;1.8638966e-20;-1.1144502e28;0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-2.8111605e28;-3.7444097e28;-1.1144502e28;128.0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
end
function SmailCrosshair()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1.2382424e28;-1.4239333e28;-1.1144502e28;-1.8331474e27;-7.1608877e24::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("7.5", gg.TYPE_FLOAT)
gg.clearResults()
end
function SpeedKnock()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0;7.0064923e-45;1;100;1;2,500,000,000.0;0.10000000149;88", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("1.7", gg.TYPE_FLOAT)
gg.clearResults()
end
function MoreDamage()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("16000~99999;3D;0.1;1D::40", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("16000~99999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("500000", gg.TYPE_FLOAT)
gg.clearResults()
end
function HeadshotMenu()
SSTL = gg.multiChoice({
   '➿🔰🔸 هيـدشـوت قــــوي\n             (قـيــم)',--MircoHeadshot
   '➿🔰🔹 قـائـمـه الـمـجــك\n             (قـيــم)',--HardHeadshot
   '➿🔰🔸 هيدشوت 50%\n             (قـيــم)',--Headshot50
   '➿🔰🔹 هيدشوت 70%\n             (قـيــم)',--Headshot70
   '➿🔰🔹 هيدشوت 90%\n             (قـيــم)',--Headshot90
   '🔙 عودة'--BACK
},nil,'')
if SSTL == nil then else
if SSTL[1] == true then MircoHeadshot() end
if SSTL[2] == true then HardHeadshot() end
if SSTL[3] == true then Headshot50() end
if SSTL[4] == true then Headshot70() end
if SSTL[5] == true then Headshot90() end
if SSTL[6] == true then WeaponMenu() end
end
end
function MircoHeadshot()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-88.66608428955;26:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("26", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("-280", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-88.73961639404;28:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("-380", gg.TYPE_FLOAT)
gg.clearResults()
end
function HardHeadshot()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-88.66608428955;26:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("26", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("-460", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-88.73961639404;28:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("-560", gg.TYPE_FLOAT)
gg.clearResults()
end
function Headshot50()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("150", gg.TYPE_FLOAT)
gg.clearResults()
end
function Headshot70()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("200", gg.TYPE_FLOAT)
gg.clearResults()
end
function Headshot90()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("225", gg.TYPE_FLOAT)
gg.clearResults()
end
function MagicBulletMenu()
SSJJ = gg.multiChoice({
   '➿🔰 مــجــك خفـيف\n             (lobby/game)',--WeakMagicBullet
   '➿🔰 مــجــك قــــوي\n             (lobby/game)',--HardMagicBullet
   '➿🔰 مــجــك قــــوي v2\n             (lobby/game)',--HardMagicBulletV2
   '🔙 عودة'--BACK
},nil,'')
if SSJJ == nil then else
if SSJJ[1] == true then WeakMagicBullet() end
if SSJJ[2] == true then HardMagicBullet() end
if SSJJ[3] == true then HardMagicBulletV2() end
if SSJJ[4] == true then WeaponMenu() end
end
end
function WeakMagicBullet()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("69.5;35;33", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("80;70;115", gg.TYPE_FLOAT)
gg.clearResults()
end
function HardMagicBullet()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("69.5;35;33", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("160;140;230", gg.TYPE_FLOAT)
gg.clearResults()
end
function HardMagicBulletV2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.20161819458;23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("200", gg.TYPE_FLOAT)
gg.clearResults()
end
function ZoomMenu()
SSU = gg.multiChoice({
   '➿🔰🔸 تكبير 4X\n             (قـيــم)',--zoom4x
   '➿🔰🔸 تكبير 6X\n             (قـيــم)',--zoom6x
   '➿🔰🔸 تكبير 8X\n             (قـيــم)',--zoom8x
   '➿🔰🔹 تكبير 15X\n             (قـيــم)',--zoom15x
   '🔙 عودة'
},nil,'')
if SSU == nil then else
if SSU[1] == true then Zoom4X() end
if SSU[2] == true then Zoom6X() end
if SSU[3] == true then Zoom8X() end
if SSU[4] == true then Zoom15X() end
if SSU[5] == true then WeaponMenu() end
end
end
function Zoom4X()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("60;55;1.9618179e-44 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("15", gg.TYPE_FLOAT)
gg.clearResults()
end
function Zoom6X()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("60;55;1.9618179e-44 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("14", gg.TYPE_FLOAT)
gg.clearResults()
end
function Zoom8X()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("60;55;1.9618179e-44 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("13", gg.TYPE_FLOAT)
gg.clearResults()
end
function Zoom15X()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("60;55;1.9618179e-44 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("9", gg.TYPE_FLOAT)
gg.clearResults()
end
function ScopeMenu()
SST = gg.multiChoice({
   '➿🔰🔹 سيت سكوب \n             (قـيــم)',
   '➿🔰🔹 سيت سكوب يمين \n             (قـيــم)',
   '➿🔰🔹 سيت سكوب يسار \n             (قـيــم)',
   '➿🔰🔹 سيت سكوب للامام \n             (قـيــم)',
   '➿🔰🔹 سيت سكوب يمين \n             (قـيــم)',
   '➿🔰🔹 ستاند سكوب للامام \n             (قـيــم)',
   '➿🔰🔹 ستاند سكوب يسار\n             (قـيــم)',
   '➿🔰 قائمه الغاء سيت سكوب',
   '🔙 عودة'
},nil,'')
if SST == nil then else
if SST[1] == true then SitScope() end
if SST[2] == true then SitScopeRight() end
if SST[3] == true then SitScopeLeft() end
if SST[4] == true then SitScopeFront() end
if SST[5] == true then SitScopeRight() end
if SST[6] == true then StandScopeFront() end
if SST[7] == true then StandScopeLeft() end
if SST[8] == true then ScopeDeactivateMenu() end
if SST[9] == true then WeaponMenu() end
end
end
function SitScopeRight()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4548109841269983040", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109841269983040", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109841269983040", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4548109841324179456", gg.TYPE_QWORD)
gg.clearResults()
end
function SitScopeLeft()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4548109841269983040", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109841269983040", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109841269983040", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4548109839176695808", gg.TYPE_QWORD)
gg.clearResults()
end
function SitScopeFront()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4848124999984742400", gg.TYPE_QWORD)
gg.clearResults()
end
function StandScopeLeft()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4548109952939150800", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109952939150800", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109952939150800", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4548109950845845504", gg.TYPE_QWORD)
gg.clearResults()
end
function StandScopeFront()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4848124999984742400", gg.TYPE_QWORD)
gg.clearResults()
end
function ScopeDeactivateMenu()
SSTTG = gg.multiChoice({
   '➿🔰🔹 سيت سكوب يسار \n             (قـيــم)',
   '➿🔰🔹 سيت سكوب للامام \n             (قـيــم)',
   '➿🔰🔹 سيت سكوب يمين \n             (قـيــم)',
   '➿🔰🔹 ستاند سكوب للامام \n             (قـيــم)',
   '➿🔰🔹 ستاند سكوب يسار \n             (قـيــم)',
   '➿🔰🔹 قائمه الغاء سيت سكوب\n             (قـيــم)',
   '🔙 عودة'
},nil,'')
if SSTTG == nil then else
if SSTTG[1] == true then SITSCOPEOFF() end
if SSTTG[2] == true then SITSCOPEROFF() end
if SSTTG[3] == true then SITSCOPELOFF() end
if SSTTG[4] == true then STANDSCOPEOFF() end
if SSTTG[5] == true then STANDSCOPEROFF() end
if SSTTG[6] == true then STANDSCOPELOFF() end
if SSTTG[7] == true then ScopeMenu() end
end
end
function SITSCOPEOFF()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-4767057191527907328", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("-4767057191527907328", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("-4767057191527907328", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("-4767057191653227520", gg.TYPE_QWORD)
gg.clearResults()
end
function SITSCOPEROFF()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4548109841324179456", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109841324179456", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109841324179456", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4548109841269983040", gg.TYPE_QWORD)
gg.clearResults()
end
function SITSCOPELOFF()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4548109839176695808", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109839176695808", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109839176695808", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4548109841269983040", gg.TYPE_QWORD)
gg.clearResults()
end
function STANDSCOPEOFF()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4848124999984742400", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4848124999984742400", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4848124999984742400", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4138667321167981973", gg.TYPE_QWORD)
gg.clearResults()
end
function STANDSCOPEROFF()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4548109952993329152", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109952993329152", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109952993329152", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4548109952939150800", gg.TYPE_QWORD)
gg.clearResults()
end
function STANDSCOPELOFF()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4548109950845845504", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109950845845504", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109950845845504", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4548109952939150800", gg.TYPE_QWORD)
gg.clearResults()
end

function VegetationOtherMenu()
SSR = gg.multiChoice({
'➿🔰🔸 رؤيه واضحه\n             (لـوبي)',--NoFog
'➿🔰🔸 رؤيه واضحهv2\n             (قـيــم)',--NoFogv2
'➿🔰🔸 لا عشب \n             (قـيــم)',--NoGrass
'➿🔰🔸 لا عشب v2\n             (لـوبي)',--NoGrassv2
'➿🔰🔸 ازاله الاشجار والعشب\n             (قـيــم)',--NoGrassTrees
'➿🔰🔸 انتينا مستمر\n             (قـيــم)',--AlwaysAntenna
'➿🔰🔸 رؤيـــه واســعـــه\n             (قـيــم)',--moreView
'➿🔰🔸 رؤيه ايـباد\n             (قـيــم)',--ipadview
'➿🔰🔸 رؤيـــه ايــبـــاد\n             (قـيــم)',--wideView
'➿🔰🔸 رؤيـــه ايــبـــاد v2\n             (لـوبي/قـيــم)',--wideview2
'➿🔰🔸 طيران سياره\n             (قـيــم)',--FlyCar
'🔙 عودة'--BACK
},nil,'')
if SSR == nil then else 
if SSR[1] == true then NoFogLobby() end
if SSR[2] == true then NoFogGame() end
if SSR[3] == true then NoGrassGame() end
if SSR[4] == true then NoGrassLobby() end
if SSR[5] == true then NoGrassTrees() end
if SSR[6] == true then AlwaysAntenna() end
if SSR[7] == true then MoreView() end
if SSR[8] == true then IpadView() end
if SSR[9] == true then WideView() end
if SSR[10] == true then WideViewV2() end
if SSR[11] == true then FlyCar() end
if SSR[12] == true then HOME() end
end
end
function NoFogGame()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-486470348;-298841535;-409731072:9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-298841535", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("08")
gg.getResults(551)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
end
function NoFogLobby()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber(":Default__ExponentialHeightFog", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("0", gg.TYPE_BYTE)
gg.clearResults()
end
function NoGrassGame()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("8.0F;1.20000004768F;0.80000001192F;1.5F;0.80000001192F;1.5F::512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
end
function NoGrassLobby()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber(":Default__MaterialExpressionLandscapeGrassOutput", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("0", gg.TYPE_BYTE)
gg.clearResults()
end
function NoGrassTrees()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("0.00390625;1;0.99900001287;2", gg.TYPE_FLOAT, false)
gg.searchNumber("1", gg.TYPE_FLOAT, false)
gg.getResults(30)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
end
function AlwaysAntenna()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88.50576019287F;87.27782440186F;-100.91194152832F;1F::13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("88.50576019287F;87.27782440186F;1F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(12)
gg.editAll("1.96875;1.96875;999;1.96875;1.96875;999", gg.TYPE_FLOAT)
gg.clearResults()
end
function MoreView()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("220", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("300", gg.TYPE_FLOAT)
gg.clearResults()
end
function IpadView()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("2.8025969e-45;220;25;178;15;100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("220", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("440", gg.TYPE_FLOAT)
gg.clearResults()
end
function WideView()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("80", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("260", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
end
function WideViewV2()
GCR = gg.clearResults
function split(szFullString, szSeparator)
	local nFindStartIndex = 1
	local nSplitIndex = 1
	local nSplitArray = {}
	while true do
		local nFindLastIndex = string.find(
			szFullString,
			szSeparator,
			nFindStartIndex
		)
		if not nFindLastIndex then
			nSplitArray[nSplitIndex] = string.sub(
				szFullString,
				nFindStartIndex,
				string.len(szFullString)
			)
			break
		end
		nSplitArray[nSplitIndex] = string.sub(
			szFullString,
			nFindStartIndex,
			nFindLastIndex - 1
		)
		nFindStartIndex = nFindLastIndex + string.len(szSeparator)
		nSplitIndex = nSplitIndex + 1
	end
	return nSplitArray
end
function xgxc(szpy, qmxg)
	for x = 1, #(qmxg) do
		xgpy = szpy + qmxg[x]["offset"]
		xglx = qmxg[x]["type"]
		xgsz = qmxg[x]["value"]
		gg.setValues({[1] = {address = xgpy, flags = xglx, value = xgsz}})
		xgsl = xgsl + 1
	end
end
function xqmnb(qmnb)
	gg.clearResults()
	gg.setRanges(qmnb[1]["memory"])
	gg.searchNumber(qmnb[3]["value"], qmnb[3]["type"])
	if gg.getResultCount() == 0 then
		gg.toast(qmnb[2]["name"] .. "Open failed")
	else
		gg.refineNumber(qmnb[3]["value"], qmnb[3]["type"])
		gg.refineNumber(qmnb[3]["value"], qmnb[3]["type"])
		gg.refineNumber(qmnb[3]["value"], qmnb[3]["type"])
		if gg.getResultCount() == 0 then
			gg.toast(qmnb[2]["name"] .. "Open failed")
		else
			sl = gg.getResults(999999)
			sz = gg.getResultCount()
			xgsl = 0
			if sz > 999999 then
				sz = 999999
			end
			for i = 1, sz do
				pdsz = true
				for v = 4, #(qmnb) do
					if pdsz == true then
						pysz = {}
						pysz[1] = {}
						pysz[1].address = sl[i].address + qmnb[v]["offset"]
						pysz[1].flags = qmnb[v]["type"]
						szpy = gg.getValues(pysz)
						pdpd = qmnb[v]["lv"] .. ";" .. szpy[1].value
						szpd = split(pdpd, ";")
						tzszpd = szpd[1]
						pyszpd = szpd[2]
						if tzszpd == pyszpd then
							pdjg = true
							pdsz = true
						else
							pdjg = false
							pdsz = false
						end
					end
				end
				if pdjg == true then
					szpy = sl[i].address
					xgxc(szpy, qmxg)
					xgjg = true
				end
			end
			if xgjg == true then
				gg.toast(qmnb[2]["name"] .. "Modified " .. xgsl .. " Values")
			else
				gg.toast(qmnb[2]["name"] .. "Open failed")
			end
		end
	end
end

qmnb = {
	{["memory"] = 8},
	{["name"] = "Wide View"},
	{["value"] = 3.612870300195559E-37, ["type"] = 16},
	{["lv"] = 360.0, ["offset"] = -8, ["type"] = 16},
}
qmxg = {
	{["value"] = 254.70928955078125, ["offset"] = -8, ["type"] = 16},
}
xqmnb(qmnb)
end
function FlyCar()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.76000005007;0.96078431606;1;0.74509805441::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.74509805441", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(9999)
gg.editAll("99999", gg.TYPE_FLOAT)
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("45F;15F;20F;2500F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("45", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("500", gg.TYPE_FLOAT)
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("45F;15F;20F;2500F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("45", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999999)
gg.editAll("700", gg.TYPE_FLOAT)
gg.clearResults()
end
function HighJump()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1;35;443;55;0.57357645035", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("3", gg.TYPE_FLOAT)
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3;35;443;55;0.57357645035", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("443", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("2500", gg.TYPE_FLOAT)
gg.clearResults()
end

function SpeedMenu()
SSY = gg.multiChoice({
   '➿🔰 اصلاح الاسحله \n             (قـيــم)',--FixDamageMenu
   '[ON]\n➿🔰🔹 تشغيل سرعه فلاش \n             (قـيــم)',--SpeedhackON
   '[OFF]\n➿🔰🔹 إطفاء سرعه فلاش \n             (قـيــم)',--SpeedhackOFF
   '[ON]\n➿🔰🔸 تشغيل سرعه خفيفه \n             (قـيــم)',--MircoSpeedON
   '[OFF]\n➿🔰🔸 إطفاء سرعه خفيفه \n             (قـيــم)',--MircoSpeedOFF
   '➿🔰🔹 سرعه نزول + برشوت \n             (قـيــم)',--SpeedFallParachute
   '➿🔰🔸 سرعه برشوت فقط \n             (قـيــم)',--SpeedParachute
   '➿🔰🔸 سرعه جيب \n             (قـيــم)',--SpeedJeep
   '➿🔰🔸 سرعه ساديا \n             (قـيــم)',--SpeedCar
   '➿🔰🔹 نقزه عاليه \n             (قـيــم)',--HighJump
   '🔙 عودة'--BACK
},nil,'')
if SSY == nil then else
if SSY[1] == true then FixDamageMenu() end
if SSY[2] == true then SpeedhackON() end 
if SSY[3] == true then SpeedhackOFF() end 
if SSY[4] == true then MircoSpeedON() end 
if SSY[5] == true then MircoSpeedOFF() end 
if SSY[6] == true then SpeedFallParachute() end  
if SSY[7] == true then SpeedParachute() end  
if SSY[8] == true then SpeedJeep() end 
if SSY[9] == true then SpeedCar() end
if SSY[10] == true then HighJump() end  
if SSY[11] == true then HOME() end
end
end
function SpeedhackON()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1296744149883614555", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("-1296744153870237696", gg.TYPE_QWORD)
gg.clearResults()
gg.searchNumber("-1904987454010553855", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("-1904987454002165247", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("50000~100000;0;1;5D~100D::13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("50000~100000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("35125", gg.TYPE_FLOAT)
gg.clearResults()
end
function SpeedhackOFF()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1296744153870237696", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("-1296744149883614555", gg.TYPE_QWORD)
gg.clearResults()
gg.searchNumber("-1904987454002165247", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("-1904987454010553855", gg.TYPE_QWORD)
gg.clearResults()
end
function MircoSpeedON()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1;1;1;0.0001;20;0.0005;0.4::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("1.06", gg.TYPE_FLOAT)
gg.clearResults()
end
function MircoSpeedOFF()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1.06;1.06;1.06;0.0001;20;0.0005;0.4::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1.06", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("1", gg.TYPE_FLOAT)
gg.clearResults()
end
function SpeedJeep()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.647058857", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1337)
gg.editAll("-170", gg.TYPE_FLOAT)
gg.clearResults()
end
function SpeedCar()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.76000005007;0.96078431606;1;0.74509805441::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.74509805441", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(9999)
gg.editAll("100", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("50;5;0.01", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.01", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(280)
gg.editAll("-0.23", gg.TYPE_FLOAT)
gg.clearResults()
end
function SpeedParachute()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.75;150;1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("30", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("0.75;150;30", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("0.75", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
end
function SpeedFallParachute()
gg.clearResults()
gg.setRanges(gg.REGION_C_BSS)
gg.searchNumber("2048D;4D;1F;1F;1D:30", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResultsCount()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3000;5000;1024;1000::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(6284)
gg.editAll("999999", gg.TYPE_FLOAT)
gg.clearResults()
end
function FixDamageMenu()
FD = gg.multiChoice({
  '➿🔰 Fix All Weapon',
  '➿🔰 M416',
  '➿🔰 SCAR',
  '➿🔰 M16A4',
  '➿🔰 AKM',
  '➿🔰 KAR',
  '➿🔰 AWM',
  '➿🔰 SKS',
  '➿🔰 MINI',
  '➿🔰 M249',
  '➿🔰 DP28',
  '➿🔰 QBZ',
  '➿🔰 G36',
  '➿🔰 AUG',
  '➿🔰 BERYL',
  '➿🔰 GROZA',
  '➿🔰 MUTAN',
  '➿🔰 M24',
  '➿🔰 MK',
  '➿🔰 SLR',
  '➿🔰 QBU',
  '🔙 BACK'
},nil, '')
if FD == nil then else
if FD[1] == true then fixallweaponnnn() end
if FD[2] == true then M416D() end
if FD[3] == true then SCARD() end
if FD[4] == true then M16A4D() end
if FD[5] == true then AKMD() end
if FD[6] == true then KARD() end
if FD[7] == true then AWMD() end
if FD[8] == true then SKSD() end
if FD[9] == true then MINID() end
if FD[10] == true then M249D() end
if FD[11] == true then DP28D() end
if FD[12] == true then FD1() end
if FD[13] == true then FD2() end
if FD[14] == true then FD3() end
if FD[15] == true then FD4() end
if FD[16] == true then FD5() end
if FD[17] == true then FD6() end
if FD[18] == true then FD7() end
if FD[19] == true then FD8() end
if FD[20] == true then FD9() end
if FD[21] == true then FD10() end
if FD[22] == true then SpeedMenu() end
end
end
function fixallweaponnnn()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88000;0.08600000292", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("88000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("87000;0.09600000083", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("87000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("90000;0.07500000298", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("90000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("87000;0.09229999781", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("87000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("87000;0.86", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("87000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("94000;0.08570999652", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("94000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500;0.10000000149", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500;0.07999999821", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("78000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("78000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("91000;2.2;2.5::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("91000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("76000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("76000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("79000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("79000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("80000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("80000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("85300;0.09000000358", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("85300", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("99000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("99000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("84000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("84000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("94500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("94500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("91500;0.07500000298", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("91500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500;0.109", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function M416D()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88000;0.08600000292", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("88000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function SCARD()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("87000;0.09600000083", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("87000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function M16A4D()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("90000;0.07500000298", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("90000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function AKMD()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500;0.10000000149", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function KARD()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("76000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("76000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end 
function AWMD()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("91000;2.2;2.5::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("91000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function SKSD()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("80000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("80000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function MINID()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("99000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("99000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function M249D()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("91500;0.07500000298", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("91500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function DP28D()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500;0.109", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function FD1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('87000;0.09229999781', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('87000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('87000;0.86', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('87000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD3()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('94000;0.08570999652', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('94000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD4()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('71500', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('71500', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD5()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('71500;0.07999999821', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('71500', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD6()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('78000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('78000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD7()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('79000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('79000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD8()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('85300;0.09000000358', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('85300', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD9()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('84000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('84000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD10()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('94500', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('94500', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
   
function WallhackColors()
  WHMN2 = gg.choice({
    "⁦📚 قائمة الألوان",
    "👁️ Snapdragon 855",
    "👁️ Snapdragon 855 v2",
    "👁️ Snapdragon 845",
    "👁️ Snapdragon 845 v2",
    "👁️ Snapdragon 835",
    "👁️ Snapdragon 820",
    "👁️ Snapdragon 810",
    "👁️ Snapdragon 710",
    "👁️ Snapdragon All 6XX",
    "👁️ Snapdragon 675 v1",
    "👁️ Snapdragon 675 v2",
    "👁️ Snapdragon 660",
    "👁️ Snapdragon 636",
    "👁️ Snapdragon 625 v1",    
    "👁️ Snapdragon 625 v2",
    "👁️ Snapdragon 430",
    "👁️ Snapdragon 425",
    "👁️ جميع Snapdragons",
    "👁️🧹 ولهاك الاسحله",
    "👁️ إصلاح الوميض 430-835",
    "👁️ إصلاح الوميض 845-855",
    "👁️ إصلاح الوميض v3",
    "🔙 عودة"
  }, nil, "")
  if WHMN2 == nil then
  else
    if WHMN2 == 1 then
      ColorMenu()
    end
    if WHMN2 == 2 then
      WH855()
    end
    if WHMN2 == 3 then
      WH855V2()
    end
    if WHMN2 == 4 then
      WH845()
    end
    if WHMN2 == 5 then
      WH855V2()
    end
    if WHMN2 == 6 then
      WH835()
    end
    if WHMN2 == 7 then
      WH820()
    end
    if WHMN2 == 8 then
      WH810()
    end
    if WHMN2 == 9 then
      WH710()
    end
    if WHMN2 == 10 then
      WH6XX()
    end
    if WHMN2 == 11 then
      WH675()
    end
    if WHMN2 == 12 then
      WH6752()
    end
    if WHMN2 == 13 then
      WH660()
    end
    if WHMN2 == 14 then
      WH636()
    end
    if WHMN2 == 15 then
      WH625()
    end
    if WHMN2 == 16 then
      WH6252()
    end
    if WHMN2 == 17 then
      WH430()
    end
    if WHMN2 == 18 then
      WH425()
    end    
    if WHMN2 == 19 then
      ALLD()
    end
    if WHMN2 == 20 then
      ItemWallhack()
    end
    if WHMN2 == 21 then
      FIXWH()
    end
    if WHMN2 == 22 then
      FIXWH2()
    end
    if WHMN2 == 23 then
      FIXSCOPE()
    end   
    if WHMN2 == 24 then
      HOME()
    end
  end
  HOMEDM = -1
end
function ColorMenu()
  CLRMN2 = gg.choice({
    "📚 قائمة لون السماء",
    "⚪ لون ابيض كل الاجهزه",
    "⚫ لون أسود كل الاجهزه",
    "🔴 لون أحمر HDR",
    "🔴 أحمر اللون 855",
    "🔵 اللون الأزرق 855",
    "🟡 اللون الاصفر 855",    
    "🟢 اللون الاخضر 855",
    "🔵 اللون الأزرق 845",    
    "🟢 اللون الاخضر 845",        
    "⚪ لون أبيض 845",            
    "🟡 اللون الاصفر 845",
    "🔴 أحمر اللون 845",    
    "🟡 اللون الاصفر 835",                        
    "🔴 أحمر اللون 835",                                            
    "⚫ لون أسود",
    "⚪ لون أبيض",    
    "🟢 اللون الاخضر 675",
    "🔵 اللون الأزرق 675",    
    "⚪ لون أبيض 675",                                                                                                                                                                                    
    "🟡 اللون الاصفر 660", 
    "🔴 أحمر اللون 660",                                                                                                                                                                                                                                                                
    "🟡 اللون الاصفر 625",                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
    "🔴 أحمر اللون 625",
    "🟡 اللون الاصفر 425",    
    "🔴 أحمر اللون 425",                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        
    "🔙 عودة️"
  }, nil, "")
  if CLRMN2 == nil then
  else
    if CLRMN2 == 1 then
      skycolormenupro()
    end
    if CLRMN2 == 2 then
      whitealldevices()
    end
    if CLRMN2 == 3 then
      BlackColorEEE()
    end
    if CLRMN2 == 4 then
      redHDRcolor()
    end
    if CLRMN2 == 5 then
      RED855()
    end    
    if CLRMN2 == 6 then
      BLUE845()
    end    
    if CLRMN2 == 7 then
      YELL855()
    end    
    if CLRMN2 == 8 then
      GREEN845()
    end
    if CLRMN2 == 9 then
      BLUE845()
    end    
    if CLRMN2 == 10 then
      GREEN845()
    end        
    if CLRMN2 == 11 then
      WHITEALL()
    end            
    if CLRMN2 == 12 then
      YELL845()
    end                
    if CLRMN2 == 13 then
      RED845()
    end                    
    if CLRMN2 == 14 then
      YELL835()
    end                            
    if CLRMN2 == 15 then
      RED835()
    end
    if CLRMN2 == 16 then
      BLACKALL()
    end    
    if CLRMN2 == 17 then
      WHITEALL()
    end        
    if CLRMN2 == 18 then
      GREEN675()
    end 
    if CLRMN2 == 19 then
      BLUE675()
    end    
    if CLRMN2 == 20 then
      WHITE675()
    end                    
    if CLRMN2 == 21 then
      YELL625()
    end                                    
    if CLRMN2 == 22 then
      RED625()
    end
    if CLRMN2 == 23 then
      YELL636()
    end
    if CLRMN2 == 24 then
      YELL625()
    end
    if CLRMN2 == 25 then
      RED625()
    end    
    if CLRMN2 == 26 then
      YELL425()
    end
    if CLRMN2 == 27 then
      RED425()
    end                                                                                                                                                                           
    if CLRMN2 == 28 then
      WallhackColors()
    end
  end
  HOMEDM = -1
end
function skycolormenupro()
  CLRMN6752 = gg.choice({
    "🔵 سماء صافية",
    "⚪ وايت سكاي",
    "⚫ السماء السوداء",
    "🔙 عودة"
  }, nil, "")
  if CLRMN6752 == nil then
  else
    if CLRMN6752 == 1 then
      clearsky()
    end
    if CLRMN6752 == 2 then
      whitesky()
    end
    if CLRMN6752 == 3 then
      blackskyall()
    end
    if CLRMN6752 == 4 then
      ColorMenu()
    end
  end
  HOMEDM = -1
end
function BlackColorEEE()
GCR = gg.clearResults
function split(szFullString, szSeparator)
	local nFindStartIndex = 1
	local nSplitIndex = 1
	local nSplitArray = {}
	while true do
		local nFindLastIndex = string.find(
			szFullString,
			szSeparator,
			nFindStartIndex
		)
		if not nFindLastIndex then
			nSplitArray[nSplitIndex] = string.sub(
				szFullString,
				nFindStartIndex,
				string.len(szFullString)
			)
			break
		end
		nSplitArray[nSplitIndex] = string.sub(
			szFullString,
			nFindStartIndex,
			nFindLastIndex - 1
		)
		nFindStartIndex = nFindLastIndex + string.len(szSeparator)
		nSplitIndex = nSplitIndex + 1
	end
	return nSplitArray
end
function xgxc(szpy, qmxg)
	for x = 1, #(qmxg) do
		xgpy = szpy + qmxg[x]["offset"]
		xglx = qmxg[x]["type"]
		xgsz = qmxg[x]["value"]
		gg.setValues({[1] = {address = xgpy, flags = xglx, value = xgsz}})
		xgsl = xgsl + 1
	end
end
function xqmnb(qmnb)
	gg.clearResults()
	gg.setRanges(qmnb[1]["memory"])
	gg.searchNumber(qmnb[3]["value"], qmnb[3]["type"])
	if gg.getResultCount() == 0 then
		gg.toast(qmnb[2]["name"] .. "Open failed")
	else
		gg.refineNumber(qmnb[3]["value"], qmnb[3]["type"])
		gg.refineNumber(qmnb[3]["value"], qmnb[3]["type"])
		gg.refineNumber(qmnb[3]["value"], qmnb[3]["type"])
		if gg.getResultCount() == 0 then
			gg.toast(qmnb[2]["name"] .. "Open failed")
		else
			sl = gg.getResults(999999)
			sz = gg.getResultCount()
			xgsl = 0
			if sz > 999999 then
				sz = 999999
			end
			for i = 1, sz do
				pdsz = true
				for v = 4, #(qmnb) do
					if pdsz == true then
						pysz = {}
						pysz[1] = {}
						pysz[1].address = sl[i].address + qmnb[v]["offset"]
						pysz[1].flags = qmnb[v]["type"]
						szpy = gg.getValues(pysz)
						pdpd = qmnb[v]["lv"] .. ";" .. szpy[1].value
						szpd = split(pdpd, ";")
						tzszpd = szpd[1]
						pyszpd = szpd[2]
						if tzszpd == pyszpd then
							pdjg = true
							pdsz = true
						else
							pdjg = false
							pdsz = false
						end
					end
				end
				if pdjg == true then
					szpy = sl[i].address
					xgxc(szpy, qmxg)
					xgjg = true
				end
			end
			if xgjg == true then
				gg.toast(qmnb[2]["name"] .. "Modified " .. xgsl .. " Values")
			else
				gg.toast(qmnb[2]["name"] .. "Open failed")
			end
		end
	end
end
qmnb = {
	{["memory"] = 8},
	{["name"] = "Black Color CD xClusive "},
	{["value"] = 3.612870300195559E-37, ["type"] = 16},
	{["lv"] = -1.2281847608595372E23, ["offset"] = -8732656, ["type"] = 16},
}
qmxg = {
	{["value"] = 1.2281847608595372E23, ["offset"] = -8732656, ["type"] = 16},
}
xqmnb(qmnb)
end
function WH636V2()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
end
function YELL636()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("256;8200;13::150", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("6", gg.TYPE_DWORD)
gg.clearResults()
end
function whitealldevices()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-5.1210619E-18;1:20", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1000)
gg.editAll("100", gg.TYPE_FLOAT)
gg.clearResults()
end
function ItemWallhack()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("-7.00649232e-45",gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0,-1)
gg.refineAddress("38",-1,gg.TYPE_FLOAT,gg.SIGN_EQUAL,0,-1)
gg.getResults(7243)
gg.editAll("5444",gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-3.12839322e-39",gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0,-1)
gg.refineAddress("38",-1,gg.TYPE_FLOAT,gg.SIGN_EQUAL,0,-1)
gg.getResults(7243)
gg.editAll("5444",gg.TYPE_FLOAT)
gg.clearResults()
end
function redHDRcolor()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("298", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
  gg.editAll("6", gg.TYPE_DWORD)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("8,196D;8,192D;8,200D::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.clearResults()
end
function clearsky()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.clearResults()
gg.searchNumber("100F;1F;1,008,981,770D:99", gg.TYPE_FLOAT, false, gg.SING_EQUAL, 0, -1)
gg.searchNumber("100", gg.TYPE_FLOAT, false, gg.SING_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("99999", gg.TYPE_FLOAT)
gg.clearResults()
end
function blackskyall()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("000", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("-90", gg.TYPE_FLOAT)
gg.clearResults()
end
function whitesky()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("1.5;0.16513200104", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
lgg.searchNumber("1.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("-99", gg.TYPE_FLOAT)
gg.clearResults()
end
function GREEN675()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("69,897;147,457;69,739", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.clearResults()
end
function WHITE675()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8202", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(330)
  gg.editAll("14", gg.TYPE_DWORD)
  gg.clearResults()
end
function BLUE675()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("5,129,821,174,980,681,738", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.sleep(140)
  gg.refineNumber("5,129,821,174,980,681,738", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.sleep(140)
  gg.refineAddress("2D0", -1, gg.TYPE_QWORD, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("5,129,821,174,980,681,738", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1401)
  gg.editAll("5,129,821,174,980,673,543", gg.TYPE_QWORD)
  gg.clearResults()
end
function RED425()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("\"8204\"", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.processResume()
  gg.refineAddress("\"408\"", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  revert = gg.getResults(10, nil, nil, nil, nil, nil, nil, nil, nil)
  gg.editAll("\"96\"", gg.TYPE_DWORD)
  local t = gg.getResults(10, nil, nil, nil, nil, nil, nil, nil, nil)
  gg.addListItems(t)
  t = nil
  gg.clearResults()
end
function YELL425()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("\"8204\"", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.processResume()
  gg.refineAddress("\"408\"", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  revert = gg.getResults(10, nil, nil, nil, nil, nil, nil, nil, nil)
  gg.editAll("\"95\"", gg.TYPE_DWORD)
  local t = gg.getResults(10, nil, nil, nil, nil, nil, nil, nil, nil)
  gg.addListItems(t)
  t = nil
  gg.clearResults()
end
function RED625()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("1.3912525e-19F;8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll("8199", gg.TYPE_DWORD)
  gg.clearResults()
end
function YELL845()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("0A8", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(5)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("0B0", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(5)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.clearResults()
end
function YELL625()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8196D;8192D;8200D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("8198", gg.TYPE_DWORD)
gg.clearResults()
end
function WHITEALL()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("573.70306396484;0.05499718338;1::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1)
  gg.editAll("999", gg.TYPE_FLOAT)
  gg.clearResults()
end
function BLACKALL()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("573.70306396484;0.05499718338;1::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1)
  gg.editAll("-999", gg.TYPE_FLOAT)
  gg.clearResults()
end
function RED835()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8,196D;8,192D;8,200D::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.clearResults()
end
function YELL835()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("098", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("8198", gg.TYPE_DWORD)
  gg.clearResults()
end
function RED845()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("0A8", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(5)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.clearResults()
end
function WHITE845()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("256;8200;26", 4, false, 536870912, 0, -1)
  gg.searchNumber("8200", 4, false, 536870912, 0, -1)
  gg.getResults(5)
  gg.editAll("5", 4)
  gg.clearResults()
end
function YELL855()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("0A8", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1000)
  gg.editAll("8198", gg.TYPE_DWORD)
  gg.clearResults()
  gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("0B0", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1000)
  gg.editAll("8199", gg.TYPE_DWORD)
  gg.clearResults()
end
function GREEN845()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("0B0", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(5)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.clearResults()
end
function BLUE845()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("0B0", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(5)
  gg.editAll("6", gg.TYPE_DWORD)
  gg.clearResults()
end
function WHITE855()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("0A0")
  gg.getResults(10)
  gg.editAll("8197", gg.TYPE_DWORD)
  gg.clearResults()
end
function RED855()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8,196D;8,192D;8,200D::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.clearResults()
end
function FIXWH()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("5.2806111e-40;6.50000333786;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("1.1202011e-19;1.1202015e-19;3.7615819e-37;255.0;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.clearResults()
end
function FIXWH2()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("5.2806111e-40;6.50000333786;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("1.1202011e-19;1.1202015e-19;3.7615819e-37;255.0;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.clearResults()
end
function WH855V2()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("-2 145 644 340", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("7E0", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("1 168 777 216", gg.TYPE_DWORD)
gg.clearResults()
gg.searchNumber("-2 147 483 636", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("4F8", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("1 168 777 216", gg.TYPE_DWORD)
gg.clearResults() 
ColorMenu()
end
function WH6XX()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("-2 147 086 191", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("4C8", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("1 168 777 216", gg.TYPE_DWORD)
gg.clearResults()
gg.searchNumber("-2 145 644 352", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("7E0", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("1 168 777 216", gg.TYPE_DWORD)
gg.clearResults()
ColorMenu()
end
function FIXSCOPE()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("5.2806111e-40;6.50000333786;3.7615819e-37;2", 16, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", 16, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("9999", 16)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("1.1202011e-19;1.1202015e-19;3.7615819e-37;255.0;2", 16, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", 16, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(120)
gg.editAll("9999", 16)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("4140D;1.1202011e-19~1.1202013e-19;1.1202015e-19~1.1202017e-19;2::", 16, false, gg.SIGN_EQUAL, 0, -1)                                                                                                                                                                                                                                                                                --SosnA
gg.searchNumber("2", 16, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(102)
gg.editAll("99999", 16)
gg.clearResults()
end
function WH425()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2.9427268e-44;2.0;3.0828566e-44;-1.0;3.2229865e-44;3.3631163e-44;3.643376e-44:97", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(100)
  gg.editAll("120", 16)
  gg.clearResults()
  gg.searchNumber("3.1529215e-43;2.0F;3.1669345e-43F;3.1809475e-43:49", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(100)
  gg.editAll("120", 16)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("227;1,073,741,824;1,073,741,824;-1,082,130,432;1,073,741,824:49", 4, false, 536870912, 0, -1)
  gg.searchNumber("1,073,741,824", 4, false, 536870912, 0, -1)
  gg.getResults(100)
  gg.editAll("1,123,024,896", 4)
  gg.clearResults()
  ColorMenu()
end
function WH430()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH625()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH6252()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("5.79227989e21;-5.56955884e-40;2.0;1.39125666e-19;2.0:9285", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(50)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH636()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("5.1097599e21;2.0;1.6623071e-19;3.6734297e-39;1.66433e10::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.0;-1.0;0.0;1.0;-127.0::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH660()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", 16)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", 16)
  gg.clearResults()
  ColorMenu()
end
function WH675()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("274,677,779D;2.25000452995;2;1.6623054e-19", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(20)
  gg.editAll("130", 16)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("218D;3.7615819e-37;2;-1;1", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(10)
  gg.editAll("130", 16)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("95D;2;9.2194229e-41", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(15)
  gg.editAll("130", 16)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("206D;3.7615819e-37;2;-1;1", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(10)
  gg.editAll("130", 16)
  gg.clearResults()
  ColorMenu()
end
function WH6752()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("200")
  gg.getResults(999)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("930")
  gg.getResults(999)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH710()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH810()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH820()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH835()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH845()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("200", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(25)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("930", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(25)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH855()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("95D;2;9.2194229e-41::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2;-1;0;1;-127;0.24022650719;0.69314718246;0.00999999978::30", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function ALLD()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end

function exit()
gg.setVisible(true)
os.exit()
end

startscript()

while true do
 if gg.isVisible(true) then
   HOMEDM = 1
   gg.setVisible(false)
 end
 if HOMEDM == 1 then
   HOME()
 end
end
