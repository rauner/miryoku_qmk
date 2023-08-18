# QMK
## compile
qmk compile -c -kb crkbd -km manna-harbour_miryoku \
  -e MIRYOKU_ALPHAS=QWERTY \
  -e MIRYOKU_EXTRA=COLEMAKDH \
  -e MIRYOKU_TAP=QWERTY \
  -e MIRYOKU_NAV=INVERTEDT \
  -e MIRYOKU_CLIPBOARD=WIN \
  -e MIRYOKU_LAYERS=FLIP # build for crkbd with alternative layouts
## flash

qmk flash -c -kb crkbd -km manna-harbour_miryoku # build for crkbd and flash


## adjust layout
users/manna-harbour_miryoku/miryoku_babel
the standart is MIRYOKU_ALTERNATIVES_BASE_COLEMAKDH

add a alternative to list and change layout there
