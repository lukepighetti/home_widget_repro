# hw

After adding a Widget Extension in Xcode and `google_mlkit_barcode_scanner` to dependencies, the builds in Xcode stop working, but continue to work with `flutter run`.

It seems that the widget will not be installed to Simulator unless you disable the dependency and launch the app from xcode.