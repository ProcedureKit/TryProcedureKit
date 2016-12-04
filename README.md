# TryProcedureKit
This repository is used as part of the automated testing of [ProcedureKit](ProcedureKit/ProcedureKit).

It consists of branches which each contain an application that uses the _ProcedureKit_ framework.

## CocoaPods, `cocoapods` branch
Triggering a CI build of `HEAD` on the `cocoapods` branch will do the following:

1. Checkout the correct hash of _ProcedureKit_ (as a submodule)
2. Run `pod install` - to install _ProcedureKit_ via CocoaPods
3. Build & test the application - to check that `ProcedureKit` is available and compiles.