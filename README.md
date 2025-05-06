## Atari ANTIC Displaylist Designer
A web-based tool for designing and visualizing Atari 8-bit ANTIC display lists. Create, edit, and preview display lists with a drag-and-drop interface, generate assembly code, and monitor scan line and byte usage.

**Features**

Interactive List: Add, remove, duplicate, and reorder display list rows (modes, blanks, JVB) with support for LMS, DLI, VSCROLL, and HSCROLL flags.

Visual Preview: Canvas-based visualization of scan lines with color-coded text/graphics modes, DLI, HS and VS flags and overscan indicator zones.

Code Output: Generates assembly code (.byte directives) for the display list.

Summary: Shows total scan lines and byte count.

---

**Usage**

Add rows with the "Add Row" button.

Edit modes, flags, and addresses in the list pane.

Drag rows to reorder (JVB always stays last).

View the visual preview, assembly code, and summary in real-time.

No server needed, this can be run from your filesystem.

No server-side dependencies; runs entirely client-side with Tailwind CSS and Alpine.js via CDNs.

</br>
Feel free to make pull requests.
</br>
</br>
</br>

Author  
Chris Worton, 2025

