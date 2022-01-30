# zmk config for corne (crkbd)

west build -b nice_nano_v2 --pristine -- -DSHIELD=corne_left -DZMK_CONFIG="/home/timwalker/projects/zmk-crkbd/corne.config"


# layout

### default_layer

| | | | | | | — | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:-----:|:---:|:---:|:---:|:---:|:---:|:---:|
|  TAB |  Q  |  W  |  F  |  P  |  B  |   |  J  |  L   |  U  |  Y  |  ;  |   BSPC    |
|  ESC |  A  |  R  |  S  |  T  |  G  |   |  M  |  N   |  E  |  I  |  O  |    '      |
|      |  Z  |  X  |  C  |  D  |  V  |   |  K  |  H   |  ,  |  .  |  /  |   RET     |
| | | | **#** | **$** | **N** |          | **SN** | | **W** | | | |

#### legend
| | |
|---|---|
| **#** | numbers layer
| **$** | symbols layer
| **N** | navigation layer
| **SN** | space on press, navigation layer on hold
| **W** | window management layer

### symbols layer ($)

| | | | | | | — | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:-----:|:---:|:---:|:---:|:---:|:---:|:---:|
|    |  !  |  @  |  {  |  }  | "|" |   |  &  |  *  |  <  |  >  |     |     |
|    |  #  |  $  |  (  |  )  |  `  |   |  -  |  =  |  +  |  _  |     |     |
|    |  %  |  ^  |  [  |  ]  |  ~  |   |  /  |     |     |     |     |     |


# navigation layer (N)

| | | | | | | — | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:-----:|:---:|:---:|:---:|:---:|:---:|:---:|
|    |     |     |     |     |     |   |     | HOME| PGUP|     | END |     | DEL |
|    | CTRL| ALT | GUI | SHFT|     |   |     | LEFT| DOWN|  UP |RIGHT|     |     |
|    | UNDO| CUT |COPY |     | PSTE|   |     | <tab| PGDN|     |tab> |     |     |


# numbers layer (#)
| | | | | | | — | | | | | | |
|:---:|:---:|:---:|:---:|:---:|:---:|:-----:|:---:|:---:|:---:|:---:|:---:|:---:|
|    | F1  | F2  | F3  | F4  |     |   |     |  7  |  8  |  9  |     |     |
|    | F5  | F6  | F7  | F8  |     |   |     |  4  |  5  |  6  |     |     |
|    | F9  | F10 | F11 | F12 |     |   |     |  1  |  2  |  3  |     |     |
| | | | | | |                          | | 0 | . | | | | |

# windows/adjust layer

* Varies by keyboard and OS.
