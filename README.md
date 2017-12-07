# Predix Design Stencil
This repository contains files with the most current symbols library, stencils, color swatches, and fonts for your Predix UI design project. Stencils are provided in Sketch formats.

The Predix Components Master is a Sketch document that contains Predix component symbols which you can use in any of your Sketch documents. If there are updates to the master file, documents containing instances of the master file will receive a notification to update to the lastest version. This will guarantee you will have the lastest version and any additions to the Sketch documents.
The Predix Design System starter kit is composed of symbols from the Predix Components Master file and layout examples. Please use the starter kit as a way to build stencils for your product and applications.

For a technical overview of Predix UI, and live demos of all of the components included, visit https://predix-ui.com.

**PLEASE NOTE:** The repo for the Starter Kit has moved. All updates and files will be located in this repo moving forward. 

## Adding Libraries
***Sketch Libraries is only available with Sketch 47 and above.***

To start using the Predix Components Master Library, you will need to clone this repository to your local environment and link the library to your file. You can follow [these instructions](https://help.github.com/articles/cloning-a-repository/) to clone this repository in your local environment.

**WARNING:** Do not edit the local copy of the Predix Components Master file. If you are creating symbols, be sure to create symbols from a separate file that links to the library. Any changes to the local copy of the Predix Components Master will need to be discarded when fetching any updates.

To add Predix Components Master as a Library, first open your preference window and go to the Libraries tab. Click on the “Add Library…” button that appears on the bottom right of the preference window, and choose the document from the cloned repository. Once you've added Predix Components Master as a Library, you will now be able to insert its Symbols into any of your documents.

![Selecting a library](/images/sketch-preference.png)

Once you've added Predix Components Master to your Libraries, you can use the symbols to build symbols for your own Libraries or for your local documents. The Predix Components will appear in its own menu item within the symbols option.

![Selecting a Libraries Symbol](/images/insert-symbol.png)

If you are looking for more information about how Libraries work, you can find documentation [here](https://sketchapp.com/docs/libraries/)

## Using the Starter Kit
The Starter Kit will have the components from the Predix Components Master, components that have not been converted to symbols, and sample layouts. Use the Starter Kit to create symbols or pages for your product and applications.

## Integrating the Predix Components Master Library to your Current File
If you've used previous versions of the Starter Kit to build your screens, you will need to replace your symbols with those that are in the Libraries file. [Symbol Swapper](https://github.com/sonburn/symbol-swapper) is a plug-in that will help to streamline this process. Symbol Swapper provides you with a way to select a symbol and replace it with a symbol with the same name.
![Symbol Swapper](/images/symbol-swapper.png)
