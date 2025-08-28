# Windows 11 Registry Tweaks Collection

A curated collection of Windows 11 registry tweaks organized into three simple categories.

## Repository Structure

### 📁 Windows 11 Requirements Bypass

Essential tweaks to bypass Windows 11 hardware requirements for installation and updates.

**Files:**

-   `BypassTPMandCPU.reg` - Bypass TPM and CPU checks for updates
-   `All-Bypass-Requirements.reg` - Complete bypass package (TPM, CPU, RAM, Secure Boot)

### 📁 Essential Tweaks

**Must-have tweaks** that dramatically improve the Windows 11 experience.

**Files:**

-   `Essential-Tweaks-All.reg` - All essential tweaks in one file
-   `OldContextMenu.reg` - Restore Windows 10 right-click menu
-   `DisableBingStartMenuSearch.reg` - Remove Bing from Start menu search
-   `DisableSearchHighlights.reg` - Disable taskbar search highlights
-   `FasterShutdown.reg` - Reduce shutdown wait time
-   `LastActiveClick.reg` - Taskbar icons open last active window
-   `VerboseStatus.reg` - Show detailed startup/shutdown messages
-   `DisableWidgets.reg` - Remove Windows widgets from taskbar
-   `HideRecommendedSection.reg` - Remove "Recommended" from Start menu

### 📁 Optional Tweaks

**Nice-to-have tweaks** that enhance the experience but aren't essential.

**Files:**

-   `Optional-Tweaks-All.reg` - All optional tweaks in one file
-   `FasterInternetSpeed.reg` - Network performance optimization
-   `DisableSnapLayouts.reg` - Disable snap assist flyout
-   `DisableTeamsAutoStart.reg` - Prevent Teams from auto-starting
-   `DisableCortana.reg` - Disable Cortana (mostly irrelevant now)

## Quick Start Guide

### For New Windows 11 Users:

1. **Start here**: `Essential Tweaks/Essential-Tweaks-All.reg`
2. **If needed**: `Windows 11 Requirements Bypass/BypassTPMandCPU.reg`
3. **Optional**: Browse `Optional Tweaks/` for additional enhancements

### For Hardware Compatibility Issues:

Use `Windows 11 Requirements Bypass/All-Bypass-Requirements.reg` during installation

## Usage Instructions

1. **Download** the desired `.reg` file
2. **Right-click** and select "Merge" or double-click to run
3. **Click "Yes"** when prompted to add to registry
4. **Restart** your computer for changes to take effect

## Safety Information

✅ **Essential Tweaks**: Completely safe, improve daily experience
✅ **Optional Tweaks**: Safe but not necessary for everyone
✅ **Bypass Tweaks**: Required for older hardware, no security impact

## System Requirements

-   Windows 11 (any build)
-   Administrator privileges
-   Basic understanding of registry editing

## Compatibility

All tweaks tested on Windows 11 as of August 2025.

## Disclaimer

Always backup your system before making registry changes. Use at your own risk.
