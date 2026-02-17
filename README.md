<img src="Theia-sdk-unity-2022-3-packages.png" width="200px" alt="Theia SDK">

# Theia SDK - Core Package

Eye tracking SDK for Unity VR development.

## Installation via Unity Package Manager

**Unity Package Manager Import URL:**
```
https://github.com/RandyHaylor/theia-sdk-core.git
```

**How to install:**
1. Open Unity Package Manager (Window > Package Manager)
2. Click the "+" button and select "Add package from git URL..."
3. Paste the URL above
4. Click "Add"

## What's Included

- HarmonEyesSDK.dll (precompiled runtime)
- Eye tracking common scripts (AnalyzeEyeTrackingData, EyeTrackingConfig)
- HarmonEyes.EyeTracking assembly with namespace support
- Third-party dependencies (ONNX Runtime, Android libs)

## Requirements

- Unity 2022.3 or later
- Dependencies installed automatically: TextMeshPro, Newtonsoft.Json

## Version

Current version: 3.4.1

---

## Platform Samples

After installing the core SDK, add platform-specific samples. Each sample is a separate package that installs to the Packages folder, then you import the sample content to your Assets folder where you can modify it.

**Installation steps:**
1. Install a sample package via Unity Package Manager (URLs below)
2. Find the sample in Package Manager's package list
3. Expand the "Samples" section in the package details
4. Click "Import" to copy sample content to your Assets folder

**⚠️ Important:** Install only ONE platform sample per project to avoid dependency conflicts.

**Unity Package Manager Import URLs** (paste in Unity: Window > Package Manager > + > Add package from git URL):

### Unity 2022.3 LTS Samples

**Oculus/Meta Quest:**
```
https://github.com/RandyHaylor/theia-sdk-unity2022-3-lts-samples.git?path=/OculusSample
```

**HTC VIVE:**
```
https://github.com/RandyHaylor/theia-sdk-unity2022-3-lts-samples.git?path=/HTCViveSample
```

**Varjo (Experimental):**
```
https://github.com/RandyHaylor/theia-sdk-unity2022-3-lts-samples.git?path=/VarjoSample
```

---

### Unity 6 LTS Samples

**Oculus/Meta Quest:**
```
https://github.com/RandyHaylor/theia-sdk-unity6-lts-samples.git?path=/OculusSample
```

**HTC VIVE:**
```
https://github.com/RandyHaylor/theia-sdk-unity6-lts-samples.git?path=/HTCViveSample
```

**Varjo (Experimental):**
```
https://github.com/RandyHaylor/theia-sdk-unity6-lts-samples.git?path=/VarjoSample
```

---

### Unity 6.3 LTS Samples

**Oculus/Meta Quest:**
```
https://github.com/RandyHaylor/theia-sdk-unity6-3-lts-samples.git?path=/OculusSample
```

**HTC VIVE:**
```
https://github.com/RandyHaylor/theia-sdk-unity6-3-lts-samples.git?path=/HTCViveSample
```

**Varjo (Experimental):**
```
https://github.com/RandyHaylor/theia-sdk-unity6-3-lts-samples.git?path=/VarjoSample
```

---

## Support

For issues or questions, please open an issue on GitHub.
