# Graph Report - m-c-p---os-binaural-pro-demo  (2026-11-10)

## Corpus Check
- 9 files · ~82,565 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 2358 nodes · 5348 edges · 111 communities (64 shown, 43 thin omitted)
- Extraction: 94% EXTRACTED · 6% INFERRED · 0% AMBIGUOUS · INFERRED: 337 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- webgl-backgrounds.js
- _
- three.min.js
- At
- tn
- U
- constructor
- vt
- en
- sn
- St
- sr
- app.js
- ws
- eh
- Lt
- Lc
- W
- Xe
- Ce
- .applyMatrix4
- update
- .z
- .constructor
- Kn
- copy
- ke
- Ne
- yc
- .intersectMeshes
- .constructor
- Wn
- it
- .normalize
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
- .computeFrenetFrames
- bl
- ._update
- package.json
- no
- parse
- ls
- 🛠️ Arquitetura Técnica
- .update
- le
- uo
- ml
- yo
- setupTrackEventListeners
- ol
- en
- q
- .fromArray
- .toJSON
- .multiplyScalar
- nc
- uc
- unlockAppWithTracks
- K
- .copy
- _o
- ya
- us
- Jr
- .getRenderList
- .x
- .fromJSON
- ct
- fo
- .addAttribute
- manifest.json
- initBackground
- gr
- fl
- qc
- Tt
- Aa
- ge
- vercel.json
- checkAllCachesAndStartDownloads
- Mh
- ms
- ss
- Yl
- ln
- pl
- handleUnlockSubmit
- ic
- Tt
- rc
- Zc
- jt
- sw.js

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
- `tt()` --indirect_call--> `Y()`  [INFERRED]
  js/ogl.js → js/vendor/three.min.js
- `gt()` --indirect_call--> `tt()`  [INFERRED]
  js/vendor/three.min.js → js/ogl.js

## Import Cycles
- None detected.

## Communities (111 total, 43 thin omitted)

### Community 0 - "webgl-backgrounds.js"
Cohesion: 0.06
Nodes (61): gt, buildStrandsPalette(), easePower2InOut(), getOptimizedDPR(), hexToRgb(), hexToRgbArr(), initAcidSquares(), initAntigravity() (+53 more)

### Community 1 - "_"
Cohesion: 0.03
Nodes (49): _, ae(), at, bs(), bt(), ce(), ct(), dt (+41 more)

### Community 2 - "three.min.js"
Cohesion: 0.04
Nodes (28): Ba, bs, $c(), Ga, Hi(), hr(), intersectObject(), intersectObjects() (+20 more)

### Community 3 - "At"
Cohesion: 0.06
Nodes (4): me(), pe, At, fe

### Community 4 - "tn"
Cohesion: 0.06
Nodes (8): bo, dt(), $e(), is(), Ke(), Qe(), tn, ut()

### Community 5 - "U"
Cohesion: 0.05
Nodes (15): ai(), di(), fi(), gi(), hi(), ii(), li(), mi() (+7 more)

### Community 6 - "constructor"
Cohesion: 0.14
Nodes (23): ze, br(), constructor(), i(), er(), hl, l(), o() (+15 more)

### Community 8 - "en"
Cohesion: 0.07
Nodes (12): ca, Da, v(), en, t(), fh, hh, mn (+4 more)

### Community 9 - "sn"
Cohesion: 0.05
Nodes (10): an, cn, dn, fn, hn, on, pn, sn (+2 more)

### Community 11 - "sr"
Cohesion: 0.17
Nodes (8): he(), sr(), C(), et(), L(), N(), tt(), xs()

### Community 12 - "app.js"
Cohesion: 0.05
Nodes (37): appMain, audioCtxQueue, audioSourcesMap, badgePlayingCount, bgLayerActive, bgLayerNext, bgSlideshow, btnLock (+29 more)

### Community 13 - "ws"
Cohesion: 0.08
Nodes (40): j(), bi(), ds(), F(), G(), k(), V(), s() (+32 more)

### Community 16 - "Lc"
Cohesion: 0.08
Nodes (4): bc, getInput(), getOutput(), Lc

### Community 17 - "W"
Cohesion: 0.06
Nodes (17): be(), bi(), _i(), nn(), on, pn, pt, rn (+9 more)

### Community 18 - "Xe"
Cohesion: 0.09
Nodes (8): _a, cs, Do, go, Rs, Vs, Xe(), zo

### Community 19 - "Ce"
Cohesion: 0.05
Nodes (11): Ee(), Re(), Te(), xe(), Ce, gs, sh, ts() (+3 more)

### Community 20 - ".applyMatrix4"
Cohesion: 0.07
Nodes (5): ri(), ai, setFromCamera(), h(), xs

### Community 21 - "update"
Cohesion: 0.17
Nodes (10): ci, fi(), pi(), p(), V(), Si(), ti, update() (+2 more)

### Community 22 - ".z"
Cohesion: 0.08
Nodes (4): Gs(), Hs(), qs(), Xs()

### Community 23 - ".constructor"
Cohesion: 0.11
Nodes (19): d(), u(), dc, y(), gi(), v(), mc(), mi() (+11 more)

### Community 24 - "Kn"
Cohesion: 0.11
Nodes (4): fs, Jl, Kn, vl()

### Community 25 - "copy"
Cohesion: 0.08
Nodes (9): _e(), copy(), hs, qn, _s(), n(), _sceneToCubeUV(), updateMatrixWorld() (+1 more)

### Community 26 - "ke"
Cohesion: 0.09
Nodes (8): ci(), er, v(), ke, tr, R(), ue(), we()

### Community 29 - ".intersectMeshes"
Cohesion: 0.16
Nodes (3): Fs(), ki(), xn

### Community 31 - "Wn"
Cohesion: 0.13
Nodes (20): _allocateTargets(), _applyPMREM(), _blur(), _cleanup(), compileCubemapShader(), compileEquirectangularShader(), _compileMaterial(), fromCubemap() (+12 more)

### Community 32 - "it"
Cohesion: 0.16
Nodes (3): Ds(), it, St

### Community 33 - ".normalize"
Cohesion: 0.10
Nodes (4): S(), ht(), M(), b()

### Community 35 - "ar"
Cohesion: 0.08
Nodes (5): ar, kt(), mr, Ut(), yr

### Community 36 - "V"
Cohesion: 0.08
Nodes (4): De(), ji(), qi(), V

### Community 37 - "ei"
Cohesion: 0.13
Nodes (11): dispose(), ei, s(), gn(), a(), o(), ni, G() (+3 more)

### Community 39 - "jc"
Cohesion: 0.08
Nodes (3): bind(), getValue(), jc

### Community 41 - "tn"
Cohesion: 0.15
Nodes (6): fr(), A(), E(), m(), ns(), tn

### Community 42 - "bt"
Cohesion: 0.17
Nodes (4): bt, li(), Ra, Mt()

### Community 43 - "parseObject"
Cohesion: 0.14
Nodes (5): fa, $l, parseObject(), ta, tc

### Community 44 - "se"
Cohesion: 0.07
Nodes (3): as(), ia, se

### Community 47 - "nl"
Cohesion: 0.11
Nodes (3): il(), Ll, nl

### Community 48 - "re"
Cohesion: 0.09
Nodes (3): Ea(), re, rh

### Community 50 - ".computeFrenetFrames"
Cohesion: 0.17
Nodes (5): cr, dr(), Lt, pr(), ur()

### Community 54 - "package.json"
Cohesion: 0.12
Nodes (16): author, description, keywords, license, main, name, repository, type (+8 more)

### Community 55 - "no"
Cohesion: 0.16
Nodes (8): ao(), eo(), io(), no(), oo(), ro(), so(), xa

### Community 56 - "parse"
Cohesion: 0.14
Nodes (11): bindSkeletons(), ii, oc, parse(), parseAnimations(), parseGeometries(), parseImages(), parseSkeletons() (+3 more)

### Community 58 - "🛠️ Arquitetura Técnica"
Cohesion: 0.17
Nodes (11): 1. Web Audio DSP Chain (Anti-Clipping & Amplificação), 2. Mixagem Paralela e Time-Stretching, 3. Motor WebGL com 37 Shaders Nativos, 4. Persistência Offline com IndexedDB & Service Worker, 🛠️ Arquitetura Técnica, 👤 Autor, 🎧 Binaural Labs Pro — Interactive Portfolio Demo, 🚀 Como Executar Localmente (+3 more)

### Community 59 - ".update"
Cohesion: 0.16
Nodes (4): cs, is, rr, Ys()

### Community 62 - "ml"
Cohesion: 0.10
Nodes (3): el, ml, Rl

### Community 63 - "yo"
Cohesion: 0.14
Nodes (3): jo, qo, yo

### Community 64 - "setupTrackEventListeners"
Cohesion: 0.22
Nodes (11): applyPendingCachedSrcIfIdle(), connectTrackToWebAudio(), drawVisualizer(), handleTrackStoppedState(), hasAnyActiveOrDesiredTracks(), initAudioEngine(), nextTrackToken(), setupTrackEventListeners() (+3 more)

### Community 65 - "ol"
Cohesion: 0.16
Nodes (6): cl, load(), ol, setTexturePath(), ul, vc

### Community 67 - "q"
Cohesion: 0.23
Nodes (3): p(), q, zi()

### Community 69 - ".toJSON"
Cohesion: 0.11
Nodes (3): ac, r(), sc

### Community 73 - "unlockAppWithTracks"
Cohesion: 0.25
Nodes (11): calculateDecibels(), checkSavedSession(), renderTracks(), setMasterBoost(), setMasterVolume(), setupMasterBoostControls(), setupMasterVolumeControls(), setupSoundMasterWidget() (+3 more)

### Community 74 - "K"
Cohesion: 0.22
Nodes (3): br, K, kr

### Community 75 - ".copy"
Cohesion: 0.10
Nodes (7): Ie(), Ne(), or, Ot, ui(), ye(), zt

### Community 77 - "ya"
Cohesion: 0.29
Nodes (8): ho(), ja(), lo(), Na, to(), Va(), Wa(), ya

### Community 78 - "us"
Cohesion: 0.15
Nodes (5): clone(), kl, Ql, us(), b()

### Community 79 - "Jr"
Cohesion: 0.22
Nodes (7): Vr(), Jr(), kr(), nr(), qr(), vr(), zr()

### Community 82 - ".fromJSON"
Cohesion: 0.12
Nodes (4): Al, n(), parseShapes(), zl

### Community 83 - "ct"
Cohesion: 0.16
Nodes (3): ct(), es(), ns()

### Community 84 - "fo"
Cohesion: 0.24
Nodes (4): fo(), mo(), l(), po

### Community 86 - "manifest.json"
Cohesion: 0.20
Nodes (9): background_color, description, display, icons, name, orientation, short_name, start_url (+1 more)

### Community 87 - "initBackground"
Cohesion: 0.36
Nodes (9): getRandomGalleryFromPool(), initBackground(), changeBackground(), getNextBgUrl(), loadVideoSource(), playNextVideoTrack(), startBgInterval(), updateIndicator() (+1 more)

### Community 95 - "vercel.json"
Cohesion: 0.25
Nodes (7): cleanUrls, headers, outputDirectory, rewrites, $schema, trailingSlash, version

### Community 96 - "checkAllCachesAndStartDownloads"
Cohesion: 0.38
Nodes (7): checkAllCachesAndStartDownloads(), getCachedAudio(), openDB(), processDownloadQueue(), queueSingleTrackDownload(), saveCachedAudio(), setOrQueueCachedAudioSrc()

### Community 104 - "handleUnlockSubmit"
Cohesion: 0.40
Nodes (5): base64ToUint8Array(), deriveAesKey(), handleUnlockSubmit(), showUnlockError(), unlockVaultWithPasscode()

### Community 110 - "Tt"
Cohesion: 0.40
Nodes (3): Et, Tt(), Zh()

## Knowledge Gaps
- **106 isolated node(s):** `DEFAULT_TRACKS`, `VAULT_CONFIG`, `GALLERIES`, `CINEMATIC_VIDEOS`, `GALLERIES_POOL` (+101 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 725 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **43 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `_` connect `_` to `webgl-backgrounds.js`, `At`, `U`, `constructor`, `sr`, `W`, `Ce`, `.applyMatrix4`, `.z`, `copy`, `ke`, `.intersectMeshes`, `it`, `ar`, `V`, `tn`, `ks`, `.computeFrenetFrames`, `.update`, `le`, `en`, `q`, `K`, `.copy`, `Jr`, `.getRenderList`, `.x`, `.addAttribute`, `gr`?**
  _High betweenness centrality (0.337) - this node is a cross-community bridge._
- **Why does `ws()` connect `ws` to `three.min.js`, `tn`, `constructor`, `vt`, `en`, `St`, `sr`, `Lt`, `Xe`, `Ce`, `.applyMatrix4`, `update`, `.constructor`, `copy`, `ke`, `ei`, `xc`, `bt`, `se`, `parse`, `yo`, `.multiplyScalar`, `Tt`?**
  _High betweenness centrality (0.132) - this node is a cross-community bridge._
- **Why does `R()` connect `ke` to `_`, `ws`?**
  _High betweenness centrality (0.097) - this node is a cross-community bridge._
- **Are the 21 inferred relationships involving `ws()` (e.g. with `L()` and `R()`) actually correct?**
  _`ws()` has 21 INFERRED edges - model-reasoned connections that need verification._
- **What connects `DEFAULT_TRACKS`, `VAULT_CONFIG`, `GALLERIES` to the rest of the system?**
  _106 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `webgl-backgrounds.js` be split into smaller, more focused modules?**
  _Cohesion score 0.06218487394957983 - nodes in this community are weakly interconnected._
- **Should `_` be split into smaller, more focused modules?**
  _Cohesion score 0.03449367088607595 - nodes in this community are weakly interconnected._