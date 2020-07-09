# We are using CLANG6 (soon to be deprecated) rather than CLANG10 as
#  there are problems compiling ffmpeg 4.3 from source with CLANG10
FROM trzeci/emscripten:1.39.4

# Bring in all of our source files
COPY ./ ./

# Build the lzw-wasm.js
RUN make lzw-wasm.js

ENTRYPOINT sleep 10000