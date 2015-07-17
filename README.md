Sass-HSB
====
Sassで、HSBとRGBの相互変換をする関数

##Usage

###import
`@import '_sass-hsb.scss';`

###call function

```:css
// calculation hue
background: calc-color-hue(#9673FF, -25); // #738aff

// calculation saturation
background: calc-color-saturation(#9673FF, -25); // #c5b2ff

// calculation bright
background: calc-color-bright(#9673FF, -25); // #7056bf
```