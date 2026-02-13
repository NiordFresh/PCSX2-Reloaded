![pcsx2](https://github.com/user-attachments/assets/13f8412a-261d-4209-b33f-87bfa251385a)

# PCSX2-Reloaded
PCSX2 2.0+ fork with Windows 8.1+ support. 

For now only as a proof of concept, based on nightly build v2.3.19, but with potential for higher versions like v2.5...

| OS  | Working? |
| ------------- | ------------- |
| Windows 10 1809+ | Use official PCSX2 builds |
| Windows 10 (1507 - 1809) | ✅  |
| Windows 8.1 (05.2025 - All Official + All S2012 R2 Updates)  | ✅  |
| Windows 8.0 (05.2025 - All Official + All S2012 Updates) | ⚠️* |
| Windows 7 (07.2021 - All Official + Some ESU Updates) | ❌ |

*Windows 8.0 is having issues with DXGI.dll for now... Probably fixable...

Issues:
DX12 is not working on Windows 8.1 
DX11 is not Working on Windows 8.1 (DXGI.dll issue, working on that)
DX11 is crashing on Windows 8.0 (Missing CreateDXGIFactory2 issue, and prob. quite more)
Software/None Rendering is crashing app.
Some games on Windows 8.1 can crash for now.
