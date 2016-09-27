# ns-hello-world-angular
Sample project for NativeScript Angular2 support in AppBuilder.

### Test in AppBuilder
Add the following dependencies to your project:
```
    "nativescript-angular": "1.0.0",
    "@angular/core": "2.0.0",
    "@angular/common": "2.0.0",
    "@angular/compiler": "2.0.0",
    "@angular/platform-browser": "2.0.0",
    "@angular/platform-browser-dynamic": "2.0.0",
    "@angular/platform-server": "2.0.0",
    "@angular/forms": "2.0.0",
    "@angular/router": "3.0.0",
    "reflect-metadata": "0.1.8",
    // NOTE: When using npm 2, @angular/http must be installed last as it has some PEER DEPENDENCIES which will cause failure in case it's installed before the other dependencies.
    "@angular/http": "2.0.0",
```

After that transpilation, build and deploy should work.
