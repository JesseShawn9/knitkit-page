# KnitKit2 Unraveler

Standalone receiving page for the KnitKit2 Cimbar batch extension.

- Open: https://jesseshawn9.github.io/knitkit-page/knitkit2/
- Use the matching offline batch sender, not the legacy QR sender or the unmodified Cimbar sender.
- The page includes its JS, WASM and Worker code. No file or camera data is uploaded.
- Completed batches are saved in the browser. An unfinished batch may need to be read again after refresh.
- Source, tests and third-party license material: [source.zip](source.zip).
- The decoder uses unmodified libcimbar v0.6.8, under MPL-2.0. Corresponding upstream source: https://github.com/sz3/libcimbar/tree/v0.6.8 .
- Existing root and Pocket pages are unchanged.

Automated protocol, real image-codec and synthetic-camera tests passed. Actual iPhone camera speed and long-running stability remain device-test items.
