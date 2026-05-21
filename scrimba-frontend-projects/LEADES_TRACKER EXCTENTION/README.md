# 🚀 Chrome Leads Tracker Extension

A lightweight and efficient Google Chrome extension designed to help you quickly save and manage URLs or text leads. Built entirely with Vanilla JavaScript, this project demonstrates direct interaction with the Chrome Tabs API and browser local storage.

## 📸 Interface Preview
<img width="1918" height="916" alt="Capture d&#39;écran 2026-05-02 031555" src="https://github.com/user-attachments/assets/c3d7f65e-c52a-406f-9c25-9c8599085dba" />

## ✨ Core Features

*   **Save Current Tab:** Instantly grab and save the URL of the currently active Chrome tab with a single click using the Chrome Extensions API.
*   **Manual Input:** A dedicated text field to manually paste and save custom links or notes.
*   **Persistent Storage:** All leads are saved locally in the browser using `localStorage`, ensuring your data remains intact even if you close the tab or restart the browser.
*   **Safe Deletion:** Features a "Delete All" button that requires a double-click (`dblclick` event) to clear the storage, preventing accidental data loss.
*   **Clickable Links:** Dynamically renders the saved leads as a clean, unordered list of clickable anchor tags (`<a>`) that open in a new tab.

