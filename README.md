# Line Following Warehouse Robot Barcode Generator
An app to help create and save barcodes for the [magni-warehouse-line-follower](https://github.com/dylancajigas/magni-warehouse-line-follower) as images to the computer.

## Usage
There are three main windows that this application has: the default window, batch creation, and a graphical interface. 

### Default Window
The default window simply asks for the number of stations in the loop, and the stations to stop at. This window has a preview for the barcode generated. The save button will save this barcode as either a .png or .jpg file at the location specified. The size of the image can also be changed, since more complicated barcodes require more pixels to display correctly.

### Batch Creation
Enter the number of stations and stops on corresponding lines in the text boxes. The size and filetype of the barcode images saved can be changed like in the default window, but there is no preview for what is being generated. 

### Graphical Interface
The graphical interface can be opened from both the default and batch creation windows. It gives a more straightforward and visual way to select which stations to stop at. The stations are separated into a maximum of 5 groups, the details of which can be edited through a settings menu. By clicking on each group, stations can be selected. Clicking the "Add" button will add the selected information to either the default or batch creation window.