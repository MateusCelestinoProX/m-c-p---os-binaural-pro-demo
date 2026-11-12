# Graph Report - m-c-p---os-binaural-pro-demo  (2026-11-12)

## Corpus Check
- 9 files · ~80,321 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 2345 nodes · 5327 edges · 123 communities (54 shown, 66 thin omitted)
- Extraction: 94% EXTRACTED · 6% INFERRED · 0% AMBIGUOUS · INFERRED: 337 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `afccb34d`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- webgl-backgrounds.js
- _
- three.min.js
- At
- tn
- U
- constructor
- vt
- .setAttribute
- sn
- St
- ws
- app.js
- gt
- eh
- Lt
- Lc
- pt
- _a
- Ce
- en
- update
- .z
- .constructor
- Kn
- copy
- .copy
- Ne
- yc
- .computeFrenetFrames
- .constructor
- _fromTexture
- it
- .subVectors
- yt
- ar
- V
- ei
- pt
- jc
- xc
- tn
- bt
- parseObject
- se
- ks
- nl
- re
- ec
- be
- bl
- .equals
- ._update
- package.json
- Xe
- .fromJSON
- ls
- 🛠️ Arquitetura Técnica
- W
- le
- mc
- ml
- yo
- setupTrackEventListeners
- e
- en
- q
- .dispatchEvent
- .toJSON
- .multiplyScalar
- nc
- .updateMatrix
- unlockAppWithTracks
- K
- zt
- Na
- .translateOnAxis
- ys
- .update
- .getRenderList
- .x
- Al
- ct
- fo
- .addAttribute
- manifest.json
- initBackground
- gr
- fl
- qc
- Tt
- Ll
- ge
- .setHSL
- vercel.json
- checkAllCachesAndStartDownloads
- .isEmpty
- ms
- ss
- Rl
- .rotateOnAxis
- el
- bind
- sc
- Te
- ic
- hs
- Et
- rc
- Zc
- tc
- ts
- drawVisualizer
- Do
- jt
- sw.js
- .copyLinearToSRGB
- .convertSRGBToLinear
- zo
- bo

## God Nodes (most connected - your core abstractions)
1. `_` - 208 edges
2. `Lt` - 135 edges
3. `copy()` - 128 edges
4. `vt` - 90 edges
5. `ws()` - 70 edges
6. `tn` - 65 edges
7. `St` - 60 edges
8. `Ce` - 59 edges
9. `sn` - 53 edges
10. `se` - 49 edges

## Surprising Connections (you probably didn't know these)
- `xi()` --indirect_call--> `f()`  [INFERRED]
  js/ogl.js → js/vendor/three.min.js
- `ws()` --indirect_call--> `R()`  [INFERRED]
  js/vendor/three.min.js → js/ogl.js
- `ws()` --indirect_call--> `L()`  [INFERRED]
  js/vendor/three.min.js → js/ogl.js
- `et()` --indirect_call--> `S()`  [INFERRED]
  js/ogl.js → js/vendor/three.min.js
- `et()` --indirect_call--> `Y()`  [INFERRED]
  js/ogl.js → js/vendor/three.min.js

## Import Cycles
- None detected.

## Communities (123 total, 66 thin omitted)

### Community 0 - "webgl-backgrounds.js"
Cohesion: 0.06
Nodes (61): gt, buildStrandsPalette(), easePower2InOut(), getOptimizedDPR(), hexToRgb(), hexToRgbArr(), initAcidSquares(), initAntigravity() (+53 more)

### Community 1 - "_"
Cohesion: 0.03
Nodes (49): _, ae(), at, bs(), bt(), ce(), ct(), dt (+41 more)

### Community 2 - "three.min.js"
Cohesion: 0.03
Nodes (40): Vr(), bi(), bs, $c(), compileCubemapShader(), compileEquirectangularShader(), _compileMaterial(), er() (+32 more)

### Community 3 - "At"
Cohesion: 0.06
Nodes (4): me(), pe, At, fe

### Community 5 - "U"
Cohesion: 0.05
Nodes (16): ai(), ci(), di(), fi(), gi(), hi(), ii(), li() (+8 more)

### Community 6 - "constructor"
Cohesion: 0.17
Nodes (21): br(), constructor(), i(), t(), gi(), l(), o(), c() (+13 more)

### Community 8 - ".setAttribute"
Cohesion: 0.11
Nodes (10): ca, ci, v(), Ga, mn, i(), Pa, uh() (+2 more)

### Community 9 - "sn"
Cohesion: 0.05
Nodes (10): an, cn, dn, fn, hn, ln, on, pn (+2 more)

### Community 11 - "ws"
Cohesion: 0.17
Nodes (11): dispose(), C(), setValue(), ws(), Ct(), Dt(), It(), Pt() (+3 more)

### Community 12 - "app.js"
Cohesion: 0.06
Nodes (31): appMain, audioCtxQueue, audioSourcesMap, badgePlayingCount, bgLayerActive, bgLayerNext, bgSlideshow, btnPauseAll (+23 more)

### Community 13 - "gt"
Cohesion: 0.12
Nodes (31): j(), L(), tt(), ds(), G(), k(), V(), s() (+23 more)

### Community 16 - "Lc"
Cohesion: 0.08
Nodes (4): bc, getInput(), getOutput(), Lc

### Community 17 - "pt"
Cohesion: 0.11
Nodes (7): bi(), _i(), pt, Si(), Ti(), vi(), zi()

### Community 20 - "en"
Cohesion: 0.14
Nodes (3): en, Si(), ti

### Community 21 - "update"
Cohesion: 0.13
Nodes (11): fi(), jn(), pi(), p(), V(), update(), M(), wh() (+3 more)

### Community 22 - ".z"
Cohesion: 0.08
Nodes (4): Gs(), Hs(), qs(), Xs()

### Community 23 - ".constructor"
Cohesion: 0.13
Nodes (17): _allocateTargets(), d(), u(), y(), v(), mi(), f(), g() (+9 more)

### Community 24 - "Kn"
Cohesion: 0.05
Nodes (10): n(), fs, Jl, kl, Kn, parseShapes(), Ql, vl() (+2 more)

### Community 25 - "copy"
Cohesion: 0.08
Nodes (9): _e(), copy(), Ea(), qn, _sceneToCubeUV(), updateMatrixWorld(), h(), xs (+1 more)

### Community 26 - ".copy"
Cohesion: 0.06
Nodes (17): er, v(), he(), ke, Lt, Ot, sr(), C() (+9 more)

### Community 27 - "Ne"
Cohesion: 0.09
Nodes (3): ri(), ai, Ne

### Community 29 - ".computeFrenetFrames"
Cohesion: 0.15
Nodes (4): cr, dr(), ki(), pr()

### Community 31 - "_fromTexture"
Cohesion: 0.29
Nodes (10): _applyPMREM(), _blur(), _cleanup(), fromCubemap(), fromEquirectangular(), fromScene(), _fromTexture(), _halfBlur() (+2 more)

### Community 32 - "it"
Cohesion: 0.13
Nodes (4): Ds(), it, St, ui()

### Community 33 - ".subVectors"
Cohesion: 0.09
Nodes (3): S(), ht(), rh

### Community 34 - "yt"
Cohesion: 0.05
Nodes (4): Da, ia, la, yt

### Community 35 - "ar"
Cohesion: 0.07
Nodes (6): ar, kt(), mr, Ut(), yr, je

### Community 36 - "V"
Cohesion: 0.08
Nodes (4): De(), ji(), qi(), V

### Community 37 - "ei"
Cohesion: 0.14
Nodes (10): ei, s(), i(), a(), o(), ni, rt, Tt() (+2 more)

### Community 41 - "tn"
Cohesion: 0.14
Nodes (7): fr(), A(), E(), m(), p(), ns(), tn

### Community 42 - "bt"
Cohesion: 0.13
Nodes (5): Aa, bt, li(), Ra, Mt()

### Community 43 - "parseObject"
Cohesion: 0.12
Nodes (6): fa, $l, parseObject(), Rs, ta, Vs

### Community 49 - "ec"
Cohesion: 0.10
Nodes (4): Ys(), ec, _s(), n()

### Community 50 - "be"
Cohesion: 0.16
Nodes (8): be(), nn(), rn, l(), Se(), zr, h(), l()

### Community 54 - "package.json"
Cohesion: 0.12
Nodes (16): author, description, keywords, license, main, name, repository, type (+8 more)

### Community 55 - "Xe"
Cohesion: 0.09
Nodes (22): ao(), co(), cs, eo(), fh, go, hh, ho() (+14 more)

### Community 56 - ".fromJSON"
Cohesion: 0.09
Nodes (6): bindSkeletons(), dl, oc, parseGeometries(), parseSkeletons(), pl

### Community 58 - "🛠️ Arquitetura Técnica"
Cohesion: 0.17
Nodes (11): 1. Web Audio DSP Chain (Anti-Clipping & Amplificação), 2. Mixagem Paralela e Time-Stretching, 3. Motor WebGL com 37 Shaders Nativos, 4. Persistência Offline com IndexedDB & Service Worker, 🛠️ Arquitetura Técnica, 👤 Autor, 🎧 Binaural Labs Pro — Interactive Portfolio Demo, 🚀 Como Executar Localmente (+3 more)

### Community 59 - "W"
Cohesion: 0.09
Nodes (9): Fs(), is, on, pn, rr, un, W, xn (+1 more)

### Community 63 - "yo"
Cohesion: 0.14
Nodes (3): jo, qo, yo

### Community 64 - "setupTrackEventListeners"
Cohesion: 0.31
Nodes (10): applyPendingCachedSrcIfIdle(), connectTrackToWebAudio(), handleTrackStoppedState(), hasAnyActiveOrDesiredTracks(), initAudioEngine(), nextTrackToken(), setupTrackEventListeners(), syncAudioContextState() (+2 more)

### Community 65 - "e"
Cohesion: 0.09
Nodes (19): cl, hl, ii, il(), load(), ol, or(), parse() (+11 more)

### Community 73 - "unlockAppWithTracks"
Cohesion: 0.25
Nodes (11): calculateDecibels(), escapeHtml(), renderTracks(), setMasterBoost(), setMasterVolume(), setupMasterBoostControls(), setupMasterVolumeControls(), setupSoundMasterWidget() (+3 more)

### Community 74 - "K"
Cohesion: 0.19
Nodes (3): br, K, kr

### Community 75 - "zt"
Cohesion: 0.24
Nodes (4): Ie(), Ne(), or, zt

### Community 76 - "Na"
Cohesion: 0.18
Nodes (5): Ba, Ko, Na, _o, to()

### Community 83 - "ct"
Cohesion: 0.15
Nodes (3): ct(), es(), ns()

### Community 84 - "fo"
Cohesion: 0.32
Nodes (3): fo(), l(), po

### Community 86 - "manifest.json"
Cohesion: 0.20
Nodes (9): background_color, description, display, icons, name, orientation, short_name, start_url (+1 more)

### Community 87 - "initBackground"
Cohesion: 0.36
Nodes (9): getRandomGalleryFromPool(), initBackground(), changeBackground(), getNextBgUrl(), loadVideoSource(), playNextVideoTrack(), startBgInterval(), updateIndicator() (+1 more)

### Community 93 - "ge"
Cohesion: 0.20
Nodes (3): F(), z(), ge

### Community 94 - ".setHSL"
Cohesion: 0.33
Nodes (3): dt(), Qe(), ut()

### Community 95 - "vercel.json"
Cohesion: 0.25
Nodes (7): cleanUrls, headers, outputDirectory, rewrites, $schema, trailingSlash, version

### Community 96 - "checkAllCachesAndStartDownloads"
Cohesion: 0.38
Nodes (7): checkAllCachesAndStartDownloads(), getCachedAudio(), openDB(), processDownloadQueue(), queueSingleTrackDownload(), saveCachedAudio(), setOrQueueCachedAudioSrc()

## Knowledge Gaps
- **100 isolated node(s):** `DEFAULT_TRACKS`, `GALLERIES`, `CINEMATIC_VIDEOS`, `GALLERIES_POOL`, `webglTypes` (+95 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 717 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **66 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `_` connect `_` to `webgl-backgrounds.js`, `three.min.js`, `At`, `U`, `pt`, `.z`, `copy`, `.copy`, `Ne`, `.computeFrenetFrames`, `it`, `ar`, `V`, `tn`, `ks`, `ec`, `be`, `W`, `le`, `en`, `q`, `.dispatchEvent`, `K`, `zt`, `.translateOnAxis`, `.update`, `.getRenderList`, `.x`, `.addAttribute`, `gr`, `.rotateOnAxis`, `Te`?**
  _High betweenness centrality (0.336) - this node is a cross-community bridge._
- **Why does `ws()` connect `ws` to `three.min.js`, `tn`, `constructor`, `vt`, `.setAttribute`, `St`, `gt`, `Lt`, `_a`, `update`, `.constructor`, `copy`, `.copy`, `Ne`, `yt`, `ei`, `bt`, `se`, `.fromJSON`, `yo`, `.dispatchEvent`, `.multiplyScalar`?**
  _High betweenness centrality (0.119) - this node is a cross-community bridge._
- **Why does `R()` connect `.copy` to `_`, `ws`?**
  _High betweenness centrality (0.095) - this node is a cross-community bridge._
- **Are the 21 inferred relationships involving `ws()` (e.g. with `L()` and `R()`) actually correct?**
  _`ws()` has 21 INFERRED edges - model-reasoned connections that need verification._
- **What connects `DEFAULT_TRACKS`, `GALLERIES`, `CINEMATIC_VIDEOS` to the rest of the system?**
  _100 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `webgl-backgrounds.js` be split into smaller, more focused modules?**
  _Cohesion score 0.06134453781512605 - nodes in this community are weakly interconnected._
- **Should `_` be split into smaller, more focused modules?**
  _Cohesion score 0.03449367088607595 - nodes in this community are weakly interconnected._