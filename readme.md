# zmk config for corne (crkbd)

west build -b nice_nano_v2 --pristine -- -DSHIELD=corne_left -DZMK_CONFIG="/home/timwalker/projects/zmk-crkbd/corne.config"

                adjust_layer {
// -----------------------------------------------------------------------------------------
// | RGB BRI+ | RGB SAT+ | RGB HUE+ | RGB ANI+ |    | RGB TOG |   |       |     |     |     |     | RESET  |
// | RGB BRI- | RGB SAT- | RGB HUE- | RGB ANI+ |    |         |   |       |     |     |     |     |        |
// | BT CLR   |          |          |          |    |         |   |       |     |     |     |     |        |
//                                              |     |     |     |     |     |
                        bindings = <
   &rgb_ug RGB_BRI &rgb_ug RGB_SAI &rgb_ug RGB_HUI &rgb_ug RGB_EFF &none &rgb_ug RGB_TOG &none    &none &none &none &none &none &reset
   &rgb_ug RGB_BRD &rgb_ug RGB_SAD &rgb_ug RGB_HUD &rgb_ug RGB_EFR &none &none              &none        &none        &none        &none        &none        &none
   &bt BT_CLR      &bt SEL_0       &bt SEL_1       &rgb_ug RGB_COLOR_HSB(128,100,100) &none &none              &none       &none        &none        &none        &none        &none
                        &trans     &trans      &trans       &trans        &trans      &trans
                        >;
                };
