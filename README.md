# Trillian4.0 (Astra) multi-language support package
How to use? 
Just copy the Languages ​​folder of this repository and paste it into the installation path of Trillian4.0 (Astra)  

Currently only English and Simplified Chinese supported by Trillian4.0 (Astra) are supported 

You can also fork this repository and modify it based on the original English language of Trillian4.0 (Astra) that comes with this repository. Replace the XML, DTD and txt in the Languages\en folder with the language of your region 

Note: When dealing with "language type=" attributes in any context, you should always use the English name of the language. For example:

- 简体中文 → Chinese(Simplified)
- 日本語 → Japanese
- Español → Spanish
- Français → French
- Deutsch → German

Full translations would follow this pattern:
- in xml
#<language type="Chinese(Simplified)">
- in dtd file
#<!-- Chinese(Simplified) Language Pack for Skins -->
