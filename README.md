# C3 Board Lab

An interactive 3D model of the Espressif **ESP32-C3-DevKitM-1** for EECS2021 Lab K (memory-mapped I/O on RISC-V).

**Open it:** https://amirhossein1001.github.io/c3-board-lab/

- Rotate the board, hover parts and pins, and hold the **Boot** button (or press `B`).
- Watch `GPIO_IN_REG` (0x6000403C) and the W1TS / W1TC stores change live.
- Six short lessons: the board, K02 to K05, and why `volatile` matters.

Running code here is simulated. The board model is simplified; pin labels follow Espressif's DevKitM-1 user guide, and register addresses follow ESP-IDF v5.5.6.

The code panels are plain-language outlines, not the lab's sample code.

Not affiliated with or endorsed by Espressif. Made by an EECS2021 TA.

## Feedback

Use the **Feedback** button on the page (left rail). It fills in a GitHub issue for you, or copies your feedback so you can email it to your TA.
