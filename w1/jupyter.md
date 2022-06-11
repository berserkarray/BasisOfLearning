# Jupyter Notebook Installation

This page contains information and links about installing and using tools across the Jupyter ecosystem. Generally speaking, the documentation of each tool is the place to learn about the best-practices for how to install and use the tool.

Use the following installation steps:

1.Download Anaconda. We recommend downloading Anaconda’s latest Python 3 version (currently Python 3.9).

2.Install the version of Anaconda which you downloaded, following the instructions on the download page.

3.Congratulations, you have installed Jupyter Notebook. To run the notebook type in conda command prompt:

#### jupyter notebook

or directly use anaconda navigator to access it.

# Creating a new Notebook

A new notebook may be created at any time, either from the dashboard, or using the File → New menu option from
within an active notebook. The new notebook is created within the same directory and will open in a new browser tab.
It will also be reflected as a new entry in the notebook list on the dashboard.

When you create a new notebook document, you will be presented with the notebook name, a menu bar, a toolbar
and an empty code cell.

# Structure of Notebook

The notebook consists of a sequence of cells. A cell is a multiline text input field, and its contents can be executed by
using Shift-Enter, or by clicking either the “Play” button the toolbar, or Cell, Run in the menu bar. The execution
behavior of a cell is determined by the cell’s type. There are three types of cells: code cells, markdown cells, and raw
cells. Every cell starts off being a code cell, but its type can be changed by using a drop-down on the toolbar (which
will be “Code”, initially), or via keyboard shortcuts

# Code Cells

A code cell allows you to edit and write new code, with full syntax highlighting and tab completion. The programming
language you use depends on the kernel, and the default kernel (IPython) runs Python code.
When a code cell is executed, code that it contains is sent to the kernel associated with the notebook. The results that
are returned from this computation are then displayed in the notebook as the cell’s output. The output is not limited to
text, with many other possible forms of output are also possible, including matplotlib figures and HTML tables (as
used, for example, in the pandas data analysis package). This is known as IPython’s rich display capability.
