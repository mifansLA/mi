---
title: "[Magisk Module] Improve Gaming Experience, No more Lags!"
excerpt: Magisk Module for better gaming experience by adding custom props
categories:
 - Magisk Modul
tags:
 - build prop
 - mod android gaming
 - better gaming magisk
 - magisk build prop
 - pubg mobile no lag
header:
 og_image: /assets/image/pubg-no-lag-tweaks.png
 image: /assets/image/pubg-no-lag-tweaks.png
 caption: PUBG Mobile Tweaks
 teaser: /assets/image/improve-gaming-xperience.jpeg

---
If you use your phone for extensive gaming, this module is worth to try. I am using this prop value into my phone manually after experiencing lag while playing PUBG Mobile on my android phone. This modified build prop has increasing my gaming experience. But (maybe) if someone want to try will facing difficulties to implementing this. So [I decided](https://mi.knoacc.org/) to make this build prip tweaking easy to addopt by creating simple magisk module.

![Improve Gaming Xperience](/assets/image/improve-gaming-xperience.jpeg)

FYI, this module adding the following code at the end. You can also manually adding these props into your build.prop file if you have ability to do that. If not, you can download the **Improve Game Xperience** magisk module [below](download-module), and install it directly from Magisk Manager or custom recovery. Off course You need [Magisk Systemless Interface installed](https://www.google.co.id/amp/s/www.knoacc.org/2017/04/penjelasan-magisk-root-cara-sembunyikan-status-root.html) on your phone.

{% include inarticle.html %}

````
persist.sys.NV_FPSLIMIT=60
persist.sys.NV_POWERMODE=1
persist.sys.NV_PROFVER=15
persist.sys.NV_STEREOCTRL=0
persist.sys.NV_STEREOSEPCHG=0
persist.sys.NV_STEREOSEP=20
persist.sys.purgeable_assets=1
debug.enabletr=true
debug.qctwa.preservebuf=1
dev.pm.dyn_samplingrate=1
video.accelerate.hw=1
ro.vold.umsdirtyratio=20
debug.overlayui.enable=1
debug.egl.hw=1
ro.fb.mode=1
hw3d.force=1
persist.sys.ui.hw=1
ro.sf.compbypass.enable=0
debug.sf.hw=1
debug.composition.type=c2d
persist.sys.composition.type=c2
debug.performance.tuning=1
ro.media.dec.jpeg.memcap=8000000
ro.media.enc.hprof.vid.bps=8000000
ro.media.dec.aud.wma.enabled=1
ro.media.dec.vid.wmv.enabled=1
ro.media.cam.preview.fps=0
ro.media.codec_priority_for_thumb=so
````

Those prop value (above) will enable **tile rendering**, **utilize processing power** and **improve 3d performance**.
## Download Module

{% include adsense1.html %}

| Module | pCloud | MEGA |
|---|:---:|:---:|
| Improve Game Xperience v1 | [Download](/dl/pcloud?code=XZ3QhT7Z7XkM33T2YfkKNyVXT2s3jBwtc0MX&size=14KB&name=ImproveGamingXperience.zip){: .btn.btn--primary} | [Download](/dl/mega?hash=cg0DHQ6Q!VIdqqmwelYL43KWEwOkW1HvZ4TrtebbRY7hter1Jc1Y&size=14KB&name=ImproveGamingXperience.zip){: .btn.btn--primary} |

Check another [usefull android build props optimatization](https://mi.knoacc.org/20-more-useful-android-build-prop-tweaks-for-better-experience).
