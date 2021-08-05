/ *******************************************
/ Zone file for QCon Pro G2 by PeterGabriel
/ *******************************************
/
/ v1.0 - 22.07.2021
/
/ =================================================================
/
/ General Tips:
/
/ NameValue button is used as a Home button.
/ Help displays info regarding Function keys F1-F8
/ Control+Help displays another page of Function keys F1L2-F8L2
/
/ =================================================================
/
/ Buttons are named according to the printed names on the Qcon G2, not on the Reaper overlay,
/ excluding few exceptions like modifier buttons (Control, Alt, Shift)
/
/ The surface is divided into various sections based on the physical location of buttons
/ and each section reflects certain general functionality that is realised, such as,
/ TransportSection, NavigateSection, DisplaySection and so on.
/ E.g., TransportSection contains Play, Record, Stop button etc.
/ DisplaySection is responsible for changing displayed information
/ regardless which layer and mode is active. However, exact behaviour how the information
/ is changed is defined in particular layer/mode/zone. The sections are not explicitly referred
/ in the zone files, but they allow for easier logical mapping regarding button behaviours
/ in different zones (and remembering how they work).
/
/ The surface can operate using different layers/modes (zones). In various zones,
/ buttons in various sections have assigned different actions.
/ (same buttons can and definitely should belong to various zones).
/
/ Layer is more general concept than mode, where certain general functionality is realised.
/ In more detail, layer includes one or more modes (zones) defined across several physical sections
/ and allow for switching between modes.
/ E.g., ViewLayer includes two modes: ViewLayerScrollMode and ViewLayerZoomMode.
/ Note that buttons in some sections do not
/ change its behaviour, so they only have one zone.
/ E.g., transport buttons does not change its behaviour, so there is only created one TransportZone
/ in Transport.zon without any additional layers/modes.
/
/ As certain layer contains several modes, therefore only <name>Layer zone should be included or mapped with GoZone directive
/ and other dependent modes are referred within that zone.
/
/
/ =================================================================
/ Inspired by Luis from Sinisound.
/ https://siniarch.wixsite.com/sinisound/post/qcon-pro-g2-csi
/ Thank you for your great work!
/ =================================================================
