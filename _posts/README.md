# Magisk Module to Improve Gaming Experience

If you use your phone for extensive gaming, this module is worth to try. FYI, this module adding the following code at the end. You can also manually adding these props into your build.prop file

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
```

Those prop value (above) will enable **tile rendering**, **utilize processing power** and **improve 3d performance**.

Check another [usefull android build props optimatization](https://mi.knoacc.org/20-more-useful-android-build-prop-tweaks-for-better-experience.