use_relative_paths = True

vars = {
  "checkout_chromium": False,
}

deps = {
  "buildtools"                            : "https://chromium.googlesource.com/chromium/buildtools.git@505de88083136eefd056e5ee4ca0f01fe9b33de8",
  "common"                                : "https://skia.googlesource.com/common.git@9737551d7a52c3db3262db5856e6bcd62c462b92",

  "../src": {
    "url": "https://chromium.googlesource.com/chromium/src.git@e96090c328fe6b9edfffb9ad479dc89ff364ed49",
    "condition": "checkout_chromium",
  },
}

recursedeps = [
  "common",
  "../src",
]

gclient_gn_args_from = 'src'
