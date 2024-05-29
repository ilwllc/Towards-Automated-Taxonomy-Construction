Project
-------
Towards Automated Taxonomy Construction


Description
-----------
This project contains the files to generate the figures in the Towards Automated Taxonomy Construction blog https://ilwllc.com/2024/05/towards-automated-taxonomy-construction/, which describes a method of generating taxonomies from a series of SQL queries.

It contains the following directories:

  data: includes json files containing data used within Finegan-Dollak, Catherine, et al. "Improving text-to-sql evaluation methodology." arXiv preprint arXiv:1806.09029 (2018) and the SPIDER data set (Yu, Tao, et al. "Spider: A large-scale human-labeled dataset for complex and cross-domain semantic parsing and text-to-sql task." arXiv preprint arXiv:1809.08887 (2018).

  examples: png files generated assuming simple toy taxonomy, used to demonstrate our methodology

  graph_png_files: png files of the taxonomies generated using the methodology described in the blog
taxonomy.ipynb: jupyter notebook that generates the diagrams in the blog


Running the Project
-------------------
Open the taxonomy.ipynb using a jupyter notebook to run the project.  The code is using a Python 3 (ipykernel) kernel.  Depending on computing resources, the notebook may take several hours to run.  However, to cut the run time, a subset of taxonomies can be generated by manipulating the 'selects' list, which contains the select statements for the queries.


Credits
-------
Thanks to Srini Anand for his suggested improvements to the Jupyter notebook.


License
-------
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
