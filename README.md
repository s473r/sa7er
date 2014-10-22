
GUIEditor = {
    button = {},
    window = {},
    label = {},
    edit = {}
}
GUIEditor.window[1] = guiCreateWindow(133, 133, 537, 392, "===============[ #TCS Cl4n GUI ]===============", false)
guiWindowSetSizable(GUIEditor.window[1], false)
guiSetProperty(GUIEditor.window[1], "CaptionColour", "FFFD0D0D")

GUIEditor.edit[1] = guiCreateEdit(93, 29, 435, 25, "هايي  ابhfhf hff hf hfhfhf fhf ", false, GUIEditor.window[1])
GUIEditor.button[1] = guiCreateButton(465, 367, 55, 15, "edit", false, GUIEditor.window[1])
guiSetProperty(GUIEditor.button[1], "AlwaysOnTop", "True")
GUIEditor.button[2] = guiCreateButton(10, 60, 116, 27, "information", false, GUIEditor.window[1])
guiSetAlpha(GUIEditor.button[2], 0.90)
guiSetFont(GUIEditor.button[2], "default-bold-small")
GUIEditor.button[3] = guiCreateButton(9, 97, 117, 32, "Rules | القوانين", false, GUIEditor.window[1])
guiSetAlpha(GUIEditor.button[3], 0.90)
guiSetFont(GUIEditor.button[3], "default-bold-small")
GUIEditor.button[4] = guiCreateButton(9, 139, 117, 33, " Cl4n Members         أعضاء الكلان", false, GUIEditor.window[1])
guiSetAlpha(GUIEditor.button[4], 0.90)
guiSetFont(GUIEditor.button[4], "default-bold-small")
GUIEditor.button[5] = guiCreateButton(9, 182, 117, 31, "Spars | التحديات", false, GUIEditor.window[1])
guiSetFont(GUIEditor.button[5], "default-bold-small")
GUIEditor.button[6] = guiCreateButton(10, 359, 81, 23, "X  |   Close", false, GUIEditor.window[1])
guiSetFont(GUIEditor.button[6], "clear-normal")
GUIEditor.edit[2] = guiCreateEdit(126, 60, 394, 304, "", false, GUIEditor.window[1])
GUIEditor.label[1] = guiCreateLabel(24, 33, 92, 27, "Note ==>", false, GUIEditor.window[1])
guiSetFont(GUIEditor.label[1], "clear-normal")
GUIEditor.label[2] = guiCreateLabel(126, 364, 282, 18, "All rights reserved clan TCS Ⓒ 2014 - 2015", false, GUIEditor.window[1])
