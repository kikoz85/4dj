# Third-party notices

4DJ includes third-party components under their own licenses.

## Outside the dependency tree

- **Demucs v4 (htdemucs) model** — MIT License, Copyright (c) Meta
  Platforms, Inc. and affiliates. Used by StemX to separate stems.
- **ONNX Runtime** — MIT License, Copyright (c) Microsoft Corporation.
  Linked into the StemX helper (`fourdj-stemx`) through the `ort` crate;
  on Intel Macs Microsoft's own 1.23.2 library ships unchanged in the app
  bundle (`Contents/Frameworks/libonnxruntime.dylib`) and is loaded at run
  time.
