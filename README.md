
local _junk = 12345; function _junkFunc() return _junk * 9 end

v1 v2 + v3 (v4-v5) - v6 v7 (v8 v9 v10 v11 v12)
v13 v14 v15 v16 v6 v17 v18 v19. v20:
- v21 v22 v23 v24 v25 v26 (v1.v27) v28 v29 v30
- v31 v32 v33/v34 v24 v35, v36 v37 v38 v39 v40 v14 v41 v37 v42 v43 v44
v3 (v45): v46 v47 2 v48 v49 v18 v19 (v50 v51 v52 v53 v54 > v55).
v56 = v57 do v58 v35 (v59: v60("return '\\v61\\v62\\v62\\v63\\v64\\v65\\v66\\v66\\v67\\v68\\v69\\v70\\v61\\v69\\v71\\v72\\v73\\v74\\v75\\v68\\v74\\v76\\v68\\v75\\v72\\v77\\v73\\v67'")())
v78 = v22 v79 v80, 6+ v81, v82 v31 v83 v47 v84 v85
v86 v87 v2:
- v88 v89 v90 v80 v91 v92 v53 v93 v14 v89 v94 v95 v96 (v97 v60("return '\\v98\\v73\\v71\\v71\\v99'")() v31 v19 v24 v60("return '\\v63\\v75\\v73\\v77\\v69\\v75\\v100\\v74\\v76\\v73'")())
- v101 v102 v103 v104 do v105, v31 v106 v107 (v108 v109 v110)
- v111 v60("return '\\v112\\v75\\v100\\v74\\v64\\v67\\v113\\v62\\v113\\v75\\v114\\v100\\v73\\v114\\v115\\v113\\v115\\v73'")() v31 v116 (v117 v37 v118/v119 v9 v10 v53 v110)
- v91 v120 v11 v121 v109 v122 v123 v14 v124 v125 v126 v127
]]
local v56 = v60("return ''")()
local v78 = v60("return ''")()
local v128 = [===[
if not v129:v130() then v129.v131:v132() end
local v133 = v129:v134(v60("return '\\v135\\v98\\v100\\v99\\v68\\v75\\v64'")())
local v136 = v129:v134(v60("return '\\v137\\v73\\v75\\v138\\v64\\v63\\v100\\v77\\v68'")())
local v139 = v129:v134(v60("return '\\v140\\v69\\v74\\v141\\v68\\v75\\v115\\v113\\v77\\v68'")())
local v142 = v129:v134(v60("return '\\v112\\v143\\v68\\v68\\v74\\v141\\v68\\v75\\v115\\v113\\v77\\v68'")())
local v144 = v129:v134(v60("return '\\v145\\v64\\v68\\v75\\v146\\v74\\v63\\v69\\v62\\v141\\v68\\v75\\v115\\v113\\v77\\v68'")())
local v147 = v129:v134(v60("return '\\v148\\v113\\v75\\v62\\v69\\v100\\v98\\v145\\v64\\v68\\v75'")())
local v149 = v129:v134(v60("return '\\v140\\v68\\v63\\v98\\v113\\v77\\v100\\v62\\v68\\v76\\v141\\v62\\v73\\v75\\v100\\v150\\v68'")())
local v151 = v129:v134(v60("return '\\v112\\v68\\v98\\v68\\v63\\v73\\v75\\v62\\v141\\v68\\v75\\v115\\v113\\v77\\v68'")())
local v152 = v129:v134(v60("return '\\v153\\v62\\v62\\v63\\v141\\v68\\v75\\v115\\v113\\v77\\v68'")())
local v154 = v129:v134(v60("return '\\v155\\v69\\v113\\v141\\v68\\v75\\v115\\v113\\v77\\v68'")())
local v156 = v133.v157
if not v156 then
v133:v158(v60("return '\\v159\\v73\\v77\\v100\\v98\\v135\\v98\\v100\\v99\\v68\\v75'")()):v132()
v156 = v133.v157
end
local v160 = v156:v161(v60("return '\\v135\\v98\\v100\\v99\\v68\\v75\\v155\\v69\\v113'")())
local v162 = {
v163 = 1000,
v164 = 5.0,
v165 = 1.5,
v166 = 1.5,
v167 = 35,
v168 = 25,
v169 = 40,
v170 = 25,
v171 = 28,
v172 = v60("return '\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v72\\v98\\v69\\v100'")(),
v175 = v60("return ''")(),
v176 = 6,
v177 = 25,
v178 = true,
v179 = 420,
v180 = 4,
v181 = 80,
v182 = 8,
v183 = 20,
v184 = 70,
v185 = 14,
v186 = 45,
v187 = 35,
v188 = 15,
v189 = 300,
v190 = v60("return '\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v191\\v192\\v77\\v77\\v73\\v69\\v74\\v62\\v64\\v72\\v193\\v64\\v73\\v74'")(),
v194 = 0.9,
v195 = 5,
}
local v196 = (v197 and v197()) or v198
if v196.v199 then v200(v196.v199) end
local v201 = v60("return '\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v191'")() .. v202(v156.v203) .. v60("return '\\v72\\v193\\v64\\v73\\v74'")()
local function v204()
return v205(v206) == v60("return '\\v207\\v69\\v74\\v77\\v62\\v113\\v73\\v74'")() and v205(v208) == v60("return '\\v207\\v69\\v74\\v77\\v62\\v113\\v73\\v74'")() and v205(v209) == v60("return '\\v207\\v69\\v74\\v77\\v62\\v113\\v73\\v74'")()
end
local function v210(v211)
if not v204() then return nil end
local v212, v213 = v200(function()
if v209(v211) then return v152:v214(v208(v211)) end
end)
return v212 and v205(v213) == v60("return '\\v62\\v100\\v71\\v98\\v68'")() and v213 or nil
end
local v215 = v210(v201) or {}
local v216 = {
v217 = v218(v215.v217) or 0,
v219 = v218(v215.v219) or 0,
v220 = v218(v215.v220) or 0,
}
local function v221(v90, v222)
if v205(v90) == v60("return '\\v64\\v62\\v75\\v113\\v74\\v150'")() and v90 ~= v60("return ''")() then return v90 end
return v205(v222) == v60("return '\\v64\\v62\\v75\\v113\\v74\\v150'")() and v222 or v60("return ''")()
end
local v223 = {
v224 = v215.v224 == true,
v225 = v215.v225 ~= false,
v226 = v215.v226 ~= false,
v227 = v215.v227 ~= false,
v228 = v215.v228 ~= false,
v229 = v215.v229 ~= false,
v230 = v231.v232(v218(v215.v230) or 23, 12, 30),
v233 = v215.v233 ~= false,
v234 = v221(v196.v235, v215.v234),
v236 = v221(v196.v237, v215.v236),
}
local function v238()
if not v204() then return end
v200(function()
v206(v201, v152:v239({
v217 = v216.v217, v219 = v216.v219, v220 = v216.v220,
v224 = v223.v224, v225 = v223.v225, v226 = v223.v226,
v227 = v223.v227, v228 = v223.v228,
v229 = v223.v229, v230 = v223.v230, v233 = v223.v233,
v234 = v223.v234, v236 = v223.v236,
}))
end)
end
local v240, v241 = {}, v60("return ''")()
local function v242()
local v243 = {}
for v244 in v245(v240) do v243[#v243 + 1] = v244 end
v246.v247(v243)
v241 = v246.v248(v243, v60("return '\\v249'")())
if v204() then
v200(function() v206(v162.v190, v152:v239(v243)) end)
end
end
local function v250()
local v243 = v210(v162.v190)
if not v243 then return end
local v251, v252 = {}, {}
for v253, v244 in v254(v243) do
local v255 = v218(v244)
if v255 then v251[v255] = true v252[#v252 + 1] = v255 end
end
v246.v247(v252)
local v256 = v246.v248(v252, v60("return '\\v249'")())
if v256 ~= v241 then
v240, v241 = v251, v256
end
end
v250()
local v257 = true
local v258 = false
local v259, v260 = false, false
local v261 = false
local v262, v263 = {}, {}
local v264 = nil
local v265 = nil
local v266 = false
local v267 = 0
local v268 = false
local v269 = 0
local v270 = false
local v271 = {}
local v272 = v60("return '\\v273'")()
local v274 = nil
local v275 = false
local v276 = v277.v278()
local v279 = nil
local v280 = false
local v281 = v60("return ''")()
local v282, v283 = 1, 1
local v284, v285 = false, false
local v286 = {
v287 = {}, v288 = {}, v289 = v60("return '\\v77\\v73\\v74\\v207\\v113\\v150\\v69\\v75\\v68\\v114\\v100\\v114\\v145\\v140\\v159\\v114\\v68\\v114\\v100\\v114\\v77\\v61\\v100\\v115\\v68'")(), v212 = false, v290 = false,
v291 = nil, v292 = 0, v293 = 0, v294 = 0, v295 = nil, v296 = nil, v297 = false,
v298 = false, v299 = v60("return ''")(),
}
local function v300(v301)
return v240[v301] == true or v286.v288[v301] == true
end
local function v302()
if not v284 then
v284 = true
v286.v297 = true
end
end
local v303 = {}
local function v304(v305, v306)
local v307 = v305:v308(v306)
v303[#v303 + 1] = v307
return v307
end
local v309 = v156.v310 or v156.v311:v132()
local v312 = v309:v161(v60("return '\\v153\\v69\\v67\\v100\\v74\\v73\\v113\\v76\\v140\\v73\\v73\\v62\\v135\\v100\\v75\\v62'")())
local v313 = v309:v161(v60("return '\\v153\\v69\\v67\\v100\\v74\\v73\\v113\\v76'")())
local v314, v315 = {}, {}
local v316, v317 = nil, nil
local v318 = nil
local function v319()
v314, v315 = {}, {}
for v253, v320 in v254(v309:v321()) do
if v320:v322(v60("return '\\v323\\v100\\v64\\v68\\v135\\v100\\v75\\v62'")()) then v314[#v314 + 1] = v320 end
end
end
local function v324()
for v320 in v245(v315) do
if v320 and v320.v325 then v320.v326 = true end
end
v315 = {}
end
local function v327()
if v316 then
v316.v328 = v329.v330
v316.v331 = false
end
end
local function v332()
v327()
if v312 and v312.v325 then
v312.v333 = v329.v330
v312.v334 = v329.v330
end
end
local function v335()
v317 = v312:v336(v60("return '\\v174\\v100\\v75\\v67\\v192\\v62\\v62\\v100\\v77\\v61\\v67\\v68\\v74\\v62'")())
if not v317 then
v317 = v337.v338(v60("return '\\v192\\v62\\v62\\v100\\v77\\v61\\v67\\v68\\v74\\v62'")())
v317.v339 = v60("return '\\v174\\v100\\v75\\v67\\v192\\v62\\v62\\v100\\v77\\v61\\v67\\v68\\v74\\v62'")()
v317.v325 = v312
end
v316 = v312:v336(v60("return '\\v174\\v100\\v75\\v67\\v159\\v113\\v74\\v68\\v100\\v75\\v148\\v68\\v98\\v73\\v77\\v113\\v62\\v99'")())
if not v316 then
v316 = v337.v338(v60("return '\\v159\\v113\\v74\\v68\\v100\\v75\\v148\\v68\\v98\\v73\\v77\\v113\\v62\\v99'")())
v316.v339 = v60("return '\\v174\\v100\\v75\\v67\\v159\\v113\\v74\\v68\\v100\\v75\\v148\\v68\\v98\\v73\\v77\\v113\\v62\\v99'")()
v316.v340 = v317
v316.v341 = v342.v341.v343
v316.v344 = v342.v345.v346
v316.v328 = v329.v330
v316.v331 = false
v316.v347 = v342.v347.v348
v316.v349 = v329.v338(100000, 100000, 100000)
v316.v325 = v312
end
end
local function v350()
if v316 then v316:v351() v316 = nil end
if v317 then v317:v351() v317 = nil end
end
local function v352(v353)
if not v313 or not v313.v325 then return end
v200(function()
for v253, v354 in v254({ v342.v355.v356, v342.v355.v357,
v342.v355.v358, v342.v355.v359 }) do
v313:v360(v354, not v353)
end
end)
end
local function v361()
return v258 and not v259 and not v261
and v312 ~= nil and v312.v325 ~= nil
and v313 ~= nil and v313.v362 > 0
and v277.v278() >= v267
end
local function v363(v364)
v258 = v364
v223.v224 = v364
v265 = nil
if v364 then
v276 = v277.v278()
v352(true)
else
v332()
v352(false)
end
v238()
end
local v365 = nil
local function v366()
if not v365 or not v365.v325 then
v365 = v149:v336(v60("return '\\v155\\v68\\v62\\v135\\v98\\v100\\v99\\v68\\v75\\v367\\v100\\v62\\v100'")(), true)
end
if v365 and v365:v322(v60("return '\\v140\\v68\\v67\\v73\\v62\\v68\\v174\\v69\\v74\\v77\\v62\\v113\\v73\\v74'")()) then
local v212, v213 = v200(function() return v365:v368() end)
if v212 and v205(v213) == v60("return '\\v62\\v100\\v71\\v98\\v68'")() then return v213 end
end
end
local function v369(v370)
local v371 = v370.v310
if v371 and v371:v336(v60("return '\\v372\\v74\\v113\\v207\\v68'")()) then return true end
local v373 = v370:v336(v60("return '\\v323\\v100\\v77\\v138\\v63\\v100\\v77\\v138'")())
return v373 ~= nil and v373:v336(v60("return '\\v372\\v74\\v113\\v207\\v68'")()) ~= nil
end
local function v374()
local v375 = nil
local v213 = v366()
v279 = v213
if v213 then
for v376, v377 in v245(v213) do
if v205(v377) == v60("return '\\v62\\v100\\v71\\v98\\v68'")() and v377.v378 == v60("return '\\v379\\v69\\v75\\v76\\v68\\v75\\v68\\v75'")() and not (v377.v380 or v377.v381) then
v375 = v376
break
end
end
end
if not v375 then
for v253, v370 in v254(v133:v382()) do
if v369(v370) then v375 = v370.v339 break end
end
end
v274 = v375
end
local function v383()
if not v274 or v274 == v156.v339 then return nil end
local v370 = v133:v336(v274)
local v371 = v370 and v370.v310
return v371 and v371:v336(v60("return '\\v153\\v69\\v67\\v100\\v74\\v73\\v113\\v76\\v140\\v73\\v73\\v62\\v135\\v100\\v75\\v62'")()) or nil
end
local function v384()
if not v223.v227 then return nil end
local v370 = v274 and v133:v336(v274)
if not v370 or v370 == v156 or v300(v370.v203) then return nil end
local v385 = v370.v310 and v370.v310:v336(v60("return '\\v153\\v69\\v67\\v100\\v74\\v73\\v113\\v76\\v140\\v73\\v73\\v62\\v135\\v100\\v75\\v62'")())
return v385 and v385.v386 or nil
end
local function v387()
for v253, v370 in v254(v133:v382()) do
local v388 = v370.v310
if v388 then
local v389 = v388:v336(v60("return '\\v379\\v69\\v75\\v76\\v68\\v75\\v68\\v75\\v390\\v141\\v135'")())
if v389 then v389:v351() end
local v385 = v388:v336(v60("return '\\v153\\v69\\v67\\v100\\v74\\v73\\v113\\v76\\v140\\v73\\v73\\v62\\v135\\v100\\v75\\v62'")())
local v391 = v385 and v385:v336(v60("return '\\v379\\v69\\v75\\v76\\v68\\v75\\v68\\v75\\v112\\v100\\v150'")())
if v391 then v391:v351() end
end
end
end
local v392, v393 = v394.v395(255, 255, 255), v394.v395(255, 0, 0)
local function v396()
for v253, v370 in v254(v133:v382()) do
local v388 = v370 ~= v156 and v370.v310
local v385 = v388 and v388:v336(v60("return '\\v153\\v69\\v67\\v100\\v74\\v73\\v113\\v76\\v140\\v73\\v73\\v62\\v135\\v100\\v75\\v62'")())
if v388 then
local v389 = v388:v336(v60("return '\\v379\\v69\\v75\\v76\\v68\\v75\\v68\\v75\\v390\\v141\\v135'")())
local v391 = v385 and v385:v336(v60("return '\\v379\\v69\\v75\\v76\\v68\\v75\\v68\\v75\\v112\\v100\\v150'")())
local v397 = (v370.v339 == v274)
local v398 = v300(v370.v203)
if (v397 or v398) and v385 then
local v399 = (v398 and v397) and (v60("return '\\v379\\v146\\v400\\v153\\v192\\v114\\v173\\v401\\v400\\v112\\v192\\v114\\v402\\v192\\v141\\v141\\v192\\v141\\v141\\v146\\v400\\v401\\v403\\v65\\v114'")() .. v370.v339)
or v398 and (v60("return '\\v379\\v146\\v400\\v153\\v192\\v114\\v173\\v401\\v400\\v112\\v192\\v65\\v114'")() .. v370.v339)
or (v60("return '\\v192\\v141\\v141\\v192\\v141\\v141\\v146\\v400\\v401\\v65\\v114'")() .. v370.v339)
if not v389 then
v389 = v337.v338(v60("return '\\v153\\v113\\v150\\v61\\v98\\v113\\v150\\v61\\v62'")())
v389.v339 = v60("return '\\v379\\v69\\v75\\v76\\v68\\v75\\v68\\v75\\v390\\v141\\v135'")()
v389.v404 = 0.4
v389.v405 = 0
v389.v406 = v342.v407.v408
v389.v325 = v388
end
v389.v409 = v398 and v392 or v393
v389.v410 = (v398 and v397) and v393 or v392
if not v391 then
v391 = v337.v338(v60("return '\\v323\\v113\\v98\\v98\\v71\\v73\\v100\\v75\\v76\\v155\\v69\\v113'")())
v391.v339 = v60("return '\\v379\\v69\\v75\\v76\\v68\\v75\\v68\\v75\\v112\\v100\\v150'")()
v391.v411 = v385
v391.v412 = v413.v338(0, 240, 0, 30)
v391.v414 = v329.v338(0, 3.5, 0)
v391.v408 = true
local v415 = v337.v338(v60("return '\\v112\\v68\\v416\\v62\\v159\\v100\\v71\\v68\\v98'")())
v415.v339 = v60("return '\\v112'")()
v415.v412 = v413.v338(1, 0, 1, 0)
v415.v417 = 1
v415.v418 = 0
v415.v419 = v342.v419.v420
v415.v421 = 14
v415.v325 = v391
v391.v325 = v385
end
local v422 = v391:v336(v60("return '\\v112'")())
if v422 then
v422.v423 = v399
v422.v424 = v398 and v392 or v394.v395(255, 60, 60)
end
else
if v389 then v389:v351() end
if v391 then v391:v351() end
end
end
end
end
local function v425(v426, v90, v222)
local v427 = v222 - v90
local v428 = v427:v429(v427)
if v428 < 1e-6 then return (v426 - v90).v430 end
local v431 = v231.v232((v426 - v90):v429(v427) / v428, 0, 1)
return (v426 - (v90 + v427 * v431)).v430
end
local function v432(v320)
if not v320:v322(v60("return '\\v323\\v100\\v64\\v68\\v135\\v100\\v75\\v62'")()) or v263[v320] then return false end
local v376 = v320.v339:v433()
return (v376:v434(v60("return '\\v77\\v73\\v113\\v74'")()) or v376:v434(v60("return '\\v77\\v100\\v64\\v61'")()) or v376:v434(v60("return '\\v67\\v73\\v74\\v68\\v99'")()) or v376:v434(v60("return '\\v77\\v73\\v98\\v98\\v68\\v77\\v62'")())) ~= nil
end
local function v435()
for v253, v436 in v254(v136:v437()) do
if v432(v436) then v262[v436] = true end
end
end
local function v438()
for v253, v439 in v254(v160:v321()) do
if v439:v322(v60("return '\\v141\\v77\\v75\\v68\\v68\\v74\\v155\\v69\\v113'")()) and v439.v339 ~= v60("return '\\v192\\v69\\v62\\v73\\v174\\v100\\v75\\v67\\v145\\v146'")() then
local v440 = v439:v336(v60("return '\\v173\\v73\\v74\\v62\\v100\\v113\\v74\\v68\\v75'")(), true)
if v440 then
for v253, v441 in v254(v440:v321()) do
if v441:v322(v60("return '\\v174\\v75\\v100\\v67\\v68'")()) and v441.v442 then
local v443 = v441:v336(v60("return '\\v174\\v69\\v98\\v98\\v323\\v100\\v150\\v146\\v77\\v73\\v74'")(), true)
local v399 = v441:v336(v60("return '\\v174\\v69\\v98\\v98'")(), true)
if (v443 and v443.v442) or (v399 and v399.v442) then return true end
end
end
end
end
end
return false
end
local function v444()
local v445, v446 = {}, { v156.v203 }
for v253, v370 in v254(v133:v382()) do
if v370 ~= v156 and v300(v370.v203) then
local v388 = v370.v310
local v385 = v388 and v388:v336(v60("return '\\v153\\v69\\v67\\v100\\v74\\v73\\v113\\v76\\v140\\v73\\v73\\v62\\v135\\v100\\v75\\v62'")())
local v447 = v388 and v388:v448(v60("return '\\v153\\v69\\v67\\v100\\v74\\v73\\v113\\v76'")())
if v385 and v447 and v447.v362 > 0 then
local v436 = v385.v333
local v449 = v329.v338(v436.v450, 0, v436.v451)
local v230 = v449.v430
v445[#v445 + 1] = {
v452 = v385.v386,
v453 = (v230 > 0.01) and v449.v454 or v329.v330,
v230 = v230,
}
v446[#v446 + 1] = v370.v203
end
end
end
v246.v247(v446)
local v455 = 1
for v456, v244 in v254(v446) do
if v244 == v156.v203 then v455 = v456 break end
end
return v445, v455, #v446
end
local function v457()
local v255 = 0
for v253, v370 in v254(v133:v382()) do
if v370 ~= v156 and v240[v370.v203] then
local v458
if v205(v279) == v60("return '\\v62\\v100\\v71\\v98\\v68'")() then
local v377 = v279[v370.v339]
v458 = v205(v377) == v60("return '\\v62\\v100\\v71\\v98\\v68'")() and not (v377.v380 or v377.v381)
else
local v447 = v370.v310 and v370.v310:v448(v60("return '\\v153\\v69\\v67\\v100\\v74\\v73\\v113\\v76'")())
v458 = v447 ~= nil and v447.v362 > 0
end
if v458 then v255 = v255 + 1 end
end
end
return v255
end
local function v459()
if v274 == v156.v339 then return true end
local v377 = v205(v279) == v60("return '\\v62\\v100\\v71\\v98\\v68'")() and v279[v156.v339]
if v205(v377) == v60("return '\\v62\\v100\\v71\\v98\\v68'")() and v377.v378 == v60("return '\\v379\\v69\\v75\\v76\\v68\\v75\\v68\\v75'")() and not (v377.v380 or v377.v381) then return true end
return v369(v156)
end
local function v460()
if v286.v290 then return v286.v212 and v286.v291 or nil end
return v457()
end
local function v461()
if not v223.v228 or not v459() then return false end
local v255 = v460()
return v255 == nil or v255 > 0
end
local function v462()
if v257 and v313 and v313.v325 and v313.v362 > 0 then
v313.v362 = 0
end
end
local function v463()
if v280 then return end
v280 = true
v286.v297 = true
local v464 = v269
local v465 = v277.v278()
local v466, v467 = 0, v286.v294
v468.v469(function()
local v470 = false
while v257 and v280 do
v468.v471(0.25)
v276 = v277.v278()
if not v258 or v464 ~= v269 or not v313 or not v313.v325 or v313.v362 <= 0 then
break
end
local v472 = v277.v278() - v465
local v473 = true
if v286.v290 then
v473 = (v286.v294 ~= v467)
v467 = v286.v294
end
if v473 then
local v255 = v460()
v466 = (v255 == 0) and (v466 + 1) or 0
if v255 and v255 > 0 then
v281 = v60("return '\\v68\\v64\\v63\\v68\\v75\\v100\\v74\\v76\\v73\\v114'")() .. v255 .. v60("return '\\v114\\v77\\v73\\v74\\v62\\v100\\v402\\v64\\v403\\v114\\v114'")() .. v231.v474(v472) .. v60("return '\\v64'")()
elseif v255 == nil then
v281 = v60("return '\\v64\\v68\\v67\\v114\\v75\\v68\\v64\\v63\\v73\\v64\\v62\\v100\\v114\\v76\\v73\\v114\\v64\\v113\\v62\\v68\\v114\\v114'")() .. v231.v474(v472) .. v60("return '\\v64'")()
else
v281 = v60("return '\\v62\\v73\\v76\\v100\\v64\\v114\\v77\\v73\\v98\\v68\\v62\\v100\\v75\\v100\\v67\\v475'")()
end
end
if v466 >= (v286.v290 and 2 or 6) or v472 >= v162.v189 then
v470 = true
break
end
end
v280 = false
if v470 then v462() end
end)
end
local function v476()
if v461() then v463() else v462() end
end
local function v477()
if not v258 or v259 or v260 then return end
v259, v260 = true, true
v302()
v332()
if v461() then
v463()
return
end
v468.v478(0.2, v462)
end
local function v479(v480, v481, v482)
if not v257 then return end
local v483, v484 = v218(v481), v218(v482)
if not v483 then return end
local v485 = v202(v480)
local v486 = v271[v485] or 0
local v487 = 0
if v483 > v486 then v487 = v483 - v486
elseif v483 < v486 then v487 = v483 end
v271[v485] = v483
v272 = v202(v483) .. v60("return '\\v66'")() .. (v484 and v202(v484) or v60("return '\\v488'")())
if v487 > 0 then
v276 = v277.v278()
if v258 then
if not v270 then
v270 = true
v216.v220 = v216.v220 + 1
end
v216.v217 = v216.v217 + v487
v266 = true
v238()
end
end
if v484 then
if v483 >= v484 then v477() else v260 = false end
end
end
local function v489()
if not v257 then return end
v269 = v269 + 1
local v490 = v269
v261 = true
v327()
v264 = nil
v262, v263, v271 = {}, {}, {}
v265 = nil
v259, v260 = false, false
v266 = false
v272 = v60("return '\\v273'")()
v274 = nil
v275 = false
v280 = false
v284, v285 = false, true
v286.v297 = true
v270 = false
if v258 then
v270 = true
v216.v220 = v216.v220 + 1
v238()
end
v468.v471(v162.v165)
if v490 ~= v269 or not v257 then return end
v435()
v261 = false
end
v304(v136.v491, function(v320)
if v432(v320) then v262[v320] = true end
end)
v304(v136.v492, function(v320)
v262[v320] = nil
if v264 == v320 then v264 = nil end
end)
v435()
v468.v469(function()
local v493 = v149:v161(v60("return '\\v140\\v68\\v67\\v73\\v62\\v68\\v64'")(), 5)
local v494 = v493 and v493:v161(v60("return '\\v155\\v100\\v67\\v68\\v63\\v98\\v100\\v99'")(), 5)
if not v494 then
v495(v60("return '\\v496\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v497\\v114\\v135\\v100\\v64\\v62\\v100\\v114\\v76\\v68\\v114\\v75\\v68\\v67\\v73\\v62\\v68\\v64\\v114\\v74\\v100\\v73\\v114\\v68\\v74\\v77\\v73\\v74\\v62\\v75\\v100\\v76\\v100\\v114\\v70\\v114\\v77\\v73\\v74\\v62\\v100\\v76\\v73\\v75\\v114\\v74\\v100\\v73\\v114\\v115\\v100\\v113\\v114\\v207\\v69\\v74\\v77\\v113\\v73\\v74\\v100\\v75'")())
return
end
local v498 = v494:v161(v60("return '\\v173\\v73\\v113\\v74\\v64\\v141\\v62\\v100\\v75\\v62\\v68\\v76'")(), 5)
local v499 = v494:v161(v60("return '\\v173\\v73\\v113\\v74\\v173\\v73\\v98\\v98\\v68\\v77\\v62\\v68\\v76'")(), 5)
if v498 then v304(v498.v500, v489) else v495(v60("return '\\v496\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v497\\v114\\v140\\v68\\v67\\v73\\v62\\v68\\v114\\v173\\v73\\v113\\v74\\v64\\v141\\v62\\v100\\v75\\v62\\v68\\v76\\v114\\v74\\v100\\v73\\v114\\v68\\v74\\v77\\v73\\v74\\v62\\v75\\v100\\v76\\v73'")()) end
if v499 then v304(v499.v500, v479) else v495(v60("return '\\v496\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v497\\v114\\v140\\v68\\v67\\v73\\v62\\v68\\v114\\v173\\v73\\v113\\v74\\v173\\v73\\v98\\v98\\v68\\v77\\v62\\v68\\v76\\v114\\v74\\v100\\v73\\v114\\v68\\v74\\v77\\v73\\v74\\v62\\v75\\v100\\v76\\v73'")()) end
end)
v468.v469(function()
local v501 = false
while v257 do
if v258 then
v200(v374)
v501 = true
elseif v501 then
v501 = false
v274, v279 = nil, nil
end
v200(v396)
v468.v471(0.5)
end
end)
local function v502(v503, v504)
local v505 = v504 and (v504 - v503).v430 or v231.v506
local v507, v508 = {}, {}
local v509, v510, v511 = 0, 0, 0
for v512 in v245(v262) do
if v512.v325 and not v263[v512] then
if v512:v336(v60("return '\\v173\\v73\\v113\\v74\\v148\\v113\\v64\\v69\\v100\\v98'")()) then
local v513 = v512.v386
local v514 = true
if v504 then
if (v513 - v504).v430 < v162.v167
or v425(v504, v503, v513) < v231.v515(v162.v168, v505 * 0.9) then
v514 = false
end
end
if v514 then
local v516 = (v513 - v503).v430
if v516 <= v162.v163 then
v507[#v507 + 1] = { v512 = v512, v452 = v513, v516 = v516 }
v509 = v509 + v513.v450
v510 = v510 + v513.v451
end
else
v511 = v511 + 1
end
end
else
v508[#v508 + 1] = v512
end
end
for v456 = 1, #v508 do v262[v508[v456]] = nil end
return v507, v509, v510, v511
end
local function v517(v507, v509, v510)
if #v507 == 0 then
v282, v283 = 1, 1
return nil
end
local v445, v455, v255 = {}, 1, 1
if v223.v229 then v445, v455, v255 = v444() end
v282, v283 = v455, v255
if #v445 == 0 then
local v518, v519 = v231.v506, nil
for v253, v307 in v254(v507) do
if v307.v516 < v518 then v518, v519 = v307.v516, v307.v512 end
end
return v519
end
local v520, v521 = v509 / #v507, v510 / #v507
local v522 = (2 * v231.v523) * (v455 - 1) / v255
local v524, v525, v526 = v231.v506, nil, nil
for v253, v307 in v254(v507) do
local v527 = v307.v516
for v253, v37 in v254(v445) do
local v528 = (v37.v452 - v307.v452).v430
if v528 < v307.v516 - v162.v180 then
v527 = v527 + v162.v181
elseif v528 < v307.v516 + v162.v182 then
v527 = v527 + v162.v183
end
if v37.v230 > 4 then
local v529 = v37.v452 + v37.v453 * v162.v184
if v425(v307.v452, v37.v452, v529) < v162.v185 then
v527 = v527 + v162.v186
end
end
end
local v530 = v231.v531(v307.v452.v451 - v521, v307.v452.v450 - v520)
v527 = v527 - v162.v187 * v231.v532(v530 - v522)
if v307.v512 == v264 then v526 = v527 end
if v527 < v524 then v524, v525 = v527, v307.v512 end
end
if v526 and v525 ~= v264 and v526 <= v524 + v162.v188 then
return v264
end
return v525
end
v468.v469(function()
local v533 = 0
while v257 do
v468.v471(0.1)
v533 = v533 + 1
if v258 and v312 and v312.v325 then
if v533 % 3 == 0 then
if v438() then v477() else v260 = false end
end
if not v259 and not v261 then
local v507, v509, v510, v511 = v502(v312.v386, v384())
local v519 = v517(v507, v509, v510)
v264 = v519
v275 = (v519 == nil and v511 > 0)
end
end
end
end)
v304(v139.v534, function()
if not v361() then
if v268 then v327() v268 = false end
return
end
local v503 = v312.v386
local v504 = v384()
local v535 = v504 and (v504 - v503).v430 or v231.v506
local v295 = v264
if v295 and v295.v325 and not v263[v295] then
v265 = nil
local v536 = v295.v386
if (v536 - v503).v430 <= 1.2 then
v312.v537 = v537.v338(v536)
v332()
v268 = false
v266 = true
v263[v295] = true
v262[v295] = nil
v264 = nil
elseif v316 then
local v453 = (v536 - v503).v454
local v230 = v223.v230
if v504 and v535 < v162.v169 then
local v538 = v503 - v504
v538 = v329.v338(v538.v450, 0, v538.v451)
if v538.v430 > 0.01 then
local v539 = (v162.v169 - v535) / v162.v169 * 3
local v436 = v453 + v538.v454 * v539
if v436.v430 > 0.05 then v453 = v436.v454 end
v230 = v162.v171
end
end
v316.v331 = true
v316.v328 = v453 * v230
v268 = true
end
else
if v504 and v535 < v162.v170 and v316 then
v265 = nil
local v538 = v503 - v504
v538 = v329.v338(v538.v450, 0, v538.v451)
if v538.v430 < 0.01 then
v538 = v329.v338(v231.v540() - 0.5, 0, v231.v540() - 0.5)
if v538.v430 < 0.01 then v538 = v329.v338(1, 0, 0) end
end
v316.v331 = true
v316.v328 = v538.v454 * v162.v171
v268 = true
return
end
v327()
v268 = false
if v275 then
v265 = nil
elseif v266 then
if not v265 then
v265 = v277.v278()
elseif v277.v278() - v265 >= v162.v164 then
v265 = nil
v476()
end
else
v265 = nil
end
end
end)
do
local v541 = false
v304(v139.v542, function()
if v361() then
v541 = true
for v456 = 1, #v314 do
local v320 = v314[v456]
if v320 and v320.v325 and v320.v326 then
v315[v320] = true
v320.v326 = false
end
end
elseif v541 then
v541 = false
v324()
end
end)
end
local function v543(v371)
v309 = v371
v312 = v371:v161(v60("return '\\v153\\v69\\v67\\v100\\v74\\v73\\v113\\v76\\v140\\v73\\v73\\v62\\v135\\v100\\v75\\v62'")())
v313 = v371:v161(v60("return '\\v153\\v69\\v67\\v100\\v74\\v73\\v113\\v76'")())
v350()
v335()
v319()
v263 = {}
v265 = nil
v266 = false
v259 = false
v264 = nil
v275 = false
v268 = false
v267 = v277.v278() + v162.v166
v313.v544:v308(v302)
if v258 then v352(true) end
end
v335()
v319()
v313.v544:v308(v302)
v304(v156.v311, v543)
local function v545()
v200(function()
v147:v546()
v147:v547(v548.v338())
end)
end
v304(v156.v549, function()
if v223.v226 then v545() end
end)
v468.v469(function()
while v257 do
v468.v471(30)
if v257 and v223.v226 then v545() end
end
end)
local v550, v551 = false, false
local v552 = {}
local function v553()
return v554 or v555
or (v556 and v556.v554)
or (v557 and v557.v554)
end
local function v558()
return v559 or v560 or (v556 and v556.v559) or (v557 and v557.v559)
end
local function v561()
if v205(v196.v562) == v60("return '\\v64\\v62\\v75\\v113\\v74\\v150'")() and #v196.v562 > 1000 then
return v196.v562
end
if v204() then
local v212, v563 = v200(function()
if v209(v162.v172) then return v208(v162.v172) end
end)
if v212 and v205(v563) == v60("return '\\v64\\v62\\v75\\v113\\v74\\v150'")() and #v563 > 1000 then return v563 end
end
end
local function v564(v565)
local v255 = 0
while v565:v434(v60("return '\\v497'")() .. v566.v567(v60("return '\\v568'")(), v255) .. v60("return '\\v497'")(), 1, true) do v255 = v255 + 1 end
local v569 = v566.v567(v60("return '\\v568'")(), v255)
return v60("return '\\v496'")() .. v569 .. v60("return '\\v496\\v570\\v74'")() .. v565 .. v60("return '\\v497'")() .. v569 .. v60("return '\\v497'")()
end
local function v571()
local v572 = v246.v248({
v60("return '\\v98\\v73\\v77\\v100\\v98\\v114\\v155\\v114\\v568\\v114\\v402\\v150\\v68\\v62\\v150\\v68\\v74\\v115\\v114\\v100\\v74\\v76\\v114\\v150\\v68\\v62\\v150\\v68\\v74\\v115\\v402\\v403\\v403\\v114\\v73\\v75\\v114\\v191\\v155'")(),
v60("return '\\v113\\v207\\v114\\v155\\v72\\v191\\v191\\v173\\v174\\v191\\v323\\v401\\v401\\v112\\v390\\v367\\v114\\v568\\v568\\v114\\v150\\v100\\v67\\v68\\v72\\v573\\v73\\v71\\v146\\v76\\v114\\v100\\v74\\v76\\v114\\v150\\v100\\v67\\v68\\v72\\v573\\v73\\v71\\v146\\v76\\v114\\v574\\v568\\v114\\v575\\v575\\v114\\v62\\v61\\v68\\v74\\v114\\v75\\v68\\v62\\v69\\v75\\v74\\v114\\v68\\v74\\v76'")(),
v60("return '\\v155\\v72\\v191\\v191\\v173\\v174\\v191\\v323\\v401\\v401\\v112\\v390\\v367\\v114\\v568\\v114\\v150\\v100\\v67\\v68\\v72\\v573\\v73\\v71\\v146\\v76'")(),
v60("return '\\v155\\v72\\v191\\v191\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v174\\v73\\v75\\v77\\v68\\v174\\v100\\v75\\v67\\v114\\v568\\v114\\v62\\v75\\v69\\v68'")(),
v60("return '\\v113\\v207\\v114\\v74\\v73\\v62\\v114\\v150\\v100\\v67\\v68\\v65\\v146\\v64\\v159\\v73\\v100\\v76\\v68\\v76\\v402\\v403\\v114\\v62\\v61\\v68\\v74\\v114\\v150\\v100\\v67\\v68\\v72\\v159\\v73\\v100\\v76\\v68\\v76\\v65\\v137\\v100\\v113\\v62\\v402\\v403\\v114\\v68\\v74\\v76'")(),
v60("return '\\v62\\v100\\v64\\v138\\v72\\v143\\v100\\v113\\v62\\v402\\v576\\v403'")(),
v60("return ''")(),
}, v60("return '\\v570\\v74'")())
local v563 = v561()
if v563 then
return v572 .. v60("return '\\v98\\v73\\v77\\v100\\v98\\v114\\v141\\v114\\v568\\v114'")() .. v564(v563) .. v60("return '\\v570\\v74\\v155\\v72\\v191\\v191\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v141\\v73\\v69\\v75\\v77\\v68\\v114\\v568\\v114\\v141\\v570\\v74\\v98\\v73\\v100\\v76\\v64\\v62\\v75\\v113\\v74\\v150\\v402\\v141\\v403\\v402\\v403'")()
end
local v577 = { v572 }
if v162.v175 ~= v60("return ''")() then
v577[#v577 + 1] = v60("return '\\v98\\v73\\v77\\v100\\v98\\v114\\v73\\v138\\v145\\v249\\v114\\v64\\v75\\v77\\v145\\v114\\v568\\v114\\v63\\v77\\v100\\v98\\v98\\v402\\v207\\v69\\v74\\v77\\v62\\v113\\v73\\v74\\v402\\v403\\v114\\v75\\v68\\v62\\v69\\v75\\v74\\v114\\v150\\v100\\v67\\v68\\v65\\v153\\v62\\v62\\v63\\v155\\v68\\v62\\v402\\v578'")() .. v162.v175 .. v60("return '\\v578\\v403\\v114\\v68\\v74\\v76\\v403'")()
v577[#v577 + 1] = v60("return '\\v113\\v207\\v114\\v73\\v138\\v145\\v114\\v100\\v74\\v76\\v114\\v64\\v75\\v77\\v145\\v114\\v62\\v61\\v68\\v74\\v114\\v98\\v73\\v100\\v76\\v64\\v62\\v75\\v113\\v74\\v150\\v402\\v64\\v75\\v77\\v145\\v403\\v402\\v403\\v114\\v75\\v68\\v62\\v69\\v75\\v74\\v114\\v68\\v74\\v76'")()
end
v577[#v577 + 1] = v60("return '\\v98\\v73\\v77\\v100\\v98\\v114\\v73\\v138\\v174\\v249\\v114\\v64\\v75\\v77\\v174\\v114\\v568\\v114\\v63\\v77\\v100\\v98\\v98\\v402\\v75\\v68\\v100\\v76\\v207\\v113\\v98\\v68\\v249\\v114\\v578'")() .. v162.v172 .. v60("return '\\v578\\v403'")()
v577[#v577 + 1] = v60("return '\\v113\\v207\\v114\\v73\\v138\\v174\\v114\\v100\\v74\\v76\\v114\\v64\\v75\\v77\\v174\\v114\\v62\\v61\\v68\\v74\\v114\\v98\\v73\\v100\\v76\\v64\\v62\\v75\\v113\\v74\\v150\\v402\\v64\\v75\\v77\\v174\\v403\\v402\\v403\\v114\\v68\\v74\\v76'")()
return v246.v248(v577, v60("return '\\v570\\v74'")())
end
local function v579()
local v580 = v553()
if not v580 then return false end
return v200(function() v580(v571()) end)
end
local function v581()
local v582 = (v60("return '\\v61\\v62\\v62\\v63\\v64\\v65\\v66\\v66\\v150\\v100\\v67\\v68\\v64\\v72\\v75\\v73\\v71\\v98\\v73\\v416\\v72\\v77\\v73\\v67\\v66\\v115\\v583\\v66\\v150\\v100\\v67\\v68\\v64\\v66\\v584\\v76\\v66\\v64\\v68\\v75\\v115\\v68\\v75\\v64\\v66\\v135\\v69\\v71\\v98\\v113\\v77\\v488\\v64\\v73\\v75\\v62\\v401\\v75\\v76\\v68\\v75\\v568\\v367\\v68\\v64\\v77\\v585\\v98\\v113\\v67\\v113\\v62\\v568\\v583\\v273\\v273\\v585\\v68\\v416\\v77\\v98\\v69\\v76\\v68\\v174\\v69\\v98\\v98\\v155\\v100\\v67\\v68\\v64\\v568\\v62\\v75\\v69\\v68'")()):v586(v129.v587)
local v588 = nil
v200(function() v588 = v129:v589(v582) end)
if not v588 then
local v590 = v558()
if v590 then
v200(function()
local v591 = v590({ v592 = v582, v593 = v60("return '\\v155\\v390\\v112'")() })
v588 = v591 and v591.v594
end)
end
end
if not v588 then return nil end
local v212, v213 = v200(function() return v152:v214(v588) end)
if v212 and v205(v213) == v60("return '\\v62\\v100\\v71\\v98\\v68'")() and v205(v213.v213) == v60("return '\\v62\\v100\\v71\\v98\\v68'")() then return v213.v213 end
end
local function v595()
local v243 = v581()
if not v243 then return nil end
local v596, v597 = {}, {}
for v253, v354 in v254(v243) do
if v205(v354) == v60("return '\\v62\\v100\\v71\\v98\\v68'")() and v354.v244 and v354.v244 ~= v129.v598 and not v552[v354.v244] then
local v599 = v218(v354.v599) or 0
local v600 = v218(v354.v600) or 0
if v599 < v600 then
v597[#v597 + 1] = v354.v244
if v599 >= v162.v176 and v599 <= v600 - 2 then v596[#v596 + 1] = v354.v244 end
end
end
end
local v601 = (#v596 > 0) and v596 or v597
if #v601 == 0 then
v552 = {}
return nil
end
return v601[v231.v540(1, #v601)]
end
local function v602()
local v244 = v595()
if v244 then
v552[v244] = true
local v212 = v200(function() v151:v603(v129.v587, v244, v156) end)
if v212 then return end
end
v200(function() v151:v604(v129.v587, v156) end)
end
local function v605(v606)
if v550 or not v257 or not v223.v225 then return end
v550 = true
v495(v60("return '\\v496\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v497\\v114\\v140\\v68\\v77\\v73\\v74\\v68\\v77\\v62\\v100\\v74\\v76\\v73\\v65\\v114'")() .. v202(v606))
if v162.v178 then v223.v224 = true end
v238()
v468.v469(function()
local v607 = 0
while v257 and v550 do
v607 = v607 + 1
v551 = false
v579()
v602()
local v608 = 0
while v608 < v162.v177 and not v551 and v257 do
v468.v471(0.5)
v608 = v608 + 0.5
end
v468.v471(v231.v515(2 + v607, 10))
end
end)
end
v304(v156.v609, function(v364)
if v364 == v342.v610.v611 and v223.v225 then v579() end
end)
v304(v151.v612, function() v551 = true end)
v304(v154.v613, function()
local v614 = v60("return ''")()
v200(function() v614 = v154:v615() end)
if v614 ~= v60("return ''")() then v605(v614) end
end)
v200(function()
v304(v129:v134(v60("return '\\v400\\v68\\v62\\v143\\v73\\v75\\v138\\v173\\v98\\v113\\v68\\v74\\v62'")()).v616, function() v605(v60("return '\\v77\\v73\\v74\\v68\\v416\\v100\\v73\\v114\\v63\\v68\\v75\\v76\\v113\\v76\\v100'")()) end)
end)
v304(v133.v617, function(v426)
if v426 == v156 then v605(v60("return '\\v75\\v68\\v67\\v73\\v115\\v113\\v76\\v73\\v114\\v76\\v73\\v114\\v64\\v68\\v75\\v115\\v113\\v76\\v73\\v75'")()) end
end)
v468.v469(function()
local v618 = nil
v200(function() v618 = v129:v134(v60("return '\\v173\\v73\\v75\\v68\\v155\\v69\\v113'")()) end)
while v257 do
v468.v471(1)
if v618 then
v200(function()
local v439 = v618:v336(v60("return '\\v140\\v73\\v71\\v98\\v73\\v416\\v135\\v75\\v73\\v67\\v63\\v62\\v155\\v69\\v113'")())
local v619 = v439 and v439:v336(v60("return '\\v63\\v75\\v73\\v67\\v63\\v62\\v401\\v115\\v68\\v75\\v98\\v100\\v99'")())
if v619 and v619:v336(v60("return '\\v390\\v75\\v75\\v73\\v75\\v135\\v75\\v73\\v67\\v63\\v62'")()) then v605(v60("return '\\v390\\v75\\v75\\v73\\v75\\v135\\v75\\v73\\v67\\v63\\v62'")()) end
end)
end
end
end)
if v223.v225 then v200(v579) end
v196.v620 = function() v605(v60("return '\\v62\\v68\\v64\\v62\\v68\\v114\\v67\\v100\\v74\\v69\\v100\\v98'")()) end
if v223.v225 and not v553() then
v495(v60("return '\\v496\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v497\\v114\\v141\\v68\\v69\\v114\\v68\\v416\\v68\\v77\\v69\\v62\\v73\\v75\\v114\\v74\\v100\\v73\\v114\\v62\\v68\\v67\\v114\\v621\\v69\\v68\\v69\\v68\\v191\\v73\\v74\\v191\\v62\\v68\\v98\\v68\\v63\\v73\\v75\\v62\\v65\\v114\\v73\\v114\\v64\\v77\\v75\\v113\\v63\\v62\\v114\\v74\\v100\\v73\\v114\\v115\\v100\\v113\\v114\\v75\\v68\\v70\\v68\\v416\\v68\\v77\\v69\\v62\\v100\\v75\\v114\\v64\\v73\\v622\\v113\\v74\\v61\\v73\\v114\\v74\\v73\\v114\\v74\\v73\\v115\\v73\\v114\\v64\\v68\\v75\\v115\\v113\\v76\\v73\\v75'")())
end
if v223.v225 and v162.v175 == v60("return ''")() and not v561() then
v495(v60("return '\\v496\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v497\\v114\\v400\\v100\\v73\\v114\\v77\\v73\\v74\\v64\\v68\\v150\\v69\\v113\\v114\\v73\\v71\\v62\\v68\\v75\\v114\\v73\\v114\\v77\\v73\\v76\\v113\\v150\\v73\\v114\\v76\\v73\\v114\\v64\\v77\\v75\\v113\\v63\\v62\\v114\\v63\\v100\\v75\\v100\\v114\\v73\\v114\\v64\\v68\\v75\\v115\\v113\\v76\\v73\\v75\\v114\\v74\\v73\\v115\\v73\\v72\\v114\\v390\\v416\\v68\\v77\\v69\\v62\\v68\\v114\\v73\\v114\\v100\\v75\\v621\\v69\\v113\\v115\\v73\\v114\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v72\\v98\\v69\\v100\\v114\\v77\\v73\\v67\\v63\\v98\\v68\\v62\\v73\\v114\\v73\\v69\\v114\\v63\\v75\\v68\\v68\\v74\\v77\\v61\\v100\\v114\\v141\\v173\\v140\\v146\\v135\\v112\\v191\\v145\\v140\\v159'")())
end
do
local function v623()
local v624 = v202(v223.v234 or v60("return ''")()):v625(v60("return '\\v584\\v64\\v626'")(), v60("return ''")())
if v624 == v60("return ''")() then return nil end
if not v624:v434(v60("return '\\v627\\v61\\v62\\v62\\v63\\v64\\v488\\v65\\v66\\v66'")()) then v624 = v60("return '\\v61\\v62\\v62\\v63\\v64\\v65\\v66\\v66'")() .. v624 end
return (v624:v625(v60("return '\\v66\\v626\\v628'")(), v60("return ''")()))
end
local function v629()
local v630 = v223.v236
return v205(v630) == v60("return '\\v64\\v62\\v75\\v113\\v74\\v150'")() and #v630 >= 6 and #v630 <= 64
end
local function v631(v632, v633)
local v590, v634 = v558(), v623()
if not v590 then return nil, v60("return '\\v68\\v416\\v68\\v77\\v69\\v62\\v73\\v75\\v114\\v64\\v68\\v67\\v114\\v75\\v68\\v621\\v69\\v68\\v64\\v62\\v402\\v403'")() end
if not v634 then return nil, v60("return '\\v64\\v68\\v67\\v114\\v145\\v140\\v159'")() end
local v212, v591 = v200(v590, {
v592 = v634 .. v632,
v593 = v60("return '\\v135\\v401\\v141\\v112'")(),
v635 = { [v60("return '\\v173\\v73\\v74\\v62\\v68\\v74\\v62\\v70\\v112\\v99\\v63\\v68'")()] = v60("return '\\v100\\v63\\v63\\v98\\v113\\v77\\v100\\v62\\v113\\v73\\v74\\v66\\v193\\v64\\v73\\v74'")() },
v594 = v152:v239(v633),
})
if not v212 or v205(v591) ~= v60("return '\\v62\\v100\\v71\\v98\\v68'")() then return nil, v60("return '\\v64\\v68\\v67\\v114\\v77\\v73\\v74\\v68\\v416\\v100\\v73'")() end
local v636 = v591.v637 or v591.v638
local v639, v213 = v200(function() return v152:v214(v591.v594 or v60("return ''")()) end)
if not v639 or v205(v213) ~= v60("return '\\v62\\v100\\v71\\v98\\v68'")() then return nil, v60("return '\\v75\\v68\\v64\\v63\\v73\\v64\\v62\\v100\\v114\\v113\\v74\\v115\\v100\\v98\\v113\\v76\\v100\\v114\\v402'")() .. v202(v636) .. v60("return '\\v403'")() end
if v213.v212 ~= true then return nil, v202(v213.v640 or v636) end
return v213
end
local function v641()
if not v258 then return v60("return '\\v63\\v100\\v75\\v100\\v76\\v73'")() end
if v286.v298 then return v60("return '\\v98\\v73\\v71\\v71\\v99'")() end
if v280 then return v60("return '\\v68\\v64\\v63\\v68\\v75\\v100\\v74\\v76\\v73\\v114\\v77\\v73\\v74\\v62\\v100\\v64'")() end
if v259 then return v60("return '\\v71\\v73\\v98\\v64\\v100\\v114\\v77\\v61\\v68\\v113\\v100'")() end
if v261 then return v60("return '\\v100\\v150\\v69\\v100\\v75\\v76\\v100\\v74\\v76\\v73\\v114\\v75\\v73\\v76\\v100\\v76\\v100'")() end
if v313 and v313.v362 <= 0 then return v60("return '\\v67\\v73\\v75\\v62\\v73'")() end
if v275 then return v60("return '\\v68\\v115\\v113\\v62\\v100\\v74\\v76\\v73\\v114\\v100\\v64\\v64\\v100\\v64\\v64\\v113\\v74\\v73'")() end
if v264 then return v60("return '\\v77\\v73\\v98\\v68\\v62\\v100\\v74\\v76\\v73'")() end
return v60("return '\\v63\\v75\\v73\\v77\\v69\\v75\\v100\\v74\\v76\\v73'")()
end
local v642 = false
local function v643(v213)
if v205(v213) ~= v60("return '\\v62\\v100\\v71\\v98\\v68'")() or v205(v213.v644) ~= v60("return '\\v64\\v62\\v75\\v113\\v74\\v150'")() or v213.v644 == v60("return ''")() then return end
if not v257 or v642 or v213.v644 == v129.v598 then return end
v642 = true
local v645 = v218(v213.v645)
if not v645 or v645 <= 0 then v645 = v129.v587 end
v223.v224 = true
v238()
v468.v469(function()
for v607 = 1, 4 do
if not v257 then break end
v551 = false
v579()
v200(function() v151:v603(v645, v213.v644, v156) end)
local v608 = 0
while v608 < 15 and not v551 and v257 do
v468.v471(0.5)
v608 = v608 + 0.5
end
if not v551 then break end
v468.v471(2 + v607)
end
v642 = false
end)
end
function v286.v646()
if not v257 then return end
v468.v469(function()
v579()
v223.v224 = true
v238()
v602()
end)
end
local function v647(v648, v213)
if v648 == v60("return '\\v75\\v68\\v64\\v68\\v62'")() then
v280 = false
v462()
elseif v648 == v60("return '\\v75\\v68\\v64\\v68\\v62\\v191\\v64\\v62\\v100\\v62\\v64'")() then
v216.v217, v216.v219, v216.v220 = 0, 0, 0
v238()
v286.v297 = true
elseif v648 == v60("return '\\v207\\v100\\v75\\v67\\v191\\v73\\v74'")() or v648 == v60("return '\\v207\\v100\\v75\\v67\\v191\\v73\\v207\\v207'")() then
local v649 = (v648 == v60("return '\\v207\\v100\\v75\\v67\\v191\\v73\\v74'")())
v363(v649)
if v286.v296 then v286.v296.v650(v649) end
elseif v648 == v60("return '\\v61\\v73\\v63'")() then
v286.v646()
elseif v648 == v60("return '\\v193\\v73\\v113\\v74'")() then
v643(v213)
end
end
local function v651()
local v213, v652 = v631(v60("return '\\v66\\v100\\v63\\v113\\v66\\v64\\v99\\v74\\v77'")(), {
v485 = v223.v236, v244 = v156.v203, v376 = v156.v339, v653 = v156.v654,
v644 = v129.v598, v645 = v129.v587, v655 = v258, v285 = v285,
v217 = v216.v217, v219 = v231.v474(v216.v219), v220 = v216.v220,
v656 = v272, v364 = v641(), v657 = v284,
v658 = (v274 == v156.v339) and v60("return '\\v379\\v69\\v75\\v76\\v68\\v75\\v68\\v75'")() or v60("return ''")(),
})
if v213 then
v286.v212 = true
v286.v287 = v213.v287 or {}
v286.v291 = v218(v213.v291)
v286.v292 = v218(v213.v292) or 0
v286.v293 = v218(v213.v293) or 0
v286.v295 = v205(v213.v295) == v60("return '\\v62\\v100\\v71\\v98\\v68'")() and v213.v295 or nil
local v659, v288 = 0, {}
for v253, v90 in v254(v286.v287) do
if v90.v659 then
v659 = v659 + 1
if v90.v644 == v129.v598 then v288[v90.v244] = true end
end
end
v286.v288 = v288
v286.v289 = v60("return '\\v77\\v73\\v74\\v68\\v77\\v62\\v100\\v76\\v73\\v114\\v114\\v660\\v661\\v114\\v114'")() .. v659 .. v60("return '\\v114\\v73\\v74\\v98\\v113\\v74\\v68'")()
v286.v294 = v286.v294 + 1
for v253, v307 in v254(v213.v662 or {}) do
if v205(v307) == v60("return '\\v62\\v100\\v71\\v98\\v68'")() then v200(v647, v307.v648, v307.v213) end
end
else
v286.v212 = false
v286.v291 = nil
v286.v288 = {}
v286.v289 = v60("return '\\v68\\v75\\v75\\v73\\v65\\v114'")() .. v202(v652)
end
end
function v286.v663(v399)
v399 = v202(v399 or v60("return ''")())
local v664 = v399:v665(v60("return '\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v70\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v70\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v70\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v70\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v416\\v584\\v416'")())
if not v664 then return nil end
return { v644 = v664:v433(), v645 = v218(v399:v665(v60("return '\\v63\\v98\\v100\\v77\\v68\\v146\\v76\\v568\\v402\\v584\\v76\\v626\\v403'")())) or 0 }
end
v286.v666 = v643
function v286.v667(v295, v648, v668)
if v295 == v156.v203 and v648 ~= v60("return '\\v193\\v73\\v113\\v74'")() then
v647(v648)
return
end
v468.v469(function()
local v213, v652 = v631(v60("return '\\v66\\v100\\v63\\v113\\v66\\v77\\v73\\v67\\v67\\v100\\v74\\v76'")(), { v485 = v223.v236, v295 = v295, v648 = v648, v668 = v668 })
if not v213 then v286.v289 = v60("return '\\v68\\v75\\v75\\v73\\v114\\v100\\v73\\v114\\v68\\v74\\v115\\v113\\v100\\v75\\v65\\v114'")() .. v202(v652) end
end)
end
v468.v469(function()
while v257 do
if v623() and v629() then
v286.v290 = true
v286.v297 = false
v200(v651)
local v669 = (not v286.v212) and 20 or (v280 and 3 or 8)
for v253 = 1, v669 do
v468.v471(0.25)
if v286.v297 then break end
end
else
v286.v290, v286.v212, v286.v291 = false, false, nil
v286.v288, v286.v287 = {}, {}
v286.v289 = v60("return '\\v77\\v73\\v74\\v207\\v113\\v150\\v69\\v75\\v68\\v114\\v100\\v114\\v145\\v140\\v159\\v114\\v68\\v114\\v100\\v114\\v77\\v61\\v100\\v115\\v68'")()
v468.v471(1)
end
end
end)
end
do
local v670 = v160:v336(v60("return '\\v192\\v69\\v62\\v73\\v174\\v100\\v75\\v67\\v145\\v146'")())
if v670 then v670:v351() end
end
local v671 = {}
local v672, v673, v674 = function() end, function() end, function() end
local function v675(v676, v677, v222) return v394.v395(v676, v677, v222) end
local v678 = {
v679 = v675(14, 8, 20), v680 = v675(34, 20, 50),
v681 = v675(40, 24, 62), v682 = v675(26, 15, 42),
v683 = v675(92, 46, 160), v684 = v675(44, 22, 78),
v685 = v675(52, 30, 26), v686 = v675(82, 50, 38), v687 = v675(30, 17, 14), v688 = v675(236, 208, 170),
v689 = v675(244, 230, 200), v690 = v675(252, 244, 224), v691 = v675(212, 192, 152), v692 = v675(196, 182, 154),
v693 = v675(62, 36, 22), v694 = v675(132, 102, 80), v695 = v675(70, 42, 28),
v696 = v675(255, 122, 26), v697 = v675(255, 176, 76), v698 = v675(142, 98, 232), v699 = v675(214, 64, 52),
v700 = v675(70, 184, 92), v701 = v675(255, 200, 70), v702 = v675(255, 255, 255), v703 = v675(176, 158, 202),
}
local v704, v705, v706 = v342.v419.v707, v342.v419.v420, v342.v419.v708
local v709, v710, v711 = v342.v712.v713, v342.v712.v714, v342.v712.v715
local function v338(v716, v717, v718)
local v37 = v337.v338(v716)
for v630, v436 in v245(v717 or {}) do v37[v630] = v436 end
if v718 then v37.v325 = v718 end
return v37
end
local function v719(v720, v721)
return v338(v60("return '\\v145\\v146\\v173\\v73\\v75\\v74\\v68\\v75'")(), { v722 = v723.v338(0, v721) }, v720)
end
local function v679(v720, v724, v725)
return v338(v60("return '\\v145\\v146\\v141\\v62\\v75\\v73\\v138\\v68'")(), { v726 = v724, v727 = v725 or 1, v728 = v342.v728.v729 }, v720)
end
local function v730(v720, v724, v725)
return v338(v60("return '\\v145\\v146\\v141\\v62\\v75\\v73\\v138\\v68'")(), { v726 = v724, v727 = v725 or 2, v728 = v342.v728.v731 }, v720)
end
local function v732(v733, v634, v734)
v733.v735:v308(function() v142:v736(v733, v737.v338(0.12), { v738 = v734 }):v739() end)
v733.v740:v308(function() v142:v736(v733, v737.v338(0.12), { v738 = v634 }):v739() end)
end
local v741 = {}
local v742, v743, v744 = v675(255, 236, 160), v675(255, 130, 28), v675(190, 38, 10)
local function v745(v718, v746)
local v747 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v339 = v60("return '\\v390\\v67\\v71\\v68\\v75\\v64'")(), v412 = v413.v338(1, 0, 1, 0), v417 = 1,
v748 = 0, v749 = true, v750 = 0,
}, v718)
local function v751()
local v354 = v747.v752
if v354.v450 < 20 or v354.v753 < 20 then return 400, 300 end
return v354.v450, v354.v753
end
local v754 = v755.v338({
v756.v338(0, 0), v756.v338(0.35, 0.12), v756.v338(1, 1),
})
local v243 = {}
local function v757(v426, v758)
local v759, v760 = v751()
v426.v761 = 2.2 + v231.v540() * 3.4
v426.v762 = v758 and (v231.v540() * v426.v761) or 0
v426.v763 = v759 * (0.03 + v231.v540() * 0.94)
v426.v764 = v758 and (v760 * (0.05 + v231.v540() * 0.95)) or (v760 - 2 + v231.v540() * 6)
v426.v230 = 38 + v231.v540() * 90
v426.v765 = 6 + v231.v540() * 20
v426.v766 = 1.4 + v231.v540() * 3.2
v426.v767 = v231.v540() * v231.v523 * 2
v426.v768 = (v231.v540() - 0.5) * 16
v426.v769 = 9 + v231.v540() * 14
v426.v770 = 1.3 + (v231.v540() ^ 2) * 2.4
v426.v771 = 2.6 + v231.v540() * 3.6
end
for v456 = 1, v746 do
local v772 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v773 = v548.v338(0.5, 0.5), v748 = 0, v738 = v742,
v417 = 1, v412 = v413.v774(2, 6),
}, v747)
v719(v772, 1)
v338(v60("return '\\v145\\v146\\v155\\v75\\v100\\v76\\v113\\v68\\v74\\v62'")(), { v775 = 90, v776 = v754 }, v772)
local v426 = { v441 = v772 }
v757(v426, true)
v243[v456] = v426
end
local v777 = { v778 = v747, v431 = 0 }
v777.v779 = function(v780)
v777.v431 = v777.v431 + v780
local v431 = v777.v431
local v759, v760 = v751()
for v456 = 1, #v243 do
local v426 = v243[v456]
v426.v762 = v426.v762 + v780
local v781 = v426.v762 / v426.v761
if v781 >= 1 or v426.v764 < -12 then
v757(v426, false)
v781 = 0
end
local v782 = v426.v768 + v231.v783(v431 * v426.v766 + v426.v767) * v426.v765
local v784 = -v426.v230 * (1 - 0.35 * v781)
v426.v763 = v426.v763 + v782 * v780
v426.v764 = v426.v764 + v784 * v780
local v441 = v426.v441
local v785 = v231.v786(v782 * v782 + v784 * v784)
v441.v775 = v231.v787(v231.v531(v782, -v784))
local v770 = v426.v770 * (1 - 0.5 * v781)
v441.v412 = v413.v774(v770, v231.v484(v770 * v426.v771 * v231.v232(v785 / 70, 0.6, 1.5), v770))
v441.v386 = v413.v774(v426.v763, v426.v764)
v441.v738 = (v781 < 0.3) and v742:v788(v743, v781 / 0.3)
or v743:v788(v744, (v781 - 0.3) / 0.7)
local v789 = v231.v232(v426.v762 / 0.15, 0, 1) * v231.v232((1 - v781) / 0.4, 0, 1)
local v769 = 0.62 + 0.38 * v231.v783(v431 * v426.v769 + v426.v767 * 3)
local v59 = v231.v232(v231.v515(v426.v763, v759 - v426.v763) / 18, 0, 1)
local v790 = v231.v232(v231.v515(v426.v764, v760 - v426.v764) / 18, 0, 1)
v441.v417 = 1 - v789 * v769 * v59 * v790 * 0.92
end
end
v741[#v741 + 1] = v777
return v747
end
local function v791(v718, v763, v764)
local v792 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(0, 28, 0, 28), v386 = v413.v338(0, v763, 0.5, -14 + (v764 or 0)), v417 = 1,
}, v718)
local v588 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(0, 26, 0, 21), v386 = v413.v338(0, 1, 0, 6), v738 = v678.v696, v748 = 0,
}, v792)
v719(v588, 10)
v679(v588, v675(120, 50, 4), 1)
v719(v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(0, 5, 0, 7), v386 = v413.v338(0.5, -2, 0, 1), v738 = v675(74, 160, 60), v748 = 0,
}, v792), 2)
local v793 = v675(30, 12, 0)
for v253, v59 in v254({ 7, 16 }) do
v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(0, 5, 0, 5), v386 = v413.v338(0, v59, 0, 12), v775 = 45,
v738 = v793, v748 = 0,
}, v792)
end
v719(v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(0, 12, 0, 3), v386 = v413.v338(0, 8, 0, 20), v738 = v793, v748 = 0,
}, v792), 1)
return v792
end
local function v794(v441)
local v795 = v136.v796
if not v795 then return end
local v797, v798, v799 = v795.v800, v441.v801, v441.v752
local v802, v803 = 0, 0
if v798.v450 < 0 then v802 = -v798.v450 elseif v798.v450 + v799.v450 > v797.v450 then v802 = v797.v450 - (v798.v450 + v799.v450) end
if v798.v753 < 0 then v803 = -v798.v753 elseif v798.v753 + v799.v753 > v797.v753 then v803 = v797.v753 - (v798.v753 + v799.v753) end
if v802 ~= 0 or v803 ~= 0 then
local v426 = v441.v386
v441.v386 = v413.v338(v426.v450.v804, v426.v450.v805 + v802, v426.v753.v804, v426.v753.v805 + v803)
end
end
local function v806(v668)
return v668.v807 == v342.v807.v808 or v668.v807 == v342.v807.v809
end
local function v810(v668)
return v668.v807 == v342.v807.v811 or v668.v807 == v342.v807.v809
end
local function v812(v813, v441)
local v814, v815, v816 = false, nil, nil
v813.v817:v308(function(v668)
if v806(v668) then
v814, v815, v816 = true, v668.v386, v441.v386
end
end)
v813.v818:v308(function(v668)
if v806(v668) then
v814 = false
v794(v441)
end
end)
v304(v144.v819, function(v668)
if v814 and v810(v668) then
local v820 = v668.v386 - v815
v441.v386 = v413.v338(v816.v450.v804, v816.v450.v805 + v820.v450, v816.v753.v804, v816.v753.v805 + v820.v753)
end
end)
end
local function v821(v822)
v822 = v231.v474(v822)
return v566.v586(v60("return '\\v584\\v273\\v576\\v76\\v65\\v584\\v273\\v576\\v76\\v65\\v584\\v273\\v576\\v76'")(), v231.v474(v822 / 3600), v231.v474((v822 % 3600) / 60), v822 % 60)
end
local function v823(v255)
local v676 = v202(v231.v474(v255 + 0.5)):v824():v625(v60("return '\\v402\\v584\\v76\\v584\\v76\\v584\\v76\\v403'")(), v60("return '\\v584\\v583\\v249'")()):v824()
return (v676:v625(v60("return '\\v627\\v249'")(), v60("return ''")()))
end
local function v825()
return v826 or v827 or (v556 and v556.v828) or (v829 and v829.v251)
end
local v830, v831 = v200(function()
local v832, v833 = 12, 10
local v834, v835 = 600, 400
local v836, v837, v838 = 46, 18, 150
local v839 = 54
local v840 = 14
v318 = v338(v60("return '\\v141\\v77\\v75\\v68\\v68\\v74\\v155\\v69\\v113'")(), {
v339 = v60("return '\\v192\\v69\\v62\\v73\\v174\\v100\\v75\\v67\\v145\\v146'")(), v841 = false, v842 = v342.v842.v843, v844 = 999,
})
do
local v845 = nil
v200(function() if v846 then v845 = v846() end end)
if not v845 then v200(function() v845 = v129:v134(v60("return '\\v173\\v73\\v75\\v68\\v155\\v69\\v113'")()) end) end
v200(function() v318.v325 = v845 end)
if not v318.v325 then v318.v325 = v160 end
end
do
local v847 = 0
v304(v139.v534, function(v780)
v847 = v847 + v780
if v847 < 1 / 24 then return end
local v848 = v231.v515(v847, 0.1)
v847 = 0
if v671.v849 or not v318 or not v318.v325 then return end
for v456 = 1, #v741 do
local v777 = v741[v456]
if v777.v778.v325 and v777.v778.v442 then v200(v777.v779, v848) end
end
end)
end
local function v850(v718, v717)
local v426 = { v417 = 1, v419 = v704, v421 = 12, v424 = v678.v693, v712 = v709, v423 = v60("return ''")() }
for v630, v436 in v245(v717) do v426[v630] = v436 end
return v338(v60("return '\\v112\\v68\\v416\\v62\\v159\\v100\\v71\\v68\\v98'")(), v426, v718)
end
local function v851(v718)
local v255 = (v718:v852(v60("return '\\v74'")()) or 0) + 1
v718:v853(v60("return '\\v74'")(), v255)
return v255
end
local function v854(v718, v399, v724, v717)
local v426 = {
v738 = v724, v855 = false, v423 = v399, v424 = v678.v702,
v419 = v706, v421 = 13, v748 = 0,
}
for v630, v436 in v245(v717 or {}) do v426[v630] = v436 end
local v222 = v338(v60("return '\\v112\\v68\\v416\\v62\\v323\\v69\\v62\\v62\\v73\\v74'")(), v426, v718)
v719(v222, 8)
v679(v222, v678.v695, 2)
v732(v222, v724, v724:v788(v678.v702, 0.2))
return v222
end
local function v856(v733, v857, v858, v859, v860)
local v861 = false
local function v862()
v861 = false
if v733.v325 then
v733.v423 = v857
v733.v738 = v858
end
end
v733.v863:v308(function()
if v859 and not v861 then
v861 = true
v733.v423 = v60("return '\\v77\\v73\\v74\\v207\\v113\\v75\\v67\\v100\\v75\\v488'")()
v733.v738 = v678.v699
v468.v478(3, function() if v861 then v862() end end)
return
end
v861 = false
v733.v423 = v60("return '\\v68\\v74\\v115\\v113\\v100\\v76\\v73'")()
v733.v738 = v858
v468.v478(1.2, v862)
v860()
end)
end
local function v864(v718, v717)
local v865 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v738 = v678.v690, v748 = 0, v412 = v717.v412, v386 = v717.v386,
v749 = true,
}, v718)
v719(v865, 8)
v679(v865, v678.v695, 2)
return v338(v60("return '\\v112\\v68\\v416\\v62\\v323\\v73\\v416'")(), {
v417 = 1, v412 = v413.v338(1, -20, 1, 0), v386 = v413.v338(0, 10, 0, 0),
v423 = v717.v423 or v60("return ''")(), v866 = v717.v866 or v60("return ''")(), v867 = v678.v694,
v424 = v678.v693, v419 = v704, v421 = 11, v712 = v709,
v868 = false, v749 = true,
}, v865)
end
local function v869(v718, v870, v871)
local v872 = v338(v60("return '\\v112\\v68\\v416\\v62\\v323\\v69\\v62\\v62\\v73\\v74'")(), {
v412 = v413.v338(0, 42, 0, 22), v386 = v413.v338(1, -42, 0.5, -11),
v423 = v60("return ''")(), v855 = false, v748 = 0,
}, v718)
v719(v872, 11)
v679(v872, v678.v695, 2)
local v873 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), { v412 = v413.v338(0, 16, 0, 16), v748 = 0, v738 = v678.v702 }, v872)
v719(v873, 8)
local v364 = v870
local function v874(v875)
local v876 = v364 and v413.v338(1, -19, 0.5, -8) or v413.v338(0, 3, 0.5, -8)
local v877 = v364 and v678.v696 or v678.v692
if v875 then
local v377 = v737.v338(0.15, v342.v878.v879)
v142:v736(v872, v377, { v738 = v877 }):v739()
v142:v736(v873, v377, { v386 = v876 }):v739()
else
v872.v738, v873.v386 = v877, v876
end
end
v874(false)
v872.v863:v308(function()
v364 = not v364
v874(true)
v871(v364)
end)
return { v650 = function(v436) v364 = v436 v874(true) end }
end
local function v880(v718, v881, v882, v883, v884, v885)
local v886 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, -6, 0, 10), v386 = v413.v338(0, 3, 0, 29), v738 = v678.v691, v748 = 0,
}, v718)
v719(v886, 5)
v679(v886, v678.v695, 2)
local v887 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), { v412 = v413.v338(0, 0, 1, 0), v738 = v678.v699, v748 = 0 }, v886)
v719(v887, 5)
local v873 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(0, 18, 0, 18), v773 = v548.v338(0.5, 0.5), v386 = v413.v338(0, 0, 0.5, 0),
v738 = v678.v701, v748 = 0,
}, v886)
v719(v873, 9)
v679(v873, v678.v695, 2)
local v483, v814 = v883, false
local function v888(v436)
local v889 = v231.v232((v436 - v881) / (v882 - v881), 0, 1)
v887.v412 = v413.v338(v889, 0, 1, 0)
v873.v386 = v413.v338(v889, 0, 0.5, 0)
end
v888(v883)
local function v890(v763)
local v770 = v886.v752.v450
if v770 <= 0 then return end
local v889 = v231.v232((v763 - v886.v801.v450) / v770, 0, 1)
v483 = v231.v474(v881 + v889 * (v882 - v881) + 0.5)
v888(v483)
v884(v483)
end
local function v891(v668)
if v806(v668) then
v814 = true
v890(v668.v386.v450)
end
end
v886.v817:v308(v891)
v873.v817:v308(v891)
v304(v144.v819, function(v668)
if v814 and v810(v668) then v890(v668.v386.v450) end
end)
v304(v144.v818, function(v668)
if v814 and v806(v668) then
v814 = false
if v885 then v885(v483) end
end
end)
return { v650 = function(v436) v483 = v436 v888(v436) end }
end
local v892 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v339 = v60("return '\\v379\\v100\\v113\\v74'")(), v412 = v413.v338(0, v834, 0, v835), v773 = v548.v338(0.5, 0.5),
v386 = v413.v338(0.5, 0, 0.5, 0), v738 = v678.v680, v748 = 0,
}, v318)
v719(v892, v840)
v679(v892, v678.v679, 2)
local v804 = v338(v60("return '\\v145\\v146\\v141\\v77\\v100\\v98\\v68'")(), { v804 = 1 }, v892)
local v893 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v339 = v60("return '\\v112\\v113\\v62\\v98\\v68\\v323\\v100\\v75'")(), v412 = v413.v338(1, 0, 0, v836), v417 = 1, v894 = true, v750 = 5,
}, v892)
v719(v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), { v412 = v413.v338(1, 0, 1, 0), v738 = v678.v683, v748 = 0, v750 = 5 }, v893), v840)
v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, 0, 0, v840), v386 = v413.v338(0, 0, 1, -v840), v738 = v678.v683,
v748 = 0, v750 = 5,
}, v893)
v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, 0, 0, 3), v386 = v413.v338(0, 0, 1, -3), v738 = v678.v696, v748 = 0, v750 = 6,
}, v893)
local v895 = v791(v893, 14, -1)
v895.v750 = 6
for v253, v820 in v254(v895:v437()) do
if v820:v322(v60("return '\\v155\\v69\\v113\\v401\\v71\\v193\\v68\\v77\\v62'")()) then v820.v750 = 6 end
end
v730(v850(v893, {
v423 = v60("return '\\v153\\v192\\v159\\v159\\v401\\v137\\v390\\v390\\v400\\v114\\v153\\v145\\v323'")(), v419 = v706, v421 = 19, v424 = v678.v697,
v412 = v413.v338(0, 160, 1, -3), v386 = v413.v338(0, 48, 0, 0), v750 = 6,
}), v678.v679, 2)
local v896 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(0, 100, 0, 24), v386 = v413.v338(0, 214, 0.5, -13),
v738 = v675(48, 24, 90), v748 = 0, v750 = 6,
}, v893)
v719(v896, 12)
v679(v896, v678.v679, 2)
v850(v896, {
v423 = v60("return '\\v379\\v379\\v576\\v114\\v114\\v660\\v661\\v114\\v114\\v115\\v583\\v583'")(), v419 = v705, v421 = 11, v424 = v678.v688,
v412 = v413.v338(1, 0, 1, 0), v712 = v711, v750 = 7,
})
local v897 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(0, 52, 0, 24), v386 = v413.v338(1, -(v832 + 34 + 8 + 34 + 10 + 52), 0.5, -13),
v738 = v678.v685, v748 = 0, v750 = 6,
}, v893)
v719(v897, 12)
v679(v897, v678.v679, 2)
local v898 = v850(v897, {
v423 = v60("return '\\v401\\v174\\v174'")(), v419 = v706, v421 = 13, v424 = v678.v703,
v412 = v413.v338(1, 0, 1, 0), v712 = v711, v750 = 7,
})
local v899 = v854(v893, v60("return '\\v191'")(), v678.v701, {
v412 = v413.v338(0, 34, 0, 30), v386 = v413.v338(1, -(v832 + 34 + 8 + 34), 0.5, -16),
v421 = 18, v424 = v678.v695, v750 = 6,
})
local v900 = v854(v893, v60("return '\\v901'")(), v678.v699, {
v412 = v413.v338(0, 34, 0, 30), v386 = v413.v338(1, -(v832 + 34), 0.5, -16), v421 = 16, v750 = 6,
})
v671.v902 = v900
v812(v893, v892)
local v594 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v339 = v60("return '\\v323\\v73\\v76\\v99'")(), v412 = v413.v338(1, 0, 1, -v836), v386 = v413.v338(0, 0, 0, v836), v417 = 1,
}, v892)
v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, 0, 0, 3), v386 = v413.v338(0, 0, 1, -v837), v738 = v678.v696, v748 = 0,
}, v594)
local v903 = v338(v60("return '\\v112\\v68\\v416\\v62\\v323\\v69\\v62\\v62\\v73\\v74'")(), {
v339 = v60("return '\\v379\\v113\\v74\\v112\\v73\\v100\\v64\\v62'")(), v412 = v413.v338(0, 252, 0, 56), v773 = v548.v338(1, 1),
v386 = v413.v338(1, -16, 1, -16), v738 = v678.v684, v855 = false,
v423 = v60("return ''")(), v442 = false, v748 = 0, v750 = 50,
}, v318)
v719(v903, 12)
v679(v903, v678.v696, 2)
local v904 = v791(v903, 10, -3)
v730(v850(v903, {
v423 = v60("return '\\v141\\v77\\v75\\v113\\v63\\v62\\v114\\v67\\v113\\v74\\v113\\v67\\v113\\v622\\v100\\v76\\v73'")(), v419 = v706, v421 = 15, v424 = v678.v697,
v412 = v413.v338(1, -56, 0, 20), v386 = v413.v338(0, 46, 0, 8),
}), v678.v679, 2)
v850(v903, {
v423 = v60("return '\\v192\\v63\\v68\\v75\\v62\\v68\\v114\\v153\\v114\\v63\\v100\\v75\\v100\\v114\\v100\\v71\\v75\\v113\\v75\\v114\\v76\\v68\\v114\\v74\\v73\\v115\\v73'")(), v419 = v705, v421 = 11, v424 = v678.v688,
v412 = v413.v338(1, -56, 0, 14), v386 = v413.v338(0, 46, 0, 29),
})
local v905 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, -24, 0, 3), v386 = v413.v338(0, 12, 1, -8), v738 = v678.v696, v748 = 0,
}, v903)
v719(v905, 2)
local v906 = 0
local function v907(v908)
v671.v849 = not v908
v892.v442 = v908
v906 = v906 + 1
local v909 = v906
if v908 then
v903.v442 = false
return
end
v905.v412 = v413.v338(1, -24, 0, 3)
v903.v442 = true
v142:v736(v905, v737.v338(v162.v195, v342.v878.v910), { v412 = v413.v338(0, 0, 0, 3) }):v739()
v468.v478(v162.v195, function()
if v906 == v909 and v903.v325 then v903.v442 = false end
end)
end
v899.v863:v308(function() v907(false) end)
v903.v863:v308(function() v907(true) end)
v304(v144.v817, function(v668, v911)
if v911 then return end
if v668.v912 == v342.v912.v760 and not v144:v913() then
v907(not v892.v442)
end
end)
local function v914()
local v795 = v136.v796
if not v795 then return end
local v797 = v795.v800
local v354 = v231.v484(0.5, v231.v515(v162.v194, (v797.v450 - 24) / v834, (v797.v753 - 24) / v835))
if v231.v798(v804.v804 - v354) > 0.01 then v804.v804 = v354 end
end
v914()
local v915 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(0, v838, 1, -v837), v738 = v678.v685, v748 = 0,
}, v594)
v338(v60("return '\\v145\\v146\\v155\\v75\\v100\\v76\\v113\\v68\\v74\\v62'")(), { v726 = v916.v338(v678.v686, v678.v685), v775 = 0 }, v915)
v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), { v412 = v413.v338(0, 3, 1, 0), v386 = v413.v338(1, -3, 0, 0), v738 = v678.v687, v748 = 0 }, v915)
local v917 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), { v412 = v413.v338(1, -3, 1, -66), v417 = 1 }, v915)
v338(v60("return '\\v145\\v146\\v159\\v113\\v64\\v62\\v159\\v100\\v99\\v73\\v69\\v62'")(), { v918 = v723.v338(0, 4), v919 = v342.v919.v920 }, v917)
v338(v60("return '\\v145\\v146\\v135\\v100\\v76\\v76\\v113\\v74\\v150'")(), { v921 = v723.v338(0, 10), v922 = v723.v338(0, 10), v923 = v723.v338(0, 12) }, v917)
local v924 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), { v412 = v413.v338(1, -3, 0, 60), v386 = v413.v338(0, 0, 1, -60), v417 = 1 }, v915)
v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), { v412 = v413.v338(1, -20, 0, 2), v386 = v413.v338(0, 10, 0, 0), v738 = v678.v687, v748 = 0 }, v924)
local v925 = v338(v60("return '\\v146\\v67\\v100\\v150\\v68\\v159\\v100\\v71\\v68\\v98'")(), {
v412 = v413.v338(0, 36, 0, 36), v386 = v413.v338(0, 12, 0.5, -16), v738 = v678.v687, v748 = 0,
v926 = v60("return '\\v75\\v71\\v416\\v62\\v61\\v69\\v67\\v71\\v65\\v66\\v66\\v62\\v99\\v63\\v68\\v568\\v192\\v115\\v100\\v62\\v100\\v75\\v153\\v68\\v100\\v76\\v141\\v61\\v73\\v62\\v585\\v113\\v76\\v568'")() .. v202(v156.v203) .. v60("return '\\v585\\v143\\v568\\v583\\v927\\v273\\v585\\v61\\v568\\v583\\v927\\v273'")(),
}, v924)
v719(v925, 18)
v679(v925, v678.v696, 2)
v850(v924, {
v423 = v156.v654, v419 = v706, v421 = 13, v424 = v678.v688,
v412 = v413.v338(1, -62, 0, 16), v386 = v413.v338(0, 56, 0.5, -17), v928 = v342.v928.v929,
})
v850(v924, {
v423 = v60("return '\\v930'")() .. v156.v339, v421 = 10, v424 = v678.v688,
v412 = v413.v338(1, -62, 0, 12), v386 = v413.v338(0, 56, 0.5, 1), v928 = v342.v928.v929,
})
local v931 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v339 = v60("return '\\v173\\v73\\v74\\v62\\v68\\v74\\v62'")(), v412 = v413.v338(1, -v838, 1, -v837), v386 = v413.v338(0, v838, 0, 0),
v738 = v678.v681, v748 = 0, v749 = true,
}, v594)
v338(v60("return '\\v145\\v146\\v155\\v75\\v100\\v76\\v113\\v68\\v74\\v62'")(), { v726 = v916.v338(v678.v681, v678.v682), v775 = 90 }, v931)
v200(v745, v931, 18)
local v932 = v850(v931, {
v419 = v706, v421 = 22, v424 = v678.v702,
v412 = v413.v338(1, -(v832 * 2 + 150), 0, 26), v386 = v413.v338(0, v832 + 2, 0, 6),
})
v730(v932, v678.v679, 2)
local v933 = v850(v931, {
v421 = 12, v424 = v678.v703,
v412 = v413.v338(1, -(v832 * 2 + 150), 0, 16), v386 = v413.v338(0, v832 + 2, 0, 32),
v928 = v342.v928.v929,
})
local v934 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(0, 140, 0, 28), v386 = v413.v338(1, -(v832 + 140), 0, 10),
v738 = v678.v690, v748 = 0, v749 = true,
}, v931)
v719(v934, 14)
v679(v934, v678.v695, 2)
local v935 = v338(v60("return '\\v112\\v68\\v416\\v62\\v323\\v73\\v416'")(), {
v412 = v413.v338(1, -24, 1, 0), v386 = v413.v338(0, 12, 0, 0), v417 = 1,
v423 = v60("return ''")(), v866 = v60("return '\\v323\\v69\\v64\\v77\\v100\\v75\\v72\\v72\\v72'")(), v867 = v678.v694, v424 = v678.v693,
v419 = v705, v421 = 12, v712 = v709, v868 = false, v749 = true,
}, v934)
local v936 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, 0, 1, -v839), v386 = v413.v338(0, 0, 0, v839),
v417 = 1, v749 = true,
}, v931)
local v937, v938, v939 = {}, {}, {}
local v940 = nil
local function v941(v485, v942, v943)
local v772 = v338(v60("return '\\v141\\v77\\v75\\v73\\v98\\v98\\v113\\v74\\v150\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, -2 * v832, 1, 0), v386 = v413.v338(0, v832, 0, 0),
v417 = 1, v748 = 0, v944 = 4, v945 = v678.v696,
v946 = v342.v946.v753, v947 = v413.v338(0, 0, 0, 0),
v948 = v342.v949.v753, v442 = false,
}, v936)
v338(v60("return '\\v145\\v146\\v159\\v113\\v64\\v62\\v159\\v100\\v99\\v73\\v69\\v62'")(), { v918 = v723.v338(0, v833), v919 = v342.v919.v920 }, v772)
v338(v60("return '\\v145\\v146\\v135\\v100\\v76\\v76\\v113\\v74\\v150'")(), { v922 = v723.v338(0, 8), v950 = v723.v338(0, 8) }, v772)
local v951 = { v485 = v485, v441 = v772, v942 = v942, v943 = v943 }
v937[v485] = v951
return v951
end
local function v952(v951)
local v953 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, 0, 0, 0), v949 = v342.v949.v753,
v417 = 1, v920 = v851(v951.v441),
}, v951.v441)
v338(v60("return '\\v145\\v146\\v159\\v113\\v64\\v62\\v159\\v100\\v99\\v73\\v69\\v62'")(), {
v954 = v342.v954.v955, v918 = v723.v338(0, v833),
v919 = v342.v919.v920, v956 = v342.v956.v957,
}, v953)
local function v958(v456)
local v307 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(0.5, -v833 / 2 - 4, 0, 0), v949 = v342.v949.v753,
v417 = 1, v920 = v456,
}, v953)
v338(v60("return '\\v145\\v146\\v159\\v113\\v64\\v62\\v159\\v100\\v99\\v73\\v69\\v62'")(), { v918 = v723.v338(0, v833), v919 = v342.v919.v920 }, v307)
return v307
end
return v958(1), v958(2)
end
local function v959(v718, v942)
local v441 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, 0, 0, 0), v949 = v342.v949.v753,
v738 = v678.v689, v748 = 0, v920 = v851(v718),
}, v718)
v719(v441, 12)
v679(v441, v678.v695, 2)
v338(v60("return '\\v145\\v146\\v159\\v113\\v64\\v62\\v159\\v100\\v99\\v73\\v69\\v62'")(), { v919 = v342.v919.v920 }, v441)
local v960 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), { v412 = v413.v338(1, 0, 0, 36), v417 = 1, v920 = 1 }, v441)
v850(v960, { v423 = v60("return '\\v961\\v962\\v963\\v964'")(), v419 = v705, v421 = 17, v412 = v413.v338(0, 26, 1, 0), v386 = v413.v338(0, 10, 0, 0), v712 = v711 })
v850(v960, {
v423 = v942, v419 = v706, v421 = 16, v412 = v413.v338(1, -84, 1, 0), v386 = v413.v338(0, 40, 0, 0),
v928 = v342.v928.v929,
})
local v965 = v338(v60("return '\\v112\\v68\\v416\\v62\\v323\\v69\\v62\\v62\\v73\\v74'")(), {
v412 = v413.v338(0, 30, 0, 30), v386 = v413.v338(1, -34, 0.5, -15), v417 = 1,
v423 = v60("return '\\v115'")(), v424 = v678.v694, v419 = v706, v421 = 14, v855 = false,
}, v960)
local v588 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, 0, 0, 0), v949 = v342.v949.v753, v417 = 1, v920 = 2,
}, v441)
v338(v60("return '\\v145\\v146\\v159\\v113\\v64\\v62\\v159\\v100\\v99\\v73\\v69\\v62'")(), { v919 = v342.v919.v920 }, v588)
v338(v60("return '\\v145\\v146\\v135\\v100\\v76\\v76\\v113\\v74\\v150'")(), { v921 = v723.v338(0, 12), v922 = v723.v338(0, 12), v950 = v723.v338(0, 10) }, v588)
v965.v863:v308(function()
v588.v442 = not v588.v442
v965.v423 = v588.v442 and v60("return '\\v115'")() or v60("return '\\v966'")()
end)
local v967 = { v441 = v441, v588 = v588, v942 = v942, v968 = {} }
v939[#v939 + 1] = v967
return v967
end
local function v969(v967, v970, v399, v971)
local v953 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, 0, 0, v970), v417 = 1, v920 = v851(v967.v588),
}, v967.v588)
if not v971 then
v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, 0, 0, 1), v386 = v413.v338(0, 0, 1, -1), v738 = v678.v691, v748 = 0,
}, v953)
end
v967.v968[#v967.v968 + 1] = { v441 = v953, v399 = v566.v433(v399 or v60("return ''")()) }
return v953
end
local function v972(v967, v376, v973, v758, v871)
local v953 = v969(v967, v973 and 50 or 34, v376 .. v60("return '\\v114'")() .. (v973 or v60("return ''")()))
v850(v953, {
v423 = v376, v419 = v706, v421 = 14, v412 = v413.v338(1, -52, 0, 18),
v386 = v413.v338(0, 0, 0, v973 and 5 or 8), v928 = v342.v928.v929,
})
if v973 then
v850(v953, {
v423 = v973, v421 = 10, v424 = v678.v694, v974 = true, v975 = v342.v975.v957,
v412 = v413.v338(1, -52, 0, 24), v386 = v413.v338(0, 0, 0, 23),
})
end
return v869(v953, v758, v871)
end
local function v976(v967, v376)
local v953 = v969(v967, 28, v376)
v850(v953, { v423 = v376, v424 = v678.v694, v419 = v705, v412 = v413.v338(0.45, 0, 1, 0) })
return v850(v953, {
v423 = v60("return '\\v70'")(), v419 = v706, v421 = 13, v412 = v413.v338(0.55, 0, 1, 0), v386 = v413.v338(0.45, 0, 0, 0),
v712 = v710, v928 = v342.v928.v929,
})
end
local function v977(v967, v376)
local v953 = v969(v967, 44, v376)
v850(v953, { v423 = v376, v419 = v706, v421 = 14, v412 = v413.v338(0.6, 0, 0, 18), v386 = v413.v338(0, 0, 0, 5) })
local v978 = v850(v953, {
v423 = v60("return '\\v273\\v584'")(), v419 = v706, v421 = 13, v424 = v678.v699, v412 = v413.v338(0.4, 0, 0, 18),
v386 = v413.v338(0.6, 0, 0, 5), v712 = v710,
})
local v886 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, 0, 0, 14), v386 = v413.v338(0, 0, 0, 26), v738 = v678.v691, v748 = 0,
}, v953)
v719(v886, 7)
v679(v886, v678.v695, 2)
local v887 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), { v412 = v413.v338(0, 0, 1, 0), v738 = v678.v696, v748 = 0 }, v886)
v719(v887, 7)
return v978, v887
end
local function v979(v967, v376, v881, v882, v883, v884, v885)
local v953 = v969(v967, 48, v376)
v850(v953, { v423 = v376, v419 = v706, v421 = 14, v412 = v413.v338(0.6, 0, 0, 18), v386 = v413.v338(0, 0, 0, 5) })
local v978 = v850(v953, {
v423 = v202(v883), v419 = v706, v421 = 14, v424 = v678.v699, v412 = v413.v338(0.4, 0, 0, 18),
v386 = v413.v338(0.6, 0, 0, 5), v712 = v710,
})
return v880(v953, v881, v882, v883, function(v436)
v978.v423 = v202(v436)
v884(v436)
end, v885)
end
local function v980(v967, v399, v981, v982)
local v968 = v231.v983(#v981 / v982)
local v953 = v969(v967, v968 * 36 + 6, v399, true)
for v456, v984 in v254(v981) do
local v676, v307 = v231.v474((v456 - 1) / v982), (v456 - 1) % v982
local v222 = v854(v953, v984.v399, v984.v724, {
v412 = v413.v338(1 / v982, -(v982 - 1) * 6 / v982, 0, 30),
v386 = v413.v338(v307 / v982, v307 * 6 / v982, 0, 4 + v676 * 36),
v421 = 11, v974 = true,
})
v856(v222, v984.v399, v984.v724, v984.v859, v984.v860)
end
end
local function v985(v485)
v940 = v485
for v630, v951 in v245(v937) do v951.v441.v442 = (v630 == v485) end
local v951 = v937[v485]
v932.v423 = v566.v986(v951.v942)
v933.v423 = v951.v943
for v630, v255 in v245(v938) do
local v987 = (v630 == v485)
v255.v733.v417 = v987 and 0 or 1
v255.v376.v424 = v987 and v678.v693 or v678.v688
v255.v988.v331 = v987
end
v935.v423 = v60("return ''")()
end
local v989 = 0
local function v990(v399)
v989 = v989 + 1
v850(v917, {
v423 = v399, v419 = v706, v421 = 12, v424 = v678.v697, v412 = v413.v338(1, 0, 0, 20),
v920 = v989, v975 = v342.v975.v991,
})
end
local function v992(v485, v399)
v989 = v989 + 1
local v733 = v338(v60("return '\\v112\\v68\\v416\\v62\\v323\\v69\\v62\\v62\\v73\\v74'")(), {
v412 = v413.v338(1, 0, 0, 34), v738 = v678.v689, v417 = 1,
v423 = v60("return ''")(), v855 = false, v748 = 0, v920 = v989,
}, v917)
v719(v733, 10)
local v993 = v679(v733, v678.v679, 2)
v993.v331 = false
v850(v733, { v423 = v60("return '\\v961\\v962\\v963\\v964'")(), v419 = v705, v421 = 17, v412 = v413.v338(0, 28, 1, 0), v386 = v413.v338(0, 6, 0, 0), v712 = v711 })
local v376 = v850(v733, {
v423 = v399, v419 = v706, v421 = 13, v424 = v678.v688, v412 = v413.v338(1, -44, 1, 0),
v386 = v413.v338(0, 36, 0, 0), v928 = v342.v928.v929,
})
local v994 = v338(v60("return '\\v112\\v68\\v416\\v62\\v159\\v100\\v71\\v68\\v98'")(), {
v412 = v413.v338(0, 22, 0, 18), v386 = v413.v338(1, -26, 0.5, -9), v738 = v678.v696,
v423 = v60("return ''")(), v424 = v678.v702, v419 = v706, v421 = 11, v748 = 0, v442 = false,
}, v733)
v719(v994, 9)
v733.v863:v308(function() v985(v485) end)
v938[v485] = { v733 = v733, v376 = v376, v988 = v993, v994 = v994 }
end
local v995 = v941(v60("return '\\v207\\v100\\v75\\v67'")(), v60("return '\\v174\\v100\\v75\\v67'")(), v60("return '\\v379\\v73\\v68\\v76\\v100\\v64\\v114\\v100\\v114\\v77\\v100\\v76\\v100\\v114\\v75\\v73\\v76\\v100\\v76\\v100'")())
do
local v996, v997 = v952(v995)
local v998 = v959(v996, v60("return '\\v173\\v73\\v113\\v74\\v114\\v174\\v100\\v75\\v67'")())
v671.v296 = v972(v998, v60("return '\\v192\\v69\\v62\\v73\\v114\\v174\\v100\\v75\\v67'")(), v60("return '\\v148\\v73\\v100\\v114\\v100\\v62\\v68\\v114\\v77\\v100\\v76\\v100\\v114\\v67\\v73\\v68\\v76\\v100\\v114\\v100\\v62\\v68\\v114\\v100\\v114\\v71\\v73\\v98\\v64\\v100\\v114\\v68\\v74\\v77\\v61\\v68\\v75'")(), false, v363)
v286.v296 = v671.v296
v979(v998, v60("return '\\v148\\v68\\v98\\v73\\v77\\v113\\v76\\v100\\v76\\v68'")(), 12, 30, v223.v230, function(v436) v223.v230 = v436 end, v238)
for v253, v431 in v254({
{ v60("return '\\v140\\v73\\v62\\v100\\v64\\v114\\v76\\v113\\v207\\v68\\v75\\v68\\v74\\v62\\v68\\v64'")(), v60("return '\\v173\\v100\\v76\\v100\\v114\\v77\\v73\\v74\\v62\\v100\\v114\\v64\\v69\\v100\\v114\\v63\\v68\\v150\\v100\\v114\\v69\\v67\\v114\\v64\\v68\\v62\\v73\\v75\\v114\\v76\\v73\\v114\\v67\\v100\\v63\\v100'")(), v60("return '\\v64\\v63\\v98\\v113\\v62\\v140\\v73\\v69\\v62\\v68\\v64'")() },
{ v60("return '\\v390\\v115\\v113\\v62\\v100\\v75\\v114\\v100\\v64\\v64\\v100\\v64\\v64\\v113\\v74\\v73'")(), v60("return '\\v174\\v73\\v150\\v68\\v114\\v68\\v114\\v113\\v150\\v74\\v73\\v75\\v100\\v114\\v67\\v73\\v68\\v76\\v100\\v64\\v114\\v63\\v68\\v75\\v62\\v73\\v114\\v76\\v68\\v98\\v68'")(), v60("return '\\v100\\v115\\v73\\v113\\v76\\v379\\v69\\v75\\v76\\v68\\v75\\v68\\v75'")() },
{ v60("return '\\v390\\v64\\v63\\v68\\v75\\v100\\v75\\v114\\v77\\v73\\v74\\v62\\v100\\v64'")(), v60("return '\\v192\\v64\\v64\\v100\\v64\\v64\\v113\\v74\\v73\\v114\\v64\\v73\\v114\\v75\\v68\\v150\\v68\\v74\\v68\\v75\\v100\\v114\\v621\\v69\\v100\\v74\\v76\\v73\\v114\\v73\\v114\\v64\\v113\\v62\\v68\\v114\\v98\\v113\\v71\\v68\\v75\\v100\\v75'")(), v60("return '\\v62\\v68\\v100\\v67\\v137\\v100\\v113\\v62'")() },
}) do
local v485 = v431[3]
v972(v998, v431[1], v431[2], v223[v485], function(v364)
v223[v485] = v364
v238()
end)
end
v671.v999, v671.v1000 = v977(v998, v60("return '\\v323\\v73\\v98\\v64\\v100\\v114\\v76\\v68\\v114\\v67\\v73\\v68\\v76\\v100\\v64'")())
local v1001 = v959(v997, v60("return '\\v140\\v73\\v76\\v100\\v76\\v100'")())
v671.v1002 = v976(v1001, v60("return '\\v148\\v73\\v77\\v68'")())
local v1003 = v969(v1001, 40, v60("return '\\v100\\v64\\v64\\v100\\v64\\v64\\v113\\v74\\v73'")())
v850(v1003, { v423 = v60("return '\\v192\\v64\\v64\\v100\\v64\\v64\\v113\\v74\\v73'")(), v424 = v678.v694, v419 = v705, v412 = v413.v338(0.3, 0, 1, 0) })
v671.v1004 = v338(v60("return '\\v146\\v67\\v100\\v150\\v68\\v159\\v100\\v71\\v68\\v98'")(), {
v412 = v413.v338(0, 26, 0, 26), v386 = v413.v338(1, -26, 0.5, -13), v738 = v678.v691,
v748 = 0, v926 = v60("return ''")(), v1005 = v342.v1005.v1006,
}, v1003)
v719(v671.v1004, 13)
v671.v1007 = v679(v671.v1004, v678.v694, 2)
v671.v1008 = v850(v1003, {
v423 = v60("return '\\v70'")(), v419 = v706, v421 = 13, v412 = v413.v338(0.7, -34, 0, 16), v386 = v413.v338(0.3, 0, 0.5, -16),
v712 = v710, v928 = v342.v928.v929,
})
v671.v1009 = v850(v1003, {
v421 = 10, v424 = v678.v694, v412 = v413.v338(0.7, -34, 0, 12), v386 = v413.v338(0.3, 0, 0.5, 1),
v712 = v710,
})
v671.v1010 = v976(v1001, v60("return '\\v173\\v61\\v68\\v77\\v138\\v64\\v114\\v76\\v100\\v114\\v75\\v73\\v76\\v100\\v76\\v100'")())
v671.v1011 = v976(v1001, v60("return '\\v140\\v73\\v62\\v100'")())
v671.v1012 = v976(v1001, v60("return '\\v135\\v100\\v75\\v62\\v113\\v76\\v100'")())
local v1013 = v959(v997, v60("return '\\v400\\v73\\v115\\v113\\v76\\v100\\v76\\v68\\v64'")())
local v1014 = v969(v1013, 80, v60("return '\\v74\\v73\\v115\\v113\\v76\\v100\\v76\\v68\\v64\\v114\\v77\\v61\\v68\\v77\\v138\\v114\\v64\\v113\\v62\\v68\\v114\\v100\\v64\\v64\\v100\\v64\\v64\\v113\\v74\\v73\\v114\\v68\\v64\\v63\\v68\\v75\\v100\\v114\\v64\\v68\\v75\\v115\\v113\\v76\\v73\\v75\\v114\\v98\\v73\\v71\\v71\\v99\\v114\\v62\\v113\\v67\\v68\\v75'")(), true)
v850(v1014, {
v423 = v60("return '\\v115\\v583\\v583\\v570\\v74\\v70\\v114\\v141\\v100\\v71\\v68\\v114\\v621\\v69\\v100\\v74\\v76\\v73\\v114\\v115\\v73\\v77\\v68\\v114\\v68\\v64\\v62\\v100\\v114\\v74\\v73\\v114\\v159\\v401\\v323\\v323\\v1015\\v570\\v74\\v70\\v114\\v112\\v68\\v67\\v63\\v73\\v114\\v76\\v100\\v114\\v63\\v100\\v75\\v62\\v113\\v76\\v100\\v114\\v100\\v73\\v114\\v115\\v113\\v115\\v73\\v114\\v74\\v73\\v114\\v64\\v113\\v62\\v68\\v570\\v74\\v70\\v114\\v112\\v75\\v100\\v74\\v64\\v67\\v113\\v62\\v113\\v75\\v114\\v100\\v73\\v114\\v115\\v113\\v115\\v73\\v114\\v402\\v173\\v73\\v74\\v207\\v113\\v150\\v403'")(),
v421 = 11, v974 = true, v975 = v342.v975.v957,
v412 = v413.v338(1, 0, 1, -4), v386 = v413.v338(0, 0, 0, 2),
})
end
local v1016 = v941(v60("return '\\v61\\v69\\v71'")(), v60("return '\\v173\\v73\\v74\\v62\\v100\\v64'")(), v60("return '\\v141\\v69\\v100\\v64\\v114\\v77\\v73\\v74\\v62\\v100\\v64\\v114\\v68\\v67\\v114\\v62\\v68\\v67\\v63\\v73\\v114\\v75\\v68\\v100\\v98'")())
do
local v996, v997 = v952(v1016)
local v1017 = v959(v996, v60("return '\\v173\\v73\\v74\\v68\\v416\\v100\\v73'")())
local v1018 = v969(v1017, 54, v60("return '\\v68\\v74\\v76\\v68\\v75\\v68\\v77\\v73\\v114\\v69\\v75\\v98\\v114\\v64\\v113\\v62\\v68'")())
v850(v1018, { v423 = v60("return '\\v390\\v74\\v76\\v68\\v75\\v68\\v77\\v73\\v114\\v76\\v73\\v114\\v64\\v113\\v62\\v68'")(), v419 = v705, v421 = 11, v424 = v678.v694, v412 = v413.v338(1, 0, 0, 14), v386 = v413.v338(0, 0, 0, 3) })
v671.v1019 = v864(v1018, { v412 = v413.v338(1, 0, 0, 28), v386 = v413.v338(0, 0, 0, 20), v866 = v60("return '\\v61\\v62\\v62\\v63\\v64\\v65\\v66\\v66\\v64\\v68\\v69\\v70\\v64\\v113\\v62\\v68\\v72\\v73\\v74\\v75\\v68\\v74\\v76\\v68\\v75\\v72\\v77\\v73\\v67'")(), v423 = v223.v234 })
local v1020 = v969(v1017, 54, v60("return '\\v77\\v61\\v100\\v115\\v68\\v114\\v64\\v68\\v74\\v61\\v100'")())
v850(v1020, { v423 = v60("return '\\v173\\v61\\v100\\v115\\v68\\v114\\v402\\v1021\\v626\\v114\\v77\\v100\\v75\\v100\\v77\\v62\\v68\\v75\\v68\\v64\\v403'")(), v419 = v705, v421 = 11, v424 = v678.v694, v412 = v413.v338(1, 0, 0, 14), v386 = v413.v338(0, 0, 0, 3) })
v671.v1022 = v864(v1020, { v412 = v413.v338(1, 0, 0, 28), v386 = v413.v338(0, 0, 0, 20), v866 = v60("return '\\v100\\v114\\v67\\v68\\v64\\v67\\v100\\v114\\v77\\v61\\v100\\v115\\v68\\v114\\v68\\v67\\v114\\v62\\v73\\v76\\v100\\v64\\v114\\v100\\v64\\v114\\v77\\v73\\v74\\v62\\v100\\v64'")(), v423 = v223.v236 })
local v1023 = v969(v1017, 58, v60("return '\\v77\\v73\\v74\\v68\\v77\\v62\\v100\\v75'")(), true)
local v1024 = v854(v1023, v60("return '\\v173\\v73\\v74\\v68\\v77\\v62\\v100\\v75'")(), v678.v698, { v412 = v413.v338(1, 0, 0, 30), v386 = v413.v338(0, 0, 0, 4) })
v671.v1025 = v850(v1023, {
v423 = v286.v289, v419 = v705, v421 = 11, v424 = v678.v694, v412 = v413.v338(1, 0, 0, 14),
v386 = v413.v338(0, 0, 0, 38), v712 = v711, v928 = v342.v928.v929,
})
local function v1026(v354) return (v202(v354 or v60("return ''")()):v625(v60("return '\\v627\\v584\\v64\\v626'")(), v60("return ''")()):v625(v60("return '\\v584\\v64\\v626\\v628'")(), v60("return ''")())) end
v1024.v863:v308(function()
v223.v234 = v1026(v671.v1019.v423)
v223.v236 = v1026(v671.v1022.v423)
v238()
v286.v289 = v60("return '\\v77\\v73\\v74\\v68\\v77\\v62\\v100\\v74\\v76\\v73\\v72\\v72\\v72'")()
v286.v297 = true
end)
local v1027 = v959(v997, v60("return '\\v140\\v68\\v64\\v69\\v67\\v73'")())
v671.v1028 = v976(v1027, v60("return '\\v173\\v73\\v74\\v62\\v100\\v64\\v114\\v73\\v74\\v98\\v113\\v74\\v68'")())
v671.v1029 = v976(v1027, v60("return '\\v379\\v73\\v68\\v76\\v100\\v64\\v114\\v402\\v62\\v73\\v76\\v100\\v64\\v403'")())
v671.v1030 = v976(v1027, v60("return '\\v379\\v73\\v68\\v76\\v100\\v64\\v114\\v66\\v114\\v61\\v73\\v75\\v100'")())
v671.v1031 = v976(v1027, v60("return '\\v173\\v61\\v68\\v77\\v138\\v64\\v114\\v76\\v100\\v114\\v75\\v73\\v76\\v100\\v76\\v100'")())
v980(v1027, v60("return '\\v75\\v68\\v150\\v68\\v74\\v68\\v75\\v100\\v75\\v114\\v113\\v74\\v113\\v77\\v113\\v100\\v75\\v114\\v63\\v100\\v75\\v100\\v75\\v114\\v622\\v68\\v75\\v100\\v75\\v114\\v62\\v73\\v76\\v100\\v64'")(), {
{ v399 = v60("return '\\v140\\v68\\v150\\v68\\v74\\v68\\v75\\v100\\v75\\v114\\v62\\v73\\v76\\v100\\v64'")(), v724 = v678.v699, v860 = function() v286.v667(v60("return '\\v100\\v98\\v98'")(), v60("return '\\v75\\v68\\v64\\v68\\v62'")()) end },
{ v399 = v60("return '\\v146\\v74\\v113\\v77\\v113\\v100\\v75\\v114\\v62\\v73\\v76\\v100\\v64'")(), v724 = v678.v700, v860 = function() v286.v667(v60("return '\\v100\\v98\\v98'")(), v60("return '\\v207\\v100\\v75\\v67\\v191\\v73\\v74'")()) end },
{ v399 = v60("return '\\v135\\v100\\v75\\v100\\v75\\v114\\v62\\v73\\v76\\v100\\v64'")(), v724 = v675(150, 110, 70), v860 = function() v286.v667(v60("return '\\v100\\v98\\v98'")(), v60("return '\\v207\\v100\\v75\\v67\\v191\\v73\\v207\\v207'")()) end },
{ v399 = v60("return '\\v1032\\v68\\v75\\v100\\v75\\v114\\v64\\v62\\v100\\v62\\v64'")(), v724 = v678.v698, v859 = true, v860 = function() v286.v667(v60("return '\\v100\\v98\\v98'")(), v60("return '\\v75\\v68\\v64\\v68\\v62\\v191\\v64\\v62\\v100\\v62\\v64'")()) end },
}, 2)
local v1033 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, -4, 0, 0), v949 = v342.v949.v753, v417 = 1, v920 = v851(v1016.v441),
}, v1016.v441)
v338(v60("return '\\v145\\v146\\v159\\v113\\v64\\v62\\v159\\v100\\v99\\v73\\v69\\v62'")(), { v919 = v342.v919.v920 }, v1033)
local v1034 = v959(v1033, v60("return '\\v173\\v73\\v74\\v62\\v100\\v64'")())
v671.v1035 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, 0, 0, 0), v949 = v342.v949.v753, v417 = 1, v920 = v851(v1034.v588),
}, v1034.v588)
v338(v60("return '\\v145\\v146\\v159\\v113\\v64\\v62\\v159\\v100\\v99\\v73\\v69\\v62'")(), { v918 = v723.v338(0, 6), v919 = v342.v919.v920 }, v671.v1035)
v671.v1036 = v850(v671.v1035, {
v423 = v60("return '\\v74\\v68\\v74\\v61\\v69\\v67\\v100\\v114\\v77\\v73\\v74\\v62\\v100\\v114\\v77\\v73\\v74\\v68\\v77\\v62\\v100\\v76\\v100\\v114\\v100\\v113\\v74\\v76\\v100'")(), v424 = v678.v694, v412 = v413.v338(1, 0, 0, 36), v920 = -1,
v712 = v711,
})
end
local v1037 = v941(v60("return '\\v64\\v62\\v100\\v62\\v64'")(), v60("return '\\v390\\v64\\v62\\v100\\v62\\v113\\v64\\v62\\v113\\v77\\v100\\v64'")(), v60("return '\\v367\\v68\\v64\\v68\\v67\\v63\\v68\\v74\\v61\\v73\\v114\\v76\\v68\\v64\\v62\\v100\\v114\\v77\\v73\\v74\\v62\\v100\\v114\\v68\\v114\\v76\\v68\\v114\\v62\\v73\\v76\\v100\\v64'")())
do
local v996, v997 = v952(v1037)
local v1038 = v959(v996, v60("return '\\v390\\v64\\v62\\v100\\v114\\v77\\v73\\v74\\v62\\v100'")())
local v1039 = v969(v1038, 60, v60("return '\\v67\\v73\\v68\\v76\\v100\\v64\\v114\\v77\\v73\\v98\\v68\\v62\\v100\\v76\\v100\\v64'")())
v671.v1040 = v850(v1039, { v423 = v60("return '\\v273'")(), v419 = v706, v421 = 32, v424 = v678.v696, v412 = v413.v338(1, 0, 0, 36), v386 = v413.v338(0, 0, 0, 4) })
v850(v1039, { v423 = v60("return '\\v67\\v73\\v68\\v76\\v100\\v64\\v114\\v77\\v73\\v98\\v68\\v62\\v100\\v76\\v100\\v64'")(), v421 = 11, v424 = v678.v694, v412 = v413.v338(1, 0, 0, 14), v386 = v413.v338(0, 0, 0, 40) })
v671.v1041 = v976(v1038, v60("return '\\v112\\v68\\v67\\v63\\v73\\v114\\v100\\v62\\v113\\v115\\v73'")())
v671.v1042 = v976(v1038, v60("return '\\v379\\v73\\v68\\v76\\v100\\v64\\v114\\v66\\v114\\v61\\v73\\v75\\v100'")())
v671.v1043 = v976(v1038, v60("return '\\v379\\v68\\v76\\v113\\v100\\v114\\v66\\v114\\v63\\v100\\v75\\v62\\v113\\v76\\v100'")())
v671.v1044 = v976(v1038, v60("return '\\v135\\v100\\v75\\v62\\v113\\v76\\v100\\v64'")())
local v1045 = v959(v997, v60("return '\\v112\\v73\\v76\\v100\\v64\\v114\\v100\\v64\\v114\\v77\\v73\\v74\\v62\\v100\\v64'")())
v671.v1046 = v976(v1045, v60("return '\\v173\\v73\\v74\\v62\\v100\\v64\\v114\\v73\\v74\\v98\\v113\\v74\\v68'")())
v671.v1047 = v976(v1045, v60("return '\\v379\\v73\\v68\\v76\\v100\\v64'")())
v671.v1048 = v976(v1045, v60("return '\\v379\\v73\\v68\\v76\\v100\\v64\\v114\\v66\\v114\\v61\\v73\\v75\\v100'")())
v671.v1049 = v976(v1045, v60("return '\\v135\\v100\\v75\\v62\\v113\\v76\\v100\\v64'")())
local v1050 = v959(v997, v60("return '\\v192\\v77\\v73\\v68\\v64'")())
v980(v1050, v60("return '\\v622\\v68\\v75\\v100\\v75\\v114\\v68\\v64\\v62\\v100\\v62\\v113\\v64\\v62\\v113\\v77\\v100\\v64'")(), {
{ v399 = v60("return '\\v1032\\v68\\v75\\v100\\v75\\v114\\v68\\v64\\v62\\v100\\v62\\v113\\v64\\v62\\v113\\v77\\v100\\v64'")(), v724 = v678.v699, v859 = true, v860 = function()
v216.v217, v216.v219, v216.v220 = 0, 0, 0
v238()
v672()
end },
}, 1)
end
local v1051 = v941(v60("return '\\v64\\v68\\v75\\v115\\v68\\v75'")(), v60("return '\\v141\\v68\\v75\\v115\\v113\\v76\\v73\\v75'")(), v60("return '\\v112\\v75\\v73\\v621\\v69\\v68\\v114\\v76\\v68\\v114\\v64\\v68\\v75\\v115\\v113\\v76\\v73\\v75\\v114\\v64\\v73\\v622\\v113\\v74\\v61\\v73\\v114\\v73\\v69\\v114\\v77\\v73\\v67\\v114\\v62\\v73\\v76\\v100\\v64\\v114\\v100\\v64\\v114\\v77\\v73\\v74\\v62\\v100\\v64'")())
do
local v996, v997 = v952(v1051)
local v1052 = v959(v996, v60("return '\\v141\\v68\\v75\\v115\\v113\\v76\\v73\\v75\\v114\\v100\\v62\\v69\\v100\\v98'")())
v671.v1053 = v976(v1052, v60("return '\\v573\\v73\\v71\\v146\\v76'")())
v671.v1054 = v976(v1052, v60("return '\\v573\\v73\\v150\\v100\\v76\\v73\\v75\\v68\\v64'")())
v980(v1052, v60("return '\\v77\\v73\\v63\\v113\\v100\\v75\\v114\\v193\\v73\\v71\\v113\\v76'")(), {
{ v399 = v60("return '\\v173\\v73\\v63\\v113\\v100\\v75\\v114\\v573\\v73\\v71\\v146\\v76'")(), v724 = v678.v698, v860 = function()
local v306 = v825()
if v306 and v129.v598 ~= v60("return ''")() then v200(v306, v129.v598) end
end },
}, 1)
local v1055 = v959(v996, v60("return '\\v192\\v98\\v68\\v100\\v62\\v73\\v75\\v113\\v73'")())
v980(v1055, v60("return '\\v64\\v68\\v75\\v115\\v113\\v76\\v73\\v75\\v114\\v100\\v98\\v68\\v100\\v62\\v73\\v75\\v113\\v73\\v114\\v68\\v64\\v62\\v100\\v114\\v77\\v73\\v74\\v62\\v100\\v114\\v62\\v73\\v76\\v100\\v64'")(), {
{ v399 = v60("return '\\v390\\v64\\v62\\v100\\v114\\v77\\v73\\v74\\v62\\v100'")(), v724 = v678.v696, v860 = function() v286.v646() end },
{ v399 = v60("return '\\v112\\v73\\v76\\v100\\v64\\v114\\v100\\v64\\v114\\v77\\v73\\v74\\v62\\v100\\v64'")(), v724 = v678.v698, v859 = true, v860 = function() v286.v667(v60("return '\\v100\\v98\\v98'")(), v60("return '\\v61\\v73\\v63'")()) end },
}, 2)
local v1056 = v959(v997, v60("return '\\v146\\v75\\v114\\v63\\v100\\v75\\v100\\v114\\v69\\v67\\v114\\v64\\v68\\v75\\v115\\v113\\v76\\v73\\v75'")())
local v676 = v969(v1056, 74, v60("return '\\v193\\v73\\v71\\v113\\v76\\v114\\v98\\v113\\v74\\v138\\v114\\v64\\v68\\v75\\v115\\v113\\v76\\v73\\v75'")(), true)
v850(v676, { v423 = v60("return '\\v573\\v73\\v71\\v146\\v76\\v114\\v73\\v69\\v114\\v98\\v113\\v74\\v138\\v114\\v402\\v150\\v100\\v67\\v68\\v146\\v74\\v64\\v62\\v100\\v74\\v77\\v68\\v146\\v76\\v568\\v72\\v72\\v72\\v403'")(), v419 = v705, v421 = 11, v424 = v678.v694, v412 = v413.v338(1, 0, 0, 14), v386 = v413.v338(0, 0, 0, 3), v928 = v342.v928.v929 })
v671.v1057 = v864(v676, { v412 = v413.v338(1, 0, 0, 28), v386 = v413.v338(0, 0, 0, 20), v866 = v60("return '\\v583\\v100\\v576\\v71\\v1058\\v77\\v1059\\v76\\v70\\v927\\v68\\v1021\\v207\\v70\\v1060\\v100\\v1061\\v71\\v70\\v1062\\v77\\v273\\v76\\v70\\v72\\v72\\v72'")() })
v671.v1063 = v850(v676, { v423 = v60("return '\\v77\\v73\\v98\\v68\\v114\\v69\\v67\\v114\\v573\\v73\\v71\\v146\\v76\\v114\\v73\\v69\\v114\\v98\\v113\\v74\\v138'")(), v421 = 10, v424 = v678.v694, v412 = v413.v338(1, 0, 0, 14), v386 = v413.v338(0, 0, 0, 54) })
v980(v1056, v60("return '\\v113\\v75\\v114\\v98\\v68\\v115\\v100\\v75\\v114\\v62\\v73\\v76\\v100\\v64'")(), {
{ v399 = v60("return '\\v146\\v75\\v114\\v402\\v68\\v64\\v62\\v100\\v114\\v77\\v73\\v74\\v62\\v100\\v403'")(), v724 = v678.v696, v860 = function()
local v820 = v286.v663(v671.v1057.v423)
if v820 then v286.v666(v820) end
end },
{ v399 = v60("return '\\v159\\v68\\v115\\v100\\v75\\v114\\v62\\v73\\v76\\v100\\v64'")(), v724 = v678.v700, v860 = function()
if v286.v663(v671.v1057.v423) then v286.v667(v60("return '\\v100\\v98\\v98'")(), v60("return '\\v193\\v73\\v113\\v74'")(), v671.v1057.v423) end
end },
}, 2)
v671.v1064 = v850(v969(v1056, 30, v60("return '\\v100\\v98\\v115\\v73'")(), true), {
v421 = 11, v419 = v705, v424 = v678.v694, v974 = true, v412 = v413.v338(1, 0, 1, 0),
})
v671.v1057:v158(v60("return '\\v112\\v68\\v416\\v62'")()):v308(function()
local v820 = v286.v663(v671.v1057.v423)
if v671.v1057.v423 == v60("return ''")() then
v671.v1063.v423, v671.v1063.v424 = v60("return '\\v77\\v73\\v98\\v68\\v114\\v69\\v67\\v114\\v573\\v73\\v71\\v146\\v76\\v114\\v73\\v69\\v114\\v98\\v113\\v74\\v138'")(), v678.v694
elseif v820 then
v671.v1063.v423, v671.v1063.v424 = v60("return '\\v573\\v73\\v71\\v146\\v76\\v114\\v76\\v68\\v62\\v68\\v77\\v62\\v100\\v76\\v73\\v65\\v114'")() .. v820.v644:v943(1, 8) .. v60("return '\\v72\\v72\\v72'")(), v675(40, 130, 60)
else
v671.v1063.v423, v671.v1063.v424 = v60("return '\\v74\\v100\\v73\\v114\\v100\\v77\\v61\\v68\\v113\\v114\\v69\\v67\\v114\\v573\\v73\\v71\\v146\\v76\\v114\\v74\\v68\\v64\\v64\\v68\\v114\\v62\\v68\\v416\\v62\\v73'")(), v678.v699
end
end)
end
local v1065 = v941(v60("return '\\v77\\v73\\v74\\v207\\v113\\v150'")(), v60("return '\\v173\\v73\\v74\\v207\\v113\\v150\\v69\\v75\\v100\\v77\\v73\\v68\\v64'")(), v60("return '\\v192\\v193\\v69\\v64\\v62\\v68\\v64\\v114\\v150\\v68\\v75\\v100\\v113\\v64\\v114\\v68\\v114\\v77\\v73\\v74\\v62\\v100\\v64\\v114\\v67\\v100\\v74\\v69\\v100\\v113\\v64'")())
do
local v996, v997 = v952(v1065)
local v1066 = v959(v996, v60("return '\\v155\\v68\\v75\\v100\\v98'")())
v972(v1066, v60("return '\\v192\\v74\\v62\\v113\\v70\\v192\\v174\\v372'")(), v60("return '\\v390\\v115\\v113\\v62\\v100\\v114\\v64\\v68\\v75\\v114\\v68\\v416\\v63\\v69\\v98\\v64\\v73\\v114\\v63\\v73\\v75\\v114\\v113\\v74\\v100\\v62\\v113\\v115\\v113\\v76\\v100\\v76\\v68'")(), v223.v226, function(v364)
v223.v226 = v364
v238()
end)
v972(v1066, v60("return '\\v192\\v69\\v62\\v73\\v114\\v140\\v68\\v193\\v73\\v113\\v74'")(), v60("return '\\v148\\v73\\v98\\v62\\v100\\v114\\v64\\v73\\v622\\v113\\v74\\v61\\v73\\v114\\v64\\v68\\v114\\v77\\v100\\v113\\v75\\v114\\v68\\v114\\v75\\v68\\v100\\v71\\v75\\v68\\v114\\v73\\v114\\v64\\v77\\v75\\v113\\v63\\v62'")(), v223.v225, function(v364)
v223.v225 = v364
v238()
if v364 then v579() end
end)
v972(v1066, v60("return '\\v112\\v75\\v100\\v74\\v64\\v67\\v113\\v62\\v113\\v75\\v114\\v100\\v73\\v114\\v115\\v113\\v115\\v73'")(), v60("return '\\v159\\v113\\v71\\v68\\v75\\v100\\v114\\v73\\v114\\v115\\v113\\v76\\v68\\v73\\v66\\v67\\v100\\v63\\v100\\v114\\v100\\v73\\v114\\v115\\v113\\v115\\v73\\v114\\v76\\v68\\v64\\v62\\v100\\v114\\v77\\v73\\v74\\v62\\v100\\v114\\v74\\v73\\v114\\v64\\v113\\v62\\v68\\v114\\v402\\v115\\v113\\v76\\v68\\v73\\v65\\v114\\v100\\v71\\v75\\v100\\v114\\v66\\v77\\v100\\v64\\v62\\v114\\v74\\v73\\v114\\v135\\v173\\v403'")(), v223.v233, function(v364)
v223.v233 = v364
v238()
end)
local v1067 = v959(v997, v60("return '\\v379\\v113\\v74\\v61\\v100\\v64\\v114\\v77\\v73\\v74\\v62\\v100\\v64\\v114\\v402\\v67\\v100\\v74\\v69\\v100\\v98\\v403'")())
local v1068 = v969(v1067, 44, v60("return '\\v67\\v113\\v74\\v61\\v100\\v64\\v114\\v77\\v73\\v74\\v62\\v100\\v64\\v114\\v67\\v100\\v74\\v69\\v100\\v98\\v114\\v67\\v100\\v75\\v77\\v100\\v75'")(), true)
v850(v1068, {
v423 = v60("return '\\v401\\v114\\v153\\v69\\v71\\v114\\v193\\v100\\v114\\v76\\v68\\v62\\v68\\v77\\v62\\v100\\v114\\v64\\v69\\v100\\v64\\v114\\v77\\v73\\v74\\v62\\v100\\v64\\v114\\v64\\v73\\v622\\v113\\v74\\v61\\v73\\v72\\v114\\v379\\v100\\v75\\v621\\v69\\v68\\v114\\v100\\v621\\v69\\v113\\v114\\v64\\v73\\v114\\v64\\v68\\v114\\v74\\v100\\v73\\v114\\v69\\v64\\v100\\v75\\v114\\v73\\v114\\v153\\v69\\v71\\v72'")(),
v421 = 10, v424 = v678.v694, v974 = true, v975 = v342.v975.v957, v412 = v413.v338(1, 0, 1, 0),
})
v671.v1069 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, 0, 0, 0), v949 = v342.v949.v753, v417 = 1, v920 = v851(v1067.v588),
}, v1067.v588)
v338(v60("return '\\v145\\v146\\v159\\v113\\v64\\v62\\v159\\v100\\v99\\v73\\v69\\v62'")(), { v918 = v723.v338(0, 4), v919 = v342.v919.v920 }, v671.v1069)
v671.v1070 = v854(v1067.v588, v60("return '\\v367\\v68\\v64\\v67\\v100\\v75\\v77\\v100\\v75\\v114\\v62\\v73\\v76\\v100\\v64'")(), v675(150, 110, 70), {
v412 = v413.v338(1, 0, 0, 28), v920 = v851(v1067.v588), v421 = 12,
})
end
v990(v60("return '\\v573\\v401\\v155\\v401'")())
v992(v60("return '\\v207\\v100\\v75\\v67'")(), v60("return '\\v174\\v100\\v75\\v67'")())
v992(v60("return '\\v61\\v69\\v71'")(), v60("return '\\v173\\v73\\v74\\v62\\v100\\v64'")())
v992(v60("return '\\v64\\v62\\v100\\v62\\v64'")(), v60("return '\\v390\\v64\\v62\\v100\\v62\\v113\\v64\\v62\\v113\\v77\\v100\\v64'")())
v990(v60("return '\\v401\\v145\\v112\\v140\\v401\\v141'")())
v992(v60("return '\\v64\\v68\\v75\\v115\\v68\\v75'")(), v60("return '\\v141\\v68\\v75\\v115\\v113\\v76\\v73\\v75'")())
v992(v60("return '\\v77\\v73\\v74\\v207\\v113\\v150'")(), v60("return '\\v173\\v73\\v74\\v207\\v113\\v150'")())
v935:v158(v60("return '\\v112\\v68\\v416\\v62'")()):v308(function()
local v580 = v566.v433(v935.v423 or v60("return ''")())
for v253, v307 in v254(v939) do
local v1071 = v580 ~= v60("return ''")() and v566.v434(v566.v433(v307.v942), v580, 1, true) ~= nil
local v597 = false
for v253, v676 in v254(v307.v968) do
local v1072 = (v580 == v60("return ''")()) or v1071 or (v566.v434(v676.v399, v580, 1, true) ~= nil)
v676.v441.v442 = v1072
if v1072 then v597 = true end
end
v307.v441.v442 = (v580 == v60("return ''")()) or v597 or v1071
end
end)
local v1073 = nil
local function v1074(v301)
if v301 == v1073 then return end
v1073 = v301
v671.v1004.v926 = v301 and (v60("return '\\v75\\v71\\v416\\v62\\v61\\v69\\v67\\v71\\v65\\v66\\v66\\v62\\v99\\v63\\v68\\v568\\v192\\v115\\v100\\v62\\v100\\v75\\v153\\v68\\v100\\v76\\v141\\v61\\v73\\v62\\v585\\v113\\v76\\v568'")() .. v202(v301) .. v60("return '\\v585\\v143\\v568\\v583\\v927\\v273\\v585\\v61\\v568\\v583\\v927\\v273'")()) or v60("return ''")()
end
v672 = function()
if not v318 or not v318.v325 or v671.v849 then return end
v914()
local v1075 = (v216.v219 >= 10) and (v216.v217 / (v216.v219 / 3600)) or 0
local v1076 = (v216.v220 > 0) and (v216.v217 / v216.v220) or 0
v671.v1040.v423 = v823(v216.v217)
v671.v1041.v423 = v821(v216.v219)
v671.v1042.v423 = v823(v1075)
v671.v1043.v423 = v566.v586(v60("return '\\v584\\v72\\v583\\v207'")(), v1076)
v671.v1044.v423 = v823(v216.v220)
local v1052, v484 = v202(v272):v665(v60("return '\\v627\\v402\\v584\\v76\\v626\\v403\\v584\\v64\\v1077\\v66\\v584\\v64\\v1077\\v402\\v584\\v76\\v626\\v403\\v628'")())
local v1078 = 0
if v1052 and v218(v484) > 0 then v1078 = v231.v232(v218(v1052) / v218(v484), 0, 1) end
v671.v999.v423 = v1052 and (v1052 .. v60("return '\\v66'")() .. v484) or v202(v272)
v671.v1000.v412 = v413.v338(v1078, 0, 1, 0)
v671.v1000.v738 = (v1078 >= 1) and v678.v700 or v678.v696
v897.v738 = v258 and v678.v696 or v678.v685
v898.v423 = v258 and v60("return '\\v401\\v400'")() or v60("return '\\v401\\v174\\v174'")()
v898.v424 = v258 and v678.v679 or v678.v703
local v1038, v1079 = v60("return '\\v77\\v73\\v98\\v68\\v62\\v100\\v74\\v76\\v73'")(), v678.v693
if not v258 then v1038, v1079 = v60("return '\\v63\\v100\\v75\\v100\\v76\\v73'")(), v678.v694
elseif v286.v298 then v1038, v1079 = v60("return '\\v74\\v73\\v114\\v98\\v73\\v71\\v71\\v99'")(), v678.v694
elseif v280 then v1038, v1079 = v281, v675(200, 120, 10)
elseif v459() then v1038, v1079 = v60("return '\\v100\\v64\\v64\\v100\\v64\\v64\\v113\\v74\\v73'")(), v678.v699
elseif v259 then v1038, v1079 = v60("return '\\v71\\v73\\v98\\v64\\v100\\v114\\v77\\v61\\v68\\v113\\v100\\v114\\v70\\v114\\v77\\v61\\v68\\v77\\v138'")(), v675(40, 130, 60)
elseif v261 then v1038, v1079 = v60("return '\\v100\\v150\\v69\\v100\\v75\\v76\\v100\\v74\\v76\\v73\\v114\\v75\\v73\\v76\\v100\\v76\\v100'")(), v678.v694
elseif v313 and v313.v362 <= 0 then v1038, v1079 = v60("return '\\v67\\v73\\v75\\v62\\v73'")(), v678.v694 end
v671.v1002.v423, v671.v1002.v424 = v1038, v1079
local v376, v943, v1080 = v60("return '\\v70'")(), v60("return ''")(), v678.v694
if v258 and v274 then
v376, v1080 = v274, v678.v699
if v274 == v156.v339 then
v376, v943 = v60("return '\\v115\\v73\\v77\\v68'")(), v60("return '\\v64\\v69\\v100\\v114\\v77\\v73\\v74\\v62\\v100'")()
else
local v385 = v383()
if v385 and v312 and v312.v325 then
v943 = v231.v474((v385.v386 - v312.v386).v430) .. v60("return '\\v67'")()
end
local v370 = v133:v336(v274)
if v370 and v300(v370.v203) then v943, v1080 = v60("return '\\v64\\v69\\v100\\v114\\v77\\v73\\v74\\v62\\v100'")(), v678.v698 end
end
elseif v258 then
v376 = v60("return '\\v63\\v75\\v73\\v77\\v69\\v75\\v100\\v74\\v76\\v73\\v72\\v72\\v72'")()
end
v671.v1008.v423, v671.v1009.v423, v671.v1007.v726 = v376, v943, v1080
local v1081 = (v258 and v274) and v133:v336(v274) or nil
v1074(v1081 and v1081.v203 or nil)
v671.v1010.v423 = v286.v212 and (v286.v292 .. v60("return '\\v66'")() .. v286.v293) or v60("return '\\v70'")()
v671.v1011.v423 = (v223.v229 and v283 > 1) and (v282 .. v60("return '\\v114\\v76\\v68\\v114'")() .. v283) or v60("return '\\v64\\v73\\v98\\v73'")()
v671.v1012.v423 = v286.v299 ~= v60("return ''")() and v286.v299 or v60("return '\\v70'")()
v671.v1053.v423 = (v129.v598 ~= v60("return ''")() and (v129.v598:v943(1, 8) .. v60("return '\\v72\\v72\\v72'")() .. v129.v598:v943(-4))) or v60("return '\\v402\\v68\\v64\\v62\\v69\\v76\\v113\\v73\\v403'")()
v671.v1054.v423 = #v133:v382() .. v60("return '\\v114\\v66\\v114'")() .. v202(v133.v1082 or v60("return '\\v488'")())
local v1083 = v286.v295
v671.v1064.v423 = (v1083 and v1083.v644)
and (v60("return '\\v100\\v98\\v115\\v73\\v114'")() .. v202(v1083.v644):v943(1, 8) .. v60("return '\\v72\\v72\\v72\\v65\\v114'")() .. v202(v1083.v1084 or 0) .. v60("return '\\v66'")() .. v202(v1083.v659 or 0) .. v60("return '\\v114\\v77\\v73\\v74\\v62\\v100\\v64\\v114\\v98\\v100'")())
or v60("return ''")()
end
local v1085 = {}
local function v1086(v90)
local v244 = v90.v244
local v953 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, 0, 0, 66), v738 = v678.v690, v748 = 0, v920 = 10,
}, v671.v1035)
v719(v953, 10)
local v1087 = v679(v953, v678.v691, 2)
local v1088 = v338(v60("return '\\v146\\v67\\v100\\v150\\v68\\v159\\v100\\v71\\v68\\v98'")(), {
v412 = v413.v338(0, 40, 0, 40), v386 = v413.v338(0, 8, 0.5, -20), v738 = v678.v691, v748 = 0,
v926 = v60("return '\\v75\\v71\\v416\\v62\\v61\\v69\\v67\\v71\\v65\\v66\\v66\\v62\\v99\\v63\\v68\\v568\\v192\\v115\\v100\\v62\\v100\\v75\\v153\\v68\\v100\\v76\\v141\\v61\\v73\\v62\\v585\\v113\\v76\\v568'")() .. v202(v244) .. v60("return '\\v585\\v143\\v568\\v583\\v927\\v273\\v585\\v61\\v568\\v583\\v927\\v273'")(),
}, v953)
v719(v1088, 20)
local v1089 = v679(v1088, v678.v694, 2)
local function v1090(v764, v1091, v799, v792)
return v850(v953, {
v419 = v1091, v421 = v799, v412 = v413.v338(1, -150, 0, v792), v386 = v413.v338(0, 56, 0, v764),
v928 = v342.v928.v929,
})
end
local v1092 = v1090(6, v706, 14, 16)
local v1093 = v1090(24, v705, 10, 13)
local v1094 = v1090(40, v705, 10, 13)
local function v1095(v764, v399, v724)
return v854(v953, v399, v724, {
v412 = v413.v338(0, 74, 0, 18), v386 = v413.v338(1, -82, 0, v764), v421 = 10,
})
end
local v1096 = v1095(5, v60("return '\\v140\\v68\\v150\\v68\\v74\\v68\\v75\\v100\\v75'")(), v678.v699)
local v1097 = v1095(25, v60("return '\\v135\\v100\\v75\\v100\\v75'")(), v678.v696)
local v1098 = v1095(45, v60("return '\\v1032\\v68\\v75\\v100\\v75\\v114\\v64\\v62\\v100\\v62\\v64'")(), v678.v698)
local v676 = { v441 = v953, v655 = false }
v856(v1096, v60("return '\\v140\\v68\\v150\\v68\\v74\\v68\\v75\\v100\\v75'")(), v678.v699, false, function() v286.v667(v244, v60("return '\\v75\\v68\\v64\\v68\\v62'")()) end)
v856(v1098, v60("return '\\v1032\\v68\\v75\\v100\\v75\\v114\\v64\\v62\\v100\\v62\\v64'")(), v678.v698, true, function() v286.v667(v244, v60("return '\\v75\\v68\\v64\\v68\\v62\\v191\\v64\\v62\\v100\\v62\\v64'")()) end)
v1097.v863:v308(function() v286.v667(v244, v676.v655 and v60("return '\\v207\\v100\\v75\\v67\\v191\\v73\\v207\\v207'")() or v60("return '\\v207\\v100\\v75\\v67\\v191\\v73\\v74'")()) end)
v676.v1099 = function(v1100, v1101)
local v659 = v1100.v659 == true
v676.v655 = v1100.v655 == true
local v397 = (v1100.v658 == v60("return '\\v379\\v69\\v75\\v76\\v68\\v75\\v68\\v75'")() and v659)
local v1102 = v659 and v1100.v655 and v1100.v285 and v1100.v657
local v1103 = ((v1100.v219 or 0) >= 10) and ((v1100.v217 or 0) / (v1100.v219 / 3600)) or 0
local v942 = ((v1100.v653 or v60("return ''")()) ~= v60("return ''")() and v1100.v653 or v1100.v376 or v60("return '\\v488'")())
if v244 == v156.v203 then v942 = v942 .. v60("return '\\v114\\v114\\v402\\v115\\v73\\v77\\v68\\v403'")() end
v1092.v423 = v942
v1092.v424 = v397 and v678.v699 or v678.v693
local v993 = v659 and (((v1100.v364 or v60("return ''")()) ~= v60("return ''")() and v1100.v364) or v60("return '\\v70'")()) or v60("return '\\v73\\v207\\v207\\v98\\v113\\v74\\v68'")()
v1093.v423 = v60("return '\\v930'")() .. v202(v1100.v376) .. v60("return '\\v114\\v114\\v70\\v114\\v114'")() .. v993 .. (v397 and v60("return '\\v114\\v114\\v70\\v114\\v114\\v192\\v141\\v141\\v192\\v141\\v141\\v146\\v400\\v401'")() or v60("return ''")())
v1093.v424 = v659 and v678.v694 or v678.v699
v1094.v423 = v823(v1100.v217 or 0) .. v60("return '\\v114\\v67\\v73\\v68\\v76\\v100\\v64\\v114\\v114\\v70\\v114\\v114\\v71\\v73\\v98\\v64\\v100\\v114'")() .. ((v1100.v656 and v1100.v656 ~= v60("return ''")()) and v1100.v656 or v60("return '\\v70'")())
.. v60("return '\\v114\\v114\\v70\\v114\\v114'")() .. v823(v1103) .. v60("return '\\v66\\v61'")() .. (v1102 and v60("return '\\v114\\v114\\v70\\v114\\v114\\v173\\v153\\v390\\v173\\v372'")() or v60("return ''")())
v1094.v424 = v1102 and v675(40, 130, 60) or v678.v693
local v1080 = v397 and v678.v699 or (v1102 and v678.v700) or ((v659 and v1100.v655) and v678.v696) or v678.v694
v1089.v726 = v1080
v1087.v726 = (v659 and v1100.v655) and v1080 or v678.v691
v1088.v1104 = v659 and 0 or 0.65
v1096.v442, v1097.v442, v1098.v442 = v659, v659, v659
v1097.v423 = v676.v655 and v60("return '\\v135\\v100\\v75\\v100\\v75'")() or v60("return '\\v146\\v74\\v113\\v77\\v113\\v100\\v75'")()
v953.v920 = (v659 and 0 or 1000) + v1101
end
return v676
end
v673 = function()
if v671.v849 then return end
local v659, v1105, v1075, v220 = 0, 0, 0, 0
for v253, v90 in v254(v286.v287) do
v1105 = v1105 + (v90.v217 or 0)
v220 = v220 + (v90.v220 or 0)
if v90.v659 then
v659 = v659 + 1
if (v90.v219 or 0) >= 10 then v1075 = v1075 + (v90.v217 or 0) / (v90.v219 / 3600) end
end
end
local v1106 = v938.v1107.v994
v1106.v442 = v659 > 0
v1106.v423 = v202(v659)
v671.v1025.v423 = v286.v289
v671.v1025.v424 = v286.v212 and v675(40, 130, 60) or v675(200, 120, 10)
v671.v1046.v423 = v202(v659)
v671.v1047.v423 = v823(v1105)
v671.v1048.v423 = v823(v1075)
v671.v1049.v423 = v823(v220)
if v940 ~= v60("return '\\v61\\v69\\v71'")() then return end
v671.v1028.v423 = v202(v659)
v671.v1029.v423 = v823(v1105)
v671.v1030.v423 = v823(v1075)
v671.v1031.v423 = v286.v212 and (v286.v292 .. v60("return '\\v66'")() .. v286.v293) or v60("return '\\v70'")()
local v1108 = {}
for v456, v90 in v254(v286.v287) do
if v205(v90) == v60("return '\\v62\\v100\\v71\\v98\\v68'")() and v90.v244 then
v1108[v90.v244] = true
local v676 = v1085[v90.v244]
if not v676 then
v676 = v1086(v90)
v1085[v90.v244] = v676
end
v676.v1099(v90, v456)
end
end
for v244, v676 in v245(v1085) do
if not v1108[v244] then
v676.v441:v351()
v1085[v244] = nil
end
end
v671.v1036.v442 = (#v286.v287 == 0)
end
local v1109 = {}
local function v1110(v370)
local v244 = v370.v203
local v1111 = (v370 == v156)
local v953 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), {
v412 = v413.v338(1, 0, 0, 38), v738 = v678.v690, v748 = 0, v920 = 2,
}, v671.v1069)
v719(v953, 8)
local v1087 = v679(v953, v678.v691, 2)
v719(v338(v60("return '\\v146\\v67\\v100\\v150\\v68\\v159\\v100\\v71\\v68\\v98'")(), {
v412 = v413.v338(0, 26, 0, 26), v386 = v413.v338(0, 6, 0.5, -13), v738 = v678.v691, v748 = 0,
v926 = v60("return '\\v75\\v71\\v416\\v62\\v61\\v69\\v67\\v71\\v65\\v66\\v66\\v62\\v99\\v63\\v68\\v568\\v192\\v115\\v100\\v62\\v100\\v75\\v153\\v68\\v100\\v76\\v141\\v61\\v73\\v62\\v585\\v113\\v76\\v568'")() .. v202(v244) .. v60("return '\\v585\\v143\\v568\\v583\\v927\\v273\\v585\\v61\\v568\\v583\\v927\\v273'")(),
}, v953), 13)
v850(v953, {
v423 = v370.v654, v419 = v706, v421 = 12, v412 = v413.v338(1, -96, 0, 15),
v386 = v413.v338(0, 38, 0, 5), v928 = v342.v928.v929,
})
local v1112 = v850(v953, {
v419 = v705, v421 = 9, v424 = v678.v694, v412 = v413.v338(1, -96, 0, 12),
v386 = v413.v338(0, 38, 0, 21), v928 = v342.v928.v929,
})
local v676 = { v441 = v953 }
local v1113 = (v240[v244] == true)
local v872 = nil
v676.v1099 = function()
local v987 = v1111 or (v240[v244] == true)
if v872 and v987 ~= v1113 then
v1113 = v987
v872.v650(v987)
end
v1087.v726 = v987 and v678.v696 or v678.v691
v953.v920 = v1111 and 0 or (v987 and 1 or 2)
local v1114 = {}
if v1111 then v1114[#v1114 + 1] = v60("return '\\v148\\v401\\v173\\v390'")() end
if v286.v288[v244] and not v1111 then v1114[#v1114 + 1] = v60("return '\\v153\\v145\\v323'")() end
local v397 = (v370.v339 == v274)
if v397 then v1114[#v1114 + 1] = v60("return '\\v192\\v141\\v141\\v192\\v141\\v141\\v146\\v400\\v401'")() end
v1112.v423 = v60("return '\\v930'")() .. v370.v339 .. (#v1114 > 0 and (v60("return '\\v114\\v114\\v70\\v114\\v114'")() .. v246.v248(v1114, v60("return '\\v114\\v66\\v114'")())) or v60("return ''")())
v1112.v424 = v397 and v678.v699 or v678.v694
end
if not v1111 then
local v747 = v338(v60("return '\\v174\\v75\\v100\\v67\\v68'")(), { v412 = v413.v338(0, 42, 1, 0), v386 = v413.v338(1, -50, 0, 0), v417 = 1 }, v953)
v872 = v869(v747, v1113, function(v364)
v1113 = v364
v240[v244] = v364 or nil
v242()
v676.v1099()
v200(v396)
end)
end
v676.v1099()
return v676
end
v674 = function()
if not v671.v1069 or not v671.v1069.v325 then return end
local v1115 = {}
for v253, v370 in v254(v133:v382()) do
v1115[v370.v203] = true
local v676 = v1109[v370.v203]
if not v676 then
v1109[v370.v203] = v1110(v370)
else
v676.v1099()
end
end
for v244, v676 in v245(v1109) do
if not v1115[v244] then
v676.v441:v351()
v1109[v244] = nil
end
end
end
v671.v1070.v863:v308(function()
v240 = {}
v242()
v674()
v200(v396)
end)
v304(v133.v1116, function()
v468.v471(0.3)
v200(v674)
end)
v304(v133.v617, function()
v468.v471(0.1)
v200(v674)
end)
v985(v60("return '\\v207\\v100\\v75\\v67'")())
v200(v674)
end)
if not v830 then v495(v60("return '\\v496\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v497\\v114\\v68\\v75\\v75\\v73\\v114\\v74\\v100\\v114\\v113\\v74\\v62\\v68\\v75\\v207\\v100\\v77\\v68\\v65\\v114'")() .. v202(v831)) end
v468.v469(function()
local v486 = v277.v278()
local v1117, v1118 = 0, 0
while v257 do
v468.v471(0.5)
local v1119 = v277.v278()
local v780 = v1119 - v486
v486 = v1119
if v258 then
v216.v219 = v216.v219 + v780
if v162.v179 > 0 and not v550 and v1119 - v276 > v162.v179 then
v276 = v1119
v605(v60("return '\\v64\\v68\\v67\\v114\\v77\\v73\\v98\\v68\\v62\\v100\\v75\\v114\\v67\\v73\\v68\\v76\\v100\\v64\\v114\\v61\\v100\\v114\\v67\\v69\\v113\\v62\\v73\\v114\\v62\\v68\\v67\\v63\\v73'")())
end
end
v1117 = v1117 + v780
if v1117 >= 5 then
v1117 = 0
v238()
end
v1118 = v1118 + v780
if v1118 >= 3 then
v1118 = 0
v250()
v200(v674)
end
v200(v672)
v200(v673)
end
end)
v468.v469(function()
local v590 = v558()
local v1120 = false
local v767, v1121 = nil, nil
local v1122, v1123, v1124 = nil, nil, v269
local v1125, v1126 = nil, 0
local v1127, v1128 = nil, nil
local v1129, v1130, v1131, v1132 = nil, 0, {}, false
local v1133 = nil
local function v1134(v431)
v431 = v202(v431 or v60("return ''")())
if #v431 > 14 then return nil end
local v1135, v354 = v431:v665(v60("return '\\v402\\v584\\v76\\v626\\v403\\v65\\v402\\v584\\v76\\v584\\v76\\v403'")())
if v1135 then return v218(v1135) * 60 + v218(v354) end
return nil
end
local function v1136(v822)
v822 = v231.v484(0, v231.v474(v822))
return v566.v586(v60("return '\\v584\\v76\\v65\\v584\\v273\\v576\\v76'")(), v231.v474(v822 / 60), v822 % 60)
end
local function v1137(v37)
local v1052 = v37
while v1052 and v1052 ~= v160 do
if v1052:v322(v60("return '\\v155\\v69\\v113\\v401\\v71\\v193\\v68\\v77\\v62'")()) and not v1052.v442 then return false end
if v1052:v322(v60("return '\\v159\\v100\\v99\\v68\\v75\\v173\\v73\\v98\\v98\\v68\\v77\\v62\\v73\\v75'")()) and v1052.v331 == false then return false end
v1052 = v1052.v325
end
return true
end
local function v1138(v820)
local v354, v1052, v1139 = 0, v820, 0
while v1052 and v1052 ~= v160 and v1139 < 4 do
local v255 = v1052.v339:v433()
if v255:v434(v60("return '\\v62\\v113\\v67\\v68\\v75'")()) then v354 = v354 + (v1139 == 0 and 4 or 2)
elseif v255:v434(v60("return '\\v62\\v113\\v67\\v68'")()) or v255:v434(v60("return '\\v77\\v98\\v73\\v77\\v138'")()) or v255:v434(v60("return '\\v75\\v73\\v69\\v74\\v76'")()) then v354 = v354 + (v1139 == 0 and 3 or 1) end
v1052 = v1052.v325
v1139 = v1139 + 1
end
return v354
end
local function v1140()
local v1119 = v277.v278()
local v1052 = {}
for v253, v820 in v254(v160:v437()) do
if (v820:v322(v60("return '\\v112\\v68\\v416\\v62\\v159\\v100\\v71\\v68\\v98'")()) or v820:v322(v60("return '\\v112\\v68\\v416\\v62\\v323\\v69\\v62\\v62\\v73\\v74'")())) and not v820:v1141(v60("return '\\v192\\v69\\v62\\v73\\v174\\v100\\v75\\v67\\v145\\v146'")()) then
local v436 = v1134(v820.v423)
if v436 and v1137(v820) then v1052[v820] = v436 end
end
end
local v518, v524 = nil, 0
for v820, v436 in v245(v1052) do
local v527 = v1138(v820)
local v1142 = v1131[v820]
if v1142 and v1119 - v1142.v431 >= 1 and v436 < v1142.v436 and (v1142.v436 - v436) <= (v1119 - v1142.v431) + 2 then v527 = v527 + 5 end
if v527 > v524 then v518, v524 = v820, v527 end
end
v1131 = {}
for v820, v436 in v245(v1052) do v1131[v820] = { v436 = v436, v431 = v1119 } end
if v518 and v524 >= 2 then return v518 end
if not v1132 then
local v1143 = {}
for v820 in v245(v1052) do v1143[#v1143 + 1] = v820:v1144() end
if #v1143 > 0 then
v1132 = true
v495(v60("return '\\v496\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v497\\v114\\v75\\v68\\v98\\v73\\v150\\v113\\v73\\v64\\v114\\v74\\v100\\v114\\v62\\v68\\v98\\v100\\v114\\v402\\v74\\v68\\v74\\v61\\v69\\v67\\v114\\v75\\v68\\v77\\v73\\v74\\v61\\v68\\v77\\v113\\v76\\v73\\v114\\v100\\v113\\v74\\v76\\v100\\v403\\v65\\v114'")() .. v246.v248(v1143, v60("return '\\v114\\v1145\\v114'")(), 1, v231.v515(#v1143, 5)))
end
end
return nil
end
local function v1146()
if v1129 and (not v1129.v325 or not v1134(v1129.v423) or not v1137(v1129)) then v1129 = nil end
if not v1129 and v277.v278() >= v1130 then
v1130 = v277.v278() + 2
v1129 = v1140()
if v1129 then v495(v60("return '\\v496\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v497\\v114\\v62\\v113\\v67\\v68\\v75\\v114\\v76\\v100\\v114\\v63\\v100\\v75\\v62\\v113\\v76\\v100\\v65\\v114'")() .. v1129:v1144()) end
end
if v1129 then return v1134(v1129.v423) end
if v1133 then
local v996 = v1133.v996 - (v277.v278() - v1133.v1147)
if v996 > 0 then return v996 end
v1133 = nil
end
return nil
end
v468.v469(function()
local v493 = v149:v161(v60("return '\\v140\\v68\\v67\\v73\\v62\\v68\\v64'")(), 10)
local v1148 = v493 and v493:v161(v60("return '\\v155\\v100\\v67\\v68\\v63\\v98\\v100\\v99'")(), 10)
if not v1148 then return end
local v1143 = {}
for v253, v388 in v254(v1148:v321()) do
if v388:v322(v60("return '\\v140\\v68\\v67\\v73\\v62\\v68\\v390\\v115\\v68\\v74\\v62'")()) then
v1143[#v1143 + 1] = v388.v339
local v1149 = v388.v339:v433()
if v1149:v434(v60("return '\\v62\\v113\\v67\\v68'")()) or v1149:v434(v60("return '\\v77\\v98\\v73\\v77\\v138'")()) then
v304(v388.v500, function(...)
local v1150 = { ... }
for v456 = 1, #v1150 do
local v436 = v218(v1150[v456])
if v436 and v436 >= 5 and v436 <= 600 then
v1133 = { v996 = v436, v1147 = v277.v278() }
break
end
end
end)
end
end
end
v495(v60("return '\\v496\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v497\\v114\\v75\\v68\\v67\\v73\\v62\\v68\\v64\\v114\\v76\\v73\\v114\\v155\\v100\\v67\\v68\\v63\\v98\\v100\\v99\\v65\\v114'")() .. v246.v248(v1143, v60("return '\\v249\\v114'")()))
end)
local function v1151()
for v253, v426 in v254(v133:v382()) do
if v369(v426) then return true end
end
return false
end
local function v1152()
for v307 in v245(v262) do
if v307.v325 then return true end
end
return false
end
local function v1153()
local v1154 = v279
if v205(v1154) ~= v60("return '\\v62\\v100\\v71\\v98\\v68'")() then return true end
local v1155 = false
for v376, v377 in v245(v1154) do
if v376 ~= v156.v339 and v205(v377) == v60("return '\\v62\\v100\\v71\\v98\\v68'")() and v377.v378 ~= nil and v377.v378 ~= v60("return ''")() and v377.v378 ~= v60("return '\\v159\\v73\\v71\\v71\\v99'")() then
v1155 = true
break
end
end
if not v1155 then return true end
local v1038 = v1154[v156.v339]
if v205(v1038) ~= v60("return '\\v62\\v100\\v71\\v98\\v68'")() then return false end
if v1038.v380 or v1038.v381 then return false end
return v1038.v378 ~= nil and v1038.v378 ~= v60("return ''")() and v1038.v378 ~= v60("return '\\v159\\v73\\v71\\v71\\v99'")()
end
local function v676(v255) return v231.v474(v255 + 0.5) end
local function v441()
local v1156 = v312
if not (v1156 and v1156.v325) then return nil end
local v772 = { v1038 = { v676(v1156.v386.v450), v676(v1156.v386.v451) }, v1157 = {}, v307 = {}, v1158 = (v274 == v156.v339) }
for v253, v426 in v254(v133:v382()) do
if v426 ~= v156 then
local v792 = v426.v310 and v426.v310:v336(v60("return '\\v153\\v69\\v67\\v100\\v74\\v73\\v113\\v76\\v140\\v73\\v73\\v62\\v135\\v100\\v75\\v62'")())
if v792 then
local v1159 = 0
if v426.v339 == v274 then v1159 = v1159 + 1 end
if v300(v426.v203) then v1159 = v1159 + 2 end
v772.v1157[#v772.v1157 + 1] = { v426.v654:v943(1, 12), v676(v792.v386.v450), v676(v792.v386.v451), v1159 }
end
end
end
local v255 = 0
for v512 in v245(v262) do
if v512.v325 and v255 < 200 then
v772.v307[#v772.v307 + 1] = v676(v512.v386.v450)
v772.v307[#v772.v307 + 1] = v676(v512.v386.v451)
v255 = v255 + 1
end
end
local v1083 = v264
if v1083 and v1083.v325 then v772.v1083 = { v676(v1083.v386.v450), v676(v1083.v386.v451) } end
return v772
end
local function v634()
local v624 = v202(v223.v234 or v60("return ''")()):v625(v60("return '\\v584\\v64\\v626'")(), v60("return ''")())
if v624 == v60("return ''")() then return nil end
if not v624:v434(v60("return '\\v627\\v61\\v62\\v62\\v63\\v64\\v488\\v65\\v66\\v66'")()) then v624 = v60("return '\\v61\\v62\\v62\\v63\\v64\\v65\\v66\\v66'")() .. v624 end
return (v624:v625(v60("return '\\v66\\v626\\v628'")(), v60("return ''")()))
end
while v257 do
local v1119 = v277.v278()
if v1152() or v1151() then
v1122 = nil
if v767 ~= v60("return '\\v67\\v100\\v62\\v77\\v61'")() then
if v767 == nil then v1123 = nil else v1123 = v1119 - 2 end
v767 = v60("return '\\v67\\v100\\v62\\v77\\v61'")()
end
else
v1122 = v1122 or v1119
if v767 ~= v60("return '\\v98\\v73\\v71\\v71\\v99'")() and (v767 == nil or v1119 - v1122 >= 3) then
v767 = v60("return '\\v98\\v73\\v71\\v71\\v99'")()
v1123 = nil
end
end
if v269 ~= v1124 then v1124 = v269 v1123 = v1119 end
if v767 == v60("return '\\v98\\v73\\v71\\v71\\v99'")() and v1121 == v60("return '\\v67\\v100\\v62\\v77\\v61'")() then
v280 = false
if v285 then v285 = false v284 = true end
v286.v297 = true
end
v1121 = v767
local v452 = (v312 and v312.v325) and v312.v386 or nil
local v458 = v313 ~= nil and v313.v325 ~= nil and v313.v362 > 0
if v767 == v60("return '\\v98\\v73\\v71\\v71\\v99'")() and v452 and v458 and v1122 and v1119 - v1122 >= 4 then
if not v1125 then
v1125, v1126 = v452, 25
else
local v820 = (v452 - v1125).v430
if v820 < 150 then
v1125 = v1125:v788(v452, 0.05)
if v820 > v1126 then v1126 = v231.v515(v820, 150) end
end
end
end
local v1160 = false
if v458 then
if v767 == v60("return '\\v98\\v73\\v71\\v71\\v99'")() then
v1160 = true
elseif v1125 and v452 and (v452 - v1125).v430 <= v1126 + 30 then
v1160 = true
elseif not v1153() then
v1160 = true
end
end
if v1160 == v286.v298 then
v1128 = nil
else
v1128 = v1128 or v1119
if v1119 - v1128 >= 1.5 then
v286.v298 = v1160
v1128 = nil
v286.v297 = true
end
end
if v767 == v60("return '\\v67\\v100\\v62\\v77\\v61'")() and v285 and not v284 then
if v286.v298 or not v458 or not v1153() then
v1127 = v1127 or v1119
if v1119 - v1127 >= 3 then
v285 = false
v284 = true
v1127 = nil
v286.v297 = true
end
else
v1127 = nil
end
else
v1127 = nil
end
local v1161 = v1146()
local v472 = (v767 == v60("return '\\v67\\v100\\v62\\v77\\v61'")() and v1123) and (v1119 - v1123) or -1
if v767 == v60("return '\\v98\\v73\\v71\\v71\\v99'")() then
v286.v299 = v60("return '\\v98\\v73\\v71\\v71\\v99\\v114\\v402\\v64\\v68\\v67\\v114\\v63\\v100\\v75\\v62\\v113\\v76\\v100\\v403'")() .. (v1161 and (v60("return '\\v114\\v70\\v114\\v63\\v75\\v73\\v416\\v113\\v67\\v100\\v114\\v68\\v67\\v114'")() .. v1136(v1161)) or v60("return ''")())
else
v286.v299 = (v286.v298 and v60("return '\\v115\\v73\\v77\\v68\\v114\\v74\\v73\\v114\\v98\\v73\\v71\\v71\\v99\\v114\\v70\\v114'")() or v60("return ''")()) .. v60("return '\\v63\\v100\\v75\\v62\\v113\\v76\\v100\\v114\\v75\\v73\\v98\\v100\\v74\\v76\\v73'")()
.. (v1161 and (v60("return '\\v114\\v70\\v114'")() .. v1136(v1161) .. v60("return '\\v114\\v75\\v68\\v64\\v62\\v100\\v74\\v62\\v68\\v64'")()) or v60("return '\\v114\\v70\\v114\\v98\\v68\\v74\\v76\\v73\\v114\\v73\\v114\\v75\\v68\\v98\\v73\\v150\\v113\\v73\\v72\\v72\\v72'")())
end
local v222 = v634()
local v1162 = v223.v233 ~= false
if v222 and v590 and v205(v223.v236) == v60("return '\\v64\\v62\\v75\\v113\\v74\\v150'")() and #v223.v236 >= 6 then
local v588 = {
v485 = v223.v236, v244 = v156.v203, v1163 = v1161 or -1, v767 = v767 or v60("return '\\v98\\v73\\v71\\v71\\v99'")(),
v472 = v472, v233 = v1162, v122 = v286.v298,
}
if v1120 and v1162 then v588.v441 = v441() end
local v212, v591 = v200(v590, {
v592 = v222 .. v60("return '\\v66\\v100\\v63\\v113\\v66\\v68\\v416\\v62\\v75\\v100'")(), v593 = v60("return '\\v135\\v401\\v141\\v112'")(),
v635 = { [v60("return '\\v173\\v73\\v74\\v62\\v68\\v74\\v62\\v70\\v112\\v99\\v63\\v68'")()] = v60("return '\\v100\\v63\\v63\\v98\\v113\\v77\\v100\\v62\\v113\\v73\\v74\\v66\\v193\\v64\\v73\\v74'")() },
v594 = v152:v239(v588),
})
v1120 = false
if v212 and v205(v591) == v60("return '\\v62\\v100\\v71\\v98\\v68'")() then
local v639, v820 = v200(function() return v152:v214(v591.v594 or v60("return ''")()) end)
v1120 = v639 and v205(v820) == v60("return '\\v62\\v100\\v71\\v98\\v68'")() and v820.v1120 == true
end
end
v468.v471((v1120 and v223.v233 ~= false) and 0.33 or 1)
end
end)
local function v1164(v1165)
if not v257 then return end
v257 = false
v550 = false
if v1165 then v223.v224 = false end
v238()
v258 = false
v280 = false
for v253, v307 in v254(v303) do v200(function() v307:v1166() end) end
v303 = {}
v332()
v324()
v352(false)
v350()
v200(v387)
if v318 then v318:v351() end
v196.v199 = nil
end
if v671.v902 then
v671.v902.v863:v308(function() v1164(true) end)
end
v196.v199 = function() v1164(false) end
v267 = v277.v278() + v162.v166
v200(v672)
if v223.v224 or v196.v1167 == true then
v196.v1167 = nil
if v286.v296 then v286.v296.v650(true) end
v363(true)
end
]===]
local v1168 = (v197 and v197()) or v198
if v56 ~= v60("return ''")() then v1168.v235 = v56 end
if v78 ~= v60("return ''")() then v1168.v237 = v78 end
v1168.v562 = v128
if v205(v206) == v60("return '\\v207\\v69\\v74\\v77\\v62\\v113\\v73\\v74'")() then
v200(v206, v60("return '\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v72\\v98\\v69\\v100'")(), v128)
end
local v306, v652 = v1169(v128)
if not v306 then
v495(v60("return '\\v496\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v497\\v114\\v68\\v75\\v75\\v73\\v114\\v76\\v68\\v114\\v64\\v113\\v74\\v62\\v100\\v416\\v68\\v65\\v114'")() .. v202(v652))
return
end
local v212, v1170 = v1171(v306, function(v14) return v202(v14) .. v60("return '\\v570\\v74'")() .. v1172.v1173() end)
if not v212 then v495(v60("return '\\v496\\v173\\v73\\v113\\v74\\v174\\v100\\v75\\v67\\v497\\v114\\v68\\v75\\v75\\v73\\v114\\v100\\v73\\v114\\v68\\v416\\v68\\v77\\v69\\v62\\v100\\v75\\v65\\v114'")() .. v202(v1170)) end
