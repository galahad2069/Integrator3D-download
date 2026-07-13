# Integrator3D — downloads

Windows 64-bit binaries for **Integrator3D**, a real-time solar-system visualiser and
high-precision numerical integrator, together with **BSPMerge**, its one-click ephemeris builder.

## Download

Get the latest zip from the [**Releases**](../../releases/latest) page, extract the
`Integrator3D` folder anywhere, and run **`Integrator3D.exe`** — or
**`Integrator3D-compatible.exe`** on older CPUs without AVX2. First-run steps are in the
`README.txt` inside the zip (build an ephemeris with BSPMerge, then **Load** it in Integrator3D).

Every release lists a **SHA-256** checksum so you can verify your download.

## Notes

- No installer — just extract and run. Settings save to an `.ini` next to the exe.
- The exes are unsigned, so Windows SmartScreen may warn — click *More info → Run anyway*.
- Requires an OpenGL-capable GPU. An internet connection is only needed for BSPMerge's downloads.

---

*This repository hosts only the compiled binaries. The source is kept private for now and
will be opened once the first round of tester feedback has been folded in.*
