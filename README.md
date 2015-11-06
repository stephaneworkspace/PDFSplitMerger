# PDFSplitMerger
Split and merge pdf files. Three functionalities: merge multiple pdfs into one, split single pdf by page and an option to cut each page in half (useful for fixing scanned files).

Uses hummus/podofo for the pdf library and Qt as the GUI. 

hummus

http://pdfhummus.com/

podofo 0.9.3

http://podofo.sourceforge.net/

Qt 5.5

http://www.qt.io/qt-framework/


The master branch uses hummus as the pdf library. Check the podofo branch for implementation using podofo. Podofo was abandoned due to its complexity and difficulty when dealing with splitting without copying the whole document (currently podofo branch's splitted pdf files always have the same size as the original).

