Various shell scripts available for download

pdfrename - will change all .pdf files in a directory into ./PDF/Author-Title-Date.pdf
            based on the information from pdfinfo. Spaces are removed from Author.
            The characters ':&/,! and space are removed or replaced in Title.
            Date is in the YYYMMDD (20210909) format. A ./.BACKUP/ directory is created
            with the original files.

            if the command 'pdfrename no' is issued no author name is used.
