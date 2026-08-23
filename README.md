# LWJGL3_Consolidated_SDK

An unofficial, consolidated distribution of the Lightweight Java Game Library (LWJGL 3). 
This package provides a clean, pre-bundled Developer Kit (SDK) for Windows and Linux 
across multiple hardware architectures (x64, ARM64, RISC-V, and PPC64le).

## Package Structure
Inside the distribution ZIP archive, you will find a clean, modular layout:
* **`LICENSE`** – Main, high-level MIT license governing ONLY this custom distribution layout and configuration scripts.
*  **`Detailed_Licenses (DOC / TXT)`** – In-depth legal documentation containing the original "All Rights Reserved" and proprietary/open-source licenses for all third-party components (LWJGL 3, GLFW, Khronos, etc.).
*  **`jar/` (.jar)** – A single, consolidated Java archive bundling all core class modules (GLFW, OpenGL, OpenAL Soft, OpenCL, STB, TinyFD).
*  **`native/` (.dll / .so)** – Raw, uncompressed native binaries organized by platform and hardware architecture for direct IDE linking.
