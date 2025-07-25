Last build command :

`west build -p -b "nice_nano_v2" -S studio-rpc-usb-uart -S zmk-usb-logging -- -DZMK_CONFIG=/workspaces/zmk-config/config/ -DSHIELD="gadget_futuriste_11 nice_view_adapter nice_view" -DCONFIG_ZMK_STUDIO=y`

- west build -p -b nice_nano_v2 -- -DSHIELD="some_native_shield nice_view"


west build -p -b "nice_nano_v2" -- -DZMK_CONFIG=/workspaces/zmk-config/config/ -DSHIELD="gadget_futuriste_11"`