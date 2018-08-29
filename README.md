# C/C++ Barcode Reader for Raspberry Pi

The samples demonstrate how to use [Dynamsoft Barcode Reader SDK](http://www.dynamsoft.com/Products/Dynamic-Barcode-Reader.aspx) to build C/C++ barcode reader on Raspberry Pi. 

## License
Get the [trial license for Linux](http://www.dynamsoft.com/Downloads/Dynamic-Barcode-Reader-for-Raspberry-Pi-Download.aspx).

## Download
[DBR v6.3](http://www.dynamsoft.com/Downloads/Dynamic-Barcode-Reader-for-Raspberry-Pi-Download.aspx)

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
