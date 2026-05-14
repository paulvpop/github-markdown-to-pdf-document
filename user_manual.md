This user manual describes a method to convert a Github Markdown object to a pdf file using the Markdown Viewer browser extension.

**Step 1:** Go to [this extensions web page for 'Markdown Viewer'][1]

**Step 2:** Click on "Add to Brave" on the top right (it will work in Google Chrome too, but if you're still using Google Chrome, you are not worthy of this user manual).

<img src="https://github.com/user-attachments/assets/687f00ee-ef6d-4e88-b9d2-e16632d5fb4c" alt="markdown-viewer-page" width="800" height="525"> <br>

**Step 3:** Click on 'Add extension' on the pop-up.

<img width="450" height="250" alt="image" src="https://github.com/user-attachments/assets/fda636d7-0ff7-4f9d-a086-e0799fd25dd8" />

You should see the following near the toolbar:

<img width="500" height="250" alt="image" src="https://github.com/user-attachments/assets/2f88bc06-5c97-4963-9cb3-1d3a9fe9ebe7" /> <br>

**Step 4:** Pin the extension to the toolbar

<img width="350" height="350" alt="image" src="https://github.com/user-attachments/assets/8fe6004f-e76d-407d-b7c2-67d36c63a0d0" /> <br>

**Step 5:** Click on the 'Markdown Viewer' on the dropdown menu from the toolbar (as seen above), and click on 'Advanced Options'.

<img width="338" height="376" alt="image" src="https://github.com/user-attachments/assets/55171909-ebee-44c7-9d6e-f97146c0f34e" /> <br>

**Step 6:** On this page, click on 'Allow Access'.

<img width="800" height="208" alt="image" src="https://github.com/user-attachments/assets/baae1ff0-bcee-495e-a0c9-d0b701be1fb8" /> <br>

**Step 7:** On the resulting page, turn on 'Allow access to file URLs'.

<img width="450" height="700" alt="image" src="https://github.com/user-attachments/assets/1616674a-a2ec-437e-89d8-a8700326d01d" />
<img width="450" height="700" alt="image" src="https://github.com/user-attachments/assets/ed8af330-89df-499b-aa10-9ee5de598af9" /> <br><br>

**Step 8:** Go to the page containing github markdown object/file, and click on the 'Raw' option on the top right of the viewer pane.

<img width="1892" height="937" alt="image" src="https://github.com/user-attachments/assets/a06468c5-4219-4bd8-bfb6-1dcd672cc45f" />

It should show a page like this:

<img width="800" height="461" alt="image" src="https://github.com/user-attachments/assets/e75d5a79-d621-4787-8a08-831c06029d90" /> <br>

**Step 9:** Click on the pinned 'Markdown Viewer' extension icon (*m*) on the top right of the toolbar.

<img width="400" height="150" alt="image" src="https://github.com/user-attachments/assets/e5c3760c-c85f-4513-a83f-dae4b24934dd" /> <br>

**Step 10:**  In the resulting page, add the url starting with "https://raw.githubusercontent.com..." from step 8 to the 'Site Access' text box.

<img width="800" height="529" alt="image" src="https://github.com/user-attachments/assets/34328ad3-82ff-4e7c-9a1f-b5b94f221ab2" /> <br>

**Step 11:**  Click 'Allow' on the pop-up.

<img width="400" height="150" alt="image" src="https://github.com/user-attachments/assets/e79f93ad-7021-4737-8c68-81486051c17e" /> <br>

**Step 12:** Go back to the "https://raw.githubusercontent.com/..." page and click on the 'Markdown Viewer' icon again. Select a theme that you prefer to the pdf document.

<img width="250" height="450" alt="image" src="https://github.com/user-attachments/assets/73ce95a4-d415-4bec-a2b5-b1340c8cf081" /> <br>

And keep the width to 'FULL' in case there are wide images.

<img width="250" height="450" alt="image" src="https://github.com/user-attachments/assets/41cc7ff0-8af9-4d60-8680-781134f67f1e" /> <br>

**Step 13:** Similarly, based on your markdown object and requirements, you can select the relevant 'Content' and 'Compiler' options. In the 'Compiler', remove the 'Linkify' option as it will not hyperlinks and only render the full links as links in the document. When you uncheck, the 'Linkify' option, the link text will not show as a hyperlink, but all other hyperlinks including within-document hyperlinks (like section header links) will render correctly.

<img width="382" height="435" alt="image" src="https://github.com/user-attachments/assets/649dfdc8-a535-4af9-8d15-994705560052" /> <br>

**Step 14:** On the page, right click anywhere and select the "Print..." option in this menu (or simply press Ctrl+P).

<img width="370" height="375" alt="image" src="https://github.com/user-attachments/assets/d56fbd6e-ad2b-4c44-963e-2ee3a35447cd" /> <br>

**Step 15:** To export as a pdf, select 'Destination' as "Save as PDF". Adjust the many parameters for the print option. If the markdown document contains images with large height and width, it would be best to keep the 'Layout' as landscape, 'Pages per sheet' as 2, and adjust the 'Scale' until the most proportionate version is visible to you on all the pages. Uncheck the 'Headers and footers' option if you don't want the date and timestamp, as well as the url of the raw markdown on all pages (it looks cleaner without).

<img width="1307" height="852" alt="image" src="https://github.com/user-attachments/assets/35036e6a-730c-419d-b41f-9573fc2ea20f" /> <br>

**Step 16:** Click on 'Save' and then 'Save' to device after renaming if needed.

<img width="1154" height="315" alt="image" src="https://github.com/user-attachments/assets/7035c3bc-19a9-44f7-baab-f544dfa4df88" />

Now the pdf is saved in the folder you selected.

**Troubleshooting:**

If you are using Brave and the content doesn't render in Markdown, then remove the shields for the page (if you know for sure that there are no malicious content on that webpage). The shields can be pulled up as soon as the markldown renders.

<img width="471" height="328" alt="image" src="https://github.com/user-attachments/assets/a44a69fd-17cf-4e52-aea4-a5db8af937c2" />


































[1]: https://chromewebstore.google.com/detail/markdown-viewer/ckkdlimhmcjmikdlpkmbgfkaikojcbjk?pli=1
