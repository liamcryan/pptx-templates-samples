To run the examples, you must have Python 3.6 or higher, then install the pptx-templater package::

    %pip install git+https://github.com/liamcryan/pptx-templater.git

Using pptx-template
===================
We can template text, tables and chart when creating one PowerPoint at a time use pptx_template.

Text Templating
---------------
Before running the command below, take a look at the template.pptx & model.json files.  The out.pptx will be overridden.

::

    %pptx_template --template text-template/template.pptx --model text-template/model.json --out text-template/out.pptx

Table Templating
----------------
Before running the command below, take a look at the template.pptx & model.json files.  The out.pptx will be overridden.

::

    %pptx_template --template table-template/template.pptx --model table-template/model.json --out table-template/out.pptx

Chart Templating
----------------
Before running the command below, take a look at the template.pptx & model.json files.  The out.pptx will be overridden.

::

    % pptx_template --template chart-template/template.pptx --model chart-template/model.json --out chart-template/out.pptx


Using pptx-templater
====================

When creating multiple PowerPoint files at a time, we want to use pptx-templater.


PPTX Templating
---------------
Before running the command below, take a look at the template.pptx & model.json files.  The out.pptx files will be overridden.

::

    % pptx-templater --template pptx-templater/template.pptx --model-template pptx-templater/model.json --out pptx-templater/out.pptx --data pptx-templater/data.csv