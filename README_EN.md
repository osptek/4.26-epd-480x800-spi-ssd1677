# 4.26" 480×800 E-Paper (EPD) SPI module (SSD1677) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides **sample projects** and reference material for the 4.26-inch e-paper (EPD) module, aimed at evaluation and integration. The sample demonstrates black-and-white and 4-grey image display, partial refresh and text rendering. The panel is GDEQ0426T82 (SSD1677 controller).

## Product overview

| Item | Description |
|:--|:--|
| Module | 4.26-inch **E-Paper (EPD)**, **480×800** resolution (portrait logical; 800×480 native panel) |
| Interface | **SPI** |
| Driver IC | **SSD1677** (GDEQ0426T82 panel) |
| Display modes | Black & white (1bpp) and **4 grey levels (4G)**, with partial refresh |
| Spec ID | **`4.26-epd-480x800-spi-ssd1677`** is the common product designation in documentation |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `docs/` | Adapter-board material and 4-grey waveform table (reference) |
| `examples/` | Sample projects |

### `examples/` layout

| Location | Description |
|:--|:--|
| `examples/` root | GDEQ0426T82 (SSD1677) SPI bring-up sample: B/W and 4-grey image slideshow, partial refresh and text display |

### Sample project paths

| Description | Path |
|:--|:--|
| SSD1677 SPI bringup (B/W + 4-grey + partial refresh) | `examples/esp32s3-4.26-epd-480x800-spi-ssd1677-bringup/` |
