<div align="center">
	<span style="font-weight: bold"> English | <a href=README_CN.md> 中文 </a> </span>
</div>

## SGSI-build-action

Don't build directly in this warehouse, please fork this warehouse first, and then go to your own warehouse to build!

## Instructions:
```

1. Fork this warehouse
2. Edit Config.env:
     ROM_URL: https://bigota.d.miui.com/V12.5.3.0.RFXCNXM/miui_CRUX_V12.5.3.0.RFXCNXM_190e6aea41_11.0.zip
     ZIP_NAME: MIUI
     OS_TYPE: GIS
     BUILD_TYPE: a
     REPACK_NAME: 1
3. After modification, click Start commit -> Actions tab -> Star -> SGSI-Build
```

 
## Output result
Download the results in [Release](../../releases)
Files larger than 2G will be automatically uploaded using sub-volume compression
If the upload result is sub-volume compression, download all sub-volumes and merge them with the following command:
```

cat upload/*> SGSI.zip‌‌
```

## Links
Android R Version: [Action-SGSI-build](https://github.com/XayahSuSuSu/Action-SGSI-build)
