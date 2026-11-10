# SEG-Y Cropper

Crop SEG-Y volumes in the browser: open one or more volumes, look at inlines,
crosslines and time slices, drag a box (or type inline, crossline and time
ranges), and save cropped SEG-Y files. Everything runs on your own computer;
nothing is uploaded.

**Use it:** open the GitHub Pages address of this repository, or download
`index.html` and open it from your computer (it works offline).

* All files should share one grid; the crop is applied to each file.
* Inline / crossline header bytes are set at the top (defaults 189 / 193).
* Headers are copied from each input; the sample count and start time are
  updated. Samples are copied byte for byte, in the input's own format.
* Made to cut volumes down to a size the web version of the Seismic Facies
  Clustering Tool can handle.

Built for teaching by Dr. April Moreno-Ward and Dr. Heather Bedle, University
of Oklahoma, with the AASPI consortium.

**To cite:** A. Moreno-Ward and H. Bedle, 2026, SEG-Y Cropper (version 1.0)
[DOI to follow].

Licensed CC BY-SA 4.0 (see `LICENSE.txt`). SEG-Y is read and written as
described in the SEG-Y revision 2.0 standard (SEG Technical Standards
Committee, 2017).

**Privacy:** the page records only that it was opened (GoatCounter, via
`assets/count.js`): no cookie, no account, no personal information, and none
of your data. Local copies opened from disk are never counted.
