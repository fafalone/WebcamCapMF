# WebcamCapMF
Using MediaFoundation to capture webcam stills

<img width="438" height="570" alt="image" src="https://github.com/user-attachments/assets/1478cf2e-22fc-4055-90be-db5e5a7949fa" />

**New project:** I've added WebcamCaptureEngine.twinproj, which uses the alternative IMFCaptureEngine etc, which makes it easy to implement full recording of video and audio. This version can still take advantage of the processing effects like brightness.

**Project update:** Added options to adjust brightness, contrast, etc, if available, and also zoom, if available.

**Project update:** Video preview now renders to a Direct2D render target.

**Project update:** Fix error when property can be read but not set, fix tab stops/indexes.

**Project update:** Now uses WIC to allow saving as JPG or PNG in addition to BMP. The name picker dialog box for save also implements a customization to add a 'Quality' entry box for JPG.
