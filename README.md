# C/C++ Barcode Reader for Raspberry Pi

The samples demonstrate how to use Dynamsoft Barcode Reader SDK to build C/C++ barcode reader on Raspberry Pi. The shared library **libDynamsoftBarcodeReader.so** is not publicly available yet. If you are interested in the **barcode SDK for Raspberry Pi**, please contact [support@dynamsoft.com](mailto:support@dynamsoft.com) to get a trial version.

## Getting Started
1. Folder structure:

    ![Raspberry Pi Barcode Reader](http://www.codepool.biz/wp-content/uploads/2016/03/tree.png)

2. Build C/C++ samples:

    ```
    cd samples/c
    make
    ```
3. Read barcode images:

    ```
    ./BarcodeReaderDemo ../../AllSupportedBarcodeTypes.tif
    ```

    ![Raspberry Pi Barcode Reader](http://www.codepool.biz/wp-content/uploads/2016/03/rpi_dbr_result.png)
