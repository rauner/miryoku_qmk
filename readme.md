# QMK

## adjust layout
users/manna-harbour_miryoku/miryoku_babel
the standart is MIRYOKU_ALTERNATIVES_BASE_COLEMAKDH

add a alternative to list and change layout there

## current changes

### compile and flash
qmk compile -c -kb crkbd -km manna-harbour_miryoku -e MIRYOKU_NAV=VI -e MIRYOKU_ALPHAS=SEBASTIAN
### ALPHAS
move home row mod keys one step to inner, ctrl shift super alt
