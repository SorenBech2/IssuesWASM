# Blazor WebAssembly .NET 10 Debugger Crash Reproduction

This is a minimal reproduction project for a debugger crash issue in Blazor WebAssembly on .NET 10.

## Issue Description

When debugging a Blazor WebAssembly application targeting .NET 10 with ASP.NET JavaScript debugging enabled, the debugger crashes with a Mono WASM assertion when `HttpClient.GetAsync` is called within an async method.

### Error Messages
