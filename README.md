# Box
![Build](https://shields.io/github/workflow/status/xczxcx2255/TVBox-takagen99/Test%20Build?event=push&logo=github&label=Build)
[![Download](https://img.shields.io/github/v/release/xczxcx2255/TVBox-takagen99?color=orange&logoColor=orange&label=Download&logo=DocuSign)](https://github.com/xczxcx2255/TVBox-takagen99/releases) 
[![Total](https://shields.io/github/downloads/xczxcx2255/TVBox-takagen99/total?logo=Bookmeter&label=Counts&logoColor=yellow&color=yellow)](https://github.com/xczxcx2255/TVBox-takagen99/releases)

Dynamic Wallpaper for sharing :
https://takagen-wallpaper.herokuapp.com

App default settings can be set here :
/src/main/java/com/github/tvbox/osc/base/App.java

    private void initParams() {

        putDefault(HawkConfig.HOME_REC, 2);       // Home Rec 0=豆瓣, 1=推荐, 2=历史
        putDefault(HawkConfig.PLAY_TYPE, 1);      // Player   0=系统, 1=IJK, 2=Exo
        putDefault(HawkConfig.IJK_CODEC, "硬解码");// IJK Render 软解码, 硬解码
        putDefault(HawkConfig.DOH_URL, 2);        // DNS
        putDefault(HawkConfig.SEARCH_VIEW, 2);    // Text or Picture

    }
