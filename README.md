# Lỗi "Couldn't find package "@rollup/rollup-freebsd-arm64@4.24.1" required by "rollup@^4.20.0" on the "npm" registry."

- Fix : Vào files package.json thêm 
     "resolutions": {
    "rollup": "4.24.0"
  },
