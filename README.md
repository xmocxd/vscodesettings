# vscodesettings

## Keyboard Shortcuts

Navigate to File > Preferences > Keyboard Shortcuts.  
Alternatively, use the keyboard shortcut Ctrl+K Ctrl+S (Windows/Linux) or Cmd+K Cmd+S (macOS).

## Edit Settings JSON

CTRL+SHIFT+P - settings JSON

## Install Exts

(Windows)

for /f %i in (extensions.txt) do code --install-extension %i




---- test these settings


{
  // --- UI DECLUTTERING ---
  "workbench.activityBar.location": "hidden", // Hide the left icon bar
  "workbench.statusBar.visible": false,       // Hide the bottom bar
  "editor.minimap.enabled": false,            // Remove the code map on the right
  "breadcrumbs.enabled": false,               // Hide file path at the top
  "workbench.editor.showTabs": "single",      // Show only one tab at a time
  
  // --- PERFORMANCE & PRIVACY ---
  "telemetry.telemetryLevel": "off",          // Disable data collection
  "extensions.autoCheckUpdates": false,       // Stop background update checks
  "editor.hover.enabled": false,              // Disable popups when hovering
  "editor.lightbulb.enabled": "off",          // Remove the "Quick Fix" lightbulb
  "editor.parameterHints.enabled": false      // Stop automatic parameter popups
}
