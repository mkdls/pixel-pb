# Pixel Uecapa pb Editor (MD3 Fork)

> [!NOTE]
> This is a modified fork of the original Pixel Uecapa pb Editor, focusing on Material Design 3 interface updates and advanced combination management tools.

## Added Features

* **Batch Generation**: A new tool to generate multiple combinations using 3GPP bandwidth classes (e.g., `b3+b7C+n78C`). It includes settings for max CCs, MIMO, anchors, and dynamic NR band feature index configuration.
* **Clear All**: A button to clear all existing combinations at once.

> [!TIP]
> **Android App Integration**: Added `AndroidBridge` support to directly save `.binarypb` and `.zip` files when used inside an Android WebView wrapper.

## Improvements

* **Interface Redesign**: Applied a Material Design 3 (MD3) visual style with dark and light mode variables.
* **Mobile Layout**: Adjusted the interface for better touch usability, including dynamic input field widths, minimum button sizes, and horizontal scrolling for data tables.
* **Dialog System**: Replaced native browser alerts and prompts with custom MD3 modal dialogs.

> [!IMPORTANT]
> **mmWave Support**: Refined the bandwidth class calculation logic to accurately process carriers that are 200MHz or wider.
