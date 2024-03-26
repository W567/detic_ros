python3 run_container.py -host wu-desktop -mount ./launch -name detection2d.launch \
    out_debug_img:=true \
    out_debug_segimg:=false \
    compressed:=false \
    device:=auto

python3 run_container.py -host wu-desktop -mount ./launch -name detection3d.launch \
    debug:=true \
    vocabulary:=custom \
    custom_vocabulary:=bottle,cup