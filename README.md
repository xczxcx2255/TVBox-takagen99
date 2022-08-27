# Box
![Build](https://shields.io/github/workflow/status/xczxcx2255/TVBox-takagen99/Test%20Build?event=push&logo=github&label=Build)
[![Download](https://img.shields.io/github/v/release/xczxcx2255/TVBox-takagen99?color=orange&logoColor=orange&label=Download&logo=DocuSign)](https://github.com/xczxcx2255/TVBox-takagen99/releases) 
[![Total](https://shields.io/github/downloads/xczxcx2255/TVBox-takagen99/total?logo=Bookmeter&label=Counts&logoColor=yellow&color=yellow)](https://github.com/xczxcx2255/TVBox-takagen99/releases)

Dynamic Wallpaper for sharing :
https://takagen-wallpaper.herokuapp.com

App default settings can be set here :
/src/main/java/com/github/tvbox/osc/base/App.java

    private void initParams() {

        if (!Hawk.contains(HawkConfig.PLAY_TYPE)) {
            Hawk.put(HawkConfig.PLAY_TYPE, 1);
        }

        // HW Render
        if (!Hawk.contains(HawkConfig.IJK_CODEC)) {
            Hawk.put(HawkConfig.IJK_CODEC, "硬解码");
        }

        // DNS
        if (!Hawk.contains(HawkConfig.DOH_URL)) {
            Hawk.put(HawkConfig.DOH_URL, 2);
        }

        // Search Mode : Text or Picture
        if (!Hawk.contains(HawkConfig.SEARCH_VIEW)) {
            Hawk.put(HawkConfig.SEARCH_VIEW, 2);
        }

    }
