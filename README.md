# Knotcress 1.0 TEST
Native Android fixed-anchor Planarity/Untangle. Android8+ (min26), target35. Package com.gg007.knotcress. Twelve original connected non-isomorphic graphs.

## Rules
Planarity/Untangle, fixed-anchor edition. Six lettered nodes stay connected by the same straight links. Tap a node, then one of nine anchors. Moving to an occupied anchor swaps its two nodes. Only edges sharing an endpoint may meet there. No other crossing, touch, overlap or node resting on an unrelated edge is allowed. Red lines mark every edge involved in a conflict. Empty anchors do not obstruct edges. Tap CHECK when no red lines remain; any valid arrangement wins. This edition uses nine fixed anchors instead of free dragging. Twelve original connected non-isomorphic graphs, each with a known valid layout and a tangled start. Multiple solutions are allowed. Unlimited moves, undo, reset, next, level selection, saved palette and optional anchor numbers. Node letters always remain visible.

## Download and status
https://mega.co.nz/#!hVtSXJoa!Ix7ICdcpTtaj6x9Z2BWf_wv_Wtp9tLCarC7FGeaqA2k
APK SHA256 30d771fb8a2abf3e75c3d9e0a442aacf057d556fad79aa6fad0a50d3fc6b4c6c; 20974 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous downloaded bytes match. No requested permissions. Original icon unchanged.

## Checks
Independent exact parametric segment and dot-product point oracle agrees with production orientation/bounding geometry for all 725,760 six-node placements across twelve graphs and all 3,024 distinct-endpoint segment cases on nine anchors. 18,424 valid layouts counted in total; no uniqueness claim. Tap/select/move/swap/cancel, undo, failed check, solved lock, replay, bounds and reset pass. Generator verifies connected non-isomorphic graphs and known crossing-free placements. Actual drawing-adapter game taps, menu/levels/privacy/settings and saved palette/anchor numbers pass. Six drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Reviewed all 170 prior studio mechanics and all 803 web registry records. Chromaring changes colors on a fixed graph; Knotcress moves graph vertices while preserving connections. Starstitch chooses an edge-traversal order; Knotcress instead solves spatial segment crossings and node-on-edge obstructions. Fixed-anchor swapping is not Fifteen sliding, because no vacancy-adjacency rule or tile-order goal exists. No Planarity/Untangle mechanic match found. This is an adaptation of the known game, not a global invention claim. Original generated boards, implementation and visuals; no source puzzles, code or art copied. Recovered repository corpus remains partial.
Rules https://docs.puzzles-game.com/en/untangle ; university model https://ccl.northwestern.edu/netlogo/models/Planarity .

## Build
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/knot-test src/com/gg007/knotcress/Board.java BoardTest.java then java -cp /tmp/knot-test com.gg007.knotcress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret is included.

## Privacy and branding
Knotcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, anchor numbers and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 original icon, menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative171-card studio and published catalog/studio sources and updater privately preserved at https://files.instinct.com/glxi3d35jdvh-knotcress-source-archive . Repository https://github.com/iLanis-agent/knotcress holds README only; full Git source commit pending. Existing Jekyll static includes retained without changes; no Pages settings changes or client loader. Both site publications verified separately.
